# Basic/Virtual #
此项目主要用于探究virtual关键字在多态中的用法。

## 结论 ##
1. virtual关键字可以确保目标在被用"->"访问时调用正确的子类方法。
2. 直接用"."访问并不能调用子类的方法，只有用"->"访问才能调用子类方法。