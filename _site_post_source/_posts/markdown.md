---
title: Markdown格式&语法 测试
date: 2018-10-04 17:07:14
---

# 1级标题
## 2级标题
### 3级标题
#### 4级标题
##### 5级标题
###### 6级标题


### 富文本样式

*斜体*
**加粗**
***加粗+斜体***
~~删除线~~



上标<sup>a</sup>   
下标<sub>a</sub>

键盘
<kbd>Ctrl</kbd> + <kbd>Alt</kbd> + <kbd>A</kbd>

分隔符

***
---
---




邮箱链接
<xxx@outlook.com>




### 引用

> hello world!
hello world!
hello world! 



### 引用多层嵌套 段落

> aaaaaaaaa
> > bbbbbbbbb
> >
> > > cccccccccc

### 行内标记
标记之外`hello world`标记之外

### 代码块

``` html
<div>   
    <div>1</div>
    <div>2</div>
    <div>3</div>
</div>
```

``` javascript
for (var i = 0; i < 5; i++) {
    num+=i;
}
console.log(num);
```



### 链接和图片



[百度1](http://www.baidu.com/" 百度一下")





![](https://tvax1.sinaimg.cn/wap800/006bfoyggy1gcb4h0htybj31hc0u0ta9.jpg '描述')

插入图片带有链接

[![](https://tvax1.sinaimg.cn/wap800/006bfoyggy1gcb4h0htybj31hc0u0ta9.jpg '百度')](http://www.baidu.com)  



### 有序

1. one
2. two
3. three

### 无序

* one
* two
* three

### 序表嵌套

1. one
    1. one-1
    2. two-2
2. two 
    * two-1
    * two-2

### 序表嵌套代码块

* one

    var a = 10;     // 与上行保持空行并 递进缩进
    [x] 选项一var a = 10;     // 与上行保持空行并 递进缩进



### 任务列表

- 选项列表
- [x] 选项一
- [ ] 选项二
    - [ ] 选项二.1
    - [ ] 选项二.1
        - [ ] 选项二.1.1
        - [ ] 选项二.1.1



- [ ]表示该项目未完成
- [x]表示该项目已完成




### 表格 
表格自适应：
``` javascript
//jQuery
//判断是否有表格  表格需要自适应
if($("table").html()){
    $("table").wrap("<div style='overflow-x: auto;'></div>");
}
//javascript
[].slice.call(document.querySelectorAll('table')).forEach(function(el){
    var wrapper = document.createElement('div');
    wrapper.style.overflowX="auto";
    el.parentNode.insertBefore(wrapper, el);
    el.parentNode.removeChild(el);
    wrapper.appendChild(el);
})

```



|    a    |       b       |      c     |
|:-------:|:------------- | ----------:|
|   居中  |     左对齐    |   右对齐   |
|=========|===============|============|



### 脚注 footnote

使用 Markdown[^1]可以效率的书写文档, 直接转换成 HTML[^2], 你可以使用 Typora[^T] 编辑器进行书写。

[^1]:Markdown是一种纯文本标记语言
[^2]:HyperText Markup Language 超文本标记语言
[^T]:NEW WAY TO READ & WRITE MARKDOWN.


### 表情
表情(emoji)
参考网站: https://www.webpagefx.com/tools/emoji-cheat-sheet/
😆😊😃😃