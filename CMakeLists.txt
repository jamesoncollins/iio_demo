cmake_minimum_required(VERSION 2.6)
project(iio_demo)

add_custom_target(iio_demo ALL COMMAND make WORKING_DIRECTORY ${CMAKE_CURRENT_SOURCE_DIR}/projects/iio_demo)

#install( TARGETS iio_demo DESTINATION bin )

#set(CMAKE_BUILD_TYPE Debug)
#set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -O0 -O0 -g3  -ggdb")
#set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -O0 -O0 -g3  -ggdb")
