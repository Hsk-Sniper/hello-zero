##### hello
***
###### 版本问题：
```
1. git log [--oneline]

2. git reflog

3. git reset [--hard] <versioncode>
```
###### 工作目录与本地仓库问题
```
1. git status

2. git add [index.html] [-A]

3. git commit [-m <"修改的内容解释">]
```
###### Merge:
```
1. git fetch <远程主机名> <远程分支名>

2. git merge <要合并的分支>
```
hi
nihao
###### 先fetch得到远程仓库副本，然后再通过（本地仓库）merge远程仓库副本到
###### 工作目录，再add，commit到本地仓库后push到远程仓库。