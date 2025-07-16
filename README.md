# Overview of A Bitset Library

# Dependencies
* [A cmake library](https://github.com/knode-ai-open-source/a-cmake-library) needed for the cmake build

## Building

### Build and Install
```bash
mkdir -p build
cd build
cmake ..
make
sudo make install
```

### Uninstall
```bash

```

### Build Tests and Test Coverage
```bash
mkdir -p build
cd build
cmake BUILD_TESTING=ON ENABLE_CODE_COVERAGE=ON ..
make
ctest
make coverage
```

