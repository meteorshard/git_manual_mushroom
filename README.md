# GIT 命令

## 基本

添加所有改动过的文件  
    git add .

提交修改  
    git commit -m '注释'

发布到远程仓库  
    git push (远程仓库别名) (分支名称)

## 分支操作

创建并切换到新分支  
    git checkout -b (分支名)

切换到已有分支  
    git checkout (分支名)

查看所有分支  
    git branch -a

把分支B合并到分支A  
    git checkout A  
    git merge B

删除分支B  
    git branch -d B

删除远程分支B  
    git push (远程仓库别名) :B