# Project README

## Overview
- This project demonstrates the use of smart pointers in a C program, specifically shared and unique pointers. The code is designed to be platform-independent using conditional compilation.

## Features
- Shared Pointer (SharedPointer)
- Unique Pointer (UniquePointer)

## Project Structure
- `build/`: Contains executable files produced by compiling `Main.c`.
- `src/`: Contains the source code for the project.
  - `Main.c`: The entry point of the program, demonstrating the usage of shared and unique pointers.

### Prerequisites
- C/C++ Compiler and Debugger (GCC, Clang)
- Make utility

## Build & Run
To build and run the project, follow these steps:

1. **Navigate to the Project Directory:**
   ```sh
   cd /path/to/project
   ```

2. **Build for Linux:**
   ```sh
   make -f Makefile.linux all
   ```

3. **Build for Windows (using GCC):**
   ```sh
   make -f Makefile.windows all
   ```

4. **Build for Wine:**
   ```sh
   make -f Makefile.wine all
   ```

5. **Build for WebAssembly:**
   ```sh
   make -f Makefile.web all
   ```

6. **Run the Executable:**
   - After building, you can run the executable using:
     ```sh
     make -f Makefile.(os) exe
     ```

7. **Clean and Rebuild (Linux):**
   ```sh
   make -f Makefile.linux clean
   make -f Makefile.linux all
   ```

8. **Clean and Rebuild (Windows):**
   ```sh
   make -f Makefile.windows clean
   make -f Makefile.windows all
   ```

9. **Clean and Rebuild (Wine):**
   ```sh
   make -f Makefile.wine clean
   make -f Makefile.wine all
   ```

10. **Clean and Rebuild (WebAssembly):**
    ```sh
    make -f Makefile.web clean
    make -f Makefile.web all
    ```

These steps ensure that you can build the project for different platforms and run the executable as needed.