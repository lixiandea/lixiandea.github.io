---
title: My first hexo blog about how to deploy hexo
date: 2019-12-05 23:20:00
tags: 配置自己的hexo博客； 配置ssh
---
# 为什么写博客、
在学生生活中，无聊是最为恐怖的事情，那么怎么避免太过无聊的事情呢，当然是写点什么记录自己的生活，但是日记又太过无聊（我的字丑），而跟风写一下博客就还行。
# 怎么配置hexo博客
写博客当然是要找一个教程比较多，起点低的方法，其中hexo博客要求很低（windows下面，有一个github账号就可以完成相应的配置），其次hexo的工作流也是一个和未来找工作比较相关工作流（git流程），所以使用hexo进行相应的配置。下面是正式配置过程
## 环境安装
我是在windows下进行的配置，所以相对来说都是有界面的比较简单，总的来说需要以下几个windows不自带的东西
1. git
2. npm
3. 相应的markdown编辑软件（我用的vscode+markdown all in one）
下面进行相应的安装介绍
### git 安装
简单来说就是按照官方给的教程一步步来[安装git](https://git-scm.com/book/zh/v2/%E8%B5%B7%E6%AD%A5-%E5%AE%89%E8%A3%85-Git),因为git之前我已经搞过了，所以忘了具体的流程，需要注意到的是windows下的不一定会自动添加路径，有可能需要自己添加，如何检查自己的git是否安装好，只需要打开powershell（powershell是不需要折腾的windows最好的命令行软件），输入：`git`要是提示不是可执行的命令行，那么就应该去找一下路径手动配置一下，总的来说是简单的。
### npm安装
这或许就是windows广泛使用的原因了，就是基本提供了可视化的才是windows的软件，npm就是按照[安装指导]()安装就完事
