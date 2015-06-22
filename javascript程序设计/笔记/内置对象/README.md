#简介

>笔记持续更新，原地址:  https://github.com/Niefee/Wangyi-Note ;

<ul>
<li><a href="#内置对象">内置对象</a><ul>
<li><a href="#简介">简介</a></li>
<li><a href="#object">Object</a><ul>
<li><a href="#objectcreate">Object.create</a></li>
<li><a href="#objectprototypetostring">Object.prototype.toString</a></li>
<li><a href="#objectprototypehasownproperty">Object.prototype.hasOwnProperty</a></li>
<li><a href="#booleannumberstring">Boolean\Number\String</a><ul>
<li><a href="#boolean">Boolean</a></li>
<li><a href="#string">String</a><ul>
<li><a href="#stringprototypeindex">String.prototype.index</a></li>
<li><a href="#stringprototypereplace">String.prototype.replace</a></li>
<li><a href="#stringprototypesplit">String.prototype.split</a></li>
</ul>
</li>
<li><a href="#number">Number</a><ul>
<li><a href="#numberprotoytypetofixed">Number.protoytype.toFixed</a></li>
</ul>
</li>
</ul>
</li>
</ul>
</li>
<li><a href="#array">Array</a><ul>
<li><a href="#arrayprototypesplice">Array..prototype.splice</a></li>
<li><a href="#arrayprototypeforeach">Array.prototype.forEach</a></li>
</ul>
</li>
<li><a href="#function">Function</a><ul>
<li><a href="#自定义对象构造器">自定义对象构造器</a></li>
<li><a href="#functionprototypeapply">Function.prototype.apply</a></li>
<li><a href="#functionprototypebind">Function.prototype.bind</a></li>
<li><a href="#子类构造器">子类构造器</a></li>
<li><a href="#函数调用">函数调用</a></li>
<li><a href="#arguments">arguments</a></li>
<li><a href="#值传递">值传递</a></li>
<li><a href="#函数重载">函数重载</a></li>
</ul>
</li>
<li><a href="#regexpdateerror">RegExp、Date、Error</a><ul>
<li><a href="#regexp">RegExp</a><ul>
<li><a href="#regexpprototypetest">RegExp.prototype.test</a></li>
</ul>
</li>
<li><a href="#date">Date</a></li>
</ul>
</li>
<li><a href="#mathjson">Math\JSON</a><ul>
<li><a href="#mathfloor">Math.floor</a></li>
<li><a href="#mathrandom">Math.random</a></li>
</ul>
</li>
<li><a href="#json">JSON</a><ul>
<li><a href="#jsonstringify">JSON.stringify</a></li>
<li><a href="#jsonparse">JSON.parse</a></li>
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

##内置对象
###简介
![Alt text](img/1433922022267.png)
>“a&b&c”是字符串字面量，调用了split这个方法。
>只有对象才可以调用方法跟属性。

![Alt text](img/1433922237277.png)
![Alt text](img/1433922260426.png)

###Object
![Alt text](img/1433922481932.png)

####Object.create
![Alt text](img/1433922557728.png)

####Object.prototype.toString
![Alt text](img/1433922686031.png)
**toString()**函数用于将当前对象以字符串的形式返回。

该方法属于Object对象，由于所有的对象都"继承"了Object的对象实例，因此几乎所有的实例对象都可以使用该方法。

>参考：http://www.cnblogs.com/muguaworld/archive/2008/07/18/1246338.html 。

####Object.prototype.hasOwnProperty
![Alt text](img/1433922806161.png)

####Boolean\Number\String
#####Boolean
![Alt text](img/1433922986196.png)
![Alt text](img/1433923021597.png)

#####String
![Alt text](img/1433923110028.png)
######String.prototype.index
![Alt text](img/1433923260295.png)
######String.prototype.replace
![Alt text](img/1433923354187.png)
######String.prototype.split
![Alt text](img/1433923489489.png)

#####Number
![Alt text](img/1433923559529.png)
######Number.protoytype.toFixed
![Alt text](img/1433923617211.png)

###Array
![Alt text](img/1433936183877.png)
>isArray用来判断对象是否是数组。

####Array..prototype.splice
![Alt text](img/1433936335603.png)
####Array.prototype.forEach
![Alt text](img/1433939757622.png)

###Function
![Alt text](img/1433991291104.png)
####自定义对象构造器
![Alt text](img/1433991394990.png)
![Alt text](img/1433991431543.png)

####Function.prototype.apply
![Alt text](img/1433991515896.png)
![Alt text](img/1433991619220.png)

####Function.prototype.bind
![Alt text](img/1433991741784.png)

####子类构造器
![Alt text](img/1433991857270.png)
####函数调用
![Alt text](img/1433991923902.png)
####arguments
![Alt text](img/1433992050992.png)
####值传递
![Alt text](img/1433993217680.png)
![Alt text](img/1433993302806.png)
####函数重载
![Alt text](img/1433993597791.png)

###RegExp、Date、Error
####RegExp
![Alt text](img/1433993967360.png)
#####RegExp.prototype.test
![Alt text](img/1433994056828.png)

####Date
![Alt text](img/1433994095887.png)

###Math\JSON
![Alt text](img/1433994169601.png)

####Math.floor
![Alt text](img/1433994217144.png)
>ceil是向上取整，round是四舍五入。

####Math.random
![Alt text](img/1433994281869.png)

###JSON
![Alt text](img/1433994302024.png)

####JSON.stringify
![Alt text](img/1433994346099.png)
####JSON.parse
![Alt text](img/1433994743203.png)
###全局对象
![Alt text](img/1433994810288.png)

####NaN
![Alt text](img/1433994846574.png)
![Alt text](img/1433994861754.png)
![Alt text](img/1433994873091.png)
![Alt text](img/1433994894141.png)

####parseInt
![Alt text](img/1433994939256.png)
![Alt text](img/1433994950853.png)

####eval
![Alt text](img/1433994997101.png)
>因为安全性，一般不建议使用。

####encodedURIComponent
![Alt text](img/1433995122302.png)



