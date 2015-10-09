**目录**：

>笔记持续更新，原地址 : https://github.com/Niefee/Wangyi-Note ;

<ul>
<li><a href="#数据存储">数据存储</a><ul>
<li><a href="#cookie">cookie</a></li>
<li><a href="#storage">storage</a></li>
</ul>
</li>
</ul>

#数据存储
##cookie
![Alt text](img/1435566665013.png)
>大小在4kb左右，由键值对构成，用分号（；）跟空格隔开。

![Alt text](img/1435566763070.png)
 
 - 浏览器端
![Alt text](img/1435566820356.png)

 - 属性
 
![Alt text](img/1435566879211.png)

>Expires表示时间戳，Max-Age是表示以毫秒为单位的时间长度。

 - 作用域
![Alt text](img/1435566927701.png)

 - 作用路径
![Alt text](img/1435566984167.png)

 - 读取

![Alt text](img/1435567019263.png)

 - 设置/修改
![Alt text](img/1435567051417.png)

 - 删除
![Alt text](img/1435567083597.png)
>name\path\domain是唯一标示一个cookie的。


 - 缺陷
	 - 流量代价
	 - 安全性问题
	 - 大小限制

##storage
 - localStorage
	有效期是永久
	
 - sessionStorage
	有效期是浏览器的会话时间

 - 作用域
![Alt text](img/1435567531871.png)

 - 大小
**5MB**

 - javascript对象
![Alt text](img/1435567592308.png)

 - API
![Alt text](img/1435567640899.png)
![Alt text](img/1435567665110.png)

 - 实例
![Alt text](img/1435573196087.png)
![Alt text](img/1435573246386.png)
