# How to use Git

## 绑定用户

## 设置SSH key

## 添加关联

key:saved in "user/kitty/.ssh"

## 更新文件

1. `git init`
2. `git add .`
3. `git commit -m "message"`
4. `git remote add origin git@github.com:Yjy20050126/Bioinformatics-KittyYang.git`
5. `git push -u origin master`

- Tips: `git pull origin master`当遇到网页内容与本地不同步时
- 改变分支：`git config --global init.defaultBranch main``git init -b main`
- 本地操作main分支，先将库克隆到本地`git clone <URL> `
