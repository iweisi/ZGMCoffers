
<link rel="stylesheet" type="text/css" href="./style/css/index.css">

<div align="center">  

<img src="https://ws1.sinaimg.cn/large/0069RVTdly1fubocn5pxaj30go082dg1.jpg" width=""/> 
<br/>

[![Build Status](https://travis-ci.org/zgm1547497656/ZGMCoffers.svg?branch=master)](https://travis-ci.org/zgm1547497656/ZGMCoffers)
[![QQ群](https://img.shields.io/badge/QQ%E7%BE%A4-787381170-yellowgreen.svg)]

[qq0groupsvg]: https://img.shields.io/badge/QQ%E7%BE%A4-787381170-yellowgreen.svg
[qq0group]: https://jq.qq.com/?_wv=1027&k=5HPYvQk

</div><br>


> `Java Coffers`： Java 小金库。

**访问这里获取更好的阅读体验**：[博客还没有]

<br/>

<div class="wrap">
	<div class="logo">
	 <h1><a href="#"><img src="./style/images/code.png"></a></h1>
	</div>
	<p>鼠标移入侧边栏，二级菜单3D展开</br>鼠标hover背景变色</br>鼠标移入二维码背景变色</p>

</div>
<div class="nav-main">
<div class="nav-box">
<div class="nav">
  <ul class="nav-ul">
  	<li><a href="#" class="home"><span>首页</span></a></li>
  	<li><a href="#" class="develop"><span>H5开发</span></a></li>
  	<li><a href="#" class="wechat"><span>微信推广</span></a></li>
  	<li><a href="#" class="case"><span>项目案例</span></a></li>
  	<li><a href="#" class="news"><span>信息资讯</span></a></li>
  	<li><a href="#" class="contact"><span>关于我们</span></a></li>
  </ul>
</div>
<div class="nav-slide">
    <div class="nav-slide-o"></div>
    <div class="nav-slide-o">
    	<ul>
    		<li><a href="#"><span>微信开发</span></a></li>
    		<li><a href="#"><span>微信开发</span></a></li>
    		<li><a href="#"><span>微信开发</span></a></li>
    		<li><a href="#"><span>微信开发</span></a></li>
    		<li><a href="#"><span>微信开发</span></a></li>
    		<li><a href="#"><span>微信开发</span></a></li>
    		<li><a href="#"><span>微信开发</span></a></li>
    		<li><a href="#"><span>微信开发</span></a></li>
    		<li><a href="#"><span>微信开发</span></a></li>
    		<li><a href="#"><span>微信开发</span></a></li>
    	</ul>
    </div>
    <div class="nav-slide-o">
    	<ul>
    		<li><a href="#"><span>微信关注</span></a></li>
    		<li><a href="#"><span>微信关注</span></a></li>
    		<li><a href="#"><span>微信关注</span></a></li>
    		<li><a href="#"><span>微信关注</span></a></li>
    		<li><a href="#"><span>微信关注</span></a></li>
    		<li><a href="#"><span>微信关注</span></a></li>
    		<li><a href="#"><span>微信关注</span></a></li>
    		<li><a href="#"><span>微信关注</span></a></li>
    	</ul>
    </div>
    <div class="nav-slide-o">
    	<ul>
    		<li><a href="#"><span>网站设计</span></a></li>
    		<li><a href="#"><span>网站设计</span></a></li>
    		<li><a href="#"><span>网站设计</span></a></li>
    		<li><a href="#"><span>网站设计</span></a></li>
    		<li><a href="#"><span>网站设计</span></a></li>
    		<li><a href="#"><span>网站设计</span></a></li>
    		<li><a href="#"><span>网站设计</span></a></li>
    		<li><a href="#"><span>网站设计</span></a></li>
    		<li><a href="#"><span>网站设计</span></a></li>
    	</ul>
    </div>
    <div class="nav-slide-o">
    	<ul>
    		<li><a href="#"><span>企业建站</span></a></li>
    		<li><a href="#"><span>企业建站</span></a></li>
    		<li><a href="#"><span>企业建站</span></a></li>
    		<li><a href="#"><span>企业建站</span></a></li>
    		<li><a href="#"><span>企业建站</span></a></li>
    		<li><a href="#"><span>企业建站</span></a></li>
    		<li><a href="#"><span>企业建站</span></a></li>
    		<li><a href="#"><span>企业建站</span></a></li>
    		<li><a href="#"><span>企业建站</span></a></li>
    	</ul>
    </div>
</div>
</div>
</div>

<script type="text/javascript" src="./style/js/jquery-1.9.1.min.js"></script>
<script type="text/javascript">
	$(function(){
	var thisTime;
	$('.nav-ul li').mouseleave(function(even){
			thisTime	=	setTimeout(thisMouseOut,1000);
	})

	$('.nav-ul li').mouseenter(function(){
		clearTimeout(thisTime);
		var thisUB	=	$('.nav-ul li').index($(this));
		if($.trim($('.nav-slide-o').eq(thisUB).html()) != "")
		{
			$('.nav-slide').addClass('hover');
			$('.nav-slide-o').hide();
			$('.nav-slide-o').eq(thisUB).show();
		}
		else{
			$('.nav-slide').removeClass('hover');
		}
		
	})
	
	function thisMouseOut(){
		$('.nav-slide').removeClass('hover');
	}
	 
	$('.nav-slide').mouseenter(function(){
		clearTimeout(thisTime);
		$('.nav-slide').addClass('hover');
	})
	$('.nav-slide').mouseleave(function(){
		$('.nav-slide').removeClass('hover');
	})

})
</script>



| 📊 |⚔️ | 🖥 | 🚏 | 🏖  | 🌁| 📮 | 🔍 | 🚀 | <img src="style/images/fujiajineng.jpg" title='images' style='max-width:600px'></img>  |💡
| :--------: | :---------: | :---------: | :---------: | :---------: | :---------:| :---------: | :-------: | :-------:| :------:|:------:|
| [集合](#常用集合) | [多线程](#java-多线程)|[JVM](#jvm) | [分布式](#分布式相关) |[框架](#常用框架第三方组件)|[架构设计](#架构设计)| [数据库](#db-相关) |[算法](#数据结构与算法)|[Netty](#netty-相关)| [附加技能](#附加技能)|[联系作者](#联系作者) |



### 常用集合
- [ArrayList/Vector](https://github.com/zgm1547497656/ZGMCoffers/blob/master/MD/ArrayList.md)
- [LinkedList](https://github.com/zgm1547497656/ZGMCoffers/master/blob/MD/LinkedList.md)
- [HashMap](https://github.com/zgm1547497656/ZGMCoffers/blob/master/MD/HashMap.md)
- [HashSet](https://github.com/zgm1547497656/ZGMCoffers/blob/master/MD/collection/HashSet.md)
- [LinkedHashMap](https://github.com/zgm1547497656/ZGMCoffers/blob/master/MD/collection/LinkedHashMap.md)

### Java 多线程
- [多线程中的常见问题](https://github.com/zgm1547497656/ZGMCoffers/blob/master/MD/Thread-common-problem.md)
- [synchronized 关键字原理](https://github.com/zgm1547497656/ZGMCoffers/blob/master/MD/Synchronize.md)
- [多线程的三大核心](https://github.com/zgm1547497656/ZGMCoffers/blob/master/MD/Threadcore.md)
- [对锁的一些认知](https://github.com/zgm1547497656/ZGMCoffers/blob/master/MD/Java-lock.md)
- [ReentrantLock 实现原理 ](https://github.com/zgm1547497656/ZGMCoffers/blob/master/MD/ReentrantLock.md)
- [ConcurrentHashMap 的实现原理](https://github.com/zgm1547497656/ZGMCoffers/blob/master/MD/ConcurrentHashMap.md)
- [如何优雅的使用和理解线程池](https://github.com/zgm1547497656/ZGMCoffers/blob/master/MD/ThreadPoolExecutor.md)
- [深入理解线程通信](https://github.com/zgm1547497656/ZGMCoffers/blob/master/MD/concurrent/thread-communication.md)

### JVM
- [Java 运行时内存划分](https://github.com/zgm1547497656/ZGMCoffers/blob/master/MD/MemoryAllocation.md)
-  [类加载机制](https://github.com/zgm1547497656/ZGMCoffers/blob/master/MD/ClassLoad.md)
-  [OOM 分析](https://github.com/zgm1547497656/ZGMCoffers/blob/master/MD/OOM-analysis.md)
- [垃圾回收](https://github.com/zgm1547497656/ZGMCoffers/blob/master/MD/GarbageCollection.md)
- [对象的创建与内存分配](https://github.com/zgm1547497656/ZGMCoffers/blob/master/MD/newObject.md)
- [你应该知道的 volatile 关键字](https://github.com/zgm1547497656/ZGMCoffers/blob/master/MD/concurrent/volatile.md)
- [一次内存溢出排查优化实战](https://crossoverjie.top/2018/08/29/java-senior/OOM-Disruptor/)

### 分布式相关

- [分布式限流](http://crossoverjie.top/2018/04/28/sbc/sbc7-Distributed-Limit/)
- [基于 Redis 的分布式锁](http://crossoverjie.top/2018/03/29/distributed-lock/distributed-lock-redis/)
- [分布式缓存设计](https://github.com/zgm1547497656/ZGMCoffers/blob/master/MD/Cache-design.md)
- [分布式 ID 生成器](https://github.com/zgm1547497656/ZGMCoffers/blob/master/MD/ID-generator.md)

### 常用框架\第三方组件

- [Spring Bean 生命周期](https://github.com/zgm1547497656/ZGMCoffers/blob/master/MD/spring/spring-bean-lifecycle.md)
- [Spring AOP 的实现原理](https://github.com/zgm1547497656/ZGMCoffers/blob/master/MD/SpringAOP.md) 
- [Guava 源码分析（Cache 原理）](https://crossoverjie.top/2018/06/13/guava/guava-cache/)
- [轻量级 HTTP 框架](https://github.com/crossoverJie/cicada)
- [Kakfa produce 源码分析](https://github.com/crossoverJie/JCSprout/blob/master/MD/kafka/kafka-product.md)
- SpringBoot 启动过程
- Tomcat 类加载机制


### 架构设计
- [秒杀系统设计](https://github.com/zgm1547497656/ZGMCoffers/blob/master/MD/Spike.md)
- [秒杀架构实践](http://crossoverjie.top/2018/05/07/ssm/SSM18-seconds-kill/)
- [设计一个百万级的消息推送系统](https://github.com/zgm1547497656/ZGMCoffers/blob/master/MD/architecture-design/million-sms-push.md)

### DB 相关

- [MySQL 索引原理](https://github.com/zgm1547497656/ZGMCoffers/blob/master/MD/MySQL-Index.md)
- [SQL 优化](https://github.com/zgm1547497656/ZGMCoffers/blob/master/MD/SQL-optimization.md)
- [数据库水平垂直拆分](https://github.com/zgm1547497656/ZGMCoffers/blob/master/MD/DB-split.md)

### 数据结构与算法
- [红包算法](https://github.com/zgm1547497656/ZGMCoffers/blob/master/src/main/java/com/crossoverjie/red/RedPacket.java)
- [二叉树层序遍历](https://github.com/zgm1547497656/ZGMCoffers/blob/master/src/main/java/com/crossoverjie/algorithm/BinaryNode.java#L76-L101)
- [是否为快乐数字](https://github.com/zgm1547497656/ZGMCoffers/blob/master/src/main/java/com/crossoverjie/algorithm/HappyNum.java#L38-L55)
- [链表是否有环](https://github.com/zgm1547497656/ZGMCoffers/blob/master/src/main/java/com/crossoverjie/algorithm/LinkLoop.java#L32-L59)
- [从一个数组中返回两个值相加等于目标值的下标](https://github.com/zgm1547497656/ZGMCoffers/blob/master/src/main/java/com/crossoverjie/algorithm/TwoSum.java#L38-L59)
- [一致性 Hash 算法](https://github.com/zgm1547497656/ZGMCoffers/blob/master/MD/Consistent-Hash.md)
- [限流算法](https://github.com/zgm1547497656/ZGMCoffers/blob/master/MD/Limiting.md)
- [三种方式反向打印单向链表](https://github.com/zgm1547497656/ZGMCoffers/blob/master/src/main/java/com/crossoverjie/algorithm/ReverseNode.java)
- [合并两个排好序的链表](https://github.com/zgm1547497656/ZGMCoffers/blob/master/src/main/java/com/crossoverjie/algorithm/MergeTwoSortedLists.java)
- [两个栈实现队列](https://github.com/zgm1547497656/ZGMCoffers/blob/master/src/main/java/com/crossoverjie/algorithm/TwoStackQueue.java)
- [动手实现一个 LRU cache](http://crossoverjie.top/2018/04/07/algorithm/LRU-cache/)
- [链表排序](./src/main/java/com/crossoverjie/algorithm/LinkedListMergeSort.java)
- [数组右移 k 次](./src/main/java/com/crossoverjie/algorithm/ArrayKShift.java)
-  [交替打印奇偶数](https://github.com/zgm1547497656/ZGMCoffers/blob/master/src/main/java/com/crossoverjie/actual/TwoThread.java)

### Netty 相关
- [SpringBoot 整合长连接心跳机制](https://crossoverjie.top/2018/05/24/netty/Netty(1)TCP-Heartbeat/)
- [从线程模型的角度看 Netty 为什么是高性能的？](https://crossoverjie.top/2018/07/04/netty/Netty(2)Thread-model/)

### 附加技能

- [TCP/IP 协议](https://github.com/zgm1547497656/ZGMCoffers/blob/master/MD/TCP-IP.md)
- [如何高效的使用 Git](https://github.com/zgm1547497656/ZGMCoffers/blob/master/MD/additional-skills/how-to-use-git-efficiently.md)


### 联系作者

> 

<img src="" width="300"/> 
