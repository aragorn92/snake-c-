cmake_minimum_required(VERSION 2.8)

file(GLOB snake_SRC
     "*.h"
     "*.cpp"
)

add_executable(snake ${snake_SRC})
