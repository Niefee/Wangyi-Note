**目录**：

>笔记持续更新，原地址: https://github.com/Niefee/Wangyi-Note ;


<ul>
<li><a href="#动画">动画</a><ul>
<li><a href="#transition">transition</a><ul>
<li><a href="#transition-property">transition-property</a></li>
<li><a href="#transition-duration">transition-duration</a></li>
<li><a href="#transition-timing-function">transition-timing-function</a></li>
<li><a href="#transition-delay">transition-delay</a></li>
<li><a href="#transition简写">transition</a></li>
</ul>
</li>
<li><a href="#animation">animation</a><ul>
<li><a href="#animation-name">animation-name</a></li>
<li><a href="#animation-duration">animation-duration</a></li>
<li><a href="#animation-timing-function">animation-timing-function</a></li>
<li><a href="#animation-iteration-count">animation-iteration-count</a></li>
<li><a href="#animation-direction">animation-direction</a></li>
<li><a href="#animation-play-state">animation-play-state</a></li>
<li><a href="#animation-delay">animation-delay</a></li>
<li><a href="#animation-fill-mode">animation-fill-mode</a></li>
<li><a href="#animation-1">animation</a></li>
<li><a href="#keyframes">@keyframes</a></li>
</ul>
</li>
</ul>
</li>
</ul>

#动画
##transition
###transition-property
**执行表换属性**
![Alt text](img/1433488710912.png)
![Alt text](img/1433488829670.png)

###transition-duration
**变换延续时间**

![Alt text](img/1433488875042.png)
![Alt text](img/1433488914308.png)

###transition-timing-function
**变换的速率变化 **

![Alt text](img/1433489218200.png)
![Alt text](img/1433489302031.png)

###transition-delay
**变换延迟时间**

![Alt text](img/1433489686509.png)
![Alt text](img/1433489718320.png)

###transition简写
>transition: <property> <duration> <animation type> <delay>

![Alt text](img/1433489831142.png)

##animation

###animation-name
**动画名称**

![Alt text](img/1433490396387.png)
![Alt text](img/1433490521532.png)

###animation-duration
**元素动画的持续时间**

![Alt text](img/1433490565885.png)
![Alt text](img/1433490608241.png)

###animation-timing-function
**属性变化速率曲线**

![Alt text](img/1433490689096.png)
![Alt text](img/1433490723892.png)

###animation-iteration-count
**动画播放的循环次数**

![Alt text](img/1433491892925.png)
![Alt text](img/1433491934137.png)

###animation-direction
**元素动画的播放方向**

>normal是默认方向播放，reverse是反向播放。
>alternate是往返播放，alternate是反向往返播放。
![Alt text](img/1433492072794.png)
![Alt text](img/1433492135934.png)

###animation-play-state

**元素动画的播放 状态**

![Alt text](img/1433492162144.png)
![Alt text](img/1433492234883.png)

###animation-delay
**动画播放延迟时间**

![Alt text](img/1433492283341.png)
![Alt text](img/1433492296947.png)

###animation-fill-mode
**元素动画播放前后的界面显示**

![Alt text](img/1433492393840.png)
![Alt text](img/1433492470611.png)
>**none **  不改变默认行为。

>**forwards**    当动画完成后，保持最后一个属性值（在最后一个关键帧中定义）。

>**backwards**   在animation-delay 所指定的一段时间内，在动画显示之前，应用开始属性值（在第一个关键帧中定义）。

>**both**    向前和向后填充模式都被应用。

###animation 
![Alt text](img/1433492678446.png)

###@keyframes
![Alt text](img/1433492934555.png)
![Alt text](img/1433493016525.png)
>动画的兼容性问题说明：
本节所讲语法和案例，均以W3规范为准，所有案例在webkit内核的高版本浏览器（如chrome）中测试通过。
本节所讲语法和案例在低版本浏览器（如IE6、IE7、IE8等）中不支持。




