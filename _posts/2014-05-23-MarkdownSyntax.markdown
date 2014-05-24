---
layout: post
title:  "Markdown 语法对照"
date:   2014-05-24 14:46:42
categories:  bug
---

Markdown 常用语法：

*  标题

	markdown 形式

    {% highlight ruby %}
	
	这里为H1标题
	============
	这里为H2标题
	------------

    或者

    # 这里为H1标题
    
    ##这里为H2标题

    这里#可拓展到6个，也就是到 H6

    {% endhighlight %}

*  区块
    
    markdown 形式

    {% hightlight ruby %}

    > # 段落内 H1
    > 段落内容
    > * 段落列表
    >
    
    {% endhighlight %}