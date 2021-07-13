# 1. java基础知识

## 1. 基础

1. HashMap 
    HashMap 的底层结构，实现方式（源码）
    插入的原理，put操作源码
    loadfactor的作用
    hashmap扩容，为什么每次扩容是翻倍，增加1.5倍不行吗？增加4倍不行吗？
    java中解决Hash冲突的四种方式
    和treemap比较，put，get，扩容，并发问题，rehash？
    concurrentHashMap是什么？中的分段锁是什么？
    HashTable和HashMap有什么区别。应用场景有什么不同？


2. string、stringbulider、stringbuffer的区别

3. ArrayList、LinkedList、Vector区别

4. Class.forName和classloader的区别

5. Java设计模式，你知道哪些设计模式

6. ==和equals的区别

7. 什么是多态

8. hashcode（）相同，equals一定相同吗，怎么实现线程安全的，CAS是什么。我自己发散了很多东西，没等他问

10. Java中抽象类和接口的区别，都有抽象类了为什么还要有接口



## 2. jvm虚拟机

1. java内存区域划分？都是干什么的？程序计数器保存什么
2. 垃圾回收算法 ？
    垃圾回收算法的CMS和G1的区别，或者各自的特性
3. JDK代理和cglib代理的区别？ 代理更底层一点是怎么实现的？
动态代理和字节码的关系（面试官说字节增强）

4. JVM的具体细节（内存结构、GC算法、GC工具、引用方式等）
5. 垃圾回收算法，追问两个互相引用的对象能否回收

6. STW（stop the world，垃圾回收线程工作的话会暂停用户线程的执行）？ 工作线程暂停的话是立马暂停吗
安全点
7. Java中的内存泄漏

# 3. 多线程

1. ThreadLocal底层结构
2. 三个线程按指定顺序执行的实现方法
3. 解释一下volatile
4. 线程实现的几种方式，
5. 线程池
6. 线程和进程的区别
7. 线程各种锁
8. 线程死锁原因，解决方法
9. 一个类中两个方法都用sybchronized修饰，线程A调用方法1，线程2调用方法2；线程1先获取时间片那么线程2能够获取到时间片吗