# Visual Studio C++ Try Out Development Containers

This project is derived from a VS Code focused Try Development Container repo for C++. It was changed to use a Visual Studio CMake project as the base example instead of a simpler Hello World without CMake. The instructions below are also focused on just Visual Studio as opposed to Codespaces and VS Code.

A **development container** is a running [Docker](https://www.docker.com) container with a well-defined tool/runtime stack and its prerequisites. You can try out development containers with **[GitHub Codespaces](https://github.com/features/codespaces)** or **[Visual Studio Code Remote - Containers](https://aka.ms/vscode-remote/containers)**.

## Setting up the development container

### Visual Studio - Dev Containers

If you already have [Visual Studio 2022 17.4 Preview 2](https://visualstudio.microsoft.com/vs/preview/) with the Linux workload and Docker installed, you can clone the source code and open the folder in Visual Studio and get going.

[Dev Containers for C++ in Visual Studio](https://devblogs.microsoft.com/cppblog/dev-containers-for-c-in-visual-studio/) has a full write up of the experience.

1. If this is your first time using a development container, please ensure your system meets the pre-reqs (i.e. have Docker installed) in the [getting started steps](https://aka.ms/vscode-remote/containers/getting-started).


## Things to try

Once you have this sample opened, you'll be able to work with it like you would locally.

Some things to try:

1. **Edit:**
   - Open `main.cpp`
   - Try adding some code and check out the language features.
1. **Terminal:** Press <kbd>ctrl</kbd>+<kbd>shift</kbd>+<kbd>\`</kbd> and type `uname` and other Linux commands from the terminal window.
1. **Build, Run, and Debug:**
   - Open `MyCppApp.cpp`
   - Add a breakpoint (e.g. on line 10).
   - Press <kbd>F5</kbd> to launch the app in the container.
   - Once the breakpoint is hit, try hovering over variables, examining locals, and more.

## License

Copyright © Microsoft Corporation All rights reserved.<br />
Licensed under the MIT License. See LICENSE in the project root for license information.
