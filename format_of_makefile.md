makefile多文件工程应该以zip压缩包的形式提交, 且makefile文件必须位于zip压缩包的根目录下

也就是说, 在一个空文件夹 new folder下, 把你的zip文件a.zip粘贴进来, "解压到当前文件夹"或者在linux下调用`unzip a.zip`, 然后调用make命令, 应当能够正常编译

要求最后生成的可执行文件名字*必须*为client.exe

要求上交的压缩包中不能含有任何中间文件或最终文件(如main.o, client.exe), 只含源代码. 因为在你的机器上编译的main.o, client.exe在服务器平台上可能无法正常运行
