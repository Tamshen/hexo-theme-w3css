# hexo-theme-w3css

Language: [简体中文](README.zh.md) | [English](README.md)


> The theme was built a few years ago when I first learned to program, and some of the code may be written too stupid...



#### Technology Stack

- Hexo(static) + Pjax + gitalk

- Built-in search without plugins
- No thumbnail auto-randomization (implemented by `ejs`, generation of static will be fixed, repeated generation will be random)



#### test environment

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

### Steps to use

Theme reference file(source)：[Link->](https://github.com/Tamshen/hexo-theme-w3css/tree/generate/_site_post_source)

#### 0. Clone or download this theme to the themes of hexo

#### 1. Configure the theme file

See  notes and instructions in the theme **`_config.yml`** file.



#### 2. Create a search page



Create a page and add `search: true` to the header

(Please note, please configure the theme file according to your routing, the default is `/search/`)

**source/search/index.md example**

```
---
title: Search
date: 2019-2-13 11:35:10
search: true
---
```



#### [optional] friend link page theme

**Create a page Just copy the following over**

**source/links/index.md example**

``` yaml
---
title: Link
date: 2018-10-05 21:35:10
links: true #Enable friend friendly links
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

Here is the friendly links page! Here the writing is in Markdown format.

```





### Article writing features

Support for custom authors, author sites, thumbnails and comments off

```yaml
---
author: custom author
siteurl: http://authorsite.com/ #author sites
img: https://wx3.sinaimg.cn/mw690/006bfoyggy1fkbswme506j30j60br7bh.jpg #custom thumbnails
nocomment: true #Close comments
---
```
