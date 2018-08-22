Git is a distributed version control system.
Git is free software distributed under the GPL.
Git has a mutable index called stage.
Git tracks changes of files.

```bash
git checkout -- file
撤销工作区的修改
git reset HEAD <file>
撤销暂存区的修改
git branch -D <name>
强制删除指定分支
git remote <-v>
获取远程库信息
git branch --set-upstream-to=origin/<branch> dev
指定本地dev分支与远程origin/dev分支的链接
git pull
抓取远程的新提交
```