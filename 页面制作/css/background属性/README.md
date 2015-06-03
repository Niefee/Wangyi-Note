**目录**:

>笔记持续更新，原地址:https://github.com/Niefee/Wangyi-Note ;


<ul>
<li><a href="#背景">背景</a><ul>
<li><a href="#background-color">background-color</a></li>
<li><a href="#background-image">background-image</a></li>
<li><a href="#background-repeat">background-repeat</a><ul>
<li><a href="#space与round补充">space与round补充</a></li>
</ul>
</li>
<li><a href="#background-attachment">background-attachment</a></li>
<li><a href="#background-position">background-position</a><ul>
<li><a href="#精灵模式">精灵模式</a></li>
</ul>
</li>
<li><a href="#linear-gradient">linear-gradient</a></li>
<li><a href="#radial-gradient">radial-gradient</a></li>
<li><a href="#repeat-gradient">repeat-*-gradient</a></li>
<li><a href="#background-origin">background-origin</a></li>
<li><a href="#background-clip">background-clip</a></li>
<li><a href="#background-size">background-size</a></li>
<li><a href="#background综合写法">background综合写法</a></li>
</ul>
</li>
</ul>
##背景
###background-color
**写法**
![Alt text](img/1433331199996.png)
![Alt text](img/1433331208044.png)
![Alt text](img/1433331216644.png)
![Alt text](img/1433331227293.png)

###background-image
![Alt text](img/1433331376205.png)
>background-color在最后面。

###background-repeat
![Alt text](img/1433331478061.png)

####space与round补充
>补充：
>space值的功效可以简单理解为图片的两端对齐平铺，多出来的空间用空白代替：
>![Alt text](img/1433331703422.png)

---
>round属性的效果也可以说是两端对齐，但出来空间通过自身的拉伸来填充。
>![Alt text](img/1433331745637.png)

###background-attachment
![Alt text](img/1433331884043.png)
>fixed的参照物是整个页面，好少用，不建议使用。

###background-position
![Alt text](img/1433332092958.png)
>图片的百分百跟页面的百分百位置重合。

####精灵模式
![Alt text](img/1433332385409.png)

###linear-gradient
![Alt text](img/1433332820146.png)
![Alt text](img/1433332833957.png)
![Alt text](img/1433332857828.png)
![Alt text](img/1433332870723.png)
![Alt text](img/1433332904693.png)
###radial-gradient
![Alt text](img/1433333084350.png)
![Alt text](img/1433333137416.png)
![Alt text](img/1433333199339.png)
![Alt text](img/1433333216900.png)
![Alt text](img/1433333239709.png)
![Alt text](img/1433333273615.png)
###repeat-*-gradient
![Alt text](img/1433333342327.png)
![Alt text](img/1433333357571.png)
###background-origin
![Alt text](img/1433333457710.png)
![Alt text](img/1433333470559.png)
![Alt text](img/1433333484790.png)
###background-clip
![Alt text](img/1433333580248.png)
![Alt text](img/1433333590150.png)
![Alt text](img/1433333601203.png)
###background-size
![Alt text](img/1433333692424.png)
![Alt text](img/1433333710863.png)
![Alt text](img/1433333735994.png)
![Alt text](img/1433333746589.png)
###background综合写法
![Alt text](img/1433333871911.png)

---

>背景的兼容性问题说明：
>本节所讲语法和案例，均以W3规范为准，所有案例在webkit内核的高版本浏览器（如chrome）中测试通过。
>部分语法和案例在低版本浏览器（如IE6、IE7、IE8等）中不支持，比如：多背景图、渐变背景、background-size、background-origin、background-clip等。





