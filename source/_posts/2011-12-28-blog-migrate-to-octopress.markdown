---
layout: post
title: "blog 迁移到 octopress"
date: 2011-12-28 09:32
comments: true
categories: notes
---

很久没有写blog了，这次是我的aws一周年试用到期了，准备换一个空间继续写。wordpress使用了一年左右，还是感觉不爽，不够geek。原来是先写rst格式文件，生成html然后再到Wordpress中发布，主要还是有洁癖，不喜欢所见即所得编辑器生成的html代码，相当凌乱。在v2ex上看到讨论jekll模版引擎来写文章，mrakdown我不熟悉，blog发布的原理与movbletype。当年我就想，如果有一个blog程序,有movable type的静态文件生成能力，又能不用写html发布,那就完美了。octopress刚好能满足这种需求，足够简洁， 静态文件发布，爱不失手。



主要改变：
 
1. wordpress 迁移到otcopress,原来文件进行了迁移。

2. 熟悉git ,原来是使用hg，主要原因是bitbucket当时不支持git.git使用起来真是相当爽，比hg还好用.相比git ,svn、tfs这类简直没法用.

3. 域名服务器从godaddy转到国内的dnspod,更改生效的时间相当快，改域名后很短时间内就可以生效。

4. 使用github 的pages服务，并设置了CNAME映射，blog.xiangjian.info就映射到xiangjian.github.com.

