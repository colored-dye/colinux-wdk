Work on coLinux with Windows WDK 10 and xmake.

To build for Windows x86 architecture with clang-cl compiler and msvc linker, in debug mode:

````
xmake f -p windows -a x86 -m debug -o d:\Code\coLinux-wdk/build --toolchain=clang-cl
```

Q1: Does clang-cl offer compatibility between Windows and Linux platform?
