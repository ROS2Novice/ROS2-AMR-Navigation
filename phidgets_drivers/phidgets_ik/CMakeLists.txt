cmake_minimum_required(VERSION 3.5)
project(phidgets_ik)

find_package(ament_cmake REQUIRED)

install(DIRECTORY launch
  DESTINATION share/${PROJECT_NAME}
)

ament_package()
