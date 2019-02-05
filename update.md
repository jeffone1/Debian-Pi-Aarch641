# 更新说明

## 2019.02.06 &nbsp;&nbsp;//

1. 内核已更新至Linux主线版本: *4.14.97* 
2. 固件驱动已同步更新至主线内核: *4.14.97*


## 2019.02.05 &nbsp;&nbsp;// *All Released to U5*

1. 修复音频热插拔电源问题
2. 去除内核多余的ARMV7支持
3. 调整内核GPU有关CMA的内存交换大小设置
4. 修复bcm2835相关驱动内核重载问题
5. 优化深度桌面rootFS构建结构
6. 优化Xface桌面rootFS构建结构
7. 重新调整构建系统
8. 升级OPENGL驱动
9. 发布基于U5基础系统的深度桌面环境的系统镜像
10. 发布基于U5基础系统的Xface桌面环境的系统镜像
11. 强化内核GPU内存交换效率
12. 优化VC4的内核代码
13. 修正时区设置问题
14. 优化字体缓存
15. 添加对本地终端中文显示的支持
16. 重构桌面系统镜像的构建环境
17. 内核升级至主线 *4.14.95，Jan 30 2019*
18. 系统升级至 *debian 9 arm64* 兼容主线 *Feb 5 2019*

## 2019.02.01 &nbsp;&nbsp;// *Desktop System Image Released U4*

1. **Xface** *Aarch64(ARM64)* 桌面系统镜像U4 **已发布！** (基于U4版基础系统镜像)
2. **Deepin** *Aarch64(ARM64)* 深度桌面系统镜像U4 **已发布！** (基于U4版基础系统镜像)

## 2019-01-31-v2019-1.0-U4 &nbsp;&nbsp;// *Update4*

1. 调整构建系统参数
2. 优化内核GPU驱动
3. 调整内核CMA至32
4. 增大GPU内存交换空间
5. 内核魔改,以兼容深度系统
6. 优化深度系统下内核GPU的效率
7. 系统包更新至Debian稳定主线：2019-01-31

## 2019-01-26-v2019-1.0-U3 &nbsp;&nbsp;// *Update3*

1. 系统内核同步更新至Linux主线长期支持：**4.14.95**
2. 固件 *Firmware *更新至对应内核主线：*4.14.95*
3. 加入内核对 *virtio_pci、virtio_mmio、virtio_gpu* 的支持 
4. 其他内核细微改动
5. 系统包更新至Debian稳定主线：2019-01-26

## 2019-01-18-v2019-1.0-U2 &nbsp;&nbsp;// *Update2*

1. 系统内核同步更新至Linux主线长期支持：**4.14.93**
2. 固件 *Firmware *更新至对应内核主线：*4.14.93*
3. 启用内核对USB连接SCSI设备的支持
4. 更新内核提交内容至0118
5. 增加了对 *shellinabox* 的支持，最新镜像可用
6. 添加了对 *zram* 的支持，以满足一些特殊场景下的需求
7. 最新镜像默认添加了对各类压缩软件格式的支持
8. 最新镜像加入了对vfat分区修复检查工具的支持
9. 新版镜像调整了 *cmdline.txt* 的默认启动参数
10. 新版镜像调整了 *config.txt* 的默认配置模板
11. *Dcoker-CE* 更新至：**18.09.1**
12. 默认开启WebShell，现可以直接使用浏览器登录系统
13. 系统包更新至Debian稳定主线：2019-01-18


## 2019.01.10 &nbsp;&nbsp;// *SoftWare Update*

- **qemu-kvm** 虚拟机更新至 *qemu-2.12+dfsg-3ubuntu9*

## 2019-01-02-v2019-1.0-u1 &nbsp;&nbsp;// *Update1*

1. 系统内核同步更新至Linux主线长期支持：4.14.91
2. 为KVM硬件虚拟化模式加入KSM内核支持（自动开启，无需手动加载）
3. 发布原生Aarch64架构的QEMU虚拟机软件包，支持KVM硬件加速，并提供了默认的*Debian Aarch64*虚拟机镜像
4. 系统包更新至Debian稳定主线：2019-01-02

>**什么是KSM ？**
</br>KSM的原理，是多个进程中，Linux将内核相似的内存页合并成一个内存页
这个特性，被KVM用来减少多个相似的虚拟机的内存占用，提高内存的使用效率由于内存是共享的
所以多个虚拟机使用的内存减少了，这个特性，对于虚拟机使用相同镜像和操作系统时，效果更加明显

#### 2018-12-30-v2019-1.0 &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;// *第一版*

1. 系统包更新至Debian稳定主线：2018-12-30
2. 使用官方Dcoker-CE 版本已更新至：18.09
3. 固件Firmware已更新至：v1.20181112
4. 无线固件已更新至：2018-08-20官方版
5. 系统内核同步更新至Linux主线长期支持：4.14.90