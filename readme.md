# 初识git
* Git is a dietributed version control system.
* Git is a free software.

### git命令
1. git innit                    初始化一个git仓库
2. git add fileName             把文件修改添加到暂存区
3. git commit -m "des"          把暂存区的所有内容提交到当前分支 -m 后面描述提交改变
4. git status                   查看仓库当前状态
5. git diff                     查看更改
6. git pull URL                 拉取一个请求 URL为实际项目地址
7. git push -u origin master    把更改内容推到主分支
8. git reset --hard HEAD^       回退到上一个版本(HEAD^^上上个版本，HEAD~100上100个版本)
9. git checkout -- readme.md    把readme.md文件在工作区的修改全部撤销(还原文件)
10. git reset HEAD file         把暂存区的修改撤销掉(还原文件)
11. git rm file                 删除文件
12. git checkout -b dev         创建dev分支，并切换到dev分支
13. git branch dev              创建dev分支
14. git checkout dev            切换到dev分支
15. git branch                  查看当前分支
16. 