# OCMethodTrace - Trace Any Objective-C Method Calls

跟踪打印Objective-C实例(类)中任何方法

## 功能：
1. 支持任意OC实例(类)方法的跟踪打印
2. 避免跟踪基类super调用导致的递归死循环
3. 避免输出打印时调用-[description]导致的递归死循环

## TODO：
1. 完善struct类型参数的自动解析
2. 跳板实现改用更简单的Objc原生方法"IMP imp_implementationWithBlock(id block) + 内联汇编"的模式
3. 增加示例程序和单元测试

## 感谢：
https://github.com/qhd/ANYMethodLog
https://github.com/SatanWoo/MainThreadChecker.git

欢迎提Issues和Pull requests，如有问题，可以联系 Michael Chen (omxcodec@gmail.com)