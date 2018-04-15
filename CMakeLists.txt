project(ArduinoSTL CXX C)

add_library(ArduinoSTL STATIC
        src/del_op.cpp
        src/new_op.cpp
        src/func_exception.cpp
)

target_include_directories(ArduinoSTL PUBLIC src)
