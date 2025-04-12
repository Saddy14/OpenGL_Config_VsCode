# OpenGL_Config_VsCode

## If you have not already set up MinGw in your PC follow the guide below
### [GCC from MinGW to run C++ code](https://code.visualstudio.com/docs/cpp/config-mingw)

---

## **Install FreeGLUT via MSYS2 UCRT64 terminal**

`pacman -S mingw-w64-x86_64-freeglut`

---

**Important you might need to edit these files due to compiler path**

> .._properties.json
- For compiler location

> tasks.json
- Path for -  "-IC:/msys64/mingw64/include"

- Path for -  "-LC:/msys64/mingw64/lib"

### If you installed MinGW in default directory and the path in your system enviroment is this
*C:\msys64\ucrt64\bin*
### You don't need to change anything

---

## Note 
Don't remove *.dll* files from *src*, your code will complie and run however, the window will disappear as it needs the files during runtime

## Optional
If you don't like the *.dll* files in *src* you may create a *bin* and add the path to your system variable


*Current files tested and working in Windows*
*Properly best to use for anyone new to OpenGL and want use VsCode and just learning the basics*
