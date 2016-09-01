# 入门文献列表 

## 简介
本文档罗列以下研究方向的一些典型、部分经典的入门资料:
* MTD 
* SDN网络 
* SDN安全
* 虚拟网安全

## 参加步骤

* 在 GitHub上`fork`到自己的仓库，如 `user/ireadlist`，然后`clone`到本地，并设置用户信息。
```
$ git clone git@github.com:chengguozhen/ireadlist.git
$ cd ireadlist
$ git config user.name "yourname"
$ git config user.email "your email"
```
* 修改代码后提交，并推送到自己的仓库。
```
$ #do some change on the content
$ git commit -am "Fix issue #1: change helo to hello"
$ git push
```
* 在 GitHub 网站上提交 pull request。

* 定期使用项目仓库内容更新自己仓库内容。
```
$ git remote add upstream https://github.com/chengguozhen/ireadlist
$ git fetch upstream
$ git checkout master
$ git rebase upstream/master
$ git push -f origin master
```