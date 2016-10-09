# vscode-python
# 总体流程
1. 下载安装python

2. 在vscode上安装python的开发环境

3. 配置环境

# 下载安装python
python现在主要有两个分支，一个是python2.7.x，另一个是3.5.x，这个主要是个人的习惯，哪个使用的顺手就用哪个。如果是新手的话，建议学习3.5.x吧，毕竟比较新。

[python的下载链接](https://www.python.org/downloads/)

# 在vscode上安装python的开发环境
打开你的vscode，然后按下 ‘ctrl + e’， 输入ext install python', 然后再众多的选项当中选一个安装（一般选择热度最高的）

![image](https://github.com/Fuyi-Huang/Fuyi-Huang.github.io-vscode-python/raw/master/pictures/capture.JPG)

# 配置环境
继续打开你的vscode，然后在文件下选择打开文件夹，因为vscode的编程环境都是以文件夹区分的

![image](https://github.com/Fuyi-Huang/Fuyi-Huang.github.io-vscode-python/raw/master/pictures/capture1.JPG)

然后你就会发现在打开的文件夹下多了一个.vscode文件夹，里面有一个task.json文件，打开它，将内容修改为

`
{
    // See https://go.microsoft.com/fwlink/?LinkId=733558
    // for the documentation about the tasks.json format
    "version": "0.1.0",
    "command": "D:/python/python.exe",
    "isShellCommand": true,
    "args": ["${file}"],
    "showOutput": "always"
}
`
其中command的地址是自己的python的安装地址

接着打开用户设置：

![image](https://github.com/Fuyi-Huang/Fuyi-Huang.github.io-vscode-python/raw/master/pictures/capture2.JPG)

搜索到python的设置，将python.pythonPath修改为你的python的安装地址

![image](https://github.com/Fuyi-Huang/Fuyi-Huang.github.io-vscode-python/raw/master/pictures/capture3.JPG)

到这里你的python就可以用了，随便编写一个hello world试一下

![image](https://github.com/Fuyi-Huang/Fuyi-Huang.github.io-vscode-python/raw/master/pictures/capture4.JPG)

![img](http://img05.tooopen.com/images/20140604/sy_62331342149.jpg)

耶，撒花！
