---
title: '利用git提交代码'
date: 2021-07-15 18:42:44
tags: []
published: true
hideInList: false
feature: 
isTop: false
---
安装git:sudo apt-get install git
输入命令:git --version 可查看当前git版本
配置用户名和邮箱:
$ git config --global user.name "Your Name"  
$ git config --global user.email "email@example.com"  
使用 --global 修饰后设置的全局的用户,如果设置单个项目的用户,可cd到项目根目录下,执行如下命令
$ git config user.name "Your Name"
$ git config user.email "email@example.com"
使用命令:git config --list 可查看当前用户信息以及其他的一些信息
### 建立本地git仓库
创建了一个空的本地仓库： git init
将项目的所有文件添加到缓存中:git add .
将缓存中的文件Commit到git库：git commit -m "注释"
### 建立远程库
$ git remote add origin https://gitee.com/penkai/simpost.git
$ git push origin master