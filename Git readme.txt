Git 命令大全

git init -- 把当前目录变成Git可以管理的仓库；
git add <file> -- 把文件添加到仓库；
git commit -m <message> -- 把文件提交到仓库，并标注说明信息；
git status -- 查看仓库当前状况；
git diff <file> -- 查看文件的变化；
git log -- 显示从最近到最远的提交日志；
git reset --hard commit_id -- 把当前版本变为commit_id指向的版本；
git reflog -- 查看命令历史，以便确定要回到未来的哪个版本；
git checkout -- <file> -- 把文件在工作区的修改全部撤销，回到最近一次git commit或git add时的状态；
git reset HEAD <file> -- 把暂存区的修改撤销掉，重新放回工作区;
git rm -- 先手动删除文件，然后从暂存区删除一个文件