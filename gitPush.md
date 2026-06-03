```

# 初始化 Git 仓库
#git init

# 添加远程仓库地址（替换为你的仓库 URL）
#git remote add origin https://github.com/用户名/仓库名.git
#git remote -v
git remote set-url origin git@github.com:用户名/仓库名.git

# 添加所有修改到暂存区
git add .

# 或添加特定文件
git add 文件名

# 提交更改（写清楚本次做了什么）
git commit -m "描述本次修改的内容"

# 推送到远程仓库的 main 分支
git push origin main

# 如果是 master 分支（旧项目）
git push origin master
```



## create a new repository on the command line
```
echo "# MachineLearningNotes" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/bwAI123/MachineLearningNotes.git
git push -u origin main
```


## push an existing repository from the command line
```
git remote add origin https://github.com/bwAI123/MachineLearningNotes.git
git branch -M main
git push -u origin main
```

