**目录**：

>笔记持续更新，原地址 : https://github.com/Niefee/Wangyi-Note ;

<ul>
<li><ul>
<li><a href="#类型系统">类型系统</a><ul>
<li><a href="#基本类型">基本类型</a><ul>
<li><a href="#标准类型">标准类型</a><ul>
<li><a href="#原始类型与应用类型的区别">原始类型与应用类型的区别</a></li>
</ul>
</li>
<li><a href="#undefined">Undefined</a></li>
<li><a href="#null">Null</a></li>
<li><a href="#boolean">Boolean</a></li>
<li><a href="#string">String</a></li>
<li><a href="#number">Number</a></li>
<li><a href="#object">Object</a></li>
</ul>
</li>
<li><a href="#类型识别">类型识别</a><ul>
<li><a href="#typeof">typeof</a></li>
<li><a href="#objectprototypetostring">Object.prototype.toString</a></li>
<li><a href="#constructor">constructor</a></li>
<li><a href="#instanceof">instanceof</a></li>
</ul>
</li>
</ul>
</li>
</ul>
</li>
</ul>
##类型系统
![Alt text](img/1433817596409.png)
###基本类型
####标准类型
![Alt text](img/1433817696364.png)
#####原始类型与应用类型的区别
![Alt text](img/1433817878862.png)
**复制的区别**
![Alt text](img/1433817962429.png)
####Undefined
 - 类型说明
	 - 值：undefined


- 出现场景

1、已声明未赋值的变量

![Alt text](img/1433818134186.png)

>声明一个变量a，却没有赋值， 打印出来是undefined。

2、获取对象不存在的属性

![Alt text](img/1433818245109.png)

3、无返回值的函数的执行结果

![Alt text](img/1433818315689.png)

4、函数参数没有传入

![Alt text](img/1433818349989.png)

5、void（expression）

---

 - 类型转换

**Undefined转Boolean**

![Alt text](img/1433818702785.png)
>obj.c = Boolean(undefined)

**Undefined转Number**

![Alt text](img/1433818825258.png)
![Alt text](img/1433818805815.png)

**Undefined转String**

![Alt text](img/1433818861270.png)
![Alt text](img/1433818894211.png)

---

####Null
![Alt text](img/1433818952753.png)

####Boolean
![Alt text](img/1433819018443.png)

####String
![Alt text](img/1433819075343.png)

####Number
![Alt text](img/1433819123576.png)
>NaN表示非数字值。 NaN = 'Not a Number' 非数字值。
>Infinity表示无穷大。

####Object
![Alt text](img/1433819221467.png)

###类型识别
![Alt text](img/1433820055635.png)

####typeof
![Alt text](img/1433820141773.png)

####Object.prototype.toString
![Alt text](img/1433820255609.png)
>首先封装一个函数type()。

####constructor
![Alt text](img/1433820382879.png)

####instanceof
![Alt text](img/1433820500616.png)


