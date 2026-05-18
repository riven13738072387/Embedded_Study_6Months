# Day 2 Git/Gitee 入门

## 今日学习命令

```bash
git clone https://github.com/user/project.git //复制远程仓库到本地
git pull = git fetch + git merge //拉取代码
git switch main //切换分支
git branch /dev/-d dev //查看、创建dev、删除dev分支 
git status	//查看仓库状态
git diff //查看修改
git init //在空文件夹创建一个仓库或在已有文件夹中初始化仓库，会生成.git文件夹
git add . //添加当前目录内容到暂存区区
git commit -m "初始化学习仓库" //提交暂存区内容，并给这次提交加一次说明 -m = -message
git mv old.txt new.txt //把old.txt重命名为new.txt
git restore --staged main.py //取消暂存
git restore main.py //撤销文件修改
git rm a.txt // 删除文件并记录删除
git log --oneline --graph --all //查看提交记录
git merge dev //把dev分支合并
git rest --mixed commit_id //回退到某次提交，取消暂存保留修改
git tag v1.0.0 //给当前版本打标记
git fetch origin //更新仓库但不合并
git push //本地提交推送到远程仓库
```plaintext

## Git 的作用

Git 用于代码管理，项目开发

## 今日遇到的问题

1. 问题：git有哪些命令
2. 解决：在bash中"git -h"查看帮助
3. 问题：git的命令分别是什么意思，怎么使用？
4. 解决：问AI，先理解命令，再操作
5. 问题：git不会推送空文件夹
6. 解决：touch XXX/.gitkeep占位，再重复 add -> commit -> push

## 今日总结

今天完成了 clone、push、 fetch 、diff、 merge、 switch、 branch dev创建dev分支、 status
init、add .、commit -m "初始化学习仓库" 的初次实操