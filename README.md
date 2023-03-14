```bash
echo "deb [trusted=yes] https://raw.githubusercontent.com/moveit/moveit2_packages/jammy-rolling/ ./" | sudo tee /etc/apt/sources.list.d/moveit_moveit2_packages.list
echo "yaml https://raw.githubusercontent.com/moveit/moveit2_packages/jammy-rolling/local.yaml rolling" | sudo tee /etc/ros/rosdep/sources.list.d/1-moveit_moveit2_packages.list
```
