```bash
echo "deb [trusted=yes] https://github.com/moveit/moveit2_packages/raw/jammy-humble/ ./" | sudo tee /etc/apt/sources.list.d/moveit_moveit2_packages.list
echo "yaml https://github.com/moveit/moveit2_packages/raw/jammy-humble/local.yaml humble" | sudo tee /etc/ros/rosdep/sources.list.d/1-moveit_moveit2_packages.list
```
