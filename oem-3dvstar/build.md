1.安装Visual Studio 2008到C盘默认路径，

  1.1安装Visual Studio 2008 SP1---非常重要，否则编译出来的版本会崩溃。

  1.2安装Windows SDK，推荐的版本是Windows7SDK

  1.3安装DirectX SDK，推荐的版本是DXSDK_Jun10.exe

2.将yasm.exe拷贝到C:\Program Files (x86)\Microsoft Visual Studio 9.0\VC\bin

3.编译BaseClasses的Release版本

4.以debug 编译一下renderer_prototype整个解决方案， 会报若干错，无视它，只要shader编译正常即可

5.以Realease编译一下report_server.

6.以release filter编译一下my12doomSource的BaseVideoFilter

7.运行build_bo3d_vstar.bat