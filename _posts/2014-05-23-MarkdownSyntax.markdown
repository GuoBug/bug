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

    效果 
> H1:
> 这里为 H1 标题
> ============
> 这里为 H2 标题
> ------------

*  区块
    
    markdown 形式

```
    > # 段落内 H1
    > 段落内容
    > * 段落列表
    >
```
*  列表
    
    markdown 形式

    1. 无序列表使用星号、加号或是减号作为列表标记

    {% highlight ruby %}

    * 段落列表
    等价于
    - 列表
    等价于 
    + 列表
    
    {% endhighlight %}

    2. 序列表使用数字接着一个英文句点

    {% highlight ruby %}

    1. 内容
    2. 内容
    3. 内容
    
    {% endhighlight %}