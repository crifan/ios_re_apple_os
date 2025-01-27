# Mach

* Mach微内核
  * 概述
    * Mach是一个Microkernel微内核，主要包含虚拟内存的管理、任务管理的进程和线程的抽象、任务调度、进程间通信等内容，优点是服务进程容易扩展
    * iOS系列系统内核就用到Mach微内核。由其优点而扩展出，Mach-O格式支持多种架构，以及使得macOS能顺利的从PowerPC过渡到Intel再到M1。
  * 详解
    * [Mach内核 · iOS逆向：Mach消息和XPC进程通信](https://book.crifan.org/books/ios_re_mach_xpc/website/mach/core/)
* Mach消息
  * 概述
    * Mach消息的基础概念就是两个端点Port中交换的message。
    * 一个message就是msgh_size大小的blob, 带着一些flags，从一个端口发送到另一个端口
    * 核心函数有：`mach_msg()`、`mach_msg_send()`、`mach_msg_receive()`、`mach_msg_trap()`、`mach_msg_overwrite_trap()`
  * 架构
    * ![mach_msg_arch](../../../assets/img/mach_msg_arch.webp)
  * 详解
    * [Mach消息 · iOS逆向：Mach消息和XPC进程通信](https://book.crifan.org/books/ios_re_mach_xpc/website/mach/message/)
