# 不可变性

## 不可变对象

- 可以引用传递，可以缓存
- 线程安全

## 如何实现不可变

- final关键字
  - 类申明：类不可以被继承
  - 函数申明：函数不可以在派生类中重写
  - 变量申明：变量不可以指向其他对象，如果是引用类型，内容还是可以变的
- 从接口定义，类的实现上保证不可变性
- Collections.unmodifiableList()

