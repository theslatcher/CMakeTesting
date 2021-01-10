cmake_minimum_required (VERSION 3.8)

add_executable (CMakeTest "Main.cpp" )

target_link_libraries(CMakeTest library)

target_include_directories(CMakeTest PUBLIC ${CMAKE_CURRENT_SOURCE_DIR}/../3rdParty ${CMAKE_CURRENT_SOURCE_DIR}/../Utils ${CMAKE_CURRENT_SOURCE_DIR}/../Utils/Math)