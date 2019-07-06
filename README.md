# LLVM Hello

Hello world on LLVM C API example

## Building

Install llvm and compile using cmake

```bash
mkdir build && cd build
cmake ..
cmake --build .
```

## Running

After building run `llvm_hello` executable from build directory.

This executable generate `hello.ll` using LLVM C API

To run `hello.ll` file use this command ``lli hello.ll``