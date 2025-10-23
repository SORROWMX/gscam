```bash
echo "deb [trusted=yes] https://raw.githubusercontent.com/SORROWMX/gscam/focal-noetic-arm64/ ./" | sudo tee /etc/apt/sources.list.d/SORROWMX_gscam-focal-noetic-arm64.list
echo "yaml https://github.com/SORROWMX/gscam/raw/focal-noetic-arm64/local.yaml noetic" | sudo tee /etc/ros/rosdep/sources.list.d/1-SORROWMX_gscam-focal-noetic-arm64.list
```
