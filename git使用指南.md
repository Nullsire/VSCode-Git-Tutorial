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

![初始化界面](fig/初始化界面.png)

点击左上角 Initialize Repository 即可在当前路径下新建一个 git 仓库，相当于 git init.

### 暂存

![暂存](fig/暂存.png)

![暂存效果](fig/暂存效果.png)

注：当暂存区存在文件时，提交时仅有暂存区的文件会被提交；暂存区为空时，VSCode 会询问是否提交未被暂存的文件（可通过设置令 VSCode 遇到该类情况不再询问，直接提交发生修改的所有文件）

### 提交（本地）

![提交（本地）1](fig/提交（本地）方法1.png)

在输入提交信息后点击 Commit 即可提交修改，或者先点击 Commit，之后会跳出填写提交信息的界面，填写内容后点击右上角的 "√" 即可提交修改

![提交（本地）2](fig/提交（本地）方法2.png)

### 向远程仓库提交



### 与远程仓库同步

### 新建分支

### 切换分支

## 插件推荐

- gitlens