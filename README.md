# Git 提交指令速查

## 新建仓库（本地已有文件, 非代码文件）

1. GitHub上新建仓库名，不勾选.README .gitignore .License
2. 需要上传的文件夹右键选 git bash，输入指令: 
git init
git add .
git commit -m "初始化备注"
git remote add origin https://github.com/ntoprevd/xxx.git
git branch -M main
git push -u origin main

## 日常更新

输入指令:
git add .
git commit -m "更新了XX内容"
git push
