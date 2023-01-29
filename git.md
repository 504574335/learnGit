# Git学习
## 常用命令
1. 初始化
   - `git init` 设置仓库
2. 提交/删除文件
   - `git add ...` 添加文件到仓库
   - `git rm ...` 从仓库中删除文件
   - `git commit` 提交暂存区中的修改
   - `git status` 查看仓库的状态
3. 查看历史
   - `git log` 查看提交历史
   - `git relog` 查看历史命令
4. 修改版本
   - `git reset --hard ...` 修改仓库版本
   - `git checkout -- ...` 撤销工作区的文件修改
   - `git reset HEAD ...` 撤销暂存区的文件修改
5. 远程仓库
   - `git remote add/remove/set-rul origin ...` 管理远程仓库
   - `git push -u origin main` 推送到远程仓库
   - `git clone ...` 克隆远程仓库
6. 分支管理
   - `git switch -c ...` 创建并转换分支
   - `git merge ...` 合并分支
   - `git branch -d ...` 删除分支


## 基本概念
1. 仓库（版本库）
2. 本地仓库：工作区与暂存区
3. 远程仓库
4. 分支管理、合并冲突