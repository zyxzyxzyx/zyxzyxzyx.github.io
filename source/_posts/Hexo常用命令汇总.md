---
title: Hexo常用命令汇总
date: 2019-08-12 19:55:02
tags: [Hexo, 常用命令]
categories: Hexo
copyright: true
top: 95
---

# Hexo常用命令

## 常见命令

```bash
hexo new "postName" #新建文章
hexo generate #生成静态页面至public目录
hexo server #开启预览访问端口（默认端口4000，'ctrl + c'关闭server）
hexo deploy #部署到GitHub
hexo help  # 查看帮助
hexo version  #查看Hexo的版本
```

## 缩写：

```bash
hexo n == hexo new
hexo g == hexo generate
hexo s == hexo server
hexo d == hexo deploy
```

## 组合命令：

```bash
hexo s -g #生成并本地预览
hexo d -g #生成并上传
```

# Hexo常用的命令行：
```bash
hexo help #查看帮助
hexo init #初始化一个目录
hexo new "postName" #新建文章
hexo new page "pageName" #新建页面
hexo generate #生成生成静态网页，可以在 public 目录查看整个网站的文件
hexo server #本地预览，'Ctrl+C'关闭
hexo deploy #部署.deploy目录
hexo clean #清除缓存，强烈建议每次执行命令前先清理缓存，每次部署前先删除 .deploy 文件夹
    
简写：

hexo n == hexo new
hexo g == hexo generate
hexo s == hexo server
hexo d == hexo deploy
```