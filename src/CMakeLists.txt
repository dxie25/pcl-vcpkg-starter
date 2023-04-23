# Hello World target
add_executable(hello_world hello_world_main.cpp)
target_include_directories(hello_world
    PRIVATE ${PCL_INCLUDE_DIRS})
target_link_libraries(hello_world
    ${PCL_LIBRARIES})
target_compile_definitions(hello_world
    PRIVATE ${PCL_DEFINITIONS})

# PCL test target
add_executable(hello_pcl pcl_main.cpp)
target_include_directories(hello_pcl
    PRIVATE ${PCL_INCLUDE_DIRS})
target_link_libraries(hello_pcl
    ${PCL_LIBRARIES})
target_compile_definitions(hello_pcl
    PRIVATE ${PCL_DEFINITIONS})
