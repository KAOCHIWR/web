# web
web 学习\
 html        
html基础语法
<!-- 
发现了这个网页也可以编写网页
<html></html>表示一个网页
<head></head>头部信息
	标题标签
		<h1></h1>.......<h6></h6>   标签大小 
	水平标签
		<hr>
		size 水平线粗细
		width 宽带 （1.百分比  2.px）
		align 对齐方式  （left right center(默认)）
	
<body></body>身体部分、
	文字颜色 ，背景颜色
		<body text='red' bgcolor='black'>文本颜色是红色,背景是黑色</body>
	<p>标签 段落自动对齐   对齐方法（align: left right center justify(两端对齐)）    换行会产生空白，会多跳一行
	<br>标签   换行 强行换，不多跳一行
	<sup></sup>上标   
	<sub></sub>下标
	<del></del>中划线
	<u></u>下划线
	<i></i>斜体
	<b></b>	<strong></strong>加粗
	常用字符字体：
	字符实体： 	&lt 小于号<		&gt 大于号>		&nbsp 等于号=		&copy 版权号
	列表
		无序列表  
			<ul>
				<li></li>
				<li></li>
			</ul>   
			常用属性： type列表图标      
							spuare 实心方块
							circle 空心园
							disc 实心园
		有序列表（可以排序）
			<ol>
				<li></li>
				<li></li>
			</ol>
			常用属性： type列表图标
							1 数字序号
							a 小写字母序号
							A 大写字母序号
							i 小写罗马序号
							I 大写罗马序号
  -->
<!DOCTYPE html> <!-- 表示是html5 -->
		
<!--
<html></html>表示一个网页
<head></head>头部信息
	标题标签
		<h1></h1>.......<h6></h6>   标签大小 
	水平标签
		<hr>
		size 水平线粗细
		width 宽带 （1.百分比  2.px）
		align 对齐方式  （left right center(默认)）
	
<body></body>身体部分、
	文字颜色 ，背景颜色
		<body text='red' bgcolor='black'>文本颜色是红色,背景是黑色</body>
	<p>标签 段落自动对齐   对齐方法（align: left right center justify(两端对齐)）    换行会产生空白，会多跳一行
	<br>标签   换行 强行换，不多跳一行
	<sup></sup>上标   
	<sub></sub>下标
	<del></del>中划线
	<u></u>下划线
	<i></i>斜体
	<b></b>	<strong></strong>加粗
	常用字符字体：
	字符实体： 	&lt 小于号<		&gt 大于号>		&nbsp 等于号=		&copy 版权号
	列表
		无序列表  
			<ul>
				<li></li>
				<li></li>
			</ul>   
			常用属性： type列表图标      
							spuare 实心方块
							circle 空心园
							disc 实心园
		有序列表（可以排序）
			<ol>
				<li></li>
				<li></li>
			</ol>
			常用属性： type列表图标
							1 数字序号
							a 小写字母序号
							A 大写字母序号
							i 小写罗马序号
							I 大写罗马序号
-->
	<head>
		<meta charset="utf-8">
		<title></title>
	</head>
	<body bgcolor="black" text="red" >
		<hr width="50%" align="left" size="20%">
		这是第一行<br>
		<h2>文本颜色是红色,背景是黑色</h2>
		这是第三行<br>
		<p align="left">居右显示</p>
		<p align="center">居中显示</p>
		<p align="justify">两端对齐</p>
		<hr width="50%" align="left" size="20%">
		<h2> 无序列表</h2>
			<ul type="square">
					<li>张三</li>
					<li>李四</li>
			</ul>
		<h2>
			<ol type="i">
				<li>张三</li>
				<li>李四</li>
			</ol>
		</h2>
	</body>
</html>                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    
