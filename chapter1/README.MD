##基本的用法

###创建远程github公用库
github.com -> New repository -> Repository name :  xxx ; Public -> Create repository

##拉取或通过远程github

###拉取方式
```
1.git clone git@github.com:nihaoqkl/xxx.git 

```


###同步方式
```
mkdir xxx
cd xxx
git init
vim README.MD
git add .
git status
git commit -m "add readme.md"
git remote add origin git@github.com:nihaoqkl/xxx.git
git push -u origin master:master //master:master  本地分支:远程分支
```

