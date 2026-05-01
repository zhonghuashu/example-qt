example-cpp
=================================
# Introduction
Example code for Linux Qt.
- app/hello_world       : First Qt program.

# Hello world
Create Hello world Qt program
- New project > Application (Qt) > Qt Widgets Application
  - Set as default project path
  - Build system : qmake
- Base class QMainWindow
- 编译器: Desktop Qt 5.12.9 GCC 64 bit
- Project overview
  - hello_world.pro 是项目管理文件
  - *.ui 样式文件由 XML 语言描述组成, 可以跳转到设计界面
- Run hellp world
  `cd build-hello_world-Desktop_Qt_5_12_9_GCC_64bit-Debug && ./hello_world`

