git教学
初始化仓库: git init
把文件添加到仓库: git add readme.txt
把文件提交到仓库: git commit -m 'append a readme file'
查看当前仓库的状态: git status
查看修改的内容: git diff
查看历史纪录: git log
查看历史纪录一行版: git log --pretty=oneline
把当前版本回退到上一个版本: git reset --hard HEAD^
把当前版本回退到上两个版本: git reset --hard HEAD^^
回退到上100个版本: git reset --hard HEAD~100
指定到某个版本: git reset --hard d257e868
每一次命令查询: git reflog