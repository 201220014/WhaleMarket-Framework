# 框架代码的说明



**@author: 家才**
**@email: 201220014@smail.nju.edu.cn**



在初始框架代码中写好了一个简单的多模块的“Welcome”程序,整个项目可以在此基础上展开。
框架代码中有一些可能在各位知识范围之外的东西————主要是关于终端字体样式设置(ANSI控制码)，
可以先上网搜索，还是无法理解可以询问我。

构建项目的Makefile我已经为各位写好了，同时添加了注释，有兴趣的同学可以看一看，
没兴趣的话只需要知道它的功能是构建整个项目就是了。

基本使用方法：

```shell
user@linux WhaleMarket> make # 或者 make main
```

一些过程信息

```shell
user@linux WhaleMarket> ./main
输出main函数运行结果
user@linux WhaleMarket> make clean # 清除项目生成过程中产生的中间文件和生成的可执行程序
```

编辑项目的方式：

```shell
user@linux WhaleMarket> code .
```

会弹出vscode窗口，在窗口下编辑文件即可

建议自主设计项目的文件结构，不要所有的代码都堆在一个文件里，
也不要所有的代码文件都堆在一个文件夹里。



## 正常构建项目需要遵守的约定

1. 在src文件夹下放源文件，在include文件夹下放头文件；
2. 包含头文件的路径名是从include文件夹开始的相对路径，可以看框架；
3. 文件IO的路径名是从WhaleMarket开始的相对路径；



## 环境测试

```shell
user@linux WhaleMarket> code . # 能够正常唤起vscode
user@linux WhaleMarket> make # 或者 make main
# 一些过程信息，没有报错信息
user@linux WhaleMarket> ./main
#得到下图中的结果并听到系统提示音
```

![initial](initial.png)



命令成功编译运行程序并获得图中的输出结果，听到系统提示音，则环境配置成功，
可以正式开始了。

这是一个几乎从0开始的项目，也是各位的第一个多模块项目，过程可能会有些辛苦，
但坚持下来一定会收获颇丰的。

最后祝大家寒假愉快！

