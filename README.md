# smart-cache-cpp
Smart-cache: Pre-fetching in Distributed Caching (C++)

## Building the Project
### Requirements
- A compiler with good C++14 support (gcc >= 5.4.0+ is recommended)
- CMake >= 3.10.0

### Building
After cloning the project, create a build directory:
```
mkdir -p build && cd build
```

run CMake with relevant configuration:
```
cmake ..
```

Build with good parallelism:
```
make -j$(nproc)
```
