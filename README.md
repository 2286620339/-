# Novice-Village

命令行自学
命令行中本身给的提示也蛮多的

1、git init ：使当前目录被指定为库（创建本地空仓库）

2、git clone + 库地址：将库克隆到本地

3、git add/rm + 文件：将文件的增加/删除信息提交缓存
    add时文件要存在，可以直接在命令行中输入"touch + 文件"来创建目标文件
    
4、git commit -m + "描述"：将缓存中操作添加备注并添加到本地库中
    git reflog：查看提交历史
5、git log ：日志，能够为每次操作提供id参数
    git log --pretty=oneline：简洁打印输出
    git log + 文件：该文件的操作日志
6、git reset --hard + 参数：回滚到目标参数时间
    git reset --hard HEAD~3：回滚3次，3可变
7、git status：查看当前仓库状态（绿色：在缓存中未提交；红色：没有操作，未在缓存中）
8、git push origin master：上传本地当前分支到master
    git push：上传本地所有分支到master
9、
