1 创建一个新的仓库
2 将该仓库的地址复制下来，放到vscode 中
    git clone '仓库地址' 
3 创建一个文件，将该文件上传到该仓库中
    1、git add '新文件名'
    2、git status 查看当前的仓库中的新文件
    3、git commit -m '备注'
    4、git status 查看当前的仓库中的新文件
    5、git push  将该文件提交到仓库中

git 进阶功能

Git is free distributed under the GPL

git reset --hard HEAD^  回退到上一个存档中
git reset --hard + 某个版本的id  回退到某个特定的版本

git status   查看当前的情况
git diff  查看与之前提交的代码的区别
git log  用来显示最近到最远的一次提交日志
git log --pretty=oneline  查看每一次的提价记录


新增分支dev
