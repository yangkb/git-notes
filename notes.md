git 命令

获取代码：git clone  (git clone ssh://xiaoming@192.168.1.1:29418/MTK/framework/base)
查看分支：git branch -a  (*为当前所在分支)
创建分支：git branch s
切换分支到s中：git checkout s

对代码进行修改后，查看文件内容差异 ：git diff
查看修改的文件：git status

将修改的文件添加到缓存区：
	1 git add .
	2 git commit -m "备注"
	
提交：git push
