# Change Log

* 2017-9-12
  * Change help logic. Now argument `-h` will display help and exit.  
    修改帮助逻辑。现在`-h`参数会在显示帮助后退出。
  * Fix many warnings and errors when building on Linux.  
    修正在Linux系统下编译时的许多警告和错误。
* 2017-5-16
  * Fixed a bug when reading command lines.  
    修复了一个读取命令行时的bug。
* 2017-5-13
  * `inpout32` added. Now we can play with the speaker on Windows 7 and above.  
    加入`inpout32`库。现在可以在Windows7及以上版本系统的中调用蜂鸣器了。
  * `WinMake.bat` and `WinMakeClean.bat` added to compile with `mingw`(`GCC`) on Windows.  
    加入`WinMake.bat`和`WinMakeClean.bat`，用来在Windows下使用`mingw`（`GCC`）编译。
* 2017-5-10
  * `^c` support added. May be buggy on Linux.  
    加入对`^c`的支持。在Linux下支持不好。