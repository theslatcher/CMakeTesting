project(Utils)

set(UTILS_SOURCE_FILES "Math/Vector4.h" "IO/File.h" "IO/File.cpp")

add_library(Utils STATIC ${UTILS_SOURCE_FILES})

#target_include_directories(Utils PUBLIC ${CMAKE_CURRENT_SOURCE_DIR} ${CMAKE_CURRENT_SOURCE_DIR}/Math)
target_include_directories(Utils PUBLIC ${ENGINE_INCLUDES})