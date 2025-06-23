cmake_minimum_required(VERSION 3.13)
project(HintsToPot)

add_executable(hintsToPot
    HintsToPot.cpp)

target_link_libraries(hintsToPot PRIVATE boost_headeronly Boost::filesystem Boost::system)

#encoding_check(HintsToPot)



