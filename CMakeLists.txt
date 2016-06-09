cmake_minimum_required(VERSION 3.5)

project(labyrinth)

add_executable(labyrinth src/labyrinth.cxx
                         src/board.cxx
                         src/brain.cxx
                         src/bot.cxx)
