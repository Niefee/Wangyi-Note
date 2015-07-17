**目录**：

>笔记持续更新，原地址:https://github.com/Niefee/Wangyi-Note ;


<ul>
<li><a href="#变形">变形</a><ul>
<li><a href="#transform">transform</a><ul>
<li><a href="#rotate">rotate</a></li>
</ul>
</li>
<li><a href="#translate">translate</a></li>
<li><a href="#scale">scale</a></li>
<li><a href="#skew">skew</a></li>
<li><a href="#transform-transform-function">transform:&lt; transform-function &gt;+</a></li>
<li><a href="#transform-origin">transform-origin</a></li>
<li><a href="#perspective">perspective</a><ul>
<li><a href="#perspective-origin">perspective-origin</a></li>
</ul>
</li>
<li><a href="#translate3d">translate3d()</a></li>
<li><a href="#scale3d">scale3d()</a></li>
<li><a href="#rotate3d">rotate3d()</a></li>
<li><a href="#transform-style">transform-style</a></li>
<li><a href="#backface-visibity">backface-visibity</a></li>
</ul>
</li>
</ul>
##变形
###transform
![Alt text](img/1433469271740.png)
####rotate
 rotate(< angle>)
 ![Alt text](img/1433469356005.png)
 
###translate
![Alt text](img/1433469671171.png)
![Alt text](img/1433469806776.png)
>百分百的取值基础是容器的宽或高。


###scale
![Alt text](img/1433470006272.png)
![Alt text](img/1433470171159.png)

###skew
![Alt text](img/1433470431656.png)

###transform:< transform-function >+
![Alt text](img/1433470737285.png)

 - 顺序对比
![Alt text](img/1433470810642.png)
![Alt text](img/1433470828578.png)

###transform-origin
![Alt text](img/1433471134163.png)
![Alt text](img/1433471319056.png)

###perspective
![Alt text](img/1433472259577.png)
>length的取值意思是人眼到物体的距离

####perspective-origin
![Alt text](img/1433472580208.png)

###translate3d()
![Alt text](img/1433473486896.png)

###scale3d()
![Alt text](img/1433473680526.png)

###rotate3d()
![Alt text](img/1433474002746.png)

###transform-style
![Alt text](img/1433474258722.png)
![Alt text](img/1433474318732.png)

###backface-visibity
![Alt text](img/1433474470023.png)

>变形的兼容性问题说明：
>本节所讲语法和案例，均以W3规范为准，所有案例在webkit内核的高版本浏览器（如chrome）中测试通过。
>本节所讲语法和案例在低版本浏览器（如IE6、IE7、IE8等）中不支持。