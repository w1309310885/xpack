
set(CURRENT_PROJECT_NAME xpack)
add_library(${CURRENT_PROJECT_NAME} INTERFACE)
target_include_directories(${CURRENT_PROJECT_NAME} INTERFACE ${CMAKE_CURRENT_SOURCE_DIR}/..)
target_compile_features(${CURRENT_PROJECT_NAME} INTERFACE cxx_std_11)
