# git
deep study for git
1.git status -s 查看简略的状态
2.git diff 查看unstash状态
3.git diff --cached 查看stash状态
4.git stash 存储当前工作修改但是不想提交的代码
5.git stash list 列出当前工作修改但是不想提交的stash
6.git stash apply 应用最近的stash

7.git commit --amend --no-edit 追加到最近的一次commit

8.git reset 文件名 staged状态到unstage状态
9.git reset --hard HEAD 回到最近的一次commit
10.git reset --hard HEAD^ 回到倒数第二次提交 ^后边可以加数字 HEAD~1
11.git reset --hard id 回到id处

12.git reflog 显示所有的HEAD信息，为了回到过去之后取不到将来的HEAD ID
