**目录**：

>笔记持续更新，原地址: https://github.com/Niefee/Wangyi-Note ;

<ul>
<li><a href="#技术选型">技术选型</a><ul>
<li><a href="#模块化">模块化</a><ul>
<li><a href="#模块组织">模块组织</a></li>
</ul>
</li>
<li><a href="#模块系统">模块系统</a><ul>
<li><a href="#amd优点缺点">AMD优点、缺点</a></li>
<li><a href="#es6-module">ES6 module</a></li>
<li><a href="#systemjs">systemJS</a></li>
</ul>
</li>
<li><a href="#框架">框架</a><ul>
<li><a href="#库">库</a></li>
<li><a href="#框架-1">框架</a></li>
<li><a href="#解决方案">解决方案</a></li>
<li><a href="#dom">DOM</a></li>
<li><a href="#框架-2">框架</a><ul>
<li><a href="#dom专业领域">DOM专业领域</a></li>
<li><a href="#communiction">Communiction</a></li>
<li><a href="#reqwest">Reqwest</a></li>
<li><a href="#qwest">qwest</a></li>
</ul>
</li>
<li><a href="#ullty">Ullty</a></li>
<li><a href="#extension">Extension</a></li>
<li><a href="#模版">模版</a></li>
<li><a href="#component">Component</a></li>
<li><a href="#routing">Routing</a></li>
<li><a href="#architecture">ARchitecture</a></li>
</ul>
</li>
</ul>
</li>
</ul>
#技术选型
##模块化
###模块组织
![Alt text](img/1436665946872.png)
**模块**
 - 封装实现
 - 暴露接口
 - 生命依赖

##模块系统
 - 依赖管理（加载、分析、注入、初始化）
 - 决定模块写法

![Alt text](img/1436667359891.png)

**有点**
 - 依赖管理成熟可靠
 - 社区活跃，规范接受度高
 - 运行时支持，模块定义非常简单
 - 文件级的模块作用域隔离
 - 可以处理循环依赖

**缺点**
 - 不是标准组织规范
 - 同步的require，没有考虑浏览器环境

![Alt text](img/1436667740253.png)
![Alt text](img/1436667911713.png)
![Alt text](img/1436667950065.png)

###AMD优点、缺点
![Alt text](img/1436668049552.png)
![Alt text](img/1436668100051.png)

###ES6 module
![Alt text](img/1436668190659.png)
![Alt text](img/1436668228773.png)
![Alt text](img/1436668255542.png)

###systemJS
![Alt text](img/1436668972926.png)

##框架
###库
![Alt text](img/1436669545302.png)
###框架
![Alt text](img/1436669650601.png)
![Alt text](img/1436669676391.png)
![Alt text](img/1436669695863.png)
###解决方案
![Alt text](img/1436669778078.png)
![Alt text](img/1436669876608.png)
**什么时候放弃？**
![Alt text](img/1436669951965.png)

![Alt text](img/1436670111819.png)


###DOM
![Alt text](img/1436670231474.png)
###框架
![Alt text](img/1436671426177.png)
**轻量级**
![Alt text](img/1436671466935.png)
![Alt text](img/1436671489507.png)
**对比**
![Alt text](img/1436671790864.png)
![Alt text](img/1436671862367.png)
####DOM专业领域
![Alt text](img/1436671967205.png)
####Communiction
![Alt text](img/1436672048324.png)
![Alt text](img/1436672059786.png)
####Reqwest
![Alt text](img/1436672213083.png)
![Alt text](img/1436672292454.png)

####qwest
![Alt text](img/1436672307506.png)
![Alt text](img/1436672352382.png)
![Alt text](img/1436672469642.png)

###Ullty
![Alt text](img/1436672587314.png)

###Extension 
![Alt text](img/1436672797185.png)

###模版
![Alt text](img/1436673430696.png)
###Component
![Alt text](img/1436673561282.png)
![Alt text](img/1436673682723.png)
###Routing
![Alt text](img/1436673855158.png)
![Alt text](img/1436674530385.png)
###ARchitecture
![Alt text](img/1436674687856.png)


