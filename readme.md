-当前是项目目录
-成为一个代码仓库，管理文件的不同版本
-git init                   ：初始化
-git add file               ：如果未添加（add）是一个未跟踪的文件,需要将修改的文件添加到暂存区，
-git add .                  ：添加了根目录下的所有文件
-git status                 ：查看文件状态：待提交的变更
-git diff file              ：查看文件修改与修改前的差别
-git commit -m '提交的原因'  ：最后提交一次严谨的修改到本地仓库（里面是各个文件的快照）
-git remote add origin https://github.com/iamf12/fhz_ai.git  ：将本地仓库提交到远程仓库
-git branch -M main         ：在fhz_ai远程仓库建立分支main
-git push -u origin main    :并把本地learn_git文件全部推送到fhz_ai远程仓库的main文件中

-git log --oneline          ：查看日志（版本）
