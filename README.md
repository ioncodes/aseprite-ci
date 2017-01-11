# aseprite-ci
Build configurations to compile Aseprite via a GitLab CI Runner on Windows.

# Prerequisites
1. Visual Studio 2015 Installed
2. CMake installed and in PATH
3. Ninja.exe in the bin folder of the CMake installation or in the PATH variable

# Setup
1. Put the batch file somewhere and add it to the PATH
2. Add the YAML to the aseprite project
3. Push to GitLab
4. It will build
