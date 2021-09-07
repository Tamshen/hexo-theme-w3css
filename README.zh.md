# hexo-theme-w3css

Language: [简体中文](README.zh.md) | [English](README.md)


> 主题构建于几年前我初学编程，有一些代码可能会写的过于愚蠢...



#### 技术栈

- Hexo(静态) + Pjax + gitalk

- 内置搜索无需插件
- 没有略缩图自动随机(通过 `ejs` 实现，生成静态将会固定，重复生成将会随机)



#### 测试环境

```
time: 20210907
-------------
hexo: 5.4.0
hexo-cli: 4.2.0
os: Windows_NT 10.0.18363 win32 x64
node: 14.15.3
v8: 8.4.371.19-node.17
uv: 1.40.0
zlib: 1.2.11
brotli: 1.0.9
ares: 1.16.1
modules: 83
nghttp2: 1.41.0
napi: 7
llhttp: 2.1.3
openssl: 1.1.1g
cldr: 37.0
icu: 67.1
tz: 2020a
unicode: 13.0
```

### 使用步骤

#### 1.配置主题文件 _config.yml

**请看文件内备注与说明**



#### 2.建立搜索页面

建立一个页面，在头部加入`search: true`

(请注意，请根据你的路由情况配置主题文件，默认是`/search/`)

**source/search/index.md 示例**

```
---
title: Search
date: 2019-2-13 11:35:10
search: true
---
```



#### [可选]朋友友链页面主题

**建立一个页面 将下面复制过去即可**

**source/links/index.md 示例**

```yaml
---
title: Link
date: 2018-10-05 21:35:10
links: true #开启朋友 友链
linksdata:
-
 name: Tamshen
 info: 冉冉时光，微微细语。
 url: https://tamshen.com
 img: https://q.qlogo.cn/g?b=qq&nk=774024602@qq.com&s=100
-
 name: Github@Tamshen
 info: shen Tam
 url: https://github.com/Tamshen
 img: https://avatars.githubusercontent.com/u/33705179
---

这里是友情链接页面！这里书写是Markdown格式。

*Here is the friendly links page! Here the writing is in Markdown format.*

```





### 文章书写功能

支持自定义作者、作者网站、略缩图和评论关闭

```yaml
---
author: 自定义作者
siteurl: http://google.com/#自定义作者网站
img: https://wx3.sinaimg.cn/mw690/006bfoyggy1fkbswme506j30j60br7bh.jpg #自定义略缩图
nocomment: true #关闭评论
---
```



