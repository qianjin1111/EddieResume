---
title: "Android 高级客户端开发工程师"
author: "钱弋海"
date: "2026-06-15"
geometry: "margin=1in"
fontsize: "11pt"
mainfont: "PingFang SC"
monofont: "SF Mono"
colorlinks: true
linkcolor: blue
urlcolor: blue
---

# 钱弋海

**Android 高级客户端开发** · 10 年经验 · 现居北京

📧 qianjin1111@gmail.com · 🌐 [qianjin1111.github.io/EddieResume](https://qianjin1111.github.io/EddieResume)

---

## 个人简介

10 年移动客户端研发经验，长期聚焦 **Android 原生 + HarmonyOS + 跨端（KMP/Compose）**，能独立完成从需求梳理、方案设计、核心编码、联调到发布及线上质量治理的闭环。

- 2021.04 起就职于 **懂车帝**（至今在职）
- 既做过大跨度系统版本升级、多设备适配，也主导过冷启动 / 卡顿 / 内存 / 包体积等性能专项
- 擅长用 Profiler / 抓栈 / Hook 等手段定位疑难问题并形成可复用方法论
- 在字节内部持续沉淀鸿蒙工程基础能力、一多与体验提升、性能优化日报等实践文档

---

## 专业技能

### 平台与语言
精通 **Java / Kotlin**，熟悉 C/C++（JNI/NDK）、ArkTS；具备 Kotlin Multiplatform / Compose 跨端实战经验

### Android 客户端与架构
熟悉 Activity/Fragment、View 体系与复杂列表构建，掌握 **MVVM、组件化/模块化分层**，具备折叠屏 / PAD / 横竖屏等多形态 UI 适配经验

### 网络通信
熟练基于 HTTP/HTTPS、WebSocket 进行接口通信与长连接管理，了解 TCP/UDP 基础与常见网络问题定位

### 数据存储与本地能力
熟悉 SharedPreferences / 文件 / SQLite 等本地存储，掌握 Keva、AutoDatabase 等 K-V / ORM 方案

### 性能与稳定性（核心优势）
- Android/HarmonyOS 冷启动、ANR/卡顿/掉帧、内存/OOM、包体积与功耗优化
- 熟悉 Native Crash 分析（信号/寄存器/Tombstone/backtrace）、ANR 归因、Java/Native OOM 分类与治理
- 理解 **Hook 技术**（PLT/GOT hook、Inline hook、Java/ART Hook），结合 bytehook/shadowhook 做监控与问题定位
- 熟悉 Slardar/NPTH、btrace、Sliver、Raphael、Tailor 等监控与 Trace 工具

### 工程化与发布
掌握多分支协作与 MR 流程，熟悉灰度发布与稳定发布节奏；主导过 IDE/SDK 大版本升级

---

## 工作经历

### 懂车帝 · Android 高级开发工程师
**2021.04 — 至今** · 北京

- 主导 **Android 问题定位与性能优化体系建设**，覆盖 Native Crash / ANR / OOM / 启动 / 卡顿丢帧等核心稳定性与性能问题，建立标准化 SOP
- 主导 **鸿蒙客户端性能治理**，以 DevEco Profiler 为统一口径治理冷启动、卡顿丢帧与内存问题，形成每日性能优化日报机制
- 负责多设备适配（折叠屏 / 三折叠 / PAD），双折叠屏体验评分 4.79、三折叠屏 4.54，领先竞品
- 主导 HarmonyOS API17 → API20 大版本升级，制定可控升级节奏，升级期间主流程无重大线上事故

### 趣头条 · Android 开发工程师
**2018.09 — 2021.04** · 上海

- 独立完成「爱走路」网赚 App 从 0 到 1 的整体搭建和上线
- 参与主 App 冷启动专项，拆分启动耗时点和启动线程治理
- 承担包体积压缩专项，将主包体积从 20M+ 压缩至约 11M

### 自如网 · Android 开发工程师
**2015.09 — 2018.09** · 北京

- 参与自如客 App 核心业务模块的功能开发、性能优化与架构演进

---

## 教育背景

**延边大学** · 计算机科学与技术 · 全日制本科 · 2011 — 2015

---

## 项目经历

> 详细项目经历（STAR 描述）待补充，以下为概要：

### Android 问题定位与性能优化体系建设
围绕 Native Crash、ANR、OOM、启动慢、卡顿丢帧等高频问题，建设统一问题定位 SOP。通过 Slardar 聚类发现线上问题，结合 Tombstone、ANR traces、Perfetto、Memory Profiler 等证据进行线下归因，沉淀团队排查手册与复盘模板。

### 鸿蒙客户端性能优化专项
以 DevEco Profiler 为统一口径治理冷启动、卡顿丢帧与内存问题。通过 Launch 拆解启动阶段耗时并将启动任务按首屏必需/非必需分级；通过 Frame/Trace 定位复杂页面掉帧问题；形成每日性能优化日报与同口径复测机制。

### 多端工程实践与鸿蒙性能治理
在 DcarHarmony + DcarKMP 双仓架构下，搭建多设备 UI 适配规范，设计「进入态保持 + 中转退出」方案解决 KMP 车系页横竖屏切换状态丢失问题，沉淀横竖屏 / 状态栏 / 挖孔区适配工具类。

---

> 📄 下载 PDF 版本：[resume.pdf](https://github.com/qianjin1111/EddieResume/releases/latest/download/resume.pdf)
