本程序使用Qt Creator IDE进行开发。借助qmake工具来便利程序的编译。可以在IDE中直接编译生成可以执行文件。

我的个人电脑是mac ，编译的时候使用的kit是Desktop Qt 5.12.9 clang 64bit ，程序可以顺利编译。在windows平台上测试使用Desktop Qt 6.3.9 MSVC2019 64bit同样可以顺利编译。

我在文档中同时附上了Unix可执行文件和exe文件，不过我也发现exe文件在部分电脑运行的时候显示缺少Qt6.0Core.dll文件依赖，基于windows平台的同学在测试的时候需要在环境变量里加上这一文件。

如果测试的时候无法顺利编译或者无法顺利打开exe文件或Unix可执行文件，关于详细的操作演示，我在文档中另附了一份操作演示视频，可以观看。



 




因为pta传不上80M以上的视频，所以就压缩了演示视频大小，可能看起来比较糊……


------------------
on Sept 26, 2022
this is one of my initial programs in Object-Oriented Programming class.
it uses qt to implement a geometrical drawing software.
