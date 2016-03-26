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
查看工作区和版本库里面最新版本的区别: git diff HEAD -- readme.md
删除文件: git rm README.md
版本库里的版本替换工作区的版本，无论是修改还是删除: git checkout -- README.md
本地仓库与远程仓库关联: git remote add origin git@github.com:LittleDragonX/liuzhou-ui.git
本地库的内容推送到远程仓库: git push -u origin master
从现在起，只要本体作了提交，就可以推送到远程仓库: git push origin master