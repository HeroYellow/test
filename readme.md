0. `git clone 仓库地址`：克隆远程仓库代码
1. `git init`：初始化git仓库
2. `git add .`：将工作区的代码添加到暂存区
3. `git commit -m '提交信息'`：将暂存区的代码添加到版本区
4. `git remote add origin github项目地址 `：本地仓库和远程仓库进行关联
5. `git push -u origin master`：把本地仓库内容推送到远程仓库中，首次加 -u，以后推送或拉去可以简化命令`git push origin master`
6. `git remote remove origin`：删除关联的仓库地址
7. `git pull origin 分支名称`：拉取远程仓库xxx分支到本地xxx分支来（远程仓库有更新，本地要拉取更新）
_________

1. `git log`：显示从最近到最远的1所有提交日志
2. `git reflog`：显示每次提交的commit id
3. `git reset --hard HEAD^`：回退到上一个版本
4. `git reset --hard id`：回退到指定版本

____________

1. `git branch dev`：创建dev分支
2. `git checkout -b dev`：创建dev分支，并切换到dev分支
3. `git checkout master`：切换分支
4. `git merge dev`：合并指定dev分支到当前分支
5. `git branch -d dev`：删除指定分支
6. `git branch`：查看当前分支

