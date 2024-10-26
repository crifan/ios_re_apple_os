# XNU版本

## Mac

* Mac
  * uname -a
    ```bash
    Darwin crifandeMacBook-Pro.local 20.6.0 Darwin Kernel Version 20.6.0: Mon Aug 30 06:12:21 PDT 2021; root:xnu-7195.141.6~3/RELEASE_X86_64 x86_64
    ```
  * sysctl
    * kern.version
      ```bash
      Darwin Kernel Version 20.6.0: Mon Aug 30 06:12:21 PDT 2021; root:xnu-7195.141.6~3/RELEASE_X86_64
      ```

## iPhone6

* Mac
  * uname -a
    ```bash
    Darwin Crifan-iPhone6 18.7.0 Darwin Kernel Version 18.7.0: Mon Aug 19 22:24:08 PDT 2019; root:xnu-4903.272.1~1/RELEASE_ARM64_T7000 iPhone7,2 arm64 N61AP Darwin
    ```
  * sysctl
    * kern.version
      ```bash
      Darwin Kernel Version 18.7.0: Mon Aug 19 22:24:08 PDT 2019; root:xnu-4903.272.1~1/RELEASE_ARM64_T7000
      ```

### checkra1n

用checkra1n给iPhone6越狱的日志中有：

```bash
set xnu boot arg cmdline to : [rootdev=md0]
```

## iPhone7

对于自己的越狱手机，此处的iPhone7，去查看对应的xnu的版本：

```bash
➜  ~ ssh root@192.168.0.33
iPhone7:~ root# uname -a
Darwin iPhone7 19.6.0 Darwin Kernel Version 19.6.0: Sat Jun 27 04:35:37 PDT 2020; root:xnu-6153.142.1~4/RELEASE_ARM64_T8010 iPhone9,1 arm64 D10AP Darwin
```

此处被测的已越狱的iPhone的xnu是：

`xnu-6153.142.1`

去官网找对应版本的代码：

[xnu Source Browser (apple.com)](https://opensource.apple.com/tarballs/xnu/)

没看到这个版本

-》只能找到，最接近的版本：

* xnu-6153.141.1.tar.gz
  * https://opensource.apple.com/tarballs/xnu/xnu-6153.141.1.tar.gz

可下载下来，供后续参考研究。

### unc0ver

用unc0ver给iPhone7越狱的日志中的：

```bash
Kernel Version: Darwin Kernel Version 19.6.0: Sat Jun 27 04:35:37 PDT 2020; root:xnu-6153.142.1~4/RELEASE_ARM64_T8010
```

## iPhone8, iOS 15.1

iOS 15.1，iPhone8的信息：

```bash
iPhone8-150:~ root# uname -a
Darwin iPhone8-150 21.0.0 Darwin Kernel Version 21.0.0: Sun Aug 15 20:55:55 PDT 2021; root:xnu-8019.12.5~1/RELEASE_ARM64_T8015 iPhone10,1 arm Darwin
```

中，就有：

* `xnu-8019.12.5~1/RELEASE_ARM64_T8015 `

其中xnu就是：iOS的内核

版本是：`8019.12.5`
