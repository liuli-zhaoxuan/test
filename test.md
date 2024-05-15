this is a test for git.

先本地创一个文件夹：test

初始化仓库

提交

问题1：
The following file has unsaved changes which won't be included in the commit if youproceed: test.md. Would you like to save it before committing?

没有保存就直接提交了，所以有这个弹窗。可以在vscode的setting中设置 Smart Commit Changes
This option is in all it will automatically stage all the changes.[default option]
if the option is in tracked it will automatically stage the tracked changes only.