# Hi~KyoDream

### 🔭 爱好

+ 代码研究
+ 研究调试技术

### 现期维护的项目
+ [router-router(Java web动态调试)](https://github.com/kyo-w/router-router)
+ [net-router(C#动态调试)](https://github.com/kyo-w/net-route)

### 项目阶段性
#### [router-router(Java web动态调试)](https://github.com/kyo-w/router-router)
+ 考虑引入本地库第三方库的引入，这样的话，是不是可以引入反编译源代码的功能
+ 引入IDEA的表达式解析功能，但是似乎需要引入断点设置线程的问题

#### [net-router(C#动态调试)](https://github.com/kyo-w/net-route)
+ 项目预计进行迁移，动态调试分析C#的效果十分糟糕，也许静态分析.net的项目会更好。原因如下：
1. C#有大量的优化，一个没有被访问的Controller是不会被扫描到的。这就导致需要进行大量的访问，然后重新进行大量内存遍历，十分糟糕。
2. 由于.net的web技术其实相对Java而已，框架比较稳定，基本都是官方的MVC架构，不会出现太大的分析差异，我觉得静态效果会很好。