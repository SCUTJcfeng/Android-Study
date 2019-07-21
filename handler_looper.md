## Android 线程间通讯机制

### Android 线程

[参考资料](https://www.cnblogs.com/leon19870907/archive/2012/02/25/2367549.html)

1. 主线程(UI 线程)

   - 主线程中进行 UI 元素操作

2. 其它线程
   - CPU 或 IO 操作

#### 基本概念

1. Looper
   - 概念: 每个线程都可以产生一个 Looper, 用来管理线程的 Message, Looper 对象会建立一个 MessageQueue 数据结构来存放 message
2. Handler
