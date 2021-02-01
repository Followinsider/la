# la.html
<!DOCTYPE html>(定义文本类型）
<html lang="en">（别人以什么语言去理解我写的）
<head>
    <meta charset="UTF-8">（字符规则吧，就道上的规矩）
    <meta name="viewport" content="width=device-width, initial-scale=1.0">(用户浏览时页面适合其设备宽度与高度，初始缩放比例为1.0)，其中还可以加入
  1.user-scalable="Yes or No",表示用户可否缩放屏幕
  2.minimum-scale="x",表示限制用户缩放比例，同理有maximum，x属于（0.25~10.0）
    <title>Document</title>
<style>
            a:link {color:green}
            a:visited {color:black}
            a:hover {color:red}
            a:active {color:yellow}
    /*  hover放在visited前面会失效，但active不会失效
        hover放在active后面时不会失效，但中间的active会失效
        active放在最前面时会失效
        最后去查了下，原来在 CSS 定义中，a:hover 必须被置于 a:link 和 a:visited 之后，才是有效的。
        a:active 必须被置于 a:hover 之后，才是有效的。
    */
</style>
</head>
<body>
    <p style=" text-align:center">中心</p>
    <a href="javascript:;">点我前是绿，点我后是黑，摸到我是红，反应时是黄</a>
</body>
</html>
(以上是我从vscode复制过来的一个模板，并对其中一些元素做出自己理解的解释)
