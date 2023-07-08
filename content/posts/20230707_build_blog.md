---
title: "建一个博客需要几个步骤"
date: 2023-07-07
draft: false
tags: ["blog", "生活"]
slug: "build-blog"
---

> 希望自己能多多使用这个博客。记录自己的生活。

上次搭博客还是2023年初，一晃半年过去了。重新捡起来的时候，竟然一丁丁都想不起来该怎么办了。
这回聪明一点，记录一下过程。万一还要建站就能参考。

主体是用 hugo + github page 搭起来的。

## Step 1. 选择一个喜欢的模版

我用的是[zozo](https://github.com/varkai/hugo-theme-zozo)。看起来很简单清爽。

## Step 2. Setup Github

参考这篇[blog](https://www.pseudoyu.com/zh/2022/05/29/deploy_your_blog_using_hugo_and_github_action/) 里**自动发布** 那一截。特别好用。
能够做到push 代码到github，博客就自动发布了。

## Step 3. 购买域名 + DNS Setup
还是上篇[博客](https://www.pseudoyu.com/zh/2022/05/29/deploy_your_blog_using_hugo_and_github_action/)。
我这个域名是39块钱 3年，四舍五入不要钱哈哈。

## Step 4. 写一篇博客
随便写写。方便修改样式。

## Step 5. 留言系统 Twikoo + Railway
参考的是友邻这篇[blog：在静态博客里添加Twikoo评论系统，并配置邮箱和TG通知](https://thirdshire.com/post/twikoo-tutorial/). Railway现在要收费了，每个月五块钱。

## Step 6. 根据自己的喜好进行修改
主要是修改了 留言部分 的[css](https://github.com/saally/blog/blob/master/themes/hugo-theme-zozo/static/css/twikoo.css)，与博客theme一致。删去了很多不必要的元素。
同时默认comment部分为隐藏，不影响阅读。

---
