#ccollect
Tool used to collect structs and functions info from c/c++ sources to JSON.

usage:
```
    ccolect example.c -I/your/include/path \
                      -D_AND_OTHER_COMPILER_OPTIONS_ > output.json
```

build:
    - depends from libclang-3.5, llvm-3.5, ncurses
      (debian: libclang-dev, llvm-dev, libncursesw5-dev)


