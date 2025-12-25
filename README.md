# 进入你的项目目录（替换成实际路径）
cd shooting-game

# 初始化 Git 仓库
git init

# 添加所有文件到暂存区
git add .

# 提交到本地仓库
git commit -m "feat: 添加三关射击小游戏"

# 确认分支为 main
git branch -M main

# 关联远程仓库（替换成你的 GitHub 仓库地址）
git remote add origin https://github.com/<你的用户名>/<仓库名>.git

# 推送到 GitHub
git push -u origin main
