---
title: 关于 MarkDwon 语法
abbrlink: 26827
date: 2022-03-05 09:08:29
tags:
---
# 一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题

## 区块引用
- 在段落的第一行最前面加上">"
> I don't mind being alone. I just don't want to be insignificant.
> 我不介意孤身独行，却不想活得微不足道。
- 区块引用可以嵌套(使用方法">">>")
> I don't mind being alone. I just don't want to be insignificant.
>> 我不介意孤身独行，却不想活得微不足道。
- 区块引用也可以套用其他MarkDown语法,包括加粗、列表、代码区块等:
- --
**Hello**
**World
*Hello
*World

## 列表
- MarkDown支持有序列表和无序列表
- 无序列表使用星号、加号或是减号作为列表标记，效果一样：
> 1无序列表
* Yes
* No
+ Yes
+ No
> 有序列表则使用数字接着一个英文句点：
1. Yes
2. No
3. Yes
4. No

## 代码区块
- 要在 Markdown 中建立代码区块很简单，只要简单地缩进 4 个空格或是 1 个制表符就可以
> 代码区块
    Hello World


## 分割线
- 一行中用三个以上的星号、减号、底线来建立一个分隔线，行内不能有其他东西 中间可以插空格
***
---
* * *

## 区段元素

1. **链接**
字段>方块括号后面紧接着圆括号并插入网址链接
***
[链接备注]（放入链接）
---
[MyBlog](https://hkzmai.top/)

2. **强调作用**
> Markdown 使用星号（*）和底线（_）作为标记强调字词的符号
***
- **粗体** 
> （** ** 中间填写需要加粗的字段）
- ~~删除线~~
>(~~ ~~ 中间填写需要的字段) 
- 空格
>Markdown语法会忽略首行开头的空格，要体现出首行开头空两个的效果，可以使用英文输入状态下的空格空
>>        Markdown语法会忽略首行开头的空格，要体现出首行开头空两个的效果，可以使用英文输入状态下的空格空
3. 行内标记
>行内标记用反引号把它包起来`` （英文输入状态下esc下面那个键）
* 行内标记
>Markdown语法会忽略首行开头`空格`，要体现出首行开头空两个的效果，可以使用`英文`输入状态下的空格空
4. 插入图片
>![Alt text] (图片链接 "optional title") []中间不能留空()
>>Alt text：图片的Alt标签，用来描述图片的关键词，可以不写。最初的本意是当图片因为某种原因不能被显示时而出现的替代文字，后来又被用于SEO，可以方便搜索引擎根据Alt text里面的关键词搜索到图片。 图片链接：可以是图片的本地地址或者是网址。"optional title"：鼠标悬置于图片上会出现的标题文字，可以不写。
>>>[出处：简书清风Python](https://www.jianshu.com/p/280c6a6f2594)
5. 插入本地图片
>![avatar] (/home/picture/1.png)
>>只需要在基础语法的括号中填入图片的位置路径即可，支持绝对路径和相对路径.不灵活不好分享，本地图片的路径更改或丢失都会造成markdown文件调不出图。
>>>[出处：简书清风Python](https://www.jianshu.com/p/280c6a6f2594)
6. 插入网络图片
>![avatar] (http://baidu.com/pic/doge.png)
>>只需要在基础语法的括号中填入图片的网络链接即可，现在已经有很多免费/收费图床和方便传图的小工具可选。
>>>将图片存在网络服务器上，非常依赖网络。[出处：简书清风Python](https://www.jianshu.com/p/280c6a6f2594)
***
<div align=center>
<img src="https://cdn.jsdelivr.net/gh/chen-xing/figure_bed_02/cdn/20220305101353718.jpg" width="500px" height="300px" />
</div>





