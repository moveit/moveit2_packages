```bash
echo "deb [trusted=yes] https://github.com/moveit/moveit2_packages/raw/jammy-rolling/ ./" | sudo tee /etc/apt/sources.list.d/moveit_moveit2_packages.list
echo "yaml https://github.com/moveit/moveit2_packages/raw/jammy-rolling/local.yaml rolling" | sudo tee /etc/ros/rosdep/sources.list.d/1-moveit_moveit2_packages.list
```
