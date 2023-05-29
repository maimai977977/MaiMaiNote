---
title: 初识Bootstrap框架
abbrlink: 22186
date: 2022-03-05 11:37:22
tags:
---
# Bootstrap框架
>Bootstrap，来自 Twitter，是目前最受欢迎的前端框架。Bootstrap 是基于 HTML、CSS、JAVASCRIPT 的，它简洁灵活，使得 Web 开发更加快捷。
>>**框架下载**[Bootstrap中文网](https://www.bootcss.com/)
## 引用
```html 
<meta name="viewport" content="width=device-width,initial-scale=1">
<!--viewport 主要用于实现对不同屏幕分辨率的支持-->
```
***
```html
<link rel="stylesheet" type="text/css" href="css/bootstrap.min.css" />
<!--bootstrap 基于jquery 先引用jquery  再引用js-->
```
>简单的布局
```html
<div class="container">
		<div class="row">
			<!--默认平分12份 自由按份组合  行row 列col-->
			<div class="col-md-1">col-md-1</div>
			<div class="col-md-1">col-md-1</div>
			<div class="col-md-1">col-md-1</div>
			<div class="col-md-1">col-md-1</div>
			<div class="col-md-1">col-md-1</div>
			<div class="col-md-1">col-md-1</div>
			<div class="col-md-1">col-md-1</div>
			<div class="col-md-1">col-md-1</div>
			<div class="col-md-1">col-md-1</div>
			<div class="col-md-1">col-md-1</div>
			<div class="col-md-1">col-md-1</div>
			<div class="col-md-1">col-md-1</div>
		</div>
		<!--左8 右4-->
		<div class="row">
			<div class="col-md-8">col-md-8</div>
			<div class="col-md-4">col-md-4</div>
		</div>
		<!--平分3份-->
		<div class="row">
			<div class="col-md-4">col-md-4</div>
			<div class="col-md-4">col-md-4</div>
			<div class="col-md-4">col-md-4</div>

		</div>
		<!--平分2份-->
		<div class="row">
			<div class="col-md-6">col-md-6</div>
			<div class="col-md-6">col-md-6</div>


		</div>
	</div>
```
### 😀深入学习😀Bootstrap😀
>[菜鸟教程](https://www.runoob.com/bootstrap/bootstrap-tutorial.html)
***
<div align=center>
<img src="https://cdn.jsdelivr.net/gh/chen-xing/figure_bed_02/cdn/20220305120612108.jpg" width="500px" height="300px" />
</div>
