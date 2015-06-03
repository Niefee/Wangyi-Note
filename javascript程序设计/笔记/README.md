**目录**：

>笔记持续更新，原地址:https://github.com/Niefee/Wangyi-Note ;


<ul>
<li><a href="#javascript介绍">javascript介绍</a></li>
<li><a href="#javascript调试">javascript调试</a><ul>
<li><a href="#观察窗口">观察窗口</a></li>
</ul>
</li>
<li><a href="#javascript词法">javascript词法</a></li>
<li><a href="#类型系统">类型系统</a><ul>
<li><a href="#标准类型">标准类型</a></li>
<li><a href="#原始类型和应用类型">原始类型和应用类型</a></li>
<li><a href="#undefined">Undefined</a></li>
<li><a href="#null">null</a></li>
<li><a href="#boolean">Boolean</a></li>
<li><a href="#string">String</a></li>
<li><a href="#number">Number</a></li>
<li><a href="#object">Object</a></li>
</ul>
</li>
<li><a href="#类型识别">类型识别</a><ul>
<li><a href="#typeof">typeof</a></li>
<li><a href="#objectprototypetosting">Object.prototype.toSting</a></li>
<li><a href="#constructor">constructor</a></li>
<li><a href="#instanceof">instanceof</a></li>
</ul>
</li>
<li><a href="#内置对象">内置对象</a><ul>
<li><a href="#标准内置对象">标准内置对象</a><ul>
<li><a href="#object-1">Object</a><ul>
<li><a href="#objectcreate">Object.create</a></li>
<li><a href="#objectprototypetostring">Object.prototype.toString</a></li>
<li><a href="#objectprototypehasownproperty">Object.prototype.hasOwnProperty</a></li>
</ul>
</li>
</ul>
</li>
<li><a href="#boolean-1">Boolean</a><ul>
<li><a href="#其他类型向布尔类型转换">其他类型向布尔类型转换</a></li>
</ul>
</li>
<li><a href="#string-1">String</a><ul>
<li><a href="#stringprototypeindexof">String.prototype.indexOf</a></li>
<li><a href="#stringprototyreplace">String.prototy.replace</a></li>
<li><a href="#stingprototypesplit">Sting.prototype.split</a></li>
</ul>
</li>
<li><a href="#number-1">Number</a><ul>
<li><a href="#numberprototypetofixed">Number.prototype.toFixed</a></li>
</ul>
</li>
<li><a href="#array">Array</a><ul>
<li><a href="#arrayprototypesplice">Array.prototype.splice</a></li>
<li><a href="#arrayprototypeforeach">Array.prototype.forEach</a></li>
</ul>
</li>
<li><a href="#function">Function</a><ul>
<li><a href="#自定义对象构造器">自定义对象构造器</a></li>
<li><a href="#functionprototypeapply">Function.prototype.apply</a></li>
<li><a href="#functionprototypebind">Function.prototype.bind</a></li>
<li><a href="#子类构造器">子类构造器</a></li>
<li><a href="#函数调用">函数调用</a></li>
<li><a href="#函数参数">函数参数</a></li>
<li><a href="#arguments">arguments</a></li>
<li><a href="#值传递">值传递</a></li>
<li><a href="#函数重载">函数重载</a></li>
</ul>
</li>
<li><a href="#regexp">RegExp</a><ul>
<li><a href="#regexpprototypetest">RegExp.prototype.test</a></li>
</ul>
</li>
<li><a href="#date">Date</a></li>
<li><a href="#标准内置对象-1">标准内置对象</a><ul>
<li><a href="#math">Math</a><ul>
<li><a href="#mathfloor">Math.floor</a></li>
</ul>
</li>
<li><a href="#mathrandom">Math.random</a></li>
<li><a href="#json">JSON</a><ul>
<li><a href="#jsonstringify">JSON.stringify</a></li>
<li><a href="#jsonparse">JSON.parse</a></li>
</ul>
</li>
</ul>
</li>
<li><a href="#全局对象">全局对象</a><ul>
<li><a href="#nan">NaN</a></li>
<li><a href="#parseint">parseInt</a></li>
<li><a href="#eval">eval</a></li>
<li><a href="#encodeduricomponent">encodedURIComponent</a></li>
</ul>
</li>
</ul>
</li>
</ul>

##javascript介绍
![Alt text](img/1432902619343.png)
 - **javascript简介**
    - 解释型编程语言（脚本）。
    - 运行环境↓
 ![Alt text](img/1432902748636.png)
 
 - **javascript历史**
![Alt text](img/1432903067448.png)

 - **浏览器中的javascript**
![Alt text](img/1432903121953.png)

 - **javascript引入 **
![Alt text](img/1432903248795.png)

##javascript调试
![Alt text](img/1432910582102.png)
![Alt text](img/1432910653744.png)
 - 第一个：继续执行按钮
 - 第二个：单步调试
 - 第三个：进入函数执行
 - 第四个：跳出函数执行

 ###观察窗口
![Alt text](img/1432912421803.png)

##javascript词法
![Alt text](img/1432952952399.png)

 - 变量标识符
![Alt text](img/1432953025108.png)
 - 保留字与关键字
![Alt text](img/1432953247486.png)
![Alt text](img/1432953256797.png)
![Alt text](img/1432953281315.png)
 - 大小写敏感
![Alt text](img/1432953416567.png)
>图中道德Arr跟arr是不同的变量

 - 严格模式  
![Alt text](img/1432953579966.png)
	- 标准与严格模式的区别
		 - 隐式声明或定义
	![Alt text](img/1432953675797.png)
	![Alt text](img/1432953697629.png)
		- 对象重名的属性
	![Alt text](img/1432953848874.png)
	![Alt text](img/1432953864447.png)
		 - argument.callee
	![Alt text](img/1432953918137.png)
	![Alt text](img/1432953937620.png)
		 - with语句
	![Alt text](img/1432954012958.png)
	![Alt text](img/1432954044066.png)
		 - .....
 - 注释
