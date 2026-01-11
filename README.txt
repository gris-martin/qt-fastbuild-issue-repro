How to build:
1. Set up environment:
    a. Install Visual Studio (tested with VS2026)
    b. Download and extract FASTBuild, and include the folder to PATH.
    c. Install and bootstrap vcpkg according to step 1 in this guide: https://learn.microsoft.com/en-gb/vcpkg/get_started/get-started?pivots=shell-cmd#1---set-up-vcpkg
    d. Set the `VCPKG_ROOT_LOCAL` environment variable to the vcpkg root directory (the `VCPKG_ROOT` can't be used since it will be overwritten in step 2a, and the VS2026 version of vcpkg is not compatible with VS2026 at the moment...)

2. Generate and build:
    a. Start the "x64 Native Tools Command Prompt for VS"
    b. Navigate to this directory.
    c. Run `cmake --example-debug`.
    d. Navigate to the `build` directory.
    e. Run `cmake --build`
