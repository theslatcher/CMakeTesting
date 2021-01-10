cmake_minimum_required (VERSION 3.8)

project ("CMakeTest")

#

set(ENGINE_INCLUDES ${CMAKE_CURRENT_SOURCE_DIR}/Utils ${CMAKE_CURRENT_SOURCE_DIR}/Utils/Math)

#

add_subdirectory ("3rdParty")
add_subdirectory ("Utils")
add_subdirectory ("App")