# Setup Instructions for Building and Running the Codebase

## Prerequisites

Ensure you have the following tools and libraries installed:

- **C++ Compiler**: Clang (recommended for macOS) or GCC.
- **Make**: For building the project.
- **macOS**: macOS SDK and Xcode.
- **SDL Port**: `libsdl2`.
- **Windows**: WSL (Windows Subsystem for Linux).

## Environment Setup

### Windows (Using WSL)

1. **Install WSL**:
   - Follow the instructions on the [Microsoft WSL documentation](https://docs.microsoft.com/en-us/windows/wsl/install) to install WSL and a Linux distribution (e.g., Ubuntu).

2. **Install Development Tools**:
   - Open your WSL terminal and run:
     ```bash
     sudo apt update
     sudo apt install build-essential libsdl2-dev
     ```

3. **Build the Project**:
   - Navigate to your project directory in the WSL terminal.
   - Run the following command:
     ```bash
     make
     ```

### macOS

1. **Install Required Tools**:
   - Ensure Xcode and the macOS SDK are installed.
   - Install `libsdl2` using Homebrew:
     ```shell
     brew install sdl2
     ```

2. **Build the Project**:
   - Open a terminal in the project directory.
   - Run the following command:
     ```shell
     make
     ```

### Linux

1. **Install Required Tools**:
   - Install GCC or Clang, and `make`.
   - Install `libsdl2` using your package manager.

2. **Build the Project**:
   - Open a terminal in the project directory.
   - Run the following command:
     ```shell
     make
     ```

## Running the Application

After building, you can run the application using the generated executable. The location of the executable will depend on your platform and configuration.

## Additional Notes

- Ensure all required tools and libraries are in your `%PATH%` and `%lib%` on Windows.
- For more detailed instructions, refer to the `build-faq.md` and `README.md` files in the codebase. 