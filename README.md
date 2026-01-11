# How to build
## Set up environment:
1. Install Visual Studio (tested with VS2026)
2. Download and extract FASTBuild, and include the folder to PATH.
3. Install and bootstrap vcpkg according to step 1 in this guide: https://learn.microsoft.com/en-gb/vcpkg/get_started/get-started?pivots=shell-cmd#1---set-up-vcpkg
4. Set the `VCPKG_ROOT_LOCAL` environment variable to the vcpkg root directory (the `VCPKG_ROOT` can't be used since it will be overwritten in step 1 of the **Generate and build** section, and the VS2026 version of vcpkg is not compatible with VS2026 at the moment...)

## Generate and build
1. Start the "x64 Native Tools Command Prompt for VS"
2. Navigate to this directory.
3. Run `cmake --example-debug`.
4. Navigate to the `build` directory.
5. Run `cmake --build`
