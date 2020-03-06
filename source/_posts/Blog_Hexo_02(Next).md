---
title: Next
date: 2020-03-06 14:14:03
categories:
    - '博客搭建'
tags:
    - '博客搭建'
    - 'Hexo'
    - 'Next'
description:
    Hexo(Next)主题基本安装与使用。
---

# 参考信息
> http://theme-next.iissnan.com

# 安装 NexT

## 主题下载
```
$ cd [blogDir]
$ git clone https://github.com/iissnan/hexo-theme-next themes/next
```

## 效果预览
1. 切换主题(Hexo:_config.yml)
```
#them: landscape
theme: next
```
2. 清除&预览
```
hexo clean
hexo server --debug
```


# 主题设定
## 选择 Scheme
```
  # Schemes
  #scheme: Muse
  #scheme: Mist
  #scheme: Pisces
  scheme: Gemini
```

## 设置菜单
1. 配置菜单
```
# 配置菜单
menu:
  home: 首页
  archives: 归档
  categories: 分类
  tags: 标签
  about: 关于
  search: 搜索
  commonweal: 公益404
  something: 有料

# 配置菜单icon
menu_icons:
  enable: true
  # Icon Mapping.
  home: home
  about: user
  categories: th
  tags: tags
  archives: archive
  commonweal: heartbeat

# 综合配置
menu:
  home: / || home
  #about: /about/ || user
  tags: /tags/ || tags
  categories: /categories/ || th
  archives: /archives/ || archive
  #schedule: /schedule/ || calendar
  #sitemap: /sitemap.xml || sitemap
  #commonweal: /404/ || heartbeat
```

## 设置 侧栏
```
sidebar:
  position: left
```