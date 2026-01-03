# 上传github仓库步骤
# first 合并
git init

git add memo.md

git commit -m "first commit code"

git branch -M main

git remote add origin https://github.com/prettyyefan/Corn_ML.git

git pull origin main --allow-unrelated-histories

# after

git add memo.md

git commit -m "update 2026.01.03"

git push -u origin main

# 激活虚拟环境
.\venv\Scripts\activate 

# To do
python csv_finetuner.py
