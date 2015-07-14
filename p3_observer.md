# 观察者模式（observer）模式
## 自定义的观察者模式
* 应该是针对接口编程
* 主题者接口
  - 接口只有update()一 个方法,当主题状态改变时它被 调用。
* 观察者接口
  - 接口应该定义registerObserver()、removeObserver()、notifyObservers()等的方法
  - 观察者自己去注册哪一个主题
  - notifyObservers时就调用
* 最能体现松耦合的设计模式，估计也是为什么jdk中使用最多模式的原因

## JDK中自带的观察者模式
* 多种的实现方法中不那么和理论吻合的方式
* 使用observer接口和observable类，而不是都用接口
* mvc可以看做是观察者模式的最佳实践
* 具体讨论jdk中实现
  - 消息传递可以是推和拉，而不是以前那样只能一次全推过来
  - 继承Observable的不再使用register()、remove()、notifyObservers()而用addObserver()、deleteObserver()、notifyObservers()代替

## 就这么多吧
* `最近又要忙成狗，通过meteor学js、拿django开始接外包，学习docker、还不想放弃机器学习的东西，加油，看到cmd-markdown，又发现svg这个东西是终极解决方案，又有前端东西要学了。`