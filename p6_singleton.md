# 单例模式（singlenton）模式
## 简单的单例模式
* 问题原因
  - 将对象赋值给全局变量时，若开销大，而又一直未使用到
* 保证资源的唯一性

## 线程安全的单例
* 多线程的风险在于一个未返回但已生成，而另一个线程刚好生成
* JAVA的线程安全可以synchroniced，但一般会想tornado IOloop实现一样，用double check，python的用_indtance_lock，而java还要用volatile来修饰变量保证变量在线程使用顺序正确

## 没了
* 好水