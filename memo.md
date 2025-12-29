# 激活虚拟环境
.\venv\Scripts\activate 

# 上传github仓库步骤
# first 合并
git init

git add memo.md

git commit -m "first commit code"

git branch -M main

git remote add origin https://github.com/prettyyefan/IJCNN2026.git

git pull origin main --allow-unrelated-histories

# after

git add memo.md

git commit -m "update 2025.12.17"

git push -u origin main