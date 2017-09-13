---
title: draft-jekyll
layout: post
categories: [markdown]
tags: [Writting]
---

### 创建文章的文件Permalink
发表一篇新文章，你所需要做的就是在 /_posts 文件夹中创建一个新的文件。文件名的命名非常重要。Jekyll 要求一篇文章的文件名遵循下面的格式：
年-月-日-标题.MARKUP
在这里，年是 4 位数字，月和日都是 2 位数字。MARKUP扩展名代表了这篇文章是用什么格式写的。下面是一些合法的文件名的例子：
2011-12-31-new-years-eve-is-awesome.md
2012-09-12-how-to-write-a-blog.textile

------------

### 使用草稿
草稿是没有日期的文章。它们是你还在创作中而暂时不想发表的文章。想要开始使用草稿，你需要在网站根目录下创建一个名为 _drafts 的文件夹（如在目录结构章节里描述的），并新建你的第一份草稿：

|-- _drafts/
|   |-- a-draft-post.md
为了预览你拥有草稿的网站，运行带有 --drafts 配置选项的 jekyll serve 或者 jekyll build。此两种方法皆会将该草稿的修改时间赋值给草稿文章，作为其发布日期，所以你将看到当前编辑的草稿文章作为最新文章被生成。

[48 个你需要知道的 Jekyll 使用技巧]https://crispgm.com/page/48-tips-for-jekyll-you-should-know.html


http://jekyllcn.com/docs/home/

https://mba811.gitbooks.io/jekyll-study/content/index.html

$ git add .
$ git commit -a -m 'add a post.'
$ git push origin master
