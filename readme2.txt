git add -f <file>  假如文件被忽略这样可以强制添加

git commit -m "balabalabala" 提交暂存区的文件到本地仓库

git log --graph --pretty=oneline 查看日志

git reset --hard HEAD^   (git reset --hard 版本编号)  版本回退 

git reset HEAD <file> 添加到了暂存区时，想丢弃修改 

git checkout --<file>  当你改乱了工作区某个文件的内容，想直接丢弃工作区的修改时

git rm <file> 从版本库中删除该文件(然后commit)