---
title: test
date: 2025-04-07 14:41:30
tags:
---
This is a test.

## BIGGGG TITLE
    content


### smaller title
content

*content*
**content**

## TITLE STILL
```
code
code
```

{% notel default fa-info 信息 %}
换行测试
换行测试
换行测试
{% endnotel %}
 
{% notel blue 提示 %}
换行测试
换行测试
换行测试
{% endnotel %}
 
{% notel red 自定义标题 %}
换行测试
换行测试
换行测试
{% endnotel %}

{% note %} 默认 提示块标签 {% endnote %} {% note default %} default 提示块标签
{% endnote %} {% note primary %} primary 提示块标签 {% endnote %} {% note
success %} success 提示块标签 {% endnote %} {% note info %} info 提示块标签 {%
endnote %} {% note warning %} warning 提示块标签 {% endnote %} {% note danger %}
danger 提示块标签 {% endnote %} {% note red fa-bolt%} 自定义提示块标签 {%
endnote %}

{% btn regular::example::https://sol-long.github.io/::fa-solid fa-play-circle %}

{% folding blue::Folding 测试： 点击查看更多 %}
 
啊啊啊啊啊
 
{% note danger  %}
danger 提示块标签
{% endnote %}
 
{% note tip  %}
tip 提示块标签
{% endnote %}
 
{% endfolding %}

{% tabs 页面内不重复的ID %}
 
<!-- tab 栏目1名称 -->
 
内容
 
<!-- endtab -->
<!-- tab 栏目2名称 -->
 
内容
 
<!-- endtab -->
 
{% endtabs %}

THE END