# Git 指令速查

## 新建仓库（本地已有文件）

1. GitHub 上新建仓库名，不勾选 `.README` `.gitignore` `.License`
2. 需要上传的文件夹下新建.gitignore文档，并添加不上传的内容
3. 需要上传的文件夹右键选 `git bash`，依次输入以下指令：

```bash
git init
git add .
git commit -m "初始化备注"
git remote add origin https://github.com/ntoprevd/xxx.git
git branch -M main
git push -u origin main
```

## 日常更新

```bash
git add .
git commit -m "更新了XX内容"
git push
```
