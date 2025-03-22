# opencv-template

## Overview

This project is a template for setting up a basic C++ project using OpenCV. It uses CMake for building, vcpkg for package management.

## Windows Requirements

- **CMake**: Version 3.12 or higher ([Install Link](https://cmake.org/download/))
- **Ninja**: On Windows, it is included with Visual Studio 2022
- **vcpkg**: Have it available using `VCPKG_ROOT` environment variable ([Tutorial for Windows](https://learn.microsoft.com/en-us/vcpkg/get_started/get-started?pivots=shell-powershell))
- Any C++ compiler with C++20 support (Visual Studio Installer -> Modify -> Desktop Development witg C++)

## MAC Requirements

- **Homebrew**: Install it if it is not already installed, and make sure to add it to your path. (The required commands can be found at the end of the installation.)

  ```sh
  /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
  ```

- **CMake and Compiler**: We need a C compiler to run our project.

  ```sh
  brew install cmake ninja llvm
  ```

## Build and run the project

### Mac

For the Mac users, we recommend using Visual Studio Code.

First, we have to install some required extensions.

- CMake Tools (by Microsoft)
- C/C++ (by Microsoft)

Then:

1. Open the project folder in Visual Studio Code
2. Cmd + Shift + P -> CMake: Select a Kit -> And select: /usr/bin/clang
3. Cmd + Shift + P -> CMake: Configure
4. Cmd + Shift + P -> CMake: CMake: Build
5. Cmd + Shift + P -> CMake: Run without Debugging

That’s it! 🎉 Your CMake project is now set up, built, and running on macOS in VS Code. 🚀

### Windows

For Windows users, we recommend to use Visual Studio 2022

1. Open the project folder in Visual Studio
2. Wait for the build then Run
