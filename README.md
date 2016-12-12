JAVA：
======
### 基本语法
1. static
  - 修饰变量 方法
  - 静态块
  - 静态内部类
  - 静态导包
2. final
3. transient
4. foreach循环原理
5. volatile底层实现

### 集合类(`底层实现原理，实现类的优缺点`)
1. List
  - ArrayList
  - LinkedList
2. Map
  - Hashtable
  - HashMap
  - ConcurrentHashMap
    1. 锁分段技术
    2. 读是否加锁，为什么
    3. 迭代器是强一致性还是弱一致性
3. Set
  - HashSet
4. *CopyOnWrite容器*
5. *Queue*


### 设计模式(`研究常用的十几钟`)
1. 你的项目中用到了哪些设计模式，如何使用
2. 知道常用设计模式的优缺点
3. 能画出常用设计模式的UML图

### Concurrency
1. ConcurrentHashMap
  -  并发怎么控制性能
  -  用什么数据结构实现
2. 并发编程模式（Java程序性能优化）
3. Thread和Runnable的区别和联系
4. 多次start一个线程会怎样
5. 线程有哪些状态
6. 线程池
  - 常用的线程池有几种，这几种线程池有什么区别和联系
  - 线程池的实现原理
  - 判断什么场景该使用什么样的线程池比较合适
7. 多线程同步([40个Java多线程问题总结]:(http://www.cnblogs.com/xrq730/p/5060921.html))
8. 锁
  - synchronized和ReentrantLock的区别
  - synchronized锁普通方法和锁静态方法
  - 死锁的原理及排查方法
9. *假如有Thread1、Thread2、Thread3、Thread4四条线程分别统计C、D、E、F四个盘的大小，所有线程都统计完毕交给Thread5线程去做汇总，应当如何实现？(java.util.concurrent下就有现成的类可以使用)*

### Socekt IO(阻塞/非阻塞 同步/异步的区别)
1. 四种IO模型
  - 阻塞IO
  - 非阻塞IO
  - 多路复用IO
  - 异步IO
  - Socket IO如何和这四种模型相关联
2. NIO
  - NIO的原理
  - NIO属于哪种IO模型(`NIO并不是严格意义上的非阻塞IO而应该属于多路复用IO`)
  - NIO的三大组成
  - *NIO会阻塞在Selector的select方法上*
  - *Netty框架*

### JDK源码
1. String的hashCode()方法是怎么实现的
2. List、Map、Set实现类的源代码
3. ReentrantLock、AQS的源代码
4. AtomicInteger的实现原理，主要能说清楚CAS机制并且AtomicInteger是如何利用CAS机制实现的
5. 线程池的实现原理
6. Object类中的方法以及每个方法的作用

### DS
1. 数组链表
2. 栈和队列
3. `树`
  - 二叉查找树
  - 平衡树
  - B+树(数据库的索引，为什么要使用这个数据结构)
  - *AVL树 红黑树 区别*
4. 算法分析
  1. *Collection.sort方法使用的是哪种排序算法(TimSort 增强型的归并排序)*

### JVM
1. Java虚拟机的内存布局
2. GC算法及几种垃圾收集器
3. 类加载机制，也就是双亲委派模型
4. Java内存模型
5. happens-before规则
6. volatile关键字使用规则
7. 参数调优
8. 调优工具
9. OOM

### Servlet
1. 规范

数据库：
======
### SQL
1. union和union all的区别
2. left join
3. 性能优化(`SQL基础和SQL优化`)

### 类型
1. 关系型 MySQL
2. 非关系型 Redis MongoDB

### 框架
#### hibernate
1. 性能分析
2. 一级二级缓存

### 事务
1. 四个性质ACID
2. 隔离级别

### 索引(`几种索引及其区别`)
1. 实现方式

### 读写分离

### 缓存

### 快照

### 多表查询单表查询

### 锁
1. `读锁`
2. `写锁`

### CAS

WEB：
======
### Session
1. 谈谈分布式Session的几种实现方式(常用的四种)
2. 讲一下Session和Cookie的区别和联系以及Session的实现原理

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

### 分布式
1. CAP原则

### 框架
1. Spring
  - ioc/aop 使用/实现

### 容器
1. Tomcat
  - 源码
  - 责任链模式



### OAuth2.0

### 架构
1. 负载均衡
2. 一致性hash([MemCache超详细解读]:(http://www.cnblogs.com/xrq730/p/4948707.html), [一致性Hash算法，Java代码实现的深入研究]:(http://www.cnblogs.com/xrq730/p/5186728.html))
3. *SOA和RPC*(面向服务体系，大型分布式架构)
3. 消息队列
4. Dubbo

### 网络服务抖动

### 场景
1. 多点登录
2. 秒杀系统

源码:
======
### OKHttp3
### Spring-core
1. 想要在Spring初始化bean的时候做一些事情该怎么做
2. 想要在bean销毁的时候做一些事情该怎么做
3. Spring AOP的实现原理
4. *画一下Spring的Bean工厂实现的UML图*

### Tomcat
### Hibernate
### MyBatis
1. MyBatis中$和#的区别

### 集合类
### Concurrent包
