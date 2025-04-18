# 基础操作
1. 在需要上传的文件夹内打开控制台
 
2. ls：查看当前目录下的文件
 
3.在github上创建仓库
4. git init:初始化一个本地git仓库
 
5. git config --list:查看当前本地仓库配置（查看是否有git remote add origin https://github.com/huang-chenyi/仓库名.git）
 
6. 如果没有则输入git remote add origin https://github.com/huang-chenyi/仓库名.git
7. git branch -M main：推送至主分支
 
8. git add .:将本地仓库文件放到暂存区
 
9. git commit -m"[中间放置对提交东西的注释]"
 
10. git push origin main：推送（结束）



# 其他
11. git branch <分支名>：创建分支

12. git checkout <分支名>：切换到分支（若已经提交或者已经切换，会进行查看操作）
或者git checkout -b <your-branch-name>一步完成创建和切换

13. git merge <要合并的分支名或main>：合并分支（将<>中的合并至当前支线或主线）

14. git rebase <要复制的分支名或main>（将<>中的合并至当前支线或主线-以复制的形式）（前置要求是两个支线要求均提交）

15. git checkout HEAD^：向上移动查看分支提交记录的指针

16. git checkout HEAD~<number>（波浪号，esc下面的键）

17. 移动分支。可以直接使用 -f 选项让分支指向另一个提交。
例如:git branch -f main HEAD~3（波浪号，esc下面的键）
上面的命令会将 main 分支强制指向 HEAD 的第 3 级 parent 提交。
HEAD似乎是强制要求的指令
18. 

