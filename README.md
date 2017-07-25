# HTML5 常用 meta 标签

HTML5可复用模板，尽可能保持简洁。

### DOCTYPE

```html
<!DOCTYPE html>
```

### charset

```html
<meta charset="utf-8">
```

### lang

```html
<!-- google -->
<html lang="zh-CN">
```

> [网页头部的声明应该是用 lang="zh" 还是 lang="zh-cn"？](https://www.zhihu.com/question/20797118)


### 优先使用 IE 最新版本和 Chrome

```html
<meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1">
```

### 360 使用 WebKit

```html
<meta name="renderer" content="webkit">
```

### 移动优先

```html
<meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1, user-scalable=no">
```

### 禁止自动转换为电话号码

```html
<!-- google -->
<meta name="format-detection" content="telephone=no">
```

### Favicon icon

```html
<!-- Yahoo -->
<link rel="shortcut icon" href="https://s.yimg.com/rz/l/favicon.ico">
```

### iOS 添加网页放到主屏幕展示的图标

```html
<!-- Amazon -->
<link rel="apple-touch-icon" href="apple-touch-icon.png">
```

### 百度禁止转码

```html
<meta http-equiv="Cache-Control" content="no-siteapp">
```

### 手机QQ浏览器x5内核定制<meta>标签说明

> 详见：[http://open.mb.qq.com/web/doc?id=1201#_1](http://open.mb.qq.com/web/doc?id=1201#_1)

#### 1. x5-orientation：横竖屏控制 
* landscape：强制横屏
  实例说明：

  ```html
  <meta name="x5-orientation" content="landscape"/>
  ```
* portrait：强制竖屏
  实例说明：

  ```html
  <meta name="x5-orientation" content="portrait"/>
  ```
* auto：跟随浏览器设置【默认】
  实例说明：

  ```html
  <meta name="x5-orientation" content="auto"/>
  ```

#### 2. x5-fullscreen：全屏控制

* true：强制全屏
  实例说明：

  ```html
  <meta name="x5-fullscreen" content="true"/>
  ```

* auto：跟随浏览器设置【默认】
  实例说明：
  ```html
  <meta name="x5-fullscreen" content="auto"/>
  ```

#### 3. x5-page-mode ：页面模式

* default：普通浏览模式【默认】
  实例说明：
  ```html
  <meta name="x5-page-mode" content="default"/>
  ```

* app：网页应用模式（定制工具栏，全屏显示）
  实例说明：
  ```html
  <meta name="x5-page-mode" content="app"/>
  ```

### 其它

```html
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
```


## 参考

* [QQ手机浏览器 x5内核定制<meta>标签说明](http://open.mb.qq.com/web/doc?id=1201)
* [https://github.com/h5bp/html5-boilerplate](https://github.com/h5bp/html5-boilerplate)
* [http://fex.baidu.com/blog/2014/10/html-head-tags/](http://fex.baidu.com/blog/2014/10/html-head-tags/)