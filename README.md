# croaring_cmake_demo_from_single_header
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
