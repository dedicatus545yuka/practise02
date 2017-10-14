# practise02
图片轮播
### 其實還是前幾天就寫的練習，週六的晚上就想著偷下懶，但是又不想斷更，這其實還是乾貨吧-—_——  
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>图片轮播</title>
    <link rel="stylesheet" href="图片轮播.css">
</head>
<body>
<div class="windows">
    <div class="box">
        <img src="http://a3.qpic.cn/psb?/V118JuTr3rHMrA/IRsNPTViXwp.wAbeTKK7ruWpDa6gEXvJ6y2yiGYPRBE!/b/dPIAAAAAAAAA&bo=ZQSAAgAAAAARB9M!&rf=viewer_4">
        <img src="http://a1.qpic.cn/psb?/V118JuTr3rHMrA/u8DKZ2..XGowEbmJF38U*RSKRwY1l1faLlnvllHqhGg!/b/dPMAAAAAAAAA&bo=PASAAgAAAAARAI0!&rf=viewer_4" >
        <img src="http://a1.qpic.cn/psb?/V118JuTr3rHMrA/q5GAmB1HW2IvWOhoxlzn.zgcGQyQkQNIM9Q3YhbkXv0!/b/dPMAAAAAAAAA&bo=cQSAAgAAAAARAMA!&rf=viewer_4" >
        <img src="http://a1.qpic.cn/psb?/V118JuTr3rHMrA/E.TDKqLPkWn5X.cPLdIH25suOqf6U4prxUxVN9qXNTY!/b/dPMAAAAAAAAA&bo=cgSAAgAAAAARAMM!&rf=viewer_4" >
    </div>
</div>
</body>
</html>
```  

`圖片輪播`  
  
```CSS
.windows {
    border: 5px solid lightskyblue;
    margin: 0 auto;
    width: 600px;
    height: 400px;
    /* 给元素设置基本样式 */
    overflow: auto;
    position: relative;
}
img {
    width: 600px;
    height: 400px;
    float: left;
    /* 给图片设置尺寸以适应项目 */

    /*margin-left: -600px;*/
}
.box {
    width: 2400px;
    position: absolute;
    /*left: -600px;*/
}
```
