
<p align='center'>
<img src='https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1526457040696&di=0c64726aa0fbf502bbb2af5142b8a1c2&imgtype=0&src=http%3A%2F%2Fimg2.jiemian.com%2F101%2Foriginal%2F20170408%2F149163479116565200.jpg'>
</p>

<p align='center'>
<img src="https://img.shields.io/badge/platform-iOS-ff69b4.svg">
<img src="https://img.shields.io/badge/language-Objective--C-orange.svg">
</p>

## iOS-InterviewQuestion

> 双非本科，目标大厂，有网易实习经历，但秋招全部失败，重整旗鼓，备战春招。
> 分析失败原因：1.计算机基础不扎实，所以会另开一个仓库总结计算机基础，本仓库主要总结常见的 `iOS` 面试题。2. 技术栈不明确，后面会学习下相机、直播和`webview`使用。

### 书籍

1. 《Effective Objective-C 2.0》
2. 《禅与 Objective-C 编程艺术》
3. 《Objective-C 高级编程》(待总结)
4. 《Objective-C 编程之道》
5. 《iOS UI开发捷径》

## iOS 内存管理

1. `ARC`和`MRC` - [总结](内存管理/0.md)
    1. 对`ARC`和`MRC`的理解，了解`GC`吗（垃圾回收机制）。
    2. `iOS`内存管理思考方式。
    3. `alloc`、`retain`、`release`、`delloc`作用和实现。
    4. `autorelease`作用和实现。
    5. 使用自动引用计（`ARC`）数应该遵循的原则。
    6. 所有权修饰符`__stong`、`__weak`、`__autoreleasing`的作用和实现。
    7. 引用计数的实现。
    8. `ARC`在编译时做了哪些工作。
    9. `ARC`在运行期做了哪些工作。
    10. 在`MRC`下如何重写属性的`Setter`和`Getter`。
2. 关键字。
    1. 说一下对 `retain`,`copy`,`assign`,`weak`,`_unsafe_unretain` 关键字的理解。
    2. `weak`、`assign`、`unsafe_unretain`的区别。
    3. `strong`、`copy`的区别。
    4. `__weak`属性修饰的变量，如何实现在变量没有强引用后自动置为`nil`。
    5. `_weak`和`@autoreleasing`的关系。
    6. 深拷贝和浅拷贝。
    7. 悬挂指针和野指针。
    8. `BAD_ACCESS`在什么情况下出现
    9. 内存管理的默认关键字。
3. 内存泄漏
    1. 出现内存泄漏的场景。
    2. 如何检查内存泄漏、如何解决。
4. 内存分区。 






