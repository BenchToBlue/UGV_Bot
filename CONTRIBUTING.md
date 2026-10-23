# Contributing to BenchToBlue UGV_Bot

Thank you for contributing to the **UGV_Bot** project! To maintain code quality, maintain ROS 2 package stability, and prevent breaking changes on the `main` branch, all team members must adhere to these contribution guidelines.

---

## 1. Repository & Package Structure

All team ROS 2 packages must be organized within the `src/` directory at the root of the repository:

```text
UGV_Bot/
├── README.md               # Project overview and setup guide
├── CONTRIBUTING.md         # Team contribution guidelines
├── .gitignore              # Ignores build, install, and cache files
└── src/                    # All ROS 2 packages reside here
    ├── ugv_description/    # URDF/Xacro models, Gazebo Fortress plugins, launch scripts
    ├── ugv_firmware/       # ESP32 micro-ROS firmware & motor control
    ├── ugv_navigation/     # SLAM Toolbox & Nav2 configurations
    └── <your_package>/     # New ROS 2 packages
