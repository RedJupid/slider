# slider
JS原生轮播图插件
## 效果图   
![效果图](result.jpg)
## Demo
演示地址：[demo](https://redjupid.github.io/slider/demo.html)
## Quick Start
var mySlider = new MySlider('slide');`'slide'`为元素id
```html
<!doctype html>
<html>
<head>
	<meta charset="UTF-8">
	<title>轮播图</title>
	<style type="text/css">
	#slide{
		width: 520px;
		height: 280px;
		margin: 0 auto;
	}
	</style>
</head>
<body>
	<div id="slide">
		<div>
			<img src="1.jpg" alt="">
			<img src="2.jpg" alt="">
			<img src="3.jpg" alt="">
			<img src="4.jpg" alt="">
			<img src="5.jpg" alt="">
		</div>
	</div>
</body>
<script src="mySlider.js"></script>
<script>
	var mySlider = new MySlider('slide');
</script>
</html>
```
