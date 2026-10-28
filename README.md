# FlymeEars

把**第三方蓝牙耳机**接进**魅族耳机 App**（`com.meizu.earphone`）的 LSPosed 模块。
首个支持型号：**OPPO Enco X2**（魅族 21 Pro / Flyme 12.6 / Android 16）。

## 功能

- 连接耳机时拉起 Flyme **原生连接弹窗**（名称 / 配图 / 左右耳与充电盒电量）
- 第三方耳机出现在魅族耳机 App 的**设备列表**中，可进入原生设备详情页
- 详情页显示**电量与当前降噪模式**，可切换 关闭 / 降噪 / 通透
- 控制中心「降噪」磁贴，标签带电量
- 直接走 OPPO 私有 RFCOMM 协议，**无需「欢律」App**

## 使用条件

- 魅族手机 + Flyme（当前验证：魅族 21 Pro / Flyme 12.6 / Android 16）
- 已安装 LSPosed，作用域勾选：`com.android.systemui`、`com.meizu.earphone`、`com.meizu.connectivitysettings`
- 首次使用需重启手机

## 源码与问题反馈

- 源码：<https://github.com/cnnceart/FlymeEars>
- 问题反馈：<https://github.com/cnnceart/FlymeEars/issues>

## 许可

GPL-3.0。协议实现与耳机渲染素材来自 [HyperEars](https://github.com/silverpoetry/HyperEars)（GPL-3.0），
更多出处见源码仓库的 `THIRD_PARTY_NOTICES.md`。

Meizu、Flyme、OPPO、Enco 等商标仅用于兼容性描述，归各自权利人所有。
