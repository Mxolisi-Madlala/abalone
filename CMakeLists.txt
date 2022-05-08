cmake_minimum_required(VERSION 3.10)
project(abalone)

link_directories(-L/usr/ -L/lib -L/usr/lib -L/etc/lib)
link_libraries(-lstdc++)

add_executable(main main.cpp board.h board.cpp cell.h cell.cpp)