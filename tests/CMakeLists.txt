include(GoogleTest)

include_directories(${CMAKE_SOURCE_DIR}/src/)

add_subdirectory(unit)
add_subdirectory(integration)
