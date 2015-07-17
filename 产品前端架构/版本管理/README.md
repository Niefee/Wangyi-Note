**目录**：

>笔记持续更新，原地址 : https://github.com/Niefee/Wangyi-Note ;

<ul>
<li><a href="#版本管理">版本管理</a><ul>
<li><a href="#简介">简介</a></li>
<li><a href="#版本控制系统">版本控制系统</a><ul>
<li><a href="#人肉vcs">人肉VCS</a></li>
<li><a href="#local-vcs-本地式">Local VCS-本地式</a></li>
<li><a href="#cvcs-集中式">CVCS-集中式</a></li>
<li><a href="#dvcs-分布式">DVCS-分布式</a></li>
</ul>
</li>
<li><a href="#分支模型">分支模型</a><ul>
<li><a href="#分支模型-1">分支模型</a></li>
</ul>
</li>
<li><a href="#git">git</a><ul>
<li><a href="#优势">优势</a></li>
<li><a href="#git命令">git命令</a></li>
<li><a href="#基本操作">基本操作</a><ul>
<li><a href="#git-init">git-init</a></li>
<li><a href="#git-status">git-status</a></li>
<li><a href="#git-add">git-add</a></li>
<li><a href="#git-rm">git-rm</a></li>
<li><a href="#暂存区">暂存区</a></li>
<li><a href="#git-commit">git-commit</a></li>
<li><a href="#git-log">git-log</a></li>
<li><a href="#git-diff">git-diff</a></li>
<li><a href="#撤销本地修改">撤销本地修改</a></li>
<li><a href="#撤销暂存区的内容">撤销暂存区的内容</a></li>
<li><a href="#撤销全部改动">撤销全部改动</a></li>
</ul>
</li>
<li><a href="#分支操作">分支操作</a><ul>
<li><a href="#git-branch">git-branch</a></li>
<li><a href="#git-reset">git-reset</a></li>
<li><a href="#git-stash">git-stash</a></li>
<li><a href="#git-merge">git merge</a></li>
<li><a href="#git-rebase">git-rebase</a></li>
<li><a href="#git-tag">git tag</a></li>
</ul>
</li>
<li><a href="#远程操作">远程操作</a></li>
</ul>
</li>
</ul>
</li>
</ul>
#版本管理
>网上一个比较简单易懂的课程： http://www.imooc.com/learn/390 。

##简介
![Alt text](img/1435806239814.png)

##版本控制系统
![Alt text](img/1435806280786.png)
###人肉VCS
![Alt text](img/1435806318825.png)

###Local VCS-本地式
![Alt text](img/1435806380238.png)

###CVCS-集中式
![Alt text](img/1435806446706.png)

###DVCS-分布式
![Alt text](img/1435806492833.png)

##分支模型
![Alt text](img/1435806742562.png)
![Alt text](img/1435806779478.png)

###分支模型
![Alt text](img/1435806982680.png)

![Alt text](img/1435807107459.png)
![Alt text](img/1435807190335.png)
>测试环境使用release/develop  ment分支，预发布环境使用release分支，生产环境使用master分支。

##git
![Alt text](img/1435807393719.png)
![Alt text](img/1435807451607.png)
###优势

 - 快
 - 完全的分布式
 - 轻量级的分支操作
 - Git已经成为现实意义上的标准
 - 社区成熟活跃

>**git ≠ github ** 。

**安装**
 - window：msysgit  http://msysgit.github.io .

>help、config、status、init、add、rm、commit、log、diff、File级别的checkout、reset 。

###git命令 
![Alt text](img/1435807942833.png)
![Alt text](img/1435807955317.png)

###基本操作
![Alt text](img/1435808055733.png)

####git-init
![Alt text](img/1435808144343.png)

####git-status
![Alt text](img/1435822489192.png)

####git-add
![Alt text](img/1435822573430.png)
![Alt text](img/1435822639413.png)
![Alt text](img/1435822684214.png)

####git-rm
![Alt text](img/1435822752390.png)
![Alt text](img/1435822803962.png)

####暂存区
![Alt text](img/1435823064597.png)

####git-commit
![Alt text](img/1435823131863.png)

####git-log
![Alt text](img/1435823271598.png)

####git-diff
![Alt text](img/1435823384989.png)

####撤销本地修改
![Alt text](img/1435823455519.png)

####撤销暂存区的内容
![Alt text](img/1435823520762.png)

####撤销全部改动
![Alt text](img/1435823609333.png)

**总结**
![Alt text](img/1435823680539.png)

###分支操作
####git-branch
![Alt text](img/1435838113525.png)

####git-reset
![Alt text](img/1435838371261.png)
![Alt text](img/1435838389227.png)
![Alt text](img/1435838481612.png)
![Alt text](img/1435838536367.png)

**reset vs checkout**
![Alt text](img/1435838621491.png)

####git-stash
![Alt text](img/1435839255126.png)

####git merge
![Alt text](img/1435839898831.png)

####git-rebase
![Alt text](img/1435839953028.png)
![Alt text](img/1435839985530.png)

**rebase vs merge**
![Alt text](img/1435840015826.png)

####git tag
![Alt text](img/1435840206026.png)

###远程操作
![Alt text](img/1435840659245.png)
