Git is a distributed version control system.
Git is free software.
Creating a new branch is quick.

正常进行项目文件推拉处理方式：
1. 本地创建一个和远程仓库一样的文件夹BBB；
2. 进入BBB；
3. 用git init 把本地的BBB 变成一个仓库
4. 通过 git remote add  仓库名称（自己取名，默认为origin） BBB远程仓库地址 进行关联
5. 通过 git pull 仓库名称  远程分支（master）   将BBB远程仓库的文件拉取下来
6. 通过 git push 仓库名称  远程分支（master）   将BBB本地仓库的文件推送到BBB远程仓库；