---
layout: post
title: 导入本地代码到github
date: 2012-12-08 10:11
comments: true
categories: note
---

最近把本地得一个项目导入到github，下面是将代码嵌入github得过程。


1. 在github中创建一个项目，获得类似这样得url git://github.com/youruser/somename.git
如果您本地得项目已经使用git管理，请忽略2-3步。

2. 在本地项目得根目录，运行git init ,并在.gitignore中写入排除的文件或目录。

3. 将本地代码加入版本库(可以执行以下代码git add . git commit -m 'initial commit comment')。

4. 添加远程得地址  git remote add origin [第一步得地址]

5. 推送代码道远程分支中: git push origin master
