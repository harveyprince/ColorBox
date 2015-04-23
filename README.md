# ColorBox
create a panel to select the color you want.取色器.based on js,jquery.
# 使用方法[using method]
## 初始化[init]
#### html part<br>
    <div class="color_bo"></div>
actually, the `color_bo` can change to any string you like.<br>
but it should keep the same with the follow when you use it.
#### js part<br>
    var c = new ColorBox($(".color_bo"));
    c.initBox();
now you have the panel on your website<br>
[demo](http://harveyprince.github.io/ColorBox/doc/html/color_box.html)
## 取指方法[the method to get value]
you can use `c.value` to get the value.it's a decimal number<br>
if you want to get the hexadecimal value like `#FFFFFF`<br>
you can use `c.getStringValue()`.<br>
