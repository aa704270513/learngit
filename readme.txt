
git diff 是工作区和暂存区的对比
git diff -- cached 是暂存区和分支的对比
git diff HEAD readme.txt  工作区和分支的对比


文件已修改，未add到暂存区:
git checkout -- file可还原
文件已修改，并add到暂存区未commit：
git read HEAD file
git checkout -- file可还原
保存到暂存区的情况，其实可以一条命令搞定：
git reset --hard head



Git鼓励大量使用分支：
查看分支：git branch
创建分支：git branch <name>
切换分支：git checkout <name>
创建+切换分支：git checkout -b <name>
合并某分支到当前分支：git merge <name>
删除分支：git branch -d <name>


git push origin master


可以用git push origin :dev 删除远程分支dev，origin和:dev之间有空格


用git log --graph命令可以看到分支合并图。
