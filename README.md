AppleALC
========

[![Build Status](https://github.com/ziesnp57/AppleALC/workflows/CI/badge.svg?branch=master)](https://github.com/ziesnp57/AppleALC/actions) [![Scan Status](https://scan.coverity.com/projects/16166/badge.svg?flat=1)](https://scan.coverity.com/projects/16166)

一个开源的内核扩展，为非官方的声卡提供支持的 Codec，无需修改任何系统文件，即可启用原生的 macOS HD 音频，AppleALCU 可用于具有纯数字音频的系统。


#### 特性
- 在系统安装阶段即可使用数字或模拟音频
- 支持恢复模式与安装模式
- 自动检测声卡 Codec
- 启用 Apple 官方不支持的编解码器 (无论是内置还是外置的声卡设备)
- 任意的 Kext 修改补丁
- 可自定义设备的 Layout 和 platform
- 工作在 SIP 模式 / El Capitan+ 系统
- 当前版本兼容: 10.4-14
- 无需任何系统文件修改



