# missing_noetic_pkgs

missing packages of ROS Noetic

## Usage

```sh
git clone git@github.com:kenji-miyake/missing_noetic_pkgs.git
cd missing_noetic_pkgs
mkdir -p src
vcs import src < workspace.repos
colcon build --symlink-install --cmake-args -DCMAKE_BUILD_TYPE=Release --continue-on-error
```
