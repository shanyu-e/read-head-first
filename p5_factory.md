# 工厂（factory）模式

## 静态工厂
* 工厂模式就是为了封装创建实例，而静态工厂劣势在于依赖构造器(应该理解为，任然是对具体类的依赖)


## 对（抽象）工厂方法模式
* 针对new的东西会有改变
* 对于case一样的生产无法解决仍有大量可见预期修改存在
* 而工厂就是为了反向依赖这些修改的
* 依赖倒置是最有效的解耦方式之一，而工厂模式是这个最佳实践之一
* 依赖抽象的结果就是，类的实例化推迟到合适的时候了

## 结束
* 下班回家，还是很迷糊，写下来还是有点用