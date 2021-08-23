# OOP_arcade_2019

This is a project made in C++ that simulates an arcade. You can swap through different graphical libs using the key 'P', and you can swap between games using the key 'O'.

The goal of this project was to handle different dynamic libraries and to be able to swap them at run-time flawlessly.

Some crashes may occur.

## How to compile :
This project only compiles on Unix systems and require these packages : `libncurses5-dev`, `libsdl2-dev`, `libsdl2-image-dev`, `libsdl2-ttf-dev`, `libsfml-dev`.
After installing the packages, you can now compile with : `make`

## Usage:
`./arcade ./lib/lib_of_your_choice.so`
(don't try to write 'lib/lib_of_your_choice' and write './lib/lib_of_your_choice' or it won't work !)
