cmake_minimum_required (VERSION 3.8)

project(outExe)

add_executable (outExe "Main.cpp" )

target_link_libraries(outExe library Utils)

target_include_directories(outExe PUBLIC ${CMAKE_CURRENT_SOURCE_DIR}/../3rdParty ${CMAKE_CURRENT_SOURCE_DIR}/../Utils ${CMAKE_CURRENT_SOURCE_DIR}/../Utils/Math)