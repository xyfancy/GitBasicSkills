Git是一种分布式代码版本控制管理工具

* gitpush.sh是Linux下用于推送更新的脚本,使用方法为`./gitpush.sh`

* 文件夹中存放的是不同系统下安装Git的方法

* Git学习网址为:https://www.liaoxuefeng.com/wiki/0013739516305929606dd18361248578c67b8067c8c017b000/

* Git远程登陆方法见文档

Tips记录：

1. 如何删除之前的commit记录
```
1.Checkout

   git checkout --orphan latest_branch

2. Add all the files

   git add -A

3. Commit the changes

   git commit -am "commit message"


4. Delete the branch

   git branch -D master

5.Rename the current branch to master

   git branch -m master

6.Finally, force update your repository

   git push -f origin master
```
