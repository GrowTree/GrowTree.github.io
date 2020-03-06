---
title:
    Hexo
date:
    2020-03-06 09:25:03
categories:
    - '博客搭建'
tags:
    - '博客搭建'
    - 'Hexo'
description:
    Hexo博客引擎基本安装与使用。
---

# 参考信息
> https://hexo.io/zh-cn/docs

# hexo 安装
## 安装前提
- Node.js (Node.js 版本需不低于 8.10，建议使用 Node.js 10.0 及以上版本)
- Git

## 安装
- npm instll hexo-cli -g

## hexo 尝试运行
- hexo init [dir]
- hexo server

---

# Hexo 命令
## Hexo 常用命令
- hexo init [dir]
- hexo server
- hexo new
- hexo clean
- hexo generater
- hexo deploy

---

# Hexo 进阶
## hexo 内容构成
- 目录结构
| 文件 | 文件名称 | 文件作用 |
| :-: | :-: | :-: |
| _config.yml | 站点配置 文件 | 网站的 配置 信息|
| package.json | npm包管理 文件 | Hexo应用程序的信息|
| scaffolds  | 模版 文件夹 | Hexo 会根据主题来生成静态页面|
| source | 资源 文件夹 | 存放用户资源的地方|
| themes | 主题 文件夹 | Hexo 会根据主题来生成静态页面|

- 网站配置(_config.yml)
| 参数 | 描述 |
| :-: | :-: |
| title	| 网站标题
| subtitle	| 网站副标题
| description	| 网站描述
| keywords	| 网站的关键词。使用半角逗号 , 分隔多个关键词。
| author	| 您的名字
| language	| 网站使用的语言
| timezone	| 网站时区。Hexo 默认使用您电脑的时区。请参考 时区列表 进行设置，如 America/New_York, Japan, 和 UTC 。一般的，对于中国大陆地区可以使用 Asia/Shanghai。

### 内容分类


### 部署
1. 安装 hexo-deployer-git
'''
npm install hexo-deployer-git --save
'''

2. 修改配置 (_config.yml)
deploy:
  type: git
  repo: <repository url> #https://bitbucket.org/JohnSmith/johnsmith.bitbucket.io
  branch: [branch]
  message: [message]


## hexo 主题更换

---