cmake_minimum_required(VERSION 3.4.0)
project(tiago_description_calibration)

find_package(ament_cmake_auto REQUIRED)

# PAL Robotics stricter build flags, other developers should not worry about this
find_package(ament_cmake_pal QUIET)

ament_auto_package(INSTALL_TO_SHARE urdf)
