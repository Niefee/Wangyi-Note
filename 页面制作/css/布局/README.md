**目录**：

>笔记持续更新，原地址:https://github.com/Niefee/Wangyi-Note ;


<ul>
<li><a href="#布局">布局</a><ul>
<li><a href="#display">display</a><ul>
<li><a href="#block">block</a></li>
<li><a href="#inline">inline</a></li>
<li><a href="#inline-block">inline-block</a></li>
<li><a href="#none">none</a></li>
<li><a href="#居中导航">居中导航</a></li>
</ul>
</li>
<li><a href="#position">position</a><ul>
<li><a href="#toptightbottomleft">top/tight/bottom/left</a></li>
<li><a href="#z-index">z-index</a><ul>
<li><a href="#z-index栈">z-index栈</a></li>
</ul>
</li>
<li><a href="#position属性">position属性</a><ul>
<li><a href="#relative">relative</a></li>
<li><a href="#absolute">absolute</a></li>
<li><a href="#fixed">fixed</a></li>
<li><a href="#遮罩">遮罩</a></li>
<li><a href="#自适应三栏布局">自适应三栏布局</a></li>
</ul>
</li>
</ul>
</li>
<li><a href="#float">float</a></li>
<li><a href="#clear">clear</a><ul>
<li><a href="#两列布局">两列布局</a></li>
</ul>
</li>
<li><a href="#flex">flex</a><ul>
<li><a href="#flex-item">flex item</a></li>
<li><a href="#flex-direction">flex-direction</a></li>
<li><a href="#flex-wrap">flex-wrap</a></li>
<li><a href="#flex-flow">flex-flow</a></li>
<li><a href="#order">order</a></li>
<li><a href="#flex-basis">flex-basis</a></li>
<li><a href="#flex-grow">flex-grow</a></li>
<li><a href="#flex-shrink">flex-shrink</a></li>
<li><a href="#flex-1">flex</a></li>
<li><a href="#justify-content">justify-content</a></li>
<li><a href="#align-items">align-items</a></li>
<li><a href="#align-self">align-self</a></li>
<li><a href="#align-content">align-content</a></li>
<li><a href="#三行两列自适应布局">三行两列自适应布局</a></li>
</ul>
</li>
</ul>
</li>
</ul>
##布局
###display
![Alt text](img/1433388517534.png)
####block
![Alt text](img/1433388607063.png)
####inline
![Alt text](img/1433388773858.png)
>对比：
>![Alt text](img/1433388886317.png)
####inline-block
![Alt text](img/1433389014398.png)
![Alt text](img/1433389099215.png)
####none
![Alt text](img/1433389131588.png)
>display：none与visibility：hidden的区别
>![Alt text](img/1433389219964.png)
>后者保留空间，前者会忽略空间。

####居中导航
![Alt text](img/1433389437962.png)
![Alt text](img/1433389488246.png)

###position
![Alt text](img/1433389780523.png)
####top/tight/bottom/left
![Alt text](img/1433389839008.png)
####z-index
![Alt text](img/1433391369006.png)
>默认是 0，数字小在下面。
#####z-index栈
![Alt text](img/1433391482940.png)

####position属性
#####relative
![Alt text](img/1433392180555.png)
#####absolute
![Alt text](img/1433392304028.png)
![Alt text](img/1433392475052.png)
> - **实例**
轮播头图：
![Alt text](img/1433392581464.png)
![Alt text](img/1433392677806.png)

#####fixed
![Alt text](img/1433392915644.png)

> - 实例
> 固定顶栏：
> ![Alt text](img/1433393131223.png)

#####遮罩
![Alt text](img/1433393309193.png)

#####自适应三栏布局
![Alt text](img/1433393480642.png)
###float
![Alt text](img/1433399848082.png)
>none是默认值

![Alt text](img/1433399944166.png)
![Alt text](img/1433400093650.png)
![Alt text](img/1433400221335.png)
**文档流**
![Alt text](img/1433400344803.png)
![Alt text](img/1433400411339.png)

###clear
![Alt text](img/1433407839834.png)
![Alt text](img/1433408155167.png)
 - 增加一个清除浮动的元素cb
![Alt text](img/1433408201873.png)

---

![Alt text](img/1433408122453.png)

####两列布局
![Alt text](img/1433408305678.png)
![Alt text](img/1433408357301.png)

###flex
![Alt text](img/1433408816198.png)
![Alt text](img/1433408839960.png)
####flex item
![Alt text](img/1433408916327.png)
####flex-direction
![Alt text](img/1433408994503.png)
![Alt text](img/1433409060931.png)
####flex-wrap
![Alt text](img/1433409116377.png)
![Alt text](img/1433409182526.png)
####flex-flow
![Alt text](img/1433409226430.png)
####order
![Alt text](img/1433409270451.png)
![Alt text](img/1433409362826.png)
####flex-basis
![Alt text](img/1433409455858.png)
####flex-grow
![Alt text](img/1433409497354.png)
![Alt text](img/1433409507108.png)
![Alt text](img/1433415176085.png)
####flex-shrink
![Alt text](img/1433415361949.png)
![Alt text](img/1433415421487.png)
![Alt text](img/1433415523695.png)
####flex
![Alt text](img/1433415562231.png)
####justify-content
![Alt text](img/1433415753822.png)
![Alt text](img/1433415814003.png)
####align-items
![Alt text](img/1433415906666.png)
![Alt text](img/1433416008109.png)
> 像vertical-align；

####align-self
![Alt text](img/1433416082359.png)
####align-content
![Alt text](img/1433416209801.png)
####三行两列自适应布局
![Alt text](img/1433416878476.png)
![Alt text](img/1433416967579.png)
>flex ie9及以下不支持，目前主要用于移动web页面中.














