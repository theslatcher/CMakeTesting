project(3pLib)

set(3PLIB_SOURCE_FILES "library.h" "library.cpp")

add_library(3pLib STATIC ${3PLIB_SOURCE_FILES})