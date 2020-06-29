## Java基础

1. 强引用、软引用、弱引用、虚引用
2. 聊聊类加载器
3. 常用的数据结构？
4. 栈跟队列的区别？
5. hashmap的原理？hashcode和equals的关系？hashcode相等，equals是否相等？
6. hashmap为什么是线程不安全的？
7. hashmap的尾部遍历？
8. 什么情况的会用到锁？介绍一下java中的锁？
9. synchronized的锁的底层实现？
10. 锁升级理论？什么时候会转化为重量级锁？
11. hashmap的基本原理
12. 处理hash冲突的方式
13. jdk1.8使用treemap来处理哈希冲突，你是怎么理解的？
14. arraylist和linkedlist的区别
15. 增加删除线性表的第一个元素，使用哪种数据结构
16. java面向对象特性？继承、封装、多态？
17. 什么是反射？使用场景？
18. hashmap如何遍历？
19. hashcode和equals方法区别和作用？
20. new一个对象，java中有什么操作？
21. 类加载的过程？
22. 泛型？泛型的两个关键字介绍一下？（extends、*super*）
23. 抽象类和接口的区别？分别用于在什么场景？
24. String 、Stringbuffer、Stringbuilder
25. 重载和重写的区别？
26. arraylist和linkedlist的区别？
27. 为什么hashmap不是线程安全的？
28. ArrayList 和 LinkedList 的区别 
29. HashMap & ConcurrentHashMap 的比较 : 线程安全问题等等。深入一些 ： HashMap 为什么线程不安全？ 能否举例 = { 并发resize()触发闭环结构 ，覆盖put操作 }
30. 【高频】 HashMap 的 相关问题  *// HashMap系列需要通过关键源码理解，比较重要为什么 HashMap的size 为 2的幂次方 ？  HashMap resize()过程能否介绍 ？ HashMap效率受什么影响 (负载因子、hash数组size)？ HashMap中扰动函数的作用 ？* 
31. Hashtable 和 HashMap的区别 ： { 底层数据结构 (JDK1.8后不同)、父类不同 、扩容方法不同 、 线程上锁范围不同（重点） } 
32. equals 和 == 区别；为啥重写equals要重写hashCode()；hash值相等，而两个对象不一定equals 
33. 【高频】 String StringBuffer StringBuilder 区别 和各自使用场景。深入一些 ： String 是如何实现它不可变的？ 为什么要设置String为不可变对象 ?  (字节一面这个问题给我问懵了) 
34. 接口和抽象类区别 
35. 重写和重载的区别 
36. 深拷贝和浅拷贝区别 
37. Java三大特性 
38. Object的方法 ： { finalize 、 clone、 getClass 、 equals 、 hashCode } 
39. 【高频】 设计模式  ： { 单例模式 、 工厂模式 、 装饰者模式 、 代理模式 、 策略模式 等等} （此处我的掌握也不是很好）。深入一些 ： 单例模式为什么采用双检测机制 ？ 单例为什么用Volatile修饰？ 装饰模式和代理模式的区别