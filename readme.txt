This is my dev branch yeah!

Git is a distributed version control system.
Git is free software.
Learn git
git has a mutable index called stage
git tracks changes of files
git move
git creating a new branch is quick
creat branch dev

git is simple and diffrent


概念：
1、工作区：就是你在电脑里能看到的目录
2、版本库：工作区有一个隐藏目录.git，这个不算工作区，而是Git的版本库。Git的版本库里存了很多东西，其中最重要的就是称为stage（或者叫index）的暂存区，还有Git为我们自动创建的第一个分支master，以及指向master的一个指针叫HEAD
3、暂存区：在工作区执行 git add . 就是把工作区提交到版本库的暂存区里
4、master分支：如果当前切换到的是master分支，在工作区执行 git commit -m "提交注释",就是把版本库的暂存区的内容提交到版本库的master分支里
5、远程仓库：比如说GitHub或者码云等，不在本地的仓库就是远程仓库，我们在GitHub上创建好一个仓库时，GitHub会自动将这个仓库命名为origin仓库，在工作区里执行 git push -u origin master 就是将本地的master分支的内容提交到GitHub上我们新创建好的仓库origin的master分支中


常用git命令:
1、git status ---查看工作区的状态(是否有修改了还没有提交到版本库的)
2、git add readme.txt/. ---将工作区的指定文件或者全部文件提交到暂存区中
3、git commit -m '提交注释'  ---将暂存区中的内容提交到版本库的当前分支(master)中
4、git remote add origin git@github.com:youngwellcool/learngit.git   ---把本地的版本库和远程仓库origin建立连接(关联)
5、git push -u origin master  ---将本地的版本库中的当前分支中的内容提交到远程仓库origin的master分支中 (第一次提交时需要加上-u，会把本地的master分支和远程的master分支关联起来，以后的提交就可以不需要加上-u)
6、git checkout -b dev  ---创建dev分支，并切换到dev分支（将dev分支置为当前分支，以后的操作add、commit、push等都是在dev分支中操作，而原先的master分支保持不变）
7、git brach  ---查看所有的分支，其中前面带‘*’的是当前分支
8、git checkout master  ---将master分支置为当前分支
9、git merge dev   ---把dev分支的工作成果合并到当前分支上
10、git branch -d dev  ---删除dev分支
