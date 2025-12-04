# VSCode Git 使用指南

## 常用指令

- 初始化git仓库：`git init`

- 向仓库中添加文件：`git add [files]`

- 提交修改：`git commit`

- 链接远程仓库：
```bash
  git remote add origin https://github.com/{Username}/{repo_name}.git
  git branch -M main
  git push -u origin main
```

- 克隆远程仓库：`git clone [link]`
- 向远程仓库提交本地修改：`git push`
- 切换分支：`git checkout [branch_name]`

## VSCode Git 可视化界面常用操作

### 初始化仓库

![初始化界面](初始化界面.png)

点击右上角 Initialize Repository 即可在当前路径下新建一个 git 仓库，相当于 git init.

### 暂存

![暂存](暂存.png)

点击文件

### 提交（本地）

### 向远程仓库提交

### 与远程仓库同步

### 新建分支

### 切换分支

## 插件推荐

- gitlens