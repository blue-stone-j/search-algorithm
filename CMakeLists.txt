cmake_minimum_required(VERSION 3.16.3)
project(search_algorithm)

set(CMAKE_BUILD_TYPE "Release")
add_compile_options(-std=c++17)
set(CMAKE_CXX_FLAGS_RELEASE "-O3")

# set(TARGET_LIBRARIES "")
# list(APPEND TARGET_LIBRARIES ${OpenCV_LIBRARIES})
add_executable(backtracking backtracking/backtracking.cpp)

# target_link_libraries(backtracking ${TARGET_LIBRARIES})
