# -Linux-Windows-socket-
跨Linux,Windows_Socket操作极简封装

在Windows下：
用visual studio 创建一个空项目，项目类型为:静态库（lib）或者动态库(dll)，然后编译即可。

在Linux下：
安装好GCC  G++编译后。
修改compile.sh 里面第一行的 cd 后面的路径，指向：源文件路径，保存。
然后运行compile.sh 然后远文件路径就会出现 *.a文件，静态库。

具体函数说明直接看头文件即可。很简单。

这次封装只是极简封装，同步还算健全，异步只有发送和接收的异步调用，没有异步的处理事件（即:回调函数）
如果需要异步，可以采用：多线程+同步 即可实现异步。

若有疑问请联系我，喜欢请送个星星。
