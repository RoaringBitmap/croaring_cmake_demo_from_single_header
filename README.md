# croaring_cmake_demo_from_single_header
![Ubuntu 20.04 CI (GCC 9)](https://github.com/RoaringBitmap/croaring_cmake_demo_from_single_header/workflows/Ubuntu%2020.04%20CI%20(GCC%209)/badge.svg)
![Ubuntu 18.04 CI (GCC 7)](https://github.com/RoaringBitmap/croaring_cmake_demo_from_single_header/workflows/Ubuntu%2018.04%20CI%20(GCC%207)/badge.svg)
![MinGW64-CI](https://github.com/RoaringBitmap/croaring_cmake_demo_from_single_header/workflows/MinGW64-CI/badge.svg)
![MSYS2-CI](https://github.com/RoaringBitmap/croaring_cmake_demo_from_single_header/workflows/MSYS2-CI/badge.svg)
![MinGW32-CI](https://github.com/RoaringBitmap/croaring_cmake_demo_from_single_header/workflows/MinGW32-CI/badge.svg)
![VS16-CI](https://github.com/RoaringBitmap/croaring_cmake_demo_from_single_header/workflows/VS16-CI/badge.svg)

Really simple CMake demo using CRoaring's single header files.

If you have a recent version of CMake (3.15 or better) under linux, macOS or freeBSD,  you can simply
go in the directory and type the following commands:

```
cmake -B build .
cmake --build build
./build/src/test
./build/src/testcpp
```

If you are using Visual Studio, the instructions are nearly the same:


```
cmake -B build .
cmake --build build --config Release
./build/src/Release/test
./build/src/Release/testcpp
```
