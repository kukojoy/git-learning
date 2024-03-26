

# git常用命令

git init --- 初始化本地仓库

git add -A --- 添加文件进入仓库

git commit -m “caption” --- 提交修改

git clone 仓库链接 --- 克隆仓库到本地

git status --- 查看仓库状态

git remote add 远程仓库名（约定俗成叫作origin） 仓库链接 --- 将本地与远程仓库关联

注：本地可以和多个仓库关联，origin不能重复用

git pull 远程仓库名 分支名 --- 拉取分支到本地

git push -u origin master / git push --- 上传本地到远程仓库（在第一次上传时，记得先commit）

git log --- 查看commit记录