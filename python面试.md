## __new__ 和 __init__ 的区别
* __new__ 是一个静态方法，__init__ 是一个实例方法
* __new__ 方法会返回一个创建的实例，而 __init__ 什么都不返回
* 只有 __new__ 返回一个 cls 实例时，后面的 __init__ 才会被调用
* 当创建一个新实例时调用 __new__，初始化实例时用 __init__

## 列表和元组的区别
* 元组是不可变的，而列表是可变的
* 元组表示的是结构，而列表表示的是顺序
* 列表不能当作字典的 key，而元组可以

## 标准数据类型
Python3 中有六个标准的数据类型：

* Number（数字）
* String（字符串）
* List（列表）
* Tuple（元组）
* Sets（集合）
* Dictionary（字典）
