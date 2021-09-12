cmake_minimum_required(VERSION 3.8)

aux_source_directory(./ SRC)
add_executable(Chess ${SRC})

target_link_libraries(Chess PRIVATE sfml-system sfml-graphics sfml-window)