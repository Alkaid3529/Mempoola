# Memory Pool A
本项目实现了一个基于 C++ 11 `高性能内存池`的可`动态内存分配`的链表队列，队列支持`多线程`下 30 Hz 到 50 Hz 的数据输入和 10 Hz 的数据输出，项目内含自实现的 内存池 分配器，可以在一定程度上`提升内存分配性能`，减少内存碎片的产生和内存分配失败引起的程序崩溃。

# 数据缓存池
数据池可以`存储多种格式数据`，并保证数据的`先入先出`存取，通过内存池提升数据存取效率。
