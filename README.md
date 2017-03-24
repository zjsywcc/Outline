JAVA：
======
### 基本语法
1. static
  - 修饰变量 方法
  - 静态块(初始化块 构造函数 [区别](http://www.cnblogs.com/BlackStorm/p/5699965.html))
  - 静态内部类([内部类](https://www.cnblogs.com/chenssy/p/3388487.html))
  - 静态导包
2. final([String类分析](http://www.hollischuang.com/archives/99))
3. transient([transient小记](http://www.cnblogs.com/lanxuezaipiao/p/3369962.html))
4. foreach循环原理([foreach循环原理](http://www.cnblogs.com/xrq730/p/4868465.html))
5. volatile底层实现([volatile原理](http://ifeve.com/volatile/))
6. equals和hashcode([在Java中正确地使用equals()和hashCode()方法](http://boxingp.github.io/blog/2015/02/24/use-equals-and-hashcode-methods-in-java-correctly/),[Java中的equals()和hashcode()之间关系](http://www.hollischuang.com/archives/1290) [java提高篇(十三)-----equals()方法总结](http://www.cnblogs.com/chenssy/p/3416195.html) [如何在JAVA中避免EQUALS方法的隐藏陷阱](http://coolshell.cn/articles/1051.html))
7. string,stringbuffer和stringbuilder([Java 基础之 String、StringBuilder、StringBuffer、CharSequence 区别](https://github.com/android-cn/android-discuss/issues/5),[Java：String、StringBuffer和StringBuilder的区别](http://blog.csdn.net/kingzone_2008/article/details/9220691),[浅谈 Java 字符串（String, StringBuffer, StringBuilder）](https://segmentfault.com/a/1190000002683782),[JAVA 中的 StringBuilder 和 StringBuffer 适用的场景是什么？](https://www.zhihu.com/question/20101840), [Java中的substring真的会引起内存泄露么？](http://droidyue.com/blog/2014/12/14/substring-memory-issue-in-java/?hmsr=toutiao.io&utm_medium=toutiao.io&utm_source=toutiao.io))
8. 伪泛型([Java 泛型总结（一）：基本用法与类型擦除](https://segmentfault.com/a/1190000005179142))
9. 自动装箱([Java中的自动装箱与拆箱](http://droidyue.com/blog/2015/04/07/autoboxing-and-autounboxing-in-java/index.html),[java自动装箱拆箱总结](https://www.kancloud.cn/digest/rainnnbow-javabase/136298))
10. Try-with-resources([Java 7中的Try-with-resources](http://ifeve.com/java-7%E4%B8%AD%E7%9A%84try-with-resources/))
11. 序列化 反序列化([serialVersionUID作用](http://swiftlet.net/archives/1268), [JAVA序列化](http://blog.csdn.net/u013256816/article/details/50474678), [序列化和反序列化](http://tech.meituan.com/serialization_vs_deserialization.html), [Java序列化](http://luojinping.com/2016/01/03/Java%E5%BA%8F%E5%88%97%E5%8C%96/))
12. interface 和 abstract class 区别
13. 变长参数([Java可变参数](http://www.qiuchengjia.cn/2016/08/14/JAVA/Java%E5%8F%AF%E5%8F%98%E5%8F%82%E6%95%B0/) [Java 中的变长参数](http://blog.jrwang.me/2015/java-varargs/))
14. 枚举详解([Java enum的用法详解](http://www.cnblogs.com/happyPawpaw/archive/2013/04/09/3009553.html), [Java枚举详解](http://www.jianshu.com/p/6f2f5627c27d), [通过枚举enum实现单例设计](http://www.cnblogs.com/liaokailin/p/3196253.html), [枚举单例模式如何防止反射攻击](https://segmentfault.com/a/1190000000699591), [Java 单例模式的两种高效写法](http://www.jianshu.com/p/4e8ca4e2af6c))
15. Null详解([Java中有关Null的9件事](http://www.importnew.com/14229.html)) 
16. Java 8 默认方法([Java 8 默认方法（Default Methods）](http://ebnbin.com/2015/12/20/java-8-default-methods/))

### 集合类(`底层实现原理，实现类的优缺点`)
1. List
  - ArrayList
  - LinkedList
2. Map
  - Hashtable([Java8 - HashTable源码](http://blog.csdn.net/u013124587/article/details/52655042))
  - HashMap([HashMap源码解析](http://www.jianshu.com/p/31a358d14caf),[Java 8系列之重新认识HashMap](http://tech.meituan.com/java-hashmap.html))
    1. HashMap怎么判断两个元素不是同一个(equals 和 hashcode)
    2. 多线程操作后果([疫苗：JAVA HASHMAP的死循环](http://coolshell.cn/articles/9606.html),[HashMap多线程并发问题分析](https://my.oschina.net/xianggao/blog/393990))
    3. rehash([Java集合专题总结（1）：HashMap 和 HashTable 源码学习和面试总结](http://www.cnblogs.com/kubixuesheng/p/6144535.html))
  - ConcurrentHashMap([Java ConcurrentHashMap Best Practices](http://howtodoinjava.com/core-java/collections/best-practices-for-using-concurrenthashmap/))
    1. 锁分段技术([ConcurrentHashMap分析](http://www.infoq.com/cn/articles/ConcurrentHashMap/))
    2. 读是否加锁，为什么([探索 ConcurrentHashMap 高并发性的实现机制](http://www.ibm.com/developerworks/cn/java/java-lo-concurrenthashmap/))
    3. 迭代器是强一致性还是弱一致性([为什么ConcurrentHashMap是弱一致的](http://ifeve.com/concurrenthashmap-weakly-consistent/))
3. Set
  - HashSet
4. *CopyOnWrite容器*([Java中的Copy-On-Write容器](http://ifeve.com/java-copy-on-write/))
5. *Queue*


### 设计模式(`研究常用的十几钟`)
1. 你的项目中用到了哪些设计模式，如何使用
2. 知道常用设计模式的优缺点([设计模式Java版](https://www.gitbook.com/book/quanke/design-pattern-java/details), [十种设计模式示例归纳](http://www.jianshu.com/p/61b67ca754a3))
3. 能画出常用设计模式的UML图([常用设计模式介绍及 UML 图讲解](https://gold.xitu.io/entry/5700b9732e958a005920ec19))
4. 说一下你知道的设计模式，XX设计模式写一下代码，如果需要XX,怎么优化
5. 代理模式 AOP
6. 单例模式([如何正确地写出单例模式](http://wuchong.me/blog/2014/08/28/how-to-correctly-write-singleton-pattern/))

### Concurrency
1. ConcurrentHashMap([ConcurrentHashMap源码分析--Java8](https://yq.aliyun.com/articles/36781), [ConcurrentHashMap源码分析（JDK8版本）](http://blog.csdn.net/u010723709/article/details/48007881), [jdk1.8的HashMap和ConcurrentHashMap](https://my.oschina.net/pingpangkuangmo/blog/817973),[Java并发编程总结4——ConcurrentHashMap在jdk1.8中的改进](http://www.cnblogs.com/everSeeker/p/5601861.html))
  -  并发怎么控制性能
  -  用什么数据结构实现([ConcurrentHashMap源码分析整理](http://www.molotang.com/articles/559.html))
2. 并发编程模式（Java程序性能优化）([多线程设计模式总结](http://www.cloudchou.com/softdesign/post-609.html), [网络爬虫中的那些多线程设计模式](http://www.ahathinking.com/archives/158.html), )
3. Thread和Runnable的区别和联系([Runnable VS Thread 及其资源共享问题](https://my.oschina.net/leejun2005/blog/483999))
4. 多次start一个线程会怎样([Java 线程简介](http://www.ibm.com/developerworks/cn/education/java/j-threads/j-threads.html))
5. 线程有哪些状态([JAVA线程间的状态转换](https://my.oschina.net/mingdongcheng/blog/139263), [Java多线程学习](http://blog.csdn.net/evankaka/article/details/44153709))
6. 线程池
  - 常用的线程池有几种，这几种线程池有什么区别和联系([java自带线程池和队列详细讲解](https://www.oschina.net/question/565065_86540), [Java线程池分析](http://gityuan.com/2016/01/16/thread-pool/))
  - 线程池的实现原理([从使用到原理学习Java线程池](http://www.codeceo.com/article/java-threadpool-learn.html), [几种线程池的实现算法分析
](http://www.infoq.com/cn/articles/thread-pool-algorithm-realization))
  - 判断什么场景该使用什么样的线程池比较合适
7. 多线程同步([40个Java多线程问题总结](http://www.cnblogs.com/xrq730/p/5060921.html))
8. 锁
  - synchronized和ReentrantLock的区别([ReentrantLock和synchronized两种锁定机制](https://yq.aliyun.com/articles/38340), [ReentrantLock源码](http://www.blogjava.net/zhanglongsr/articles/356782.html), [JDK 5.0 中更灵活、更具可伸缩性的锁定机制](https://www.ibm.com/developerworks/cn/java/j-jtp10264/))
  - synchronized锁普通方法和锁静态方法([静态方法加锁，和非静态方法加锁区别](http://greemranqq.iteye.com/blog/1974143))
  - 死锁的原理及排查方法([Java 程序死锁问题原理及解决方案](https://www.ibm.com/developerworks/cn/java/j-lo-deadlock/), )
9. *假如有Thread1、Thread2、Thread3、Thread4四条线程分别统计C、D、E、F四个盘的大小，所有线程都统计完毕交给Thread5线程去做汇总，应当如何实现？(java.util.concurrent下就有现成的类可以使用)*([Java的几个同步辅助类](http://www.cnblogs.com/whthomas/p/java_concurrent_tools.html), [Java并发编程：CountDownLatch、CyclicBarrier和Semaphore](http://www.cnblogs.com/dolphin0520/p/3920397.html))
10. Java的wait(), notify()和notifyAll()使用小结([Java的wait(), notify()和notifyAll()使用小结](http://www.cnblogs.com/techyc/p/3272321.html), [Java进阶（三）多线程开发关键技术](http://www.jasongj.com/java/multi_thread/))
11. 多线程和多进程([多进程与多线程的乱七八糟的事情](http://axhiao.github.io/2015/04/27/process-thread.html))
12. 进程间通信方式([线程间的通信、同步方式与进程间通信方式](http://www.jianshu.com/p/9218692cb209))
13. 自旋锁和互斥锁([自旋锁和互斥锁](http://jacean.github.io/2016/03/23/%E8%87%AA%E6%97%8B%E9%94%81%E5%92%8C%E4%BA%92%E6%96%A5%E9%94%81/))

### JUC
1. LinkedBlockingQueue([Java多线程-工具篇-BlockingQueue](Java多线程-工具篇-BlockingQueue),[BlockingQueue](http://wsmajunfeng.iteye.com/blog/1629354),[Java并发阻塞队列(put和take、offer和poll、drainTo)的使用](http://lawrence-zxc.github.io/2011/03/14/thread-blocking/))
  - poll(WebMagic中QueueScheduler放使用add,取使用带有synchronized的poll,TODO:poll没有阻塞的特性,但为什么要加sync)
  - take
2. AtomicInteger
3. ReentrantLock和Condition(TODO:java线程等待/通知模型)
4. ExecutorService
5. ConcurrentHashMap
6. ScheduledThreadPoolExecutor([Java线程池源码分析二(ScheduledThreadPoolExecutor)](http://yeming.me/2016/05/13/threadPool2/), [Executor框架延时执行任务及周期性执行任务的方法介绍](http://www.jianshu.com/p/e3889d32c8fc))
7. CountDownLatch, CyclicBarrier, Phaser([Java进阶（四）线程间通信剖析](http://www.jasongj.com/java/thread_communication/))

### Socket IO(阻塞/非阻塞 同步/异步的区别)
1. 四种IO模型([Java I/O模型从BIO到NIO和Reactor模式](http://www.jasongj.com/java/nio_reactor/), [Java I/O 模型的演进](http://www.importnew.com/21383.html))
  - 阻塞IO
  - 非阻塞IO
  - 多路复用IO
  - 异步IO ([Java AIO-异步通信](http://blog.csdn.net/a19881029/article/details/52099795))
  - Socket IO如何和这四种模型相关联
2. NIO
  - NIO的原理([NIO使用及原理分析](http://www.jianshu.com/p/6a2af505ca27))
  - NIO属于哪种IO模型(`NIO并不是严格意义上的非阻塞IO而应该属于多路复用IO`)
  - NIO的三大组成([Java NIO系列教程](http://ifeve.com/overview/))
  - *NIO会阻塞在Selector的select方法上*
  - *Netty框架*
3. 五中IO模型和原理([Java NIO：浅析I/O模型](http://www.cnblogs.com/dolphin0520/p/3916526.html), [也谈BIO | NIO | AIO （Java版）](https://my.oschina.net/bluesky0leon/blog/132361))

### JDK源码
1. String的hashCode()方法是怎么实现的
2. List、Map、Set实现类的源代码
3. ReentrantLock、AQS的源代码([AbstractQueuedSynchronizer的介绍和原理分析](http://ifeve.com/introduce-abstractqueuedsynchronizer/))
4. AtomicInteger的实现原理，主要能说清楚CAS机制并且AtomicInteger是如何利用CAS机制实现的
5. 线程池的实现原理
6. Object类中的方法以及每个方法的作用
7. JDK默认消息中间件的api,JMS([kafka：一个分布式消息系统](http://www.cnblogs.com/bbgasj/p/4176915.html))

### DS
1. Arrays and Strings([leetcode习题分类汇总-Array篇](http://zhouchaowei.com/2015/06/02/leetcode-e4-b9-a0-e9-a2-98-e5-88-86-e7-b1-bb-e6-b1-87-e6-80-bb-array-e7-af-87/))
2. Linked Lists
3. Stacks and Queues
4. `树`
  - 二叉查找树
  - 平衡树
  - B+树(数据库的索引，为什么要使用这个数据结构)
  - *AVL树 红黑树 区别*
  - 红黑树([彻底搞懂红黑树](http://www.akathink.com/2016/08/08/%E5%BD%BB%E5%BA%95%E6%90%9E%E6%87%82%E7%BA%A2%E9%BB%91%E6%A0%91/))
5. 图

### Algorithm
1. Bit Manipulation
2. Mathematics and Probability
3. Recursion and Dynamic Programming
4. Sorting and Searching
  - 三匹马,找跑得第二快的(冒泡到快排)
  - jdk Arrays.sort() ([Java 容器 & 泛型：四、Colletions.sort 和 Arrays.sort 的算法](http://www.bysocket.com/?p=219), [快速排序—三路快排 vs 双基准](http://www.importnew.com/8445.html), [JDK的快速排序算法实现DualPivotQuicksort](http://blog.csdn.net/lnho2015/article/details/50669816))
5. 算法分析
  - *Collection.sort方法使用的是哪种排序算法(TimSort 增强型的归并排序)*
6. 经验: 一步一步优化答案, 重要的是过程
7. string contains([为什么java String.contains 没有使用类似KMP字符串匹配算法进行优化？](https://www.zhihu.com/question/27852656))
8. Java实现tail([Java高效实现Tail -f](http://6140717.blog.51cto.com/6130717/1052845))
9. Java重写equals([Java中equals()与hashCode()的原理与设计](http://blog.csdn.net/vernonzheng/article/details/8153669)
10. 冒泡排序([白话经典算法系列之一 冒泡排序的三种实现](http://blog.csdn.net/morewindows/article/details/6657829))

### JVM
1. Java虚拟机的内存布局([java虚拟机的内存布局及对象加载](http://www.acyouzi.com/2016/11/04/jvm-Memory/), [Java内存区域与内存溢出异常](http://howiefh.github.io/2015/04/07/jvm-note-1/))
2. GC算法及几种垃圾收集器([JVM 垃圾回收器工作原理及使用实例介绍](https://www.ibm.com/developerworks/cn/java/j-lo-JVMGarbageCollection/), [垃圾收集器与内存分配策略](http://howiefh.github.io/2015/04/08/jvm-note-2/))
3. 类加载机制，也就是双亲委派模型([深入探讨 Java 类加载器](http://www.ibm.com/developerworks/cn/java/j-lo-classloader/))
4. Java内存模型([深入理解Java内存模型](http://ifeve.com/java-memory-model-1/),[Jvm内存模型](http://gityuan.com/2016/01/09/java-memory/))
5. happens-before规则([happens-before俗解](http://ifeve.com/easy-happens-before/), [Java内存访问重排序的研究](http://tech.meituan.com/java-memory-reordering.html))
6. volatile关键字使用规则([正确使用 Volatile 变量](http://www.ibm.com/developerworks/cn/java/j-jtp06197.html), [Java内存模型与Volatile关键字](http://blog.csdn.net/jiankunking/article/details/53001009))
7. 参数调优([Tomcat中JVM内存溢出及合理配置](https://my.oschina.net/xianggao/blog/83823))
8. 调优工具
9. OOM
10. 四种引用类型([强引用、弱引用、软引用、虚引用](http://brucezz.itscoder.com/four-kind-of-reference-in-java))

### Servlet
1. 规范

数据库：
======
### SQL
1. union和union all的区别([union和union all 的区别](http://www.cnblogs.com/qiantuwuliang/archive/2009/05/31/1492778.html))
2. left join([关于 MySQL LEFT JOIN 你可能需要了解的三点](https://www.oschina.net/question/89964_65912), [从一个MySQL left join优化的例子加深对查询计划的理解](http://luxuryzh.iteye.com/blog/1976004))
3. 性能优化(`SQL基础和SQL优化`)
4. 范式和反范式([解释一下关系数据库的第一第二第三范式](https://www.zhihu.com/question/24696366), [高性能MySQL：范式和反范式](http://blog.wuxu92.com/hp-mysql-paradigm/))
5. 慢查询([MySQL索引原理及慢查询优化](http://tech.meituan.com/mysql-index.html))

### 类型
1. 关系型 MySQL (CA)
2. 非关系型 Redis MongoDB (CP)
3. Dynamo (AP)

### 框架
1. Hibernate
  - 性能分析
  - 一级二级缓存

### 事务
1. 四个性质ACID
2. 【常问】隔离级别([MySQL事务隔离级别](http://xstarcd.github.io/wiki/MySQL/mysql_isolation_level.html))
3. 原理([浅析Mysql InnoDB存储引擎事务原理](http://blog.csdn.net/tangkund3218/article/details/47904021), [MySQL InnoDB单机事务原理（一）](http://www.ywnds.com/?p=4961))

### 索引(`几种索引及其区别`)
1. 实现方式([MySQL索引背后的数据结构及算法原理](http://blog.codinglabs.org/articles/theory-of-mysql-index.html))
2. 索引优化问题(a, b, c列的index怎么建,联合索引)([一个mysql多列索引的问题](https://my.oschina.net/costaxu/blog/99170),[MySQL索引原理及慢查询优化](http://tech.meituan.com/mysql-index.html),[mysql索引和优化](https://github.com/zhuwei05/blog/blob/master/mysql/mysql%E7%B4%A2%E5%BC%95%E5%92%8C%E4%BC%98%E5%8C%96.md))
3. 查看索引([如何查看数据库或表的索引？](https://www.coder-note.com/questions/5213339/how-to-see-indexes-for-a-database-or-table))

### 读写分离

### 缓存

### 快照

### 多表查询单表查询

### 锁([MySQL数据库锁](https://binaryys.github.io/2017/02/08/%E7%AC%94%E8%AE%B0/MySQL/MySQL%E6%95%B0%E6%8D%AE%E5%BA%93%E9%94%81/), [MySQL数据库优化（三）——MySQL悲观锁&&乐观锁（并发控制）](http://blog.csdn.net/daybreak1209/article/details/51606939))
1. `读锁`
2. `写锁`
3. 乐观锁 ([mysql乐观锁总结和实践](http://chenzhou123520.iteye.com/blog/1863407))
4. 原理([Mysql数据库事务的隔离级别和锁的实现原理分析](http://blog.csdn.net/tangkund3218/article/details/47704527))
5. MVCC实现原理([InnoDB多版本(MVCC)实现简要分析](http://hedengcheng.com/?p=148))
6. 加锁处理分析([MySQL 加锁处理分析](http://hedengcheng.com/?p=771) [InnoDB 事务/锁/多版本 实现分析](http://hedengcheng.com/?p=286))
7. 死锁的处理([MySQL中的锁（表锁、行锁）](http://www.cnblogs.com/chenqionghe/p/4845693.html) [mysql死锁(deadlock)分析及解决](http://www.xxdafa.com/article?id=56914506b8063f1a058b456c))
8. 锁的类型([Mysql InnoDB锁和死锁](http://xiaobaoqiu.github.io/blog/2015/06/03/mysql-innodbsi-suo/))

### CAS

### Redis
1. 只有单线程,高效

### MySQL
1. 引擎
  - InnoDB和MyISAM的区别([MySQL存储引擎介绍](http://www.jellythink.com/archives/640),[MySQL存储引擎InnoDB与Myisam的六大区别](https://my.oschina.net/junn/blog/183341),[MySQL存储引擎MyISAM与InnoDB的主要区别对比](MySQL存储引擎MyISAM与InnoDB的主要区别对比),[MySQL存储引擎中的MyISAM和InnoDB](https://www.zybuluo.com/phper/note/78781),[MySQL存储引擎——MyISAM vs InnoDB](http://zheming.wang/blog/2015/02/14/2BB7BB2A-4AE3-41E5-B695-7BCFFD6E23C7/))
2. 水平切分和垂直切分(分布式)

### 场景
1. 两台服务器之间数据库通信问题，如果有网络超时，故障，如何处理（以2个银行之间转账为例），如何保持实时性(原子性和一致性, CAP,BASE)([分布式系统的事务处理](http://coolshell.cn/articles/10910.html),[分布式系统事务一致性解决方案](http://www.infoq.com/cn/articles/solution-of-distributed-system-transaction-consistency),[保证分布式系统数据一致性的6种方案](http://weibo.com/ttarticle/p/show?id=2309403965965003062676))

WEB：
======
### Session
1. 谈谈分布式Session的几种实现方式(常用的四种)
2. 讲一下Session和Cookie的区别和联系以及Session的实现原理([]谈谈分布式Session的几种实现方式,Session和Cookie的区别和联系以及Session的实现原理](http://aoyouzi.iteye.com/blog/2310193))

### Servlet
1. web.xml里面的内容(使用 *实现原理*)
  - Filter
  - Servlet
  - Listener

### HTTP
1. get/post的区别
2. forward/重定向的区别
3. HTTPS的实现原理
4. 协议
5. 输入网址enter发生了什么([当···时发生了什么？](https://github.com/skyline75489/what-happens-when-zh_CN))

### 分布式([谈谈业务中使用分布式的场景](https://segmentfault.com/q/1010000006095431))
1. CAP BASE([CAP原则(CAP定理)、BASE理论](http://www.cnblogs.com/duanxz/p/5229352.html),[如何正确理解CAP理论？](http://www.jdon.com/bigdata/how-to-understand-cap.html),[CAP理论十二年回顾："规则"变了](http://www.infoq.com/cn/articles/cap-twelve-years-later-how-the-rules-have-changed))

### 框架
1. Spring([25个经典的Spring面试问答](http://www.codeceo.com/article/spring-top-25-interview.html))
  - ioc/aop 使用/实现([java反射简单实现注入](http://www.cnblogs.com/shibalang/p/4781989.html), [深入解析Java反射（2） - invoke方法](http://www.sczyh30.com/posts/Java/java-reflection-2/), [Java深度历险（七）——Java反射与动态代理](http://www.infoq.com/cn/articles/cf-java-reflection-dynamic-proxy), [Java反射之 getMethod() 与invoke的使用](http://www.voidcn.com/blog/lycorisradiata_1/article/p-4407090.html), [ java动态代理（JDK和cglib）](http://blog.csdn.net/mdcmy/article/details/8543971))
  - 支持哪些事务,怎么支持的(代理模式)
  - 设计模式
  - Spring bean的生命周期([Spring Bean生命周期](http://www.jianshu.com/p/3944792a5fff))
  - Spring bean的作用域([Bean 的作用域](http://wiki.jikexueyuan.com/project/spring/bean-scopes.html))
  - Spring AOP的实现原理(AOP和IOC的概念和实现细节以及举例你在项目中的的使用场景)([Spring AOP 实现原理与 CGLIB 应用](https://www.ibm.com/developerworks/cn/java/j-lo-springaopcglib/),[Spring Ioc实现机制——简析](http://blog.csdn.net/anger_coder/article/details/12706277))
  - *画一下Spring的Bean工厂实现的UML图*
  - 循环引用问题([令人混淆的Spring环境的循环依赖](http://cloudate.net/?p=1583))
  - 注解([spring注解原理剖析与实现](http://miclee.cn/2015/12/22/spring-annotition/),[详解 Spring 3.0 基于 Annotation 的依赖注入实现](http://www.ibm.com/developerworks/cn/opensource/os-cn-spring-iocannt/))

### 容器
1. Tomcat
  - 源码
  - 责任链模式
  - 一个简单servlet容器实现[代码博主抄的《how tomcat works》](http://www.cnblogs.com/chenpi/p/5603072.html)
  - 涉及到的设计模式([Tomcat 系统架构与设计模式，第 2 部分: 设计模式分析](https://www.ibm.com/developerworks/cn/java/j-lo-tomcat2/))
  - pipline逐级调用valve时发生错误如何处理([tomcat架构分析(valve机制)](http://gearever.iteye.com/blog/1536022))
  - BIO和NIO([tomcat bio nio apr 模式性能测试与个人看法](https://yq.aliyun.com/articles/14768))
  - 用到的线程池细节([线程池的原理](http://www.10tiao.com/html/142/201603/403055165/1.html),[tomcat线程池策略](https://segmentfault.com/a/1190000008052008))



### OAuth2.0

### 架构
1. 负载均衡
2. 一致性hash([MemCache超详细解读](http://www.cnblogs.com/xrq730/p/4948707.html), [一致性Hash算法，Java代码实现的深入研究](http://www.cnblogs.com/xrq730/p/5186728.html))
3. *SOA和RPC*(面向服务体系，大型分布式架构)
3. 消息队列原理([消息队列设计精要](http://tech.meituan.com/mq-design.html))
4. Dubbo
5. 大型网站系统与Java中间件实践([大型网站系统与Java中间件实践](http://wanglizhi.github.io/2016/07/27/JavaWeb-And-MiddleWare/))
6. 高并发 10w并发量([秒杀系统架构分析与实战](https://my.oschina.net/xianggao/blog/524943))
7. 安全 
  - https([HTTPS背后的加密算法](http://isaachan.github.io/blog/2014/07/20/cipher-behind-https/), [大型网站的 HTTPS 实践（一）—— HTTPS 协议和原理](http://op.baidu.com/2015/04/https-s01a01/),
    [HTTPS 协议详解](https://jin-yang.github.io/post/https-introduce.html), [详解https是如何确保安全的？](http://www.wxtlife.com/2016/03/27/%E8%AF%A6%E8%A7%A3https%E6%98%AF%E5%A6%82%E4%BD%95%E7%A1%AE%E4%BF%9D%E5%AE%89%E5%85%A8%E7%9A%84%EF%BC%9F/))
  - 加密算法([Notes on Cryptography Ciphers](http://rakhesh.com/infrastructure/notes-on-cryptography-ciphers-rsa-dsa-aes-rc4-ecc-ecdsa-sha-and-so-on/))
  - TLS([TLS 握手优化详解](https://imququ.com/post/optimize-tls-handshake.html), [SSL/TLS原理详解](http://seanlook.com/2015/01/07/tls-ssl/))
8. 阿里中间件([阿里中间件团队介绍](http://jm.taobao.org/about/))
9. 序列化([Java序列化](http://luojinping.com/2016/01/03/Java%E5%BA%8F%E5%88%97%E5%8C%96/))  

### 网络服务抖动

### 场景
1. 单点登陆(Single sign in)
2. 秒杀系统

源码:
======
### OKHttp3
### Spring-core


### Tomcat


### Hibernate
### MyBatis
1. MyBatis中$和#的区别([mybatis深入理解(一)之 # 与 $ 区别以及 sql 预编译](https://segmentfault.com/a/1190000004617028))

### 集合类
### Concurrent包


Storm:
======
1. 基本概念([实时计算系统Storm学习笔记](https://geosmart.github.io/2016/09/13/%E5%AE%9E%E6%97%B6%E8%AE%A1%E7%AE%97%E7%B3%BB%E7%BB%9FStorm%E5%AD%A6%E4%B9%A0%E7%AC%94%E8%AE%B0/))
2. 通信([【源码分析】storm拓扑运行全流程源码分析](http://blog.csdn.net/lujinhong2/article/details/49943591))
3. 序列化使用kryo([序列化](https://github.com/weyo/Storm-Documents/blob/master/Manual/zh/Serialization.md))
4. thrift([Thrift序列化/反序列化方法对比](http://du00cs.github.io/2014/11/thrift-serialization-des/))
5. disrupter([【系统架构】聊聊Disruptor](http://community.bittiger.io/topic/183/%E7%B3%BB%E7%BB%9F%E6%9E%B6%E6%9E%84-%E8%81%8A%E8%81%8Adisruptor))

计算机基础
======
### 计算机网络
1. tcp/ip tcp 和 udp的区别 tcp消息重发 time wait([Linux下套接字详解（一）----TCP/UDP的区别与联系](http://blog.csdn.net/gatieme/article/details/46240775))