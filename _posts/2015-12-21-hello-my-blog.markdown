---
layout:     post
title:      "Hello My Blog"
subtitle:   " \"追上年轻人\""
date:       2015-12-21 17:05
author:     "PtrkWang"
header-img: "img/post-bg-unix-linux.jpg"
tags:
    - 生活
---

> “Yeah It's on. ”


## 前言

2014年～2015年对我来说确实是飞速变化的一段时间，是补课的时间。

[跳过废话，直接看技术实现 ](#build)



2015 年的年末， 终于碰到了类似Markdown这类的技术，同时又看到了Gitbook，看看具体有什么变化吧！


<p id = "build"></p>
---

## 正文

接下来说说搭建这个博客的技术细节。  

正好之前就有关注过 [GitHub Pages](https://pages.github.com/) + [Jekyll](http://jekyllrb.com/) 快速 Building Blog 的技术方案，非常轻松时尚。

其优点非常明显：

* **Markdown** 带来的优雅写作体验
* 非常熟悉的 Git workflow ，**Git Commit 即 Blog Post**
* 利用 GitHub Pages 的域名和免费无限空间，不用自己折腾主机
	* 如果需要自定义域名，也只需要简单改改 DNS 加个 CNAME 就好了
* Jekyll 的自定制非常容易，基本就是个模版引擎


---

## 配置

本地调试环境需要 `gem install jekyll`，结果 [rubygem](https://rubygem.com) 的源居然被墙了……后来手动改成了我[大淘宝的镜像源](https://ruby.taobao.com)才成功
