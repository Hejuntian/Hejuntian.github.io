---
layout: post
title:  "使用Jekyll快速搭建个人博客"
date:   2018-01-03
categories: post/rwd
---

## 介绍

jekyll是一个静态站点生成器，会根据网页源码生成静态文件。

- 简单。无需数据库，评论功能，不需要不断更新版本，只用关注你的博客内容

- 静态。只用Markdown(或者Textile)、Liquid、HTML&CSS就可以构建可部署的静态网站
 
- 博客形态。自定义地址、分类页面、分类博客内容以及自定义的布局设计

- 使用GitHub Pages可以运行jekyll，很简单就可以完全免费的在GitHub上发布网站

## 环境配置

1.注册Github账号，并新建仓库[教程第一部分内容,照做即可](http://blog.csdn.net/p10010/article/details/51336332)<br>
2.下载安装Git,[git for Windows](http://gitforwindows.org/),[安装教程](https://jingyan.baidu.com/article/020278117cbe921bcc9ce51c.html)<br>
3.安装Ruby & Devkit, Window 系统下，我们可以使用 RubyInstaller 来安装Ruby 环境，[下载地址](https://rubyinstaller.org/downloads/),[安装教程](https://jingyan.baidu.com/article/020278117cbe921bcc9ce51c.html)<br>
4.配置jekyll环境(前提是你的电脑有Python、easy_install)<br>

安装 jekyll

 <blockquote>$ gem install jekyll</blockquote>

创建博客

 <blockquote>$ jekyll new myBlog</blockquote>

进入博客目录

 <blockquote>$ cd myBlog</blockquote>
启动本地服务

 <blockquote>$ jekyll serve</blockquote>
在浏览器里输入： http://localhost:4000，就可以看到你的博客效果了。
