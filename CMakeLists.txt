cmake_minimum_required (VERSION 3.8)

project(Chess)

set(BUILD_SHARED_LIBS FALSE)
set(SFML_BUILD_NETWORK FALSE)
set(SFML_BUILD_AUDIO FALSE)
set(SFML_BUILD_DOC FALSE)
set(SFML_BUILD_EXAMPLES FALSE)


set(SFML_BUILD_SYSTEM TRUE)
set(SFML_BUILD_GRAPHICS TRUE)
set(SFML_BUILD_WINDOW TRUE)

add_subdirectory(./third_party/SFML)

add_subdirectory(Chess)
