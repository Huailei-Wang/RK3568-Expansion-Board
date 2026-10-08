# RK3568 Expansion Board

基于 TOPEET RK3568 核心板的扩展板 Cadence 硬件工程。

## 当前更新

更新时间：2026-10-08

- 完成到 HDMI 的元件布局。

## 历史更新

### 2026-10-06

- 新增 RK3568 官方资料及硬件设计指南。
- 新增讯为（TOPEET）RK3568 核心板原理图资料。
- 新增相对延迟等长设置参考文档。
- 新增 Cadence Allegro 快捷键配置及说明文件。
- 完成整板板框设计。
- 完成重要外设布局。
- 完成 RGMII 外设布局。

## 工程目录

- `PCB/`：Cadence Allegro PCB 工程文件。
- `SCH/`：Cadence Capture 原理图工程文件。
- `相关文档/`：RK3568 官方资料、硬件设计指南、核心板原理图及布线参考文档。
- `快捷键/`：Cadence Allegro 快捷键配置 `env` 和快捷键说明表格。

## 参考资料

- [RK3568 官方资料压缩包](<相关文档/RK3568官方资料/RK3568_Official Release.rar>)
- [Rockchip RK3568 硬件设计指南 V1.2（中文）](相关文档/Rockchip_RK3568_Hardware_Design_Guide_V1.2_CN.pdf)
- [讯为 RK3568 DDR4 核心板原理图 V1.2](相关文档/核心板原理图/TOPEET_RK3568_COREDDR4X2_V1_2_PV.pdf)
- [相对延迟等长设置](相关文档/相对延迟等长设置.pdf)
- [Allegro 快捷键配置](快捷键/env)
- [快捷键说明](快捷键/快捷键说明.xlsx)

`env` 中的 `padpath` 和 `psmpath` 使用本地封装库路径，使用时请按实际环境调整。

## 说明

本仓库用于记录 RK3568 扩展板的原理图与 PCB 设计进展。
