# Developer Guide - 开发者指南


## 设计开发原则

1. 功能**足够通用**， 其它第三方库中没有更好的选择，或者有选择但循环依赖太多；
2. **尽量**不依赖除JDK类库之外的第三方类库， 当前项目的pom中依赖越少越好， 如果实在避免不了，尽量通过拷贝代码并变更命名空间的形式进行代码级别依赖，唯一的目的就是尽量减少当前项目为jar hell问题贡献"更多能量"；
3. 尽量提供尽可能详尽的代码注释，并在README.md相应章节中提供使用说明的简单实例， quick start文档比看代码更容易给人直观的使用印象；


## 如何贡献？

本项目管理采用git的Fork模式进行， 如果要提交新的goodie， 首先fork当前repository， 然后在自己的repository进行设计开发并测试通过后，提交merge request， 管理员将根据情况评估是否合适merge到主干分支。

如果只是提交issue， 可以在当前项目的issue管理页面直接提交， 如果提交patch，最好将需要merge的patch通过merge request一并附上。



