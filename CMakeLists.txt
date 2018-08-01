set(header_files
    ${CMAKE_CURRENT_SOURCE_DIR}/fff.h)

add_library(fff INTERFACE)

target_sources(fff INTERFACE ${header_files})

target_include_directories(fff INTERFACE ${CMAKE_CURRENT_SOURCE_DIR})
