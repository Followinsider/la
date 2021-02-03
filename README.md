# la.html（Day1）
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
#(Day2)
一、
<script>            
      1.console.log(1*2*3*4*5*6*7*8*9*10*11*12*13*14*15*16*17*18*19*20*21*22*23*24*25*26*27*28*29*30*31*32*33*34*35*36*37*38*39*40*41*42*43*44*45*46*47*48*49*50*51*52*53*54*55*56*57*58*59*60*61*62*63*64*65*66)
    

2.var row=5; // row表示总行数
    for(var r=row;r>0;r--){  //外层循环控制行数 r表示每次变化的行数
  var triangle="";   //triangle表示最后的三角形
    for(var space=r;space<row;space++){ //此循环控制空格数 space表示空格数
      triangle+=" ";
   }
    for(var $=1;$<=2*r-1;$++){ //此循环控制 $ 数
      triangle+="$";
   }
console.log(triangle);
    

3.function factorialize(num){
    return num >1 ? num * factorialize (num-1):1;
}
console.log(factorialize(66));

二、
</script>
var style = document.createElement('style'); 
 style.type = 'text/css'; 
</script>
