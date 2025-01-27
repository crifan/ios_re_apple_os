# iOS逆向：Apple操作系统

* 最新版本：`v1.1.0`
* 更新时间：`20250127`

## 简介

整理iOS逆向期间常会涉及到的Apple操作系统。先是概览；然后是Unix Like系列的系统；然后是Darwin内核，以及相关常见系统macOS和iOS；接着介绍Darwin的内核XNU，包括XNU的架构和组成，源码，以及具体包含内容；包括Mach、BSD、IOKit。Mach中核心内容是Mach消息传递；最后总结iOS、macOS、Darwin、XNU、Mach、BSD、IOKit等之间的关系；

## 源码+浏览+下载

本书的各种源码、在线浏览地址、多种格式文件下载如下：

### HonKit源码

* [crifan/ios_re_apple_os: iOS逆向：Apple操作系统](https://github.com/crifan/ios_re_apple_os)

#### 如何使用此HonKit源码去生成发布为电子书

详见：[crifan/honkit_template: demo how to use crifan honkit template and demo](https://github.com/crifan/honkit_template)

### 在线浏览

* [iOS逆向：Apple操作系统 book.crifan.org](https://book.crifan.org/books/ios_re_apple_os/website/)
* [iOS逆向：Apple操作系统 crifan.github.io](https://crifan.github.io/ios_re_apple_os/website/)

### 离线下载阅读

* [iOS逆向：Apple操作系统 PDF](https://book.crifan.org/books/ios_re_apple_os/pdf/ios_re_apple_os.pdf)
* [iOS逆向：Apple操作系统 ePub](https://book.crifan.org/books/ios_re_apple_os/epub/ios_re_apple_os.epub)
* [iOS逆向：Apple操作系统 Mobi](https://book.crifan.org/books/ios_re_apple_os/mobi/ios_re_apple_os.mobi)

## 版权和用途说明

此电子书教程的全部内容，如无特别说明，均为本人原创。其中部分内容参考自网络，均已备注了出处。如发现有侵权，请通过邮箱联系我 `admin 艾特 crifan.com`，我会尽快删除。谢谢合作。

各种技术类教程，仅作为学习和研究使用。请勿用于任何非法用途。如有非法用途，均与本人无关。

## 鸣谢

感谢我的老婆**陈雪**的包容理解和悉心照料，才使得我`crifan`有更多精力去专注技术专研和整理归纳出这些电子书和技术教程，特此鸣谢。

## 其他

### 作者的其他电子书

本人`crifan`还写了其他`150+`本电子书教程，感兴趣可移步至：

[crifan/crifan_ebook_readme: Crifan的电子书的使用说明](https://github.com/crifan/crifan_ebook_readme)

### 关于作者

关于作者更多介绍，详见：

[关于CrifanLi李茂 – 在路上](https://www.crifan.org/about/)
