# some-of-git
## 切换远程仓库地址
    当前项目目录执行git remote -v 查看当前项目远程仓库地址  
    git remote set-url <新远程仓库地址>  
    git remote -v 查看即为新的远程仓库地址
## 分支相关
    git branch dev  创建分支  
    git checkout dev 或 git switch dev切换分支
    git checkout -b dev 或 git switch -c <name> 创建并切换分支
    git merge dev 合并分支 （合并dev分支到当前分支）  
    git branch -d dev  删除dev分支
## 上传代码
    git pull  拉取远端代码
    git status 查看状态  
    git add 添加要提交的代码地址  
    git commit -m "备注提交代码的功能"  
    git push 提交代码到远程服务器  
## 查看日志
    git log   
    commit 9cac9ba76574da2167  commit后面的是提交标识（备注）
## 回滚到指定的版本（hard后面接的是上面标红的ID,也就是想回滚到的版本）  
    ## 回退到指定版本，不保留原更改代码  
    git reset --hard e377f60e28c8b84158
## 回退到指定版本，保留原更改代码，且生成新的提交  
    git revert e377f60e28c8b84158
  
  
  
