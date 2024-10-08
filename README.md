# Git-CLI commands exercise
## Basic commands
[Git Commands Doc](https://git-scm.com/docs)
- git init
    初始化新的Git仓库
- git clone [URL]
  - 克隆一个仓库, HTTPS/ssh
- git add
  - git add [file-name]
  - git add -A
  - git add .
  - git add --all
- git commit -m "Your commit message"
  - 提交更改并标注修改内容
- git status
  - 查看当前git header变化状态
- git log
  - 查看提交历史
  - --all --decorate --oneline --graph 图形化显示history
- git push
  - 将本地更改推送到远程仓库
- git branch
  - 查看所有本地分支
  - -r 查看所有远程分支
- git branch [branch-name]
  - 创建分支
- git checkout [branch-name]
  - 切换分支, 如果本地不存在该分支则创建
- git merge [branch-name]
  - 合并目标分支到当前分支
- git branch -d [branch-name]
  - 删除目标分支
- git reset
  - 重置分支
- git revert
  - 回滚分支