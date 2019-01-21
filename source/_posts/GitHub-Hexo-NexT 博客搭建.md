---
title: GitHub+Hexo+NexT 博客搭建
date: 2019-01-17 21:41:02
update: 2019-01-21 23:10:12
comments: true
tags: [GitHub, 博客]
categories: 博客
top: 10
---

# 主题设置

## 设置侧栏头像

打开主题的配置文件， 通过将 avatar 设置成头像的链接地址。

- 完整的互联网 URL 如：`https://www.example.com/avatar.jpg`
- 站点内地址如：若图片存放在 ource/images/ 目录下，则是 /images/avatar.jpg

```yml
avatar: url
```

## 设置动态背景

打开主题配置文件，将 canvas_nest 设置项改为 true ，此种方法只适用于 NexT 主题在 5.1.1 以上版本

```yml
canvas_nest: true
```

# 文章模板

## Front-matter

写在文章开头，用于指定个别文件变量。

| 参数 | 描述 | 值 |
|---|---|---|
| title | 文章标题 |
| date | 创建时间 |
| updated | 更新时间 |
| comments | 启用评论 | true/false |
| tags | 设置文章标签 |
| categories | 对文章分类 |
| premalink | 设置文章网址格式 |
| layout | 建立布局 |