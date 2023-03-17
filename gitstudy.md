# git学习
1. git add

	add 到暂存区

2. git commit -m "comment"

	commit 到HEAD

3. git restore "filename"

	恢复修改或者删除的在工作目录中的文件

4. git restore --staged "filename"

	恢复已经add到暂存区的文件，包括修改、删除和添加的

5. git status

	查看当前状态

6. git log --pretty=oneline

	查看历史版本

7. git reset --hard [HEAD^ | index ID]

	版本回退 


8. git remote add origin git@github.com:kiko-Y/learngit.git

	连接远程库


9. git remote -v
	
	查看远程库


10. git push [-u] origin master

	将master分支推送到远程库中，-u把本地的master和远程的master关联起来

11. git remote rm origin
	
	断开远程库连接

12. git clone git@github.com:kiko-Y/learngit.git [dirname]
	
	克隆远程库到dirname中，不指定dirname就默认创建一个文件夹再克隆进去

13. git branch
	
	查看所有分支

14. git checkout -b "branchname" | git switch -c "branchname"
	
	创建分支并切换过去

15. git checkout "branchname" | git switch "branchname"
	
	切换分支

16. git branch -d "branchname"
	
	删除分支

17. git merge "branchname"

	将branchname合并到当前分支
