cmake_minimum_required(VERSION 3.10)
project (compute_pi)
add_executable(compute_pi compute_pi.cpp)
set_property(TARGET compute_pi PROPERTY CXX_STANDARD 17)
