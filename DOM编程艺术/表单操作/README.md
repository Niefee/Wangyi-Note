**目录**：

>笔记持续更新，原地址 : https://github.com/Niefee/Wangyi-Note ;

<ul>
<li><a href="#表单操作">表单操作</a><ul>
<li><a href="#表单元素">表单元素</a><ul>
<li><a href="#构建表单">构建表单</a></li>
<li><a href="#服务器处理">服务器处理</a></li>
<li><a href="#配置表单">配置表单</a></li>
<li><a href="#元素">元素</a><ul>
<li><a href="#form">form</a></li>
</ul>
</li>
</ul>
</li>
<li><a href="#表单验证">表单验证</a><ul>
<li><a href="#element">element</a></li>
</ul>
</li>
<li><a href="#表单提交">表单提交</a><ul>
<li><a href="#提交">提交</a></li>
</ul>
</li>
<li><a href="#表单应用">表单应用</a></li>
</ul>
</li>
</ul>
#表单操作
##表单元素
###构建表单
![Alt text](img/1436530370247.png)
###服务器处理
![Alt text](img/1436530455551.png)
###配置表单
![Alt text](img/1436530571919.png)
**优化表单**
![Alt text](img/1436530681042.png)
###元素

![Alt text](img/1436530763917.png)
####form
 - name
		var pizzaForm=document.form.pizza;

 - autocomplete
		![Alt text](img/1436530982989.png)

 - elements
	 - 1、该表单子孙表单控件（出图片按钮<input type="image"）
	如下：button、fieldset、input、keygen、output、select、textarea
	 
	 - 2、归属于该表单的表单控件（除图片按钮）
	
	![Alt text](img/1436531463137.png)

>elements.length表示包含的元素的个数。

![Alt text](img/1436531615978.png)
	
 - form[name]
![Alt text](img/1436531707589.png)
![Alt text](img/1436531840890.png)

 - reset()
![Alt text](img/1436532013112.png)

 - label
 ![Alt text](img/1436532091347.png)

	 - htmlFor
	![Alt text](img/1436532221633.png)

	 - control
	![Alt text](img/1436532458731.png)

	 - form
	![Alt text](img/1436532621450.png)


 - input
	 - type
	![Alt text](img/1436532701488.png)
**支持属性**
![Alt text](img/1436532758391.png)
![Alt text](img/1436532779030.png)

	 - 本地图片预览
![Alt text](img/1436532979465.png)

 - select
![Alt text](img/1436533187878.png)
![Alt text](img/1436533526206.png)
![Alt text](img/1436533614797.png)
![Alt text](img/1436533705266.png)
![Alt text](img/1436533751794.png)

	 - 级联下拉选择器
![Alt text](img/1436533899155.png)
![Alt text](img/1436533910955.png)



 - textarea
![Alt text](img/1436534131013.png)
![Alt text](img/1436534271238.png)
>backward表示用selectionStart调整。

![Alt text](img/1436534455373.png)

**补充**
![Alt text](img/1436534487531.png)


##表单验证
![Alt text](img/1436598464852.png)
###element
![Alt text](img/1436598493172.png)
![Alt text](img/1436598614339.png)

 - 自定义异常
	 - oninvalid
	 - setCustomValidity

![Alt text](img/1436607029291.png)
![Alt text](img/1436598904038.png)

![Alt text](img/1436606888492.png)
>type是为了唤出数字键盘，在form表单中加novalidate是为了在表单提交时，对所有表单元素做表单验证。

##表单提交
![Alt text](img/1436607689480.png)
>按下回车可以隐性提交。

###提交

 - 提交过程
	 - 根据表单enctype指定的值构建要提交的数据结构。
	 - 使用method指定的方式发送数据到 action指定的目标。

![Alt text](img/1436607882040.png)
![Alt text](img/1436607919868.png)

 - 提交方式
![Alt text](img/1436608021350.png)

![Alt text](img/1436608066352.png)
![Alt text](img/1436608090710.png)
![Alt text](img/1436608129455.png)

 - 特殊案例
![Alt text](img/1436608219803.png)
![Alt text](img/1436608349296.png)

 - submit\onsubmit
![Alt text](img/1436608432528.png)
![Alt text](img/1436608457069.png)

 - 无刷新表单提交
![Alt text](img/1436608528905.png)
![Alt text](img/1436608568383.png)

##表单应用
![Alt text](img/1436609021022.png)

 - 实例
![Alt text](img/1436609120978.png)
![Alt text](img/1436609173476.png)

 - 通用方法
![Alt text](img/1436609209429.png)
![Alt text](img/1436609239225.png)
![Alt text](img/1436609262303.png)
![Alt text](img/1436609271888.png)

 - 验证手机号
![Alt text](img/1436609387322.png)

 - 验证密码
![Alt text](img/1436609476398.png)

 - 表单提交
![Alt text](img/1436609549441.png)

 - 状态恢复
![Alt text](img/1436609570836.png)

 - 利用IFrame无刷新提交表单
![Alt text](img/1436609712089.png)
![Alt text](img/1436609728134.png)

