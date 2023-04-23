# Point Cloud Library with VCPKG

This repository contains a starter configuration for setting up a CMake project with the [Point Cloud Library](https://pointclouds.org/).

## Build Instructions

Detailed build instructions are located in [docs/BUILD.md](./docs/BUILD.md).

### Quickstart

> Make sure you have [Git](https://git-scm.com), [CMake](https://cmake.org), and [vcpkg](https://vcpkg.io) installed.

```sh
git clone https://github.com/dxie25/pcl-vcpkg-starter.git
cd pcl-vcpkg-starter
cmake -S . -B build -DCMAKE_TOOLCHAIN_FILE=<path-to-vcpkg-root>/scripts/buildsystems/vcpkg.cmake
cmake --build build
```

## License

This repository is licensed under the BSD-3-Clause license.

Third-party libraries have their own licenses. See [docs/EXTERNAL_LIBRARIES.md](./docs/EXTERNAL_LIBRARIES.md).
