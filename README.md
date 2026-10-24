# 7kimisu-susfs

7kimisu v2.30 的 `kernel/` 源码 + SUSFS v2.3.0 内联补丁，用于自编译 GKI 内核。

- 上游：https://github.com/hartgerinktarcila-design/7kimisu (GPL-2.0 kernel part)
- SUSFS 补丁来源：https://github.com/cctv18/susfs4oki (branch oki-android15-6.6)
- 内核版本号必须钉 `KSU_VERSION_PIN=32649`，与官方发布内核一致
- 相对上游的全部改动仅在 kernel/ 内，未触碰 manager/ 签名逻辑

本仓库仅为个人设备（Lenovo TB322FC / SM8750 / android15-6.6）自编译使用。
