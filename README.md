# Graphics library setup 

more detail setup can be found on the main repo [solution-to-graphics.h](https://github.com/kumarbaberval/Solution-to-graphics.h)
## Quick setup

Setup `TDM-GCC-32`
|![step1](./step1.png)|![step1](./step2.png)|
|--|--|

## Get all the files needed `graphics.h`, `winbgim.h` and `libbgi.a`

- Copy `graphics.h` and `winbgim.h` files to `TDM-GCC-32/include` folder.

location might be **("C:/TDM-GCC-32/include/")**

- Copy `libbgi.a` to file to `TDM-GCC-32/lib` folder.

location might be **("C:/TDM-GCC-32/lib")**

## My directory look like

```cmd
  D:.
├───.vscode
└───Home
    ├───build
    └───src
```

- Just `Ctrl+Shift+B` to run the build task you will get the executable file in build folder

## !mportant

- Folder `src` contains source code

- Folder `build` where compiler generate .exe

- .vscode contains c_cpp_properties.json and task require modification according to your environment and types compiler
