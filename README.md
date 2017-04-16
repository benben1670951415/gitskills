# gitskills
设置用户名和邮箱：
$git config --global user.name "your name"
$git config --global user.email "00000@qq.com"
选择合适的位置，创建一个空目录：
$ mkdir example
$ cd example
$ pwd
通过git init命令把这个目录变成git可以管理的仓库：
$ git init
通过git add把文件添加到仓库：
$ git add readme.txt
通过git commit告诉git，把文件提交到仓库：
$ git commit -m"-m后面的内容是对此次提交的说明"
通过git status命令查看当前结果，掌握仓库当前的状态：
$ git status
通过git diff readme.txt查看具体修改情况：
$ git diff readme.txt
通过git log命令查看修改记录，也就是你曾经提交过的版本情况：
$ git log
$ git lot --pretty=oneline
git中head表示当前版本，HEAD^,HEAD^^,分别表示上一个，上上一个，也可以用HEAD~100，第100个之前的版本。
git reset是回退到上一个版本。
$ git head^^
$ git reset
git reflog是查看命令历史
$ git reflog
