# 图片查看弹出框

## 参数

linkTitle: 点击图片提示信息，默认为 '点击查看原图' 
direction: 箭头显示方向，水平方向 (horizontal) 和垂直方向 (vertical)，默认为 'horizontal'

## 如何使用

1、导入

```
  	<link rel="stylesheet" href="css/jquery.imagebox.css" />
	<script type="text/javascript" src="js/jquery.imagebox.js"></script>
```

2、使用

```
	$('element').imagebox();

	$('element').imagebox({
		linkTitle: '查看原图',
		direction: 'vertical'
	});
```
