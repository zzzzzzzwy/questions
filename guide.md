#常用指令

```bash

cd 目录名           检索文件夹目录
mkdir 目录名称      创建目录
rm 目录名/文件名    删除文件夹/文件

```

```bash
git 指令名

git checkout 分支名                 切换分支

git add 文件名                      将指定文件的修改添加到提交缓存

git commit -a -m "文字说明"         总结缓存中的改动，用于推送到远程服务器

git push                           将代码改动推送到远程服务器

git merge 仓库标识                  用于合并代码到指定标识符的仓库

git status                         查看当前的改动

```

注意推送/合并等操作时所在的分支


#更新题目

1.  切换到questions分支
2.  git fetch questions             这里的questions是远程仓库的标识符
3.  git merge
4.  git status

#推送答案

1.  切换到master分支
2.  git status                      查看并确认文件改动
3.  git commit -a -m "改动说明"      提交缓存到本地仓库用于推送
4.  git push origin master          推送代码改动到远程分支
5.  git status