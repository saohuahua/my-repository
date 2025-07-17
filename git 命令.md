`git ls-files` 查看暂存区的文件

## git reset
`git reset` 三种模式
`git rest HEAD^` 回退到上一个版本
命令               工作区    暂存区
`git reset --soft`    √         √
`git reset --hard`    ×         ×
`git reset --mixed`   √         × 

## git diff
`git diff` 查看文件修改后的差异(一般用图形化界面查看，了解即可) 工作区 暂存区差异
`git diff HEAD` 比较工作区+暂存区和本地仓库差异
`git diff --cached` 比较暂存区和本地仓库差异
![alt text](QQ_1752731395422.png)

## git rm
`git rm` 文件名 从工作区和暂存区同时删除文件