# git 基本命令

+ git init                                  
  
  初始化

+ git status                                
  
  查看当前状态

+ git add .                                 
  
  添加所有文件到本地仓库

+ git commit -m "描述"                       
  
  提交所有文件到本地仓库

+ git log 

  查看日志

+ git reset --hard HEAD^ 

  代码回退到上一次提交 

+ git remote add origin [远程路径]

  连接远程服务 

+ git remote remove origin master 

  删除远程路径 

+ git push -u origin master 

  将文件提交到主分支 

+ git branch -a

  查看所有的分支

+ git branch -r 

  查看所有的远程分支 

+ git branch gh-pages 

  创建新分支  

+ git checkout gh-pages 

  切换到新分支

+ git push -u origin gh-pages 

  提交到新分支  

+ git fetch origin dev（dev为远程仓库的分支名）

  把远程分支拉到本地

+ git pull origin dev(远程分支名称)
  
  把某个分支上的内容都拉取到本地

+ 如果有未提交的更改，是不能git pull的

  先执行 git stash 

  再执行 git pull --rebase origin master 

  最后再执行  git push -u origin master
