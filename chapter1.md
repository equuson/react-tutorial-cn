# 快速入门

##环境搭建

官网地址：http://facebook.github.io/react/  
Github地址：https://github.com/facebook/react  
CDN地址：  
开发环境
```
<script src="https://fb.me/react-0.14.3.js"></script>
<script src="https://fb.me/react-dom-0.14.3.js"></script>
```

生产环境
```
<script src="https://fb.me/react-0.14.3.min.js"></script>
<script src="https://fb.me/react-dom-0.14.3.min.js"></script>
```
好吧，国内不能访问，请使用国内镜像
```
//cdn.bootcss.com/react/0.14.3/react.js
```
##入门例子
初学者还是下载完整的代码包吧。
http://facebook.github.io/react/downloads/react-0.14.3.zip
开发者很照顾大家，开发包中有详细的例子。
本教程为了摆脱对本地库的依赖都会使用CDN。
```
<!DOCTYPE html>
<html>
  <head>
    <meta charset="UTF-8" />
    <title>Hello React!</title>
    <script src="http://cdn.bootcss.com/react/0.14.3/react.js"></script>
    <script src="http://cdn.bootcss.com/react/0.14.3/react-dom.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/babel-core/5.8.23/browser.min.js"></script>
  </head>
  <body>
    <div id="example"></div>
    <script type="text/babel">
      ReactDOM.render(
        <h1>Hello, world!</h1>,
        document.getElementById('example')
      );
    </script>
  </body>
</html>
```

运行结果也很简单：就是一个**Hello, world!**。
但这可是动态插入的哦。

