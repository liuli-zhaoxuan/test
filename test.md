this is a test for git.

先本地创一个文件夹：test

初始化仓库

提交

问题1：
The following file has unsaved changes which won't be included in the commit if youproceed: test.md. Would you like to save it before committing?

没有保存就直接提交了，所以有这个弹窗。可以在vscode的setting中设置 Smart Commit Changes
This option is in all it will automatically stage all the changes.[default option]
if the option is in tracked it will automatically stage the tracked changes only.

问题二：
请确保已在 Git 中配置你的"user.name"和"user.email"
全局配置：
$ git config --global user.name "liuli-zhaoxuan"  # 配置用户名
$ git config --global user.email "liulizhaoxuan@gmail.com"  # 配置邮箱

以上是全局配置“user.name”和“user.email”的命令，如果想要配置单个项目git的“user.name”和“user.email”，打开终端，进到该项目目录下，运行命令：　　
$ git config user.name "your_username"
$ git config user.email "your_email"

配置完，查看git中配置的用户名和邮箱，看看是否配置成功
$ git config user.name
$ git config user.email

https://blog.csdn.net/weixin_48024605/article/details/136037857