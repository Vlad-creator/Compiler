# Compiler
Compiler project
```
### How to build:
Create directory ```build```, than open terminal and do this comands:
```cpp
>cd build
>cmake .. 
>cd ..
>cmake --build build
```
It will create the project in ```build```
```cpp
>./numlex <file.pcl> //to generate llvm file : file.pcl.ll
```
```cpp
>clang++ <file.pcl.ll> ../pcl_lib/lib.cpp <directory> //to run compile llvm file with pcl_lib
```

## Gratitude
Thanks to me for doing this project.
