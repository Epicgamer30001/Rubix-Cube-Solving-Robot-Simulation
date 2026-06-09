cmake_minimum_required(VERSION 3.8)
project(rubix_cube)

find_package(ament_cmake REQUIRED)

install(DIRECTORY meshes launch
  DESTINATION share/${PROJECT_NAME}
)

install(FILES rubix.urdf
  DESTINATION share/${PROJECT_NAME}
)

ament_package()
