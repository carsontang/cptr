# cptr - Learn how to use CMake

This small repo shows how to structure a C project
with the CMake build system.

## Instructions

### Regular Installation
`mkdir build && cd build && cmake .. && make && make install`
This will install the executable in /usr/local/bin on a Mac OS X.

### Custom Location Installation
`mkdir build && cd build && cmake .. -DCMAKE_INSTALL_PREFIX=../_install && make && make install`

## Resources
* [CMake by Example](https://mirkokiefer.com/cmake-by-example-f95eb47d45b1)
* [CLion's Quick CMake Tutorial](https://www.jetbrains.com/help/clion/quick-cmake-tutorial.html)
* [CMake Guide](https://rix0r.nl/blog/2015/08/13/cmake-guide/)
