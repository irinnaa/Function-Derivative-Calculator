# Function Derivative Calculator

A C/C++ application that parses mathematical expressions, generates abstract syntax trees, and calculates both the first and second derivatives of the given function. Built with a graphical user interface using the WinBGIm graphics library.

## Features
* **Expression Parsing**: Converts standard mathematical infix notation to postfix.
* **Derivation**: Computes the first and second derivatives of functions.
* **Tree Visualization**: Graphically renders the abstract syntax tree (AST) for the original function and its derivatives.
* **Expression Simplification**: Automatically simplifies the resulting derivative expressions (e.g., removing `* 1` or `+ 0`).
* **Multi-language Support**: The GUI supports English, Romanian, Spanish, and French.

## Prerequisites
To run or compile this project, you will need:
* **Code::Blocks IDE** (or a similar C++ compiler environment).
* **WinBGIm Library (`<graphics.h>`)**: This project relies on the BGI graphics library. You must have this configured in your compiler to build the project successfully.

## How to Run
1. Clone this repository to your local machine.
2. Open the `E3_Derivare_Grigorciuc Irina_Romaniuc Tudor.cbp` file in Code::Blocks.
3. Ensure your compiler is linked to the WinBGIm library.
4. Click **Build and Run**.
5. Ensure all `.txt` language files and `.bmp` flag images are located in the same directory as the generated executable.

##  Authors
* Grigorciuc Irina
* Romaniuc Tudor
