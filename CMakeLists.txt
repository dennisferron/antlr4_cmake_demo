cmake_minimum_required(VERSION 3.17)
project(antlr4_demo)

set(CMAKE_CXX_STANDARD 20)

list(APPEND CMAKE_MODULE_PATH
        ${CMAKE_SOURCE_DIR}/cmake
        )

add_subdirectory(sqlite3)
add_subdirectory(antlr4-runtime)
add_subdirectory(transpiler)
add_subdirectory(basekit)
add_subdirectory(user_prog)
add_subdirectory(tests)
