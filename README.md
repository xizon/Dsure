#  Dsure Web Development Framework

### 注意事项:

  如果使用扁平化风格，调用的核心CSS文件是"dsure.flat.css"而不是"dsure.css"

### 中文介绍:

简介：
Dsure基于纯CSS的HTML5网站响应式开发框架,可用于国内/外网站开发，完美适用于Designers Site Program 全站静态系统

来历：
Dsure参考了国内/外优秀的框架库,经过仔细研究探讨,针对国内和国外网站开发需求,重构编写了一套更适宜于国内(包括国外)的网站CSS/HTML开发框架,在这里它主要运用于Designers Site Program 全站静态系统的各类高端网站主题开发，当然如果你喜欢，也可以用于其它网站的框架开发 ^_^

特色：
+ 兼容IE6+, Firefox, Safari, Opera, Chrome 等主流浏览器,更高效适应国内/外网站 

+ 18种常用色彩方案，灵活运动到各标签元素控件中 

+ 12列自适应百分比网格(栅格)系统，适应各种分辨率和平台 

+ 纯CSS开发框架，基于HTML5+CSS3 

+ 完美兼容个版本的Designers Site Program 全站静态系统 

+ 无任何的Javascript效果代码参与到框架开发中,极大程度方便您自己扩展js组件和插件

+ 384个常用web矢量图标,icon大小和颜色灵活变更 

+ 丰富的组合样式,按钮控件样式轻松变



模块：
基础框架 (Base) *必须*
样式叠加 (Base) *通用*
内容/文本 (Text)
按钮 (Buttons)
表单 (Forms)
表格 (Tables)
网格/栅格系统 (Grids)
循环列表布局 (Layouts)
图标 (Icons)
图片 (Images)
分割线 (Dividing Line)
分页 (Paginators)
导航菜单 (Navigation)
分类导航 (Classification)
醒目牌 (Striking)
搜索框 (Search Box)
标签集 (Tags)

### 如何使用?

```html
<!doctype html><!-- Template OK -->
<!--[if lt IE 7 ]> <html dir="ltr" lang="zh-CN" xml:lang="zh-CN" class="no-js ie ie6"> <![endif]-->
<!--[if IE 7 ]>    <html dir="ltr" lang="zh-CN" xml:lang="zh-CN" class="no-js ie ie7"> <![endif]-->
<!--[if IE 8 ]>    <html dir="ltr" lang="zh-CN" xml:lang="zh-CN" class="no-js ie ie8"> <![endif]-->
<!--[if IE 9 ]>    <html dir="ltr" lang="zh-CN" xml:lang="zh-CN" class="no-js ie ie9"> <![endif]-->
<!--[if !IE]><!--> <html dir="ltr" lang="zh-CN" xml:lang="zh-CN" class="no-js"> <!--<![endif]-->

<head>
    <meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1">
    <meta name="renderer" content="webkit|ie-comp|ie-stand">
    <meta http-equiv="Content-Type" content="text/html; charset=gbk" />
    <title>网站标题</title>
    

    <!-- Dsure  Development Framework  begin  -->
        <link rel="stylesheet" type="text/css" href="dsure/dsure.css" />
        <script src="dsure/dsure.modernizr.js"></script>
        <!--[if lt IE 7 ]>  
            <script src="dsure/dsure.png.js"></script>  
            <script>  
            DD_belatedPNG.fix('img, a, span, h1, h2, h3, em, section, header');
            document.execCommand("BackgroundImageCache", false, true);
            </script>  
        <![endif]-->  
    <!-- /Dsure Development Framework  end   -->
    
    <!-- Other extended .css&.js file  begin  -->
         <!--网站加载完成前所要用到的其它的css文件和js文件，请放置到这块区域-->  
    <!-- /Other extended .css&.js file  end   -->
    

    <!-- Dsure  Development Framework  begin  -->
        <!--[if lt IE 9]>  
            <script src="dsure/dsure.respond.js"></script>  
        <![endif]-->  
    <!-- /Dsure Development Framework  end   -->


</head>
<body>

    ....

</body>
</html>

```
### Alert:

  If use flat style when the core CSS file is "dsure.flat.css" not "dsure.css".

### Typical uses:

Improve the efficiency of CSS/HTML website based development and responsive layout.

### Browser Support:
IE6 +, Firefox, Safari, Opera, Chrome and more

### Features:

- Compatible with more browsers and adapt to the china/foreign websites
- 18 color-scheme embedded in each label
- 12 grids with percentage of layout
- Pure CSS development framework which based on HTML and CSS3.
- Do not include the additional javascript plug-ins.
- Compatible with any version of the Designers Site Program <http://www.c945.com/d-s> perfectly.
- 384 web vector icons and  adjusted freely.
- Easy to change the button control with a rich combination.

### Official website:
<http://www.c945.com/d-s/dsure>

### Author:
<http://www.c945.com>

### Credits:

✓ <https://icomoon.io/>

✓ <http://modernizr.com/>

✓ <https://github.com/scottjehl/Respond/>


### How does it work?
```html
<!doctype html><!-- Template OK -->
<!--[if lt IE 7 ]> <html dir="ltr" lang="zh-CN" xml:lang="zh-CN" class="no-js ie ie6"> <![endif]-->
<!--[if IE 7 ]>    <html dir="ltr" lang="zh-CN" xml:lang="zh-CN" class="no-js ie ie7"> <![endif]-->
<!--[if IE 8 ]>    <html dir="ltr" lang="zh-CN" xml:lang="zh-CN" class="no-js ie ie8"> <![endif]-->
<!--[if IE 9 ]>    <html dir="ltr" lang="zh-CN" xml:lang="zh-CN" class="no-js ie ie9"> <![endif]-->
<!--[if !IE]><!--> <html dir="ltr" lang="zh-CN" xml:lang="zh-CN" class="no-js"> <!--<![endif]-->

<head>
    <meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1">
    <meta name="renderer" content="webkit|ie-comp|ie-stand">
    <meta http-equiv="Content-Type" content="text/html; charset=gbk" />
    <title>Site Name</title>
    

    <!-- Dsure  Development Framework  begin  -->
        <link rel="stylesheet" type="text/css" href="dsure/dsure.css" />
        <script src="dsure/dsure.modernizr.js"></script>
        <!--[if lt IE 7 ]>  
            <script src="dsure/dsure.png.js"></script>  
            <script>  
            DD_belatedPNG.fix('img, a, span, h1, h2, h3, em, section, header');
            document.execCommand("BackgroundImageCache", false, true);
            </script>  
        <![endif]-->  
    <!-- /Dsure Development Framework  end   -->
    
    <!-- Other extended .css&.js file  begin  -->
         
         ...
         
         
    <!-- /Other extended .css&.js file  end   -->
    

    <!-- Dsure  Development Framework  begin  -->
        <!--[if lt IE 9]>  
            <script src="dsure/dsure.respond.js"></script>  
        <![endif]-->  
    <!-- /Dsure Development Framework  end   -->


</head>
<body>

    ....

</body>
</html>

```
### Licensing

 This Product  is released under a Creative Commons Attribution 3.0 License

 License text may be found here:
 http://creativecommons.org/licenses/by-nc/3.0/deed.zh
