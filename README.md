# MPProject
MapReduce 大项目，电影推荐

## Git 操作流程

* 克隆项目

  git clone

* 操作之前在主分支进行 git pull

* 创建自己的分支

  git branch

* 切换到自己的分支

  git checkout

  同步主分支

  git merge main

  或者每次删除本地分支再建立新的分支

* 本地修改和提交

  git add

  git commit

* rebase 操作：将分支合并成一个链

  git rebase -i Head~n    将多个提交合并为一个

  git rebase master  合并到主链

* 切换到主链

  git checkout main

* 进行 merge 操作

  git merge 你的分支名

* 传到远程仓库

  git push