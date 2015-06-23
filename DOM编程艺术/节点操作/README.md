**目录**：

>笔记持续更新，原地址 : https://github.com/Niefee/Wangyi-Note ;

<ul>
<li><a href="#节点操作">节点操作</a><ul>
<li><a href="#获取节点">获取节点</a><ul>
<li><a href="#getelementbyid">getElementById</a></li>
<li><a href="#gerelementbytabname">gerElementByTabName</a></li>
<li><a href="#getelementbyclassname">getElementByClassName</a></li>
<li><a href="#queryselector-all">querySelector /All</a></li>
</ul>
</li>
<li><a href="#创建节点">创建节点</a><ul>
<li><a href="#createelement">createElement</a></li>
</ul>
</li>
<li><a href="#修改节点">修改节点</a></li>
<li><a href="#添加节点">添加节点</a><ul>
<li><a href="#appendchild">appendChild</a></li>
<li><a href="#insertbefore">insertBefore</a></li>
</ul>
</li>
<li><a href="#删除节点">删除节点</a><ul>
<li><a href="#removechild">removeChild</a></li>
</ul>
</li>
<li><a href="#innerhtml">innerHTML</a></li>
</ul>
</li>
</ul>
#节点操作
##获取节点
![Alt text](img/1435027057882.png)
![Alt text](img/1435027149674.png)
>通过DOM 获取节点，可维护性更强。

###getElementById
![Alt text](img/1435027303455.png)

###gerElementByTabName
![Alt text](img/1435027486802.png)
**可通过下标获取指定元素**
![Alt text](img/1435027582838.png)
>这里获取去了 **li.user.last ** 这个节点。

![Alt text](img/1435027848883.png)
>集合是活的。

###getElementByClassName
![Alt text](img/1435028075359.png)

**就版本兼容方案**
![Alt text](img/1435028265826.png)

###querySelector /All
![Alt text](img/1435028553369.png)
>静态的选择器。

 - 小结
![Alt text](img/1435028739376.png)

##创建节点
![Alt text](img/1435028877280.png)
###createElement
![Alt text](img/1435029469825.png)
![Alt text](img/1435029526712.png)
##修改节点
![Alt text](img/1435029674093.png)
>Kash变成了Tom，ie9及以下不支持

可以使用**element.innerText**替代，但火狐不支持。

![Alt text](img/1435030043239.png)

解决方案：
![Alt text](img/1435029990104.png)

##添加节点
###appendChild
![Alt text](img/1435030147876.png)
###insertBefore
![Alt text](img/1435030389524.png)

##删除节点
###removeChild
![Alt text](img/1435030909211.png)

##innerHTML
![Alt text](img/1435031015759.png)

 - 安全问题
 ![Alt text](img/1435031277311.png)

>建议只用于新节点。





