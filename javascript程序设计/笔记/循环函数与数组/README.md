#简介

>笔记持续更新，原地址:  https://github.com/Niefee/Wangyi-Note ;

<ul>
<li><a href="#循环函数与数组">循环函数与数组</a><ul>
<li><a href="#while">while</a></li>
<li><a href="#do-while">do-while</a></li>
<li><a href="#for循环">for循环</a></li>
<li><a href="#break与continue">break与continue</a></li>
<li><a href="#函数">函数</a></li>
<li><a href="#函数变量">函数变量</a></li>
<li><a href="#变量空间">变量空间</a></li>
<li><a href="#数组">数组</a></li>
<li><a href="#数组操作">数组操作</a></li>
</ul>
</li>
</ul>
#循环函数与数组
![Alt text](img/1434337502581.png)
##while
 - 循环嵌套
![Alt text](img/1434340039938.png)

##do-while
 - 数字倒转的算法
![Alt text](img/1434340223276.png)

##for循环
![Alt text](img/1434340288493.png)

>最后弹出来的是”4“，循环结束后 **i** 的值是5. 

- 比较
![Alt text](img/1434341808223.png)
![Alt text](img/1434341860283.png)

```
var amt=74;
		for(var one=0; one<=amt;++one){
   			for (var five=0;five<=amt/5;++five){
       			for (var ten=0;ten<=amt/10;++ten){
	 				for (var twenty=0;twenty<=amt/20;++twenty){ 
							if(one+five*5+ten*10+twenty*20==amt)
							{
					document.write(one+"张1元,"+five+"张5元，"+ten+"张10元，"+twenty+"张20元等于"+amt+"元"+"</br></br>");
}}}}}
```
##break与continue
![Alt text](img/1434357760223.png)

##函数
![Alt text](img/1434358078136.png)
 - 定义函数
![Alt text](img/1434358185479.png)

```
var u=42;
var v=24;
function max(a,b)
{
	return a>b?a:b;
}
function print(s){
	document.write(s);
}
function gcd(u,v){
	var a=u;
	var b=v;
	var temp=v;
	while(v!=0){
	temp=u%v;
	u=v;
	v=temp;
	}
	return u;
}
print(max(42,24)+"<br/>");//42;
print(u+"和"+v+"的最大公约数是"+gcd(u,v)+"<br/>")；//42和24的最大公约数是6；
```
##函数变量
![Alt text](img/1434359232254.png)

```
function add(a,b){
	return a+b;
}
function  cal(f,a,b){
	return f(a,b);
}
cal(add,5,6);//结果是11
```
##变量空间
![Alt text](img/1434359648238.png)

##数组
![Alt text](img/1434359958988.png)
 - 创建数组

![Alt text](img/1434360081957.png)
 - 访问数组

![Alt text](img/1434360213908.png)
 - 数组长度

![Alt text](img/1434361869366.png)
![Alt text](img/1434362068886.png)
>alert (color[2])的结果是undefined 。


![Alt text](img/1434362230408.png)
>alert (color[3])的结果是undefined 。

 - 转换数组为字符串
![Alt text](img/1434362701313.png)

 - 扩展性
![Alt text](img/1434362765516.png)
##数组操作
 - 堆栈操作
![Alt text](img/1434363281641.png)
 - 队列操作
![Alt text](img/1434363402477.png)
 - 排序操作
![Alt text](img/1434363449176.png)
 - 大小比较
![Alt text](img/1434363484508.png)
 - 数组操作
![Alt text](img/1434363570805.png)
 - splice()

![Alt text](img/1434363602164.png)
