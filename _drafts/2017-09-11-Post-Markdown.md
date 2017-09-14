---
title: post markdown
layout: post
---


# 1级标题   <small>副标题</small>
## 2级标题   <small>副标题</small>
### 3级标题   <small>副标题</small>
#### 4级标题   <small>副标题</small>
##### 5级标题   <small>副标题</small>
###### 6级标题   <small>副标题</small>
<!-- <h1>1级标题 <small>副标题</small></h1>
<h2>2级标题 <small>副标题</small></h2>
<h3>3级标题 <small>副标题</small></h3>
<h4>3级标题 <small>副标题</small></h4>
<h5>3级标题 <small>副标题</small></h5>
<h6>3级标题 <small>副标题</small></h6> -->

*single asterisks* 斜体文字 <br>
**double asterisks** 粗体文本  <br>
如果要在文字前后直接插入普通的星号或底线，你可以用反斜线：\*this text is surrounded by literal asterisks\*   <br>
如果要标记一小段行内代码，你可以用反引号把它包起来, 例如：Use the `printf()` function  <br>

<p align="center"> 将段落按左、中-center、右-right对齐 　 </p>
<b>粗体文本</b> <br>
<i>斜体文本</i> <br>
<u>下划线文本</u> <br>
<big>大一号字体</big> <br>
<small>小一号字体</small> <br>
<strong>加强显示字体</strong> <br>
<em>强调字体</em> <br>
<q>内联引用</q> <br>
<del> 被删除文字 </del> <br>
<font size="3" color="red">设置字体大小从1到7(1最小)，颜色使用名字或RGB的十六进制值</font> <br>
<font color = "00ff00">字體顏色</font> <br>
<font size="1">最小字體</font> <br>
<sup>上标字</sup> <br>
<sub>下标字</sub> <br>

### Code @ ruby
```ruby
puts "Hello World!"
```
### Code @ python
``` python
puts "Hello World!"
```

<hr>
this is a link
[the documentation here](https://help.github.com/articles/user-organization-and-project-pages/).

this is a image

![](http://upload-images.jianshu.io/upload_images/259-0ad0d0bfc1c608b6.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
## Table Example

| Tables        | Are           | Are           | Cool     |
| ------------- |:-------------:|:-------------:|---------:|
| col 111111    |1              | Hello         | $1600    |
| col 222       |2              | Hello         |   $12    |
| col 3         |3              | Hello         |    $1    |

dog | bird | cat
----|------|----
foo | foo  | foo
bar | bar  | bar
baz | baz  | baz

* 无序列表1 <ul></ul> <li></li>  
* 无序列表2
  * 第二级无序列表
  *

1. 有序列表1 <ol></ol> <li></li>
2. 有序列表2

<pre>
  has_many :favorites
  has_many :favorited_products, :through => :favorites, :source => :product
</pre>

> This is the first level of quoting.
>
> > This is nested blockquote.
>
> Back to the first level.

*   A list item with a blockquote:
    > This is a blockquote
    > inside a list item.
