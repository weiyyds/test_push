### 如何远程将本地仓库推送至远程仓库如github

1.在本地仓库中cmd命令

输入git init创建一个空的本地仓库

2.把需要提交的东东放在本地仓库

3.git add . #将文件添加至暂存区

4.git commit -m '记录提交信息' #这一步已经提交到本地仓库

5.提交至远程仓库

>git remote add origin git@github.com:weiyyds/test_push.git
>
>git push -u origin master



1.在github创建一个仓库

2.复制github上的ssh地址 

在本地仓库中输入cmd

git clone ssh地址

3.把需要提交的东东放在本地仓库

4.git add .

5.git commit -m '提交注释语句'

6.git push origin master