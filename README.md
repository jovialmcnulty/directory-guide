# directory-guide

This repository serves as a layout guide for installing packages on the jen machine, allowing us stay organized with consistent structure.

 As of the writing of this README, the following structure is observed (using `tree -L 3 ~/`)

```
.
├── code
│   ├── directory-guide
│   └── ros-setup
│       ├── README.md
│       ├── ros-setup.bash
│       └── ros-setup.zsh
├── Desktop
├── Documents
├── Downloads
├── examples.desktop
├── Music
├── Pictures
├── Public
├── ros_ws
│   ├── build
│   │   ├── catkin
│   │   ├── catkin_generated
│   │   ├── CATKIN_IGNORE
│   │   ├── catkin_make.cache
│   │   ├── CMakeCache.txt
│   │   ├── CMakeFiles
│   │   ├── cmake_install.cmake
│   │   ├── CTestTestfile.cmake
│   │   ├── gtest
│   │   ├── Makefile
│   │   ├── test_results
│   │   ├── universal_robot
│   │   └── ur_modern_driver
│   ├── devel
│   │   ├── env.sh
│   │   ├── include
│   │   ├── lib
│   │   ├── setup.bash
│   │   ├── setup.sh
│   │   ├── _setup_util.py
│   │   ├── setup.zsh
│   │   └── share
│   └── src
│       ├── CMakeLists.txt -> /opt/ros/kinetic/share/catkin/cmake/toplevel.cmake
│       ├── universal_robot
│       └── ur_modern_driver
├── Templates
└── Videos
```

## General notes

- ROS packages can be cloned in: `~/ros_ws/src/`.
- Custom installed/built packages should be placed in: `/opt/` (not shown)
- Cloned projects for testing purposes can be placed in: `~/code/`

Feel free to push/open issues for suggestions. 
