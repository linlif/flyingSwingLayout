# flyingSwingLayout
淘宝双飞翼布局

点击链接可查看效果：https://linlif.github.io/flyingSwingLayout/index.html

<br>
**html代码:**

```html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title>淘宝双飞翼布局</title>
    <link rel="stylesheet" href="app.css" type="text/css">
  </head>
  <body>
    <header id="header">header</header>

    <div id="main">
      <div class="center-wrap">
        <div class="center">淘宝双飞翼布局</div>
      </div>
      <div class="left">left</div>
      <div class="right">right</div>
    </div>
    
    <footer id="footer">footer</footer>
  </body>
</html>
```


**CSS代码：**

```css
*{
  margin: 0;
  padding: 0;
}
body{
  font-size: 30px;
  color: white;
  text-align: center;
  min-width: 650px;
}

#header,#footer{
  background-color: #303030;
  height: 80px;
  line-height: 80px;
}

#main{
  margin-left: auto;
  margin-right: auto;
  width: 100%;
}

#main .center-wrap{
  float: left;
  width: 100%;
  min-height: 600px;
}

#main .center{
  margin-left: 200px;
  margin-right: 300px;
  min-height: 600px;
  background-color: #c15716;
}

#main .left{
  float: left;
  width: 190px;
  background-color: #289ad2;
  min-height: 600px;
  margin-left: -100%;
}

#main .right{
  float: left;
  background-color: #abc444;
  width: 290px;
  min-height: 600px;
  margin-left: -290px;
}

#footer{
  clear: both;
}
```




