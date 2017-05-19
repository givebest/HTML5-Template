# HTML5 常用 meta 标签

HTML5可复用模板，尽可能保持简洁。

### DOCTYPE

	<!DOCTYPE html>

### charset

	<meta charset="utf-8">

### lang
	
	<!-- google -->
	<html lang="zh-CN"> 

> [网页头部的声明应该是用 lang="zh" 还是 lang="zh-cn"？](https://www.zhihu.com/question/20797118)


### 优先使用 IE 最新版本和 Chrome

	<meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1">

### 360 使用 WebKit

	<meta name="renderer" content="webkit">

### 移动优先

	<meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1, user-scalable=no">

### 禁止自动转换为电话号码

	<!-- google -->
    <meta name="format-detection" content="telephone=no">

### Favicon icon

	<!-- Yahoo -->
    <link rel="shortcut icon" href="https://s.yimg.com/rz/l/favicon.ico">

### iOS 添加网页放到主屏幕展示的图标
	
	<!-- Amazon -->
	<link rel="apple-touch-icon" href="apple-touch-icon.png">

### 百度禁止转码

	<meta http-equiv="Cache-Control" content="no-siteapp">

### 其它

	<meta name="viewport" content="width=device-width, initial-scale=1, user-scalable=no" />
	<meta name="apple-mobile-web-app-capable" content="yes" />
	<meta name="apple-mobile-web-app-status-bar-style" content="black" />
	<meta name="format-detection"content="telephone=no, email=no" />
	<meta name="viewport" content="width=device-width, initial-scale=1, user-scalable=no" />
	<meta name="apple-mobile-web-app-capable" content="yes" /><!-- 删除苹果默认的工具栏和菜单栏 -->
	<meta name="apple-mobile-web-app-status-bar-style" content="black" /><!-- 设置苹果工具栏颜色 -->
	<meta name="format-detection" content="telphone=no, email=no" /><!-- 忽略页面中的数字识别为电话，忽略email识别 -->
	<!-- 启用360浏览器的极速模式(webkit) -->
	<meta name="renderer" content="webkit">
	<!-- 避免IE使用兼容模式 -->
	<meta http-equiv="X-UA-Compatible" content="IE=edge">
	<!-- 针对手持设备优化，主要是针对一些老的不识别viewport的浏览器，比如黑莓 -->
	<meta name="HandheldFriendly" content="true">
	<!-- 微软的老式浏览器 -->
	<meta name="MobileOptimized" content="320">
	<!-- uc强制竖屏 -->
	<meta name="screen-orientation" content="portrait">
	<!-- QQ强制竖屏 -->
	<meta name="x5-orientation" content="portrait">
	<!-- UC强制全屏 -->
	<meta name="full-screen" content="yes">
	<!-- QQ强制全屏 -->
	<meta name="x5-fullscreen" content="true">
	<!-- UC应用模式 -->
	<meta name="browsermode" content="application">
	<!-- QQ应用模式 -->
	<meta name="x5-page-mode" content="app">
	<!-- windows phone 点击无高光 -->
	<meta name="msapplication-tap-highlight" content="no">
	<!-- 适应移动端end -->


## 参考

* [https://github.com/h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate)
* [http://fex.baidu.com/blog/2014/10/html-head-tags/](http://fex.baidu.com/blog/2014/10/html-head-tags/)