![Alt text](img/1432954593993.png)

##类型系统
![Alt text](img/1432956901779.png)

###标准类型
![Alt text](img/1432957211267.png)
###原始类型和应用类型
![Alt text](img/1432957696996.png)
>a,b,c,d,e是原始类型，f是应用类型。

![Alt text](img/1432957851819.png)

###Undefined
 - 类型说明
	 - 值：undefined

 - 出现场景
1. 已声明未赋值的变量
		![Alt text](img/1432958156438.png)
2. 获取对象 不存在的属性
		![Alt text](img/1432958186145.png)
3. 无返回值的函数的执行结果
		![Alt text](img/1432958231357.png)
4. 函数的参数没有传入
		![Alt text](img/1432958622907.png)
5. viod（expression）

 - 类型转换
1. ![Alt text](img/1432958994071.png)
2. ![Alt text](img/1432959038899.png)
3. ![Alt text](img/1432959109723.png)

###null
![Alt text](img/1432959364121.png)

###Boolean

![Alt text](img/1432959433240.png)

###String
![Alt text](img/1432959484730.png)

###Number
![Alt text](img/1432959525650.png)

###Object
![Alt text](img/1432959578968.png)

##类型识别
 1. typeof
 2. Object.prototype.toSting
 3. constructor
 4. instanceof

###typeof
![Alt text](img/1433037154205.png)
### Object.prototype.toSting
![Alt text](img/1433037225466.png)
###constructor
![Alt text](img/1433037293830.png)
###instanceof
![Alt text](img/1433037371839.png)

##内置对象
![Alt text](img/1433037653461.png)
*为何“a&b&c”能调用split这个方式了？*
>只有对象才有属性和方法

![Alt text](img/1433037893073.png)
###标准内置对象

![Alt text](img/1433037922959.png)
![Alt text](img/1433037958555.png)

####Object
![Alt text](img/1433038180533.png)
#####Object.create
![Alt text](img/1433038251152.png)
#####Object.prototype.toString
![Alt text](img/1433038361186.png)
#####Object.prototype.hasOwnProperty
![Alt text](img/1433038445149.png)

###Boolean
![Alt text](img/1433038613311.png)
####其他类型向布尔类型转换
![Alt text](img/1433038709043.png)
###String
![Alt text](img/1433038851052.png)
####String.prototype.indexOf
![Alt text](img/1433038999005.png)
####String.prototy.replace
![Alt text](img/1433039161689.png)
####Sting.prototype.split
![Alt text](img/1433039320053.png)


###Number
![Alt text](img/1433040092269.png)
####Number.prototype.toFixed
![Alt text](img/1433040180159.png)
>想进一步了解对象常用属性和方法的同学，可以通过W3C或者MDN网站进行学习
1.http://www.w3school.com.cn/jsref/jsref_obj_string.asp
2.https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects


###Array
![Alt text](img/1433040621141.png)
####Array.prototype.splice
![Alt text](img/1433040764153.png)
> console.log(ret);
4,6

>console.log(arr);
 1,2,8,5

####Array.prototype.forEach
![Alt text](img/1433041288021.png)
>想进一步了解对象常用属性和方法的同学，可以通过W3C或者MDN网站进行学习
http://www.w3school.com.cn/jsref/jsref_obj_array.asp
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects

###Function
![Alt text](img/1433041499992.png)
####自定义对象构造器
![Alt text](img/1433041601346.png)
![Alt text](img/1433042605513.png)

####Function.prototype.apply
![Alt text](img/1433042800359.png)
![Alt text](img/1433042813895.png)
####Function.prototype.bind
![Alt text](img/1433042945562.png)
####子类构造器
![Alt text](img/1433043214199.png)
####函数调用
 1. ( )
 2. apply, call

####函数参数
![Alt text](img/1433043327318.png)

####arguments
![Alt text](img/1433043462291.png)
####值传递
![Alt text](img/1433044409362.png)
![Alt text](img/1433044513181.png)

####函数重载
![Alt text](img/1433044659902.png)

>想进一步了解对象常用属性和方法的同学，可以通过W3C或者MDN网站进行学习
http://www.w3school.com.cn/jsref/jsref_obj_global.asp
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects

###RegExp
![Alt text](img/1433072665614.png)
####RegExp.prototype.test
![Alt text](img/1433072873662.png)
###Date
![Alt text](img/1433072903893.png)
>想进一步了解对象常用属性和方法的同学，可以通过W3C或者MDN网站进行学习
http://www.w3school.com.cn/jsref/jsref_obj_regexp.asp
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects

###标准内置对象
####Math
![Alt text](img/1433073017145.png)
#####Math.floor
![Alt text](img/1433073043355.png)
>ceil向上取整
>round实现四舍五入
####Math.random
![Alt text](img/1433073120057.png)
####JSON
![Alt text](img/1433073174391.png)
#####JSON.stringify
![Alt text](img/1433073212236.png)
#####JSON.parse
![Alt text](img/1433073267411.png)
>想进一步了解对象常用属性和方法的同学，可以通过W3C或者MDN网站进行学习
http://www.w3school.com.cn/jsref/jsref_obj_math.asp
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects
###全局对象
![Alt text](img/1433073470231.png)

####NaN
![Alt text](img/1433073528831.png)
####parseInt
![Alt text](img/1433073605093.png)
####eval
![Alt text](img/1433073627076.png)
####encodedURIComponent
![Alt text](img/1433073750640.png)














 









	




 
