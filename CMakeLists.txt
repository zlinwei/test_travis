cmake_minimum_required(VERSION 3.12)
project(test_travis_ci)

set(CMAKE_CXX_STANDARD 17)

add_executable(test_travis_ci main.cpp)

add_executable(test_unit test_unit.cpp)

enable_testing()
add_test(AllUnitTest test_unit)