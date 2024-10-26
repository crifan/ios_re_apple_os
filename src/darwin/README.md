# Darwin

* `Darwin`
  * logo
    * ![darwin_logo_hexley](../assets/img/darwin_logo_hexley.png)
  * 概述：各种Apple设备的操作系统的内核
    * 而`Darwin`的内核是[XNU](../xnu/README.md)
      * `Darwin` = `XNU` + 其他（`kernel` + `运行时`）
  * Darwin架构
    * 早期
      * `OS X`的架构
        * ![os_x_arch](../assets/img/os_x_arch.png)
    * `OS X`的内核 + 其他部分 => `Darwin`
      * `Darwin and OS X`的架构
        * ![darwin_os_x_arch](../assets/img/darwin_os_x_arch.png)
      * (Mac) `OS X`的内核 == `Darwin` 的架构
        * ![os_x_kernel_arch](../assets/img/os_x_kernel_arch.png)
    * 最新
      * Darwin架构细节
        * ![darwin_arch](../assets/img/darwin_arch.webp)
  * 组成
    * `XNU`
      * 微内核：`Mach`
      * 宏内核：`BSD`
        * `FreeBSD`
      * `IOKit`
    * 其他
      * `kernel`
      * `运行时`
  * 特点
    * 兼容`POSIX`
  * Darwin发展历史
    * 文字
      * `Darwin 0–8`: 对应着`Mac OS X`
      * `Darwin 9`：引入支持`iPhone OS`
      * `Darwin 10-11`：`iPhone OS`改名为`iOS`
      * `Darwin 12–15`：`Mac OS X`改名为`OS X`
      * `Darwin 16–19`：`OS X`改名为`macOS`
      * `Darwin 20+`：最新的各个版本
    * 图
      * ![darwin_arch_history](../assets/img/darwin_arch_history.png)
  