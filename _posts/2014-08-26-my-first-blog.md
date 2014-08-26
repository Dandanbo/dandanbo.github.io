---
layout: post
keywords: blog
description: blog
title: "My First Blog"
categories: [PlainBlog]
tags: [PlainTags]
---
{% include codepiano/setup %}

这是一篇练习使用ruby控制文章样式的文章，很基础，很简单。


## 1.普通的代码样式布局，下面是一行代码：

	String userName = "Dandanbo";
	
上面这一行代码结束了，再试试小标题大号字体

## 2.使用高亮布局样式

在写一段代码，使用高亮样式：

{% highlight ruby %}
while(true)
{
	Log.GetLogger().Info("I love zhezhe");
}
{% endhighlight %}

## 3.试试超链接的样式

这是我的[github个人博客](http://dandanbo.github.io)，这就是一个超链接了。
这个很简单的练习就结束了 O(∩_∩)O
