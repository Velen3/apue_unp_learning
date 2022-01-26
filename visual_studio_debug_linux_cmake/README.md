# 总结一下visual studio下调试linux程序的问题

1. __visual studio中安装cmake插件与通用c++开发，可以有linux c++开发__
2. __程序下载到windows目录下__
3. __打开visual studio后使用cmake打开CMakeLists.txt打开项目__
4. __出现如图所示问题，添加CMakeSettings.json中的wsl-GCC-Debug，出问题的地方在generator，改为Unix MakeFiles__
![Wrong](./wrong.jpg)
    ```json 
    {
      "name": "WSL-GCC-Debug",
      "generator": "Unix Makefiles",
      "configurationType": "Debug",
      "buildRoot": "${projectDir}\\out\\build\\${name}",
      "installRoot": "${projectDir}\\out\\install\\${name}",
      "cmakeExecutable": "cmake",
      "cmakeCommandArgs": "",
      "buildCommandArgs": "",
      "ctestCommandArgs": "",
      "inheritEnvironments": [ "linux_x64" ],
      "wslPath": "Ubuntu-20.04"
    }
    ```
5. __使用CMake生成项目，点运行即可__