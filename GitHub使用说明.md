# git安装
[git下载地址](https://git-scm.com/)
# 启动git bash
## 创建用户名和邮箱
`git config --global user.name "yourname"`  
`git config --global user.email "your email address"`
## 创建版本库
cd至要创建版本库的文件夹  
`git init`  
然后会在这个文件夹下生成一个.git文件夹，表示创建成功
然后将代码or工程文件放入这个文件夹
## git操作
`git add xxx.文件后缀` 表示将该文件添加到暂存区  
`git commit -m "delete/... xxx"` 表示对刚才添加的文件更改的说明  
`git log` 查看更改日志  
`git reflog` 获取版本号   
`git reset --hard(有多种模式) HEAD^{xx}` 表示回退到之前xx版本    
`git reset --hard xx` 向前到(与回退相反)xx版本  
`git remote add origin https://github.com/yourRegistrationName/RepositoryName.git`  将本地仓库连接至远程仓库  
`git push -u origin master` 将主分支上传至远程仓库,以后的操作不用加-u  
`git clone https://github.com/yourRegistrationName/RepositoryName` 克隆远程仓库到本地  
`git branch branchName` 创建分支  
`git branch` 查看分支  
`git branch -d branchName` 删除分支  
`git checkout -b branchName` 创建并切换到创建的分支  
`git merge branchName` 合并分支


