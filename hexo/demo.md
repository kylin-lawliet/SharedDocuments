---
title: 文章格式示例
date: 2019-12-23 10:24:34
tags: [hexo] #标签
categories: hexo笔记 #分类
favorite: hexo #收藏夹
top: true #置顶 true或者1
original: false #是否显示文末版权信息
toc: true #是否隐藏文章目录
toc_list_number: true #是否显隐藏目录序号
permalink: demo
---

本篇文章主要是记录写文章时各种样式写法示例,暂时记录一些使用过的(此处为摘要)
<!-- more -->

# 标题排版 标题一
## 标题排版 标题二 
### 标题排版 标题三
##### 标题排版 标题四
> 1. 该文章的源文件地址在[在共享文件仓库][1]文件夹路径:/hexo/demo.md

## 内容排版
2. 无样式

> 3. 加背景

>> 4.双层背景

> - 5.有背景列表标记
>  - 有背景列表标记

- 6.无背景列表标记
    - 如果设置子列表中间不可以有空行
    
``` js
function admin(e) {
// 代码块
}
```


## 字体样式
> **加粗字体** 
> ***斜体字体***
> ***[斜体字体]***
> <code>添加字体高亮一</code> 
> `添加字体高亮二` 



## 各种连接写法
> 1. <https://www.kylin-blackcat.com/> 
> 2. [地址](www.kylin-blackcat.com)
> 3. [地址][0]

## 表格
>居中 **`:-:`**，右对齐**`-:`**，其它**`-`**。表头也不要留空，填上`-`提高兼容性。
>经测试上方样式并没有起作用

-|表头|　　表头　　|表头|表头|表头|　　　　表头　　　　
:-:|-|-|-:|:-:|:-:|-
1|内容|内容|x|√|—|内容
2|内容|内容|内容|内容||内容



## 引入图片
> ![引入图片](/apple-touch-icon.png)



[0]:https://www.kylin-blackcat.com/
[1]:https://github.com/kylin-lawliet/SharedDocuments/



