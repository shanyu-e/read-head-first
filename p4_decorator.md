# 装饰者（decorator）模式
## 山寨星巴克中的装饰器
* 过多继承会造成混乱
* 开发扩展，关闭修改的原则（这就是为什么new了又new）
* 优势在于可以在运行时动态地、不限量地增加特性
## JAVA io中的使用
* 一个例子读懂`new LowerCaseInputStream(new BufferedInputStream(new FileInputStream("test.txt")));`
* 记得回看下bufferedinputstream，虽然现在也不太写java了
## 尾声
* 也算深入学习过python的装饰器的，所以这个模式比较好懂，其实看着java实现的有点发笑，这叫装饰吗，这明明叫包裹，哈哈哈。。。期待有机会读读java注解的含义。。。今天好懒，然后看到同学正式开始运营公司了，心中有点嗡鸣感。。。