# Awesome Rust [![lint badge](https://github.com/rust-unofficial/awesome-rust/actions/workflows/lint.yml/badge.svg)](https://github.com/rust-unofficial/awesome-rust/actions/workflows/lint.yml) [![build badge](https://github.com/rust-unofficial/awesome-rust/actions/workflows/rust.yml/badge.svg?branch=main)](https://github.com/rust-unofficial/awesome-rust/actions/workflows/rust.yml) [![Track Awesome List](https://www.trackawesomelist.com/badge.svg)](https://www.trackawesomelist.com/rust-unofficial/awesome-rust/)

精选的 Rust 代码与资源列表。

如果你想做出贡献，请阅读[这份指南](CONTRIBUTING.md)。

<!-- BEGIN mktoc {"min_depth": 2} -->

- [应用程序](#应用程序)
  - [音频与音乐](#音频与音乐)
  - [区块链](#区块链)
  - [数据库](#数据库)
  - [嵌入式](#嵌入式)
  - [模拟器](#模拟器)
  - [文件管理器](#文件管理器)
  - [金融](#金融)
  - [游戏](#游戏)
  - [图形](#图形)
  - [图像处理](#图像处理)
  - [工业自动化](#工业自动化)
  - [消息队列](#消息队列)
  - [MLOps](#mlops)
  - [可观测性](#可观测性)
  - [操作系统](#操作系统)
  - [包管理器](#包管理器)
  - [支付](#支付)
  - [效率工具](#效率工具)
  - [路由协议](#路由协议)
  - [安全工具](#安全工具)
  - [社交网络](#社交网络)
  - [系统工具](#系统工具)
  - [任务调度](#任务调度)
  - [文本编辑器](#文本编辑器)
  - [文本处理](#文本处理)
  - [实用工具](#实用工具)
  - [视频](#视频)
  - [虚拟化](#虚拟化)
  - [Web](#web)
  - [Web 服务器](#web-服务器)
  - [工作流自动化](#工作流自动化)
- [开发工具](#开发工具)
  - [构建系统](#构建系统)
  - [调试](#调试)
  - [部署](#部署)
  - [嵌入式](#嵌入式-1)
  - [FFI](#ffi)
  - [格式化工具](#格式化工具)
  - [IDE](#ide)
  - [性能分析](#性能分析)
  - [服务](#服务)
  - [静态分析](#静态分析)
  - [测试](#测试)
  - [转译](#转译)
  - [隧道](#隧道)
- [库](#库)
  - [人工智能](#人工智能)
    - [遗传算法](#遗传算法)
    - [Google Gemini](#google-gemini)
    - [机器学习](#机器学习)
    - [OpenAI](#openai)
    - [工具](#工具)
  - [天文学](#天文学)
  - [异步](#异步)
  - [音频与音乐](#音频与音乐-1)
  - [身份验证](#身份验证)
  - [汽车](#汽车)
  - [生物信息学](#生物信息学)
  - [缓存](#缓存)
  - [云](#云)
  - [命令行](#命令行)
  - [压缩](#压缩)
  - [计算](#计算)
  - [并发](#并发)
  - [配置](#配置)
  - [密码学](#密码学)
  - [数据处理](#数据处理)
  - [数据流](#数据流)
  - [数据结构](#数据结构)
  - [数据可视化](#数据可视化)
  - [数据库](#数据库-1)
  - [日期与时间](#日期与时间)
  - [分布式系统](#分布式系统)
  - [领域驱动设计](#领域驱动设计)
  - [eBPF](#ebpf)
  - [电子邮件](#电子邮件)
  - [编码](#编码)
  - [文件系统](#文件系统)
  - [金融](#金融-1)
  - [函数式编程](#函数式编程)
  - [游戏开发](#游戏开发)
  - [地理空间](#地理空间)
  - [图算法](#图算法)
  - [图形](#图形-1)
  - [GUI](#gui)
  - [图像处理](#图像处理-1)
  - [语言规范](#语言规范)
  - [许可证](#许可证)
  - [日志](#日志)
  - [宏](#宏)
  - [标记语言](#标记语言)
  - [移动端](#移动端)
  - [网络编程](#网络编程)
  - [解析](#解析)
  - [外设](#外设)
  - [平台相关](#平台相关)
  - [逆向工程](#逆向工程)
  - [脚本](#脚本)
  - [仿真](#仿真)
  - [社交网络](#社交网络-1)
  - [系统](#系统)
  - [任务调度](#任务调度-1)
  - [模板引擎](#模板引擎)
  - [文本处理](#文本处理-1)
  - [文本搜索](#文本搜索)
  - [Unsafe](#unsafe)
  - [视频](#视频-1)
  - [虚拟化](#虚拟化-1)
  - [Web 编程](#web-编程)
- [注册中心](#注册中心)
- [资源](#资源)
- [许可证](#许可证-1)
<!-- END mktoc -->

## 应用程序

* [ad-si/Woxi](https://github.com/ad-si/Woxi) [[woxi](https://crates.io/crates/woxi)] - 由 Rust 驱动的 Wolfram 语言解释器。
* [alacritty](https://github.com/alacritty/alacritty) - 跨平台、GPU 加速的终端模拟器
* [Andromeda](https://github.com/tryandromeda/andromeda) - 用 Rust 🦀 从零构建、由 Nova 引擎驱动的 JavaScript 与 TypeScript 运行时。
* [arimxyer/models](https://github.com/arimxyer/models) [[modelsdev](https://crates.io/crates/modelsdev)] - 用于浏览 AI 模型、基准测试和编码代理的 TUI [![CI](https://github.com/arimxyer/models/actions/workflows/ci.yml/badge.svg)](https://github.com/arimxyer/models/actions/workflows/ci.yml)
* [Arti](https://gitlab.torproject.org/tpo/core/arti) - Tor 的一个实现。（目前还是一个不太完整的客户端，敬请期待！） [![Crates.io](https://img.shields.io/crates/v/arti.svg)](https://crates.io/crates/arti)
* [asm-cli-rust](https://github.com/cch123/asm-cli-rust) - 交互式汇编 shell。
* [Aster-Privacy/Aster-Mail](https://github.com/Aster-Privacy/Aster-Mail) - 私密、端到端加密的电子邮件，具备抗量子保护、PGP、别名和自定义域名。使用 Tauri 构建的桌面应用。
* [clash-verge-rev/clash-verge-rev](https://github.com/clash-verge-rev/clash-verge-rev) - 基于 Tauri 和 Rust 的跨平台现代 Clash GUI，支持 Windows、macOS 和 Linux。
* [cloudflare/boringtun](https://github.com/cloudflare/boringtun) - 用户态 WireGuard VPN 实现 [![build badge](https://img.shields.io/crates/v/boringtun.svg)](https://crates.io/crates/boringtun)
* [DBX](https://github.com/t8y2/dbx) - 使用 Tauri 构建的轻量级开源数据库管理工具，支持 MySQL、PostgreSQL、SQLite、Redis、MongoDB、DuckDB 等。[![CI](https://github.com/t8y2/dbx/actions/workflows/ci.yml/badge.svg)](https://github.com/t8y2/dbx/actions/workflows/ci.yml)
* [defguard](https://github.com/defguard/defguard) - 企业级开源 SSO 与 WireGuard VPN，支持真正的 2FA/MFA
* [denoland/deno](https://github.com/denoland/deno) - 使用 V8 和 Tokio 构建的安全 JavaScript/TypeScript 运行时 [![Build Status](https://github.com/denoland/deno/actions/workflows/ci.yml/badge.svg)](https://github.com/denoland/deno/actions)
* [doprz/dipc](https://github.com/doprz/dipc) - 使用你喜欢的配色方案/主题转换你喜欢的图片和壁纸 [![crates.io](https://img.shields.io/crates/v/dipc)](https://crates.io/crates/dipc)
* [EasyTier](https://github.com/EasyTier/EasyTier) - 简单、功能齐全且去中心化的网状 VPN，支持 WireGuard。[![crates.io](https://img.shields.io/crates/v/easytier)](https://crates.io/crates/easytier) [![GitHub actions](https://github.com/EasyTier/EasyTier/actions/workflows/core.yml/badge.svg)](https://github.com/EasyTier/EasyTier/actions/)[![GitHub actions](https://github.com/EasyTier/EasyTier/actions/workflows/gui.yml/badge.svg)](https://github.com/EasyTier/EasyTier/actions/)
* [Edit](https://github.com/microsoft/edit) - 满足简单需求的简单编辑器。[![CI](https://github.com/microsoft/edit/actions/workflows/ci.yml/badge.svg)](https://github.com/microsoft/edit/actions/workflows/ci.yml)
* [fcsonline/drill](https://github.com/fcsonline/drill) - 受 Ansible 语法启发的 HTTP 负载测试应用
* [fend](https://github.com/printfn/fend) - 任意精度、支持单位的计算器 [![build](https://github.com/printfn/fend/workflows/build/badge.svg)](https://github.com/printfn/fend/actions/workflows/actions.yml)
* [Fractalide](https://github.com/fractalide/fractalide) - 简单的微服务
* [GCWing/BitFun](https://github.com/GCWing/BitFun) - 跨平台桌面 AI 代理，具备可在真实代码库中工作的 Rust 运行时，能够驱动浏览器、终端和桌面应用
* [giga-grabber](https://github.com/chanderlud/giga-grabber) - 非常快速且相对稳定的 Mega 下载器 [![build](https://github.com/chanderlud/giga-grabber/actions/workflows/release.yml/badge.svg)](https://github.com/chanderlud/giga-grabber/actions/workflows/release.yml)
* [glzr-io/glazewm](https://github.com/glzr-io/glazewm) - 受 i3wm 启发的 Windows 平铺窗口管理器，支持 YAML 配置、多显示器以及键盘驱动命令
* [google/mdbook-i18n-helpers](https://github.com/google/mdbook-i18n-helpers) [[mdbook-i18n-helpers](https://crates.io/crates/mdbook-i18n-helpers)] - 面向 mdbook 的国际化与渲染扩展。
* [habitat](https://github.com/habitat-sh/habitat) - 由 Chef 创建的用于构建、部署和管理应用的工具。
* [HaseebKhalid1507/SynapsCLI](https://github.com/HaseebKhalid1507/SynapsCLI) [[synaps](https://crates.io/crates/synaps)] - 终端原生的 AI 代理运行时，具备 ratatui TUI、并行子代理、MCP 服务器以及可用任意语言编写的插件 [![CI](https://github.com/HaseebKhalid1507/SynapsCLI/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/HaseebKhalid1507/SynapsCLI/actions/workflows/ci.yml)
* [Herd](https://github.com/imjacobclark/Herd) - 实验性的 HTTP 负载测试应用
* [hickory-dns](https://crates.io/crates/hickory-dns) - DNS 服务器 [![Build Status](https://github.com/hickory-dns/hickory-dns/actions/workflows/test.yml/badge.svg)](https://github.com/hickory-dns/hickory-dns/actions?query=workflow%3Atest)
* [innernet](https://github.com/tonarino/innernet) - 底层使用 Wireguard 的覆盖网络或私有网状网络
* [jedisct1/flowgger](https://github.com/awslabs/flowgger) - 快速、简单且轻量的数据采集器
* [kalker](https://github.com/PaddiM8/kalker) - 科学计算器，支持类数学语法，具备用户自定义变量、函数、求导、积分和复数。跨平台 + WASM 支持 [![Build Status](https://github.com/PaddiM8/kalker/workflows/Release/badge.svg)](https://github.com/PaddiM8/kalker/actions)
* [kftray](https://github.com/hcavarsan/kftray) - 跨平台系统托盘应用，用于管理和共享多个 kubectl 端口转发配置。[![Build Status](https://github.com/hcavarsan/kftray/workflows/Release/badge.svg)](https://github.com/hcavarsan/kftray/actions)
* [kytan](https://github.com/changlan/kytan) - 高性能点对点 VPN
* [linkerd/linkerd2-proxy](https://github.com/linkerd/linkerd2-proxy) - 面向 Kubernetes 的超轻量服务网格。
* [LWE](https://github.com/YangYuS8/lwe) - 用于浏览、管理和应用 Wallpaper Engine 内容的 Linux 桌面应用，使用 Rust 和 Tauri 构建。
* [lzanini/mdbook-katex](https://github.com/lzanini/mdbook-katex) [[mdbook-katex](https://crates.io/crates/mdbook-katex)] - 面向 [mdBook](https://github.com/rust-lang/mdBook) 的预处理器，使用 KaTeX 渲染 LaTeX 数学表达式。
* [MaidSafe](https://github.com/maidsafe) - 去中心化平台。
* [mayocream/koharu](https://github.com/mayocream/koharu) - 由机器学习驱动的漫画翻译器，具备自动气泡检测、OCR、图像修复和 LLM 翻译，使用 Candle 和 Tauri 构建
* [mdBook](https://github.com/rust-lang/mdBook) - 从 Markdown 文件创建书籍的命令行工具 [![Build Status](https://github.com/rust-lang/mdBook/actions/workflows/main.yml/badge.svg)](https://github.com/rust-lang/mdBook/actions)
* [Mega](https://github.com/web3infra-foundation/mega) - 支持 Git 的 monorepo 与单体代码库管理系统，也是 Google Piper 的非官方开源实现。
* [Michael-F-Bryan/mdbook-linkcheck](https://github.com/Michael-F-Bryan/mdbook-linkcheck) [[mdbook-linkcheck](https://crates.io/crates/mdbook-linkcheck)] - mdbook 的后端，可为你检查链接。
* [mirrord](https://github.com/metalbear-co/mirrord) - 将本地进程与云环境连接，在云环境中运行本地代码
* [mmalmi/nostr-vpn](https://github.com/mmalmi/nostr-vpn) [[nvpn](https://crates.io/crates/nvpn)] - 基于 Nostr 身份和 FIPS 支持的数据平面构建的 Tailscale 风格私有网状 VPN。提供原生跨平台应用（macOS、Linux、Windows、移动端）以及 CLI/守护进程。
* [newdee/magpie](https://github.com/newdee/magpie) - 本地优先的 Spotlight 风格启动器，完全在设备端对你的 GitHub 星标、本地文件、图片和视频进行语义搜索。[![CI](https://github.com/newdee/magpie/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/newdee/magpie/actions/workflows/ci.yml)
* [nicohman/eidolon](https://github.com/nicohman/eidolon) - 面向 Linux 和 macOS 的 Steam 及无 DRM 游戏注册表与启动器
* [openma-ai/Martty](https://github.com/openma-ai/Martty) - 面向 DeepSeek Harness 及其他兼容 ACP 的编码代理的 Rust/ratatui 终端客户端。[![CI](https://github.com/openma-ai/Martty/actions/workflows/package-npm.yml/badge.svg?branch=main)](https://github.com/openma-ai/Martty/actions/workflows/package-npm.yml)
* [OxideTerm](https://github.com/AnalyseDeCircuit/oxideterm) - 使用 Tauri 2.0 和纯 Rust SSH（russh）构建的跨平台 SSH 终端客户端与本地终端模拟器。具备多路复用连接、SFTP 文件管理器、内置 IDE（CodeMirror 6）、端口转发（-L/-R/-D）、宽限期自动重连、插件系统、AI 助手、加密导出（.oxide）以及 11 种语言。[![CI](https://github.com/AnalyseDeCircuit/oxideterm/actions/workflows/ci.yml/badge.svg)](https://github.com/AnalyseDeCircuit/oxideterm/actions/workflows/ci.yml)
* [pelazas/p2pmux](https://github.com/pelazas/p2pmux) [[p2pmux](https://crates.io/crates/p2pmux)] - 面向 macOS 和 Linux 的点对点终端复用器，多个用户和机器可加入同一会话；每个窗格都是打开它的那台机器上的真实 shell [![CI](https://github.com/pelazas/p2pmux/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/pelazas/p2pmux/actions/workflows/ci.yml)
* [Pijul](https://pijul.org) - 基于补丁的分布式版本控制系统
* [provrb/OBDium](https://github.com/provrb/obdium) - 基于 Tauri 的跨平台车辆诊断应用。通过 ELM327 适配器连接你的车辆，读取故障码、实时 OBD-II 数据、I/M 就绪测试等！
* [qiluo-admin](https://github.com/chelunfu/qiluo_admin) - 企业级快速开发平台（Axum + SeaORM + JWT + VUE3，支持 MySQL/Postgres/SQLite）
* [Rauthy](https://github.com/sebadob/rauthy) - OpenID Connect 单点登录身份与访问管理
* [Rio](https://github.com/raphamorim/rio) - 由 WebGPU 驱动的硬件加速 GPU 终端模拟器，专注于在桌面和浏览器中运行。
* [rkik](https://github.com/aguacero7/rkik) - 为无状态、被动式 NTP 检测而设计的 CLI 工具，正如 dig 或 ping 之于 DNS 和 ICMP。支持异步请求和持续监控。[![crates.io](https://img.shields.io/crates/v/rkik?logo=rust)](https://crates.io/crates/rkik)
* [run](https://github.com/Esubaalew/run) [[run-kit](https://crates.io/crates/run-kit)] - 通用多语言运行器和智能 REPL（支持 Python、JS、Go、C 等 25 种以上语言）。
* [runmat-org/runmat](https://github.com/runmat-org/runmat) [[runmat](https://crates.io/crates/runmat)] - 用于 MATLAB 语法数值程序的运行时，通过 wgpu 实现 GPU 加速。[![CI](https://github.com/runmat-org/runmat/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/runmat-org/runmat/actions/workflows/ci.yml)
* [Rust Iot Platform](https://github.com/iot-ecology/rust-iot-platform) - 使用 Rust 构建的高性能物联网开发平台，专为多协议支持和实时数据处理而设计。该平台支持 MQTT、WebSockets（WS）、TCP 和 CoAP 协议，对多样化的物联网应用具有极高的灵活性。
* [rx](https://github.com/cloudhead/rx) - 受 Vi 启发的现代像素艺术编辑器
* [Ryot](https://github.com/ignisda/ryot) - 用于追踪媒体消费、健身等的自托管应用。
* [s00d/switchshuttle](https://github.com/s00d/switchshuttle) - 跨平台系统托盘应用，通过全局热键、嵌套菜单和基于 JSON 的配置来组织和运行预定义的终端命令（Tauri + Vue）。
* [Saga Reader](https://github.com/sopaco/saga-reader) - 由 AI 驱动的极速、极致轻量的互联网阅读器。支持抓取搜索引擎信息和 RSS。
* [scarletkc/Hatoba](https://github.com/scarletkc/Hatoba) - 使用 Tauri 和 russh 构建的桌面 SSH 客户端，每个终端旁都有 AI 助手，并通过你自己的 Cloudflare 账户进行端到端加密同步 [![CI](https://github.com/scarletkc/Hatoba/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/scarletkc/Hatoba/actions/workflows/ci.yml)
* [Servo](https://github.com/servo/servo) - 原型 Web 浏览器引擎
* [shoes](https://github.com/cfal/shoes) - 多协议代理服务器
* [shuttle](https://github.com/shuttle-hq/shuttle) - 无服务器平台。
* [Sniffnet](https://github.com/GyulyVGC/sniffnet) - 轻松监控网络流量的跨平台应用 [![build badge](https://img.shields.io/github/actions/workflow/status/gyulyvgc/sniffnet/rust.yml?logo=github)](https://github.com/GyulyVGC/sniffnet/blob/main/.github/workflows/rust.yml) [![crate](https://img.shields.io/crates/v/sniffnet?logo=rust)](https://crates.io/crates/sniffnet)
* [SWC](https://github.com/swc-project/swc) - 超快的 TypeScript / JavaScript 编译器
* [TabbyML/tabby](https://github.com/TabbyML/tabby) - 自托管的 AI 编码助手，GitHub Copilot 的开源替代品，支持 GPU 和 OpenAPI 接口 [![latest release](https://shields.io/github/v/release/TabbyML/tabby)](https://github.com/TabbyML/tabby/releases/latest)
* [temps](https://github.com/gotempsh/temps) - 自托管 PaaS，用一个 Rust 二进制文件替代 Vercel、分析、错误追踪和正常运行时间监控
* [tiny](https://github.com/osa1/tiny) - 终端 IRC 客户端
* [topjohnwu/Magisk](https://github.com/topjohnwu/Magisk) - 一套用于定制 Android 的开源工具，提供 root 访问、启动镜像操作和无系统修改
* [tunnetio/Tunnet](https://github.com/tunnetio/Tunnet) - 具备公共隧道的私有网状网络、基于身份的 SSH 和 P2P 文件传输
* [Tura-AI/tura](https://github.com/Tura-AI/tura) - 面向终端、桌面 GUI 和命令行工作流的本地编码代理，具备持久化任务状态和有证据支持的验证。[![CI](https://github.com/Tura-AI/tura/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/Tura-AI/tura/actions/workflows/ci.yml)
* [Typst](https://github.com/typst/typst) - 基于标记的排版系统 [![crates.io](https://img.shields.io/crates/v/typst.svg)](https://crates.io/crates/typst)
* [unxsist/jet-pilot](https://github.com/unxsist/jet-pilot) - 使用 Tauri 构建的开源 Kubernetes 桌面客户端，具备多集群视图、资源图、结构化日志和内置 kubectl 终端 [![Test](https://github.com/unxsist/jet-pilot/actions/workflows/test.yml/badge.svg?branch=main)](https://github.com/unxsist/jet-pilot/actions/workflows/test.yml)
* [UpVPN](https://github.com/upvpn/upvpn-app) - 基于 Tauri 构建的 macOS、Linux 和 Windows WireGuard VPN 客户端。
* [vortix](https://github.com/Harry-kp/vortix) - 面向 WireGuard 和 OpenVPN 的终端 UI，具备实时遥测、泄漏检测和终止开关
* [vproxy](https://github.com/0x676e67/vproxy) - 高性能的 HTTP/HTTPS/SOCKS5 代理服务器 [![crates.io](https://img.shields.io/crates/v/vproxy.svg)](https://crates.io/crates/vproxy)
* [wasmer](https://github.com/wasmerio/wasmer) - 安全且快速的 WebAssembly 运行时，支持 WASI 和 Emscripten [![Build Status](https://github.com/wasmerio/wasmer/actions/workflows/build.yml/badge.svg)](https://github.com/wasmerio/wasmer/actions)
* [Weld](https://github.com/serayuzgur/weld) - 完整的假 REST API 生成器
* [wezterm](https://github.com/wezterm/wezterm) - GPU 加速的跨平台终端模拟器和复用器
* [WinterJS](https://github.com/wasmerio/winterjs) - 使用 SpiderMonkey 和 Axum 构建的安全 JavaScript 运行时
* [zellij](https://github.com/zellij-org/zellij) - 开箱即用的终端复用器（工作区）
* [Zephyr](https://github.com/Juwan-Hwang/Zephyr) - 使用 Tauri 构建的现代、轻量且安全的 Mihomo（Clash Meta）GUI 客户端。[![Security Audit](https://github.com/Juwan-Hwang/Zephyr/actions/workflows/security.yml/badge.svg)](https://github.com/Juwan-Hwang/Zephyr/actions/workflows/security.yml)

### 音频与音乐

* [AreevAI/flowcat](https://github.com/AreevAI/flowcat) - 面向实时语音 AI 代理（电话 + WebRTC）的原生 Rust 运行时，自托管单一二进制文件，兼容 pipecat
* [dano](https://github.com/kimono-koans/dano) - 面向媒体文件的 hashdeep/md5tree（但功能远不止于此）
* [enginesound](https://github.com/DasEtwas/enginesound) - 用于程序化生成半真实引擎声音的 GUI 和命令行应用。具备深入配置、可变采样率和频率分析窗口。
* [Festival](https://github.com/hinto-janai/festival) - 本地音乐播放器/服务器/客户端 [![build-badge](https://github.com/hinto-janai/festival/actions/workflows/ci.yml/badge.svg)](https://github.com/hinto-janai/festival/actions/workflows/ci.yml)
* [figsoda/mmtc](https://github.com/figsoda/mmtc) [[mmtc](https://crates.io/crates/mmtc)] - 极简的 mpd 终端客户端，力求简单但高度可配置 [![build-badge](https://github.com/figsoda/mmtc/actions/workflows/ci.yml/badge.svg)](https://github.com/figsoda/mmtc/actions/workflows/ci.yml)
* [Glicol](https://github.com/chaosprint/glicol) - 面向图形的实时编码语言，用于浏览器中的协作音乐创作。
* [LargeModGames/spotatui](https://github.com/LargeModGames/spotatui) [[spotatui](https://crates.io/crates/spotatui)] - Spotify 终端客户端，具备原生流媒体、同步歌词和实时音频可视化 [![Continuous Deployment](https://github.com/LargeModGames/spotatui/actions/workflows/cd.yml/badge.svg)](https://github.com/LargeModGames/spotatui/actions/workflows/cd.yml)
* [mierak/rmpc](https://github.com/mierak/rmpc) [[rmpc](https://crates.io/crates/rmpc)] - 现代且可配置的、基于终端的 MPD 客户端，支持专辑封面
* [ncspot](https://github.com/hrkfdn/ncspot) - 跨平台的 ncurses Spotify 客户端，受 ncmpc 等启发。[![build badge](https://github.com/hrkfdn/ncspot/actions/workflows/ci.yml/badge.svg)](https://github.com/hrkfdn/ncspot/actions?query=workflow%3ABuild)
* [OpenMeters](https://github.com/httpsworldview/openmeters) - 用 Rust 编写的、面向 Linux 的快速、简单且专业的音频计量/可视化工具。
* [Pinepods](https://github.com/madeofpendletonwool/PinePods) - 基于 Rust 的播客管理系统，支持多用户。Pinepods 使用中央数据库，因此收听时长和主题等设置可在设备间同步。配合使用 Tauri 构建的客户端，它是一套完整的跨平台收听方案！[![Docker Container Build](https://github.com/madeofpendletonwool/PinePods/actions/workflows/docker-publish.yml/badge.svg)](https://github.com/madeofpendletonwool/PinePods/actions/workflows/docker-publish.yml)
* [PodFetch](https://github.com/SamTV12345/PodFetch) - 自托管播客管理器，可自动下载新单集，提供用于收听的 Web UI 以及供 AntennaPod 等移动应用使用的、兼容 GPodder 的同步 API。[![build badge](https://github.com/SamTV12345/PodFetch/actions/workflows/rust.yml/badge.svg)](https://github.com/SamTV12345/PodFetch/actions/workflows/rust.yml)
* [Polaris](https://github.com/agersant/polaris) - 音乐流媒体应用。
* [rusty-amp](https://github.com/danylokravchenko/rusty-amp) - 完整支持外部插件的吉他音箱和踏板效果器装置，可直接在你的终端中运行。
* [Spotify Player](https://github.com/aome510/spotify-player) - 终端中的 Spotify 播放器，功能完全对等。
* [Spotifyd](https://github.com/Spotifyd/spotifyd) - 作为 UNIX 守护进程运行的开源 Spotify 客户端。[![Continuous Integration](https://github.com/Spotifyd/spotifyd/actions/workflows/ci.yml/badge.svg)](https://github.com/Spotifyd/spotifyd/actions/workflows/ci.yml)
* [termusic](https://github.com/tramhao/termusic) - 音乐播放器 TUI
* [tunein-cli](https://github.com/tsirysndr/tunein-cli) - 直接在终端中浏览并收听全球数千个电台 [![CI](https://github.com/tsirysndr/tunein-cli/actions/workflows/ci.yml/badge.svg)](https://github.com/tsirysndr/tunein-cli/actions/workflows/ci.yml)
* [WhatBPM](https://github.com/sergree/whatbpm) - 面向电子舞曲制作人的每日静态生成信息资源。利用 Beatport 和 Spotify 等公开数据，为每种 EDM 流派提供最常用数值（速度、调性、根音等）的每日分析。
* [ZacharyL2/KeyEcho](https://github.com/ZacharyL2/KeyEcho) - 使用 Tauri 构建的桌面应用，在你打字时播放录制好的机械键盘声音

### 区块链

* [Anchor](https://github.com/solana-foundation/anchor) - Anchor 是用于构建安全 Solana 程序（智能合约）的领先开发框架。
* [artemis](https://github.com/paradigmxyz/artemis) - 用于编写 MEV 机器人的简单、模块化且快速的框架。
* [Bitcoin Satoshi's Vision](https://github.com/brentongunning/rust-sv) [[sv](https://crates.io/crates/sv)] - 用于处理 Bitcoin SV 的库。
* [cairo](https://github.com/starkware-libs/cairo) - Cairo 是首个用于创建通用计算可证明程序的图灵完备语言。它也是 [StarkNet](https://www.starknet.io)（使用 STARK 证明的 ZK-Rollup）的原生语言 ![GitHub Workflow Status](https://img.shields.io/github/workflow/status/starkware-libs/cairo/CI?style=flat-square&logo=github)
* [ChainX](https://github.com/chainx-org/ChainX) - Polkadot 上完全去中心化的跨链加密资产管理。
* [CITA](https://github.com/citahub/cita) - 面向企业用户的高性能区块链内核。
* [coinbase-pro-rs](https://github.com/inv2004/coinbase-pro-rs) - Coinbase Pro 客户端，支持同步/异步/WebSocket
* [datahaven-xyz/datahaven](https://github.com/datahaven-xyz/datahaven) - 由 EigenLayer 保护的 AI 优先去中心化存储。
* [Diem](https://github.com/diem/diem) - Diem 的使命是打造一个简单的全球货币和金融基础设施，赋能数十亿人。
* [dusk-network/rusk](https://github.com/dusk-network/rusk) - Dusk 的参考实现，一个面向现实世界资产（RWA）和合规金融应用、注重隐私且可扩展的 FMI。[![Build Status](https://github.com/dusk-network/rusk/actions/workflows/rusk_ci.yml/badge.svg)](https://github.com/dusk-network/rusk/actions/workflows/rusk_ci.yml)
* [electrumrs](https://github.com/romanz/electrs) - Electrum Server 的高效重新实现。
* [equilibriumco/beerus](https://github.com/equilibriumco/beerus) - Beerus 是一个无需信任的 StarkNet 轻客户端，⚡快如闪电 ⚡ [![GitHub Workflow Status](https://github.com/equilibriumco/beerus/actions/workflows/check.yml/badge.svg)](https://github.com/equilibriumco/beerus/actions/workflows/check.yml)
* [ethabi](https://github.com/rust-ethereum/ethabi) - 对智能合约调用进行编码和解码。
* [ethaddrgen](https://github.com/Limeth/ethaddrgen) - 自定义以太坊靓号地址生成器
* [etk](https://github.com/quilt/etk) - etk 是一套用于编写、读取和分析 EVM 字节码的工具。
* [Forest](https://github.com/ChainSafe/forest) - Filecoin 实现 [![Build Status](https://img.shields.io/circleci/build/gh/ChainSafe/forest/main?branch=master)](https://app.circleci.com/pipelines/github/ChainSafe/forest?branch=main)
* [Foundry](https://github.com/foundry-rs/foundry) - Foundry 是一套快速、可移植且模块化的以太坊应用开发工具包。![Build Status](https://img.shields.io/github/workflow/status/foundry-rs/foundry/test?style=flat-square)
* [Grin](https://github.com/mimblewimble/grin/) - MimbleWimble 协议的演进
* [hdwallet](https://github.com/jjyr/hdwallet) [[hdwallet](https://crates.io/crates/hdwallet)] - BIP-32 HD 钱包相关的密钥派生工具。
* [Holochain](https://github.com/holochain/holochain) - 可扩展的 P2P 区块链替代方案，适用于你一直想构建的各种分布式应用。[![detect critical check failures](https://github.com/holochain/holochain/actions/workflows/autorebase.yml/badge.svg)](https://github.com/holochain/holochain/actions/)
* [Hyperlane](https://github.com/hyperlane-xyz/hyperlane-monorepo) - 无需许可、模块化互操作的框架。链下客户端以及 Solana VM 和 CosmWasm 的智能合约均使用 Rust 编写。
* [HyperSync](https://github.com/enviodev/hypersync-client-rust) [[hypersync-client](https://crates.io/crates/hypersync-client)] - Envio 的 HyperSync 客户端，一个返回经过过滤的区块、交易和日志的区块链数据 API，作为 JSON-RPC 的替代方案。[![Build Status](https://github.com/enviodev/hypersync-client-rust/actions/workflows/ci.yaml/badge.svg?branch=main)](https://github.com/enviodev/hypersync-client-rust/actions/workflows/ci.yaml)
* [ibc-rs](https://github.com/informalsystems/hermes) - [Interblockchain Communication](https://docs.cosmos.network/ibc) 协议的实现
* [infincia/bip39-rs](https://github.com/infincia/bip39-rs) [[bip39](https://crates.io/crates/bip39)] - BIP39 的实现。
* [interBTC](https://github.com/interlay/interbtc) - 通往 Polkadot 和 Kusama 的无需信任、完全去中心化的比特币桥。
* [Joystream](https://github.com/Joystream/joystream) - 由用户治理的视频平台
* [Kaspa](https://github.com/kaspanet/rusty-kaspa) - 世界上最快的开源、去中心化且完全可扩展的 Layer-1。
* [Lighthouse](https://github.com/sigp/lighthouse) - 以太坊共识层（CL）客户端 [![Build Status](https://github.com/sigp/lighthouse/actions/workflows/test-suite.yml/badge.svg)](https://github.com/sigp/lighthouse/actions)
* [linera-io/linera-protocol](https://github.com/linera-io/linera-protocol) - 为高度可扩展、低延迟的 Web3 应用设计的去中心化区块链基础设施 [![Build Status](https://github.com/linera-io/linera-protocol/actions/workflows/rust.yml/badge.svg)](https://github.com/linera-io/linera-protocol/actions/workflows/rust.yml)
* [near/nearcore](https://github.com/near/nearcore) - 面向低端移动设备的去中心化智能合约平台。
* [Nervos CKB](https://github.com/nervosnetwork/ckb) - Nervos CKB 是一条公共无需许可的区块链，是 Nervos 网络的公共知识层。
* [opensea-rs](https://github.com/gakonst/opensea-rs) - Opensea API 和合约的绑定与 CLI。
* [Parity-Bitcoin](https://github.com/paritytech/parity-bitcoin) - Parity 比特币客户端
* [Phala-Network/phala-blockchain](https://github.com/Phala-Network/phala-blockchain) - 基于 Intel SGX 和 Substrate 的机密智能合约区块链
* [polkadot-sdk](https://github.com/paritytech/polkadot-sdk) - Parity Polkadot 区块链 SDK
* [pragma-org/amaru](https://github.com/pragma-org/amaru) - 用 Rust 编写的 Cardano 节点客户端。
* [reth](https://github.com/paradigmxyz/reth) - 模块化、对贡献者友好且极快的以太坊协议实现。
* [revm](https://github.com/bluealloy/revm) - Revolutionary Machine（revm）是一个快速的以太坊虚拟机。
* [rust-bitcoin](https://github.com/rust-bitcoin/rust-bitcoin) - 支持比特币相关数据结构和网络消息的序列化/反序列化、解析和执行的库。
* [rust-lightning](https://github.com/lightningdevkit/rust-lightning) [![Crate](https://img.shields.io/crates/v/lightning.svg?logo=rust)](https://crates.io/crates/lightning) - 比特币闪电网络库。主 crate `lightning` 不处理网络、持久化或任何其他 I/O。因此它与运行时无关，但用户必须自行实现基本的网络逻辑、链交互和磁盘存储。
* [sigma-rust](https://github.com/ergoplatform/sigma-rust) - ErgoTree 解释器及钱包相关功能。
* [starkware-libs/cairo-vm](https://github.com/starkware-libs/cairo-vm) - Cairo VM 的实现 [![rust](https://github.com/starkware-libs/cairo-vm/actions/workflows/rust.yml/badge.svg)](https://github.com/starkware-libs/cairo-vm/actions/workflows/rust.yml)
* [Subspace](https://github.com/autonomys/subspace) - 首个能够通过同时实现可扩展性、安全性和去中心化来完全解决区块链三难困境的一层区块链。
* [Sui](https://github.com/MystenLabs/sui) - 下一代智能合约平台，具备高吞吐量、低延迟，以及由 Move 编程语言驱动的面向资产的编程模型。
* [svm-rs](https://github.com/alloy-rs/svm-rs) - Solidity 编译器版本管理器。
* [tempoxyz/tempo](https://github.com/tempoxyz/tempo) - 为大规模稳定币支付构建的区块链，具备 EVM 兼容性、亚秒级最终性和原生智能账户功能，基于 Reth SDK 构建
* [tendermint-rs](https://github.com/cometbft/tendermint-rs) - Tendermint 区块链数据结构和客户端
* [wagyu](https://github.com/howardwu/wagyu) [[wagyu](https://crates.io/crates/wagyu)] - 用于生成加密货币钱包的库
* [zcash](https://github.com/zcash/zcash) - Zcash 是 "Zerocash" 协议的一个实现。

### 数据库

* [aimdb-dev/aimdb](https://github.com/aimdb-dev/aimdb) [[aimdb-core](https://crates.io/crates/aimdb-core)] - 面向分布式系统的数据摄取层，具备类型化契约、安全的模式演进，以及从微控制器到云端的每个节点的集中查看和管理。[![CI](https://github.com/aimdb-dev/aimdb/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/aimdb-dev/aimdb/actions/workflows/ci.yml)
* [apecloud/ape-dts](https://github.com/apecloud/ape-dts) - 数据传输套件。提供 MySQL、PostgreSQL、Redis、MongoDB、Kafka、ClickHouse 等之间的数据复制。
* [Atomic-Server](https://github.com/ontola/atomic-server/) [[atomic-server](https://crates.io/crates/atomic_server)] - NoSQL 图数据库，具备实时更新、动态索引和用于 CMS 目的的易用 GUI。[![Release](https://github.com/ontola/atomic-server/actions/workflows/release_please.yml/badge.svg)](https://github.com/ontola/atomic-server/actions)
* [ayarotsky/redis-shield](https://github.com/ayarotsky/redis-shield) - 一个 Redis 模块，将令牌桶算法实现为原生命令，用于高性能限流
* [CozoDB](https://github.com/cozodb/cozo) - 事务型关系数据库，使用 Datalog，专注于图数据和算法。支持时间旅行，而且很快！[![GitHub Workflow Status](https://img.shields.io/github/actions/workflow/status/cozodb/cozo/build.yml?branch=main)](https://github.com/cozodb/cozo/actions/workflows/build.yml)
* [Curvine](https://github.com/CurvineIO/curvine) - Curvine 是用 Rust 编写的高性能并发分布式缓存系统，专为 AI、大数据等领域的低延迟和高吞吐工作负载设计。
* [darkbird](https://github.com/Rustixir/darkbird) [[darkbird](https://crates.io/crates/darkbird)] - 受 Erlang mnesia 启发的高并发、实时、内存存储
* [Databend](https://github.com/databendlabs/databend) - 采用云原生架构的现代实时数据处理与分析 DBMS [![Release](https://github.com/databendlabs/databend/actions/workflows/release.yml/badge.svg)](https://github.com/databendlabs/databend/actions)
* [DB3 Network](https://github.com/dbpunk-labs/db3) - DB3 是一个社区驱动的区块链 Layer2 去中心化数据库网络 [![GitHub Workflow Status (with event)](https://github.com/dbpunk-labs/db3/actions/workflows/ci.yml/badge.svg)](https://github.com/dbpunk-labs/db3/actions/workflows/ci.yml)
* [dsplce-co/supabase-plus](https://github.com/dsplce-co/supabase-plus) [[supabase-plus](https://crates.io/crates/supabase-plus)] - 开箱即用的命令行工具，扩展了官方 Supabase CLI [![GitHub Actions Workflow Status](https://img.shields.io/github/actions/workflow/status/dsplce-co/supabase-plus/publish.yml)
](https://github.com/dsplce-co/supabase-plus/actions/workflows/publish.yml)
* [erikgrinaker/toydb](https://github.com/erikgrinaker/toydb) - 分布式 SQL 数据库，作为学习项目编写。
* [Garage](https://github.com/deuxfleurs-org/garage) [[garage](https://crates.io/crates/garage)] - 兼容 S3 的分布式对象存储服务，专为中小规模自托管设计。[![status-badge](https://woodpecker.deuxfleurs.fr/api/badges/1/status.svg)](https://woodpecker.deuxfleurs.fr/repos/1)
* [GlueSQL](https://github.com/gluesql/gluesql) - 面向 SQL 数据库的 Rust 库，在一个包中包含了解析器（sqlparser-rs）、执行层以及多种持久化和非持久化存储选项。[![crates.io](https://img.shields.io/crates/v/gluesql.svg)](https://crates.io/crates/gluesql)
* [Goldziher/scythe](https://github.com/Goldziher/scythe) - 多语言 SQL 编译器和 linter，可从 SQL 生成类型安全代码，并具备模式感知的 lint。
* [GreptimeDB](https://github.com/grepTimeTeam/greptimedb/) - 开源、云原生的分布式时序数据库，支持 PromQL/SQL/Python。[![CI](https://github.com/greptimeTeam/greptimedb/actions/workflows/develop.yml/badge.svg)](https://github.com/greptimeTeam/greptimedb/actions/workflows/develop.yml)
* [HelixDB](https://github.com/HelixDB/helix-db) - 强大的图-向量数据库，为 RAG 和 AI 提供智能数据存储
* [Hiqlite](https://github.com/sebadob/hiqlite) - 高可用、可嵌入、基于 Raft 的 SQLite + 缓存
* [hydra-db/hydradb](https://github.com/hydra-db/hydradb) - 对象存储原生的分布式图数据库，具备 OpenCypher 查询、GraphBLAS 遍历和兼容 Neo4j 的 Bolt 连接。
* [indradb](https://crates.io/crates/indradb) - 图数据库
* [KiteSQL](https://github.com/KipData/KiteSQL) - 面向 Rust 的、作为函数的 SQL
* [lancedb](https://github.com/lancedb/lancedb) [[vectordb](https://crates.io/crates/vectordb)] - 面向 AI 应用的无服务器、低延迟向量数据库
* [Lucid](https://github.com/lucid-kv/lucid) - 通过 HTTP API 访问的高性能分布式 KV 存储。[![Build Status](https://github.com/lucid-kv/lucid/workflows/Lucid/badge.svg?branch=master)](https://github.com/lucid-kv/lucid/actions?workflow=Lucid)
* [Materialize](https://github.com/MaterializeInc/materialize) - 由 Timely Dataflow 驱动的流式 SQL 数据库 :heavy_dollar_sign:
* [microsoft/pg_durable](https://github.com/microsoft/pg_durable) - PostgreSQL 内的持久化执行。长时间运行、容错的 SQL 函数，具备自动检查点、崩溃恢复和并行执行。零基础设施——作为使用 pgrx 和 Rust 构建的 PostgreSQL 扩展运行。[![License](https://img.shields.io/badge/license-PostgreSQL%20License-3d86c6.svg)](LICENSE.txt)
* [native_db](https://github.com/vincent-herlemont/native_db) [[native_db](https://crates.io/crates/native_db)] - 面向多平台应用（服务器、桌面、移动端）的开箱即用嵌入式数据库。轻松同步 Rust 类型
* [Neon](https://github.com/neondatabase/neon) - 无服务器 Postgres。我们将存储与计算分离，以提供自动扩缩容、分支和无底存储。
* [NoKV-Lab/NoKV](https://github.com/NoKV-Lab/NoKV) - AI 原生的分布式文件系统。[![Rust](https://github.com/NoKV-Lab/NoKV/workflows/Rust/badge.svg)](https://github.com/NoKV-Lab/NoKV/actions/workflows/rust.yml)
* [noria](https://github.com/mit-pdos/noria) [[noria](https://crates.io/crates/noria)] - 面向 Web 应用后端的动态变化、部分有状态的数据流
* [oxigraph/oxigraph](https://github.com/oxigraph/oxigraph) [[oxigraph](https://crates.io/crates/oxigraph)] - 实现 [SPARQL](https://www.w3.org/TR/sparql11-overview/) 标准的图数据库 ![Crates.io Version](https://img.shields.io/crates/v/oxigraph?logo=Rust)
* [ParadeDB](https://github.com/paradedb/paradedb/) - ParadeDB 是构建在 Postgres 上的 Elasticsearch 替代品，专为实时搜索和分析设计。
* [ParityDB](https://github.com/paritytech/parity-db) - 快速可靠的数据库，针对读操作进行了优化
* [pgdogdev/pgdog](https://github.com/pgdogdev/pgdog) - 用于扩展 PostgreSQL 的快速代理，具备连接池、负载均衡和分片。
* [Picodata](https://github.com/picodata/picodata) [[picodata-plugin](https://crates.io/crates/picodata-plugin)] - 分布式 PostgreSQL 兼容数据库，具备 Rust 插件模型；通过商业插件实现 Redis 和 Cassandra 线路兼容。
* [PRQL](https://github.com/PRQL/prql) [[prqlc](https://crates.io/crates/prqlc)] - 用于转换数据的现代语言，可编译为可读的 SQL。[![Tests](https://github.com/PRQL/prql/actions/workflows/tests.yml/badge.svg)](https://github.com/PRQL/prql/actions)
* [PumpkinDB](https://github.com/PumpkinDB/PumpkinDB) - 事件溯源数据库引擎
* [Qdrant](https://github.com/qdrant/qdrant) - 开源向量相似度搜索引擎，支持扩展过滤 [![Tests](https://github.com/qdrant/qdrant/actions/workflows/rust.yml/badge.svg)](https://github.com/qdrant/qdrant/actions)
* [Qrlew/qrlew](https://github.com/Qrlew/qrlew) [[qrlew](https://crates.io/crates/qrlew)] - SQL 到 SQL 的差分隐私层 [![Qrlew](https://github.com/Qrlew/qrlew/actions/workflows/ci.yml/badge.svg)](https://github.com/Qrlew/qrlew/actions) ![Crates.io Version](https://img.shields.io/crates/v/qrlew?logo=Rust)
* [RisingWaveLabs/RisingWave](https://github.com/RisingWaveLabs/risingwave) - 云中的下一代流式数据库 [![CI](https://github.com/risingwavelabs/risingwave/actions/workflows/labeler.yml/badge.svg)](https://github.com/risingwavelabs/risingwave/actions)
* [RustFS](https://github.com/rustfs/rustfs) [[RustFS](https://crates.io/crates/rustfs)] - 🚀 RustFS 是一个开源、兼容 S3 的高性能对象存储系统，支持与 MinIO、Ceph 等其他兼容 S3 的平台进行迁移和共存。 [![status-badge](https://github.com/rustfs/rustfs/actions/workflows/ci.yml/badge.svg)](https://github.com/rustfs/rustfs)
* [ruvnet/ruvector](https://github.com/ruvnet/ruvector) [[ruvector-core](https://crates.io/crates/ruvector-core)] - 自学习向量数据库和认知容器，可在本地运行 LLM 并横向扩展。
* [RyanCodrai/turbovec](https://github.com/RyanCodrai/turbovec) [[turbovec](https://crates.io/crates/turbovec)] - 基于 TurboQuant 构建的向量索引，用 Rust 编写，具备 SIMD 加速搜索和 Python 绑定
* [sabiql](https://github.com/riii111/sabiql) [[sabiql](https://crates.io/crates/sabiql)] - 快速、无驱动、Vim 优先的数据库 TUI，具备安全编辑和 ER 图。[![CI](https://github.com/riii111/sabiql/actions/workflows/ci.yml/badge.svg)](https://github.com/riii111/sabiql/actions/workflows/ci.yml)
* [samyama-ai/samyama-graph](https://github.com/samyama-ai/samyama-graph) - 面向 GraphRAG、知识图谱、向量搜索和图分析的 Rust 原生图-向量数据库。
* [seppo0010/rsedis](https://github.com/seppo0010/rsedis) - Redis 的重新实现。
* [Skytable](https://github.com/skytable/skytable) - 多模型 NoSQL 数据库 ![GitHub Workflow Status](https://img.shields.io/github/workflow/status/skytable/skytable/Tests?style=flat-square)
* [sled](https://crates.io/crates/sled) - （beta）现代嵌入式数据库 [![Build Status](https://github.com/spacejam/sled/actions/workflows/test.yml/badge.svg)](https://github.com/spacejam/sled/actions?workflow=Rust)
* [SQLSync](https://github.com/orbitinghail/sqlsync) - 多人协作、离线优先的 SQLite [![GitHub Workflow Status](https://github.com/orbitinghail/sqlsync/actions/workflows/actions.yaml/badge.svg?branch=main)](https://github.com/orbitinghail/sqlsync/actions?query=branch%3Amain)
* [SurrealDB](https://github.com/surrealdb/surrealdb) - 可扩展的分布式文档-图数据库 [![Build Status](https://img.shields.io/github/workflow/status/surrealdb/surrealdb/Continuous%20integration/main)](https://github.com/surrealdb/surrealdb/actions)
* [tabularis](https://github.com/TabularisDB/tabularis) - 使用 Tauri 和 React 构建的、面向开发者的轻量级数据库管理工具。
* [teaql/teaql-rs](https://github.com/teaql/teaql-rs) [[teaql-core](https://crates.io/crates/teaql-core)] - 模型驱动的运行时，具备类型化查询、受管控的变更和 SQL 提供程序 [![CI](https://github.com/teaql/teaql-rs/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/teaql/teaql-rs/actions/workflows/ci.yml)
* [TerminusDB](https://github.com/terminusdb/terminusdb-store) - 开源图数据库和文档存储 [![Build Status](https://github.com/terminusdb/terminusdb-store/actions/workflows/test.yml/badge.svg)](https://github.com/terminusdb/terminusdb-store/actions)
* [tikv](https://github.com/tikv/tikv) - 用 Rust 编写的分布式 KV 数据库
* [tokio-rs/toasty](https://github.com/tokio-rs/toasty) [[toasty](https://crates.io/crates/toasty)] - 面向 Rust 的舒适、易用 ORM，支持 SQL（SQLite、PostgreSQL、MySQL）和 DynamoDB，具备派生宏、类型安全查询和数据库特定功能暴露。[![Crates.io](https://img.shields.io/crates/v/toasty.svg)](https://crates.io/crates/toasty)
* [Tonbo](https://github.com/tonbo-io/tonbo) - Tonbo 是构建在 Apache Arrow 和 Parquet 之上的嵌入式持久化数据库 [![crates.io](https://img.shields.io/crates/v/tonbo.svg)](https://crates.io/crates/tonbo)
* [TrailBase](https://github.com/trailbaseio/trailbase) - 快速、轻量的单文件 FireBase 替代品，具备类型安全 API、内置 V8 JS/ES6/TS 引擎、认证和管理仪表板 [![GitHub Workflow Status](https://github.com/trailbaseio/trailbase/workflows/test/badge.svg)](https://github.com/trailbaseio/trailbase/actions?workflow=test)
* [tsink](https://github.com/h2337/tsink) - 面向 Rust 的嵌入式时序数据库 [![crates.io](https://img.shields.io/crates/v/tsink.svg)](https://crates.io/crates/tsink)
* [Turso](https://github.com/tursodatabase/turso) - Turso Database 是一个进程内 SQL 数据库，兼容 SQLite。
* [USearch](https://github.com/unum-cloud/usearch) - 面向向量和字符串的相似度搜索引擎 [![crates.io](https://img.shields.io/crates/v/usearch.svg)](https://crates.io/crates/usearch)
* [valentinus](https://github.com/kn0sys/valentinus) - 使用 LMDB 绑定构建的下一代向量数据库 [![Crates.io Version](https://img.shields.io/crates/v/valentinus)](https://crates.io/crates/valentinus)
* [VelesDB](https://github.com/cyberlife-coder/VelesDB) [[velesdb-core](https://crates.io/crates/velesdb-core)] - 可嵌入的本地优先数据库，其三重引擎将向量搜索、属性图和列式存储融合在单一二进制文件中的一种查询语言（VelesQL）之后。内置核心内的代理记忆 SDK——语义/情景/程序——具备跨会话的 `why()` 回忆，可遍历图以揭示仅靠向量搜索会遗漏的关联事实。
* [vorot93/libmdbx-rs](https://github.com/vorot93/libmdbx-rs) [[mdbx-sys](https://crates.io/crates/mdbx-sys)] - MDBX 的绑定，MDBX 是"快速、紧凑、强大、嵌入式、事务型键值数据库，采用宽松许可证"。这是 mozilla/lmdb-rs 的一个分支，带有使其与 libmdbx 配合工作的补丁。
* [whispem/minikv](https://github.com/whispem/minikv) - 分布式、多租户的键值和对象存储，具备 Raft 共识、WAL 持久性、时序 API、向量搜索和兼容 S3 的端点。面向生产，附带 Helm chart、Grafana 仪表板和 Python SDK。[![Build Status](https://img.shields.io/badge/build-passing-brightgreen.svg)](.github/workflows/ci.yml)
* [WooriDB](https://github.com/naomijub/wooridb) - 受 Crux 和 Datomic 启发的通用时间序列数据库。

### 嵌入式

* [embassy-rs/embassy](https://github.com/embassy-rs/embassy) [[embassy](https://crates.io/crates/embassy)] - 面向嵌入式 Rust 的下一代 async/await 框架，提供 STM32、nRF、RP、ESP32 等的 HAL。具备 embassy-time、embassy-net、embassy-usb 和低功耗支持。[![Build Status](https://github.com/embassy-rs/embassy/actions/workflows/ci.yml/badge.svg)](https://github.com/embassy-rs/embassy/actions)
* [infinition/waveshare-watch-rs](https://github.com/infinition/waveshare-watch-rs) - 面向 Waveshare ESP32-S3-Touch-AMOLED-2.06 的 100% Rust `no_std` 智能手表固件。具备 QSPI 80 MHz DMA 显示、Embassy 异步运行时、带常亮显示的事件驱动电源管理。
* [rmk](https://github.com/haobogu/rmk) - 功能丰富的键盘固件。
* [rtic-rs/rtic](https://github.com/rtic-rs/rtic) [[rtic](https://crates.io/crates/rtic)] - 用于构建嵌入式实时系统的实时中断驱动并发框架。
* [uefi-rs](https://github.com/rust-osdev/uefi-rs) - 统一可扩展固件接口（UEFI）的 Rust 封装。该 crate 让你可以轻松开发利用安全、便捷且高性能的 UEFI 功能抽象的 Rust 软件。

### 模拟器

另见[匹配关键字 'emulator' 的 crates](https://crates.io/keywords/emulator)。

* CHIP-8
  * [ColinEberhardt/wasm-rust-chip8](https://github.com/ColinEberhardt/wasm-rust-chip8) - WebAssembly CHIP-8 模拟器。
  * [starrhorne/chip8-rust](https://github.com/starrhorne/chip8-rust) - chip8 模拟器
* Commodore 64
  * [kondrak/rust64](https://github.com/kondrak/rust64) - Commodore 64 模拟器
* Flash Player
  * [Ruffle](https://github.com/ruffle-rs/ruffle) - Ruffle 是一个 Adobe Flash Player 模拟器。Ruffle 通过 WebAssembly 同时面向桌面和 Web。[![CI](https://github.com/ruffle-rs/ruffle/actions/workflows/test_rust.yml/badge.svg)](https://github.com/ruffle-rs/ruffle/actions/workflows/test_rust.yml)[![CI](https://github.com/ruffle-rs/ruffle/actions/workflows/test_web.yml/badge.svg)](https://github.com/ruffle-rs/ruffle/actions/workflows/test_web.yml)
* Gameboy
  * [Gekkio/mooneye-gb](https://github.com/Gekkio/mooneye-gb) - Game Boy 研究项目和模拟器
  * [joamag/boytacean](https://github.com/joamag/boytacean) - 使用 WebAssembly 在 Web 上运行的 GameBoy Color 模拟器。
  * [mohanson/gameboy](https://github.com/mohanson/gameboy) - 功能齐全的跨平台 GameBoy 模拟器。永远的男孩们！
  * [mvdnes/rboy](https://github.com/mvdnes/rboy) - Gameboy 模拟器
* Gameboy Advance
  * [michelhe/rustboyadvance-ng](https://github.com/michelhe/rustboyadvance-ng) - RustboyAdvance-ng 是一个 Gameboy Advance 模拟器，支持桌面、Android 和 [WebAssembly](https://michelhe.github.io/rustboyadvance-ng/)。[![build badge](https://github.com/michelhe/rustboyadvance-ng/actions/workflows/deploy.yml/badge.svg)](https://github.com/michelhe/rustboyadvance-ng/actions?query=workflow%3ADeploy)
* GameMaker
  * [OpenGMK](https://github.com/OpenGMK/OpenGMK) - OpenGMK 是对专有的 GameMaker Classic 引擎的现代重写，提供了运行器的完整源码移植、反编译器、TAS 框架，以及供你自行处理游戏数据的库。
* IBM PC
  * [MartyPC](https://github.com/dbalsom/martypc) - 用 Rust 编写的 IBM PC/XT 模拟器。
* Intel 8080 CPU
  * [mohanson/i8080](https://github.com/mohanson/i8080) - Intel 8080 CPU 模拟器
* iOS
  * [touchHLE](https://github.com/touchHLE/touchHLE) - 面向 iPhone OS 应用的高层模拟器
* iPod
  * [clicky](https://github.com/daniel5151/clicky) - 点击轮 iPod 模拟器（开发中）
* NES
  * [koute/pinky](https://github.com/koute/pinky) - NES 模拟器
  * [pcwalton/sprocketnes](https://github.com/pcwalton/sprocketnes) - NES 模拟器
* Nintendo 64
  * [gopher64](https://github.com/gopher64/gopher64) - 用 Rust 编写的 N64 模拟器
* Nintendo DS
  * [dust](https://github.com/kelpsyberry/dust) - Nintendo DS 模拟器
* PlayStation 4
  * [Obliteration](https://github.com/obhq/obliteration) - 面向 Windows、macOS 和 Linux 的实验性 PS4 模拟器 [![CI](https://github.com/obhq/obliteration/actions/workflows/main.yml/badge.svg)](https://github.com/obhq/obliteration/actions/workflows/main.yml)
* Shockwave Player
  * [DirPlayer](https://github.com/igorlira/dirplayer-rs) - 用 Rust 编写的、兼容 Web 的 Shockwave Player 模拟器
* ZX Spectrum
  * [rustzx/rustzx](https://github.com/rustzx/rustzx) - [![RustZX CI](https://github.com/rustzx/rustzx/actions/workflows/ci.yml/badge.svg)](https://github.com/rustzx/rustzx/actions/workflows/ci.yml)

### 文件管理器

* [broot](https://github.com/Canop/broot) - 查看和导航目录树的新方式（概览目录，即使它很大；找到目录后 `cd` 过去；搜索时永不迷失文件层级；操作你的文件……），延伸阅读 [dystroy.org/broot](https://dystroy.org/broot/) [![Latest Version](https://img.shields.io/crates/v/broot.svg)](https://crates.io/crates/broot)
* [elio-fm/elio](https://github.com/elio-fm/elio) [[elio](https://crates.io/crates/elio)] - 开箱即用的终端文件管理器，具备丰富预览、批量操作和回收站支持。
* [FileSSH](https://github.com/JayanAXHF/FileSSH) - 快速且易用的 TUI，用于管理远程服务器上的文件，包括快速创建 SSH 会话、就地编辑文件等！![crates.io](https://img.shields.io/crates/v/filessh)
* [joshuto](https://github.com/kamiyaa/joshuto) - 类似 ranger 的终端文件管理器
* [moyangzhan/mango-finder](https://github.com/moyangzhan/mango-finder) - 使用自然语言搜索你的文件
* [pikeru](https://github.com/dvhar/pikeru) - 面向 Linux 的文件选择器，具备良好的缩略图和搜索
* [spacedriveapp/spacedrive](https://github.com/spacedriveapp/spacedrive) - 构建在虚拟分布式文件系统之上的文件管理器。
* [xplr](https://github.com/sayanarijit/xplr) - 可定制、极简、快速的 TUI 文件浏览器
* [yazi](https://github.com/sxyazi/yazi) - 基于异步 I/O 的极快终端文件管理器。

### 金融

另见[支付](#支付)类应用。

* [Ashutosh0x/rust-finance](https://github.com/Ashutosh0x/rust-finance) - AI 交易终端，具备多交易所数据摄取、执行、风险模型和 TUI 仪表板。
* [klirr](https://github.com/Sajjon/klirr) [[klirr](https://crates.io/crates/klirr)] - 零维护且智能的 FOSS，为服务和费用生成精美的发票。
* [longbridge/longbridge-terminal](https://github.com/longbridge/longbridge-terminal) - 面向长桥证券的 AI 原生 CLI：实时行情、投资组合、港股/美股/A 股/新加坡股交易。
* [makeev/alphai-tui](https://github.com/makeev/alphai-tui) [[alphai-tui](https://crates.io/crates/alphai-tui)] - 终端股票仪表板，具备免密钥行情和图表、新闻情绪、SEC Form 4 内幕交易和财报解读。![CI](https://github.com/makeev/alphai-tui/actions/workflows/ci.yml/badge.svg?branch=main)
* [nautechsystems/nautilus_trader](https://github.com/nautechsystems/nautilus_trader) - 用 Rust 和 Python 编写的高性能、生产级算法交易平台。
* [tackler](https://github.com/tackler-ng/tackler) [[tackler](https://crates.io/crates/tackler)] - 快速、可靠的记账引擎，具备对纯文本会计的原生 GIT SCM 支持 [![CI Badge](https://github.com/tackler-ng/tackler/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/tackler-ng/tackler/blob/main/.github/workflows/ci.yml)
* [tarkah/tickrs](https://github.com/tarkah/tickrs) - 终端中的实时行情数据
* [wealthfolio/wealthfolio](https://github.com/wealthfolio/wealthfolio) - 美观、私密、本地优先的个人财务追踪器：投资、净资产、支出和模拟。

### 游戏

另见[使用 Piston 制作的游戏](https://github.com/PistonDevelopers/piston/wiki/Games-Made-With-Piston)。

* [buxx/OpenCombat](https://github.com/buxx/OpenCombat) - 实时二战战术游戏
* [chess-tui](https://github.com/thomas-mauran/chess-tui) - 国际象棋 TUI 实现 ♟️
* [citybound](https://github.com/citybound/citybound) - 你应得的城市模拟游戏
* [cristicbz/rust-doom](https://github.com/cristicbz/rust-doom) - Doom 的渲染器，可能会发展成可玩的游戏
* [doukutsu-rs](https://github.com/doukutsu-rs/doukutsu-rs) - Cave Story 引擎的重新实现，带有一些增强。
* [garkimasera/gaia-maker](https://github.com/garkimasera/gaia-maker) - 行星与地形改造模拟游戏
* [garkimasera/rusted-ruins](https://github.com/garkimasera/rusted-ruins) - 可扩展的开放世界像素艺术类 Rogue 游戏
* [GitType](https://github.com/unhappychoice/gittype) - 一款 CLI 代码打字游戏，将你的源代码变成打字挑战
* [gorilla-devs/ferium](https://github.com/gorilla-devs/ferium) - Ferium 是一个快速且功能丰富的 CLI 程序，用于从 Modrinth、CurseForge 和 GitHub Releases 下载和更新 Minecraft 模组，以及从 Modrinth 和 CurseForge 下载整合包 ![ferium build](https://github.com/gorilla-devs/ferium/actions/workflows/build.yml/badge.svg?branch=main)
* [HactarCE/Hyperspeedcube](https://github.com/HactarCE/Hyperspeedcube) - 现代、对新手友好的 3D 和 4D 魔方模拟器，具备可自定义的鼠标和键盘控制以及用于速拧的高级功能
* [lifthrasiir/angolmois-rust](https://github.com/lifthrasiir/angolmois-rust) - 支持 BMS 格式的极简音乐游戏
* [louis-e/arnis](https://github.com/louis-e/arnis) - 使用 OpenStreetMap 和高程数据，从现实世界地理生成 Minecraft Java/Bedrock 世界 [![CI](https://github.com/louis-e/arnis/actions/workflows/ci-build.yml/badge.svg)](https://github.com/louis-e/arnis/actions)
* [maras-archive/rsnake](https://github.com/maras-archive/rsnake) - 贪吃蛇。
* [mcthesw/game-save-manager](https://github.com/mcthesw/game-save-manager) - 用户友好的游戏存档管理工具 [![build badge](https://github.com/mcthesw/game-save-manager/actions/workflows/tauri.yml/badge.svg)](https://github.com/mcthesw/game-save-manager/actions/workflows/tauri.yml)
* [mtkennerly/ludusavi](https://github.com/mtkennerly/ludusavi) - PC 游戏存档备份工具 [![build badge](https://img.shields.io/github/actions/workflow/status/mtkennerly/ludusavi/main.yaml?logo=github)](https://github.com/mtkennerly/ludusavi/actions/workflows/main.yaml) [![crate](https://img.shields.io/crates/v/ludusavi?logo=rust)](https://crates.io/crates/ludusavi)
* [ozkriff/zemeroth](https://github.com/ozkriff/zemeroth) - 小型 2D 回合制六边形策略游戏
* [rhex](https://github.com/dpc/rhex) - 六边形 ASCII 类 Rogue 游戏
* [rsaarelm/magog](https://github.com/rsaarelm/magog) - 类 Rogue 游戏。
* [SoftbearStudios/mk48](https://github.com/SoftbearStudios/mk48) - Mk48.io 是一款在线多人海战游戏
* [Strophox/tetro-tui](https://github.com/Strophox/tetro-tui) [[tetro-tui](https://crates.io/crates/tetro-tui)] - 跨平台终端游戏，俄罗斯方块下落并堆叠。
* [swatteau/sokoban-rs](https://github.com/swatteau/sokoban-rs) - 推箱子实现
* [thetawavegame/thetawave-legacy](https://github.com/thetawavegame/thetawave-legacy) - 一款太空射击游戏，力求成为新游戏开发者做出首次贡献的入门之选。![build badge](https://github.com/thetawavegame/thetawave-legacy/actions/workflows/ci.yml/badge.svg?branch=master)
* [Thinkofname/rust-quake](https://github.com/Thinkofname/rust-quake) - Quake 地图渲染器。
* [topheman/snake-pipe-rust](https://github.com/topheman/snake-pipe-rust) - 终端中基于 stdin/stdout（+tcp 和 unix domain socket）的贪吃蛇游戏 [![crates.io](https://img.shields.io/crates/v/snakepipe.svg)](https://crates.io/crates/snakepipe)
* [ttyperacer/terminal-typeracer](https://gitlab.com/ttyperacer/terminal-typeracer) - 为终端编写的单人打字测试游戏
* [Veloren](https://gitlab.com/veloren/veloren) - 开放世界、开源多人像素体 RPG 游戏，目前处于 alpha 开发阶段 [![build badge](https://gitlab.com/veloren/veloren/badges/master/pipeline.svg)](https://gitlab.com/veloren/veloren/-/pipelines)
* [zipxing/rust_pixel](https://github.com/zipxing/rust_pixel) [[rust_pixel](https://crates.io/crates/rust_pixel)] - 2D 像素艺术游戏引擎和快速原型工具，同时支持文本和图形渲染模式。
* [Zone of Control](https://github.com/ozkriff/zoc) - 回合制六边形策略游戏

### 图形

* [dps/rust-raytracer](https://github.com/dps/rust-raytracer) - 基于 Peter Shirley 的《Ray Tracing in One Weekend》实现的非常简单的光线追踪器。
* [flxzt/rnote](https://github.com/flxzt/rnote) - 素描和手写笔记。
* [ivanceras/svgbob](https://github.com/ivanceras/svgbob) - 将 ASCII 图表转换为 SVG 图形
* [KaminariOS/rustracer](https://github.com/KaminariOS/rustracer) - 基于 Vulkan 光线追踪的 PBR glTF 2.0 渲染器。
* [Limeth/euclider](https://github.com/Limeth/euclider) - 实时 4D CPU 光线追踪器
* [linebender/resvg](https://github.com/linebender/resvg) - SVG 渲染库。
* [monfa-red/lini](https://github.com/monfa-red/lini) [[lini](https://crates.io/crates/lini)] - 适用于各种图形的小型语言——图表、图形、时序图、示意图、技术图纸——从纯文本编译为可主题化的 SVG [![CI](https://github.com/monfa-red/lini/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/monfa-red/lini/actions/workflows/ci.yml)
* [museslabs/phonto](https://github.com/museslabs/phonto) - 用 Rust 编写的、面向 Wayland 和 macOS 的 GPU 加速视频壁纸程序。
* [rodrigorc/papercraft](https://github.com/rodrigorc/papercraft) - 用于展开 3D 模型并用剪刀和胶水制作纸质模型的工具。
* [rustq/vue-skia](https://github.com/rustq/vue-skia) - 基于 Skia 的 2D 图形 Vue 渲染库。它基于 Rust 实现软件光栅化来执行渲染。
* [storytold/artcraft](https://github.com/storytold/artcraft) - 由 AI 驱动的 IDE 和实体计算界面，可像捏黏土一样塑造场景、视频和图像。
* [storytold/cadcraft](https://github.com/storytold/cadcraft) - Autodesk AutoCAD 的开源、净室重新实现，用纯 Rust 构建。
* [turnage/valora](https://crates.io/crates/valora) - 用于生成式美术的库
* [Twinklebear/tray_rust](https://github.com/Twinklebear/tray_rust) - 光线追踪器
* [wahn/rs_pbrt](https://github.com/wahn/rs_pbrt) - 实现 PBRT 书（第 3 版）C++ 代码的对应版本。

### 图像处理

* [Darkly](https://github.com/darkly-art/darkly) - 面向数字艺术家和画家的熵编辑器。
* [Graphite](https://github.com/GraphiteEditor/Graphite) - 基于矢量的图形编辑器。
* [Imager](https://github.com/imager-io/imager) - 自动化图像优化。
* [oxipng](https://github.com/oxipng/oxipng) [[oxipng](https://crates.io/crates/oxipng)] - 用 Rust 编写的多线程 PNG 优化器。[![Build Status](https://github.com/oxipng/oxipng/workflows/oxipng/badge.svg)](https://github.com/oxipng/oxipng/actions?query=branch%3Amaster) [![Version](https://img.shields.io/crates/v/oxipng.svg)](https://crates.io/crates/oxipng)
* [skymanbp/autoshade](https://github.com/skymanbp/autoshade) - AI 辅助的 RAW 照片冲印工具：视觉模型提出编辑方案，确定性引擎将其渲染为兼容 Lightroom 的 XMP sidecar。[![build](https://github.com/skymanbp/autoshade/actions/workflows/build.yml/badge.svg?branch=main)](https://github.com/skymanbp/autoshade/actions/workflows/build.yml)
* [sorairolake/favico](https://github.com/sorairolake/favico) [[favico](https://crates.io/crates/favico)] - 用于创建 favicon 的工具 [![CI](https://github.com/sorairolake/favico/actions/workflows/CI.yaml/badge.svg?branch=develop)](https://github.com/sorairolake/favico/actions/workflows/CI.yaml)
* [Sprite Fusion Pixel Snapper](https://github.com/Hugo-Dz/spritefusion-pixel-snapper) - 一款 CLI 和 WebAssembly 工具，可清理 AI 生成的像素艺术，以获得像素完美的像素艺术精灵（MIT）。
* [storytold/lightcraft](https://github.com/storytold/lightcraft) - Adobe Lightroom 的开源、净室重新实现，用纯 Rust 编写。
* [storytold/vectorcraft](https://github.com/storytold/vectorcraft) - Adobe Illustrator 的开源、净室重新实现，用纯 Rust 构建。
* [visioncortex/vtracer](https://github.com/visioncortex/vtracer) [[vtracer](https://crates.io/crates/vtracer)] - 光栅到矢量图形转换器（jpg/png 转 svg）。

### 工业自动化

* [dora-rs/dora](https://github.com/dora-rs/dora) [[dora-cli](https://crates.io/crates/dora-cli)] - 面向机器人和多 AI 应用构建的快速、简单的数据流框架，提供 Python、Rust 和 C/C++ API [![CI](https://github.com/dora-rs/dora/workflows/CI/badge.svg)](https://github.com/dora-rs/dora/actions)
* [locka99/opcua](https://github.com/locka99/opcua) - 一个 [OPC UA](https://opcfoundation.org/about/opc-technologies/opc-ua/) 库。
* [slowtec/tokio-modbus](https://github.com/slowtec/tokio-modbus) - 一个基于 [tokio](https://tokio.rs) 的 [modbus](https://www.modbus.org) 库。

### 消息队列

* [lonewolf-io/Narwhal](https://github.com/lonewolf-io/narwhal) - 面向边缘应用的可扩展发布/订阅消息服务器。
* [Rmqtt](https://github.com/rmqtt/rmqtt) - MQTT 服务器/MQTT Broker——面向 5G 时代物联网的可扩展分布式 MQTT 消息代理。
* [RobustMQ](https://github.com/robustmq/robustmq) - 下一代云原生融合消息队列。
* [Rocketmq-Rust](https://github.com/mxsm/rocketmq-rust) - 🚀用 Rust 构建的 Apache RocketMQ🦀。更快、更安全，内存占用更低。

### MLOps

* [api7/aisix](https://github.com/api7/aisix) - 面向 LLM 和 AI 代理的开源 AI 网关：在 OpenAI、Anthropic、Gemini、Bedrock、Azure OpenAI 及其他兼容 OpenAI 的端点之前提供一个兼容 OpenAI 的 API 加原生 Anthropic Messages API，具备 MCP 和 A2A 网关、语义路由、防护栏和语义缓存。[![CI](https://github.com/api7/aisix/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/api7/aisix/actions/workflows/ci.yml)
* [cocoindex](https://github.com/cocoindex-io/cocoindex) - 用于为 AI 代理构建新鲜上下文的 ETL 框架，具备增量处理
* [TensorZero](https://github.com/tensorzero/tensorzero) - 面向 LLM 的数据与学习飞轮，统一了推理、可观测性、优化和实验 ![TensorZero Build Status](https://img.shields.io/github/check-runs/tensorzero/tensorzero/main)
* [Uteke](https://github.com/codecoradev/uteke) - 面向 AI 代理的离线优先语义记忆引擎。单一二进制文件、零依赖、MCP 原生。[![CI](https://img.shields.io/github/actions/workflow/status/codecoradev/uteke/ci.yml?branch=develop)](https://github.com/codecoradev/uteke/actions/workflows/ci.yml)

### 可观测性

* [avito-tech/bioyino](https://github.com/avito-tech/bioyino) - 高性能、可扩展的 StatsD 兼容服务器。
* [esrlabs/chipmunk](https://github.com/esrlabs/chipmunk) - 用于分析海量日志文件和流的原生 egui 桌面应用。具备 WebAssembly 插件系统和汽车格式支持。[![Chipmunk CI](https://github.com/esrlabs/chipmunk/actions/workflows/lint_master.yml/badge.svg)](https://github.com/esrlabs/chipmunk/actions/workflows/lint_master.yml)
* [madesroches/micromegas](https://github.com/madesroches/micromegas) [[micromegas](https://crates.io/crates/micromegas)] - 面向日志、指标和追踪的可观测性后端，具备低开销的 Rust 埋点。将遥测数据以 Parquet 格式存储在对象存储中，并使用 SQL 查询。[![Rust](https://github.com/madesroches/micromegas/actions/workflows/rust.yml/badge.svg?branch=main)](https://github.com/madesroches/micromegas/actions/workflows/rust.yml)
* [MegaAntiCheat/client-backend](https://github.com/MegaAntiCheat/client-backend) - [MAC](https://github.com/MegaAntiCheat) 的客户端应用。
* [openobserve](https://github.com/openobserve/openobserve) - 易用 10 倍、存储成本低 140 倍、高性能、PB 级——Elasticsearch/Splunk/Datadog 的替代品。
* [OpenTelemetry](https://crates.io/crates/opentelemetry) - OpenTelemetry 提供一套 API、库、代理和收集器服务，用于从你的应用中捕获分布式追踪和指标。你可以使用 Prometheus、Jaeger 和其他可观测性工具对其进行分析。[![GitHub Actions CI](https://github.com/open-telemetry/opentelemetry-rust/actions/workflows/ci.yml/badge.svg)](https://github.com/open-telemetry/opentelemetry-rust/actions/workflows/ci.yml)
* [parseablehq/parseable](https://github.com/parseablehq/parseable) - AI 原生的统一可观测性平台，用于收集和分析日志、指标、追踪和事件。
* [Quickwit-oss/quickwit](https://github.com/Quickwit-oss/quickwit) - 面向日志管理的云原生、高性价比搜索引擎。[![CI](https://github.com/quickwit-oss/quickwit/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/quickwit-oss/quickwit/actions?query=workflow%3ACI)
* [rustrak/rustrak](https://github.com/rustrak/rustrak) - 与 Sentry SDK 兼容的超轻量错误追踪服务器。
* [Scaphandre](https://github.com/hubblo-org/scaphandre) - 功耗监控代理，用于追踪主机和各项服务的功耗，从而设计更可持续的系统和应用。旨在适配任何监控工具链（已支持 prometheus、warp10、riemann……）。
* [vectordotdev/vector](https://github.com/vectordotdev/vector) - 高性能的日志、指标和事件路由器。

### 操作系统

另见[用 Rust 编写的操作系统对比](https://github.com/flosse/rust-os-comparison)。

* [0x59616e/SteinsOS](https://github.com/0x59616e/SteinsOS) - 面向 armv8-a 架构的操作系统。
* [Andy-Python-Programmer/aero](https://github.com/Andy-Python-Programmer/aero) - 采用宏内核设计的现代类 Unix 操作系统。
* [asterinas/asterinas](https://github.com/asterinas/asterinas) - 安全、快速且通用的操作系统内核，提供兼容 Linux 的 ABI。
* [DragonOS-Community/DragonOS](https://github.com/DragonOS-Community/DragonOS) - 拥有从零自研内核且兼容 Linux 的操作系统。
* [hexagonal-sun/moss-kernel](https://github.com/hexagonal-sun/moss-kernel) - 用 Rust 和 Aarch64 汇编编写的类 Unix、兼容 Linux 的内核。
* [koibtw/highlightos](https://github.com/koibtw/highlightos) - 用 Rust 和汇编编写的 x86_64 操作系统内核。
* [NON-OS/nonos-micro-kernel](https://github.com/NON-OS/nonos-micro-kernel) - 基于能力的常驻内存微内核，其中每个程序都是签名胶囊，必须自证身份后内核才会运行它，驱动程序运行在用户空间。
* [redox-os/redox](https://gitlab.redox-os.org/redox-os/redox) - 类 Unix 的通用微内核操作系统，注重安全、稳定、性能、正确性、简洁和务实，旨在成为 Linux 和 BSD 的完整替代品。
* [thepowersgang/rust_os](https://github.com/thepowersgang/rust_os) - 用 Rust 编写的操作系统内核。非 POSIX
* [theseus-os/Theseus](https://github.com/theseus-os/Theseus) - 从零编写的安全语言、单一地址空间和单一特权级操作系统 - [![build badge](https://img.shields.io/github/workflow/status/theseus-os/Theseus/Documentation?label=docs%20build)](https://www.theseus-os.com/Theseus/book/index.html)
* [tock/tock](https://github.com/tock/tock) - 面向基于 Cortex-M 的微控制器的安全嵌入式操作系统
* [vinc/moros](https://github.com/vinc/moros) - 面向具有 x86-64 架构和 BIOS 的计算机的基于文本的业余操作系统。

### 包管理器

* [helsing-ai/buffrs](https://github.com/helsing-ai/buffrs) [[buffrs](https://crates.io/crates/buffrs)] - 面向 protocol buffers 和 gRPC 架构的现代包管理器。
* [pkgforge/soar](https://github.com/pkgforge/soar) [[soar-cli](https://crates.io/crates/soar-cli)] - 面向便携包、AppImage 和静态二进制文件的发行版无关包管理器 [![CI](https://github.com/pkgforge/soar/actions/workflows/ci.yaml/badge.svg?branch=main)](https://github.com/pkgforge/soar/actions/workflows/ci.yaml)
* [pkgx](https://github.com/pkgxdev/pkgx) - 运行任何东西。一个可组合的包管理器，让整个开源生态系统可供你的脚本使用。
* [rebos](https://crates.io/crates/rebos) - 在任何 Linux 发行版上自动化包管理的声明式方式 [![crate](https://img.shields.io/crates/v/rebos?logo=rust)](https://crates.io/crates/rebos)

### 支付

* [hyperswitch](https://github.com/juspay/hyperswitch) - 开源支付编排器，让你能够连接多个支付处理商并无缝路由支付流量，全部只需一次 API 集成 ![GitHub last commit](https://img.shields.io/github/last-commit/juspay/hyperswitch?style=flat-square)

### 效率工具

* [0xdea/jiggy](https://github.com/0xdea/jiggy) [[jiggy](https://crates.io/crates/jiggy)] - 用 Rust 编写的极简跨平台鼠标摇动器 [![build](https://github.com/0xdea/jiggy/actions/workflows/build.yml/badge.svg)](https://github.com/0xdea/jiggy/actions/workflows/build.yml)
* [aannoo/hcom](https://github.com/aannoo/hcom) - 让 AI 代理跨终端互相发消息、监视和派生（Claude Code、Gemini CLI、Codex、OpenCode）。Rust PTY 封装，具备屏幕追踪、TUI（ratatui）和守护进程客户端二进制；Python 钩子和 API [![CI](https://github.com/aannoo/hcom/actions/workflows/ci.yml/badge.svg)](https://github.com/aannoo/hcom/actions/workflows/ci.yml)
* [agent-of-empires](https://github.com/njbrake/agent-of-empires) - 用于通过 tmux、git worktree 和 Docker 沙箱管理多个 AI 编码代理会话的 TUI/CLI [![CI](https://github.com/njbrake/agent-of-empires/actions/workflows/ci.yml/badge.svg)](https://github.com/njbrake/agent-of-empires/actions)
* [aichat](https://github.com/sigoden/aichat) - 一体化 LLM CLI 工具，具备 Shell 助手、Chat-REPL、RAG、AI 工具和代理，可访问 OpenAI、Claude、Gemini、Ollama、Groq 等。
* [akitaonrails/ai-memory](https://github.com/akitaonrails/ai-memory) - 面向 AI 编码代理的长期记忆：一个由 git 支持的 Markdown wiki，具备自动生命周期捕获、跨代理交接和自托管 MCP 服务器。[![CI](https://github.com/akitaonrails/ai-memory/actions/workflows/ci.yml/badge.svg)](https://github.com/akitaonrails/ai-memory/actions/workflows/ci.yml)
* [akitaonrails/ai-usagebar](https://github.com/akitaonrails/ai-usagebar) [[ai-usagebar](https://crates.io/crates/ai-usagebar)] - Waybar 组件、原生 Omarchy Quattro 面板和标签式 TUI，用于监控 Claude、Codex/ChatGPT、GitHub Copilot、Z.AI（GLM）、OpenRouter 等的 AI 套餐用量。[![CI](https://github.com/akitaonrails/ai-usagebar/actions/workflows/ci.yml/badge.svg)](https://github.com/akitaonrails/ai-usagebar/actions/workflows/ci.yml)
* [AlexsJones/llmfit](https://github.com/AlexsJones/llmfit) [[llmfit](https://crates.io/crates/llmfit)] - 终端工具，根据你系统的 RAM、CPU 和 GPU 为 LLM 模型匹配合适的规模。交互式 TUI，具备硬件检测、多维评分（质量/速度/契合度/上下文）、社区排行榜，并支持 Ollama、llama.cpp、MLX、vLLM 等。[![CI](https://github.com/AlexsJones/llmfit/actions/workflows/ci.yml/badge.svg)](https://github.com/AlexsJones/llmfit/actions/workflows/ci.yml)
* [AlexsJones/llmserve](https://github.com/AlexsJones/llmserve) [[llmserve](https://crates.io/crates/llmserve)] - 交互式 TUI，用于以自动检测的后端（llama-server、KoboldCpp、LocalAI、MLX、Ollama、vLLM、LM Studio）提供本地 LLM 模型服务。具备源码树导航、按后端预设、实时日志和视觉模型支持。[![CI](https://github.com/AlexsJones/llmserve/actions/workflows/ci.yml/badge.svg)](https://github.com/AlexsJones/llmserve/actions/workflows/ci.yml)
* [alphaXiv/OpenResearch](https://github.com/alphaXiv/OpenResearch) - 本地优先的工作区，用于使用 Claude Code、Codex、OpenCode 或 Cursor 运行并行研究代理，具备可复现的实验追踪。[![CI](https://github.com/alphaXiv/OpenResearch/actions/workflows/ci.yml/badge.svg)](https://github.com/alphaXiv/OpenResearch/actions/workflows/ci.yml)
* [antiburn/antiburn](https://github.com/antiburn/antiburn) - 本地桌面应用（Tauri），检查 AI 编码代理会话中常见的 token 消耗原因：会话过深、子代理过强、缓存损坏，以及未使用的 MCP 服务器、技能和工具。支持 Claude Code、Codex、Cursor、Copilot、Pi 等 [![CI](https://github.com/antiburn/antiburn/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/antiburn/antiburn/actions/workflows/ci.yml)
* [ast-grep](https://github.com/ast-grep/ast-grep) - 用于代码结构搜索、lint 和重写的 CLI 工具。
* [Bartib](https://github.com/nikolassv/bartib) [[Bartib](https://crates.io/crates/bartib)] - 简单的命令行计时器 [![Tests](https://github.com/nikolassv/bartib/actions/workflows/test.yml/badge.svg?branch=master)](https://github.com/nikolassv/bartib/actions/workflows/test.yml)
* [Beetroot](https://github.com/mnardit/beetroot-releases) - 面向 Windows 的剪贴板管理器，具备 AI 转换、OCR 和模糊搜索。
* [bitrouter/bitrouter](https://github.com/bitrouter/bitrouter) [[bitrouter](https://crates.io/crates/bitrouter)] - 代理原生的 LLM 路由器，无需改动 harness 即可在每次运行时优化你的代理，让每次模型调用都可靠、可追踪、安全且经济高效。通过单一本地端点路由 OpenAI、Anthropic、Google、OpenRouter、Bedrock、GitHub Copilot 等，具备 MCP 网关、ACP 集成、防护栏、可观测性和多账户故障转移。
* [burakdede/aisw](https://github.com/burakdede/aisw) [[aisw](https://crates.io/crates/aisw)] - 使用命名配置文件、跨工具上下文和按仓库的账户守卫来切换 Claude Code、Codex CLI、Gemini CLI 和 Antigravity CLI 账户 [![CI](https://github.com/burakdede/aisw/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/burakdede/aisw/actions/workflows/ci.yml)
* [CookCLI](https://github.com/cooklang/CookCLI) - 命令行食谱管理器，具备 Web 服务器、购物清单和膳食计划功能。
* [espanso](https://github.com/espanso/espanso) - 跨平台文本扩展器。[![CI](https://github.com/espanso/espanso/actions/workflows/ci.yml/badge.svg?branch=dev&event=push)](https://github.com/espanso/espanso/actions/workflows/ci.yml)
* [eureka](https://crates.io/crates/eureka) - 无需离开终端即可输入和存储你的想法的 CLI 工具
* [farion1231/cc-switch](https://github.com/farion1231/cc-switch) - 面向 Claude Code、Codex 和 Gemini CLI 的一体化 GUI 助手和配置文件管理器。
* [fkiene/llmtrim](https://github.com/fkiene/llmtrim) [[llmtrim](https://crates.io/crates/llmtrim)] - 本地代理，压缩 LLM API 请求以减少输入和输出 token，而不改变答案。通过 HTTPS_PROXY 位于 AI 工具和提供程序之间；适用于 Claude Code、Codex 等。[![CI](https://github.com/fkiene/llmtrim/actions/workflows/ci.yml/badge.svg)](https://github.com/fkiene/llmtrim/actions/workflows/ci.yml)
* [flusterIO/fluster](https://github.com/flusterIO/fluster) - 为 STEM 学生和专业人士打造的一体化笔记应用。[![publish](https://github.com/flusterIO/fluster/actions/workflows/release_rust.yml/badge.svg)](https://github.com/flusterIO/fluster/actions/workflows/release_rust.yml)
* [fulsomenko/kanban](https://github.com/fulsomenko/kanban) [[kanban-tui](https://crates.io/crates/kanban-tui)] - 受 lazygit 启发的基于终端的项目管理工具 [![CI](https://github.com/fulsomenko/kanban/actions/workflows/ci.yml/badge.svg)](https://github.com/fulsomenko/kanban/actions/workflows/ci.yml)
* [Furtherance](https://github.com/unobserved-io/Furtherance) - 使用 GTK4 构建的时间追踪应用
* [futuregene/future-os](https://github.com/futuregene/future-os) - 无处不在的单一 AI 代理：一个 Rust gRPC 后端驱动终端 UI、桌面应用、移动应用、CLI 和 IM 机器人，共享相同的会话、记忆和技能。信任优先、需审批的工具，3800+ 模型，以及支持 24 小时以上运行的循环控制平面。[![build](https://github.com/futuregene/future-os/actions/workflows/ci.yml/badge.svg)](https://github.com/futuregene/future-os/actions/workflows/ci.yml)
* [graves/awful_aj](https://github.com/graves/awful_aj) [[awful_aj](https://crates.io/crates/awful_aj)] - 用于处理兼容 OpenAI 的 API 的 CLI，用于提示工程的 YAML 模板，以及用于持久记忆的内置向量数据库。
* [graykode/abtop](https://github.com/graykode/abtop) [[abtop](https://crates.io/crates/abtop)] - 用于监控 AI 编码代理会话（Claude Code、Codex CLI、OpenCode）的终端 TUI。追踪 token 用量、上下文窗口百分比、速率限制、子进程和孤立端口。具备 tmux 集成、12 种主题（包括色盲友好选项）和跨平台支持。[![CI](https://github.com/graykode/abtop/actions/workflows/ci.yml/badge.svg)](https://github.com/graykode/abtop/actions/workflows/ci.yml)
* [Hmbown/DeepSeek-TUI](https://github.com/Hmbown/DeepSeek-TUI) [[deepseek-tui-cli](https://crates.io/crates/deepseek-tui-cli)] - 面向 DeepSeek V4 的终端编码代理，具备流式推理块、本地工作区编辑、自动模型选择、MCP 支持和基于 ratatui 的 TUI。[![CI](https://github.com/Hmbown/DeepSeek-TUI/actions/workflows/ci.yml/badge.svg)](https://github.com/Hmbown/DeepSeek-TUI/actions/workflows/ci.yml)
* [iBz-04/gloamy](https://github.com/iBz-04/gloamy) [[gloamy](https://crates.io/crates/gloamy)] - Rust 优先的自主代理运行时，面向 CLI、渠道、网关和硬件工作流。
* [illacloud/illa](https://github.com/illacloud/illa) - 低代码内部工具构建器。
* [iwe-org/iwe](https://github.com/iwe-org/iwe) [[iwe](https://crates.io/crates/iwe)] - 基于 Markdown 的知识管理工具，具备 LSP 服务器和 CLI [![Build Status](https://github.com/iwe-org/iwe/actions/workflows/rust.yml/badge.svg)](https://github.com/iwe-org/iwe/actions/workflows/rust.yml)
* [jchultarsky/mirador](https://github.com/jchultarsky/mirador) [[mirador](https://crates.io/crates/mirador)] - 面向终端的从容个人仪表板：时钟、日历和日程、天气、任务、笔记、行情和实时系统指标，以可配置的网格呈现 [![CI](https://github.com/jchultarsky/mirador/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/jchultarsky/mirador/actions/workflows/ci.yml)
* [kruseio/hygg](https://github.com/kruseio/hygg) [[hygg](https://crates.io/crates/hygg)] - 📚 简化你的阅读方式。极简的类 Vim TUI 文档阅读器。
* [leepokai/Codync](https://github.com/leepokai/Codync) - 一个主机，将 Claude Code、Codex、Gemini 和其他 ACP 编码代理作为持久化机器人运行，你可以从 iPhone、桌面应用或终端 UI（ratatui）向它们发消息 [![build badge](https://github.com/leepokai/Codync/actions/workflows/host.yml/badge.svg?branch=main)](https://github.com/leepokai/Codync/actions/workflows/host.yml)
* [LLDAP](https://github.com/lldap/lldap) - 用于身份验证的简化 LDAP 接口。
* [lockbook/lockbook](https://github.com/lockbook/lockbook) [[lb-rs](https://crates.io/crates/lb-rs)] - 协作式端到端加密笔记、文档和绘图，具备构建在共享 Rust 核心之上的原生跨平台客户端和可自托管服务器。[![Integration](https://github.com/lockbook/lockbook/actions/workflows/integration.yml/badge.svg?branch=master)](https://github.com/lockbook/lockbook/actions/workflows/integration.yml)
* [mag123c/toktrack](https://github.com/mag123c/toktrack) - 快速 TUI/CLI，追踪 AI 编码 CLI（Claude Code、Codex、Gemini CLI 等）的 token 用量和成本，具备可抵御 CLI 数据删除的持久缓存。[![CI](https://github.com/mag123c/toktrack/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/mag123c/toktrack/actions/workflows/ci.yml)
* [max-sixty/worktrunk](https://github.com/max-sixty/worktrunk) [[worktrunk](https://crates.io/crates/worktrunk)] - 为并行运行 AI 代理而设计的 git worktree 管理 CLI，具备钩子、LLM 提交信息和合并工作流 [![CI](https://img.shields.io/github/actions/workflow/status/max-sixty/worktrunk/ci.yaml?branch=main&logo=github)](https://github.com/max-sixty/worktrunk/actions?query=branch%3Amain+workflow%3Aci)
* [morganlinton/Albatross](https://github.com/morganlinton/Albatross) [[albatross-cli](https://crates.io/crates/albatross-cli)] - 终端优先的 AI 编码代理，在本地（Ollama、LM Studio、MLX、llama.cpp）和云后端之间进行透明的多模型路由，具备逐轮成本显示、真正的撤销和可审计的路由凭证。[![CI](https://github.com/morganlinton/Albatross/actions/workflows/ci.yml/badge.svg)](https://github.com/morganlinton/Albatross/actions/workflows/ci.yml)
* [murray17/rovai-ai](https://github.com/murray17/rovai-ai) - 面向编码代理团队的桌面和 Web 工作区，具备用于任务协调、执行追踪和协作记忆的 Rust 核心。[![Full check](https://github.com/murray17/rovai-ai/actions/workflows/full-check.yml/badge.svg?branch=main)](https://github.com/murray17/rovai-ai/actions/workflows/full-check.yml)
* [muvon/octomind](https://github.com/muvon/octomind) - 开源 AI 代理运行时 CLI，具备 48+ 专家代理、支持动态服务器注册的 MCP 主机、多提供程序支持（13+ LLM），以及针对 4 小时以上会话的自适应上下文压缩。
* [ogulcancelik/herdr](https://github.com/ogulcancelik/herdr) - 为 AI 编码代理设计的终端复用器。在一个终端中运行多个代理，具备真实终端视图、代理状态检测（阻塞/工作中/完成）、工作区、标签页和持久会话。单一 Rust 二进制文件，支持分离/重新附加。
* [pier-cli/pier](https://github.com/pier-cli/pier) - 用于管理（添加、搜索元数据等）你所有单行命令、脚本、工具和 CLI 的中央仓库
* [raine/aven](https://github.com/raine/aven) [[aven](https://crates.io/crates/aven)] - 面向高级用户和代理的本地优先任务管理器，具备键盘驱动的 TUI 和代理优先的 CLI [![CI](https://github.com/raine/aven/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/raine/aven/actions/workflows/ci.yml)
* [raine/workmux](https://github.com/raine/workmux) [[workmux](https://crates.io/crates/workmux)] - git worktree + tmux 窗口，实现零摩擦的并行开发 [![CI](https://github.com/raine/workmux/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/raine/workmux/actions/workflows/ci.yml)
* [rtk-ai/rtk](https://github.com/rtk-ai/rtk) - 高性能 CLI 代理，为 AI 编码助手减少 60-90% 的 LLM token 消耗。为 Claude Code、Copilot、Cursor、Gemini CLI、Codex 等过滤和压缩命令输出。[![CI](https://github.com/rtk-ai/rtk/workflows/Security%20Check/badge.svg)](https://github.com/rtk-ai/rtk/actions)
* [screenpipe](https://github.com/screenpipe/screenpipe) - 全天候本地 AI 屏幕和麦克风录制。构建拥有完整上下文的 AI 应用。可与 Ollama 配合使用。
* [ShadoySV/work-break](https://github.com/ShadoySV/work-break) [[work-break](https://crates.io/crates/work-break)] - 工作和休息时间平衡器，考虑你当前和当天的疲劳度 [![Build](https://github.com/ShadoySV/work-break/actions/workflows/release.yml/badge.svg)](https://github.com/ShadoySV/work-break/actions/workflows/release.yml)
* [socai-io/socai](https://github.com/socai-io/socai) - 一个社交研究代理，复用已登录的 Chrome 在 Instagram、TikTok、LinkedIn、X、小红书和抖音上搜索并阅读帖子、评论、个人资料和受支持的媒体。
* [tambourine-voice](https://github.com/kstonekuan/tambourine-voice) - 适用于任何应用的个性化 AI 语音界面——可自定义的听写，让你选择自己的模型和提示，使用 Rust 构建。
* [tassiovirginio/try-rs](https://github.com/tassiovirginio/try-rs) [[try-rs](https://crates.io/crates/try-rs)] - 工作区管理器 CLI，具备用于组织和导航临时实验的 TUI。
* [thClaws/thClaws](https://github.com/thClaws/thClaws) - 原生 Rust AI 代理工作区，具备多提供程序 LLM 支持、技能系统、MCP 服务器、知识库和代理编排。提供桌面 GUI、CLI REPL 和非交互模式。[![License](https://img.shields.io/badge/license-MIT%20OR%20Apache--2.0-blue.svg)](https://github.com/thClaws/thClaws)
* [ThinkWatchProject/ThinkWatch-Lite](https://github.com/ThinkWatchProject/ThinkWatch-Lite) - 桌面应用（Tauri），为 Claude Code、Codex 和其他 AI 编码客户端运行本地网关：无需更改客户端配置即可切换上游，在 Anthropic、OpenAI 和 Gemini API 之间转换，记录每个请求的成本，并在请求离开前脱敏 API 密钥。[![CI](https://github.com/ThinkWatchProject/ThinkWatch-Lite/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/ThinkWatchProject/ThinkWatch-Lite/actions/workflows/ci.yml)
* [tinyhumansai/opencompany](https://github.com/tinyhumansai/opencompany) - 开源运行时，将 AI 代理组装成一家运转中的公司：共享工作板、代理间交接、人工审批、定时和 DAG 工作流。可在你带来的任何模型上运行，使用 Docker 自托管。[![License](https://img.shields.io/badge/license-GPL--3.0-blue.svg)](https://github.com/tinyhumansai/opencompany)
* [tinyhumansai/openhuman](https://github.com/tinyhumansai/openhuman) - 开源代理式助手，具备桌面 UI、118+ OAuth 集成、本地优先记忆树、兼容 Obsidian 的 wiki、原生语音和 TokenJuice 压缩。使用 Tauri 和 Rust 构建，面向注重隐私的个人 AI。
* [tover0314-w/opentypeless](https://github.com/tover0314-w/opentypeless) - 使用 Tauri 和 Rust 构建的跨平台 AI 语音输入应用。
* [Tuxedo](https://github.com/webstonehq/tuxedo) - 面向 todo.txt 的快速、键盘驱动的终端 UI。
* [tw93/Pake](https://github.com/tw93/Pake) - 使用 Rust 和 Tauri，一条命令即可将任何网页变成桌面应用。轻量、快速，支持 macOS、Windows 和 Linux。
* [VisiGrid/VisiGrid](https://github.com/VisiGrid/VisiGrid) - 像代码编辑器一样构建的原生电子表格，采用 GPUI、WASM 和无头 CLI 引擎。
* [xingkongliang/skills-manager](https://github.com/xingkongliang/skills-manager) - 轻量级桌面应用，使用 Tauri 2、Rust 后端和 Git 备份支持，在 15+ 编码工具（Cursor、Claude Code、Codex、Copilot 等）之间管理、同步和组织 AI 代理技能。
* [Xoshbin/asyar](https://github.com/Xoshbin/asyar) - Raycast 的强大。Alfred 的速度。隐私源于设计。[![CodeQL](https://github.com/Xoshbin/asyar/actions/workflows/github-code-scanning/codeql/badge.svg?branch=main)](https://github.com/Xoshbin/asyar/actions/workflows/github-code-scanning/codeql)
* [y0sif/whisrs](https://github.com/y0sif/whisrs) [[whisrs](https://crates.io/crates/whisrs)] - 面向 Linux 桌面的语音听写：说话即可在 Wayland 或 X11 上任何应用的光标处出现文字，另有朗读和语音驱动的 LLM 命令。可运行在云后端，或通过 whisper.cpp 完全离线运行 [![CI](https://github.com/y0sif/whisrs/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/y0sif/whisrs/actions/workflows/ci.yml)
* [yashs662/rust_kanban](https://github.com/yashs662/rust_kanban) [[rust-kanban](https://crates.io/crates/rust-kanban)] [![Build](https://github.com/yashs662/rust_kanban/actions/workflows/build.yml/badge.svg)](https://github.com/yashs662/rust_kanban/releases) - 面向终端的看板应用
* [yicheng47/runner](https://github.com/yicheng47/runner) - 面向 macOS 和 Windows 的原生 GPUI 桌面应用，Claude Code、Codex、Copilot CLI 和 pi 等 CLI 编码代理像团队一样共同完成一项任务，各自在真实终端中保留自己的 TUI。[![CI](https://github.com/yicheng47/runner/actions/workflows/ci.yaml/badge.svg?branch=main)](https://github.com/yicheng47/runner/actions/workflows/ci.yaml)
* [Zackriya-Solutions/meetily](https://github.com/Zackriya-Solutions/meetily) - 隐私优先的 AI 会议助手，完全在你的本地机器上捕获、转录和总结会议。具备使用 Whisper/Parakeet 模型的实时转录、AI 驱动的摘要，并支持多个 AI 提供程序（Ollama、Claude、Groq、OpenAI）

### 路由协议

* [Holo](https://github.com/holo-routing/holo) - Holo 是一套路由协议，旨在支持大规模和自动化驱动的网络
* [RustyBGP](https://github.com/osrg/rustybgp) - BGP

### 安全工具

* [0xdea/augur](https://github.com/0xdea/augur) [[augur](https://crates.io/crates/augur)] - 逆向工程助手，从二进制文件中提取字符串和相关伪代码 [![build](https://github.com/0xdea/augur/actions/workflows/build.yml/badge.svg)](https://github.com/0xdea/augur/actions/workflows/build.yml)
* [0xdea/haruspex](https://github.com/0xdea/haruspex) [[haruspex](https://crates.io/crates/haruspex)] - 漏洞研究助手，从 IDA Hex-Rays 反编译器中提取伪代码 [![build](https://github.com/0xdea/haruspex/actions/workflows/build.yml/badge.svg)](https://github.com/0xdea/haruspex/actions/workflows/build.yml)
* [0xdea/oneiromancer](https://github.com/0xdea/oneiromancer) [[oneiromancer](https://crates.io/crates/oneiromancer)] - 逆向工程助手，使用本地运行的 LLM 辅助源代码分析 [![build](https://github.com/0xdea/oneiromancer/actions/workflows/build.yml/badge.svg)](https://github.com/0xdea/oneiromancer/actions/workflows/build.yml)
* [0xdea/rhabdomancer](https://github.com/0xdea/rhabdomancer) [[rhabdomancer](https://crates.io/crates/rhabdomancer)] - 漏洞研究助手，定位二进制文件中所有对潜在不安全 API 函数的调用 [![build](https://github.com/0xdea/rhabdomancer/actions/workflows/build.yml/badge.svg)](https://github.com/0xdea/rhabdomancer/actions/workflows/build.yml)
* [AdGuardian-Term](https://github.com/Lissy93/AdGuardian-Term) [[adguardian](https://crates.io/crates/adguardian)] - 面向你的 AdGuard Home 实例的基于终端的实时流量监控和统计
* [AFLplusplus/LibAFL](https://github.com/AFLplusplus/LibAFL) - 高级模糊测试库——用 Rust 拼装你的模糊测试器！可跨核心和机器扩展。适用于 Windows、Android、MacOS、Linux、no_std 等。[![build and test](https://github.com/AFLplusplus/LibAFL/actions/workflows/build_and_test.yml/badge.svg)](https://github.com/AFLplusplus/LibAFL/actions/workflows/build_and_test.yml)
* [arp-scan-rs](https://github.com/kongbytes/arp-scan-rs) - 极简 ARP 扫描工具，用于快速局域网扫描
* [biandratti/huginn-net](https://github.com/biandratti/huginn-net) - 多协议被动网络指纹识别，结合 p0f TCP 和 JA4 TLS 分析，用于操作系统和应用检测 [![CI](https://github.com/biandratti/huginn-net/actions/workflows/ci.yml/badge.svg)](https://github.com/biandratti/huginn-net/actions/workflows/ci.yml)
* [bountyyfi/lonkero](https://github.com/bountyyfi/lonkero) - 企业级 Web 漏洞扫描器，具备 60+ 攻击模块，用于渗透测试和安全评估
* [cargo-audit](https://crates.io/crates/cargo-audit) - 审计 Cargo.lock 中具有安全漏洞的 crate
* [cargo-auditable](https://crates.io/crates/cargo-auditable) - 让生产环境的 Rust 二进制文件可审计
* [cargo-crev](https://crates.io/crates/cargo-crev) - 面向 cargo 包管理器的密码学可验证代码审查系统。
* [cargo-deny](https://crates.io/crates/cargo-deny) - 帮助你管理大型依赖图的 Cargo 插件
* [Cherrybomb](https://github.com/blst-security/cherrybomb) - 用 CLI 工具终结半成品的 API 规范，通过验证你的 API 规范帮助你避免未定义的用户行为。
* [cotp](https://github.com/replydev/cotp) - 可信、加密的命令行 TOTP/HOTP 身份验证器应用，具备导入功能。
* [domcyrus/rustnet](https://github.com/domcyrus/rustnet) - 跨平台网络监控 TUI，通过 eBPF/PKTAP 进行进程识别，并具备深度包检测 [![build badge](https://img.shields.io/github/actions/workflow/status/domcyrus/rustnet/rust.yml?logo=github)](https://github.com/domcyrus/rustnet/actions/workflows/rust.yml) [![crate](https://img.shields.io/crates/v/rustnet-monitor?logo=rust)](https://crates.io/crates/rustnet-monitor)
* [EFForg/rayhunter](https://github.com/EFForg/rayhunter) - 设计用于在移动热点硬件上运行的 IMSI 捕获器检测工具，帮助用户识别潜在的蜂窝监控（Stingray/伪基站模拟器） [![Tests](https://github.com/EFForg/rayhunter/actions/workflows/main.yml/badge.svg)](https://github.com/EFForg/rayhunter/actions/workflows/main.yml)
* [entropic-security/xgadget](https://github.com/entropic-security/xgadget) [[xgadget](https://crates.io/crates/xgadget)] - 快速、并行、跨变体的 ROP/JOP gadget 搜索 [![GitHub Actions](https://github.com/entropic-security/xgadget/workflows/test/badge.svg)](https://github.com/entropic-security/xgadget/actions)
* [epi052/feroxbuster](https://github.com/epi052/feroxbuster) - 简单、快速、递归的内容发现工具。
* [getprovenant/provenant](https://github.com/getprovenant/provenant) [[provenant-cli](https://crates.io/crates/provenant-cli)] - 快速的许可证、版权、包和 SBOM 扫描器，输出 CycloneDX 和 SPDX 以及完整、封闭的依赖清单；静态且离线。[![CI](https://github.com/getprovenant/provenant/actions/workflows/check.yml/badge.svg?branch=main)](https://github.com/getprovenant/provenant/actions/workflows/check.yml)
* [Inspektor](https://github.com/inspektor-dev/inspektor) - 具备数据库协议感知的代理，用于强制执行访问策略 👮
* [kpcyrd/authoscope](https://github.com/kpcyrd/authoscope) - 可脚本化的网络身份验证破解器
* [kpcyrd/rshijack](https://github.com/kpcyrd/rshijack) - TCP 连接劫持器；shijack 的重写
* [kpcyrd/sn0int](https://github.com/kpcyrd/sn0int) - 半自动 OSINT 框架和包管理器
* [kpcyrd/sniffglue](https://github.com/kpcyrd/sniffglue) - 安全的多线程数据包嗅探器
* [LeChatP/RootAsRole](https://github.com/LeChatP/RootAsRole) - sudo(-rs)/su 的更好替代品 • ⚡ 极快 • 🛡️ 内存安全 • 🔐 面向安全 ![Build](https://img.shields.io/github/actions/workflow/status/LeChatP/RootAsRole/build.yml?logo=githubactions&label=Build&logoColor=white) ![Coverage](https://img.shields.io/codecov/c/github/lechatp/rootasrole?color=green&link=https%3A%2F%2Fapp.codecov.io%2Fgh%2FLeChatP%2FRootAsRole&label=Test%20Coverage) ![crates.io](https://img.shields.io/crates/v/rootasrole.svg?label=Version&color=e37602&logo=rust)
* [microsoft/mxc](https://github.com/microsoft/mxc) - 沙箱化代码执行系统，用于在 Windows、Linux 和 macOS 上运行不受信任的代码（模型输出、插件、工具）。具备多个隔离后端（ProcessContainer、Windows Sandbox、LXC、Bubblewrap、Seatbelt、MicroVM、Hyperlight、IsolationSession、WSLC），采用基于 JSON 的策略驱动沙箱和 TypeScript SDK。[![CI](https://github.com/microsoft/mxc/actions/workflows/ci.yml/badge.svg)](https://github.com/microsoft/mxc/actions)
* [mongodb/kingfisher](https://github.com/mongodb/kingfisher) - 极快的工具，用于在文件、Git 仓库、S3、Jira 和 Confluence 中进行机密检测和实时验证
* [mullvad/mullvadvpn-app](https://github.com/mullvad/mullvadvpn-app) - 面向 Mullvad VPN 服务的跨平台 VPN 客户端应用，支持 WireGuard、抗量子隧道和注重隐私的功能。[![CI](https://github.com/mullvad/mullvadvpn-app/actions/workflows/verify.yml/badge.svg)](https://github.com/mullvad/mullvadvpn-app/actions)
* [observer_ward](https://github.com/emo-crab/observer_ward) - Web 应用和服务指纹识别工具
* [Raspirus](https://github.com/Raspirus/Raspirus) - 对用户和资源友好的基于规则的恶意软件扫描器 [![status](https://github.com/Raspirus/Raspirus/actions/workflows/testproject.yml/badge.svg)](https://github.com/Raspirus/Raspirus/actions/workflows/testproject.yml)
* [reaction](https://framagit.org/ppom/reaction) - 扫描日志并采取行动：fail2ban 的替代品
* [ripasso](https://github.com/cortex/ripasso/) - 密码管理器，文件系统兼容 pass
* [rustscan](https://github.com/bee-san/RustScan) - 使用这款端口扫描工具让 Nmap 更快 [![build badge](https://github.com/bee-san/RustScan/actions/workflows/test.yml/badge.svg)](https://github.com/bee-san/RustScan/actions)
* [santhreal/keyhog](https://github.com/santhreal/keyhog) [[keyhog](https://crates.io/crates/keyhog)] - 在源码树、git 历史、归档和远程源中检测泄漏的凭据和 API 密钥，并对发现的机密进行实时验证 [![CI](https://github.com/santhreal/keyhog/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/santhreal/keyhog/actions/workflows/ci.yml)
* [secluso](https://github.com/secluso/core) - 使用端到端加密的私密树莓派家庭安全摄像头
* [sherlock](https://github.com/jonaylor89/sherlock-rs) [[sherlock](https://crates.io/crates/sherlock)] - 跨社交网络通过用户名追查社交媒体账户 [![status](https://github.com/jonaylor89/sherlock-rs/actions/workflows/rust.yml/badge.svg)](https://github.com/jonaylor89/sherlock-rs/actions/workflows/rust.yml)
* [ssh-vault](https://github.com/ssh-vault/ssh-vault) - 使用 ssh 密钥进行加密和解密来管理机密的简单工具。
* [timescale/rsigma](https://github.com/timescale/rsigma) [[rsigma](https://crates.io/crates/rsigma)] - 面向 Sigma 检测标准的完整检测工程工具包，具备解析器、评估引擎、规则转换、流式运行时、linter、CLI、MCP 和 LSP [![CI](https://github.com/timescale/rsigma/actions/workflows/ci.yml/badge.svg)](https://github.com/timescale/rsigma/actions/workflows/ci.yml)

### 社交网络

* Discord
  * [concord](https://github.com/chojs23/concord) - 功能丰富的 Discord TUI 客户端。
  * [Dorion](https://github.com/SpikeHD/Dorion) - 小巧的替代 Discord 客户端，占用更小、启动更敏捷，具备主题、插件等！![build](https://img.shields.io/github/actions/workflow/status/SpikeHD/Dorion/build.yml)
* Mastodon
  * [Rustodon](https://github.com/rustodon/rustodon) - 兼容 Mastodon、支持 ActivityPub 的服务器。
* Matrix
  * [poljar/weechat-matrix-rs](https://github.com/poljar/weechat-matrix-rs) - 用 Rust 重写的 python weechat-matrix 脚本。
* Telegram
  * [tgt](https://github.com/FedericoBruzzone/tgt) - 跨平台的 Telegram TUI [![ci-linux](https://github.com/FedericoBruzzone/tgt/actions/workflows/ci-linux.yml/badge.svg)](https://github.com/FedericoBruzzone/tgt/actions/workflows/ci-linux.yml) [![ci-macos](https://github.com/FedericoBruzzone/tgt/actions/workflows/ci-macos.yml/badge.svg)](https://github.com/FedericoBruzzone/tgt/actions/workflows/ci-macos.yml) [![ci-windows](https://github.com/FedericoBruzzone/tgt/actions/workflows/ci-windows.yml/badge.svg)](https://github.com/FedericoBruzzone/tgt/actions/workflows/ci-windows.yml)
* WhatsApp
  * [imtaqin/waxum](https://github.com/imtaqin/waxum) - 自托管 WhatsApp 网关，从单一静态二进制文件暴露 REST API、webhook、多会话支持和语音通话。[![CI](https://github.com/imtaqin/waxum/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/imtaqin/waxum/actions/workflows/ci.yml)

### 系统工具

* [adileo/squirreldisk](https://github.com/adileo/squirreldisk) - 面向 macOS、Windows 和 Linux 的磁盘使用分析 GUI（egui），具备旭日图和矩形树图视图，还可通过 rclone 扫描 SSH 服务器和云存储 [![CI](https://github.com/adileo/squirreldisk/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/adileo/squirreldisk/actions/workflows/ci.yml)
* [ajeetdsouza/zoxide](https://github.com/ajeetdsouza/zoxide/) - `cd` 的快速替代品，会学习你的习惯 [![release](https://github.com/ajeetdsouza/zoxide/actions/workflows/release.yml/badge.svg)](https://github.com/ajeetdsouza/zoxide/actions)
* [anylinuxfs](https://github.com/nohajc/anylinuxfs) - 用于在 Mac 上挂载任何 Linux 支持的文件系统的 CLI 工具——使用 microVM 配合 NFS
* [anylinuxfs-gui](https://github.com/fenio/anylinuxfs-gui) - anylinuxfs 的 GUI 应用
* [ataraxy-labs/sem](https://github.com/ataraxy-labs/sem) - 实体级语义版本控制 CLI。通过 tree-sitter 在 32 种语言中进行函数/类级别的差异、追溯、图谱和影响分析。[![Release](https://github.com/ataraxy-labs/sem/actions/workflows/release.yml/badge.svg)](https://github.com/ataraxy-labs/sem/actions/workflows/release.yml)
* [ataraxy-labs/weave](https://github.com/ataraxy-labs/weave) - Git 的实体级合并驱动。通过 tree-sitter 理解代码结构来解决合并冲突。通过 .gitattributes 作为自定义合并驱动接入 git。[![Release](https://github.com/ataraxy-labs/weave/actions/workflows/release.yml/badge.svg)](https://github.com/ataraxy-labs/weave/actions/workflows/release.yml)
* [atuin](https://github.com/atuinsh/atuin) [[atuin](https://crates.io/crates/atuin)] - Atuin 用 SQLite 数据库替换你现有的 shell 历史，并记录命令的额外上下文。此外，它还通过 Atuin 服务器提供可选的、完全加密的跨机器历史同步。
* [bandwhich](https://github.com/imsnif/bandwhich) - 终端带宽利用率工具
* [bolivian-peru/os-moda](https://github.com/bolivian-peru/os-moda) - NixOS 发行版，其中 AI 代理通过 91 个类型化 MCP 工具拥有 root 权限。9 个 Rust 守护进程（系统桥接、带自动回滚的原子 SafeSwitch 部署、哈希链式审计账本、AES-256-GCM 加密钱包、Noise_XX + ML-KEM-768 P2P 网状网络、本地 STT/TTS、MCP 服务器生命周期、系统学习、域名允许列表出口代理）通过 Unix socket 通信。
* [bottom](https://github.com/ClementTsang/bottom) - 又一个跨平台图形化进程/系统监控器。[![GitHub Workflow Status (branch)](https://img.shields.io/github/workflow/status/ClementTsang/bottom/ci/master)](https://github.com/ClementTsang/bottom/actions?query=branch%3Amaster)
* [brocode/fblog](https://github.com/brocode/fblog) - 小型命令行 JSON 日志查看器
* [brush-shell](https://github.com/reubeno/brush) - 兼容 bash/POSIX 的 shell [![CICD](https://github.com/reubeno/brush/actions/workflows/ci.yaml/badge.svg)](https://github.com/reubeno/brush/actions/workflows/ci.yaml)[![Crate](https://img.shields.io/crates/v/brush-shell.svg?logo=rust)](https://crates.io/crates/brush-shell)
* [bustd](https://github.com/vrmiguel/bustd) - 轻量级进程终止守护进程，用于处理 Linux 上的内存不足场景。[![GitHub Workflow Status (branch)](https://img.shields.io/github/workflow/status/vrmiguel/bustd/build-and-test)](https://github.com/vrmiguel/bustd/actions?query=branch%3Amaster)
* [buster/rrun](https://github.com/buster/rrun) - 面向 Linux 的命令启动器，类似 gmrun
* [cantino/mcfly](https://github.com/cantino/mcfly) - 飞速浏览你的 shell 历史。天呐！
* [ChurchTao/clipboard-rs](https://github.com/ChurchTao/clipboard-rs) [[clipboard-rs](https://crates.io/crates/clipboard-rs)] - 用 Rust 编写的跨平台库，用于获取、设置和监控系统级剪贴板内容的变化。
* [Cocoa-Way](https://github.com/J-x-Z/cocoa-way) [[homebrew](https://github.com/J-x-Z/homebrew-tap)] - 原生 macOS Wayland 合成器，无需 VM 开销即可运行 Linux GUI 应用。使用 Smithay 构建。[![build badge](https://github.com/J-x-Z/cocoa-way/actions/workflows/release.yml/badge.svg)](https://github.com/J-x-Z/cocoa-way/actions)
* [crabz](https://github.com/sstadick/crabz) - 多线程压缩和解压 CLI 工具 [![Build Status](https://github.com/sstadick/crabz/workflows/Check/badge.svg)](https://github.com/sstadick/crabz/actions?query=workflow%3ACheck)
* [cristianoliveira/funzzy](https://github.com/cristianoliveira/funzzy) - 受 [entr](http://eradman.com/entrproject/) 启发的可配置文件系统监视器
* [dalance/procs](https://github.com/dalance/procs) - 'ps' 的现代替代品 [![Regression](https://github.com/dalance/procs/actions/workflows/regression.yml/badge.svg)](https://github.com/dalance/procs/actions/workflows/regression.yml)
* [ddh](https://github.com/darakian/ddh) - 快速重复文件查找器
* [deshaw/procfd](https://github.com/deshaw/procfd) [[procfd](https://crates.io/crates/procfd)] - Linux lsof 替代品，用于列出进程的打开文件描述符
* [diskonaut](https://github.com/imsnif/diskonaut) - 终端可视化磁盘空间导航器
* [dust](https://github.com/bootandy/dust) - 更直观的 du 版本
* [erickochen/purple](https://github.com/erickochen/purple) [[purple-ssh](https://crates.io/crates/purple-ssh)] - 由 Ratatui 驱动的 SSH 客户端，具备云同步、容器管理、文件传输、隧道、片段和密码管理 [![CI](https://github.com/erickochen/purple/actions/workflows/ci.yml/badge.svg)](https://github.com/erickochen/purple/actions/workflows/ci.yml)
* [eza-community/eza](https://github.com/eza-community/eza) - 'ls' 的替代品
* [fish-shell/fish-shell](https://github.com/fish-shell/fish-shell) - 用户友好的命令行 shell
* [fork](https://github.com/immortal/fork) - 用于创建脱离控制终端的新进程（守护进程）的库
* [fselect](https://crates.io/crates/fselect) - 使用类 SQL 查询查找文件
* [git-ai-project/git-ai](https://github.com/git-ai-project/git-ai) - 一个 git 扩展，追踪你仓库中 AI 生成的代码，将代码行关联到代理、模型和记录。
* [gitbutlerapp/gitbutler](https://github.com/gitbutlerapp/gitbutler) - 现代基于 Git 的版本控制界面，具备从零为 AI 驱动工作流打造的 GUI 和 CLI。
* [gitui](https://github.com/gitui-org/gitui) - 极快的 git 终端客户端。[![build](https://github.com/gitui-org/gitui/actions/workflows/ci.yml/badge.svg)](https://github.com/gitui-org/gitui/actions)
* [GQL](https://github.com/amrdeveloper/gql) - 在 .git 文件上运行的类 SQL 查询语言。
* [harry0703/MangoDisk](https://github.com/harry0703/MangoDisk) - 跨平台磁盘清理和空间分析应用，具备深度清理、矩形树图可视化、重复检测、应用卸载和开发者产物清理。[![Cross-platform Check](https://github.com/harry0703/MangoDisk/actions/workflows/cross-platform-check.yml/badge.svg)](https://github.com/harry0703/MangoDisk/actions/workflows/cross-platform-check.yml)
* [httm](https://github.com/kimono-koans/httm) - 面向 ZFS/btrfs/nilfs2 的交互式、文件级类 Time Machine 工具（甚至可用于实际的 Time Machine 备份！）
* [hyperb1iss/unifly](https://github.com/hyperb1iss/unifly) [[unifly](https://crates.io/crates/unifly)] - 用于管理 Ubiquiti UniFi 网络控制器的 CLI 和 TUI，具备双 API 覆盖和 10 屏 Ratatui 仪表板 [![CI](https://github.com/hyperb1iss/unifly/actions/workflows/cicd.yml/badge.svg)](https://github.com/hyperb1iss/unifly/actions/workflows/cicd.yml)
* [j0ru/kickoff](https://github.com/j0ru/kickoff) - 快速敏捷的 Wayland 程序启动器 [![build](https://github.com/j0ru/kickoff/actions/workflows/ci.yml/badge.svg)](https://github.com/j0ru/kickoff/actions)
* [jacek-kurlit/pik](https://github.com/jacek-kurlit/pik) [[pik](https://crates.io/crates/pik)] - 帮助你查找和终止进程的 TUI 命令行工具
* [Kondo](https://github.com/tbillington/kondo) - 用于删除软件项目产物并回收磁盘空间的 CLI 和 GUI 工具
* [LACT](https://github.com/ilya-zlobintsev/LACT) - Linux AMDGPU 控制器
* [LambdaBytes/sping](https://github.com/LambdaBytes/sping) [[sping](https://crates.io/crates/sping)] - 跨平台 ICMP/TCP 连通性诊断，具备网络上下文、多目标监控和结构化 JSON 输出。[![CI](https://github.com/LambdaBytes/sping/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/LambdaBytes/sping/actions/workflows/ci.yml)
* [lodosgroup/lpm](https://github.com/lodosgroup/lpm) - 实验性系统包管理器
* [lotabout/rargs](https://github.com/lotabout/rargs) [[rargs](https://crates.io/crates/rargs)] - 支持模式匹配的 xargs + awk
* [lsd](https://github.com/lsd-rs/lsd) - 带有大量漂亮颜色和炫酷图标的 ls [![build](https://github.com/lsd-rs/lsd/actions/workflows/CICD.yml/badge.svg)](https://github.com/lsd-rs/lsd/actions)
* [Luminarys/synapse](https://github.com/Luminarys/synapse) - 灵活且快速的 BitTorrent 守护进程。
* [m4b/bingrep](https://github.com/m4b/bingrep) - 从各种操作系统和架构的二进制文件中 grep，并为其着色。
* [macpow](https://github.com/k06a/macpow) - 面向 Apple Silicon Mac（M1–M5+）的实时功耗监控 TUI。读取 IOReport、SMC、IORegistry——无需 sudo。[![CI](https://github.com/k06a/macpow/actions/workflows/ci.yml/badge.svg)](https://github.com/k06a/macpow/actions/workflows/ci.yml)[![crates.io](https://img.shields.io/crates/v/macpow.svg?logo=rust)](https://crates.io/crates/macpow)
* [Mapika/portview](https://github.com/Mapika/portview) [[portview](https://crates.io/crates/portview)] - 查看你的端口上有什么：每个端口背后的进程，以及冲突、通配符暴露和连接泄漏的诊断。还兼作 MCP 服务器。[![CI](https://github.com/Mapika/portview/actions/workflows/ci.yml/badge.svg)](https://github.com/Mapika/portview/actions)
* [matheus-git/systemd-manager-tui](https://github.com/matheus-git/systemd-manager-tui) [[systemd-manager-tui](https://crates.io/crates/systemd-manager-tui)] - 通过 TUI（终端用户界面）管理 systemd 服务的程序。
* [matthart1983/diskwatch](https://github.com/matthart1983/diskwatch) - 单主机磁盘诊断 TUI：跨越设备、卷、文件系统、IO、SMART、热点文件和洞察的八个标签页。
* [matthart1983/netwatch](https://github.com/matthart1983/netwatch) [[netwatch-tui](https://crates.io/crates/netwatch-tui)] - 实时网络诊断 TUI：跨 13 种协议（TLS、QUIC、HTTP、DNS、SSH、MQTT、SNMP……）的深度包检测，通过 eBPF / PKTAP 进行按进程归因，TCP 重传分析，JA4 指纹识别，可选的 Landlock 沙箱，以及 Flight Recorder 事件包。
* [matthart1983/syswatch](https://github.com/matthart1983/syswatch) [[syswatch](https://crates.io/crates/syswatch)] - 单主机系统诊断 TUI：跨越 CPU、内存、磁盘、进程、GPU、电源、服务和网络的十二个标签页，外加时间线滑块和 Insights 异常引擎。
* [mdgaziur/findex](https://github.com/mdgaziur/findex) - Findex 是一个使用 GTK3 的高度可定制应用查找器
* [MenkeTechnologies/fusevm](https://crates.io/crates/fusevm) - 多语言虚拟机和 JIT
* [MenkeTechnologies/temprs](https://crates.io/crates/temprs) - 具备栈机制的临时文件管理器
* [MenkeTechnologies/zshrs](https://crates.io/crates/zshrs) - 具备 JIT 的 zsh 超集 UNIX shell
* [mitnk/cicada](https://github.com/mitnk/cicada) - 类 bash 的 Unix shell
* [mmstick/concurr](https://github.com/mmstick/concurr) - GNU Parallel 的替代品，采用客户端-服务器架构
* [mmstick/fontfinder](https://github.com/mmstick/fontfinder) - 用于预览和安装 Google 字体的 GTK3 应用
* [mmstick/tv-renamer](https://github.com/mmstick/tv-renamer) - 电视剧重命名应用，具备可选的 GTK3 前端。
* [mxseev/logram](https://github.com/mxseev/logram) - 将日志文件的更新推送到 Telegram
* [netscanner](https://github.com/Chleba/netscanner) - TUI 网络扫描器
* [nickgerace/gfold](https://github.com/nickgerace/gfold) [[gfold](https://crates.io/crates/gfold)] - 帮助你跟踪多个 Git 仓库的 CLI 工具 [![build](https://img.shields.io/github/workflow/status/nickgerace/gfold/merge/main)](https://github.com/nickgerace/gfold/actions?query=workflow%3Amerge+branch%3Amain)
* [nivekuil/rip](https://github.com/nivekuil/rip) - `rm` 的安全且符合人体工程学的替代品
* [nushell/nushell](https://github.com/nushell/nushell) - 一种新型 shell
* [nwiizo/tfmcp](https://github.com/nwiizo/tfmcp) - Terraform MCP 工具——供 AI 助手通过 Model Context Protocol 管理 Terraform 环境的 CLI。
* [nwiizo/tfocus](https://github.com/nwiizo/tfocus) - 用于选择和执行 Terraform plan/apply 操作的交互式工具
* [orbit-tui](https://github.com/ziuus/orbit-tui) - 键盘驱动的终端系统仪表板（约 3MB，0.5% CPU），具备 CPU、内存、磁盘、网络、GPU、进程、时钟、日历和音频可视化
* [orhun/kmon](https://github.com/orhun/kmon) - Linux 内核管理器和活动监视器 ![https://github.com/orhun/kmon/actions](https://img.shields.io/github/actions/workflow/status/orhun/kmon/ci.yml?branch=master&label=build)
* [orhun/systeroid](https://github.com/orhun/systeroid) - sysctl(8) 的更强大替代品，具备终端用户界面 ![https://github.com/orhun/systeroid/actions](https://img.shields.io/github/actions/workflow/status/orhun/systeroid/ci.yml?branch=main&label=build)
* [ouch](https://github.com/ouch-org/ouch) - 命令行上无痛的压缩和解压 [![GitHub Workflow Status (branch)](https://img.shields.io/github/workflow/status/ouch-org/ouch/build-and-test)](https://github.com/ouch-org/ouch/actions?query=branch%3Amaster)
* [pkolaczk/fclones](https://github.com/pkolaczk/fclones) - 高效的重复文件查找器和移除器
* [pop-os/popsicle](https://github.com/pop-os/popsicle) - 用于并行刷写多个 USB 设备的 GTK3 和 CLI 工具
* [pop-os/system76-power](https://github.com/pop-os/system76-power/) - Linux 电源管理守护进程（DBus 接口），附带 CLI 工具。
* [pueue](https://github.com/nukesor/pueue) - 管理你的长时间运行的 shell 命令。[![GitHub Actions Workflow](https://github.com/Nukesor/pueue/actions/workflows/test.yml/badge.svg)](https://github.com/nukesor/pueue/actions)
* [qarmin/czkawka](https://github.com/qarmin/czkawka) - 多功能应用，用于查找重复文件、空文件夹、相似图片等。[![GitHub Actions Workflow](https://github.com/qarmin/czkawka/actions/workflows/pages/pages-build-deployment/badge.svg?branch=master)](https://github.com/qarmin/czkawka/actions)
* [redox-os/ion](https://github.com/redox-os/ion) - 下一代系统 shell
* [sharkdp/bat](https://github.com/sharkdp/bat) - 长了翅膀的 cat(1) 克隆。[![CICD](https://github.com/sharkdp/bat/actions/workflows/CICD.yml/badge.svg?branch=master)](https://github.com/sharkdp/bat/actions/workflows/CICD.yml)
* [sharkdp/fd](https://github.com/sharkdp/fd) - find 的简单、快速且用户友好的替代品。[![CICD](https://github.com/sharkdp/fd/actions/workflows/CICD.yml/badge.svg)](https://github.com/sharkdp/fd/actions/workflows/CICD.yml)
* [sharkdp/hexyl](https://github.com/sharkdp/hexyl) [[hexyl](https://crates.io/crates/hexyl)] - 命令行十六进制查看器，为不同字节类别提供彩色输出 [![CICD](https://github.com/sharkdp/hexyl/actions/workflows/CICD.yml/badge.svg)](https://github.com/sharkdp/hexyl/actions/workflows/CICD.yml)
* [sitkevij/hex](https://github.com/sitkevij/hex) - 彩色化的 hexdump 终端工具。
* [Skardyy/mcat](https://github.com/Skardyy/mcat) [[mcat](https://crates.io/crates/mcat)] - 在终端中查看图片、视频、Markdown 和其他文档。
* [skim](https://github.com/skim-rs/skim) - 模糊查找器
* [sorairolake/hf](https://github.com/sorairolake/hf) [[hf](https://crates.io/crates/hf)] - 跨平台隐藏文件库和工具 [![CI](https://github.com/sorairolake/hf/actions/workflows/CI.yaml/badge.svg?branch=develop)](https://github.com/sorairolake/hf/actions/workflows/CI.yaml)
* [sorairolake/ngrv](https://github.com/sorairolake/ngrv) [[ngrv](https://crates.io/crates/ngrv)] - 类似 `pv(1)` 的基于终端的管道查看器 [![CI](https://github.com/sorairolake/ngrv/actions/workflows/CI.yaml/badge.svg?branch=develop)](https://github.com/sorairolake/ngrv/actions/workflows/CI.yaml)
* [sorairolake/rzopfli](https://github.com/sorairolake/rzopfli) [[rzopfli](https://crates.io/crates/rzopfli)] - 使用 Zopfli 的无损数据压缩工具 [![CI](https://github.com/sorairolake/rzopfli/actions/workflows/CI.yaml/badge.svg?branch=develop)](https://github.com/sorairolake/rzopfli/actions/workflows/CI.yaml)
* [supercilex/fuc](https://github.com/supercilex/fuc) - 快速的 `cp` 和 `rm` 命令
* [theBGuy/GitDesktop](https://github.com/theBGuy/GitDesktop) - 键盘优先的 Git 桌面客户端，跨 GitHub、GitLab 和 Bitbucket 管理 PR、issue、讨论、CI 和通知，外加 Jira 关联和 AI 代理集成；Tauri + Rust 后端 [![Release](https://github.com/theBGuy/GitDesktop/actions/workflows/release.yml/badge.svg)](https://github.com/theBGuy/GitDesktop/actions/workflows/release.yml)
* [timhartmann7/omnyssh](https://github.com/timhartmann7/omnyssh) - 快速、键盘驱动的 TUI，用于管理 SSH 连接 [![CI](https://github.com/timhartmann7/omnyssh/actions/workflows/ci.yml/badge.svg)](https://github.com/timhartmann7/omnyssh/actions/workflows/ci.yml)
* [topheman/webassembly-component-model-experiments](https://github.com/topheman/webassembly-component-model-experiments) - 基于 WebAssembly Component Model 的 REPL，具备沙箱化多语言插件系统 [![Crates.io](https://img.shields.io/crates/v/pluginlab.svg)](https://crates.io/crates/pluginlab)
* [trippy](https://github.com/fujiapple852/trippy) - 网络诊断工具 [![build badge](https://github.com/fujiapple852/trippy/workflows/CI/badge.svg)](https://github.com/fujiapple852/trippy/actions/workflows/ci.yml)
* [tw93/Kaku](https://github.com/tw93/Kaku) - 为 AI 编码打造的快速、开箱即用的终端模拟器，具备零配置默认值、AI 助手集成和兼容 WezTerm 的 Lua 配置。仅限 macOS。
* [uutils/coreutils](https://github.com/uutils/coreutils) - GNU coreutils 的跨平台重写 [![CICD](https://github.com/uutils/coreutils/actions/workflows/CICD.yml/badge.svg)](https://github.com/uutils/coreutils/actions/workflows/CICD.yml)
* [vyrti/cleaner](https://github.com/vyrti/cleaner) - 面向 Windows、macOS、Linux 和 FreeBSD 的最快磁盘空间使用分析器和清理器。[![CI](https://github.com/vyrti/cleaner/actions/workflows/ci.yml/badge.svg)](https://github.com/vyrti/cleaner/actions)
* [watchexec](https://github.com/watchexec/watchexec) - 响应文件修改执行命令
* [XAMPPRocky/tokei](https://github.com/XAMPPRocky/tokei) - 统计代码行数
* [ynqa/jnv](https://github.com/ynqa/jnv) - 使用 jq 的交互式 JSON 过滤器 [![ci](https://github.com/ynqa/jnv/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/ynqa/jnv/actions/workflows/ci.yml)
* [ynqa/logu](https://github.com/ynqa/logu) - 从（流式）非结构化日志消息中提取模式 [![ci](https://github.com/ynqa/logu/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/ynqa/logu/actions/workflows/ci.yml)
* [ynqa/sig](https://github.com/ynqa/sig) - 交互式 grep（用于流式数据） [![ci](https://github.com/ynqa/sig/actions/workflows/ci.yml/badge.svg)](https://github.com/ynqa/sig/actions/workflows/ci.yml)

### 任务调度

* [tasklet](https://github.com/stav121/tasklet) [[tasklet](https://crates.io/crates/tasklet)] - 用 Rust 编写的任务调度库 ![Build Status](https://img.shields.io/github/actions/workflow/status/stav121/tasklet/rust.yml)

### 文本编辑器

* [amp](https://amp.rs) - 受 Vi/Vim 启发。
* [Ferrite](https://github.com/OlaProeis/Ferrite) - 使用 egui 构建的跨平台 Markdown 编辑器，具备实时预览、语法高亮和 mermaid 图表。
* [Fresh](https://github.com/sinelaw/fresh) - 易用、强大且快速的终端文本编辑器和 IDE，支持 TypeScript 插件。
* [gchp/iota](https://github.com/gchp/iota) - 简单的文本编辑器
* [helix](https://github.com/helix-editor/helix) - 受 Neovim/Kakoune 启发的后现代模态文本编辑器。[![build badge](https://github.com/helix-editor/helix/actions/workflows/build.yml/badge.svg)](https://github.com/helix-editor/helix/actions)
* [ilai-deutel/kibi](https://github.com/ilai-deutel/kibi) - 极小的（≤1024 行代码）文本编辑器，具备语法高亮、增量搜索等。[![build badge](https://github.com/ilai-deutel/kibi/actions/workflows/ci.yml/badge.svg)](https://github.com/ilai-deutel/kibi/actions?query=branch%3Amaster)
* [Inkwell](https://github.com/4worlds4w-svg/inkwell) - 使用 Tauri v2 构建的便携、离线优先 Markdown 编辑器。单一可执行文件，零遥测。
* [jamii/focus](https://github.com/jamii/focus) - 极简文本编辑器，内置 jj（Jujutsu）版本控制集成。
* [ki-editor/ki-editor](https://github.com/ki-editor/ki-editor) - 多光标组合式模态编辑器
* [Lapce](https://github.com/lapce/lapce) - 带后端的现代编辑器。灵感来自已停止开发的 [xi-editor](https://github.com/xi-editor/xi-editor)。
* [manyougz/velotype](https://github.com/manyougz/velotype) - 基于块的原生 Markdown 编辑器，具备所见即所得渲染和源码编辑模式，构建在 GPUI 之上，无 WebView 外壳。
* [mathall/rim](https://github.com/mathall/rim) - 类 Vim 文本编辑器。
* [Oleafly/Oleafly](https://github.com/Oleafly/Oleafly) - 用于使用 LaTeX、Typst 和 Markdown 撰写论文和学位论文的桌面编辑器，内置 Tectonic 引擎和实时 PDF 预览。使用 Tauri 构建。[![CI](https://github.com/Oleafly/Oleafly/actions/workflows/ci.yml/badge.svg?branch=main&event=push)](https://github.com/Oleafly/Oleafly/actions/workflows/ci.yml)
* [ox](https://github.com/curlpipe/ox) - 一个在你的终端中运行的独立 Rust 文本编辑器！
* [SoloMD](https://github.com/zhitongblog/solomd) - 使用 Tauri 2 构建的轻量级跨平台 Markdown 编辑器，具备实时预览。
* [vamolessa/pepper](https://git.sr.ht/~lessa/pepper) [[pepper](https://crates.io/crates/pepper)] - 有主见的模态编辑器，简化终端中的代码编辑
* [zed](https://github.com/zed-industries/zed) - 来自 Atom 和 Tree-sitter 创作者的高性能多人代码编辑器。

### 文本处理

* [artob/readmer](https://github.com/artob/readmer) [[readmer](https://crates.io/crates/readmer)] - Readmer 从 Liquid 或 Jinja2 模板组合 `README.md` 文件。[![Build Status](https://github.com/artob/readmer/actions/workflows/rust.yaml/badge.svg)](https://github.com/artob/readmer/blob/master/.github/workflows/rust.yaml)
* [ashvardanian/stringzilla](https://github.com/ashvardanian/StringZilla) - 面向 x86 AVX2 和 AVX-512 以及 Arm NEON 的 SIMD 加速字符串搜索、排序、编辑距离、对齐和生成器 [![crates.io](https://img.shields.io/crates/v/stringzilla.svg)](https://crates.io/crates/stringzilla)
* [bensadeh/tailspin](https://github.com/bensadeh/tailspin) [[tailspin](https://crates.io/crates/tailspin)] - 日志文件高亮器，高亮数字、日期、IP 地址、UUID 和日志级别。[![Run Tests](https://github.com/bensadeh/tailspin/workflows/Run%20Tests/badge.svg)](https://github.com/bensadeh/tailspin/actions)
* [brevity1swos/rgx](https://github.com/brevity1swos/rgx) [[rgx-cli](https://crates.io/crates/rgx-cli)] - 终端正则表达式调试器，具备实时匹配、单步调试器、3 个引擎、代码生成和实时流过滤。[![CI](https://github.com/brevity1swos/rgx/actions/workflows/ci.yml/badge.svg)](https://github.com/brevity1swos/rgx/actions/workflows/ci.yml)
* [cchexcode/complate](https://github.com/cchexcode/complate) - 终端内文本模板工具，用于标准化消息（如 GIT 提交）。[![crates.io](https://img.shields.io/crates/v/complate.svg)](https://crates.io/crates/complate) [![crates.io](https://img.shields.io/crates/d/complate?label=crates.io%20downloads)](https://crates.io/crates/complate) [![build badge](https://github.com/cchexcode/complate/actions/workflows/release.yml/badge.svg)](https://github.com/cchexcode/complate/actions)
* [dathere/qsv](https://github.com/dathere/qsv) [[qsv](https://crates.io/crates/qsv)] - 高性能 CSV 数据处理工具包。从 xsv 分叉而来，新增 34+ 命令等。[![Linux build status](https://github.com/dathere/qsv/actions/workflows/rust.yml/badge.svg)](https://github.com/dathere/qsv/actions/workflows/rust.yml) [![Windows build status](https://github.com/dathere/qsv/actions/workflows/rust-windows.yml/badge.svg)](https://github.com/dathere/qsv/actions/workflows/rust-windows.yml) [![macOS build status](https://github.com/dathere/qsv/actions/workflows/rust-macos.yml/badge.svg)](https://github.com/dathere/qsv/actions/workflows/rust-macos.yml)
* [dominikwilkowski/cfonts](https://github.com/dominikwilkowski/cfonts) [[cfonts](https://crates.io/crates/cfonts)] - 面向控制台的性感 ANSI 字体 ![build badge](https://github.com/dominikwilkowski/cfonts/actions/workflows/testing.yml/badge.svg)
* [Goldziher/uncomment](https://github.com/Goldziher/uncomment) [[uncomment](https://crates.io/crates/uncomment)] - 极快的 CLI，使用 tree-sitter 语法从代码中移除注释。
* [grex](https://github.com/pemistahl/grex) - 从用户提供的测试用例生成正则表达式的命令行工具和库
* [harehare/mq](https://github.com/harehare/mq) - 使用类 jq 语法处理 Markdown 的命令行工具和库 [![build badge](https://github.com/harehare/mq/actions/workflows/ci.yml/badge.svg)](https://github.com/harehare/mq/actions/workflows/ci.yml)
* [Lisprez/so_stupid_search](https://github.com/Lisprez/so_stupid_search) - 为人类打造的简单快速字符串搜索工具
* [loki_text](https://github.com/roquess/loki_text) [[loki_text](https://crates.io/crates/loki_text)] - 字符串操作库，具备模式搜索、文本转换和多种字符串搜索算法（KMP、Boyer-Moore、Aho-Corasick 等）
* [Melody](https://github.com/yoav-lavi/melody) - 一种编译为正则表达式的语言，旨在更易读和易维护 [![build badge](https://github.com/yoav-lavi/melody/actions/workflows/rust.yml/badge.svg)](https://github.com/yoav-lavi/melody/actions/workflows/rust.yml) [![crates.io](https://img.shields.io/crates/v/melody_compiler?label=compiler)](https://crates.io/crates/melody_compiler)
* [micahkepe/jsongrep](https://github.com/micahkepe/jsongrep) [[jsongrep](https://crates.io/crates/jsongrep)] - 面向 JSON、YAML、TOML 和其他序列化格式的快速搜索工具，具备直观的路径查询语法。
* [phiresky/ripgrep-all](https://github.com/phiresky/ripgrep-all) - ripgrep，但也能在 PDF、电子书、Office 文档、zip、tar.gz 等中搜索。
* [ripgrep](https://crates.io/crates/ripgrep) - 结合了 The Silver Searcher 的易用性和 grep 的原始速度
* [ruplacer](https://github.com/your-tools/ruplacer) - 在源文件中查找和替换文本 [![Run tests](https://github.com/your-tools/ruplacer/actions/workflows/test.yml/badge.svg?branch=master)](https://github.com/your-tools/ruplacer/actions/workflows/test.yml)
* [scooter](https://github.com/thomasschafer/scooter) - 终端中的交互式查找和替换。
* [sd](https://crates.io/crates/sd) - 直观的查找和替换 CLI
* [sstadick/hck](https://github.com/sstadick/hck) - `cut` 的更快、功能更丰富的开箱即用替代品 [![build badge](https://github.com/sstadick/hck/workflows/Check/badge.svg?branch=master)](https://github.com/sstadick/hck)
* [SylphxAI/anymd](https://github.com/SylphxAI/anymd) - 将任何文件（PDF、DOCX、PPTX、XLSX、EPUB、HTML/URL、图片、音频/视频）转换为干净的 Markdown，供 AI 代理使用；一个 CLI 和 MCP 服务器 [![build badge](https://github.com/SylphxAI/anymd/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/SylphxAI/anymd/actions/workflows/ci.yml)
* [vishaltelangre/ff](https://github.com/vishaltelangre/ff) - 按名称查找文件（ff）！
* [whitfin/bytelines](https://github.com/whitfin/bytelines) [[bytelines](https://crates.io/crates/bytelines)] - 以字节切片读取输入行以提高效率。
* [whitfin/runiq](https://github.com/whitfin/runiq) - 从无序输入中过滤重复行的高效方式。
* [xsv](https://crates.io/crates/xsv) - 快速的 CSV 命令行工具（切片、索引、选择、搜索、采样等）

### 实用工具

* [1History](https://github.com/localfirstapp/1History) - 将 Firefox/Chrome/Safari 历史备份到一个 SQLite 文件的命令行界面 [![Build Status](https://github.com/localfirstapp/1History/actions/workflows/CI.yml/badge.svg)](https://github.com/localfirstapp/1History/actions/workflows/CI.yml)
* [aravpanwar/decayfmt](https://github.com/aravpanwar/decayfmt) [[decayfmt](https://crates.io/crates/decayfmt)] - 一种文件格式，其文件每次打开都会永久损坏一点，仅凭文件本身无法恢复。[![CI](https://github.com/aravpanwar/decayfmt/actions/workflows/ci.yml/badge.svg)](https://github.com/aravpanwar/decayfmt/actions/workflows/ci.yml)
* [artob/edky](https://github.com/artob/edky) [[edky](https://crates.io/crates/edky)] - 在各种编码格式（Base58、Base64、IPFS、iroh、libp2p、OpenSSH 等）之间转换 Ed25519 公钥的命令行工具。[![Build Status](https://github.com/artob/edky/actions/workflows/rust.yaml/badge.svg)](https://github.com/artob/edky/blob/master/.github/workflows/rust.yaml)
* [bloznelis/kbt](https://github.com/bloznelis/kbt) [[kbt](https://crates.io/crates/kbt)] - 用于键盘测试的简单 TUI 工具。
* [brycx/checkpwn](https://github.com/brycx/checkpwn) - 一个 Have I Been Pwned (HIBP) 命令行工具，让你轻松检查被泄露的账户和密码。
* [cartesiancs/vessel](https://github.com/cartesiancs/vessel) - 用于编排物理设备的 C2（命令与控制）软件。
* [dcapal](https://github.com/dcapal/dcapal) - DcaPal 是一个免费、无需注册的在线工具，帮助你通过定投保持投资组合平衡。
* [Eoin-McMahon/Blindfold](https://github.com/Eoin-McMahon/Blindfold) [[Blindfold](https://crates.io/crates/blindfold)] - 用于快速轻松生成 `.gitignore` 文件的简单 CLI 工具。[![build-badge](https://github.com/Eoin-McMahon/blindfold/actions/workflows/rust.yml/badge.svg)]([https://github.com/nix-community/nurl/actions/workflows/ci.yml](https://github.com/Eoin-McMahon/blindfold/actions/workflows/rust.yml))
* [Epic Asset Manager](https://github.com/AchetaGames/Epic-Asset-Manager) - 用于安装 Unreal Engine、从 Epic Games Store 下载和管理已购资产、项目、插件和游戏的第三方客户端。
* [evansmurithi/cloak](https://github.com/evansmurithi/cloak) - 命令行 OTP（一次性密码）身份验证器应用。![CI](https://github.com/evansmurithi/cloak/workflows/CI/badge.svg) [![build badge](https://ci.appveyor.com/api/projects/status/9mlfpfru3ng4c689/branch/master?svg=true)](https://ci.appveyor.com/project/evansmurithi/cloak)
* [fcsonline/tmux-thumbs](https://github.com/fcsonline/tmux-thumbs) - tmux-fingers 的极速版本，像 vimium/vimperator 一样复制/粘贴 tmux。
* [fosk/emplace](https://codeberg.org/fosk/emplace) [[emplace](https://crates.io/crates/emplace)] - 在多台机器上同步已安装的包
* [gitlogue](https://github.com/unhappychoice/gitlogue) - 在终端中可视化 Git 提交历史的 TUI 屏保
* [guoxbin/dtool](https://github.com/guoxbin/dtool) - 一套有用的命令行工具集合，辅助开发，包括转换、编解码、哈希、加密等。
* [IvanWng97/pixtuoid](https://github.com/IvanWng97/pixtuoid) [[pixtuoid](https://crates.io/crates/pixtuoid)] - 终端像素艺术办公室，将 Claude Code 会话实时可视化为动画同事。[![CI](https://img.shields.io/github/actions/workflow/status/IvanWng97/pixtuoid/ci.yml?branch=main)](https://github.com/IvanWng97/pixtuoid/actions/workflows/ci.yml)
* [ja7ad/hydra](https://github.com/ja7ad/hydra) - 开源、高性能的下载管理器和加速器，将每个文件拆分到并行连接和镜像源。具备动态范围窃取和实时停滞恢复，适用于 Windows、macOS 和 Linux。
* [lamco-admin/lamco-rdp-server](https://github.com/lamco-admin/lamco-rdp-server) - 基于 IronRDP 构建的 Wayland 原生 RDP 服务器，在 Wayland Linux 桌面（GNOME、KDE、COSMIC、wlroots 合成器等）上提供远程桌面访问，无需 X11。
* [Linus-Mussmaecher/rucola](https://github.com/Linus-Mussmaecher/rucola) - 基于终端的 Markdown 笔记管理器。[![Crate](https://img.shields.io/crates/v/rucola-notes.svg?logo=rust)](https://crates.io/crates/rucola-notes) [![Build Status](https://github.com/Linus-Mussmaecher/rucola/actions/workflows/continuous-testing.yml/badge.svg)](https://github.com/Linus-Mussmaecher/rucola/actions/workflows/continuous-testing.yml)
* [matugen](https://github.com/InioX/matugen) - 使用模板从图像或颜色生成调色板。
* [Mobslide](https://github.com/thewh1teagle/mobslide) - 将你的智能手机变成演示遥控器的桌面应用。
* [MoonProxyHQ/moonproxy-desktop](https://github.com/MoonProxyHQ/moonproxy-desktop) - FRP（frpc）的跨平台 GUI 桌面客户端，让非技术用户一键将本地服务暴露到公网。[![CI](https://github.com/MoonProxyHQ/moonproxy-desktop/actions/workflows/ci.yml/badge.svg)](https://github.com/MoonProxyHQ/moonproxy-desktop/actions/workflows/ci.yml)
* [mprocs](https://github.com/pvolok/mprocs) - 用于运行多个进程的 TUI
* [mrjackwills/oxker](https://github.com/mrjackwills/oxker) [[oxker](https://crates.io/crates/oxker)] - 用于查看和控制 docker 容器的简单 TUI。
* [nix-community/nix-init](https://github.com/nix-community/nix-init) - 从 URL 生成 Nix 包，具备哈希预取、依赖推断、许可证检测等 [![build-badge](https://github.com/nix-community/nix-init/actions/workflows/ci.yml/badge.svg)](https://github.com/nix-community/nix-init/actions/workflows/ci.yml)
* [nix-community/nix-melt](https://github.com/nix-community/nix-melt) - 类似 ranger 的 flake.lock 查看器 [![build-badge](https://github.com/nix-community/nix-melt/actions/workflows/ci.yml/badge.svg)](https://github.com/nix-community/nix-melt/actions/workflows/ci.yml)
* [nix-community/nurl](https://github.com/nix-community/nurl) [[nurl](https://crates.io/crates/nurl)] - 从仓库 URL 生成 Nix fetcher 调用 [![build-badge](https://github.com/nix-community/nurl/actions/workflows/ci.yml/badge.svg)](https://github.com/nix-community/nurl/actions/workflows/ci.yml)
* [nomino](https://github.com/yaa110/nomino) - 面向开发者的批量重命名工具
* [pastel](https://github.com/sharkdp/pastel) - 帮助你处理颜色：生成、混合、随机颜色。
* [race604/clock-tui](https://github.com/race604/clock-tui) [[clock-tui](https://crates.io/crates/clock-tui)] - 终端时钟应用，具备本地时钟、定时器和秒表。[![Rust](https://github.com/race604/clock-tui/actions/workflows/rust.yml/badge.svg)](https://github.com/race604/clock-tui/actions/workflows/rust.yml)
* [raftario/licensor](https://github.com/raftario/licensor) - 将许可证写入 stdout [![GitHub Actions](https://github.com/raftario/licensor/actions/workflows/build.yml/badge.svg?branch=master)](https://github.com/raftario/licensor/actions/workflows/build.yml)
* [restsend/rustpbx](https://github.com/restsend/rustpbx) - 软件定义的 SIP 代理，包括注册、状态呈现、b2bua。Freeswitch/FreePBX 的替代品。
* [rleeon/hoard](https://github.com/rleeon/hoard) - 游戏存档备份和同步系统，具备自动检测、版本化快照和自托管存储。[![CI](https://github.com/rleeon/hoard/actions/workflows/ci.yml/badge.svg)](https://github.com/rleeon/hoard/actions/workflows/ci.yml)
* [rust-parallel](https://github.com/aaronriekenberg/rust-parallel) - 使用 Tokio 并行执行命令的快速命令行应用。接口类似 GNU Parallel 或 xargs。[![Crate](https://img.shields.io/crates/v/rust-parallel.svg?logo=rust)](https://crates.io/crates/rust-parallel) [![Build Status](https://github.com/aaronriekenberg/rust-parallel/actions/workflows/CI.yml/badge.svg)](https://github.com/aaronriekenberg/rust-parallel/actions/workflows/CI.yml)
* [rustdesk/rustdesk](https://github.com/rustdesk/rustdesk) - 远程桌面软件，TeamViewer 和 AnyDesk 的绝佳替代品。
* [rustic-rs/rustic](https://github.com/rustic-rs/rustic) [[rustic-rs](https://crates.io/crates/rustic-rs)] - 由 Rust 驱动的快速、加密、去重备份。[![Version](https://img.shields.io/crates/v/rustic-rs.svg)](https://crates.io/crates/rustic-rs)
* [ruvnet/RuView](https://github.com/ruvnet/RuView) - 使用 WiFi 信道状态信息（CSI）和机器学习的隐私保护人体姿态估计系统。
* [sorairolake/qrtool](https://github.com/sorairolake/qrtool) [[qrtool](https://crates.io/crates/qrtool)] - 用于编码和解码二维码图像的工具。[![CI](https://github.com/sorairolake/qrtool/workflows/CI/badge.svg?branch=develop)](https://github.com/sorairolake/qrtool/actions?query=workflow%3ACI)
* [sorairolake/randgen](https://github.com/sorairolake/randgen) [[randgen](https://crates.io/crates/randgen)] - 生成伪随机字节 [![CI](https://github.com/sorairolake/randgen/actions/workflows/CI.yaml/badge.svg?branch=develop)](https://github.com/sorairolake/randgen/actions/workflows/CI.yaml)
* [splashboard](https://github.com/unhappychoice/splashboard) [[splashboard](https://crates.io/crates/splashboard)] - 在 shell 启动和目录切换时渲染的可自定义终端启动画面，具备按目录的仪表板 [![CI](https://github.com/unhappychoice/splashboard/actions/workflows/ci.yml/badge.svg)](https://github.com/unhappychoice/splashboard/actions/workflows/ci.yml)
* [str4d/rage](https://github.com/str4d/rage) [[rage](https://crates.io/crates/rage)] - [age](https://github.com/FiloSottile/age) 的 Rust 实现。
* [suckit](https://github.com/Skallwar/suckit) - 递归访问并将网站内容下载到你的磁盘。[![Crate](https://img.shields.io/crates/v/suckit.svg?logo=rust)](https://crates.io/crates/suckit) [![Build Status](https://github.com/Skallwar/suckit/workflows/Build%20and%20test/badge.svg)](https://github.com/Skallwar/suckit/blob/master/.github/workflows/build_and_test.yml)
* [sundegan/JsonStudio](https://github.com/sundegan/JsonStudio) - 使用 Rust 和 Tauri 构建的本地优先桌面 JSON 工作区，用于格式化、编辑、差异比较、转换、验证和日志提取。
* [Tabiew](https://github.com/shshemi/tabiew) - 用于查看和查询 CSV 文件的轻量级 TUI 应用。
* [Tail Tales](https://github.com/davidmoreno/tailtales) - 支持 logfmt 的 TUI 日志查看器。[![Crate](https://img.shields.io/crates/v/tailtales.svg?logo=rust)](https://crates.io/crates/tailtales)
* [tareqmy/gitwig](https://github.com/tareqmy/gitwig) [[CRATE](https://crates.io/crates/gitwig)] - 可用鼠标驱动的 git TUI 和多仓库仪表板。
* [television](https://github.com/alexpasmantier/television) - 极快的通用模糊查找器 TUI ![GitHub branch check runs](https://img.shields.io/github/check-runs/alexpasmantier/television/main)
* [Thoth](https://github.com/anitnilay20/thoth) - 用于查看和探索 JSON 和 NDJSON 文件的高性能、功能丰富的桌面应用，具备基于 WASM 的插件支持。[![CI](https://github.com/anitnilay20/thoth/workflows/CI/badge.svg)](https://github.com/anitnilay20/thoth/actions/workflows/ci.yml)
* [vamolessa/verco](https://git.sr.ht/~lessa/verco) [[verco](https://crates.io/crates/verco)] - 专注于键盘快捷键的简单 Git/Hg TUI 客户端
* [vaultwarden](https://github.com/dani-garcia/vaultwarden#readme) [![Build](https://github.com/dani-garcia/vaultwarden/actions/workflows/build.yml/badge.svg)](https://github.com/dani-garcia/vaultwarden/actions/workflows/build.yml) - 用 Rust 编写的 Bitwarden 服务器 API 的替代实现
* [veirt/weathr](https://github.com/Veirt/weathr) [[weathr](https://crates.io/crates/weathr)] - 具备 ASCII 动画的终端天气应用。[![Release](https://github.com/Veirt/weathr/actions/workflows/release.yml/badge.svg)](https://github.com/Veirt/weathr/actions/workflows/release.yml)
* [Vibe](https://github.com/thewh1teagle/vibe) - 在每个平台上转录每种语言的音频或视频。
* [warpdotdev/Warp](https://github.com/warpdotdev/Warp) - :heavy_dollar_sign: Warp 是一个极快的现代 GPU 加速终端，旨在让你和你的团队更高效。
* [Water-Run/treepp](https://github.com/Water-Run/treepp) - 基于 Rust 的原生 Windows `tree` 替代品，在成功运行时具备差异级输入/输出兼容性，还有更多功能，包括必要的排除项和 `.gitignore` 支持，性能快数倍。
* [wrestic](https://github.com/alvaro17f/wrestic) - restic 的封装。
* [wthrr](https://github.com/ttytm/wthrr-the-weathercrab) - 终端的天气伴侣。[![crates.io](https://img.shields.io/crates/v/wthrr?logo=rust)](https://crates.io/crates/wthrr)
* [YAKC](https://github.com/iammodev/YAKC) - 用于屏幕录制、直播和演示的跨平台按键和鼠标点击可视化工具。适用于 Windows、macOS 和 Linux（X11 和 Wayland）。[![CI](https://github.com/iammodev/YAKC/actions/workflows/ci.yml/badge.svg)](https://github.com/iammodev/YAKC/actions/workflows/ci.yml)
* [YueMiyuki/Risuko](https://github.com/YueMiyuki/Risuko) - 功能齐全的下载管理器。[![Release-Badge](https://github.com/YueMiyuki/Risuko/actions/workflows/release.yml/badge.svg)](https://github.com/YueMiyuki/Risuko/actions/workflows/release.yml)
* [zerx-lab/FluxDown](https://github.com/zerx-lab/FluxDown) - 多协议下载管理器，采用 Rust/Tokio 引擎，支持 HTTP/FTP、BitTorrent、eD2K、HLS 和 DASH，具备 IDM 风格的动态分段、浏览器扩展和兼容 aria2 的 JSON-RPC 端点。

### 视频

* [dertuxmalwieder/yaydl](https://github.com/dertuxmalwieder/yaydl) [[yaydl](https://crates.io/crates/yaydl)] - 简单的视频下载器
* [gyroflow/gyroflow](https://github.com/gyroflow/gyroflow) - 使用陀螺仪数据的视频稳定应用
* [harlanc/xiu](https://github.com/harlanc/xiu) - 强大且安全的直播服务器（rtmp/httpflv/hls/relay）。[![crates.io](https://img.shields.io/crates/v/xiu.svg)](https://crates.io/crates/xiu)
* [Jorji49/streamtop](https://github.com/Jorji49/streamtop) [[streamtop](https://crates.io/crates/streamtop)] - 终端 HLS、DASH 和 IPTV 流监控器，具备线路探针、TR 101 290 和 SCTE-35 指标。
* [Michael-A-Kuykendall/muxide](https://github.com/Michael-A-Kuykendall/muxide) [[muxide](https://crates.io/crates/muxide)] - 纯 Rust MP4 复用器，无外部依赖，可从编码帧写入符合标准的 MP4。
* [open-subs/opensubs](https://github.com/open-subs/opensubs) - 在浏览器中运行的字幕生成器：设备端 Whisper 转录，配合编译为 WebAssembly 的 Rust 引擎进行字幕分段、断行和样式设置
* [storytold/effectcraft](https://github.com/storytold/effectcraft) - Adobe After Effects 的开源、净室重新实现，用于动态图形和视觉效果，用纯 Rust 构建。
* [tonhowtf/omniget](https://github.com/tonhowtf/omniget) - 桌面应用，可从 1800+ 网站下载视频、课程、音乐和书籍，内置播放器、阅读器和学习库。[![CI](https://github.com/tonhowtf/omniget/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/tonhowtf/omniget/actions/workflows/ci.yml)
* [vidmerger](https://github.com/TGotwig/vidmerger) - 通过 CLI 合并视频和音频文件
* [vuiodev/vuio](https://github.com/vuiodev/vuio) - 支持 Linux、macOS、Windows 和 Docker 的 DLNA 媒体服务器
* [xiph/rav1e](https://github.com/xiph/rav1e) - 最快且最安全的 AV1 编码器。

### 虚拟化

* [firecracker-microvm/firecracker](https://github.com/firecracker-microvm/firecracker) - 面向容器工作负载的轻量级虚拟机 [Firecracker Microvm](https://firecracker-microvm.github.io/)
* [kata-containers/kata-containers](https://github.com/kata-containers/kata-containers) - 轻量级虚拟机（VM）的实现，感觉和表现得像容器，但提供 VM 的工作负载隔离和安全优势。
* [superradcompany/microsandbox](https://github.com/superradcompany/microsandbox) - 轻量级 microVM 沙箱库，可在毫秒内运行隔离的代码执行。支持 Rust、Python 和 TypeScript SDK，兼容 OCI 容器镜像。[![GitHub release](https://img.shields.io/github/v/release/superradcompany/microsandbox?include_prereleases)](https://github.com/superradcompany/microsandbox/releases)
* [tailhook/vagga](https://github.com/tailhook/vagga) - 无守护进程的容器化工具
* [youki-dev/youki](https://github.com/youki-dev/youki) - 容器运行时 [![build badge](https://github.com/youki-dev/youki/actions/workflows/basic.yml/badge.svg)](https://github.com/youki-dev/youki/actions)

### Web

* [0xMassi/webclaw](https://github.com/0xMassi/webclaw) - 面向 LLM 的 Web 内容提取，具备 TLS 指纹识别、MCP 服务器，无需浏览器 [![CI](https://github.com/0xMassi/webclaw/actions/workflows/ci.yml/badge.svg)](https://github.com/0xMassi/webclaw/actions)
* [agrinman/tunnelto](https://github.com/agrinman/tunnelto) [[tunnelto](https://crates.io/crates/tunnelto)] - 让你通过公共 URL 暴露本地运行的 Web 服务器。
* [cfal/tobaru](https://github.com/cfal/tobaru) - 端口转发器，具备允许列表、基于 IP 和 TLS SNI/ALPN 规则的路由、iptables 支持、轮询转发（负载均衡）和热重载。
* [hook0/hook0](https://github.com/hook0/hook0) - 开源 webhooks 即服务平台，让 SaaS 开发者轻松发送 webhook
* [importantimport/hatsu](https://github.com/importantimport/hatsu) - 🩵 面向静态站点的自托管、全自动 ActivityPub 桥。[![release](https://github.com/importantimport/hatsu/actions/workflows/release.yml/badge.svg)](https://github.com/importantimport/hatsu/actions/workflows/release.yml)
* [IndexFlowing/IndexFlow-core](https://github.com/IndexFlowing/IndexFlow-core) - 自托管 SEO 索引基础设施，用于管理站点地图、URL 提交和搜索引擎索引。
* [janreges/siteone-crawler](https://github.com/janreges/siteone-crawler) [[siteone-crawler](https://crates.io/crates/siteone-crawler)] - 一体化
  网站爬虫、审计器、离线归档器和 AI 就绪的 Markdown 导出器，具备 CI/CD 质量门禁
  [![CI](https://github.com/janreges/siteone-crawler/workflows/CI/badge.svg)](https://github.com/janreges/siteone-crawler/actions)
* [konippi/servo-fetch](https://github.com/konippi/servo-fetch) - 自包含的浏览器引擎，可抓取、渲染并将 Web 内容提取为 Markdown、JSON 或截图——无需 Chromium，无需 API 密钥。CLI、Python、MCP 服务器。[![CI](https://github.com/konippi/servo-fetch/actions/workflows/ci.yml/badge.svg)](https://github.com/konippi/servo-fetch/actions/workflows/ci.yml)
* [LemmyNet/lemmy](https://github.com/LemmyNet/lemmy) - 面向联邦宇宙的链接聚合器 / reddit 克隆 [![Build Status](https://cloud.drone.io/api/badges/LemmyNet/lemmy/status.svg)](https://cloud.drone.io/LemmyNet/lemmy)
* [MASQ-Project/Node](https://github.com/MASQ-Project/Node) - MASQ Node 软件提供去中心化的节点网状网络，让全球用户访问正常的互联网内容——超越 Tor 和 VPN 的技术演进 [![build badge](https://github.com/MASQ-Project/Node/actions/workflows/ci-matrix.yml/badge.svg)](https://github.com/MASQ-Project/Node/actions)
* [Plume-org/Plume](https://github.com/Plume-org/Plume) - ActivityPub 联邦博客应用
* [Redlib](https://github.com/redlib-org/redlib) - Reddit 的替代私密前端，源自 [Libreddit](https://github.com/libreddit/libreddit)
* [shouya/rss-funnel](https://github.com/shouya/rss-funnel) - 模块化 RSS 处理管道系统。
* [SinTan1729/Chhoto URL](https://github.com/SinTan1729/chhoto-url) - 简单、极快、自托管的 URL 缩短器，没有多余功能。[![release](https://github.com/SinTan1729/chhoto-url/actions/workflows/docker-release.yml/badge.svg)](https://github.com/SinTan1729/chhoto-url/actions/workflows/docker-release.yml)
* [Stoatchat](https://github.com/stoatchat/stoatchat) - 使用现代 Web 技术构建的用户优先聊天平台。
* [zhom/donutbrowser](https://github.com/zhom/donutbrowser) - 开源反检测浏览器，具备无限隔离配置文件、Chromium/Firefox 引擎、指纹伪装、代理/VPN 支持、本地 API 和 MCP 服务器，以及端到端加密云同步。[![GitHub release](https://img.shields.io/github/v/release/zhom/donutbrowser)](https://github.com/zhom/donutbrowser/releases)

### Web 服务器

* [cloudflare/pingora](https://github.com/cloudflare/pingora) - 用于构建快速、可靠且可演进的网络服务的库。
* [dorianverlaine/pingclair](https://github.com/dorianverlaine/pingclair) - 构建在 Cloudflare Pingora 之上的 Web 服务器和反向代理，提供兼容 Caddyfile 的配置语言、自动 HTTPS、HTTP/1.1、HTTP/2 和 HTTP/3、负载均衡以及静态文件服务。[![CI](https://github.com/dorianverlaine/pingclair/actions/workflows/blocking-ci.yml/badge.svg?branch=main)](https://github.com/dorianverlaine/pingclair/actions/workflows/blocking-ci.yml?query=branch%3Amain)
* [emanuele-em/proxelar](https://github.com/emanuele-em/proxelar) - 一个 MITM 代理 🦀！面向 HTTP/1、HTTP/2 和 WebSockets 的工具包，具备 SSL/TLS 能力 [![Rust](https://github.com/emanuele-em/proxelar/actions/workflows/autofix.yml/badge.svg)](https://github.com/emanuele-em/proxelar/actions)
* [ferronweb/ferron](https://github.com/ferronweb/ferron) - 为生产调试打造的快速、现代 Web 服务器。[![Rust (Ferron 3.x)](https://github.com/ferronweb/ferron/actions/workflows/rust.yml/badge.svg)](https://github.com/ferronweb/ferron/actions/workflows/rust.yml)
* [g3proxy](https://github.com/bytedance/g3) - 正向代理服务器，支持代理链、协议检查、MITM 拦截、ICAP 适配、透明代理 [![CodeCoverage](https://github.com/bytedance/g3/actions/workflows/codecov.yml/badge.svg)](https://github.com/bytedance/g3/actions)
* [hyperlane-dev/hyperlane](https://github.com/hyperlane-dev/hyperlane) [[hyperlane](https://crates.io/crates/hyperlane)] - 构建在 Tokio 之上的轻量级、高性能、跨平台 Rust HTTP 服务器库；内置对中间件、WebSocket、SSE 和原始 TCP 的支持。[![CI](https://github.com/hyperlane-dev/hyperlane/actions/workflows/rust.yml/badge.svg)](https://github.com/hyperlane-dev/hyperlane/actions)
* [Mini RPS](https://github.com/marcodpt/minirps) - 迷你反向代理服务器、HTTPS、CORS、静态文件托管和模板引擎（minijinja） [crates.io](https://crates.io/crates/minirps)
* [mu-arch/skyfolder](https://github.com/mu-arch/skyfolder) - 🪂 美观的 HTTP/BitTorrent 服务器，省去麻烦。安全 - GUI - 漂亮 - 快速
* [mufeedvh/binserve](https://github.com/mufeedvh/binserve) - 极快的静态 Web 服务器，将路由、模板和安全集成在单一二进制文件中，零代码即可设置 [![build badge](https://github.com/mufeedvh/binserve/actions/workflows/build.yml/badge.svg)](https://github.com/mufeedvh/binserve/actions)
* [orhun/rustypaste](https://github.com/orhun/rustypaste) - 极简的文件上传/粘贴板服务 ![https://github.com/orhun/rustypaste/actions](https://img.shields.io/github/actions/workflow/status/orhun/rustypaste/ci.yml?branch=master&label=build)
* [plabayo/rama](https://github.com/plabayo/rama) - 模块化服务框架，用于移动和转换你的网络数据包，用于构建 Web 客户端、服务器，以及——最重要的是——代理
* [ronanyeah/rust-hasura](https://github.com/ronanyeah/rust-hasura) - 演示如何将 GraphQL 服务器用作 [Hasura](https://hasura.io/) 的远程 schema ![Rust](https://github.com/ronanyeah/rust-hasura/workflows/Rust/badge.svg?branch=master)
* [static-web-server](https://github.com/static-web-server/static-web-server) - 用于静态文件服务的极快异步 Web 服务器。⚡ [![CI](https://github.com/static-web-server/static-web-server/actions/workflows/devel.yml/badge.svg)](https://github.com/static-web-server/static-web-server/actions/workflows/devel.yml?query=branch%3Amaster)
* [svenstaro/miniserve](https://github.com/svenstaro/miniserve) - 一个小巧、自包含的跨平台 CLI 工具，让你只需获取二进制文件即可通过 HTTP 提供一些文件 [![build badge](https://github.com/svenstaro/miniserve/workflows/CI/badge.svg?branch=master)](https://github.com/svenstaro/miniserve/actions)
* [thecoshman/http](https://github.com/thecoshman/http) - Host These Things Please——一个基本的 http 服务器，用于快速简单地托管文件夹
* [TheWaWaR/simple-http-server](https://github.com/TheWaWaR/simple-http-server) - 简单的静态 http 服务器
* [vetis-server/vetis](https://github.com/vetis-server/vetis) - 为现代 Rust 应用打造的极快、极简 HTTP 服务器。提供虚拟主机、SNI、静态内容、反向代理、HTTP 1/2/3 以及 Tokio 或 Smol 作为异步运行时！
* [vproxy/0x676e67](https://github.com/0x676e67/vproxy) - 快速的异步 Rust HTTP/Socks5 代理

### 工作流自动化

* [cowork-forge](https://github.com/sopaco/cowork-forge) - AI 原生多代理平台，通过 7 阶段流水线编排专门的代理，将想法转化为生产就绪的软件。[![release](https://img.shields.io/github/actions/workflow/status/sopaco/cowork-forge/rust.yml?label=Build)](https://github.com/sopaco/cowork-forge/actions/workflows/release.yml)
* [dali-benothmen/woml](https://github.com/dali-benothmen/woml) - WOML（工作流编排标记语言）是一种用于工作流自动化的标记语言，具备 Rust 执行核心。像 HTML 一样可读，像代码一样可版本化，像 JavaScript 一样强大——没有可视化构建器的意大利面代码，步骤能力没有上限。[![release](https://github.com/dali-benothmen/woml/actions/workflows/release.yml/badge.svg)](https://github.com/dali-benothmen/woml/actions/workflows/release.yml)
* [SouravRoy-ETL/duckle](https://github.com/SouravRoy-ETL/duckle) - 视觉优先的开源数据工作室（ETL/ELT），完全运行在 DuckDB 上。将源、转换和汇拖到画布上，它会编译为纯 DuckDB SQL；300+ 连接器和内置 MCP 服务器。[![release](https://github.com/SouravRoy-ETL/duckle/actions/workflows/release.yml/badge.svg)](https://github.com/SouravRoy-ETL/duckle/actions/workflows/release.yml)

## 开发工具

* [7df-lab/devo](https://github.com/7df-lab/devo) - 轻量级、模型中立的编码代理，作为单一二进制文件运行。快速、token 高效且高度可定制。[![CI](https://github.com/7df-lab/devo/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/7df-lab/devo/actions/workflows/ci.yml)
* [aaif-goose/goose](https://github.com/aaif-goose/goose) - 开源、本地 AI 代理，自动化工程任务。
* [agavra/tuicr](https://github.com/agavra/tuicr) [[tuicr](https://crates.io/crates/tuicr)] - 具备 vim 键位的代码审查 TUI。连续差异查看器、PR 风格评论，并导出到 GitHub/GitLab/剪贴板。支持 git、jj 和 mercurial。[![Crates.io](https://img.shields.io/crates/v/tuicr)](https://crates.io/crates/tuicr)
* [armgabrielyan/deadbranch](https://github.com/armgabrielyan/deadbranch) [[deadbranch](https://crates.io/crates/deadbranch)] - 安全清理陈旧的 git 分支 [![CI](https://github.com/armgabrielyan/deadbranch/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/armgabrielyan/deadbranch/actions/workflows/ci.yml)
* [astral-sh/uv](https://github.com/astral-sh/uv) [[uv](https://crates.io/crates/uv)] - 用 Rust 编写的极快 Python 包和项目管理器。[![CI](https://github.com/astral-sh/uv/workflows/CI/badge.svg)](https://github.com/astral-sh/uv/actions)
* [ATAC](https://github.com/Julien-cpsn/ATAC) - 用 Rust 制作的功能齐全的 TUI API 客户端。ATAC 免费、开源、离线且无需账户。
* [bacon](https://github.com/Canop/bacon) - 后台 Rust 代码检查器，类似 cargo-watch
* [biome](https://github.com/biomejs/biome) - 面向 Web 项目的工具链，旨在提供维护它们的功能。Biome 提供格式化和 linter，可通过 CLI 和 LSP 使用
* [cachix/devenv](https://github.com/cachix/devenv) - 使用 Nix 的快速、声明式、可复现且可组合的开发者环境 [![CI](https://github.com/cachix/devenv/actions/workflows/release.yml/badge.svg)](https://github.com/cachix/devenv/actions/workflows/release.yml)
* [claudectl](https://github.com/mercurialsolo/claudectl) [[claudectl](https://crates.io/crates/claudectl)] - 面向 Claude Code 的自动驾驶，具备本地 LLM 大脑（ollama/llama.cpp/vLLM），学习自动批准/拒绝工具调用。多会话编排、健康监控、支出控制。[![CI](https://github.com/mercurialsolo/claudectl/actions/workflows/ci.yml/badge.svg)](https://github.com/mercurialsolo/claudectl/actions/workflows/ci.yml)
* [clippy](https://crates.io/crates/clippy) - Rust lint
* [clog-tool/clog-cli](https://github.com/clog-tool/clog-cli) - 从 git 元数据生成变更日志（[约定式变更日志](https://blog.thoughtram.io/announcements/tools/2014/09/18/announcing-clog-a-conventional-changelog-generator-for-the-rest-of-us.html)）
* [cloudflare/foundations](https://github.com/cloudflare/foundations) - Foundations 是一个模块化 Rust 库，旨在帮助为分布式、生产级系统扩展程序。
* [cordx56/rustowl](https://github.com/cordx56/rustowl) [[rustowl](https://crates.io/crates/rustowl)] - 在 Rust 中可视化所有权和生命周期 [![CI](https://github.com/cordx56/rustowl/actions/workflows/checks.yml/badge.svg?branch=main)](https://github.com/cordx56/rustowl/actions/workflows/checks.yml)
* [create-rust-app](https://github.com/Wulf/create-rust-app) - 通过运行一条命令搭建现代 rust+react Web 应用。[![crate](https://img.shields.io/crates/v/create-rust-app.svg)](https://crates.io/crates/create-rust-app)
* [dan-t/rusty-tags](https://github.com/dan-t/rusty-tags) - 为 cargo 项目及其所有依赖创建 ctags/etags
* [datanymizer/datanymizer](https://github.com/datanymizer/datanymizer) - 强大的数据库匿名化工具，具备灵活规则 [![build badge](https://github.com/datanymizer/datanymizer/workflows/CI/badge.svg?branch=main)](https://github.com/datanymizer/datanymizer/actions?query=workflow%3ACI+branch%3Amain)
* [delta](https://crates.io/crates/git-delta) - 面向 git 和 diff 输出的语法高亮器 [![build badge](https://github.com/dandavison/delta/actions/workflows/ci.yml/badge.svg)](https://github.com/dandavison/delta//actions)
* [dotenv-linter](https://github.com/dotenv-linter/dotenv-linter) - `.env` 文件的 linter [![build badge](https://github.com/dotenv-linter/dotenv-linter/actions/workflows/ci.yml/badge.svg)](https://github.com/dotenv-linter/dotenv-linter/actions?query=workflow%3ACI+branch%3Amaster)
* [enroute-sh/enroute](https://github.com/enroute-sh/enroute) - 对象存储上的可编程 git 基础设施
* [envio](https://github.com/humblepenguinn/envio) - 用于管理环境变量的现代且安全的 CLI 工具 [![build badge](https://github.com/humblepenguinn/envio/actions/workflows/CICD.yml/badge.svg?branch=main)](https://github.com/humblepenguinn/envio/actions/workflows/CICD.yml)
* [Feel-ix-343/markdown-oxide](https://github.com/Feel-ix-343/markdown-oxide) - 面向 Neovim、VSCode、Zed、Helix 和 Kakoune 的 PKM Markdown 语言服务器，支持 Obsidian 风格 wikilink、反向链接和每日笔记
* [FerrLabs/FerrFlow](https://github.com/FerrLabs/FerrFlow) [[ferrflow](https://crates.io/crates/ferrflow)] - 由 Conventional Commits 驱动的语义化版本、变更日志和标签发布，具备 monorepo 支持和 16 种版本文件格式 [![build badge](https://github.com/FerrLabs/FerrFlow/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/FerrLabs/FerrFlow/actions/workflows/ci.yml)
* [firelock-ai/kin](https://github.com/firelock-ai/kin) - 面向人类和 AI 代理的图原生代码仓库。Kin 帮助你和你的 AI 代理在做出代码更改之前理解它可能影响什么。
* [Flox](https://github.com/flox/flox) - Flox 是虚拟环境和包管理器二合一。
* [forgecode](https://github.com/tailcallhq/forgecode) - 基于终端的 AI 结对程序员，用于代码生成和编辑。[![Website](https://img.shields.io/badge/website-forgecode.dev-blue)](https://forgecode.dev/)
* [frolic](https://github.com/frolicflow/Frolic) - 用于以快 10 倍的速度构建面向客户仪表板的 API 层
* [fw](https://github.com/brocode/fw) - 工作区生产力助推器 [![Rust](https://github.com/brocode/fw/actions/workflows/rust.yml/badge.svg)](https://github.com/brocode/fw/actions/workflows/rust.yml)
* [fzf-make](https://github.com/kyu08/fzf-make) [[fzf-make](https://crates.io/crates/fzf-make)] - 使用带预览窗口的模糊查找器执行 make 目标的命令行工具。[![crates.io](https://img.shields.io/crates/v/fzf-make?style=flatflat-square)](https://crates.io/crates/fzf-make)
* [geiger](https://github.com/geiger-rs/cargo-geiger) - 列出 crate 及其所有依赖中 unsafe 代码使用相关统计的程序 [![Build Status](https://dev.azure.com/cargo-geiger/cargo-geiger/_apis/build/status/geiger-rs.cargo-geiger?branchName=master)](https://dev.azure.com/cargo-geiger/cargo-geiger/_build/latest?definitionId=1&branchName=master)
* [git-cliff](https://github.com/orhun/git-cliff) - 高度可定制的变更日志生成器，遵循 Conventional Commit 规范 ![https://github.com/orhun/git-cliff/actions](https://img.shields.io/github/actions/workflow/status/orhun/git-cliff/ci.yml?branch=main&label=build)
* [git-journal](https://github.com/saschagrunert/git-journal/) - Git 提交信息和变更日志生成框架
* [git-time-machine](https://github.com/dinakars777/git-time-machine) - 用于撤销 git 错误的可视化 git reflog TUI [![crate](https://img.shields.io/crates/v/git-time-machine.svg)](https://crates.io/crates/git-time-machine) [![build badge](https://github.com/dinakars777/git-time-machine/actions/workflows/rust.yml/badge.svg)](https://github.com/dinakars777/git-time-machine/actions/workflows/rust.yml)
* [GitoxideLabs/gitoxide](https://github.com/GitoxideLabs/gitoxide) [[gix](https://crates.io/crates/gix)] - 纯 Rust Git 实现，具备高性能底层 crate 以及用于 clone、fetch、status、diff、commit、config、refs 等的 CLI 工具。[![CI](https://github.com/GitoxideLabs/gitoxide/workflows/ci/badge.svg)](https://github.com/GitoxideLabs/gitoxide/actions)
* [hot-lib-reloader](https://github.com/rksm/hot-lib-reloader-rs) - 热重载 Rust 代码 [![build badge](https://github.com/rksm/hot-lib-reloader-rs/actions/workflows/ci.yml/badge.svg)](https://github.com/rksm/hot-lib-reloader-rs/actions/workflows/ci.yml)
* [intelli-shell](https://github.com/lasantosr/intelli-shell) - 使用占位符收藏命令，并可随时搜索或自动补全 [![crate](https://img.shields.io/crates/v/intelli-shell.svg)](https://crates.io/crates/intelli-shell) [![build badge](https://github.com/lasantosr/intelli-shell/actions/workflows/release.yml/badge.svg)](https://github.com/lasantosr/intelli-shell/actions/workflows/release.yml)
* [j178/prek](https://github.com/j178/prek) - 用 Rust 编写的、pre-commit 的更快、无依赖、开箱即用替代品。
* [jj-vcs/jj](https://github.com/jj-vcs/jj) - 兼容 Git 的版本控制系统，具备干净的 CLI、一流的冲突处理和自动变基 [![Release](https://img.shields.io/github/v/release/martinvonz/jj)](https://github.com/jj-vcs/jj/releases)
* [just](https://github.com/casey/just) - 用于项目特定任务的便捷命令运行器
* [mask](https://github.com/jacobdeichert/mask) - 由简单 Markdown 文件定义的 CLI 任务运行器 [![build badge](https://github.com/jacobdeichert/mask/workflows/CI/badge.svg?branch=master)](https://github.com/jacobdeichert/mask/actions?query=workflow%3ACI)
* [mise](https://github.com/jdx/mise) [[mise](https://crates.io/crates/mise)] - 多语言工具版本管理器和任务运行器；asdf 的开箱即用替代品，性能更快。[![build badge](https://github.com/jdx/mise/actions/workflows/test.yml/badge.svg)](https://github.com/jdx/mise/actions/workflows/test.yml)
* [Module Linker](https://github.com/fiatjaf/module-linker) - 在 GitHub 上为 `mod`、`use` 和 `extern crate` 语句中的引用添加 `<a>` 链接的扩展。
* [Muvon/octocode](https://github.com/Muvon/octocode) [[octocode](https://crates.io/crates/octocode)] - 语义代码索引器，具备 GraphRAG 知识图谱和 MCP 服务器。Tree-sitter AST 解析、ast-grep 结构搜索、LanceDB 向量存储、代码签名视图。面向 Claude/Cursor/Windsurf 等 AI 助手的 CLI + MCP 服务器模式。[![CI](https://github.com/Muvon/octocode/actions/workflows/ci.yml/badge.svg)](https://github.com/Muvon/octocode/actions/workflows/ci.yml)
* [persiyanov/herdr-reviewr](https://github.com/persiyanov/herdr-reviewr) - 用于审查编码代理差异并将行评论发送回 Claude Code、Codex、OpenCode 或 Pi 的终端窗格。[![CI](https://github.com/persiyanov/herdr-reviewr/actions/workflows/ci.yml/badge.svg)](https://github.com/persiyanov/herdr-reviewr/actions/workflows/ci.yml)
* [prefix-dev/pixi](https://github.com/prefix-dev/pixi) [[pixi](https://crates.io/crates/pixi)] - 面向多语言项目的快速包管理和工作流工具，构建在 conda 生态系统之上。
* [ptags](https://github.com/dalance/ptags) - 面向 git 仓库的并行 universal-ctags 封装
* [Racer](https://github.com/racer-rust/racer) - Rust 代码补全
* [reflex-search/reflex](https://github.com/reflex-search/reflex) [[reflex-search](https://crates.io/crates/reflex-search)] - 面向 AI 编码代理的本地优先全文代码搜索引擎。三元组索引、亚 100ms 查询、MCP 服务器模式、通过 tree-sitter 支持 18 种语言。
* [Rust Search Extension](https://github.com/huhu/rust-search-extension) - 便捷的浏览器扩展，可在地址栏（omnibox）中搜索 crate 和文档。[![Build Status](https://github.com/huhu/rust-search-extension/workflows/build/badge.svg?branch=master)](https://github.com/huhu/rust-search-extension/actions)
* [Rustup](https://github.com/rust-lang/rustup) - Rust 工具链安装器 [![build badge](https://github.com/rust-lang/rustup/actions/workflows/ci.yaml/badge.svg)](https://github.com/rust-lang/rustup/actions)
* [scriptisto](https://github.com/igor-petruk/scriptisto) - 语言无关的"shebang 解释器"，让你能用编译型语言编写单文件脚本。[![Build Status](https://cloud.drone.io/api/badges/igor-petruk/scriptisto/status.svg)](https://cloud.drone.io/igor-petruk/scriptisto)
* [sstraus/tuicommander](https://github.com/sstraus/tuicommander) - 桌面工作区，并行运行多个 AI 编码代理，每个都在自己的 git worktree 中，具备代理状态检测、差异、PR 管理和 MCP 代理中心 [![CI](https://github.com/sstraus/tuicommander/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/sstraus/tuicommander/actions/workflows/ci.yml)
* [Terrain](https://github.com/sopaco/terrain) - AI 原生工程环境管理，让你的代码库为代理就绪。
* [typos](https://github.com/crate-ci/typos) [[typos-cli](https://crates.io/crates/typos-cli)] - 源代码拼写检查器
* [voidzero-dev/vite-plus](https://github.com/voidzero-dev/vite-plus) - 统一的 Web 开发工具链，将 Vite、Vitest、Oxlint、Rolldown 等整合为单一的 Rust 驱动 CLI（`vp`）
* [VT Code](https://crates.io/crates/vtcode) - 终端编码代理，将现代 TUI 与由 tree-sitter 和 ast-grep 驱动的深度语义代码理解相结合。
* [Wilfred/difftastic](https://github.com/Wilfred/difftastic) [[difftastic](https://crates.io/crates/difftastic)] - 理解语法的结构化 diff 工具，支持 30+ 编程语言
* [yvgude/lean-ctx](https://github.com/yvgude/lean-ctx) [[lean-ctx](https://crates.io/crates/lean-ctx)] - 面向 AI 编码代理的上下文运行时：MCP 服务器和 shell 钩子，压缩工具和终端输出以减少 LLM token 使用；Tree-sitter 解析、会话缓存。[![CI](https://github.com/yvgude/lean-ctx/actions/workflows/ci.yml/badge.svg)](https://github.com/yvgude/lean-ctx/actions/workflows/ci.yml)

### 构建系统

* [better-fullstack](https://github.com/Marve10s/Better-Fullstack) - 端到端全栈脚手架工具，支持 Rust（Axum、Actix Web、Leptos、Dioxus、SeaORM、SQLx、tonic、async-graphql）以及 TypeScript、Go 和 Python——代码可为你或你的 AI 代理就绪。
* [Cargo](https://crates.io/) - Rust 包管理器
  * [cargo-all-features](https://github.com/frewsxcv/cargo-all-features) - 可配置的子命令，为所有功能组合简化测试、构建等 [![CI](https://github.com/frewsxcv/cargo-all-features/actions/workflows/ci.yml/badge.svg)](https://github.com/frewsxcv/cargo-all-features/actions/workflows/ci.yml)
  * [cargo-benchcmp](https://crates.io/crates/cargo-benchcmp) - 比较微基准的实用工具
  * [cargo-bins/cargo-binstall](https://github.com/cargo-bins/cargo-binstall) [[cargo-binstall](https://crates.io/crates/cargo-binstall)] - 面向 Rust crate 的快速二进制安装器，获取预构建产物而非从源码编译 [![CI](https://github.com/cargo-bins/cargo-binstall/actions/workflows/ci.yml/badge.svg)](https://github.com/cargo-bins/cargo-binstall/actions)
  * [cargo-bitbake](https://crates.io/crates/cargo-bitbake) - 可生成利用 meta-rust 中类的 BitBake 配方的 cargo 扩展
  * [cargo-cache](https://crates.io/crates/cargo-cache) - 检查/管理/清理你的 cargo 缓存（`~/.cargo/`/`${CARGO_HOME}`），打印大小等 [![Build Status](https://github.com/matthiaskrgr/cargo-cache/workflows/ci/badge.svg?branch=master)](https://github.com/matthiaskrgr/cargo-cache/actions)
  * [cargo-check](https://crates.io/crates/cargo-check) - 对 `cargo rustc -- -Zno-trans` 的封装，如果你只需要正确性检查，有助于更快编译
  * [cargo-commander](https://crates.io/crates/cargo-commander) - `cargo` 的子命令，用于运行 CLI 命令，类似 `package.json` 中 scripts 部分的工作方式 [![Build and test](https://github.com/simonhyll/cargo-commander/actions/workflows/build.yml/badge.svg)](https://github.com/simonhyll/cargo-commander/actions/workflows/build.yml)
  * [cargo-count](https://crates.io/crates/cargo-count) - 列出 cargo 项目的源代码计数和详细信息，包括 unsafe 统计
  * [cargo-deb](https://crates.io/crates/cargo-deb) - 生成二进制 Debian 包
  * [cargo-depgraph](https://crates.io/crates/cargo-depgraph) - 使用 cargo metadata 和 graphviz 为 cargo 项目创建依赖图
  * [cargo-do](https://crates.io/crates/cargo-do) - 连续运行多个 cargo 命令
  * [cargo-ebuild](https://crates.io/crates/cargo-ebuild) - 可使用树内 eclass 生成 ebuild 的 cargo 扩展
  * [cargo-edit](https://crates.io/crates/cargo-edit) - 允许你通过命令行读写 Cargo.toml 文件来添加和列出依赖
  * [cargo-generate](https://github.com/cargo-generate/cargo-generate) - 通过利用已有 git 仓库作为模板来生成 rust 项目。
  * [cargo-info](https://crates.io/crates/cargo-info) - 从命令行查询 crates.io 获取 crate 详情
  * [cargo-license](https://crates.io/crates/cargo-license) - 快速查看所有依赖许可证的 cargo 子命令。
  * [cargo-limit](https://crates.io/crates/cargo-limit) - 更少噪音的 Cargo：在错误修复之前跳过警告、Neovim 集成等。[![build badge](https://github.com/cargo-limit/cargo-limit/actions/workflows/ci.yml/badge.svg)](https://github.com/cargo-limit/cargo-limit/actions)
  * [cargo-machete](https://github.com/bnjbvr/cargo-machete) [[cargo-machete](https://crates.io/crates/cargo-machete)] - 检测 Cargo.toml 中未使用依赖的简单工具。
  * [cargo-make](https://crates.io/crates/cargo-make) - 任务运行器和构建工具。[![build badge](https://github.com/sagiegurari/cargo-make/workflows/CI/badge.svg?branch=master)](https://github.com/sagiegurari/cargo-make/actions)
  * [cargo-modules](https://crates.io/crates/cargo-modules) - 显示 crate 模块树状概览的 cargo 插件。
  * [cargo-multi](https://crates.io/crates/cargo-multi) - 在多个 crate 上运行指定的 cargo 命令
  * [cargo-outdated](https://crates.io/crates/cargo-outdated) - 显示 Rust 依赖何时有更新的版本或已过时
  * [cargo-rdme](https://github.com/orium/cargo-rdme) [[cargo-rdme](https://crates.io/crates/cargo-rdme)] - 从你的 crate 文档创建 README 的 Cargo 子命令。[![build badge](https://github.com/orium/cargo-rdme/workflows/CI/badge.svg)](https://github.com/orium/cargo-rdme/actions?query=workflow%3ACI)
  * [cargo-release](https://crates.io/crates/cargo-release) - 用于发布 git 管理的 cargo 项目的工具，构建、打标签、发布、生成文档和推送 [![Rust](https://github.com/crate-ci/cargo-release/actions/workflows/ci.yml/badge.svg)](https://github.com/crate-ci/cargo-release/actions/workflows/rust.yml)
  * [cargo-script](https://crates.io/crates/cargo-script) - 让人们快速轻松地运行可利用 Cargo 包生态系统的 Rust "脚本"
  * [cargo-udeps](https://github.com/est31/cargo-udeps) [[cargo-udeps](https://crates.io/crates/cargo-udeps)] - 查找未使用的依赖
  * [cargo-update](https://crates.io/crates/cargo-update) - 用于检查和向已安装可执行文件应用更新的 cargo 子命令
  * [cargo-watch](https://crates.io/crates/cargo-watch) - 当源文件变化时编译项目的 cargo 实用工具
  * [dtolnay/cargo-expand](https://github.com/dtolnay/cargo-expand) - 展开源代码中的宏
* CMake
  * [Devolutions/CMakeRust](https://github.com/Devolutions/CMakeRust) - 用于将 Rust 库集成到 CMake 项目
  * [SiegeLord/RustCMake](https://github.com/SiegeLord/RustCMake) - 展示 CMake 与 Rust 配合使用的示例项目
* [euv-cli](https://github.com/euv-dev/euv) [[euv-cli](https://crates.io/crates/euv-cli)] - euv UI 框架的官方 CLI 工具，提供具备 run/build 模式的 dev/release 配置文件、热重载和 wasm-pack 集成。
* [facebook/buck2](https://github.com/facebook/buck2) - [Buck2](https://buck2.build/) 是用 Rust 构建的大规模构建工具
* [Fleet](https://github.com/suptejas/fleet) [[fleet-rs](https://crates.io/crates/fleet-rs)] - 极快的 Rust 构建工具。
* GitHub actions
  * [icepuma/rust-action](https://github.com/icepuma/rust-action) - rust github action
* [Nix](https://nixos.org/)
  * [nix-community/fenix](https://github.com/nix-community/fenix) - 面向 nix 的 Rust 工具链和 rust analyzer nightly [![build-badge](https://github.com/nix-community/fenix/actions/workflows/ci.yml/badge.svg)](https://github.com/nix-community/fenix/actions/workflows/ci.yml)
* [pantsbuild/pants](https://github.com/pantsbuild/pants) - [Pants](https://www.pantsbuild.org/) 是用 Rust 构建的快速、可扩展、用户友好的构建系统，适用于各种规模的代码库。
* [rolldown/rolldown](https://github.com/rolldown/rolldown) - 用 Rust 编写的 JavaScript/TypeScript 打包器，旨在成为 Vite 的未来打包器。
* [rui314/mold](https://github.com/rui314/mold) - 面向 Linux、macOS 和 Windows（ELF、Mach-O、PE）的现代高速链接器
* [tracemachina/nativelink](https://github.com/TraceMachina/nativelink) - [NativeLink](https://nativelink.com) 是用 rust 编写的后端远程执行平台，面向 [Buck2](https://buck2.build/)、[Bazel](https://bazel.build/)、[Pants](https://www.pantsbuild.org/) 等客户端构建系统。[![OpenSSF Scorecard](https://api.securityscorecards.dev/projects/github.com/TraceMachina/nativelink/badge)](https://securityscorecards.dev/viewer/?uri=github.com/TraceMachina/nativelink) [![OpenSSF Best Practices](https://www.bestpractices.dev/projects/8050/badge)](https://www.bestpractices.dev/projects/8050)
* [vercel/turborepo](https://github.com/vercel/turborepo) - 用 Rust 编写的、面向 JavaScript 和 TypeScript monorepo 的高性能构建系统。具备增量计算、远程缓存和并行任务执行。
* [wislertt/zerv](https://github.com/wislertt/zerv) [[zerv](https://crates.io/crates/zerv)] - 动态版本工具，从任何 Git 状态为每次构建生成版本，输出 SemVer、PEP 440 和 CalVer [![CI](https://github.com/wislertt/zerv/actions/workflows/cd.yml/badge.svg?branch=main)](https://github.com/wislertt/zerv/actions/workflows/cd.yml)

### 调试

* GDB
  * [gdbgui](https://github.com/cs01/gdbgui) - 基于浏览器的 gdb 前端，用于调试 C、C++、Rust 和 go。
* [godzie44/BugStalker](https://github.com/godzie44/BugStalker) - 面向 Linux x86-64 的现代调试器。用 Rust 编写，用于 Rust 程序。
* [kxxt/tracexec](https://github.com/kxxt/tracexec) [[tracexec](https://crates.io/crates/tracexec)] - 用于 execve{,at} 和执行前行为的追踪器，调试器的启动器。
* LLDB
  * [CodeLLDB](https://marketplace.visualstudio.com/items?itemName=vadimcn.vscode-lldb) - 面向 [Visual Studio Code](https://code.visualstudio.com/) 的 LLDB 扩展。

### 部署

* Docker
  * [emk/rust-musl-builder](https://github.com/emk/rust-musl-builder) - 使用 musl-libc 和 musl-gcc 编译静态 Rust 二进制文件的 Docker 镜像，附带有用 C 库的静态版本
  * [kpcyrd/mini-docker-rust](https://github.com/kpcyrd/mini-docker-rust) - 用于极小 rust docker 镜像的示例项目
  * [lenra-io/dofigen](https://github.com/lenra-io/dofigen) [[dofigen](https://crates.io/crates/dofigen/)] - 使用 YAML 或 JSON 格式简化描述生成 Dockerfile 的生成器 ![Rust CI](https://github.com/lenra-io/dofigen/actions/workflows/build_ci.yml/badge.svg)
  * [liuchong/docker-rustup](https://github.com/liuchong/docker-rustup) - 多版本（带 musl 工具）Rust Docker 镜像
  * [LukeMathWalker/cargo-chef](https://github.com/LukeMathWalker/cargo-chef) - 用于在 Docker 构建之间缓存编译远程依赖的工具和预构建镜像。
  * [moghtech/komodo](https://github.com/moghtech/komodo) - 用于在许多服务器上构建和部署软件的工具，具备 Web UI、API，且无服务器数量限制
  * [rust-cross/rust-musl-cross](https://github.com/rust-cross/rust-musl-cross) - 使用 musl-cross 编译静态 Rust 二进制文件的 Docker 镜像 [![Build](https://github.com/rust-cross/rust-musl-cross/workflows/Build/badge.svg)](https://github.com/rust-cross/rust-musl-cross/actions?query=workflow%3ABuild)
  * [rust-lang/docker-rust](https://github.com/rust-lang/docker-rust) - 官方 Rust Docker 镜像
  * [Stavrospanakakis/is_ready](https://github.com/Stavrospanakakis/is_ready) - 等待多个服务可用 ![Build](https://github.com/Stavrospanakakis/is_ready/actions/workflows/release.yml/badge.svg)
* Heroku
  * [emk/heroku-buildpack-rust](https://github.com/emk/heroku-buildpack-rust) - 面向 Heroku 上 Rust 应用的 buildpack
* [release-plz](https://github.com/release-plz/release-plz) [[release-plz](https://crates.io/crates/release-plz)] - 从 CI 发布 crate，具备变更日志生成和 semver 检查。[![build badge](https://github.com/release-plz/release-plz/workflows/CI/badge.svg)](https://github.com/release-plz/release-plz/actions)

### 嵌入式

[Rust Embedded](https://rust-embedded.org/) 专注于改善在资源受限环境和非传统平台上使用 Rust 的端到端体验。参见 [awesome-embedded-rust](https://github.com/rust-embedded/awesome-embedded-rust) 获取精选且更详尽的嵌入式 Rust 资源列表。

* Arduino
  * [avr-rust/ruduino](https://github.com/avr-rust/ruduino) - 面向 Arduino Uno 的可复用组件。
* Cross compiling
  * [japaric/rust-cross](https://github.com/japaric/rust-cross) - 关于交叉编译 Rust 程序你需要知道的一切
  * [japaric/xargo](https://github.com/japaric/xargo) - 轻松将 Rust 程序交叉编译到 ARM Cortex-M 等自定义裸机目标
* Development Tools
  * [matheuswhite/scope-rs](https://github.com/matheuswhite/scope-rs) [[scope-monitor](https://crates.io/crates/scope-monitor)] - 跨平台串口和 RTT 监控 TUI，具备 hex/@tag 输入宏、搜索、会话录制和 Lua 插件。[![Build Status](https://github.com/matheuswhite/scope-rs/actions/workflows/build.yml/badge.svg)](https://github.com/matheuswhite/scope-rs/actions)
  * [probe-rs/probe-rs](https://github.com/probe-rs/probe-rs) [[probe-rs-tools](https://crates.io/crates/probe-rs-tools)] - 用于烧录和调试 ARM 和 RISC-V 微控制器的嵌入式调试工具包。
  * [Vaishnav-Sabari-Girish/ComChan](https://github.com/Vaishnav-Sabari-Girish/ComChan) - 具备绘图器 TUI 的极简串口监视器。
* Espressif
  * [esp-rs](https://github.com/esp-rs) - 众多社区项目的所在地，这些项目使 Rust 编程语言能够用于 Espressif Systems 生产的各种 SoC 和模块。
* Firmware
  * [oreboot/oreboot](https://github.com/oreboot/oreboot) - oreboot 是 coreboot 的分支，移除了 C，用 Rust 编写
* nRF
  * [nrf-rs/nrf-hal](https://github.com/nrf-rs/nrf-hal) - 面向 nRF 系列设备的 Rust HAL

### FFI

另见[外部函数接口](https://doc.rust-lang.org/book/first-edition/ffi.html)、[The Rust FFI Omnibus](http://jakegoulding.com/rust-ffi-omnibus/)（从其他语言使用 Rust 编写的代码的示例集合）以及[用 Rust 编写的 FFI 示例](https://github.com/alexcrichton/rust-ffi-examples)。

* C
  * [gtk-rs/gir](https://github.com/gtk-rs/gir) - 从基于 GObject 的 C 库创建安全 Rust 绑定的代码生成器。
  * [mozilla/cbindgen](https://github.com/mozilla/cbindgen) - 从 Rust 源文件生成 C 头文件。在 Gecko 中用于 WebRender
  * [Sean1708/rusty-cheddar](https://github.com/Sean1708/rusty-cheddar) - 从 Rust 源文件生成 C 头文件
  * [trevyn/librclone](https://github.com/trevyn/librclone) [[librclone](https://crates.io/crates/librclone)] - librclone C 库的 Rust 绑定。
* C#
  * [csbindgen](https://github.com/Cysharp/csbindgen) - 为 Rust 源文件生成 C# 绑定
* C++
  * [dtolnay/cxx](https://github.com/dtolnay/cxx) - Rust 和 C++ 之间的安全互操作 [![build badge](https://img.shields.io/badge/github-dtolnay/cxx-8da0cb?style=for-the-badge&labelColor=555555&logo=github)](https://github.com/dtolnay/cxx)
  * [rust-cpp](https://crates.io/crates/cpp) - 直接在 Rust 中嵌入 C++ 代码。[![Build status](https://ci.appveyor.com/api/projects/status/uu76vmcrwnjqra0u/branch/master?svg=true)](https://ci.appveyor.com/project/mystor/rust-cpp/branch/master)
  * [rust-lang/rust-bindgen](https://github.com/rust-lang/rust-bindgen) - Rust 绑定生成器
* Erlang
  * [rusterlium/rustler](https://github.com/rusterlium/rustler) - 用于创建 Erlang NIF 函数的安全 Rust 桥
* Java
  * [bennettanderson/rjni](https://github.com/benanders/rjni) - 从 Rust 使用 Java
  * [drrb/java-rust-example](https://github.com/drrb/java-rust-example) - 从 Java 使用 Rust
  * [j4rs](https://crates.io/crates/j4rs) - 从 Rust 使用 Java
  * [jni](https://crates.io/crates/jni) - 从 Java 使用 Rust
  * [jni-sys](https://crates.io/crates/jni-sys) - 对应 jni.h 的 Rust 定义
  * [rucaja](https://crates.io/crates/rucaja) - 从 Rust 使用 Java
* Lua
  * [jcmoyer/rust-lua53](https://github.com/jcmoyer/rust-lua53) - 面向 Rust 的 Lua 5.3 绑定
  * [lilyball/rust-lua](https://github.com/lilyball/rust-lua) - 到 Lua 5.1 的安全 Rust 绑定
  * [mlua-rs/mlua](https://github.com/mlua-rs/mlua) - 到 Rust 的高级 Lua 5.4/5.3/5.2/5.1（包括 LuaJIT）和 Roblox Luau 绑定，支持 async/await [![build badge](https://github.com/mlua-rs/mlua/workflows/CI/badge.svg)](https://github.com/mlua-rs/mlua/actions)
  * [tickbh/td_rlua](https://github.com/tickbh/td_rlua) [[td_rlua](https://crates.io/crates/td_rlua)] - 面向 Rust 的零成本高级 lua 5.3 封装
  * [tomaka/hlua](https://github.com/tomaka/hlua) - 与 Lua 交互的 Rust 库
* mruby
  * [anima-engine/mrusty](https://github.com/anima-engine/mrusty) - 面向 Rust 的 mruby 安全绑定
* Node.js
  * [infinyon/node-bindgen](https://github.com/infinyon/node-bindgen) - 使用 Rust 生成 nodejs 模块的简便方式
  * [neon-bindings/neon](https://github.com/neon-bindings/neon) - 用于编写安全快速的本地 Node.js 模块的 Rust 绑定
  * [zhangyuang/node-ffi-rs](https://github.com/zhangyuang/node-ffi-rs) - 用 Rust 和 N-API 编写的模块，为 Node.js 提供接口（FFI）功能
* Objective-C
  * [SSheldon/rust-objc](https://github.com/SSheldon/rust-objc) - 面向 Rust 的 Objective-C 运行时绑定和封装
* PHP
  * [phper-framework/phper](https://github.com/phper-framework/phper) - 允许我们在尽可能的情况下使用纯安全 Rust 编写 PHP 扩展的框架
* Prolog
  * [mthom/scryer-prolog](https://github.com/mthom/scryer-prolog/) - Scryer Prolog 是用 Rust 编写的自由软件 ISO Prolog 系统
* Python
  * [dgrunwald/rust-cpython](https://github.com/dgrunwald/rust-cpython) - Python 绑定
  * [getsentry/milksnake](https://github.com/getsentry/milksnake) - python setuptools 的扩展，允许你以可想象的最可移植方式在 Python wheel 中分发动态链接库。
  * [PyO3/PyO3](https://github.com/PyO3/PyO3) - Python 解释器的 Rust 绑定
  * [RustPython](https://github.com/RustPython/RustPython) - 用 Rust 编写的 Python 解释器 [![Build Status](https://github.com/RustPython/RustPython/workflows/CI/badge.svg)](https://github.com/RustPython/RustPython/actions?query=workflow%3ACI)
* Ruby
  * [d-unsed/ruru](https://github.com/d-unsed/ruru) - 用 Rust 编写的原生 Ruby 扩展
  * [danielpclark/rutie](https://github.com/danielpclark/rutie) - 用 Rust 编写的原生 Ruby 扩展，反之亦然
* Web Assembly
  * [rhysd/wain](https://github.com/rhysd/wain) - wain：用安全 Rust 从零编写、零依赖的 WebAssembly 解释器 [![build badge](https://github.com/rhysd/wain/workflows/CI/badge.svg?branch=master&event=push)](https://github.com/rhysd/wain/actions?query=workflow%3ACI+branch%3Amaster+event%3Apush)
  * [wasm-bindgen](https://github.com/wasm-bindgen/wasm-bindgen) - 促进 wasm 模块和 JS 之间高级交互的项目。
  * [wasm-pack](https://github.com/wasm-bindgen/wasm-pack) - :package: :sparkles: 打包 wasm 并发布到 npm！

### 格式化工具

* [astral-sh/ruff](https://github.com/astral-sh/ruff) - 极快的 Python linter 和代码格式化器 [![Actions status](https://github.com/astral-sh/ruff/workflows/CI/badge.svg)](https://github.com/astral-sh/ruff/actions)
* [dprint](https://github.com/dprint/dprint) - 可插拔且可配置的代码格式化平台 [![build badge](https://github.com/dprint/dprint/workflows/CI/badge.svg)](https://github.com/dprint/dprint/actions?query=workflow%3ACI)
* [Prettier Rust](https://github.com/jinxdash/prettier-plugin-rust) - 有主见的 Rust 代码格式化器，可自动修复错误语法（[Prettier](https://prettier.io/) 社区插件）
* [rustfmt](https://github.com/rust-lang/rustfmt) - 由 Rust 团队维护并包含在 cargo 中的 Rust 代码格式化器
* [rvben/rumdl](https://github.com/rvben/rumdl) [[rumdl](https://crates.io/crates/rumdl)] - 用 Rust 编写的快速 Markdown linter 和格式化器 [![CI](https://github.com/rvben/rumdl/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/rvben/rumdl/actions/workflows/ci.yml)

### IDE

另见 [Rust 工具](https://rust-lang.org/tools/)。

  * [Eclipse](https://www.eclipse.org/)
    * [Eclipse Corrosion](https://github.com/eclipse-corrosion/corrosion) - Eclipse IDE 的 Rust 开发插件，通过与 Rust Analyzer 语言服务器、Cargo 运行器和 gdb 调试器集成，提供丰富的编辑体验
  * [Emacs](https://www.gnu.org/software/emacs/)
    * [emacs-racer](https://github.com/racer-rust/emacs-racer) - 自动补全（另见 [company](https://company-mode.github.io) 和 [auto-complete](https://github.com/auto-complete/auto-complete)）
    * [flycheck-rust](https://github.com/flycheck/flycheck-rust) - 面向 [Flycheck](https://github.com/flycheck/flycheck) 的 Rust 支持
    * [rust-mode](https://github.com/rust-lang/rust-mode) - Rust 主模式
    * [rustic](https://github.com/emacs-rustic/rustic) - 面向 Emacs 的 Rust 开发环境 [![build badge](https://github.com/emacs-rustic/rustic/workflows/CI/badge.svg)](https://github.com/emacs-rustic/rustic/actions?query=workflow%3ACI)
  * [gitpod.io](https://gitpod.io) - 基于 Rust Language Server 的、完全支持 Rust 的在线 IDE
  * [gnome-builder](https://wiki.gnome.org/Apps/Builder) - 自 3.22.2 版本起原生支持 rust 和 cargo
  * [IntelliJ](https://www.jetbrains.com/idea/)
    * [intellij-rust/intellij-rust](https://github.com/intellij-rust/intellij-rust) - 面向 IntelliJ 平台的 Rust 插件
  * [Kakoune](http://kakoune.org/)
    * [kakoune-lsp](https://github.com/kakoune-lsp/kakoune-lsp/) - [LSP](https://microsoft.github.io/language-server-protocol/) 客户端。用 Rust 实现，开箱即用支持 rls。
  * [lapce](https://github.com/lapce/lapce) - 用 Rust 编写的极快且强大的代码编辑器。[![build badge](https://github.com/lapce/lapce/actions/workflows/release.yml/badge.svg)](https://github.com/lapce/lapce/actions/workflows/release.yml)
  * [Ride](https://github.com/madeso/ride) - Rust IDE
  * [RustRover](https://www.jetbrains.com/rust/) - JetBrains 出品的强大 Rust IDE，个人非商业使用免费
  * [Sublime Text](https://www.sublimetext.com/)
    * [rust-lang/rust-enhanced](https://github.com/rust-lang/rust-enhanced) - 官方 Rust 包
  * [Vim](https://vim.sourceforge.io/) - 无处不在的文本编辑器
    * [autozimu/LanguageClient-neovim](https://github.com/autozimu/LanguageClient-neovim) - [LSP](https://microsoft.github.io/language-server-protocol/) 客户端。用 Rust 实现，开箱即用支持 rls。
    * [cargo.nvim](https://github.com/nwiizo/cargo.nvim) - 与 Cargo 命令无缝集成的 Neovim 插件。
    * [crates.nvim](https://github.com/Saecki/crates.nvim) - 帮助管理 crates.io 依赖的插件。
    * [rust.vim](https://github.com/rust-lang/rust.vim) - 提供文件检测、语法高亮、格式化、Syntastic 集成等。
    * [vim-racer](https://github.com/racer-rust/vim-racer) - 允许 vim 使用 [Racer](https://github.com/racer-rust/racer) 进行 Rust 代码补全和导航。
  * Visual Studio
    * [PistonDevelopers/VisualRust](https://github.com/PistonDevelopers/VisualRust) - 面向 Rust 的 Visual Studio 扩展 [![Build status](https://ci.appveyor.com/api/projects/status/5nw5no10jj0y4p3f?svg=true)](https://ci.appveyor.com/project/vosen/visualrust)
  * [Visual Studio Code](https://code.visualstudio.com/)
    * [CodeLLDB](https://marketplace.visualstudio.com/items?itemName=vadimcn.vscode-lldb) - LLDB 扩展
    * [Dependi](https://marketplace.visualstudio.com/items?itemName=fill-labs.dependi) - 轻松管理你的依赖
    * [Even Better TOML](https://marketplace.visualstudio.com/items?itemName=tamasfe.even-better-toml) - vscode 中的 TOML 支持
    * [Prettier - Code formatter (Rust)](https://marketplace.visualstudio.com/items?itemName=jinxdash.prettier-rust) - 有主见的 Rust 代码格式化器，可自动修复错误语法（[Prettier](https://prettier.io/) 社区插件）
    * [rust-analyzer](https://marketplace.visualstudio.com/items?itemName=rust-lang.rust-analyzer) - RLS 的替代 rust 语言服务器

### 性能分析

* [Bencher](https://github.com/bencherdev/bencher) - 一套持续基准测试工具，旨在在 CI 中捕获性能回归
* [bheisler/criterion.rs](https://github.com/bheisler/criterion.rs) - 统计驱动的基准测试库
* [Bytehound](https://github.com/koute/bytehound) - 面向 Linux 的内存分析器
* [cong-or/hud](https://github.com/cong-or/hud) - 找出阻塞你的 Tokio 运行时的原因。零埋点 eBPF 分析器。
* [Divan](https://github.com/nvzqz/divan) - 简单但强大的基准测试库，具备分配分析
* [ellisonch/rust-stopwatch](https://github.com/ellisonch/rust-stopwatch) - 秒表库
* FlameGraphs
  * [llogiq/flame](https://github.com/llogiq/flame) - 面向 rust 的侵入式火焰图分析工具
* [g3bench](https://github.com/bytedance/g3) - 支持 HTTP 1.x、HTTP 2、HTTP 3、TLS 握手、DNS 和 Cloudflare Keyless 的基准测试工具
* [pawurb/hotpath](https://github.com/pawurb/hotpath-rs) - 简单的分析器，精确显示你的代码在何处花费时间和分配 [![GH Actions](https://github.com/pawurb/hotpath-rs/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/pawurb/hotpath-rs/actions)
* [sharkdp/hyperfine](https://github.com/sharkdp/hyperfine) - 命令行基准测试工具

### 服务

* [deepwiki-rs](https://github.com/sopaco/deepwiki-rs) - 将你的代码库转化为专业的架构文档。[![crates.io](https://img.shields.io/crates/v/deepwiki-rs?logo=rust)](https://crates.io/crates/deepwiki-rs)
* [deps.rs](https://github.com/deps-rs/deps.rs) - 检测过时或不安全的依赖
* [docs.rs](https://docs.rs) - crate 的自动文档生成

### 静态分析

[[assert](https://crates.io/keywords/assert), [static](https://crates.io/keywords/static)]

* [cargo-coupling](https://github.com/nwiizo/cargo-coupling) - 使用 Vlad Khononov 的 "Balancing Coupling in Software Design" 框架的 Rust 耦合分析工具
* [creusot-rs/creusot](https://github.com/creusot-rs/creusot) - 面向 Rust 的演绎验证器，通过将代码翻译到 Why3 验证平台来证明不存在 panic、溢出和断言失败
* [dupehound](https://github.com/Rafaelpta/dupehound) [[dupehound](https://crates.io/crates/dupehound)] - 重复代码检测器，对函数体进行指纹识别（winnowing），因此副本在重命名后仍能被识别。仓库 slop 评分、重复历史图表，以及指向可复用原始函数的 CI 门禁。支持 Rust 和其他 11 种语言。[![CI](https://github.com/Rafaelpta/dupehound/actions/workflows/ci.yml/badge.svg)](https://github.com/Rafaelpta/dupehound/actions/workflows/ci.yml)
* [kucherenko/jscpd](https://github.com/kucherenko/jscpd) [[jscpd](https://crates.io/crates/jscpd)] - 源代码复制/粘贴检测器，可在 220+ 文件格式中查找重复块 [![CI](https://github.com/kucherenko/jscpd/actions/workflows/rust.yml/badge.svg?branch=master)](https://github.com/kucherenko/jscpd/actions/workflows/rust.yml)
* [MIRAI](https://github.com/endorlabs/mirai) - 对 Rust 的中级中间表示（MIR）进行操作的抽象解释器 [![Continuous Integration](https://github.com/endorlabs/mirai/actions/workflows/rust.yml/badge.svg)](https://github.com/endorlabs/mirai/actions/workflows/rust.yml)
* [MykytaStel/repopilot](https://github.com/MykytaStel/repopilot) [[repopilot](https://crates.io/crates/repopilot)] - 对 Git 变更（包括 AI 代理编辑）进行本地、确定性的审查：被削弱的测试和检查、因移除 API 而破坏的调用方，以及有风险的边界变更；CLI、MCP 服务器和代理钩子 [![CI](https://github.com/MykytaStel/repopilot/actions/workflows/ci.yaml/badge.svg?branch=main)](https://github.com/MykytaStel/repopilot/actions/workflows/ci.yaml)
* [RAPx](https://github.com/safer-rust/RAPx) - 帮助 Rust 程序员开发和使用的、超越 rustc 编译器所提供的先进静态分析工具的平台。
* [static_assertions](https://crates.io/crates/static_assertions) - 编译时断言，确保满足不变量
* [tupe12334/linecheck](https://github.com/tupe12334/linecheck) [[linecheck](https://crates.io/crates/linecheck)] - 强制每文件行数限制，具备按 glob 的警告/错误阈值和 CI 友好的退出码，使过大的文件构建失败 [![CI](https://github.com/tupe12334/linecheck/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/tupe12334/linecheck/actions/workflows/ci.yml)
* [verus-lang/verus](https://github.com/verus-lang/verus) - 面向底层系统代码的已验证 Rust
* [zizmorcore/zizmor](https://github.com/zizmorcore/zizmor) [[zizmor](https://crates.io/crates/zizmor)] - 面向 GitHub Actions 的静态分析工具，可发现包括模板注入、凭据泄漏、过度权限和冒充提交在内的安全问题。[![CI](https://github.com/zizmorcore/zizmor/actions/workflows/ci.yml/badge.svg)](https://github.com/zizmorcore/zizmor/actions/workflows/ci.yml)

### 测试

[[test](https://crates.io/keywords/test), [testing](https://crates.io/keywords/testing)]
* Assertions and Matchers
  * [googletest-json-serde](https://crates.io/crates/googletest-json-serde) [![Latest Version](https://img.shields.io/crates/v/googletest-json-serde.svg)](https://crates.io/crates/googletest-json-serde) - 面向 googletest-rust 的 JSON 匹配器集合，支持路径、数组和对象。[![Build Status](https://github.com/chege/googletest-json-serde/actions/workflows/ci.yaml/badge.svg)](https://github.com/chege/googletest-json-serde/actions)
* Code Coverage
  * [minikin/cargo-crap](https://github.com/minikin/cargo-crap) [[cargo-crap](https://crates.io/crates/cargo-crap)] - 通过结合圈复杂度和 LCOV 覆盖率（CRAP 指标）查找复杂、未经测试的函数，并以评分作为 CI 门禁
  * [supercorp-ai/supercov](https://github.com/supercorp-ai/supercov) [[supercov](https://crates.io/crates/supercov)] - 面向编码代理的代码质量和测试覆盖率：Jev 为每个源文件评分，让代理知道先修复什么 [![CI](https://github.com/supercorp-ai/supercov/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/supercorp-ai/supercov/actions)
  * [tarpaulin](https://crates.io/crates/cargo-tarpaulin) - 代码覆盖率工具
* Continuous Integration
  * [trust](https://github.com/japaric/trust) - 在 5 种架构上测试你的 Rust crate 并为其发布 Linux、macOS 和 Windows 二进制版本的 Travis CI 和 AppVeyor 模板
* Frameworks and Runners
  * [AlKass/polish](https://github.com/AlKass/polish) - 迷你测试/测试驱动框架 [![Crates Package Status](https://img.shields.io/crates/v/polish.svg)](https://crates.io/crates/polish)
  * [bitfield/cargo-testdox](https://github.com/bitfield/cargo-testdox) [[cargo-testdox](https://crates.io/crates/cargo-testdox)] - 将你的 Rust 测试变成文档 [![CI](https://github.com/bitfield/cargo-testdox/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/bitfield/cargo-testdox/actions/workflows/ci.yml)
  * [cargo-dinghy](https://crates.io/crates/cargo-dinghy/) - 简化在智能手机和其他小型处理器设备上运行库测试和基准的 cargo 扩展。
  * [cucumber](https://crates.io/crates/cucumber) [![Latest Version](https://img.shields.io/crates/v/cucumber.svg)](https://crates.io/crates/cucumber) - 面向 Rust 的 Cucumber 测试框架实现。完全原生，无外部测试运行器或依赖。[![Build Status](https://github.com/cucumber-rs/cucumber/actions/workflows/ci.yml/badge.svg)](https://github.com/cucumber-rs/cucumber/actions)
  * [d-e-s-o/test-log](https://github.com/d-e-s-o/test-log) [[test-log](https://crates.io/crates/test-log)] - `#[test]` 属性的替代品，在运行测试前初始化日志和/或追踪基础设施。[![GitHub Workflow Status](https://github.com/d-e-s-o/test-log/actions/workflows/test.yml/badge.svg?branch=main)](https://github.com/d-e-s-o/test-log/actions/workflows/test.yml)
  * [demonstrate](https://crates.io/crates/demonstrate) - 声明式测试框架
  * [GoogleTest Rust](https://crates.io/crates/googletest) - 基于 C++ 测试库 GoogleTest 的强大测试断言框架 [![Build Status](https://github.com/google/googletest-rust/workflows/CI/badge.svg)](https://github.com/google/googletest-rust/actions?query=workflow%3ACI+branch%3Amain)
  * [hovinen/test-that](https://github.com/hovinen/test-that) [[test-that](https://crates.io/crates/test-that)] - 面向 Rust 的断言库，基于 GoogleTest Rust，出自其原作者。[![Build Status](https://github.com/hovinen/test-that/actions/workflows/ci.yml/badge.svg)](https://github.com/hovinen/test-that/actions?query=workflow%3ACI+branch%3Amain)
  * [mitsuhiko/insta](https://github.com/mitsuhiko/insta) [[insta](https://crates.io/crates/insta)] - 面向 Rust 的快照测试库。[![Build Status](https://github.com/mitsuhiko/insta/workflows/Tests/badge.svg)](https://github.com/mitsuhiko/insta/actions)
  * [nextest-rs/nextest](https://github.com/nextest-rs/nextest) [[cargo-nextest](https://crates.io/crates/cargo-nextest)] - 面向 Rust 的下一代测试运行器，具备并行测试执行、更快的测试运行、高级过滤和丰富输出。[![cargo-nextest on crates.io](https://img.shields.io/crates/v/cargo-nextest)](https://crates.io/crates/cargo-nextest)
  * [padamson/playwright-rust](https://github.com/padamson/playwright-rust) [[playwright-rs](https://crates.io/crates/playwright-rs)] - Microsoft Playwright 的 Rust 绑定：跨浏览器端到端测试（Chromium、Firefox、WebKit），具备自动等待定位器和追踪捕获。[![CI](https://github.com/padamson/playwright-rust/actions/workflows/test.yml/badge.svg?branch=main)](https://github.com/padamson/playwright-rust/actions/workflows/test.yml)
  * [palfrey/serial_test](https://github.com/palfrey/serial_test) [[serial_test](https://crates.io/crates/serial_test)] - 串行运行测试，可整体或按命名分组 [![CI](https://github.com/palfrey/serial_test/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/palfrey/serial_test/actions/workflows/ci.yml)
  * [rlt](https://github.com/wfxr/rlt) - 通用负载测试框架，具备实时 tui 支持。
  * [rstest](https://crates.io/crates/rstest) - 基于 fixture 的测试框架 [![Build Status](https://github.com/la10736/rstest/workflows/Test/badge.svg?branch=master)](https://github.com/la10736/rstest/actions)
  * [speculate](https://crates.io/crates/speculate) - 受 RSpec 启发的极简测试框架
* Mocking and Test Data
  * [asomers/mockall](https://github.com/asomers/mockall) [[mockall](https://crates.io/crates/mockall)] - 强大的 mock 对象库。[![CI](https://github.com/asomers/mockall/actions/workflows/ci.yml/badge.svg)](https://github.com/asomers/mockall/actions/workflows/ci.yml)
  * [bcheidemann/fixtures-rs](https://github.com/bcheidemann/fixtures-rs/tree/main/fixtures) [[fixtures](https://crates.io/crates/fixtures)] - 使用 glob 模式从 fixture 生成测试的过程宏
  * [cmccomb/hodgepodge](https://github.com/cmccomb/hodgepodge) [[hodgepodge](https://crates.io/crates/hodgepodge)] - 现成的枚举数据集和可选的动物分类，用于原型、测试和教学
  * [fake-rs](https://github.com/cksac/fake-rs) - 生成假数据的库
  * [goldenfile](https://github.com/calder/rust-goldenfile) [[goldenfile](https://crates.io/crates/goldenfile)] - 提供用于 goldenfile 测试的简单 API 的库。
  * [httpmock](https://github.com/httpmock/httpmock) - HTTP mock [![Build](https://github.com/httpmock/httpmock/actions/workflows/build.yml/badge.svg)](https://github.com/httpmock/httpmock/actions/workflows/build.yml)
  * [mockiato](https://crates.io/crates/mockiato) - 面向不稳定的 Rust 2018 的严格但友好的 mock 库
  * [mockito](https://crates.io/crates/mockito) - HTTP mock
  * [mocktail](https://github.com/IBM/mocktail) [![mocktail](https://img.shields.io/crates/v/mocktail)](https://crates.io/crates/mocktail) - 面向 Rust 的 HTTP 和 gRPC 服务器 mock ![build](https://github.com/IBM/mocktail/actions/workflows/build.yml/badge.svg)
  * [nrxus/faux](https://github.com/nrxus/faux/) [![Latest Version](https://img.shields.io/crates/v/faux.svg)](https://crates.io/crates/faux) - 从结构体创建 mock 的库。![build](https://github.com/nrxus/faux/workflows/test/badge.svg?branch=master)
  * [synth](https://github.com/shuttle-hq/synth/) - 声明式生成数据库数据。[![build](https://github.com/shuttle-hq/synth/actions/workflows/synth-test.yml/badge.svg)](https://github.com/shuttle-hq/synth)
* Mutation Testing
  * [cargo-mutants](https://github.com/sourcefrog/cargo-mutants) [[cargo-mutants](https://crates.io/crates/cargo-mutants)] - 通过注入变异来查找测试不充分的代码，无需更改源代码。[![build badge](https://github.com/sourcefrog/cargo-mutants/actions/workflows/tests.yml/badge.svg?branch=main&event=push)](https://github.com/sourcefrog/cargo-mutants/actions/workflows/tests.yml?query=branch%3Amain)
  * [mutagen](https://github.com/llogiq/mutagen) [[mutagen](https://crates.io/crates/mutagen)] - 源码级变异测试框架（仅 nightly）
* Property Testing and Fuzzing
  * [Ackee-Blockchain/trident](https://github.com/Ackee-Blockchain/trident) - 面向 Solana 智能合约的模糊测试框架，具备手动引导测试、基于流的序列和基于属性的验证
  * [proptest](https://crates.io/crates/proptest) - 受 Python 的 [Hypothesis](https://hypothesis.works/) 框架启发的属性测试框架
  * [quickcheck](https://crates.io/crates/quickcheck) - [QuickCheck](https://wiki.haskell.org/Introduction_to_QuickCheck1) 的 Rust 实现
  * [rust-fuzz/afl.rs](https://github.com/rust-fuzz/afl.rs) - 使用 [AFL](https://lcamtuf.coredump.cx/afl/) 的 Rust 模糊测试器

### 转译

* [aleph-lang/aleph_ollama](https://github.com/aleph-lang/aleph_ollama) [[aleph_ollama](https://crates.io/crates/aleph_ollama)] - 使用本地 Ollama API 的 AI 驱动源代码翻译工具。
* [BayesWitnesses/m2cgen](https://github.com/BayesWitnesses/m2cgen) - 将训练好的经典机器学习模型转译为零依赖的原生 Rust 代码的 CLI 工具。
* [immunant/c2rust](https://github.com/immunant/c2rust) - 构建在 Clang/LLVM 之上的 C 到 Rust 翻译器和交叉检查器。
* [jameysharp/corrode](https://github.com/jameysharp/corrode) - 用 Haskell 编写的 C 到 Rust 翻译器。

### 隧道

* [ekzhang/bore](https://github.com/ekzhang/bore) [[bore-cli](https://crates.io/crates/bore-cli)] - 简单的 TCP 隧道，将本地端口暴露到远程服务器，绕过 NAT 防火墙 [![Build status](https://img.shields.io/github/actions/workflow/status/ekzhang/bore/ci.yml)](https://github.com/ekzhang/bore/actions)
* [joaoh82/rustunnel](https://github.com/joaoh82/rustunnel) - 自托管安全隧道服务器。通过带 yamux 多路复用的 TLS 加密 WebSocket 暴露本地 HTTP/HTTPS/TCP/UDP 服务；多区域、Prometheus 指标、面向 AI 代理的 MCP 服务器。
* [ngrok/ngrok-rust](https://github.com/ngrok/ngrok-rust) [[ngrok-rust](https://crates.io/crates/ngrok)] - ngrok 是一个开发者工具，可将你的本地应用安全地暴露到互联网。
* [rathole-org/rathole](https://github.com/rathole-org/rathole) - 安全、高性能的反向代理，用于 NAT 穿透，具备 Noise Protocol/TLS 加密和热重载配置支持 ![CI](https://img.shields.io/github/actions/workflow/status/rathole-org/rathole/rust.yml?branch=main)

## 库

* [perf-monitor-rs](https://github.com/larksuite/perf-monitor-rs) - 一个旨在作为应用性能监控基础的工具包。[![crates.io](https://img.shields.io/crates/v/perf_monitor.svg)](https://crates.io/crates/perf_monitor)

### 人工智能

#### 遗传算法

* [innoave/genevo](https://github.com/innoave/genevo) - 以可定制、可扩展的方式执行遗传算法（GA）模拟。
* [m-decoster/RsGenetic](https://github.com/m-decoster/RsGenetic) - 遗传算法库。处于维护模式。
* [Martin1887/oxigen](https://github.com/Martin1887/oxigen) - 快速、并行、可扩展且自适应的遗传算法库。使用该库的一个示例仅在几秒内解决了 N=255 的 N 皇后问题，且占用不到 1 MB 内存。
* [pkalivas/radiate](https://github.com/pkalivas/radiate) - 可定制的并行遗传编程引擎，能够为监督、无监督和强化学习问题演化出解决方案。附带完整且可定制的 NEAT 和 Evtree 实现。![Crates.io](https://img.shields.io/crates/v/radiate)
* [willi-kappler/darwin-rs](https://github.com/willi-kappler/darwin-rs) - 进化算法

#### Google Gemini

* [gemini-client-api](https://crates.io/crates/gemini-client-api) - 使用 Google Gemini API 的库。具备自动上下文管理、schema 生成、函数调用等。

#### 机器学习

参见 [[Machine learning](https://crates.io/keywords/machine-learning)]

另见 [About Rust's Machine Learning Community](https://medium.com/@autumn_eng/about-rust-s-machine-learning-community-4cda5ec8a790#.hvkp56j3f) 和 [Are we learning yet?](https://www.arewelearningyet.com)。

* [autumnai/leaf](https://github.com/autumnai/leaf) - 开放机器智能框架。已废弃项目。最新更新的分支是 [juice](https://github.com/fff-rs/juice)。
* [ave-sergeev/tictonix](https://github.com/Ave-Sergeev/Tictonix) [[tictonix](https://crates.io/crates/tictonix)] - 提供将 token 转换为嵌入（embedding）以及编码其位置能力的库。
* [blackportal-ai/delta](https://github.com/blackportal-ai/delta) - Δ 一个用 Rust 编写的开源机器学习框架。![crates.io](https://img.shields.io/crates/v/deltaml.svg) ![build](https://img.shields.io/github/actions/workflow/status/blackportal-ai/delta/core.yml?branch=master)
* [blackportal-ai/nebula](https://github.com/blackportal-ai/nebula) - 面向机器学习数据集和模型的包管理器。![build](https://img.shields.io/github/actions/workflow/status/blackportal-ai/nebula/core.yml?branch=master)
* [burn](https://github.com/tracel-ai/burn) - 灵活且全面的深度学习框架。
* [chelsea0x3b/dfdx](https://github.com/chelsea0x3b/dfdx) - 利用 Rust 众多独特特性的 CUDA 加速机器学习框架。![Crates.io](https://img.shields.io/crates/v/dfdx)
* [cmccomb/rust-automl](https://github.com/cmccomb/rust-automl) [[automl](https://crates.io/crates/automl)] - 构建在 SmartCore 之上的自动化分类、回归和聚类工作流
* [EricLBuehler/mistral.rs](https://github.com/EricLBuehler/mistral.rs) [[mistralrs](https://crates.io/crates/mistralrs)] - 快速、灵活的 LLM 推理引擎，支持多模态模型、量化（GGUF/GPTQ/ISQ）以及兼容 OpenAI 的 API
* [guillaume-be/rust-bert](https://github.com/guillaume-be/rust-bert) [[rust_bert](https://crates.io/crates/rust_bert)] - 开箱即用的 NLP 流水线和语言模型
* [huggingface/candle](https://github.com/huggingface/candle) [[candle-core](https://crates.io/crates/candle-core)] - 一个极简的 ML 框架，专注于易用性和性能（包括 GPU 支持）
* [huggingface/tokenizers](https://github.com/huggingface/tokenizers) - Hugging Face 面向现代 NLP 流水线的 tokenizers（原始实现），带 Python 绑定。[![Build Status](https://github.com/huggingface/tokenizers/workflows/Rust/badge.svg?branch=master)](https://github.com/huggingface/tokenizers/actions)
* [katanemo/plano](https://github.com/katanemo/plano) - 面向代理式应用的 AI 原生代理服务器和数据平面。
* [LaurentMazare/tch-rs](https://github.com/LaurentMazare/tch-rs) - PyTorch 的绑定。
* [luminal-ai/luminal](https://github.com/luminal-ai/luminal) [[luminal](https://crates.io/crates/luminal)] - 高性能通用推理编译器，具备 RISC 风格架构、基于搜索的优化和原生 CUDA/Metal 后端。支持 transformers、convnets 和自动微分。[![CI Status](https://img.shields.io/github/actions/workflow/status/luminal-ai/luminal/test-core.yml?style=for-the-badge&logo=github-actions&logoColor=white&branch=main)](https://github.com/luminal-ai/luminal/actions)
* [maciejkula/rustlearn](https://github.com/maciejkula/rustlearn) - 机器学习库。[![Circle CI](https://circleci.com/gh/maciejkula/rustlearn.svg?style=svg)](https://app.circleci.com/pipelines/github/maciejkula/rustlearn)
* [Michael-A-Kuykendall/shimmy](https://github.com/Michael-A-Kuykendall/shimmy) [[shimmy](https://crates.io/crates/shimmy)] - 纯 Rust 的 WebGPU 推理引擎，具备兼容 OpenAI 的 API 和原生 GGUF 支持。
* [Michael-A-Kuykendall/shimmytok](https://github.com/Michael-A-Kuykendall/shimmytok) [[shimmytok](https://crates.io/crates/shimmytok)] - 面向 GGUF 模型的纯 Rust tokenizer，兼容 llama.cpp 的分词。
* [Mottl/lightgb3-rs](https://github.com/Mottl/lightgbm3-rs) - LightGBM 的绑定 [![Crates.io](https://img.shields.io/crates/v/lightgbm3.svg)](https://crates.io/crates/lightgbm3) [![build](https://github.com/Mottl/lightgbm3-rs/actions/workflows/ci.yml/badge.svg)](https://github.com/Mottl/lightgbm3-rs/actions)
* [nobodywho-ooo/nobodywho](https://github.com/nobodywho-ooo/nobodywho) - 设备端 LLM 推理引擎，可直接嵌入游戏和应用中，无需服务器或 API 密钥。支持流式生成、嵌入、GBNF 语法约束的结构化输出和 Whisper 语音转文本，并提供 Godot、Flutter、React Native 和 Swift 绑定。
* [openinfer-project/openinfer](https://github.com/openinfer-project/openinfer) - 纯 Rust + CUDA 的 LLM 推理引擎，无 PyTorch、无 Python 运行时——兼容 OpenAI 的 API、分页 KV 缓存、CUDA Graph，可服务从 Qwen3 到万亿参数的 Kimi-K2 等模型。
* [perpetual-ml/perpetual](https://github.com/perpetual-ml/perpetual) [[perpetual](https://crates.io/crates/perpetual)] - 一种自泛化的梯度提升机，无需超参数优化。
* [ramsyana/RustTensor](https://github.com/ramsyana/RustTensor) - 一个以学习为导向、用 Rust 从零构建的高性能张量计算库，具备自动微分和 CPU/CUDA 后端。
* [raphaelmansuy/edgequake](https://github.com/raphaelmansuy/edgequake) - 高性能的 Graph-RAG 框架，可将文档转化为智能知识图谱。
* [rust-ml/linfa](https://github.com/rust-ml/linfa) - 机器学习框架。
* [sipemu/anofox-regression](https://github.com/sipemu/anofox-regression) [[anofox-regression](https://crates.io/crates/anofox-regression)] - 统计回归模型（OLS、Elastic Net、GLM、Quantile 和 Isotonic），具备类 R 的推断（p 值、置信区间和预测区间）以及 Wasm 支持。
* [smartcorelib/smartcore](https://github.com/smartcorelib/smartcore) - 机器学习库 [![Build Status](https://img.shields.io/circleci/build/github/smartcorelib/smartcore)]
* [tag1consulting/feste](https://github.com/tag1consulting/feste) - 一个出于教学目的用 Rust 从零实现的 GPT-2 风格 transformer 语言模型。
* [tensorflow/rust](https://github.com/tensorflow/rust) - TensorFlow 的绑定。

#### OpenAI

* [0xplaygrounds/rig](https://github.com/0xplaygrounds/rig) - 用于创建代理和模块化、可扩展的 LLM 驱动应用的库
* [64bit/async-openai](https://github.com/64bit/async-openai) [[async-openai](https://crates.io/crates/async-openai)] - 基于 OpenAPI 规范为 OpenAI API 提供的人体工程学 Rust 绑定。
* [awakenworks/awaken](https://github.com/awakenworks/awaken) [[awaken](https://crates.io/crates/awaken)] - Rust 的 AI 代理运行时——类型安全状态、多协议服务、插件可扩展性。
* [bigduu/Bamboo-agent](https://github.com/bigduu/Bamboo-agent) [[bamboo-agent](https://crates.io/crates/bamboo-agent)] - 本地优先的 AI 代理框架与运行时——在统一的 HTTP + WebSocket API 背后提供持久记忆、内置工具、技能、MCP、子代理、工作流和调度。可作为 crate 嵌入，也可作为服务器运行。
* [liquidos-ai/AutoAgents](https://github.com/liquidos-ai/AutoAgents) [[AutoAgents](https://crates.io/crates/autoagents)] - 用于构建具备原生边缘支持的多代理框架。
* [openai/codex](https://github.com/openai/codex) - Codex CLI 是 OpenAI 出品的、本地运行的编码代理。
* [openai/harmony](https://github.com/openai/harmony) [[openai-harmony](https://crates.io/crates/openai-harmony/0.0.3)] - 用于配合 gpt-oss 的 harmony 响应格式渲染器。
* [xberg-io/liter-llm](https://github.com/xberg-io/liter-llm) [[liter-llm](https://crates.io/crates/liter-llm)] - 通用 LLM API 客户端，统一接口支持 142+ 提供商、流式传输，以及 11 种语言的原生绑定。
* [zurawiki/tiktoken-rs](https://github.com/zurawiki/tiktoken-rs) [[tiktoken-rs](https://crates.io/crates/tiktoken-rs)] - 使用 tiktoken 对文本进行 OpenAI 模型分词的库。[![CI](https://github.com/zurawiki/tiktoken-rs/actions/workflows/ci.yml/badge.svg)](https://github.com/zurawiki/tiktoken-rs/actions/workflows/ci.yml)

#### 工具

* [BAML](https://github.com/BoundaryML/baml) - 一种用于构建可靠 AI 工作流和代理的简单提示语言。BAML 的编译器是用 Rust 编写的！
* [Cortex Memory](https://github.com/sopaco/cortex-mem) - 一套完整的代理记忆解决方案，从提取和向量搜索到自动优化，并开箱即用地提供洞察仪表板。
* [juyterman1000/entroly](https://github.com/juyterman1000/entroly) - 信息论上下文工程引擎，使用强化学习智能地裁剪和选择最优的 RAG 片段。
* [Mattbusel/tokio-prompt-orchestrator](https://github.com/Mattbusel/tokio-prompt-orchestrator) [[tokio-prompt-orchestrator](https://crates.io/crates/tokio-prompt-orchestrator)] - 用于服务 LLM 请求的 Tokio 流水线，在 Anthropic、OpenAI、llama.cpp 或 vLLM 之前提供去重、熔断、重试、限流和死信队列。
* [memvid/memvid](https://github.com/memvid/memvid) [[memvid-core](https://crates.io/crates/memvid-core)] - 面向 AI 代理的单文件可移植记忆层，将向量搜索、全文搜索和长期回忆打包进一个 `.mv2` 文件
* [pydantic/monty](https://github.com/pydantic/monty) - 一个极简、安全的 Python 解释器，用于在 AI 代理中运行 LLM 生成的代码，具备微秒级启动、严格沙箱和快照支持 [![CI](https://github.com/pydantic/monty/actions/workflows/ci.yml/badge.svg)](https://github.com/pydantic/monty/actions/workflows/ci.yml)
* [samvallad33/vestige](https://github.com/samvallad33/vestige) - 面向 AI 代理的因果证明引擎和操作系统，构建在仅追加的签名日志 Strata 之上。无向量、无 RAG。每个答案都携带其证明作为记忆 id、边路径或收据，并可将失败追溯到导致它的提交 [![CI](https://github.com/samvallad33/vestige/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/samvallad33/vestige/actions/workflows/ci.yml)
* [tenequm/pond](https://github.com/tenequm/pond) [[pond-db](https://crates.io/crates/pond-db)] - 跨十二种编码代理客户端对 AI 代理会话进行无损存储和搜索，构建于本地目录或 S3 存储桶上的 Lance 之上，通过 CLI、HTTP、MCP 和只读 SQL 暴露 BM25 和可选的向量检索 [![build badge](https://github.com/tenequm/pond/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/tenequm/pond/actions/workflows/ci.yml)

### 天文学

[[astronomy](https://crates.io/keywords/astronomy)]

* [cds-astro/aladin-lite](https://github.com/cds-astro/aladin-lite) - 用于以不同投影可视化空间和行星图像巡天的 Web 应用
* [fitsio](https://crates.io/crates/fitsio) - 封装 cfitsio 的 fits 接口库
* [flosse/rust-sun](https://github.com/flosse/rust-sun) [[sun](https://crates.io/crates/sun)] - JS 库 suncalc 的 Rust 移植
* [saurvs/astro-rust](https://github.com/saurvs/astro-rust) - 天文学

### 异步

* [async-std](https://async.rs/) [[async-std](https://crates.io/crates/async-std)] - Rust 标准库的异步版本 [![CI](https://github.com/async-rs/async-std/actions/workflows/ci.yml/badge.svg?branch=master)](https://github.com/async-rs/async-std/actions/workflows/ci.yml)
* [dagrs](https://github.com/dagrs-dev/dagrs) - 高性能异步任务编程框架，遵循基于流的编程（Flow-based Programming）理念。
* [dpc/mioco](https://github.com/dpc/mioco) - 可扩展的、基于协程的异步 IO 处理库
* [igumnoff/gabriel2](https://github.com/igumnoff/gabriel2) [[gabriel2](https://crates.io/crates/gabriel2)] - Gabriel2：基于 Tokio 的 actor 模型库
* [iii-hq/iii](https://github.com/iii-hq/iii) [[iii-sdk](https://crates.io/crates/iii-sdk)] - 通过 Worker-Function-Trigger 原语组合服务的分布式运行时。实时目录、可追踪的函数调用，以及多语言 SDK（Rust、Node.js、Python）。引擎用 Rust 编写（ELv2），SDK 采用 Apache 2.0。
* [mio](https://github.com/tokio-rs/mio) - MIO 是一个轻量级 IO 库，专注于在 OS 抽象之上尽可能减少开销
* [nextest-rs/future-queue](https://github.com/nextest-rs/future-queue) [[future-queue](https://crates.io/crates/future-queue)] - 用于并发运行 future 的流适配器，支持带权重的并发限制和可选的按组限制。
* [rust-lang/futures-rs](https://github.com/rust-lang/futures-rs) - 零成本 future
* [t3hmrman/async-dropper](https://github.com/t3hmrman/async-dropper) [[async-dropper](https://crates.io/crates/async-dropper)] - `AsyncDrop` 的实现
* [TeaEntityLab/fpRust](https://github.com/TeaEntityLab/fpRust) - 为 Rust 提供的 Monad/MonadIO、Handler、Coroutine/doNotation、函数式编程特性
* [tokio-rs/tokio](https://github.com/tokio-rs/tokio) - 一个用于使用 Rust 编程语言编写可靠、异步且精简应用的运行时。
* [tqwewe/kameo](https://github.com/tqwewe/kameo) - 构建于 Tokio 之上的容错异步 Actor
* [Xudong-Huang/may](https://github.com/Xudong-Huang/may) - 有栈协程库
* [zonyitoo/coio-rs](https://github.com/zonyitoo/coio-rs) - 带工作窃取调度器的协程 I/O 库

### 音频与音乐

[[audio](https://crates.io/keywords/audio)]

* [aschey/stream-download-rs](https://github.com/aschey/stream-download-rs) [[stream-download](https://crates.io/crates/stream-download)] - 用于流式传输音频、视频和其他媒体内容的库 [![build badge](https://github.com/aschey/stream-download-rs/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/aschey/stream-download-rs/actions)
* [hound](https://crates.io/crates/hound) - WAV 编码和解码库
* [insomnimus/nodi](https://github.com/insomnimus/nodi) [[nodi](https://crates.io/crates/nodi)] - 用于播放和抽象 MIDI 文件的库。[![build badge](https://github.com/insomnimus/nodi/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/insomnimus/nodi/actions)
* [jhasse/ears](https://github.com/jhasse/ears) - 一个基于 OpenAL 和 libsndfile 播放声音和音乐的简单库
* [musitdev/portmidi-rs](https://github.com/musitdev/portmidi-rs) - [PortMidi](https://portmedia.sourceforge.net/portmidi/) 绑定
* [ozankasikci/rust-music-theory](https://github.com/ozankasikci/rust-music-theory) - 乐理库
* [pdeljanov/Symphonia](https://github.com/pdeljanov/Symphonia) - 音频解码和媒体解复用库，支持 AAC、FLAC、MP3、MP4、OGG、Vorbis 和 WAV。
* [RustAudio](https://github.com/RustAudio)
  * [RustAudio/cpal](https://github.com/RustAudio/cpal) - 底层跨平台音频 I/O 库。[![Actions Status](https://github.com/RustAudio/cpal/workflows/cpal/badge.svg?branch=master)](https://github.com/RustAudio/cpal/actions)
  * [RustAudio/rodio](https://github.com/RustAudio/rodio) - 音频播放库
  * [RustAudio/rust-portaudio](https://github.com/RustAudio/rust-portaudio) - PortAudio 绑定
* [Serial-ATA/lofty-rs](https://github.com/Serial-ATA/lofty-rs) [[lofty](https://crates.io/crates/lofty)] - 用于读取和编辑各种音频格式元数据的库 [![build badge](https://github.com/Serial-ATA/lofty-rs/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/Serial-ATA/lofty-rs/actions)

### 身份验证

* [constantoine/totp-rs](https://github.com/constantoine/totp-rs) [[totp-rs](https://crates.io/crates/totp-rs)] - 用于生成和验证基于 TOTP 令牌的 2fa 库 ![Build Status](https://github.com/constantoine/totp-rs/workflows/Rust/badge.svg)
* [GunduLabs/gaze](https://github.com/GunduLabs/gaze) - 面向 Linux 的面部认证，具备设备端人脸识别、PAM 集成，以及用于登录、锁屏、sudo 和桌面管理的工具。[![CI](https://github.com/GunduLabs/gaze/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/GunduLabs/gaze/actions/workflows/ci.yml)
* [Keats/jsonwebtoken](https://github.com/Keats/jsonwebtoken) - [JSON Web Token](https://en.wikipedia.org/wiki/JSON_Web_Token) 库
* [oauth2](https://github.com/ramosbugs/oauth2-rs) - 可扩展、强类型的 OAuth2 客户端库
* [oxide-auth](https://github.com/197g/oxide-auth) - 一个 OAuth2 服务器库，可与 actix 或其他前端结合使用，具备一组可配置、可插拔的后端 [![CI](https://github.com/HeroicKatora/oxide-auth/actions/workflows/ci.yml/badge.svg)](https://github.com/HeroicKatora/oxide-auth/actions/workflows/ci.yml)
* [sgrust01/jwtvault](https://github.com/sgrust01/jwtvault) - 用于管理和编排 JWT 工作流的异步库
* [tenuo-ai/tenuo](https://github.com/tenuo-ai/tenuo) [[tenuo](https://crates.io/crates/tenuo)] - 面向 AI 代理的基于能力的授权。签名凭证限定工具调用和参数范围，且仅在委派时收窄 [![CI](https://github.com/tenuo-ai/tenuo/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/tenuo-ai/tenuo/actions/workflows/ci.yml)
* [yup-oauth2](https://github.com/dermesser/yup-oauth2) - 一个 oauth2 客户端实现，提供设备、已安装和服务账号流程

### 汽车

* [idletea/tokio-socketcan](https://github.com/idletea/tokio-socketcan) [[tokio-socketcan](https://crates.io/crates/tokio-socketcan)] - 基于 socketcan crate 为 tokio 提供 Linux SocketCAN 支持
* [marcelbuesing/tokio-socketcan-bcm](https://github.com/marcelbuesing/tokio-socketcan-bcm) [[tokio-socketcan-bcm](https://crates.io/crates/tokio-socketcan-bcm)] - 为 tokio 提供 Linux SocketCAN BCM 支持
* [mbr/socketcan](https://github.com/socketcan-rs/socketcan-rs) [[socketcan](https://crates.io/crates/socketcan)] - Linux SocketCAN 库
* [oxibus/can-dbc](https://github.com/oxibus/can-dbc) [[can-dbc](https://crates.io/crates/can-dbc)] - DBC 格式的解析器
* [Sensirion/lin-bus](https://github.com/Sensirion/lin-bus-rs) [[lin-bus](https://crates.io/crates/lin-bus)] - LIN 总线驱动 trait 和协议实现 [![build badge](https://circleci.com/gh/Sensirion/lin-bus-rs.svg?style=svg)](https://app.circleci.com/pipelines/github/Sensirion/lin-bus-rs)

### 生物信息学

* [polars-bio](https://github.com/biodatageeks/polars-bio) - 在 Python DataFrame 上执行极快的生物信息学操作 ![PyPI - Version](https://img.shields.io/pypi/v/polars-bio)
* [Rust-Bio](https://github.com/rust-bio) - 生物信息学库。

### 缓存

* [06chaynes/http-cache](https://github.com/06chaynes/http-cache) [[http-cache](https://crates.io/crates/http-cache)] - 遵循 HTTP 缓存规则的缓存中间件 [![build badge](https://github.com/06chaynes/http-cache/workflows/http-cache/badge.svg)](https://github.com/06chaynes/http-cache/actions/workflows/http-cache.yml)
* [aisk/rust-memcache](https://github.com/aisk/rust-memcache) - Memcached 客户端库
* [al8n/stretto](https://github.com/al8n/stretto) - 一个高性能、线程安全、内存受限的缓存 [![build badge](https://github.com/al8n/stretto/actions/workflows/ci.yml/badge.svg)](https://github.com/al8n/stretto/actions/workflows/ci.yml)
* [hit-box/hitbox](https://github.com/hit-box/hitbox) - 声明式缓存编排框架，具备 HTTP 中间件和多层后端 [![CI](https://github.com/hit-box/hitbox/actions/workflows/CI.yml/badge.svg)](https://github.com/hit-box/hitbox/actions/workflows/CI.yml)
* [jaemk/cached](https://github.com/jaemk/cached) - 简单的函数缓存/记忆化
* [kunobi-ninja/kache](https://github.com/kunobi-ninja/kache) [[kache](https://crates.io/crates/kache)] - 面向 Rust 和 C/C++ 的内容寻址编译器缓存（[网站](https://ninja.kunobi.com/kache)）[![CI](https://github.com/kunobi-ninja/kache/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/kunobi-ninja/kache/actions/workflows/ci.yml)
* [moka-rs/moka](https://github.com/moka-rs/moka) - 一个受 Java 的 Caffeine 库启发的高性能并发缓存库 [![build badge](https://github.com/moka-rs/moka/workflows/CI/badge.svg)](https://github.com/moka-rs/moka/actions/workflows/CI.yml)
* [mozilla/sccache](https://github.com/mozilla/sccache/) - 共享编译缓存，出色的编译
* [salsa-rs/salsa](https://github.com/salsa-rs/salsa) [[salsa](https://crates.io/crates/salsa)] - 一个通用的按需增量计算框架，带记忆化查询，受 rustc 查询系统启发。[![Test](https://github.com/salsa-rs/salsa/workflows/Test/badge.svg)](https://github.com/salsa-rs/salsa/actions?query=workflow%3ATest)
* [zkat/cacache-rs](https://github.com/zkat/cacache-rs) - 一个高性能、并发、内容寻址的磁盘缓存，针对异步 API 优化 [![build badge](https://github.com/zkat/cacache-rs/workflows/CI/badge.svg)](https://github.com/zkat/cacache-rs/actions/workflows/ci.yml)

### 云

* AWS [[aws](https://crates.io/keywords/aws)]
  * [aws/aws-lambda-rust-runtime](https://github.com/aws/aws-lambda-rust-runtime) [[lambda_runtime](https://crates.io/crates/lambda_runtime)] - AWS Lambda 的运行时 [![build badge](https://github.com/aws/aws-lambda-rust-runtime/workflows/Rust/badge.svg)](https://github.com/aws/aws-lambda-rust-runtime/actions)
  * [awslabs/aws-sdk-rust](https://github.com/awslabs/aws-sdk-rust) - 新的 AWS SDK
  * [faiscadev/fakecloud](https://github.com/faiscadev/fakecloud) [[fakecloud](https://crates.io/crates/fakecloud)] - 用于开发和测试的本地 AWS 云模拟器。[![CI](https://github.com/faiscadev/fakecloud/workflows/CI/badge.svg?branch=main)](https://github.com/faiscadev/fakecloud/actions)
  * [rusoto/rusoto](https://github.com/rusoto/rusoto) - Rust 的 AWS SDK
* Azure
  * [Azure/azure-sdk-for-rust](https://github.com/Azure/azure-sdk-for-rust) - 官方 Azure Rust SDK
* 负载均衡器
  * [Convey](https://github.com/bparli/convey) - 具备动态配置加载的第 4 层负载均衡器。
* 多云
  * [Qovery/engine](https://github.com/Qovery/engine) - 抽象层库，让在云提供商上轻松部署应用只需几分钟

### 命令行

* 参数解析
  * [aisk/rust-fire](https://github.com/aisk/rust-fire) [[fire](https://crates.io/crates/fire)] - 用一行代码将你的函数变成命令行应用 [![CI](https://github.com/aisk/rust-fire/actions/workflows/ci.yml/badge.svg)](https://github.com/aisk/rust-fire/actions/workflows/ci.yml)
  * [clap-rs](https://github.com/clap-rs/clap) [[clap](https://crates.io/crates/clap)] - 一个简单易用、功能齐全的命令行参数解析器
  * [cliparser](https://crates.io/crates/cliparser) - 简单的命令行解析器。[![build badge](https://github.com/sagiegurari/cliparser/actions/workflows/ci.yml/badge.svg)](https://github.com/sagiegurari/cliparser/actions)
  * [docopt/docopt.rs](https://github.com/docopt/docopt.rs) [[docopt](https://crates.io/crates/docopt)] - DocOpt 的实现
  * [google/argh](https://github.com/google/argh) [[argh](https://crates.io/crates/argh)] - 一个有针对性的、基于 Derive 的参数解析器，针对代码体积优化 [![build badge](https://github.com/google/argh/workflows/Argh/badge.svg?branch=master)](https://github.com/google/argh/actions)
  * [killercup/quicli](https://github.com/killercup/quicli) [[quicli](https://crates.io/crates/quicli)] - 快速构建出色的 CLI 应用
  * [ksk001100/seahorse](https://github.com/ksk001100/seahorse) [[seahorse](https://crates.io/crates/seahorse)] - 一个极简的 CLI 框架 [![Build status](https://github.com/ksk001100/seahorse/workflows/CI/badge.svg?branch=master)](https://github.com/ksk001100/seahorse/actions)
  * [TeXitoi/structopt](https://github.com/TeXitoi/structopt) [[structopt](https://crates.io/crates/structopt)] - 通过定义一个 struct 来解析命令行参数
* 数据可视化
  * [nukesor/comfy-table](https://github.com/nukesor/comfy-table) [[comfy-table](https://crates.io/crates/comfy-table)] - 为你的 CLI 工具提供漂亮的动态表格。[![Build status](https://github.com/Nukesor/comfy-table/workflows/Tests/badge.svg?branch=master)](https://github.com/nukesor/comfy-table/actions)
  * [zhiburt/tabled](https://github.com/zhiburt/tabled) [[tabled](https://crates.io/crates/tabled)] - 一个易于使用的库，用于美观地打印 struct 和 enum 的表格。[![Build Status](https://github.com/zhiburt/tabled/actions/workflows/ci.yml/badge.svg)](https://github.com/zhiburt/tabled/actions)
* 以人为本的设计
  * [rust-cli/human-panic](https://github.com/rust-cli/human-panic) [[human-panic](https://crates.io/crates/human-panic)] - 面向人类的 panic 消息
* 行编辑器
  * [kkawakam/rustyline](https://github.com/kkawakam/rustyline) [[rustyline](https://crates.io/crates/rustyline)] - readline 实现
  * [MovingtoMars/liner](https://github.com/MovingtoMars/liner) [[liner](https://crates.io/crates/liner)] - 提供类 readline 功能的库
  * [murarth/linefeed](https://github.com/murarth/linefeed) [[linefeed](https://crates.io/crates/linefeed)] - 可配置、可扩展的交互式行读取器
  * [nushell/reedline](https://github.com/nushell/reedline) [[reedline](https://crates.io/crates/reedline)] - 驱动 Nushell 的功能丰富的行编辑器。支持语法高亮、Tab 补全、多行、历史记录、vi/emacs 键位和 Unicode。[![Crates.io](https://img.shields.io/crates/v/reedline)](https://crates.io/crates/reedline)
  * [srijs/rust-copperline](https://github.com/srijs/rust-copperline) [[copperline](https://crates.io/crates/copperline)] - 命令行编辑库
* 其他
  * [mgrachev/update-informer](https://github.com/mgrachev/update-informer) [[update-informer](https://crates.io/crates/update-informer)] - 面向 CLI 应用的更新通知器。它会在 Crates.io 和 GitHub 上检查新版本 [![build badge](https://github.com/mgrachev/update-informer/workflows/CI/badge.svg)](https://github.com/mgrachev/update-informer/actions)
* 管道
  * [hniksic/rust-subprocess](https://github.com/hniksic/rust-subprocess) [[subprocess](https://crates.io/crates/subprocess)] - 与外部管道交互的工具
  * [imp/pager-rs](https://gitlab.com/imp/pager-rs) [[pager](https://crates.io/crates/pager)] - 将你的输出通过外部分页器管道传输
  * [oconnor663/duct.rs](https://github.com/oconnor663/duct.rs) [[duct](https://crates.io/crates/duct)] - 子进程管道和 IO 重定向的构建器
  * [rust-cli/rexpect](https://github.com/rust-cli/rexpect) [[rexpect](https://crates.io/crates/rexpect)] - 自动化交互式应用，如 ssh、ftp、passwd 等 [![CI](https://github.com/rust-cli/rexpect/actions/workflows/ci.yml/badge.svg)](https://github.com/rust-cli/rexpect/actions/workflows/ci.yml)
  * [zhiburt/expectrl](https://github.com/zhiburt/expectrl) [[expectrl](https://crates.io/crates/expectrl)] - 用于在伪终端中控制交互式程序的库 [![build badge](https://github.com/zhiburt/expectrl/actions/workflows/ci.yml/badge.svg)](https://github.com/zhiburt/expectrl/actions/workflows/ci.yml)
* 进度
  * [a8m/pb](https://github.com/a8m/pb) [[pbr](https://crates.io/crates/pbr)] - 控制台进度条
  * [clitic/kdam](https://github.com/clitic/kdam) [[kdam](https://crates.io/crates/kdam)] - 一个受 tqdm 和 rich.progress 启发的控制台进度条库 [![CI](https://github.com/clitic/kdam/actions/workflows/tests.yml/badge.svg)](https://github.com/clitic/kdam/actions/workflows/tests.yml)
  * [console-rs/indicatif](https://github.com/console-rs/indicatif) [[indicatif](https://crates.io/crates/indicatif)] - 向用户指示进度
  * [etienne-napoleone/spinach](https://github.com/etienne-napoleone/spinach) [[spinach](https://crates.io/crates/spinach)] - 实用的 spinner。[![CI](https://github.com/etienne-napoleone/spinach/actions/workflows/ci.yml/badge.svg)](https://github.com/etienne-napoleone/spinach/actions/workflows/ci.yml)
  * [FGRibreau/spinners](https://github.com/FGRibreau/spinners) [[spinners](https://crates.io/crates/spinners)] - 60+ 优雅的终端 spinner
  * [vyfor/rattles](https://github.com/vyfor/rattles) [[rattles](https://crates.io/crates/rattles)] - 一个极简、无依赖的终端 spinner 库。
* 提示
  * [hashmismatch/terminal_cli.rs](https://github.com/hashmismatch/terminal_cli.rs) [[terminal_cli](https://crates.io/crates/terminal_cli)] - 构建交互式命令提示符
  * [mikaelmello/inquire](https://github.com/mikaelmello/inquire) [[inquire](https://crates.io/crates/inquire)] - 用于在终端上构建交互式提示的库。[![Build status](https://github.com/mikaelmello/inquire/actions/workflows/build.yml/badge.svg?branch=main)](https://github.com/mikaelmello/inquire/actions)
  * [starship/starship](https://starship.rs/) [[starship](https://crates.io/crates/starship)] - 一个极简、极快且高度可定制的、适用于任何 shell 的提示符 [![Build status](https://github.com/starship/starship/actions/workflows/workflow.yml/badge.svg)](https://github.com/starship/starship/actions)
  * [ynqa/promkit](https://github.com/ynqa/promkit) [[promkit](https://crates.io/crates/promkit)] - 用于构建交互式命令行工具的工具包 [![ci](https://github.com/ynqa/promkit/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/ynqa/promkit/actions/workflows/ci.yml)
* 样式
  * [colored](https://github.com/colored-rs/colored) [[colored](https://crates.io/crates/colored)] - 终端着色如此简单，你早就知道怎么做了！
  * [console-rs/dialoguer](https://github.com/console-rs/dialoguer) [[dialoguer](https://crates.io/crates/dialoguer)] - 用于命令行提示及类似功能的库。
  * [LukasKalbertodt/bunt](https://github.com/LukasKalbertodt/bunt) [[bunt](https://crates.io/crates/bunt)] - 使用宏实现跨平台终端颜色和样式 [![Build status](https://github.com/LukasKalbertodt/bunt/actions/workflows/ci.yml/badge.svg)](https://github.com/LukasKalbertodt/bunt/actions?query=workflow%3ACI+branch%3Amaster)
  * [LukasKalbertodt/term-painter](https://github.com/LukasKalbertodt/term-painter) [[term-painter](https://crates.io/crates/term-painter)] - 跨平台带样式的终端输出
  * [ogham/rust-ansi-term](https://github.com/ogham/rust-ansi-term) [[ansi_term](https://crates.io/crates/ansi_term)] - 在 ANSI 终端上控制颜色和格式
  * [SergioBenitez/yansi](https://github.com/SergioBenitez/yansi) [[yansi](https://crates.io/crates/yansi)] - 一个极其简单的 ANSI 终端颜色绘制库
* TUI
  * [AppCUI](https://github.com/gdt050579/AppCUI-rs) [[appcui](https://crates.io/crates/appcui)] - 一个功能齐全、跨平台的 Rust TUI/CUI 框架，内置控件、布局控制、动画、Unicode 和主题支持。
  * BearLibTerminal
    * [cfyzium/bearlibterminal](https://github.com/nabijaczleweli/BearLibTerminal.rs) [[bear-lib-terminal](https://crates.io/crates/bear-lib-terminal)] - [BearLibTerminal](https://github.com/tommyettinger/BearLibTerminal) 绑定
  * [ccbrown/iocraft](https://github.com/ccbrown/iocraft) [[iocraft](https://crates.io/crates/iocraft)] - 一个用于打造精美、匠心独运的 CLI、TUI 和基于文本的 IO 的 crate。[![Build status](https://github.com/ccbrown/iocraft/actions/workflows/commit.yaml/badge.svg?branch=main)](https://github.com/ccbrown/iocraft/actions) [![docs.rs](https://img.shields.io/docsrs/iocraft)](https://docs.rs/iocraft/)
  * [gyscos/Cursive](https://github.com/gyscos/Cursive) [[cursive](https://crates.io/crates/cursive)] - 构建丰富的 TUI 应用
  * [ivanceras/titik](https://github.com/ivanceras/titik) - 一个跨平台 TUI 控件库，目标是提供交互式控件
  * ncurses
    * [ihalila/pancurses](https://github.com/ihalila/pancurses) [[pancurses](https://crates.io/crates/pancurses)] - curses 库，支持 linux 和 windows
    * [jeaye/ncurses-rs](https://github.com/jeaye/ncurses-rs) [[ncurses](https://crates.io/crates/ncurses)] - [ncurses](https://invisible-island.net/ncurses/ncurses.html) 绑定
  * [ogham/rust-term-grid](https://github.com/ogham/rust-term-grid) [[term_grid](https://crates.io/crates/term_grid)] - 用于将内容排成网格的库
  * [ratatui-org/ratatui](https://github.com/ratatui/ratatui) [[ratatui](https://crates.io/crates/ratatui)] - 一个专注于打造终端用户界面（TUI）的库
  * [redox-os/termion](https://github.com/redox-os/termion) [[termion](https://crates.io/crates/termion)] - 用于控制终端/TTY 的无绑定库
  * [ruterm](https://crates.io/crates/ruterm) - 处理 TTY 的小巧简单库
  * [subinium/SuperLightTUI](https://github.com/subinium/SuperLightTUI) [[superlighttui](https://crates.io/crates/superlighttui)] - 即时模式 TUI 库，具备 50+ 控件、flexbox 布局和动画系统 [![CI](https://github.com/subinium/SuperLightTUI/actions/workflows/ci.yml/badge.svg)](https://github.com/subinium/SuperLightTUI/actions/workflows/ci.yml)
  * Termbox
    * [gchp/rustbox](https://github.com/gchp/rustbox) [[rustbox](https://crates.io/crates/rustbox)] - [Termbox](https://github.com/nsf/termbox) 的绑定
  * [TimonPost/crossterm](https://github.com/crossterm-rs/crossterm) [[crossterm](https://crates.io/crates/crossterm)] - 跨平台终端库

### 压缩

* [7z](https://7-zip.org/7z.html)
  * [hasenbanck/sevenz-rust2](https://github.com/hasenbanck/sevenz-rust2) [[sevenz-rust2](https://crates.io/crates/sevenz-rust2)] - 用纯 Rust 编写的 7z 解压/压缩器 [![Rust](https://github.com/hasenbanck/sevenz-rust2/actions/workflows/rust.yml/badge.svg?branch=main)](https://github.com/hasenbanck/sevenz-rust2/actions/workflows/rust.yml)
* [Brotli](https://opensource.googleblog.com/2015/09/introducing-brotli-new-compression.html)
  * [dropbox/rust-brotli](https://github.com/dropbox/rust-brotli) - 可选择避开 stdlib 的 Brotli 解压器
  * [ende76/brotli-rs](https://github.com/ende76/brotli-rs) - Brotli 压缩的实现
* bzip2
  * [trifectatechfoundation/bzip2-rs](https://github.com/trifectatechfoundation/bzip2-rs) - [libbz2](https://www.sourceware.org/bzip2/) 绑定
* gzip
  * [zopfli](https://github.com/zopfli-rs/zopfli) [[zopfli](https://crates.io/crates/zopfli)] - Zopfli 压缩算法的实现，用于更高质量的 deflate 或 zlib 压缩
* gzp
  * [sstadick/gzp](https://github.com/sstadick/gzp/) - deflate 格式和 snappy 的多线程编码与解码
* LZMA
  * [hasenbanck/lzma-rust2](https://github.com/hasenbanck/lzma-rust2) [[lzma-rust2](https://crates.io/crates/lzma-rust2)] - 从 [tukaani xz for java](https://tukaani.org/xz/java.html) 移植的 LZMA / LZMA2 / LZIP / XZ 压缩 [![Rust](https://github.com/hasenbanck/lzma-rust2/actions/workflows/rust.yml/badge.svg?branch=master)](https://github.com/hasenbanck/lzma-rust2/actions/workflows/rust.yml)
* miniz
  * [rust-lang/flate2-rs](https://github.com/rust-lang/flate2-rs) - [miniz](https://code.google.com/archive/p/miniz) 绑定 [![build badge](https://github.com/rust-lang/flate2-rs/workflows/CI/badge.svg?branch=master)](https://github.com/rust-lang/flate2-rs/actions)
* [paxit](https://github.com/roquess/paxit) [[paxit](https://crates.io/crates/paxit)] - 灵活的库，使用各种算法（zip、tar、gzip、xz、zst 等）压缩和解压文件，采用模块化设计便于扩展
* tar
  * [alexcrichton/tar-rs](https://github.com/alexcrichton/tar-rs) - tar 归档读取/写入
* zip
  * [zip-rs/zip2](https://github.com/zip-rs/zip2) [[zip](https://crates.io/crates/zip)] - 读取和写入 ZIP 归档
* zstd
  * [gyscos/zstd-rs](https://github.com/gyscos/zstd-rs) - zstd 压缩库的 Rust 绑定

### 计算

* [alphaville/optimization-engine](https://github.com/alphaville/optimization-engine) [[optimization-engine](https://crates.io/crates/optimization_engine)] - Optimization Engine (OpEn) 是一个用于求解带约束非凸优化问题的求解器 [![Continuous integration](https://github.com/alphaville/optimization-engine/actions/workflows/ci.yml/badge.svg?branch=master)](https://github.com/alphaville/optimization-engine/actions/workflows/ci.yml)
* [argmin-rs/argmin](https://github.com/argmin-rs/argmin) [[argmin](https://crates.io/crates/argmin)] - 优化库
* [BLAS](https://en.wikipedia.org/wiki/Basic_Linear_Algebra_Subprograms) [[blas](https://crates.io/keywords/blas)]
  * [mikkyang/rust-blas](https://github.com/mikkyang/rust-blas) - BLAS 绑定
* [calebwin/emu](https://github.com/calebwin/emu) - 一种用于 GPGPU 数值计算的语言
* [cmccomb/vote](https://github.com/cmccomb/vote) [[vote](https://crates.io/crates/vote)] - 常见的偏好聚合和投票方法
* [dimforge/nalgebra](https://github.com/dimforge/nalgebra) - 低维线性代数库
* [faer-rs](https://github.com/sarah-quinones/faer-rs) [[faer](https://crates.io/crates/faer)] - Rust 的线性代数基础
* [fastnum](https://github.com/neogenie/fastnum) [fastnum](https://crates.io/crates/fastnum) - 用纯 Rust 实现的快速精确十进制数。适用于金融、加密货币以及任何其他固定精度计算。
* [GSL](http://www.gnu.org/software/gsl/)
  * [GuillaumeGomez/rust-GSL](https://github.com/GuillaumeGomez/rust-GSL) - GSL 绑定
* [jolars/basin](https://github.com/jolars/basin) [[basin](https://crates.io/crates/basin)] - 数值优化库，具备一阶、无导数、非线性最小二乘、进化和约束求解器，对线性代数后端泛型 [![CI](https://github.com/jolars/basin/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/jolars/basin/actions/workflows/ci.yml)
* [LAPACK](https://en.wikipedia.org/wiki/LAPACK)
  * [stainless-steel/lapack](https://github.com/blas-lapack-rs/lapack) - LAPACK 绑定
* [ml-rust/numr](https://github.com/ml-rust/numr) [[numr](https://crates.io/crates/numr)] - 受 NumPy 启发的 Rust 数值计算库，具备张量、线性代数、FFT、统计、自动微分和 GPU 加速。[![CI](https://github.com/ml-rust/numr/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/ml-rust/numr/actions/workflows/ci.yml)
* 并行
  * [arrayfire/arrayfire-rust](https://github.com/arrayfire/arrayfire-rust) - [Arrayfire](https://github.com/arrayfire) 绑定
  * [autumnai/collenchyma](https://github.com/autumnai/collenchyma) - 一个可扩展、可插拔、与后端无关的框架，用于在 CUDA、OpenCL 和常见主机 CPU 上进行并行高性能计算。
  * [luqmana/rust-opencl](https://github.com/luqmana/rust-opencl) - [OpenCL](https://www.khronos.org/opencl/) 绑定
* 科学计算
  * [Axect/Peroxide](https://github.com/Axect/Peroxide) - Rust 数值库，以纯 Rust 包含线性代数、数值分析、统计和机器学习工具
  * [cmccomb/structural-shapes](https://github.com/cmccomb/structural-shapes) [[structural-shapes](https://crates.io/crates/structural-shapes)] - 常见结构型材的截面属性和 AISC 数据
  * [cool-japan/scirs](https://github.com/cool-japan/scirs) - 生产就绪的纯 Rust 科学计算，包括线性代数、优化、统计、神经网络等。API 受 Python 的 SciPy 启发。
  * [cpmech/russell](https://github.com/cpmech/russell) - Rust 科学计算库，用于数值数学、常微分方程、特殊数学函数、高性能（稀疏）线性代数
  * [Nonanti/mathcore](https://github.com/Nonanti/mathcore) - 具备 CAS 能力的符号数学库。支持微分、积分、方程求解和任意精度算术 [![crates.io](https://img.shields.io/crates/v/mathcore.svg)](https://crates.io/crates/mathcore)
  * [Ryan-D-Gast/differential-equations](https://github.com/Ryan-D-Gast/differential-equations) - 一个高性能库，用于数值求解微分方程
* Statrs
  * [statrs-dev/statrs](https://github.com/statrs-dev/statrs) - 稳健的统计计算库

### 并发

* [crossbeam-rs/crossbeam](https://github.com/crossbeam-rs/crossbeam) - 支持并行和底层并发
* [NikitaSmithTheOne/rate-limiters-rs](https://github.com/NikitaSmithTheOne/rate-limiters-rs) [[rate-limiters](https://crates.io/crates/rate_limiters)] - 用于限流的 Rust 库（漏桶、令牌桶、固定/滑动窗口）
* [orium/archery](https://github.com/orium/archery) [[archery](https://crates.io/crates/archery)] - 从 `Rc`/`Arc` 指针类型抽象出来的库。[![build badge](https://github.com/orium/archery/workflows/CI/badge.svg)](https://github.com/orium/archery/actions?query=workflow%3ACI)
* [orx-parallel](https://crates.io/crates/orx-parallel) - 高性能、可配置且表达力强的并行计算库。
* [Rayon](https://github.com/rayon-rs/rayon) - 数据并行库
* [rustcc/coroutine-rs](https://github.com/rustcc/coroutine-rs) - 协程库
* [zonyitoo/coio-rs](https://github.com/zonyitoo/coio-rs) - 协程 I/O

### 配置

* [andoriyu/uclicious](https://github.com/andoriyu/uclicious) [[uclicious](https://crates.io/crates/uclicious)] - 基于 [libUCL](https://github.com/vstakhov/libucl) 的功能丰富的配置库。[![CircleCI](https://circleci.com/gh/vstakhov/libucl.svg?style=svg)](https://app.circleci.com/pipelines/github/vstakhov/libucl)
* [Kixunil/configure_me](https://github.com/Kixunil/configure_me) [[configure_me](https://crates.io/crates/configure_me)] - 轻松处理应用配置的库
* [leptonyu/cfg-rs](https://github.com/leptonyu/cfg-rs) [[cfg-rs](https://crates.io/crates/cfg-rs)] - 面向 Rust 应用的配置库。
* [rust-cli/config-rs](https://github.com/rust-cli/config-rs) [[config](https://crates.io/crates/config)] - 分层配置系统（强力支持 12-factor 应用）。
* [SergioBenitez/Figment](https://github.com/SergioBenitez/Figment) [[figment](https://crates.io/crates/figment)] - 一个极其无痛的配置库。
* [softprops/envy](https://github.com/softprops/envy) - 将环境变量反序列化为类型安全的 struct [![Main](https://github.com/softprops/envy/actions/workflows/main.yml/badge.svg)](https://github.com/softprops/envy/actions/workflows/main.yml)

### 密码学

[[crypto](https://crates.io/keywords/crypto), [cryptography](https://crates.io/keywords/cryptography)]

* [arkworks-rs/circom-compat](https://github.com/arkworks-rs/circom-compat) - Circom 的 R1CS 的 Arkworks 绑定，用于 Groth16 证明和见证生成。
* [briansmith/ring](https://github.com/briansmith/ring) - 使用 Rust 和 BoringSSL 的密码学原语实现的安全、快速、小型加密。
* [briansmith/webpki](https://github.com/briansmith/webpki) - Web PKI TLS X.509 证书验证。
* [conradkleinespel/rooster](https://github.com/conradkleinespel/rooster) [[rooster](https://crates.io/crates/rooster)] - 在终端中使用的简单密码管理器
* [cossacklabs/themis](https://github.com/cossacklabs/themis) [[themis](https://crates.io/crates/themis)] - 一个高级密码学库，用于解决典型数据安全任务，最适合多平台应用。[![build badge](https://circleci.com/gh/cossacklabs/themis/tree/master.svg?style=shield)](https://app.circleci.com/pipelines/github/cossacklabs/themis)
* [DaGenix/rust-crypto](https://github.com/DaGenix/rust-crypto) - 密码学算法
* [dalek-cryptography/curve25519-dalek](https://github.com/dalek-cryptography/curve25519-dalek) - Curve25519 运算
* [debris/tiny-keccak](https://github.com/debris/tiny-keccak) - Keccak 家族（SHA3）
* [dusk-network/bls12-381](https://github.com/dusk-network/bls12_381) - 一个 Rust 原生的 BLS12-381，具备增强的 zk 性能：优化的多标量乘法、自定义哈希和 serde 支持——非常适合注重隐私的协议和零知识应用。![Build Status](https://github.com/dusk-network/bls12_381/workflows/Continuous%20integration/badge.svg) [[dusk-bls12_381](https://crates.io/crates/dusk-bls12_381)]
* [dusk-network/plonk](https://github.com/dusk-network/plonk/) - 一个高性能、Rust 原生的 PLONK zk-SNARK 实现，基于 BLS12-381，使用自定义门和 KZG10 多项式承诺优化，以实现高效的零知识证明。![Build Status](https://github.com/dusk-network/plonk/workflows/Continuous%20integration/badge.svg) [[PLONK](https://crates.io/crates/dusk-plonk)]
* [dusk-network/poseidon252](https://github.com/dusk-network/Poseidon252) - 一个 Rust 原生的、基于 BLS12-381 的 Poseidon 哈希，Poseidon252 专为 zk-SNARK 效率而构建，非常适合注重隐私的协议和零知识应用。![Build Status](https://github.com/dusk-network/Poseidon252/workflows/Continuous%20integration/badge.svg) [[Poseidon](https://crates.io/crates/dusk-poseidon)]
* [exonum/exonum](https://github.com/exonum/exonum) [[exonum](https://crates.io/crates/exonum)] - 面向区块链项目的可扩展框架
* [facebook/opaque-ke](https://github.com/facebook/opaque-ke) - 最新的 [OPAQUE](https://datatracker.ietf.org/doc/draft-krawczyk-cfrg-opaque/) 密码认证密钥交换的实现。[![build badge](https://github.com/facebook/opaque-ke/workflows/Rust%20CI/badge.svg?branch=master)](https://github.com/facebook/opaque-ke)
* [iddm/randomorg](https://github.com/iddm/randomorg) - 一个 random.org 客户端库。[![Crates badge](https://img.shields.io/crates/v/randomorg.svg)](https://crates.io/crates/randomorg)
* [klutzy/suruga](https://github.com/klutzy/suruga) - [TLS 1.2](https://datatracker.ietf.org/doc/html/rfc5246) 的实现
* [kn0sys/ecc-rs](https://github.com/kn0sys/ecc-rs) - 直观的椭圆曲线密码学教程库 [![Crates.io Version](https://img.shields.io/crates/v/kn0syseccrs)](https://crates.io/crates/kn0syseccrs)
* [kornelski/rust-security-framework](https://github.com/kornelski/rust-security-framework) - Security Framework（OSX 原生）的绑定
* [libOctavo/octavo](https://github.com/libOctavo/octavo) - 模块化哈希和密码学库
* [orion-rs/orion](https://github.com/orion-rs/orion) - 该库旨在提供简单易用的密码学。"可用"意味着暴露易于使用且难以误用的高级 API。[![Tests](https://github.com/orion-rs/orion/actions/workflows/test.yml/badge.svg?branch=master)](https://github.com/orion-rs/orion/actions/workflows/test.yml)
* [racum/rust-djangohashers](https://github.com/racum/rust-djangohashers) [[djangohashers](https://crates.io/crates/djangohashers)] - Django 项目中使用的密码原语的移植。它不依赖 Django，仅按 Django 风格对密码进行哈希和验证。
* [rust-native-tls/rust-native-tls](https://github.com/rust-native-tls/rust-native-tls) - 原生 TLS 库的绑定
* [rust-openssl](https://github.com/rust-openssl/rust-openssl) - [OpenSSL](https://www.openssl.org/) 绑定
* [rust-random/rand](https://github.com/rust-random/rand) [[rand](https://crates.io/crates/rand)] - 全面的随机数生成库，支持强 PRNG 和小型 PRNG、随机值采样、分布和随机过程。[![Test Status](https://github.com/rust-random/rand/actions/workflows/test.yml/badge.svg?event=push)](https://github.com/rust-random/rand/actions)
* [RustCrypto/hashes](https://github.com/RustCrypto/hashes) - 密码学哈希函数集合
* [rustls/rustls](https://github.com/rustls/rustls) - TLS 的实现
* [schnorrkel](https://github.com/paritytech/schnorrkel) - Ristretto 群上的 Schnorr VRF 和签名
* [sorairolake/abcrypt](https://github.com/sorairolake/abcrypt) [[abcrypt](https://crates.io/crates/abcrypt)] - 一个简单、现代且安全的文件加密库。[![CI](https://github.com/sorairolake/abcrypt/workflows/CI/badge.svg?branch=develop)](https://github.com/sorairolake/abcrypt/actions?query=workflow%3ACI)
* [sorairolake/scryptenc-rs](https://github.com/sorairolake/scryptenc-rs) [[scryptenc](https://crates.io/crates/scryptenc)] - scrypt 加密数据格式的实现。[![CI](https://github.com/sorairolake/scryptenc-rs/workflows/CI/badge.svg?branch=develop)](https://github.com/sorairolake/scryptenc-rs/actions?query=workflow%3ACI)
* [suradet-ps/encryptman](https://github.com/suradet-ps/encryptman) [[encryptman](https://crates.io/crates/encryptman)] - 使用 HKDF 密钥派生为应用设置提供 AES-256-GCM 加密 [![CI](https://github.com/suradet-ps/encryptman/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/suradet-ps/encryptman/actions/workflows/ci.yml)
* [suradet-ps/encryptman-keyring](https://github.com/suradet-ps/encryptman-keyring) [[encryptman-keyring](https://crates.io/crates/encryptman-keyring)] - 面向 encryptman 的、由 OS 钥匙串支持的主密钥存储 [![CI](https://github.com/suradet-ps/encryptman-keyring/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/suradet-ps/encryptman-keyring/actions/workflows/ci.yml)
* [verifyfetch](https://github.com/hamzaydia/verifyfetch) - 使用 Rust/WASM SHA-256 哈希进行流式文件完整性验证，内存占用恒定。支持浏览器中大文件的可续传下载。

### 数据处理

* [amv-dev/yata](https://github.com/amv-dev/yata) - 高性能技术分析库 [![Build Status](https://img.shields.io/github/workflow/status/amv-dev/yata/Rust?branch=master)](https://github.com/amv-dev/yata/actions?query=workflow%3ARust)
* [AndreaBozzo/dataprof](https://github.com/AndreaBozzo/dataprof) [[dataprof](https://crates.io/crates/dataprof)] - 面向 CSV、JSON、Parquet 和 Arrow 的数据剖析和质量门禁，带 Python 绑定 [![CI](https://github.com/AndreaBozzo/dataprof/actions/workflows/ci.yml/badge.svg?branch=master)](https://github.com/AndreaBozzo/dataprof/actions/workflows/ci.yml)
* [bluss/ndarray](https://github.com/rust-ndarray/ndarray) - N 维数组，具备数组视图、多维切片和高效运算
* [DataBora/elusion](https://github.com/DataBora/elusion) [[elusion](https://crates.io/crates/elusion)] - 构建在 DataFusion 之上的端到端数据工程 DataFrame 库，带 Microsoft Fabric、Azure、SharePoint、FTP、Postgres、MySQL 和 REST API 连接器
* [datafusion](https://github.com/apache/datafusion) - DataFusion 是一个极快、可扩展的查询引擎，用于在 Rust 中构建高质量的数据中心系统，使用 Apache Arrow 内存格式。
* [faucet-hq/faucet-stream](https://github.com/faucet-hq/faucet-stream) [[faucet-core](https://crates.io/crates/faucet-core)] - 在数据移动时对其进行治理的 ETL：一个配置驱动的数据移动平台，具备可插拔的源和汇连接器、CDC、传输中脱敏和质量检查，可由单个二进制从 YAML 运行，或作为库嵌入 [![CI](https://github.com/faucet-hq/faucet-stream/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/faucet-hq/faucet-stream/actions/workflows/ci.yml)
* [GoPlasmatic/datalogic-rs](https://github.com/GoPlasmatic/datalogic-rs) [[datalogic-rs](https://crates.io/crates/datalogic-rs)] - 高性能、类型安全的 JSONLogic 求值引擎，用于业务规则和动态过滤，具备面向 Node、WASM、Python、Go、Java、.NET 和 PHP 的官方绑定 [![CI](https://github.com/GoPlasmatic/datalogic-rs/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/GoPlasmatic/datalogic-rs/actions/workflows/ci.yml)
* [ironcalc/IronCalc](https://github.com/ironcalc/IronCalc) [[ironcalc](https://crates.io/crates/ironcalc)] - 一个全新的、现代的、进行中的电子表格引擎。
* [kernelmachine/utah](https://github.com/kernelmachine/utah) - DataFrame 结构和操作
* [lakehq/sail](https://github.com/lakehq/sail) - Sail 是用 Rust 编写的、可直接替换 Apache Spark 的实现，统一批处理、流处理和计算密集型的 AI 工作负载。
* [logisky/LogiSheets](https://github.com/logisky/LogiSheets) [[logisheets-rs](https://crates.io/crates/logisheets-rs)] - 一个全新的、现代的、驱动真实产品的电子表格引擎。
* [openooxml/betteroffice](https://github.com/openooxml/betteroffice) - 面向 DOCX、XLSX 和 PPTX 的原生 OOXML 引擎：编辑、布局、渲染、CRDT 协作和代理编辑，编译为 WebAssembly。
* [pathwaycom/pathway](https://github.com/pathwaycom/pathway) - 高性能开源 Python ETL 框架，具备 Rust 运行时，支持 300+ 数据源。
* [pg_analytics](https://github.com/paradedb/paradedb/tree/dev/pg_analytics) - PostgreSQL 扩展，将 Postgres 内的分析查询处理加速到与专用 OLAP 数据库相当的性能水平。
* [pg_lakehouse](https://github.com/paradedb/paradedb/tree/dev/pg_lakehouse) - PostgreSQL 扩展，将 Postgres 转变为面向 AWS S3/GCS 等对象存储和 Delta Lake/Iceberg 等表格式的分析查询引擎。
* [pola-rs/polars](https://github.com/pola-rs/polars) - 快速、功能完整的 DataFrame 库 [![Lint Rust](https://github.com/pola-rs/polars/actions/workflows/lint-rust.yml/badge.svg)](https://github.com/pola-rs/polars/actions)
* [PSU3D0/formualizer](https://github.com/PSU3D0/formualizer) [[formualizer](https://crates.io/crates/formualizer)] - 可嵌入的电子表格引擎，可解析、求值和修改 Excel 工作簿：400+ 函数、Arrow 支持的存储、增量重算、Python 和 WASM 绑定 [![CI](https://github.com/PSU3D0/formualizer/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/PSU3D0/formualizer/actions/workflows/ci.yml)
* [weld-project/weld](https://github.com/weld-project/weld) - 面向数据分析应用的高性能运行时

### 数据流

* [arkflow-rs/arkflow](https://github.com/arkflow-rs/arkflow) - 高性能 Rust 流处理引擎 [![CI](https://github.com/arkflow-rs/arkflow/actions/workflows/rust.yml/badge.svg?branch=main)](https://github.com/arkflow-rs/arkflow/actions)
* [ArroyoSystems/arroyo](https://github.com/ArroyoSystems/arroyo) - 使用 Rust 和 SQL 的高性能实时分析 [![CI](https://github.com/ArroyoSystems/arroyo/actions/workflows/ci.yml/badge.svg?branch=master)](https://github.com/ArroyoSystems/arroyo/actions)
* [beava-dev/beava](https://github.com/beava-dev/beava) - 单二进制特性服务器。通过 HTTP 或 TCP 推送事件，内联查询每实体最新的计数器和聚合值，中间无需 broker。适用于反欺诈、推荐、LLM 护栏和产品内分析 [![CI](https://github.com/beava-dev/beava/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/beava-dev/beava/actions)
* [fluvio](https://github.com/fluvio-community/fluvio) - 可编程数据流平台 [![CI](https://github.com/fluvio-community/fluvio/actions/workflows/ci.yml/badge.svg)](https://github.com/fluvio-community/fluvio/actions)
* [iggy](https://github.com/apache/iggy) [[iggy](https://crates.io/crates/iggy)] - 持久化消息流平台，支持 QUIC、TCP 和 HTTP 传输协议 [![CI](https://github.com/apache/iggy/actions/workflows/test.yml/badge.svg)](https://github.com/apache/iggy/actions/workflows/test.yml)
* [wingfoil](https://github.com/wingfoil-io/wingfoil) - 基于图的流处理框架 [![CI](https://github.com/wingfoil-io/wingfoil/actions/workflows/rust.yml/badge.svg)](https://github.com/wingfoil-io/wingfoil/actions/workflows/rust.yml)

### 数据结构

* [alrevuelta/rs-merkle-tree](https://github.com/alrevuelta/rs-merkle-tree) - Rust 中的 Merkle 树实现，具备可配置的存储后端和哈希函数。仅支持固定深度和增量式。针对快速证明生成优化。
* [ashvardanian/NumKong](https://github.com/ashvardanian/NumKong) - 面向 x86 AVX2 和 AVX-512 以及 Arm NEON 的 SIMD 加速向量距离和相似度函数 [![crates.io](https://img.shields.io/crates/v/simsimd.svg)](https://crates.io/crates/simsimd)
* [becheran/grid](https://github.com/becheran/grid) [[grid](https://crates.io/crates/grid)] - 提供一个易于使用且快速的二维数据结构。[![build status](https://github.com/becheran/grid/actions/workflows/rust.yml/badge.svg)](https://github.com/becheran/grid/actions)
* [billyevans/tst](https://github.com/billyevans/tst) [[tst](https://crates.io/crates/tst)] - 三叉搜索树集合
* [contain-rs](https://github.com/contain-rs) - Rust 的 std::collections 的扩展
* [danielpclark/array_tool](https://github.com/danielpclark/array_tool) - 数组辅助工具。将一些最常用于数组的方法提供给 Vector。多态实现可处理你的大多数用例。
* [enum-map](https://codeberg.org/sugar700/enum-map) [[enum-map](https://crates.io/crates/enum-map)] - 一个针对枚举优化的 map 实现，使用数组存储值。
* [fizyk20/generic-array](https://github.com/fizyk20/generic-array) - 一个允许数组大小由类型决定的技巧
* [garro95/priority-queue](https://github.com/garro95/priority-queue)[[priority-queue](https://crates.io/crates/priority-queue)] - 一个支持优先级变更的优先队列。
* [greyblake/nutype](https://github.com/greyblake/nutype) [[nutype](https://crates.io/crates/nutype)] - 定义带验证约束的 newtype 结构。[![build status](https://github.com/greyblake/nutype/actions/workflows/ci.yml/badge.svg)](https://github.com/greyblake/nutype/actions)
* [jeromefroe/lru-rs](https://github.com/jeromefroe/lru-rs) [[lru](https://crates.io/crates/lru)] - 一个 LRU 缓存的实现，具备 O(1) 的 `put`、`get`、`get_mut` 和 `pop` 操作。[![crates.io](https://img.shields.io/crates/v/lru.svg)](https://crates.io/crates/lru)
* [mikwielgus/undoredo](https://github.com/mikwielgus/undoredo) [[undoredo](https://crates.io/crates/undoredo)] - 面向任意数据结构的撤销/重做模式实现。支持基于 delta（稀疏差异）、基于快照和基于命令的撤销重做，并为自定义类型提供 derive 宏。兼容 no_std 和 serde。[![Crates.io](https://img.shields.io/crates/v/undoredo.svg)](https://crates.io/crates/undoredo)
* [mrhooray/kdtree-rs](https://github.com/mrhooray/kdtree-rs) - K 维树，用于快速地理空间索引和最近邻查找
* [orium/rpds](https://github.com/orium/rpds) [[rpds](https://crates.io/crates/rpds)] - 持久化数据结构。[![build badge](https://github.com/orium/rpds/workflows/CI/badge.svg)](https://github.com/orium/rpds/actions?query=workflow%3ACI)
* [RoaringBitmap/roaring-rs](https://github.com/RoaringBitmap/roaring-rs) - Roaring 位图
* [rust-itertools/itertools](https://github.com/rust-itertools/itertools) - 额外的迭代器适配器、函数和宏
* [sorairolake/bit-int](https://github.com/sorairolake/bit-int) [[bit-int](https://crates.io/crates/bit-int)] - 一个任意固定位宽整数库 [![CI](https://github.com/sorairolake/bit-int/actions/workflows/CI.yaml/badge.svg?branch=develop)](https://github.com/sorairolake/bit-int/actions/workflows/CI.yaml)
* [tnballo/scapegoat](https://github.com/tnballo/scapegoat) [[scapegoat](https://crates.io/crates/scapegoat)] - `BTreeSet` 和 `BTreeMap` 的安全、可失败、仅栈替代品。[![GitHub Actions](https://github.com/tnballo/scapegoat/workflows/test/badge.svg?branch=master)](https://github.com/tnballo/scapegoat/actions)
* [yamafaktory/hypergraph](https://github.com/yamafaktory/hypergraph) [[hypergraph](https://crates.io/crates/hypergraph)] - Hypergraph 是一个用于生成有向超图的数据结构库。[![ci](https://github.com/yamafaktory/hypergraph/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/yamafaktory/hypergraph/actions/workflows/ci.yml)

### 数据可视化

* [blitzarx1/egui_graphs](https://github.com/blitzarx1/egui_graphs) [[egui_graphs](https://crates.io/crates/egui_graphs)] - 由 egui 和 petgraph 驱动的交互式图形可视化控件。[![Crates.io](https://img.shields.io/crates/v/egui_graphs)](https://crates.io/crates/egui_graphs) [![docs.rs](https://img.shields.io/docsrs/egui_graphs)](https://docs.rs/egui_graphs)
* [djduque/pgfplots](https://github.com/djduque/pgfplots) [[pgfplots](https://crates.io/crates/pgfplots)] - 用于生成出版级图形的库。[![build](https://github.com/DJDuque/pgfplots/actions/workflows/rust.yml/badge.svg)](https://github.com/DJDuque/pgfplots/actions/workflows/rust.yml)
* [mazznoer/colorgrad-rs](https://github.com/mazznoer/colorgrad-rs) [[colorgrad](https://crates.io/crates/colorgrad)] - 用于数据可视化、图表、游戏、地图、生成艺术等的颜色标度库。
* [milliams/plotlib](https://github.com/milliams/plotlib) - Rust 的数据绘图库
* [plotly](https://github.com/plotly/plotly.rs) - 面向 Rust 的 Plotly
* [plotpy](https://github.com/cpmech/plotpy) [[plotpy](https://crates.io/crates/plotpy)] - 使用 Python（Matplotlib）的 Rust 绘图库
* [plotters](https://github.com/plotters-rs/plotters) - [![build badge](https://github.com/plotters-rs/plotters/workflows/CI/badge.svg)](https://github.com/plotters-rs/plotters/actions)
* [rerun](https://github.com/rerun-io/rerun) - [[rerun](https://crates.io/crates/rerun)] - 一个用于记录计算机视觉和机器人数据（张量、点云等）的 SDK，配套一个用于随时间探索这些数据的可视化器。
* [saresend/gust](https://github.com/saresend/Gust) - 一个小型图表/可视化工具及部分 vega 实现
* [shergin/malevich](https://github.com/shergin/malevich) [[malevich](https://crates.io/crates/malevich)] - 终端绘图：折线、散点、条形、直方、热力图、箱线、小提琴等，具备自动坐标轴
* [wangjiawen2013/charton](https://github.com/wangjiawen2013/charton) - 一个 Rust 的分层图形语法库。[![Documentation](https://img.shields.io/docsrs/charton/latest)](https://docs.rs/charton) [![Build Status](https://github.com/wangjiawen2013/charton/actions/workflows/ci.yml/badge.svg)](https://github.com/wangjiawen2013/charton/actions)

### 数据库

[[database](https://crates.io/keywords/database)]

* NoSQL [[nosql](https://crates.io/keywords/nosql)]

  * [ArangoDB](https://arangodb.com)
    * [Aragog](https://gitlab.com/qonfucius/aragog) [[aragog](https://crates.io/crates/aragog)] - 一个轻量级的 ArangoDB 对象文档、关系和图映射器 [![pipeline status](https://gitlab.com/qonfucius/aragog/badges/master/pipeline.svg)](https://gitlab.com/qonfucius/aragog/-/commits/master)
    * [Arangors](https://github.com/fMeow/arangors) [[arangors](https://crates.io/crates/arangors)] - 一个 ArangoDB 驱动
  * [Cassandra](https://cassandra.apache.org/_/index.html) [[cassandra](https://crates.io/keywords/cassandra), [cql](https://crates.io/keywords/cql)]
    * [AlexPikalov/cdrs](https://github.com/AlexPikalov/cdrs) [[cdrs](https://crates.io/crates/cdrs)] - 原生客户端
    * [cassandra-rs](https://github.com/cassandra-rs/cassandra-rs) - DataStax C/C++ 的绑定
    * [krojew/cdrs-tokio](https://github.com/krojew/cdrs-tokio) - 用 100% Rust 编写的高级异步 Cassandra 客户端。[![build badge](https://github.com/krojew/cdrs-tokio/actions/workflows/rust.yml/badge.svg)](https://github.com/krojew/cdrs-tokio/actions)
      * [[cassandra-protocol](https://crates.io/crates/cassandra-protocol)] - Cassandra 协议实现。
      * [[cdrs-tokio](https://crates.io/crates/cdrs-tokio)] - 生产就绪的异步 Apache Cassandra 驱动客户端
  * CouchDB [[couchdb](https://crates.io/keywords/couchdb)]
    * [chill-rs/chill](https://github.com/chill-rs/chill) [[couchdb](https://crates.io/crates/chill)] - CouchDB REST API 的客户端
  * [DynamoDB](https://aws.amazon.com/dynamodb/) [[dynamodb](https://crates.io/keywords/dynamodb)]
    * [softprops/dynomite](https://github.com/softprops/dynomite) - 一个用于与 `rusoto_dynamodb` 进行强类型、便捷交互的库 [![build badge](https://github.com/softprops/dynomite/workflows/Main/badge.svg?branch=master)](https://github.com/softprops/dynomite/actions)
  * Elasticsearch [[elasticsearch](https://crates.io/keywords/elasticsearch)]
    * [benashford/rs-es](https://github.com/benashford/rs-es) [[rs-es](https://crates.io/crates/rs-es)] - [Elastic](https://www.elastic.co/) REST API 的客户端
    * [elastic-rs/elastic](https://github.com/elastic-rs/elastic) [[elastic](https://crates.io/crates/elastic)] - elastic 是一个用 Rust 编写的、高效、模块化的 Elasticsearch API 客户端 [![build badge](https://ci.appveyor.com/api/projects/status/csa78tcumdpnbur2?svg=true)](https://ci.appveyor.com/project/KodrAus/elastic)
  * etcd
    * [jimmycuadra/rust-etcd](https://github.com/jimmycuadra/rust-etcd) [[etcd](https://crates.io/crates/etcd)] - 面向 CoreOS 的 etcd 的客户端库。
  * [InfluxDB](https://www.influxdata.com/)
    * [driftluo/InfluxDBClient-rs](https://github.com/driftluo/InfluxDBClient-rs) - 同步接口
  * LevelDB
    * [skade/leveldb](https://github.com/skade/leveldb) - [LevelDB](https://github.com/google/leveldb) 绑定
  * [LMDB](https://www.symas.com/lmdb.php) [[lmdb](https://crates.io/keywords/lmdb)]
    * [meilisearch/heed](https://github.com/meilisearch/heed) [[heed](https://crates.io/crates/heed)] - 完全类型化的 LMDB 封装，开销最小
    * [vhbit/lmdb-rs](https://github.com/vhbit/lmdb-rs) [[lmdb-rs](https://crates.io/crates/lmdb-rs)] - LMDB 的 Rust 绑定
  * [Minigraf](https://github.com/project-minigraf/minigraf) [[minigraf](https://crates.io/crates/minigraf)] - 零配置、单文件、嵌入式图数据库，具备双时态 Datalog 查询
  * MongoDB [[mongodb](https://crates.io/keywords/mongodb)]
    * [mongodb/mongo-rust-driver](https://github.com/mongodb/mongo-rust-driver) [[mongodb](https://crates.io/crates/mongodb)] - [MongoDB](https://www.mongodb.com/) 绑定
  * [MongrelDB](https://www.mongreldb.com)
    * [visorcraft/MongrelDB](https://github.com/visorcraft/MongrelDB) [[mongreldb-core](https://crates.io/crates/mongreldb-core)] - 一个嵌入式列式数据库引擎，具备 SQL、向量搜索、全文搜索和 AI 原生检索 [![build badge](https://github.com/visorcraft/MongrelDB/actions/workflows/ci.yml/badge.svg?branch=master)](https://github.com/visorcraft/MongrelDB/actions/workflows/ci.yml)
  * [PickleDB](https://pythonhosted.org/pickleDB/)
    * [seladb/pickledb-rs](https://github.com/seladb/pickledb-rs) - 一个轻量、简单的键值存储，深受 Python 的 PickleDB 启发。
  * [PoloDB](https://www.polodb.org/)
    * [PoloDB](https://github.com/PoloDB/PoloDB) - 一个嵌入式、基于 JSON 的数据库，API 与 MongoDB 类似。![GitHub Workflow Status](https://img.shields.io/github/actions/workflow/status/PoloDB/PoloDB/rust.yml)
  * [Redb](https://www.redb.org/)
    * [Redb](https://github.com/cberner/redb) - 一个嵌入式键值数据库。它提供与其他嵌入式键值存储（如 rocksdb 和 lmdb）类似的接口。![GitHub Workflow Status](https://github.com/cberner/redb/actions/workflows/ci.yml/badge.svg)
  * Redis [[redis](https://crates.io/keywords/redis)]
    * [aembke/fred](https://github.com/aembke/fred.rs) [[fred](https://crates.io/crates/fred)] - 一个面向 Rust 的、基于 Tokio 的高级异步 [Redis](https://redis.io/) 客户端。[![CircleCI](https://circleci.com/gh/aembke/fred.rs/tree/main.svg?style=svg)]([https://circleci.com/gh/aembke/fred.rs/tree/main](https://app.circleci.com/pipelines/github/aembke/fred.rs?branch=main))
    * [redis-rs](https://github.com/redis-rs/redis-rs) - [Redis](https://redis.io/) 库 [![Rust](https://github.com/redis-rs/redis-rs/actions/workflows/rust.yml/badge.svg)](https://github.com/redis-rs/redis-rs/actions/workflows/rust.yml)
  * [RocksDB](https://rocksdb.org/)
    * [rust-rocksdb/rust-rocksdb](https://github.com/rust-rocksdb/rust-rocksdb) - RocksDB 绑定 [![RocksDB CI](https://github.com/rust-rocksdb/rust-rocksdb/actions/workflows/rust.yml/badge.svg?branch=master)](https://github.com/rust-rocksdb/rust-rocksdb/actions/workflows/rust.yml)
  * [SurrealDB](https://surrealdb.com/)
    * [surrealdb/surrealdb](https://github.com/surrealdb/surrealdb) - SurrealDB 嵌入式文档图数据库
  * [UnQLite](https://github.com/symisc/unqlite)
    * [zitsen/unqlite.rs](https://github.com/zitsen/unqlite.rs) - UnQLite 绑定
  * [ZooKeeper](https://zookeeper.apache.org/)
    * [bonifaido/rust-zookeeper](https://github.com/bonifaido/rust-zookeeper) [[zookeeper](https://crates.io/crates/zookeeper)] - 面向 Apache ZooKeeper 的客户端库。
    * [krojew/rust-zookeeper](https://github.com/krojew/rust-zookeeper) [[zookeeper-async](https://crates.io/crates/zookeeper-async)] - 基于 tokio 的异步 Zookeeper 客户端。![build status](https://github.com/krojew/rust-zookeeper/actions/workflows/rust.yml/badge.svg)
* OGM [[ogm](https://crates.io/keywords/ogm)]
    * [Aragog](https://gitlab.com/qonfucius/aragog) [[aragog](https://crates.io/crates/aragog)] - 一个轻量级的 ArangoDB 对象文档、关系和图映射器 [![pipeline status](https://gitlab.com/qonfucius/aragog/badges/master/pipeline.svg)](https://gitlab.com/qonfucius/aragog/-/commits/master)
* ORM [[orm](https://crates.io/keywords/orm)]
  * [ayarotsky/diesel-guard](https://github.com/ayarotsky/diesel-guard) - 面向 Diesel 和 SQLx 的 linter，可捕获危险的 PostgreSQL 迁移（表锁、重写、阻塞操作）并建议安全的替代方案 [![crate](https://img.shields.io/crates/v/diesel-guard.svg)](https://crates.io/crates/diesel-guard)
  * [diesel-rs/diesel](https://github.com/diesel-rs/diesel) - 一个 ORM 和查询构建器
  * [ivanceras/rustorm](https://github.com/ivanceras/rustorm) - 一个 ORM
  * [njord](https://github.com/njord-rs/njord) - ⛵ 一个多才多艺、功能丰富的 Rust ORM [![build status](https://github.com/njord-rs/njord/actions/workflows/core.yml/badge.svg)](https://github.com/njord-rs/njord/actions/workflows/core.yml) ![crates.io](https://img.shields.io/crates/v/njord.svg)
  * [rbatis/rbatis](https://github.com/rbatis/rbatis) - 高性能 ORM 框架（基于 JSON）
  * [SeaQL/sea-orm](https://github.com/SeaQL/sea-orm) - 🐚 一个异步且动态的 ORM [![crate](https://img.shields.io/crates/v/sea-orm.svg)](https://crates.io/crates/sea-orm) [![docs](https://img.shields.io/docsrs/sea-orm/latest)](https://docs.rs/sea-orm) [![build status](https://github.com/SeaQL/sea-orm/actions/workflows/rust.yml/badge.svg)](https://github.com/SeaQL/sea-orm/actions/workflows/rust.yml)
  * [SeaQL/seaography](https://github.com/SeaQL/seaography) - 🧭 面向 SeaORM 的 GraphQL 框架 [![crate](https://img.shields.io/crates/v/seaography.svg)](https://crates.io/crates/seaography) [![docs](https://img.shields.io/docsrs/seaography/latest)](https://docs.rs/seaography) [![build status](https://github.com/SeaQL/seaography/actions/workflows/tests.yaml/badge.svg)](https://github.com/SeaQL/seaography/actions/workflows/tests.yaml)
  * [thegenius/taitan-orm](https://github.com/thegenius/taitan-orm) - Rust 最先进的 ORM，异步且编译期生成。
* [sfackler/r2d2](https://github.com/sfackler/r2d2) - 通用连接池
* SQL [[sql](https://crates.io/keywords/sql)]
  * 通用
    * [launchbadge/sqlx](https://github.com/launchbadge/sqlx) - 异步 PostgreSQL/MySQL/SQLite 连接池，具备强类型支持 [![build badge](https://img.shields.io/github/workflow/status/launchbadge/sqlx/Rust/master?style=flat-square)](https://github.com/launchbadge/sqlx)
    * [SeaQL/sea-query](https://github.com/SeaQL/sea-query) - 🔱 面向 MySQL、Postgres 和 SQLite 的动态 SQL 查询构建器 [![crate](https://img.shields.io/crates/v/sea-query.svg)](https://crates.io/crates/sea-query) [![docs](https://img.shields.io/docsrs/sea-query/latest)](https://docs.rs/sea-query) [![build status](https://github.com/SeaQL/sea-query/actions/workflows/rust.yml/badge.svg)](https://github.com/SeaQL/sea-query/actions/workflows/rust.yml)
    * [SeaQL/sea-schema](https://github.com/SeaQL/sea-schema) - 🌿 SQL schema 定义和发现 [![crate](https://img.shields.io/crates/v/sea-schema.svg)](https://crates.io/crates/sea-schema) [![docs](https://img.shields.io/docsrs/sea-schema/latest)](https://docs.rs/sea-schema) [![build status](https://github.com/SeaQL/sea-schema/actions/workflows/rust.yml/badge.svg)](https://github.com/SeaQL/sea-schema/actions/workflows/rust.yml)
  * Microsoft SQL
    * [prisma/tiberius](https://github.com/prisma/tiberius) - [![Cargo tests](https://github.com/prisma/tiberius/actions/workflows/test.yml/badge.svg?branch=master)](https://github.com/prisma/tiberius/actions/workflows/test.yml)
  * MySql [[mysql](https://crates.io/keywords/mysql)]
    * [AgilData/mysql-proxy-rs](https://github.com/AgilData/mysql-proxy-rs) - 一个 MySQL 代理 [![CircleCI](https://circleci.com/gh/AgilData/mysql-proxy-rs/tree/master.svg?style=svg)](https://app.circleci.com/pipelines/github/AgilData/mysql-proxy-rs?branch=master)
    * [blackbeam/mysql_async](https://github.com/blackbeam/mysql_async) [[mysql_async](https://crates.io/crates/mysql_async)] - 基于 Tokio 的异步 Mysql 驱动。[![CircleCI](https://circleci.com/gh/blackbeam/mysql_async/tree/master.svg?style=shield)](https://app.circleci.com/pipelines/github/blackbeam/mysql_async?branch=master)
    * [blackbeam/rust-mysql-simple](https://github.com/blackbeam/rust-mysql-simple) [[mysql](https://crates.io/crates/mysql)] - 一个原生 MySql 客户端
  * Oracle
    * [kubo/rust-oracle](https://github.com/kubo/rust-oracle) [[oracle](https://crates.io/crates/oracle)] - Oracle 驱动 [![build badge](https://github.com/kubo/rust-oracle/actions/workflows/run-tests.yml/badge.svg?branch=master)](https://github.com/kubo/rust-oracle/actions/workflows/run-tests.yml)
  * PostgreSql [[postgres](https://crates.io/keywords/postgres), [postgresql](https://crates.io/keywords/postgresql)]
    * [c410-f3r/wtx](https://github.com/c410-f3r/wtx) - 外部依赖极少的快速实现。
    * [isdaniel/pg-walstream](https://github.com/isdaniel/pg-walstream) - 面向 PostgreSQL 逻辑和物理复制流的高性能异步 CDC（变更数据捕获）库。[![Crates.io Version](https://img.shields.io/crates/v/pg_walstream)](https://crates.io/crates/pg_walstream)
    * [rust-postgres](https://github.com/rust-postgres/rust-postgres) [[postgres](https://crates.io/crates/postgres)] - 一个原生 [PostgreSQL](https://www.postgresql.org/) 客户端
  * Sqlite [[sqlite](https://crates.io/keywords/sqlite)]
    * [rusqlite](https://github.com/rusqlite/rusqlite) - [Sqlite3](https://sqlite.org/index.html) 绑定
* [VennDB](https://venndb.plabayo.tech/) [[venndb](https://github.com/plabayo/venndb)] - 一个用 Rust 编写的仅追加内存数据库，面向使用位（标志）列查询的行。

### 日期与时间

[[date](https://crates.io/keywords/date), [time](https://crates.io/keywords/time)]

* [arthurhenrique/rusti-cal](https://github.com/arthurhenrique/rusti-cal) [[rusti-cal](https://crates.io/crates/rusti-cal)] - 一个闪电般快速的 cal(1) 克隆 ~ 超过 9999 年 ~ 用 Rust 编写。
* [burntSushi/jiff](https://github.com/BurntSushi/jiff) - 一个鼓励你跃入成功之坑的 Rust 日期时间库。[![Build status](https://github.com/BurntSushi/jiff/workflows/ci/badge.svg)](https://github.com/BurntSushi/jiff/actions)
* [chronotope/chrono](https://github.com/chronotope/chrono) - 日期和时间库
* [Mnwa/ms](https://github.com/Mnwa/ms) [[ms-converter](https://crates.io/crates/ms-converter)] - 一个将人类可读时间转换为毫秒的库 [![build badge](https://github.com/Mnwa/ms/workflows/build/badge.svg?branch=master)](https://github.com/Mnwa/ms/actions?query=workflow%3Abuild)
* [sorairolake/dos-date-time](https://github.com/sorairolake/dos-date-time) [[dos-date-time](https://crates.io/crates/dos-date-time)] - 一个 MS-DOS 日期和时间库 [![CI](https://github.com/sorairolake/dos-date-time/actions/workflows/CI.yaml/badge.svg?branch=develop)](https://github.com/sorairolake/dos-date-time/actions/workflows/CI.yaml)
* [sorairolake/nt-time](https://github.com/sorairolake/nt-time) [[nt-time](https://crates.io/crates/nt-time)] - 一个 Windows 文件时间库。[![CI](https://github.com/sorairolake/nt-time/workflows/CI/badge.svg?branch=develop)](https://github.com/sorairolake/nt-time/actions?query=workflow%3ACI)
* [time-rs/time](https://github.com/time-rs/time) - [![build badge](https://github.com/time-rs/time/workflows/Build/badge.svg)](https://github.com/time-rs/time/actions)

### 分布式系统

* Antimony
  * [antimonyproject/antimony](https://github.com/antimonyproject/antimony) [[antimony](https://crates.io/crates/antimony)] - 流处理/分布式计算平台
* Apache Kafka
  * [fede1024/rust-rdkafka](https://github.com/fede1024/rust-rdkafka) [[rdkafka](https://crates.io/crates/rdkafka)] - [librdkafka](https://github.com/confluentinc/librdkafka) 绑定
  * [gklijs/schema_registry_converter](https://github.com/gklijs/schema_registry_converter) [[schema_registry_converter](https://crates.io/crates/schema_registry_converter)] - 用于与 [confluent schema registry](https://www.confluent.io/product/confluent-platform/data-compatibility/) 集成
  * [kafka-rust/kafka-rust](https://github.com/kafka-rust/kafka-rust) - Apache Kafka 的 Rust 客户端
* HDFS
  * [hyunsik/hdfs-rs](https://github.com/hyunsik/hdfs-rs) [[hdfs](https://crates.io/crates/hdfs)] - libhdfs 绑定
* 其他
  * [build-trust/ockam](https://github.com/build-trust/ockam) [[ockam](https://crates.io/crates/ockam)] - 面向分布式应用的端到端加密、双向认证和 ABAC [![build badge](https://github.com/build-trust/ockam/workflows/Rust/badge.svg)](https://github.com/build-trust/ockam)
  * [zannis/shove](https://github.com/zannis/shove) [[shove](https://crates.io/crates/shove)] - 类型安全的异步发布/订阅，在 RabbitMQ、Kafka、NATS JetStream、AWS SNS/SQS 和 Redis Streams 之上提供一致的 API，具备重试、死信队列路由和自动伸缩消费者组 [![CI](https://github.com/zannis/shove/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/zannis/shove/actions/workflows/ci.yml)

### 领域驱动设计

  * [serverlesstechnology/cqrs](https://github.com/serverlesstechnology/cqrs) [[cqrs-es](https://crates.io/crates/cqrs-es)] - 一个用于 CQRS 和事件溯源的框架，带[用户指南](https://doc.rust-cqrs.org/)

### eBPF

* [aya/aya-rs](https://github.com/aya-rs/aya) - 以开发者体验和可操作性为重点构建。
* [libbpf/libbpf-rs](https://github.com/libbpf/libbpf-rs) - 一个极简且有主见的 eBPF 工具集。

### 电子邮件

[[email](https://crates.io/keywords/email), [imap](https://crates.io/keywords/imap), [smtp](https://crates.io/keywords/smtp)]

* [duesee/imap-codec](https://github.com/duesee/imap-codec) [[imap-codec](https://crates.io/crates/imap-codec)] - 坚如磐石且完整的 IMAP 编解码器 [![Build & Test](https://github.com/duesee/imap-codec/actions/workflows/build_and_test.yml/badge.svg)](https://github.com/duesee/imap-codec/actions/workflows/build_and_test.yml)
* [gsquire/sendgrid-rs](https://github.com/gsquire/sendgrid-rs) - 面向 SendGrid API 的库
* [jdrouet/catapulte](https://github.com/jdrouet/catapulte) - 一个使用 [MRML](https://github.com/jdrouet/mrml) 模板发送电子邮件的微服务。
* [jdrouet/jolimail](https://github.com/jdrouet/jolimail) - 一个用于构建 [MRML](https://github.com/jdrouet/mrml) 模板的 Web 应用。
* [jdrouet/mrml](https://github.com/jdrouet/mrml) - 一个用于生成在任何邮件客户端都能正常显示的漂亮邮件模板的库。
* [lettre/lettre](https://github.com/lettre/lettre) - 一个 SMTP 库 [![CI](https://github.com/lettre/lettre/actions/workflows/test.yml/badge.svg?branch=master)](https://github.com/lettre/lettre/actions/workflows/test.yml)
* [mailtutan/mailtutan](https://github.com/mailtutan/mailtutan) - 一个用于测试和开发环境的 SMTP 服务器。
* [meli/meli](https://github.com/meli/meli) - 🐝 终端邮件客户端
* [reacherhq/check-if-email-exists](https://github.com/reacherhq/check-if-email-exists) [[check-if-email-exists](https://crates.io/crates/check-if-email-exists)] - 在不发送任何邮件的情况下检查邮箱地址是否存在，具备 SMTP 验证、一次性地址检测和 catch-all 检查 [![Actions Status](https://github.com/reacherhq/check-if-email-exists/workflows/pr/badge.svg)](https://github.com/reacherhq/check-if-email-exists/actions)
* [rustmailer/bichon](https://github.com/rustmailer/bichon) - 一个轻量、高性能的邮件归档器，具备全文搜索和 WebUI。
* [staktrace/mailparse](https://github.com/staktrace/mailparse) [[mailparse](https://crates.io/crates/mailparse)] - 一个用于解析真实世界邮件文件的库
* [stalwartlabs/mail-auth](https://github.com/stalwartlabs/mail-auth) [[mail-auth](https://crates.io/crates/mail-auth)] - DKIM、ARC、SPF 和 DMARC 邮件认证库 [![build badge](https://github.com/stalwartlabs/mail-auth/actions/workflows/rust.yml/badge.svg)](https://github.com/stalwartlabs/mail-auth/actions/workflows/rust.yml)
* [stalwartlabs/mail-parser](https://github.com/stalwartlabs/mail-parser) [[mail-parser](https://crates.io/crates/mail-parser)] - 一个快速、稳健、完整支持 MIME 的电子邮件解析库 [![build badge](https://github.com/stalwartlabs/mail-parser/actions/workflows/rust.yml/badge.svg)](https://github.com/stalwartlabs/mail-parser/actions/workflows/rust.yml)
* [stalwartlabs/mail-send](https://github.com/stalwartlabs/mail-send) [[mail-send](https://crates.io/crates/mail-send)] - 具备 DKIM 支持的电子邮件构建器和 SMTP 客户端库 [![build badge](https://github.com/stalwartlabs/mail-send/actions/workflows/rust.yml/badge.svg)](https://github.com/stalwartlabs/mail-send/actions/workflows/rust.yml)
* [tweedegolf/mailcrab](https://github.com/tweedegolf/mailcrab) - 用于开发的邮件测试服务器。

### 编码

[[encoding](https://crates.io/keywords/encoding)]

* ASN.1
  * [alex/rust-asn1](https://github.com/alex/rust-asn1) - ASN.1（DER）序列化器
* 条码
  * [rxing-core/rxing](https://github.com/rxing-core/rxing) [[rxing](https://crates.io/crates/rxing)] - zxing 条码库的 Rust 移植。[![Rust](https://github.com/rxing-core/rxing/actions/workflows/rust.yml/badge.svg?branch=main)](https://github.com/rxing-core/rxing/actions/workflows/rust.yml)
* 二进制
  * [bincode](https://crates.io/crates/bincode) - 一个二进制编码器/解码器
  * [bincode-next](https://crates.io/crates/bincode-next) - 一个二进制编码器/解码器，现已不再维护的 bincode 的继任者
  * [jamesmunns/postcard](https://github.com/jamesmunns/postcard) [[postcard](https://crates.io/crates/postcard)] - Postcard 是一个面向 #![no_std] 的 Serde 序列化器和反序列化器。
  * [m4b/goblin](https://github.com/m4b/goblin) [[goblin](https://crates.io/crates/goblin)] - 跨平台、零拷贝且感知字节序的二进制解析
* BSON
  * [mongodb/bson-rust](https://github.com/mongodb/bson-rust) - BSON 的编码和解码支持
* 字节序转换
  * [BurntSushi/byteorder](https://github.com/BurntSushi/byteorder) - 支持大端、小端和原生字节序
* Cap'n Proto
  * [capnproto/capnproto-rust](https://github.com/capnproto/capnproto-rust) - Cap'n Proto 是一种面向分布式系统的类型系统
* CBOR
  * [serde_cbor](https://crates.io/crates/serde_cbor) - 为 serde 提供 CBOR 支持
* 字符编码
  * [hsivonen/encoding_rs](https://github.com/hsivonen/encoding_rs) [[encoding_rs](https://crates.io/crates/encoding_rs)] - 一个面向 Gecko 的编码标准实现
  * [lifthrasiir/rust-encoding](https://github.com/lifthrasiir/rust-encoding) - Rust 的字符编码支持。（又称 rust-encoding）它基于 WHATWG 编码标准，还提供用于错误检测和恢复的高级接口。
* CRC
  * [mrhooray/crc-rs](https://github.com/mrhooray/crc-rs) - CRC(16, 32, 64) 的 Rust 实现，支持多种标准
* CSV
  * [BurntSushi/rust-csv](https://github.com/BurntSushi/rust-csv) - 一个快速灵活的 CSV 读写器，支持 Serde
* Data Matrix
  * [jannschu/datamatrix-rs](https://github.com/jannschu/datamatrix-rs) [[datamatrix](https://crates.io/crates/datamatrix)] - Data Matrix（ECC 200）解码和编码，具备优化编码器 [![CI](https://github.com/jannschu/datamatrix-rs/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/jannschu/datamatrix-rs/actions/workflows/ci.yml)
* EDN
  * [edn-rs](https://github.com/naomijub/edn-rs) [[edn-rs](https://crates.io/crates/edn-rs)] - 用于将 EDN 格式解析并输出为 Rust 类型的 crate。
* [FlatBuffers](https://flatbuffers.dev/)
  * [frol/flatc-rust](https://github.com/frol/flatc-rust) - 面向 Cargo 构建脚本的 FlatBuffers 编译器（flatc）集成
* HAR
  * [mandrean/har-rs](https://github.com/mandrean/har-rs) [[har](https://crates.io/crates/har)] - 一个 HTTP Archive 格式（HAR）序列化和反序列化库
* HTML
  * [servo/html5ever](https://github.com/servo/html5ever) - 高性能、浏览器级 HTML5 解析器
* JSON
  * [cloudwego/sonic-rs](https://github.com/cloudwego/sonic-rs) [[sonic-rs](https://crates.io/crates/sonic-rs)] - 一个基于 SIMD 的快速 Rust JSON 库。
  * [importcjj/rust-ajson](https://github.com/importcjj/rust-ajson) [[ajson](https://crates.io/crates/ajson)] - 快速获取 JSON 值
  * [rustadopt/jzon-rs](https://github.com/rustadopt/jzon-rs/) [[jzon](https://crates.io/crates/jzon)] - JSON 实现
  * [serde-rs/json](https://github.com/serde-rs/json) [[serde\_json](https://crates.io/crates/serde_json)] - 为 [Serde](https://github.com/serde-rs/serde) 框架提供 JSON 支持
  * [simd-lite/simd-json](https://github.com/simd-lite/simd-json) [[simd-json](https://crates.io/crates/simd-json)] - 基于 simdjson 移植的高性能 JSON 解析器
  * [vcschapp/bufjson](https://github.com/vcschapp/bufjson) [[bufjson](https://crates.io/crates/bufjson)] - 流式 JSON 解析器和词法分析器，无拷贝/无分配，可选流式 JSON Pointer 求值器
* MsgPack
  * [3Hren/msgpack-rust](https://github.com/3Hren/msgpack-rust) - 低/高级 MessagePack 实现
* NetCDF
  * [georust/netcdf](https://github.com/georust/netcdf) [[netcdf](https://crates.io/crates/netcdf)] - 中等层级的 netCDF 绑定，便于将类数组结构轻松读写到文件。
* PEM
  * [jcreekmore/pem-rs](https://github.com/jcreekmore/pem-rs) [[pem](https://crates.io/crates/pem)] - 解析和编码 PEM 编码数据
* ProtocolBuffers
  * [stepancheg/rust-protobuf](https://github.com/stepancheg/rust-protobuf) - Google protocol buffers 的 Rust 实现
  * [tokio-rs/prost](https://github.com/tokio-rs/prost) - [![continuous integration](https://github.com/tokio-rs/prost/workflows/continuous%20integration/badge.svg?branch=master)](https://github.com/tokio-rs/prost/actions)
* 二维码
  * [magiclen/qrcode-generator](https://github.com/magiclen/qrcode-generator) [[qrcode-generator](https://crates.io/crates/qrcode-generator)] - 用纯 Rust 生成 ISO/IEC 18004 二维码和 Micro 二维码符号以及 ISO/IEC 23941 rMQR 符号，并将其渲染为灰度、PNG 和 SVG 图像。[![CI](https://github.com/magiclen/qrcode-generator/actions/workflows/ci.yml/badge.svg?branch=master)](https://github.com/magiclen/qrcode-generator/actions/workflows/ci.yml)
  * [sorairolake/qrcode-rust2](https://github.com/sorairolake/qrcode-rust2) [[qrcode2](https://crates.io/crates/qrcode2)] - 一个二维码编码库 [![CI](https://github.com/sorairolake/qrcode-rust2/actions/workflows/CI.yaml/badge.svg?branch=main)](https://github.com/sorairolake/qrcode-rust2/actions/workflows/CI.yaml)
  * [WanzenBug/rqrr](https://github.com/WanzenBug/rqrr) [[rqrr](https://crates.io/crates/rqrr)] - 从任意图像源检测和读取二维码 [![CI](https://github.com/WanzenBug/rqrr/actions/workflows/CI.yaml/badge.svg?branch=master)](https://github.com/WanzenBug/rqrr/actions/workflows/CI.yaml)
* rkyv
  * [rkyv/rkyv](https://github.com/rkyv/rkyv) [[rkyv](https://crates.io/crates/rkyv)] - rkyv（archive）是一个零拷贝反序列化框架
* RON（Rusty Object Notation）
  * [https://github.com/ron-rs/ron](https://github.com/ron-rs/ron) - Rusty Object Notation
* Serde
  * [iddm/serde-aux](https://github.com/iddm/serde-aux/) - 用于配合 serde 库的附加工具。[![CI](https://github.com/iddm/serde-aux/actions/workflows/ci.yml/badge.svg)](https://github.com/iddm/serde-aux/actions/workflows/ci.yml) [![Crates badge](https://img.shields.io/crates/v/serde-aux.svg)](https://crates.io/crates/serde-aux)
* TOML
  * [tamasfe/taplo](https://github.com/tamasfe/taplo) [[taplo](https://crates.io/crates/taplo)] - 一个 TOML 工具集 [![CI](https://github.com/tamasfe/taplo/workflows/Continuous%20integration/badge.svg)](https://github.com/tamasfe/taplo/actions?query=workflow%3A%22Continuous+integration%22)
  * [toml-rs/toml](https://github.com/toml-rs/toml) - [![CI](https://github.com/toml-rs/toml/actions/workflows/ci.yml/badge.svg)](https://github.com/toml-rs/toml/actions/workflows/ci.yml)
* [vitiral/stfu8](https://github.com/vitiral/stfu8) [[stfu8](https://crates.io/crates/stfu8)] - UTF-8 中的某种文本格式
* XML
  * [Florob/RustyXML](https://github.com/Florob/RustyXML) - 一个 XML 解析器
  * [netvl/xml-rs](https://github.com/netvl/xml-rs) - 一个流式 XML 库
  * [shepmaster/sxd-document](https://github.com/shepmaster/sxd-document) - 一个 XML 库
  * [shepmaster/sxd-xpath](https://github.com/shepmaster/sxd-xpath) - 一个 XPath 库
  * [tafia/quick-xml](https://github.com/tafia/quick-xml) - 高性能 XML 拉取式读取器/写入器
  * [yaserde](https://github.com/luminvent/yaserde) - 又一个专用于 XML 的序列化器/反序列化器
* YAML
  * [chyh1990/yaml-rust](https://github.com/chyh1990/yaml-rust) - 缺失的 YAML 1.2 实现。
  * [saphyr](https://github.com/saphyr-rs/saphyr) - 一组专用于解析 YAML 的 crate。
  * [serde-saphyr](https://github.com/bourumir-wyngs/serde-saphyr) - 面向 Serde 的 YAML（反）序列化器，强调无 panic 解析和良好的错误报告 [![crates.io](https://img.shields.io/crates/d/serde-saphyr.svg)](https://crates.io/crates/serde-saphyr)

### 文件系统

[[filesystem](https://crates.io/keywords/filesystem)]
* 操作
  * [Camino](https://github.com/camino-rs/camino) [[camino](https://crates.io/crates/camino)] - 类似 Rust 的 std::path::Path，但为 UTF-8。
  * [dmtrKovalenko/fff](https://github.com/dmtrKovalenko/fff) [[fff-search](https://crates.io/crates/fff-search)] - 抗拼写错误的文件和内容搜索库，具备频率-近期（frecency）排序、git 感知注解、后台监视器和轻量级内存内容索引。提供 MCP 服务器、Node/Bun SDK、C 库和 Neovim 插件。
  * [dnbln/dir-structure](https://github.com/dnbln/dir-structure) [[dir-structure](https://crates.io/crates/dir-structure)] - 用普通 Rust 结构对文件系统树进行建模。[![Tests](https://github.com/dnbln/dir-structure/actions/workflows/test-dir-structure.yml/badge.svg?branch=trunk)](https://github.com/dnbln/dir-structure/actions/workflows/test-dir-structure.yml)
  * [OpenDAL](https://github.com/apache/opendal) [[opendal](https://crates.io/crates/opendal)] - 一个统一的数据访问层，让用户能够无缝、高效地从各种存储服务中检索数据。[![build](https://img.shields.io/github/actions/workflow/status/apache/opendal/ci_core.yml?branch=main)](https://github.com/apache/opendal/actions?query=branch%3Amain)
  * [ParthJadhav/Rust_Search](https://github.com/ParthJadhav/Rust_Search) [[rust_search](https://crates.io/crates/rust_search)] - 极快的文件搜索库。
  * [pop-os/dbus-udisks2](https://github.com/pop-os/dbus-udisks2) [[dbus-udisks2](https://crates.io/crates/dbus-udisks2)] - UDisks2 DBus API
  * [pop-os/sys-mount](https://github.com/pop-os/sys-mount) [[sys-mount](https://crates.io/crates/sys-mount)] - 对 `mount` / `umount2` 系统调用的高级抽象。
  * [vitiral/path_abs](https://github.com/vitiral/path_abs) [[path_abs](https://crates.io/crates/path_abs)] - 绝对可序列化路径类型及相关方法。
  * [webdesus/fs_extra](https://github.com/webdesus/fs_extra) - 扩展标准库 std::fs 和 std::io 的能力
* 临时文件
  * [Stebalien/tempfile](https://github.com/Stebalien/tempfile) - 临时文件库
  * [Stebalien/xattr](https://github.com/Stebalien/xattr) [[xattr](https://crates.io/crates/xattr)] - 列出和操作 unix 扩展文件属性
  * [zboxfs/zbox](https://github.com/zboxfs/zbox) [[zbox](https://crates.io/crates/zbox)] - 零细节、注重隐私的可嵌入文件系统。

### 金融

* [avhz/RustQuant](https://github.com/avhz/RustQuant) [[RustQuant](https://crates.io/crates/RustQuant)] - 一个量化金融库。![GitHub Workflow Status (with event)](https://img.shields.io/github/actions/workflow/status/avhz/RustQuant/build.yml)
* [d-e-s-o/apca](https://github.com/d-e-s-o/apca) [[apca](https://crates.io/crates/apca)] - 面向 [Alpaca API](https://alpaca.markets/) 的有主见且全面的绑定，用于股票交易等。![GitHub Workflow Status](https://github.com/d-e-s-o/apca/actions/workflows/test.yml/badge.svg?branch=main)
* [kand-ta/kand](https://github.com/kand-ta/kand) [[kand](https://crates.io/crates/kand)] - 一个现代、高性能的技术分析库，支持 Rust、Python 和 JS/TS(WASM)。[![image](https://img.shields.io/crates/v/kand.svg)](https://crates.io/crates/kand)
* [rust-dd/stochastic-rs](https://github.com/rust-dd/stochastic-rs) [[stochastic-rs](https://crates.io/crates/stochastic-rs)] - 量化金融：130+ 随机过程、期权定价和校准、波动率曲面和 copula，具备 SIMD/GPU 加速和 Python 绑定。![GitHub Workflow Status](https://github.com/rust-dd/stochastic-rs/actions/workflows/rust.yml/badge.svg?branch=main)
* [wickra-lib/wickra](https://github.com/wickra-lib/wickra) [[wickra](https://crates.io/crates/wickra)] - 流式优先的技术分析：514 个指标，每次 tick 更新为 O(1)，来自 Rust 核心，具备原生 Python、Node.js 和 WASM 绑定，以及面向 C、C++、C#、Go、Java 和 R 的 C ABI 中枢。[![CI](https://github.com/wickra-lib/wickra/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/wickra-lib/wickra/actions/workflows/ci.yml)

### 函数式编程

[[functional programming](https://crates.io/keywords/fp)]
* Prelude
  * [JasonShin/fp-core.rs](https://github.com/JasonShin/fp-core.rs) - 一个用于函数式编程的库
  * [myrrlyn/tap](https://github.com/myrrlyn/tap) - 后缀位置管道行为

### 游戏开发

另见 [Are we game yet?](https://arewegameyet.rs)
* Allegro
  * [SiegeLord/RustAllegro](https://github.com/SiegeLord/RustAllegro) - [Allegro 5](https://liballeg.org/) 绑定
* [Awesome Quads](https://github.com/ozkriff/awesome-quads) - 与 miniquad/macroquad 相关代码和资源的精选链接列表
* [Awesome wgpu](https://github.com/rofrol/awesome-wgpu) - wgpu 代码和资源的精选列表
* bracket-lib（原 RLTK）
  * [bracket-lib](https://github.com/amethyst/bracket-lib) [[bracket-lib](https://crates.io/crates/bracket-lib)] - Roguelike 工具包（RLTK）。[![Rust](https://github.com/amethyst/bracket-lib/actions/workflows/rust.yml/badge.svg)](https://github.com/amethyst/bracket-lib/actions/workflows/rust.yml)
* Challonge
  * [iddm/challonge-rs](https://github.com/iddm/challonge-rs) [[challonge](https://crates.io/crates/challonge)] - Challonge REST API 的客户端库。有助于组织锦标赛。[![CI](https://github.com/iddm/challonge-rs/actions/workflows/ci.yml/badge.svg)](https://github.com/iddm/challonge-rs/actions/workflows/ci.yml)
* 实体组件系统（ECS）
  * [amethyst/specs](https://github.com/amethyst/specs) - Specs 并行 ECS
  * [legion](https://github.com/amethyst/legion) - 一个功能丰富的高性能 ECS 库，样板代码极少 [![build badge](https://github.com/amethyst/legion/workflows/CI/badge.svg?branch=master)](https://github.com/amethyst/legion/actions)
* 游戏引擎
  * [AscendingCreations/AscendingGraphics](https://github.com/AscendingCreations/AscendingGraphics) - 一个使用 WGPU 和 Winit 的 2D 渲染框架。- [![Crates.io](https://img.shields.io/crates/v/ascending_graphics.svg)](https://crates.io/crates/ascending_graphics) [![license](https://img.shields.io/crates/l/ascending_graphics.svg)](https://github.com/AscendingCreations/AscendingGraphics/blob/main/LICENSE.MIT) [![Crates.io](https://img.shields.io/crates/d/ascending_graphics.svg)](https://crates.io/crates/ascending_graphics)
  * [Balaur](https://github.com/balaurengine/balaur) - 一个确定性 2D 和 3D 游戏引擎，具备 Rune 脚本、Rapier 物理和内置编辑器 [![Test](https://github.com/balaurengine/balaur/actions/workflows/test.yml/badge.svg?branch=main)](https://github.com/balaurengine/balaur/actions/workflows/test.yml)
  * [Bevy](https://github.com/bevyengine/bevy) - 一个清新简洁、数据驱动的游戏引擎。- [![Crates.io](https://img.shields.io/crates/v/bevy.svg)](https://crates.io/crates/bevy) [![Crates.io](https://img.shields.io/crates/d/bevy.svg)](https://crates.io/crates/bevy)
  * [euv-engine](https://github.com/euv-dev/euv) [[euv-engine](https://crates.io/crates/euv-engine)] - 一个构建在 euv 框架之上的高性能 2D 游戏引擎，具备 ECS、固定时间步游戏循环、画布渲染、物理、碰撞检测、精灵动画和音频。
  * [Fyrox](https://fyrox.rs/) - 3D 游戏引擎 [![Crates.io](https://img.shields.io/crates/v/fyrox.svg)](https://crates.io/crates/fyrox) [![license](https://img.shields.io/crates/l/fyrox.svg)](https://github.com/FyroxEngine/Fyrox/blob/master/LICENSE.md) [![Crates.io](https://img.shields.io/crates/d/fyrox.svg)](https://crates.io/crates/fyrox)
  * [ggez](https://github.com/ggez/ggez) - 一个轻量级游戏框架，以最小的阻力制作 2D 游戏 - [![Crates.io](https://img.shields.io/crates/v/ggez.svg)](https://crates.io/crates/ggez) [![license](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/ggez/ggez/blob/master/LICENSE) [![Crates.io](https://img.shields.io/crates/d/ggez.svg)](https://crates.io/crates/ggez)
  * [Kiss3d](https://github.com/dimforge/kiss3d) - 一个 Keep It Simple, Stupid 的 3D 图形引擎 [![Crates.io](https://img.shields.io/crates/d/kiss3d.svg)](https://crates.io/crates/kiss3d)
  * [oxidator](https://github.com/Ruddle/oxidator) - 一个支持 WebGPU 的即时战略游戏/引擎
  * [Piston](https://www.piston.rs/) - [![Crates.io](https://img.shields.io/crates/v/piston.svg?style=flat-square)](https://crates.io/crates/piston) [![Crates.io](https://img.shields.io/crates/l/piston.svg)](https://github.com/PistonDevelopers/piston/blob/master/LICENSE) [![Crates.io](https://img.shields.io/crates/d/piston.svg)](https://crates.io/crates/piston)
  * [Unrust](https://github.com/unrust/unrust) - Webgl 2.0 / 原生游戏引擎
* 游戏服务器
  * [gamedig/rust-gamedig](https://github.com/gamedig/rust-gamedig) [[gamedig](https://crates.io/crates/gamedig)] - 查询游戏服务器以获取名称、在线玩家、最大玩家数等信息 [![Crates.io](https://img.shields.io/crates/v/gamedig.svg)](https://crates.io/crates/gamedig) [![Crates.io](https://img.shields.io/crates/d/gamedig.svg)](https://crates.io/crates/gamedig)
* [Godot](https://godotengine.org/)
  * [adalinesimonian/gdvm](https://github.com/adalinesimonian/gdvm) - 面向 CLI 的 Godot 版本管理器 [![CI](https://github.com/adalinesimonian/gdvm/actions/workflows/build-and-test.yml/badge.svg)](https://github.com/adalinesimonian/gdvm/actions/workflows/build-and-test.yml)
  * [godot-rust/gdext](https://github.com/godot-rust/gdext) [[gdext](https://crates.io/crates/gdext)] - Godot 4+ 游戏引擎的绑定 [![CI](https://github.com/godot-rust/gdext/actions/workflows/full-ci.yml/badge.svg)](https://github.com/godot-rust/gdext/actions/workflows/full-ci.yml)
  * [godot-rust/gdnative](https://github.com/godot-rust/gdnative) [[gdnative](https://crates.io/crates/gdnative)] - Godot 3+ 游戏引擎的绑定 [![CI](https://github.com/godot-rust/gdnative/actions/workflows/full-ci.yml/badge.svg)](https://github.com/godot-rust/gdnative/actions/workflows/full-ci.yml)
* Minecraft
  * [bedrock-crustaceans/bedrock-rs](https://github.com/bedrock-crustaceans/bedrock-rs) - 用于 Rust 的 Minecraft 基岩版开发通用工具包。[![GitHub stars](https://img.shields.io/github/stars/bedrock-crustaceans/bedrock-rs)](https://github.com/bedrock-crustaceans/bedrock-rs) [![CI](https://github.com/bedrock-crustaceans/bedrock-rs/actions/workflows/ci.yml/badge.svg)](https://github.com/bedrock-crustaceans/bedrock-rs/actions/workflows/ci.yml)
  * [FerrumC](https://github.com/ferrumc-rs/ferrumc) - 用 Rust 对原版 Minecraft 服务器的升级 [![build badge](https://github.com/ferrumc-rs/ferrumc/actions/workflows/rust.yml/badge.svg)]
  * [Pumpkin](https://github.com/pumpkin-mc/pumpkin) - 一个完全用 Rust 编写的高性能 Minecraft 服务器软件
  * [SteelMC](https://github.com/Steel-Foundation/SteelMC) - 一个用 Rust 构建、注重性能和一致性的 Minecraft 服务器
* [Raylib](https://www.raylib.com/)
  * [deltaphc/raylib-rs](https://github.com/deltaphc/raylib-rs) [[raylib](https://crates.io/crates/raylib)] - raylib 的绑定
* [SDL](https://www.libsdl.org/) [[sdl](https://crates.io/keywords/sdl)]
  * [brson/rust-sdl](https://github.com/brson/rust-sdl) - SDL1 绑定
  * [Rust-SDL2/rust-sdl2](https://github.com/Rust-SDL2/rust-sdl2) - SDL2 绑定
* SFML
  * [jeremyletang/rust-sfml](https://github.com/jeremyletang/rust-sfml) - [SFML](https://www.sfml-dev.org/) 绑定
* Skillratings
  * [atomflunder/skillratings](https://github.com/atomflunder/skillratings) [[skillratings](https://crates.io/crates/skillratings)] - 面向多人游戏的技能评分算法集合，如 Elo、Glicko-2、TrueSkill 等。[![crates.io badge](https://img.shields.io/crates/v/skillratings)](https://crates.io/crates/skillratings) [![CI](https://github.com/atomflunder/skillratings/actions/workflows/ci.yml/badge.svg)](https://github.com/atomflunder/skillratings/actions/workflows/ci.yml)
* Tatami
  * [giraffekey/tatami](https://github.com/giraffekey/tatami) [[tatami](https://crates.io/crates/tatami-dungeon)] - 一个 roguelike 地牢生成算法。
* Toornament-rs
  * [iddm/toornament-rs](https://github.com/iddm/toornament-rs) - Toornament.com API 绑定。[![CI](https://github.com/iddm/toornament-rs/actions/workflows/ci.yml/badge.svg)](https://github.com/iddm/toornament-rs/actions/workflows/ci.yml) [![Crates badge](https://img.shields.io/crates/v/toornament.svg)](https://crates.io/crates/toornament)
* Victorem
  * [VictoremWinbringer/Victorem](https://github.com/VictoremWinbringer/Victorem) [[Victorem](https://crates.io/crates/Victorem)] - 易于使用的 UDP 游戏服务器和 UDP 客户端框架，用于创建简单的 2D 和 3D 在线游戏原型

### 地理空间

[[geo](https://crates.io/keywords/geo), [gis](https://crates.io/keywords/gis)]

* [apache/sedona-db](https://github.com/apache/sedona-db) - SedonaDB 是一个用 Rust 编写的地理空间 DataFrame 库。
* [DaveKram/coord_transforms](https://github.com/DaveKram/coord_transforms) [[coord_transforms](https://crates.io/crates/coord_transforms)] - 坐标变换（2 维、3 维和地理空间）
* [Georust](https://github.com/georust) - 用 Rust 编写的地理空间工具和库
* [georust/geojson](https://github.com/georust/geojson) [[geojson](https://crates.io/crates/geojson)] - 用于序列化和反序列化 GeoJSON 矢量 GIS 文件格式的库。
* [MapLibre/Martin](https://github.com/maplibre/martin) - 支持 PostGIS、MBTiles、PMTiles 和 sprites 的地图瓦片服务器。[![CI build](https://github.com/maplibre/martin/actions/workflows/ci.yml/badge.svg)](https://github.com/maplibre/martin/actions)[![crates.io version](https://img.shields.io/crates/v/martin.svg)](https://crates.io/crates/martin)[![Book](https://img.shields.io/badge/docs-Book-informational)](https://maplibre.org/martin/)
* [rust-reverse-geocoder](https://github.com/gx0r/rrgeo) - 一个快速、离线的反向地理编码器，受 [thampiman/reverse-geocoder](https://github.com/thampiman/reverse-geocoder) 启发
* [vlopes11/geomorph](https://github.com/vlopes11/geomorph) [[geomorph](https://crates.io/crates/geomorph)] - UTM、LatLon 和 MGRS 坐标之间的转换

### 图算法

* [neo4j-labs/graph](https://github.com/neo4j-labs/graph) - 一个用于高性能图算法的库 [![graph CI status](https://img.shields.io/github/workflow/status/neo4j-labs/graph/CI/main?label=CI)](https://github.com/neo4j-labs/graph/actions/workflows/rust.yml)
* [petgraph/petgraph](https://github.com/petgraph/petgraph) - 图数据结构库。[![graph CI status](https://github.com/petgraph/petgraph/workflows/Continuous%20integration/badge.svg?branch=master)](https://github.com/petgraph/petgraph/actions/workflows/ci.yml)

### 图形

[[graphics](https://crates.io/keywords/graphics)]

* 字体
  * [redox-os/rusttype](https://github.com/redox-os/rusttype) - 类似 FreeType 等库的替代品
  * [rustybuzz](https://github.com/harfbuzz/rustybuzz) - harfbuzz 的增量移植
* [gfx-rs/gfx](https://github.com/gfx-rs/gfx) - 一个高性能、无绑定的图形 API。
* [gfx-rs/wgpu](https://github.com/gfx-rs/wgpu) - 基于 gfx-hal 的原生 WebGPU 实现。[![build badge](https://github.com/gfx-rs/wgpu/workflows/CI/badge.svg?branch=master)](https://github.com/gfx-rs/wgpu/actions)
* OpenGL [[opengl](https://crates.io/keywords/opengl)]
  * [gl-rs](https://github.com/rust-windowing/gl-rs) - 一个 OpenGL 函数指针加载器
  * [glium/glium](https://github.com/glium/glium) - 安全的 OpenGL 封装。
  * [glutin](https://crates.io/crates/glutin) - [GLFW](https://www.glfw.org/) 的替代品
  * [PistonDevelopers/glfw-rs](https://github.com/PistonDevelopers/glfw-rs) - GLFW3 绑定和惯用封装
* PDF
  * [bastibense/libharu_ng](https://github.com/bastibense/libharu_ng) [[libharu_ng](https://crates.io/crates/libharu_ng)] - 从你的 Rust 应用轻松生成 PDF。
  * [fschutt/printpdf](https://github.com/fschutt/printpdf) - PDF 写入库
  * [fullbleed-engine/fullbleed-official](https://github.com/fullbleed-engine/fullbleed-official) [[fullbleed](https://crates.io/crates/fullbleed)] - 面向印刷的 HTML/CSS 转 PDF 引擎，具备可复用模板、可变数据生成和 Python 绑定。[![CI](https://github.com/fullbleed-engine/fullbleed-official/actions/workflows/ci.yml/badge.svg?branch=master)](https://github.com/fullbleed-engine/fullbleed-official/actions/workflows/ci.yml)
  * [gastongouron/ironpress](https://github.com/gastongouron/ironpress) [[ironpress](https://crates.io/crates/ironpress)] - 纯 Rust 的 HTML/CSS/Markdown 转 PDF 转换器，内置布局引擎，无浏览器或系统依赖。[![CI](https://github.com/gastongouron/ironpress/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/gastongouron/ironpress/actions/workflows/ci.yml)
  * [hayro](https://github.com/LaurenzV/hayro) - 用纯 Rust 编写的 PDF 解释器和渲染器
  * [J-F-Liu/lopdf](https://github.com/J-F-Liu/lopdf) - PDF 文档操作
  * [kaj/rust-pdf](https://github.com/kaj/rust-pdf) - 用纯 Rust 生成 PDF 文件
  * [yfedoseev/pdf_oxide](https://github.com/yfedoseev/pdf_oxide) [[pdf_oxide](https://crates.io/crates/pdf_oxide)] - 快速的 PDF 文本提取、创建和编辑，带 Python 绑定
* [Vulkan](https://www.vulkan.org/) [[vulkan](https://crates.io/keywords/vulkan)]
  * [erupt](https://gitlab.com/Friz64/erupt) [[erupt](https://crates.io/crates/erupt)] - [![build badge](https://gitlab.com/Friz64/erupt/badges/main/pipeline.svg)](https://gitlab.com/Friz64/erupt/-/pipelines)
  * [vulkano](https://github.com/vulkano-rs/vulkano) [[vulkano](https://crates.io/crates/vulkano)] - 围绕 Vulkan API 的安全且丰富的 Rust 封装

### GUI

[[gui](https://crates.io/keywords/gui)]

* [autopilot-rs/autopilot-rs](https://github.com/autopilot-rs/autopilot-rs) - 一个简单、跨平台的 GUI 自动化库。
* Cocoa
  * [servo/core-foundation-rs](https://github.com/servo/core-foundation-rs) - Core Foundation 及其他 Mac OS X 和 iOS 底层库的 Rust 绑定
* [DioxusLabs/dioxus](https://github.com/dioxuslabs/dioxus) - 一个可移植、高性能且人体工程学的框架，用于在 Rust 中构建跨平台用户界面。![rust ci](https://github.com/dioxuslabs/dioxus/actions/workflows/main.yml/badge.svg)
* [emilk/egui](https://github.com/emilk/egui) - 简单、快速且高度可移植的即时模式 GUI 库。egui 可在 Web、原生以及你喜欢的游戏引擎中运行。[![Build Status](https://github.com/emilk/egui/workflows/CI/badge.svg)](https://github.com/emilk/egui/actions?workflow=CI)
* [emoon/rust_minifb](https://github.com/emoon/rust_minifb) - minifb 是一个跨平台窗口设置，具备可选的位图渲染。它还提供简单的鼠标和键盘输入。主要面向原型设计
* [euv-dev/euv](https://github.com/euv-dev/euv) [[euv](https://crates.io/crates/euv)] - 一个声明式、跨平台的 Rust UI 框架，具备虚拟 DOM、响应式信号和面向 WebAssembly 的 HTML 宏。[![CI](https://github.com/euv-dev/euv/actions/workflows/rust.yml/badge.svg)](https://github.com/euv-dev/euv/actions)
  * [euv-ui](https://github.com/euv-dev/euv) [[euv-ui](https://crates.io/crates/euv-ui)] - 面向 euv 框架的可复用 UI 组件库，提供按钮、卡片、模态框、输入框等。
* [FerrisMind/shadcn-rs](https://github.com/FerrisMind/shadcn-rs) [[iced-shadcn](https://crates.io/crates/iced-shadcn)] - 具备 shadcn/ui 美学的 iced 和 egui 组件集；包含 [egui-shadcn](https://crates.io/crates/egui-shadcn)。
* [FLTK](https://www.fltk.org/)
  * [fltk-rs](https://github.com/fltk-rs/fltk-rs) - FLTK 绑定 [![Build](https://github.com/fltk-rs/fltk-rs/workflows/Build/badge.svg?branch=master)](https://github.com/fltk-rs/fltk-rs/actions)
* [Flutter](https://flutter.dev/)
  * [cunarist/rinf](https://github.com/cunarist/rinf) - Rust 作为你的 Flutter 后端，Flutter 作为你的 Rust 前端 [![Build Test](https://github.com/cunarist/rinf/actions/workflows/build_test.yaml/badge.svg)](https://github.com/cunarist/rinf/actions/workflows/build_test.yaml?query=branch%3Amain)
  * [flutter-rs](https://github.com/flutter-rs/flutter-rs) - 用 dart 和 rust 构建 flutter 桌面应用。
  * [fzyzcjy/flutter_rust_bridge](https://github.com/fzyzcjy/flutter_rust_bridge) - 面向 Flutter/Dart <-> Rust 的高级内存安全绑定生成器
* [fschutt/azul](https://github.com/fschutt/azul) - 一个免费、函数式、面向 IMGUI 的 GUI 框架，用于快速开发用 Rust 编写的桌面应用，由 Mozilla WebRender 渲染引擎支持。
* [GTK+](https://www.gtk.org/) [[gtk](https://crates.io/keywords/gtk)]
  * [gtk-rs/gtk4-rs](https://github.com/gtk-rs/gtk4-rs) - GTK4 绑定 ![CI](https://github.com/gtk-rs/gtk4-rs/workflows/CI/badge.svg)
  * [relm](https://github.com/antoyo/relm) - 异步、基于 GTK+ 的 GUI 库，受 Elm 启发
* [iced-rs/iced](https://github.com/iced-rs/iced) [[iced](https://crates.io/crates/iced)] - 一个跨平台 GUI 库，专注于简洁性和类型安全。受 Elm 启发。
* [ImGui](https://github.com/ocornut/imgui)
  * [imgui-rs](https://github.com/imgui-rs/imgui-rs) - ImGui 的绑定 [![Build Status](https://github.com/imgui-rs/imgui-rs/workflows/ci/badge.svg?branch=master)](https://github.com/imgui-rs/imgui-rs/actions)
* [IUP](http://webserver2.tecgraf.puc-rio.br/iup/)
  * [Kiss-ui](https://github.com/KISS-UI/kiss-ui) - 一个构建在 IUP 之上的简单 UI 框架
* [ivanceras/sauron-native](https://github.com/ivanceras/sauron-native) - 一个真正原生且跨平台的 GUI 库。一份统一代码可作为原生 GUI、Html Web 和 TUI 运行。
* [libui](https://github.com/andlabs/libui)
  * [rust-native-ui/libui-rs](https://github.com/rust-native-ui/libui-rs) - libui 绑定。
* [linebender/xilem](https://github.com/linebender/xilem) [[xilem](https://crates.io/crates/xilem)] - 一个实验性的 Rust 响应式 UI 框架，受 React、SwiftUI 和 Elm 启发。构建在 Masonry、Vello/wgpu、Parley 和 AccessKit 之上，具备 Web 和原生后端。[![CI](https://img.shields.io/github/actions/workflow/status/linebender/xilem/ci.yml?logo=github&label=CI)](https://github.com/linebender/xilem/actions)
* [longbridge/gpui-component](https://github.com/longbridge/gpui-component) [[gpui-component](https://crates.io/crates/gpui-component)] - 使用 GPUI 构建出色桌面应用的 UI 组件。
* [makepad/makepad](https://github.com/makepad/makepad) [[makepad-widgets](https://crates.io/crates/makepad-widgets)] - Makepad 是一个创意软件开发平台，可编译到 wasm/webGL、osx/metal、windows/dx11、linux/opengl。
* [Nuklear](https://github.com/Immediate-Mode-UI/Nuklear)
  * [nuklear-rust](https://github.com/snuk182/nuklear-rust) - Nuklear 的绑定
* [OrbTk](https://github.com/redox-os/orbtk) - Orbital 控件工具包是一个使用 SDL2 的多平台 (G)UI 工具包 [![Build and test](https://github.com/redox-os/orbtk/workflows/build/badge.svg?branch=develop)](https://github.com/redox-os/orbtk/actions)
* [PistonDevelopers/conrod](https://github.com/PistonDevelopers/conrod/) - 一个易于使用的即时模式 2D GUI 库
* [project-blinc/Blinc](https://github.com/project-blinc/Blinc) [[blinc_app](https://crates.io/crates/blinc_app)] - 一个 GPU 加速、跨平台的 UI 框架，具备受 GPUI 启发的构建器 API、玻璃拟态效果、弹簧物理动画，以及在桌面、Android 和 iOS 上的原生渲染。
* [Qt](https://doc.qt.io)
  * [cyndis/qmlrs](https://github.com/cyndis/qmlrs) - QtQuick 绑定
  * [rust-qt](https://github.com/rust-qt) - Rust 的 Qt 绑定
  * [woboq/qmetaobject-rs](https://github.com/woboq/qmetaobject-rs) - 通过在编译期构建 QMetaObject 来集成 Qml 和 Rust。
* [Ribir](https://github.com/RibirX/Ribir) - Ribir 是一个 Rust GUI 框架，帮助您从单一代码库构建漂亮且原生的多平台应用。
* [rise-ui](https://github.com/rise-ui/rise) - 简单的基于组件的跨平台 GUI 工具包，用于开发漂亮且用户友好的界面。
* [saurvs/nfd-rs](https://github.com/saurvs/nfd-rs) - [nativefiledialog](https://github.com/mlabbe/nativefiledialog) 绑定
* [Sciter](https://sciter.com/)
  * [sciter-sdk/rust-sciter](https://github.com/sciter-sdk/rust-sciter) - Sciter 绑定 [![build badge](https://ci.appveyor.com/api/projects/status/github/sciter-sdk/rust-sciter?svg=true)](https://ci.appveyor.com/project/sciter-sdk/rust-sciter)
* [slint-ui/slint](https://github.com/slint-ui/slint) [slint](https://crates.io/crates/slint) - [Slint](https://slint.dev/) 是一个工具包，用于为嵌入式设备和桌面应用高效开发流畅的图形用户界面。[![Build Status](https://github.com/slint-ui/slint/workflows/CI/badge.svg?branch=master)](https://github.com/slint-ui/slint/actions?query=workflow%3ACI)
* [smithay](https://github.com/Smithay/smithay) - [[smithay](https://crates.io/crates/smithay)] 是一个安全且文档完善的库，旨在为创建 Wayland 合成器提供构建块
* [tauri-apps/tauri](https://github.com/tauri-apps/tauri) - 使用 Web 前端构建更小、更快、更安全的桌面应用，由 [WRY](https://github.com/tauri-apps/wry) 提供支持。[![test library](https://img.shields.io/github/workflow/status/tauri-apps/tauri/test%20library?label=test%20library)](https://github.com/tauri-apps/tauri/actions?query=workflow%3A%22test+library%22)
* [tauri-apps/wry](https://github.com/tauri-apps/wry) - Webview 渲染库。
* [xilem](https://github.com/linebender/xilem) - 数据优先的 UI 设计工具包 [druid](https://github.com/linebender/druid) 的继任者。

### 图像处理

* [abonander/img_hash](https://github.com/abonander/img_hash) - 感知图像哈希以及用于相等性和相似性的比较。
* [Enet4/dicom-rs](https://github.com/Enet4/dicom-rs) - DICOM 标准的纯 Rust 实现，允许用户处理 DICOM 对象并与 DICOM 应用交互，同时力求快速、安全和直观易用。
* [image-rs/image](https://github.com/image-rs/image) - 基本的图像处理函数和方法，用于与图像格式之间转换
* [image-rs/imageproc](https://github.com/image-rs/imageproc) - 一个图像处理库，基于 `image` 库。
* [marekm4/dominant_color](https://github.com/marekm4/dominant_color) [[dominant_color](https://crates.io/crates/dominant_color)] - 主色提取器 ![build badge](https://github.com/marekm4/dominant_color/actions/workflows/rust.yml/badge.svg?branch=master)
* [rust-cv/cv](https://github.com/rust-cv/cv) - 实现计算机视觉算法、抽象和系统。在可能的情况下支持 `#[no_std]`。![build badge](https://github.com/rust-cv/cv/workflows/tests/badge.svg)
* [teovoinea/steganography](https://github.com/teovoinea/steganography) [[steganography](https://crates.io/crates/steganography)] - 一个简单的隐写术库
* [twistedfall/opencv-rust](https://github.com/twistedfall/opencv-rust) - OpenCV 的绑定

### 语言规范

* [shnewto/bnf](https://github.com/shnewto/bnf) - 一个用于解析巴科斯-诺尔范式（BNF）上下文无关文法的库。

### 许可证

* [WyvernIXTL/license-fetcher](https://github.com/WyvernIXTL/license-fetcher) [[license-fetcher](https://crates.io/crates/license-fetcher)] - 在构建期获取依赖的许可证并将其嵌入到你的程序中。

### 日志

[[log](https://crates.io/keywords/log)]

* [donnie4w/tklog](https://github.com/donnie4w/tklog "donnie4w/tklog") - 轻量高效的 Rust 结构化日志库，支持日志级别、文件分割、压缩归档。
* [estk/log4rs](https://github.com/estk/log4rs) - 高度可配置的日志框架，仿照 Java 的 Logback 和 log4j 库 [![CircleCI](https://circleci.com/gh/estk/log4rs.svg?style=shield)](https://app.circleci.com/pipelines/github/estk/log4rs)
* [fast/logforth](https://github.com/fast/logforth) - 一个多才多艺、可扩展且易于使用的 Rust 应用日志框架。它允许你配置多个 dispatch、filter 和 appender，以按需定制日志设置。
* [rbatis/fast_log](https://github.com/rbatis/fast_log) - 异步日志 高性能异步日志
* [rust-lang/log](https://github.com/rust-lang/log) - 日志实现
* [seanmonstar/pretty-env-logger](https://github.com/seanmonstar/pretty-env-logger) - 一个漂亮、易于使用的 logger。
* [slog-rs/slog](https://github.com/slog-rs/slog) - 结构化、可组合的日志
* [tokio-rs/tracing](https://github.com/tokio-rs/tracing) - 一个应用级追踪框架，用于异步感知的结构化日志、错误处理、指标等 [![Build Status](https://github.com/tokio-rs/tracing/workflows/CI/badge.svg?branch=master)](https://github.com/tokio-rs/tracing/actions?query=workflow%3ACI)

### 宏

* cute
  * [mattgathu/cute](https://github.com/mattgathu/cute) - 面向 Python 风格列表推导式的宏。
* [elastio/bon](https://github.com/elastio/bon) [[bon](https://crates.io/crates/bon)] - 为 struct 和函数生成编译期检查的构建器，为函数和方法提供部分应用、可选参数和命名参数。[![build status](https://github.com/elastio/bon/actions/workflows/ci.yml/badge.svg)](https://github.com/elastio/bon/actions)
* [Linq-in-Rust](https://github.com/StardustDL/Linq-in-Rust) - 面向类 C#-LINQ 表达式的宏和方法。[![CI](https://github.com/StardustDL/Linq-in-Rust/workflows/CI/badge.svg?branch=master)](https://github.com/StardustDL/Linq-in-Rust/actions?query=workflow%3ACI)

### 标记语言

* [bruits/satteri](https://github.com/bruits/satteri) [[satteri](https://crates.io/crates/satteri)] - 高性能的 Markdown 和 MDX 处理。用 Rust 解析和编译，用 JavaScript 运行插件。包含带 MDX 扩展的 CommonMark 解析器、MDAST/HAST 树操作，以及用于 JavaScript 互操作的 NAPI 绑定。
* CommonMark
  * [pulldown-cmark/pulldown-cmark](https://github.com/pulldown-cmark/pulldown-cmark) - [CommonMark](https://commonmark.org/) 解析器
* [insomnimus/tidier](https://github.com/insomnimus/tidier) [[tidier](https://crates.io/crates/tidier)] - 一个用于格式化 HTML、XHTML 和 XML 文档的库。[![build badge](https://github.com/insomnimus/tidier/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/insomnimus/tidier/actions)

### 移动端

* Android / iOS
  * [ivnsch/rust_android_ios](https://github.com/ivnsch/rust_android_ios) - 一个使用 rust-swig 和 cbindgen 分别为 Android 和 iOS 使用共享库的示例。
* 通用
  * [Geal/rust_on_mobile](https://github.com/Geal/rust_on_mobile) - iOS CocoaPods / Android JNI
  * [redbadger/crux](https://github.com/redbadger/crux) [[crux_core](https://crates.io/crates/crux_core)] - 跨平台应用开发。Crux 帮助你在移动端（iOS/Android）和 Web 之间共享应用的业务逻辑和行为——作为一个可复用的核心。[![Build status](https://img.shields.io/github/actions/workflow/status/redbadger/crux/build.yaml)](https://github.com/redbadger/crux/actions)
* iOS
  * [TimNN/cargo-lipo](https://github.com/TimNN/cargo-lipo) - 一个 cargo lipo 子命令，可自动创建用于 iOS 应用的通用库。

### 网络编程

* 蓝牙
  * [bluez/bluer](https://github.com/bluez/bluer) [[bluer](https://crates.io/crates/bluer)] - 官方 BlueZ 绑定。[![build badge](https://github.com/bluez/bluer/actions/workflows/rust.yml/badge.svg?branch=master)](https://github.com/bluez/bluer/actions/workflows/rust.yml)
* CoAP
  * [Covertness/coap-rs](https://github.com/Covertness/coap-rs) - 一个[受约束应用协议（CoAP）](https://datatracker.ietf.org/doc/html/rfc7252)库。
* DNS
  * [kweonminsung/bind9_rndc_rust](https://github.com/kweonminsung/bind9_rndc_rust) [[rndc](https://crates.io/crates/rndc)] - 面向 Rust 的 BIND9 RNDC 协议实现 [![CI](https://github.com/kweonminsung/bind9_rndc_rust/actions/workflows/ci.yml/badge.svg)](https://github.com/kweonminsung/bind9_rndc_rust/actions/workflows/ci.yml)
* Docker
  * [fussybeaver/bollard](https://github.com/fussybeaver/bollard) - Docker 守护进程 API
* FTP
  * [mattnenterprise/rust-ftp](https://github.com/mattnenterprise/rust-ftp) - 一个 [FTP](https://en.wikipedia.org/wiki/File_Transfer_Protocol) 客户端
* gRPC
  * [hyperium/tonic](https://github.com/hyperium/tonic) - 一个原生 gRPC 客户端和服务器实现，具备 async/await 支持 [![Crates.io](https://img.shields.io/crates/v/tonic)](https://crates.io/crates/tonic)
  * [tikv/grpc-rs](https://github.com/tikv/grpc-rs) - 构建在 C Core 库和 futures 之上的 gRPC 库
* HTTP
  * [deboa](https://crates.io/crates/deboa) - 一个构建在 hyper 之上、友好的 HTTP 客户端，具备若干附加功能、序列化格式和宏。[![Crates.io](https://img.shields.io/crates/v/deboa)]
  * [Hurl](https://github.com/Orange-OpenSource/hurl) - 使用纯文本和 libcurl 运行和测试 HTTP 请求 [![CI](https://github.com/Orange-OpenSource/hurl/workflows/CI/badge.svg)](https://github.com/Orange-OpenSource/hurl/actions)
* IPNetwork
  * [achanda/ipnetwork](https://github.com/achanda/ipnetwork) - 一个用于处理 IP 网络的库
  * [candrew/netsim](https://github.com/canndrew/netsim) - 一个用于网络模拟和测试的库
* 底层
  * [actix/actix](https://github.com/actix/actix) - Actor 库
  * [dylanmckay/protocol](https://github.com/dylanmckay/protocol) - 自定义 TCP/UDP 协议定义
  * [libpnet/libpnet](https://github.com/libpnet/libpnet) - 一个跨平台的底层网络库
  * [smoltcp-rs/smoltcp](https://github.com/smoltcp-rs/smoltcp) - 一个独立的、事件驱动的 TCP/IP 协议栈，面向裸机和实时系统设计
* message-io
  * [lemunozm/message-io](https://github.com/lemunozm/message-io) - 事件驱动的消息库，用于轻松快速地构建网络应用。支持 TCP、UDP 和 WebSockets。[![build badge](https://img.shields.io/github/workflow/status/lemunozm/message-io/message-io%20ci)](https://github.com/lemunozm/message-io/actions?query=workflow%3A%22message-io+ci%22)
* MQTT
  * [bytebeamio/rumqtt](https://github.com/bytebeamio/rumqtt) - 一个供开发者构建通过 TCP 和 WebSockets（带或不带 TLS）使用 [MQTT 协议](https://mqtt.org)通信的应用的库。[![Build and Test](https://github.com/bytebeamio/rumqtt/actions/workflows/build.yml/badge.svg)](https://github.com/bytebeamio/rumqtt/actions/workflows/build.yml)
  * [rmqtt/rmqtt](https://github.com/rmqtt/rmqtt) - MQTT 服务器/MQTT Broker - 面向 5G 时代物联网的可扩展分布式 MQTT 消息代理
* NanoMsg
  * [thehydroimpulse/nanomsg.rs](https://github.com/thehydroimpulse/nanomsg.rs) - [nanomsg](https://nanomsg.org/) 绑定
* NATS
  * [nats-io/nats.rs](https://github.com/nats-io/nats.rs) - NATS 的客户端，云原生消息系统。[![Build Status](https://github.com/nats-io/nats.rs/workflows/Rust/badge.svg?branch=master)](https://github.com/nats-io/nats.rs/actions)
* Nng
  * [neachdainn/nng-rs](https://gitlab.com/neachdainn/nng-rs) [[Nng](https://crates.io/crates/nng)] - [Nng（nanomsg v2）](https://nng.nanomsg.org/index.html) 绑定 [![build badge](https://gitlab.com/neachdainn/nng-rs/badges/master/pipeline.svg)](https://gitlab.com/neachdainn/nng-rs/-/pipelines)
* NNTP
  * [mattnenterprise/rust-nntp](https://github.com/mattnenterprise/rust-nntp) [[nntp](https://crates.io/crates/nntp)] - 一个 [NNTP](https://en.wikipedia.org/wiki/Network_News_Transfer_Protocol) 客户端
* P2P
  * [libp2p/rust-libp2p](https://github.com/libp2p/rust-libp2p) - libp2p 网络协议栈的实现。[![Circle CI](https://circleci.com/gh/libp2p/rust-libp2p.svg?style=svg)](https://app.circleci.com/pipelines/github/libp2p/rust-libp2p)
  * [n0-computer/iroh](https://github.com/n0-computer/iroh) [[iroh](https://crates.io/crates/iroh)] - 用于在设备之间构建直接连接的 crate [![CI](https://github.com/n0-computer/iroh/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/n0-computer/iroh/actions/workflows/ci.yml)
* POP3
  * [mattnenterprise/rust-pop3](https://github.com/mattnenterprise/rust-pop3) [[pop3](https://crates.io/crates/pop3)] - 一个 [POP3](https://en.wikipedia.org/wiki/Post_Office_Protocol) 客户端
* QUIC
  * [aws/s2n-quic](https://github.com/aws/s2n-quic) - IETF QUIC 协议的一个实现 ![ci](https://img.shields.io/github/actions/workflow/status/aws/s2n-quic/ci.yml?branch=main)
  * [cloudflare/quiche](https://github.com/cloudflare/quiche) - Cloudflare 对 QUIC 传输协议和 HTTP/3 的实现 ![build](https://img.shields.io/github/actions/workflow/status/cloudflare/quiche/stable.yml?branch=master)
  * [mozilla/neqo](https://github.com/mozilla/neqo) - QUIC 的一个实现
  * [quinn-rs/quinn](https://github.com/quinn-rs/quinn) - 基于 Future 的 QUIC 实现 [![build badge](https://dev.azure.com/dochtman/Projects/_apis/build/status/Quinn?branchName=master)](https://dev.azure.com/dochtman/Projects/_build)
  * [tencent/tquic](https://github.com/Tencent/tquic) - 一个高性能、轻量级且跨平台的 QUIC 库 [![Build Status](https://img.shields.io/github/actions/workflow/status/tencent/tquic/rust.yml)](https://github.com/Tencent/tquic/actions/workflows/rust.yml)
* Raknet
  * [b23r0/rust-raknet](https://github.com/b23r0/rust-raknet) - RakNet 协议实现 [![Build Status](https://img.shields.io/github/workflow/status/b23r0/rust-raknet/Rust)](https://github.com/b23r0/rust-raknet/actions/workflows/rust.yml)
* RPC
  * [remoc-rs/remoc](https://github.com/remoc-rs/remoc) [[remoc](https://crates.io/crates/remoc)] - Remoc 提供类似 Tokio 的通道（broadcast、mpsc、oneshot、watch），并可在任意远程传输上进行 trait 调用。[![build badge](https://github.com/remoc-rs/remoc/actions/workflows/rust.yml/badge.svg?branch=master)](https://github.com/remoc-rs/remoc/actions/workflows/rust.yml)
  * [smallnest/rpcx-rs](https://github.com/smallnest/rpcx-rs) - 一个以简单轻松方式开发微服务的 RPC 库。
* SIP
  * [restsend/rsipstack](https://github.com/restsend/rsipstack) - 一个符合 RFC 3261 的 SIP 协议栈
* Socket.io
  * [1c3t3a/rust-socketio](https://github.com/1c3t3a/rust-socketio) [[rust_socketio](https://crates.io/crates/rust_socketio)] - 一个用 Rust 编写的 [socket.io](https://socket.io) 客户端实现。
* SSH
  * [alexcrichton/ssh2-rs](https://github.com/alexcrichton/ssh2-rs) - [libssh2](https://libssh2.org/) 绑定
  * [Thrussh](https://pijul.org/thrussh) [[thrussh](https://crates.io/crates/thrussh)] - 一个 SSH 库，由 [libsodium](https://doc.libsodium.org/) 提供支持
* Stomp
  * [zslayton/stomp-rs](https://github.com/zslayton/stomp-rs) - 一个 [STOMP 1.2](http://stomp.github.io/stomp-specification-1.2.html) 客户端实现
* VPN
  * [defguard/wireguard-rs](https://github.com/DefGuard/wireguard-rs) - 一个多平台库，提供统一的高级 API，用于使用原生 OS 内核和用户态 WireGuard 协议实现来管理 WireGuard 接口
* Zenoh
  * [eclipse-zenoh-flow/zenoh-flow](https://github.com/eclipse-zenoh-flow/zenoh-flow) - 一个声明式框架，用于从*云*到*物*的计算
  * [eclipse-zenoh/zenoh](https://github.com/eclipse-zenoh/zenoh) - 零开销网络协议
* ZeroMQ
  * [erickt/rust-zmq](https://github.com/erickt/rust-zmq) - [ZeroMQ](https://zeromq.org/) 绑定

### 解析

  * [0xlane/pe-sign](https://github.com/0xlane/pe-sign) [[pe-sign]](https://crates.io/crates/pe-sign) - 一个跨平台的 rust no-std 库，用于从 PE 文件验证和提取签名信息。[![crates.io](https://img.shields.io/crates/v/pe-sign)](https://crates.io/crates/pe-sign) [![build](https://github.com/0xlane/pe-sign/actions/workflows/rust.yml/badge.svg)](https://github.com/0xlane/pe-sign/actions/workflows/rust.yml)
  * [cchexcode/wavefront_rs](https://github.com/cchexcode/wavefront_rs) - Wavefront OBJ 格式的解析器。[![crates.io](https://img.shields.io/crates/v/wavefront_rs.svg)](https://crates.io/crates/wavefront_rs) [![crates.io](https://img.shields.io/crates/d/wavefront_rs?label=crates.io%20downloads)](https://crates.io/crates/wavefront_rs) [![build badge](https://github.com/cchexcode/wavefront_rs/workflows/pipeline/badge.svg?branch=master)](https://github.com/cchexcode/wavefront_rs/actions)
  * [comex/rust-shlex](https://github.com/comex/rust-shlex) [[shlex](https://crates.io/crates/shlex)] - 像 Python 的 shlex 一样将字符串拆分为 shell 词。[![build badge](https://github.com/comex/rust-shlex/actions/workflows/test.yml/badge.svg?branch=master)](https://github.com/comex/rust-shlex/actions/workflows/test.yml)
  * [Eliah-Lakhin/lady-deirdre](https://github.com/Eliah-Lakhin/lady-deirdre) - 一个用于新编程语言和 LSP 服务器的框架。
  * [firecrawl/pdf-inspector](https://github.com/firecrawl/pdf-inspector) - 用于 PDF 分类和文本提取的快速 Rust 库。
  * [Folyd/robotstxt](https://github.com/Folyd/robotstxt) - Google 的 robots.txt 解析器和匹配器 C++ 库的移植
  * [freestrings/jsonpath](https://github.com/freestrings/jsonpath) - [JsonPath](https://goessner.net/articles/JsonPath/) 引擎。也支持 WebAssembly 和 Javascript
  * [hmeyer/stl_io](https://crates.io/crates/stl_io) - STL（STereoLithography）文件的解析器
  * [igumnoff/shiva](https://github.com/igumnoff/shiva) - Shiva 库：用 Rust 实现任意类型文档（纯文本、Markdown、HTML、PDF 等）的解析器和生成器
  * [kevinmehall/rust-peg](https://github.com/kevinmehall/rust-peg) - 解析表达式文法（PEG）解析器生成器
  * [lalrpop/lalrpop](https://github.com/lalrpop/lalrpop) - LR(1) 解析器生成器
  * [m4rw3r/chomp](https://github.com/m4rw3r/chomp) - 一个快速的 monadic 风格解析器组合子
  * [Marwes/combine](https://github.com/Marwes/combine) - 解析器组合子库
  * [mazznoer/csscolorparser-rs](https://github.com/mazznoer/csscolorparser-rs) [[csscolorparser](https://crates.io/crates/csscolorparser)] - CSS 颜色解析器库 [![CI](https://github.com/mazznoer/csscolorparser-rs/actions/workflows/rust.yml/badge.svg?branch=master)](https://github.com/mazznoer/csscolorparser-rs/actions/workflows/rust.yml)
  * [mohamadzoh/phonelib](https://github.com/mohamadzoh/phonelib) [[phonelib](https://crates.io/crates/phonelib)] - 一个无依赖的 Rust 库，用于解析、验证、格式化和规范化国际电话号码。
  * [nrc/zero](https://github.com/nrc/zero) [[zero](https://crates.io/crates/zero/)] - 二进制数据的零分配解析
  * [ophi-dev/antlr-rust-runtime](https://github.com/ophi-dev/antlr-rust-runtime) [[antlr-rust-runtime](https://crates.io/crates/antlr-rust-runtime)] - ANTLR v4 运行时，带纯 Rust 解析器生成器：直接从 `.g4` 文法生成解析器（无需 Java），并通过官方 ANTLR 一致性测试套件验证。[![build badge](https://github.com/ophi-dev/antlr-rust-runtime/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/ophi-dev/antlr-rust-runtime/actions/workflows/ci.yml)
  * [oxc-project/oxc](https://github.com/oxc-project/oxc) [[oxc](https://crates.io/crates/oxc)] - 用 Rust 编写的高性能 JavaScript/TypeScript 解析器、转换器、压缩器和解析器。为 Rolldown、Nuxt、Nova 等提供支持。[![Build Status](https://github.com/oxc-project/oxc/actions/workflows/ci.yml/badge.svg?event=push&branch=main)](https://github.com/oxc-project/oxc/actions/workflows/ci.yml)
  * [pest-parser/pest](https://github.com/pest-parser/pest) - 优雅的解析器
  * [ptal/oak](https://github.com/ptal/oak) - 一个带类型的 PEG 解析器生成器（编译器插件）
  * [run-llama/liteparse](https://github.com/run-llama/liteparse) [[liteparse](https://crates.io/crates/liteparse)] - 快速轻量的 PDF 解析库，具备空间文本提取、边界框、灵活 OCR（Tesseract/HTTP 服务器）和多语言绑定（Rust、Node.js、Python、WASM）。构建在 PDFium 之上，带 CLI 工具 `lit`。[![CI](https://github.com/run-llama/liteparse/actions/workflows/ci.yml/badge.svg)](https://github.com/run-llama/liteparse/actions/workflows/ci.yml)
  * [rust-bakery/nom](https://github.com/rust-bakery/nom) - 解析器组合子库
  * [s-panferov/queryst](https://github.com/s-panferov/queryst) - 一个查询字符串解析库，受 [gs](https://github.com/ljharb/qs#readme) 启发
  * [slimreaper35/dockerfile-parser-rs](https://github.com/slimreaper35/dockerfile-parser-rs) [[dockerfile-parser-rs](https://crates.io/crates/dockerfile-parser-rs)] - Dockerfile 解析库和 CLI 工具
  * [softdevteam/grmtools](https://github.com/softdevteam/grmtools/) - 一个具备更好错误纠正的 LR 解析器
  * [tree-sitter/tree-sitter](https://github.com/tree-sitter/tree-sitter) - 一个解析器生成器工具和面向编程工具的增量解析库
  * [winnow-rs/winnow](https://github.com/winnow-rs/winnow) [[winnow](https://crates.io/crates/winnow)] - 一个面向字节、零拷贝的解析器组合子库。[![Build status](https://github.com/winnow-rs/winnow/workflows/CI/badge.svg)](https://github.com/winnow-rs/winnow/actions)
  * [xberg-io/tree-sitter-language-pack](https://github.com/xberg-io/tree-sitter-language-pack) [[tree-sitter-language-pack](https://crates.io/crates/tree-sitter-language-pack)] - 面向 300+ 语言的预构建 tree-sitter 文法，具备统一的解析器 API 和 14 种语言的绑定。

### 外设

* [AprilNEA/OpenLogi/crates/openlogi-hidpp](https://github.com/AprilNEA/OpenLogi/tree/main/crates/openlogi-hidpp) [[openlogi-hidpp](https://crates.io/crates/openlogi-hidpp)] - OpenLogi 为支持 Logitech HID++ 协议而 vendor 的 hidpp crate 分支。
* [esp-rs/esp-hal](https://github.com/esp-rs/esp-hal) [[esp-hal](https://crates.io/crates/esp-hal)] - 面向 Espressif ESP32 设备（ESP32、ESP32-C2/C3/C5/C6/C61、ESP32-H2、ESP32-P4、ESP32-S2/S3）的裸机 `no_std` 硬件抽象层。为 GPIO、I2C、SPI、UART、定时器、DMA 等提供安全的 Rust API。[![GitHub Actions Workflow Status](https://img.shields.io/github/actions/workflow/status/esp-rs/esp-hal/ci.yml?labelColor=1C2C2E&label=CI&logo=github&style=flat-square)](https://github.com/esp-rs/esp-hal/actions/workflows/ci.yml)
* 指纹读取器
  * [alvaroparker/libfprint-rs](https://github.com/alvaroparker/libfprint-rs) [[libfprint-rs](https://crates.io/crates/libfprint-rs)] - Libfprint-rs 为 Linux 的 libfprint 库提供封装。
* [Michael-A-Kuykendall/crabcamera](https://github.com/Michael-A-Kuykendall/crabcamera) [[crabcamera](https://crates.io/crates/crabcamera)] - Tauri 插件，提供桌面摄像头访问，具备自动化质量验证和硬件控制。
* 串口
  * [serialport/serialport-rs](https://github.com/serialport/serialport-rs) [[serialport](https://crates.io/crates/serialport)] - 一个跨平台库，提供对串口的访问

### 平台相关

* 跨平台
  * [iddm/thread-priority](https://github.com/iddm/thread-priority/) - 简单的跨平台线程优先级管理。[![CI](https://github.com/iddm/thread-priority/actions/workflows/ci.yml/badge.svg)](https://github.com/iddm/thread-priority/actions/workflows/ci.yml) [![Crates badge](https://img.shields.io/crates/v/thread-priority.svg)](https://crates.io/crates/thread-priority)
  * [svartalf/rust-battery](https://crates.io/crates/battery) - 跨平台的笔记本电池信息
* FreeBSD
  * [fubarnetes/libjail-rs](https://github.com/fubarnetes/libjail-rs/) [[jail](https://crates.io/crates/jail)] - FreeBSD jail 库
* Linux
  * [hannobraun/inotify-rs](https://github.com/hannobraun/inotify-rs) - [inotify](https://en.wikipedia.org/wiki/Inotify) 绑定 [![Rust](https://github.com/hannobraun/inotify-rs/actions/workflows/rust.yml/badge.svg)](https://github.com/hannobraun/inotify-rs/actions/workflows/rust.yml)
  * [pop-os/distinst](https://github.com/pop-os/distinst/) - Linux 发行版安装器
  * [yaa110/rust-iptables](https://github.com/yaa110/rust-iptables) [[iptables](https://crates.io/crates/iptables)] - [iptables](https://www.netfilter.org/projects/iptables/index.html) 绑定
* 类 Unix
  * [nix-rust/nix](https://github.com/nix-rust/nix) - 类 Unix API 绑定 [![CI](https://github.com/nix-rust/nix/actions/workflows/ci.yml/badge.svg)](https://github.com/nix-rust/nix/actions/workflows/ci.yml)
  * [rustix](https://github.com/bytecodealliance/rustix) - 对 POSIX/Unix/Linux/Winsock2 系统调用的安全绑定 [![Actions Status](https://github.com/bytecodealliance/rustix/workflows/CI/badge.svg)](https://github.com/bytecodealliance/rustix/actions?query=workflow%3ACI)
  * [zargony/fuse-rs](https://github.com/zargony/fuse-rs) - [FUSE](https://github.com/libfuse/libfuse) 绑定
* Windows
  * [microsoft/windows-rs](https://github.com/microsoft/windows-rs) - Rust for Windows [![Actions Status](https://github.com/microsoft/windows-rs/workflows/CI/badge.svg)](https://github.com/microsoft/windows-rs/actions)
  * [retep998/winapi-rs](https://github.com/retep998/winapi-rs) - Windows API 绑定 [![Rust](https://github.com/retep998/winapi-rs/actions/workflows/rust.yml/badge.svg?branch=dev)](https://github.com/retep998/winapi-rs/actions/workflows/rust.yml)

### 逆向工程

* [binlex](https://github.com/c3rb3ru5d3d53c/binlex) - 二进制分析和逆向工程框架，具备函数指纹识别和相似度匹配。
* [idalib](https://github.com/idalib-rs/idalib) [[idalib](https://crates.io/crates/idalib)] - IDA SDK 的 Rust 绑定，支持使用 IDA v9.0 的 idalib 开发独立分析工具
* [objdiff](https://github.com/encounter/objdiff) - 面向反编译项目的本地差异比较工具
* [wakaru](https://github.com/pionxzh/wakaru) [[wakaru](https://crates.io/crates/wakaru)] - JavaScript 反编译器：将 webpack/esbuild/Metro/Browserify 打包产物拆解为模块，并将压缩器和 Babel/TypeScript 输出还原为可读代码 [![CI](https://github.com/pionxzh/wakaru/actions/workflows/rust-ci.yml/badge.svg?branch=main)](https://github.com/pionxzh/wakaru/actions/workflows/rust-ci.yml)

### 脚本

[[scripting](https://crates.io/keywords/scripting)]

* [3body-lang](https://github.com/rustq/3body-lang) - 三体语言
* [boa-dev/boa](https://github.com/boa-dev/boa) [[boa_engine](https://crates.io/crates/boa_engine)] - 一个用 Rust 编写的实验性 JavaScript 词法分析器、解析器和解释器。
* [cel-rust](https://github.com/cel-rust/cel-rust) [[cel-interpreter](https://crates.io/crates/cel-interpreter)] - 通用表达式语言解析器和解释器
* [cmccomb/mocktave](https://github.com/cmccomb/mocktave) [[mocktave](https://crates.io/crates/mocktave)] - 从 Rust 运行 Octave 或 MATLAB 代码，具备原生和捆绑模式
* [duckscript](https://crates.io/crates/duckscript) - [简单、可扩展且可嵌入的脚本语言。](https://github.com/sagiegurari/duckscript) [![build badge](https://github.com/sagiegurari/duckscript/workflows/CI/badge.svg?branch=master)](https://github.com/sagiegurari/duckscript/actions)
* [facebook/starlark-rust](https://github.com/facebook/starlark-rust) - 一个小巧、确定性、线程安全且具备 Python 语法的语言
* [fleabitdev/gamelisp](https://github.com/fleabitdev/glsp) - 一个用于游戏开发的类 Lisp 脚本语言
* [giraffekey/xylo](https://github.com/giraffekey/xylo) [[xylo-lang](https://crates.io/crates/xylo-lang)] - 一个用于程序化艺术的函数式编程语言。[![build badge](https://github.com/giraffekey/xylo/actions/workflows/rust.yml/badge.svg)](https://github.com/giraffekey/xylo/actions)
* [gluon-lang/gluon](https://github.com/gluon-lang/gluon) - 一个小巧、静态类型的函数式编程语言
* [kcl](https://github.com/kcl-lang/kcl) - 一种基于约束的记录和函数式语言，主要用于配置和策略场景。
* [kyren/piccolo](https://github.com/kyren/piccolo) [[piccolo](https://crates.io/crates/piccolo)] - 用纯 Rust 实现的实验性无栈 Lua VM，具备循环检测的增量 GC、沙箱特性和安全的 Rust <-> Lua 绑定。[![crates.io](https://img.shields.io/crates/v/piccolo)](https://crates.io/crates/piccolo)
* [metacall/core](https://github.com/metacall/core) [[metacall](https://crates.io/crates/metacall)] - 跨平台多语言运行时，支持 NodeJS、JavaScript、TypeScript、Python、Ruby、C#、Wasm、Java、Cobol 等。[![build badge](https://gitlab.com/metacall/core/badges/master/pipeline.svg)](https://gitlab.com/metacall/core)
* [mun](https://github.com/mun-lang/mun) - 一个编译型、静态类型的脚本语言，具备一等公民的热重载支持
* [murarth/ketos](https://github.com/murarth/ketos) - 一个 Lisp 方言函数式编程语言，可作为 rust 的脚本和扩展语言
* [PistonDevelopers/dyon](https://github.com/PistonDevelopers/dyon) - 一个 rusty 的动态类型脚本语言
* [rhaiscript/rhai](https://github.com/rhaiscript/rhai) - 一个小巧快速的嵌入式脚本语言，类似 JavaScript 和 Rust 的结合 [![build badge](https://github.com/rhaiscript/rhai/workflows/Build/badge.svg)](https://github.com/rhaiscript/rhai/actions)
* [rune-rs/rune](https://github.com/rune-rs/rune) - 一个可嵌入的动态编程语言
* [trynova/nova](https://github.com/trynova/nova) - 完全用 Rust 编写的 JavaScript 引擎

### 仿真

[[simulation](https://crates.io/keywords/simulation)]

* [nyx-space](https://crates.io/crates/nyx-space) - 高保真、快速、可靠且经验证的航天动力学工具包库，用于航天器任务设计和轨道确定 [![Build Status](https://gitlab.com/nyx-space/nyx/badges/master/pipeline.svg)](https://gitlab.com/nyx-space/nyx/-/pipelines)
* [rsasaki0109/rust_robotics](https://github.com/rsasaki0109/rust_robotics) [[rust_robotics](https://crates.io/crates/rust_robotics)] - 受 PythonRobotics 启发的机器人算法 Rust 实现，涵盖路径规划、定位、SLAM 和控制，具备 no_std 支持和 ROS 2 示例 [![CI](https://github.com/rsasaki0109/rust_robotics/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/rsasaki0109/rust_robotics/actions/workflows/ci.yml)

### 社交网络

* Telegram
  * [tdilb-rs](https://github.com/FedericoBruzzone/tdlib-rs) [[tdilb-rs](https://crates.io/crates/tdlib-rs)] - 围绕 Telegram Database Library（TDLib）的跨平台 Rust 封装 [![CI Linux](https://github.com/FedericoBruzzone/tdlib-rs/actions/workflows/ci-linux.yml/badge.svg)](https://github.com/FedericoBruzzone/tdlib-rs/actions/workflows/ci-linux.yml) [![CI macOS](https://github.com/FedericoBruzzone/tdlib-rs/actions/workflows/ci-macos.yml/badge.svg)](https://github.com/FedericoBruzzone/tdlib-rs/actions/workflows/ci-macos.yml) [![CI Windows](https://github.com/FedericoBruzzone/tdlib-rs/actions/workflows/ci-windows.yml/badge.svg)](https://github.com/FedericoBruzzone/tdlib-rs/actions/workflows/ci-windows.yml)

### 系统

* [ardaku/whoami](https://github.com/ardaku/whoami) [[whoami](https://crates.io/crates/whoami)] - 用于获取当前用户和环境的 crate。[![build badge](https://github.com/ardaku/whoami/actions/workflows/ci.yml/badge.svg?branch=stable)](https://github.com/ardaku/whoami/actions/workflows/ci.yml)
* [GuillaumeGomez/sysinfo](https://github.com/GuillaumeGomez/sysinfo) [[sysinfo](https://crates.io/crates/sysinfo)] - 跨平台库，用于获取系统信息 [![build badge](https://github.com/GuillaumeGomez/sysinfo/actions/workflows/CI.yml/badge.svg?branch=master)](https://github.com/GuillaumeGomez/sysinfo/actions/workflows/CI.yml)
* [navidys/procsys](https://github.com/navidys/procsys) [[procsys](https://crates.io/crates/procsys)] - 一个从伪文件系统 /proc 和 /sys 检索系统、内核和进程指标的库。
* [Phate6660/nixinfo](https://github.com/Phate6660/nixinfo) [[nixinfo](https://crates.io/crates/nixinfo)] - 一个用于收集系统信息（如 cpu、发行版、环境、内核等）的 lib crate。
* [sorairolake/sysexits-rs](https://github.com/sorairolake/sysexits-rs) [[sysexits](https://crates.io/crates/sysexits)] - 由 [`<sysexits.h>`](https://man.openbsd.org/sysexits) 定义的系统退出码。[![CI](https://github.com/sorairolake/sysexits-rs/workflows/CI/badge.svg?branch=develop)](https://github.com/sorairolake/sysexits-rs/actions?query=workflow%3ACI)

### 任务调度

* [delay-timer](https://github.com/BinChengZhao/delay-timer) - 延迟任务的时间管理器。类似 crontab，但可以执行异步任务。[![Build](https://github.com/BinChengZhao/delay-timer/actions/workflows/rust.yml/badge.svg)]( https://github.com/BinChengZhao/delay-timer/actions)
* [persistent-scheduler](https://github.com/rustmailer/persistent-scheduler) [[persistent-scheduler](https://crates.io/crates/persistent-scheduler)] - 一个用 Tokio 构建的高性能任务调度系统，提供任务持久化、可重复任务和基于 Cron 的调度，用于可靠的时间驱动操作。

### 模板引擎

* Handlebars
  * [sunng87/handlebars-rust](https://github.com/sunng87/handlebars-rust) - Handlebars 模板引擎，具备继承和自定义 helper 支持。
  * [zzau13/yarte](https://github.com/zzau13/yarte) - Yarte 代表 **Y**et **A**nother **R**ust **T**emplate **E**ngine，是最快的模板引擎。
* HTML
  * [askama](https://github.com/askama-rs/askama) - 基于 Jinja 的模板渲染引擎
  * [kaj/ructe](https://github.com/kaj/ructe) - HTML 模板系统
  * [Keats/tera](https://github.com/Keats/tera) - 基于 Jinja2 和 Django 模板语言的模板引擎。[![Actions Status](https://github.com/Keats/tera/workflows/ci/badge.svg?branch=master)](https://github.com/Keats/tera/actions)
  * [lambda-fairy/maud](https://github.com/lambda-fairy/maud) - 编译期 HTML 模板
  * [mitsuhiko/minijinja](https://github.com/mitsuhiko/minijinja) [[minijinja](https://crates.io/crates/minijinja)] - 基于 Jinja2 的极简依赖模板引擎。[![Tests](https://img.shields.io/github/actions/workflow/status/mitsuhiko/minijinja/tests.yml?branch=main&logo=github)](https://github.com/mitsuhiko/minijinja/actions/workflows/tests.yml)
  * [rshtml/rshtml](https://github.com/rshtml/rshtml) [[rshtml](https://crates.io/crates/rshtml)] - RsHtml：编译期、类型安全、轻量级的模板引擎，将 Rust 嵌入 HTML，将 HTML 嵌入 Rust。
  * [Stebalien/horrorshow-rs](https://github.com/Stebalien/horrorshow-rs) - 编译期 HTML 模板
* Mustache
  * [rustache/rustache](https://github.com/rustache/rustache) - Mustache 规范的 Rust 实现

### 文本处理

* [becheran/wildmatch](https://github.com/becheran/wildmatch) [[wildmatch](https://crates.io/crates/wildmatch)] - 使用问号和星号通配符进行简单字符串匹配 [![Actions Status](https://github.com/becheran/wildmatch/workflows/Build/badge.svg?branch=master)](https://github.com/becheran/wildmatch/actions)
* [BurntSushi/suffix](https://github.com/BurntSushi/suffix) - 线性时间后缀数组构建（支持 Unicode）
* [BurntSushi/tabwriter](https://github.com/BurntSushi/tabwriter) - 弹性制表位（即文本列对齐）
* [cmccomb/rust-stop-words](https://github.com/cmccomb/rust-stop-words) [[stop-words](https://crates.io/crates/stop-words)] - 多种语言中的常见停用词
* [cpc](https://github.com/probablykasper/cpc) - 解析并计算带单位及单位转换的数学字符串，从 `1+2` 到 `1% of round(1 lightyear / 14!s to km/h)`。
* [Daniel-Liu-c0deb0t/triple_accel](https://github.com/Daniel-Liu-c0deb0t/triple_accel) [[triple_accel](https://crates.io/crates/triple_accel)] - 使用 SIMD 加速的 Rust 编辑距离例程；支持快速 Hamming、Levenshtein、受限 Damerau-Levenshtein 等距离计算和字符串搜索 [![build badge](https://github.com/Daniel-Liu-c0deb0t/triple_accel/workflows/Test/badge.svg?branch=master)](https://github.com/Daniel-Liu-c0deb0t/triple_accel/actions)
* [fancy-regex/fancy-regex](https://github.com/fancy-regex/fancy-regex) [[fancy-regex](https://crates.io/crates/fancy-regex)] - 正则表达式实现，旨在支持相对丰富的特性，如环视和回溯。[![crates](https://img.shields.io/crates/v/fancy-regex.svg)](https://crates.io/crates/fancy-regex) [![build badge](https://github.com/fancy-regex/fancy-regex/workflows/ci/badge.svg)](https://github.com/fancy-regex/fancy-regex/actions/workflows/ci.yml)
* [greyblake/whatlang-rs](https://github.com/greyblake/whatlang-rs) - 基于三元组的自然语言检测库
* [Lucretiel/joinery](https://github.com/Lucretiel/joinery) [[joinery](https://crates.io/crates/joinery)] - 泛型字符串 + 可迭代对象连接
* [mgeisler/textwrap](https://github.com/mgeisler/textwrap) [[textwrap](https://crates.io/crates/textwrap)] - 文本自动换行（支持断字）
* [null8626/decancer](https://github.com/null8626/decancer) [[decancer](https://crates.io/crates/decancer)] - 一个极小的包，可从字符串中移除常见的 unicode 混淆字符/同形字。[![crates](https://img.shields.io/crates/v/decancer.svg)](https://crates.io/crates/decancer) [![build badge](https://github.com/null8626/decancer/workflows/CI/badge.svg)](https://github.com/null8626/decancer/actions/workflows/CI.yml)
* [ps1dr3x/easy_reader](https://github.com/ps1dr3x/easy_reader) - 一个读取器，允许在不消耗迭代器的情况下向前、向后和随机浏览超大文件的行
* [pwoolcoc/ngrams](https://github.com/pwoolcoc/ngrams) [[ngrams](https://crates.io/crates/ngrams)] - 从任意迭代器构造 [n-gram](https://en.wikipedia.org/wiki/N-gram)
* [rust-lang/regex](https://github.com/rust-lang/regex) - 正则表达式（RE2 风格）
* [strsim-rs](https://crates.io/crates/strsim) - 字符串相似度指标
* [xberg-io/html-to-markdown](https://github.com/xberg-io/html-to-markdown) [[html-to-markdown-rs](https://crates.io/crates/html-to-markdown-rs)] - 快速、符合 CommonMark 的 HTML 转 Markdown 转换器，具备 Rust 核心和 12 种语言的绑定。
* [xberg-io/xberg](https://github.com/xberg-io/xberg) [[xberg](https://crates.io/crates/xberg)] - 文档智能库，可从 97+ 格式（PDF、Office、带 OCR 的图像、HTML、电子邮件、归档）中提取文本、表格和元数据，具备 11 种语言的绑定。
* [yaa110/rake-rs](https://github.com/yaa110/rake-rs) [[rake](https://crates.io/crates/rake)] - RAKE 算法的多语言 Rust 实现

### 文本搜索

* [andylokandy/simsearch](https://github.com/andylokandy/simsearch) [[simsearch](https://crates.io/crates/simsearch)] - 一个简单轻量的内存模糊搜索引擎，用于搜索相似字符串
* [BurntSushi/fst](https://github.com/BurntSushi/fst) [[fst](https://crates.io/crates/fst)] - 使用有限状态机的有序集合和映射的快速实现
* [CurrySoftware/perlin](https://github.com/CurrySoftware/perlin) [[perlin](https://crates.io/crates/perlin)] - 一个惰性、零分配且与数据无关的信息检索库
* [meilisearch/MeiliSearch](https://github.com/meilisearch/MeiliSearch) - 超相关、即时且容忍拼写错误的全文搜索 API。[![Build Status](https://github.com/meilisearch/MeiliSearch/workflows/Cargo%20test/badge.svg?branch=master)](https://github.com/meilisearch/MeiliSearch/actions)
* [pg_search](https://github.com/paradedb/paradedb/tree/dev/pg_search) - PostgreSQL 扩展，可使用 BM25 算法对 SQL 表进行全文搜索，BM25 是全文搜索最先进的排序函数。
* [SeekStorm](https://github.com/SeekStorm/SeekStorm) [[SeekStorm](https://crates.io/crates/seekstorm)] - 亚毫秒级全文搜索库及多租户服务器，用 Rust 编写
* [tantivy](https://github.com/quickwit-oss/tantivy) [[tantivy](https://crates.io/crates/tantivy)] - 一个用 Rust 编写的、马一般速度的全文搜索引擎库。[![Build Status](https://github.com/quickwit-oss/tantivy/actions/workflows/test.yml/badge.svg)](https://github.com/quickwit-oss/tantivy/actions/workflows/test.yml)

### Unsafe

* [zerocopy](https://crates.io/crates/zerocopy) - "Zerocopy 让零成本内存操作变得轻松。我们编写 `unsafe`，因此你无需编写。"

### 视频

* [ffmpeg-sidecar](https://github.com/nathanbabcock/ffmpeg-sidecar) - 将独立的 FFmpeg 二进制文件封装在直观的 Iterator 接口中。[![Build Status](https://github.com/nathanbabcock/ffmpeg-sidecar/actions/workflows/ci.yml/badge.svg)](https://github.com/nathanbabcock/ffmpeg-sidecar/actions)
* [screencapturekit-rs](https://github.com/doom-fish/screencapturekit-rs) [[screencapturekit](https://crates.io/crates/screencapturekit)] - Apple 的 ScreenCaptureKit 框架的安全 Rust 绑定，用于 macOS 屏幕/音频捕获 [![Build Status](https://github.com/doom-fish/screencapturekit-rs/actions/workflows/ci.yml/badge.svg)](https://github.com/doom-fish/screencapturekit-rs/actions)

### 虚拟化

* [beneills/quantum](https://github.com/beneills/quantum) - 高级量子计算机模拟器
* [bytecodealliance/wasmtime](https://github.com/bytecodealliance/wasmtime) - 一个独立的 WebAssembly 运行时 [![Build Status](https://github.com/bytecodealliance/wasmtime/workflows/CI/badge.svg)](https://github.com/bytecodealliance/wasmtime/actions?query=workflow%3ACI)
* [capsule](https://github.com/capsulerun/capsule) - 用于执行不受信任代码的 WebAssembly 沙箱运行时
* [chromium/chromiumos/platform/crosvm](https://chromium.googlesource.com/chromiumos/platform/crosvm/) - CrOSVM 使 Chrome OS 能够在快速、安全的虚拟化环境中运行 Linux 应用
* [oxidecomputer/propolis](https://github.com/oxidecomputer/propolis) - 面向 illumos bhyve 内核模块的用户态程序
* [saurvs/hypervisor-rs](https://github.com/saurvs/hypervisor-rs) - OS X 上的硬件加速虚拟化
* [smol-machines/smolvm](https://github.com/smol-machines/smolvm) - 基于 libkrun 的可移植 microVM 沙箱，支持运行中 VM 的写时复制分叉
* [wasmi-labs/wasmi](https://github.com/wasmi-labs/wasmi) - 一个轻量级的 WebAssembly 运行时

### Web 编程

另见 [Are we web yet?](https://www.arewewebyet.org) 和 [Rust Web 框架对比](https://github.com/flosse/rust-web-framework-comparison)。
* 后端
  * [actix/actix-web](https://github.com/actix/actix-web) - 一个具备 websocket 支持的轻量级异步 Web 框架
  * [Anansi](https://github.com/saru-tora/anansi) - 一个简单的全栈 Web 框架
  * [loco-rs/loco](https://github.com/loco-rs/loco) [[loco-rs](https://crates.io/crates/loco-rs)] - 面向副业项目和初创公司的一人框架，受 Rails 启发。[![Build](https://github.com/loco-rs/loco/actions/workflows/ci.yml/badge.svg)](https://github.com/loco-rs/loco/actions)
  * [Rocket](https://github.com/rwf2/Rocket) - Rocket 是一个专注于易用性、表达力和速度的 Web 框架
  * [RustAPI](https://github.com/Tuntii/RustAPI) [[rustapi-rs](https://crates.io/crates/rustapi-rs)] - 具备编译期 OpenAPI 和原生 MCP 的人体工程学 Web 框架
  * [summer-rs](https://github.com/summer-rs/summer-rs) - summer-rs 是一个用 rust 编写的应用框架，受 java 的 spring-boot 启发。
  * [tako](https://github.com/rust-dd/tako) [[tako-rs](https://crates.io/crates/tako-rs)] - 多传输 Web 框架：HTTP/1.1、HTTP/2、HTTP/3、WebSocket、SSE、gRPC、TCP/UDP 和 Unix socket 统一在一个路由器之后，运行于 Tokio 或 Compio。[![CI](https://github.com/rust-dd/tako/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/rust-dd/tako/actions/workflows/ci.yml)
  * [tokio-rs/axum](https://github.com/tokio-rs/axum) - 使用 Tokio、Tower 和 Hyper 构建的人体工程学且模块化的 Web 框架 [![Build badge](https://github.com/tokio-rs/axum/actions/workflows/CI.yml/badge.svg?branch=main)](https://github.com/tokio-rs/axum/actions/workflows/CI.yml)
  * [tokio-rs/topcoat](https://github.com/tokio-rs/topcoat) [[topcoat](https://crates.io/crates/topcoat)] - 一个模块化、开箱即用的 Rust 全栈 Web 框架。具备服务端渲染、无 WASM 的客户端响应式、基于模块的路由，以及内置的 Tailwind/资源打包。[![Build Status](https://img.shields.io/github/actions/workflow/status/tokio-rs/topcoat/ci.yml?branch=main&style=flat-square)](https://github.com/tokio-rs/topcoat/actions)
  * [trillium](https://github.com/trillium-rs/trillium) [[trillium](https://crates.io/crates/trillium)] - 一个可组合的工具包，用于使用异步 Rust 构建互联网应用。
* 客户端 / WASM
  * [cargo-web](https://crates.io/crates/cargo-web) - 一个面向客户端 Web 的 Cargo 子命令
  * [leptos](https://github.com/leptos-rs/leptos) - Leptos 是一个全栈、同构的 Web 框架，利用细粒度响应式来构建声明式用户界面。[![crate](https://img.shields.io/crates/v/create-rust-app.svg)](https://crates.io/crates/leptos)
  * [sauron](https://github.com/ivanceras/sauron) - 严格遵循 Elm 架构的客户端 Web 框架。
  * [seed](https://github.com/seed-rs/seed) - 一个用于创建 Web 应用的框架
  * [stdweb](https://crates.io/crates/stdweb) - 面向客户端 Web 的标准库
  * [synphonyte/leptos-use](https://github.com/synphonyte/leptos-use) [[leptos-use](https://crates.io/crates/leptos-use)] - 受 React-Use 和 VueUse 启发的 Leptos 常用工具集合，具备 SSR 支持 [![Build Status](https://github.com/synphonyte/leptos-use/actions/workflows/cd.yml/badge.svg)](https://github.com/synphonyte/leptos-use/actions/workflows/cd.yml)
  * [thaw-ui/thaw](https://github.com/thaw-ui/thaw) [[thaw](https://crates.io/crates/thaw)] - 一个基于 Fluent Design 的易于使用的 Leptos 组件库
  * [tinyweb](https://github.com/LiveDuo/tinyweb) - 一个用 800 行代码为 wasm 编写的极简 Rust Web 框架
  * [yew](https://crates.io/crates/yew) - 一个用于制作客户端 Web 应用的框架
* HTTP 客户端
  * [0x676e67/wreq](https://github.com/0x676e67/wreq) - 一个具备 TLS 指纹的人体工程学 Rust HTTP 客户端。[![CI](https://github.com/0x676e67/wreq/actions/workflows/ci.yml/badge.svg)](https://github.com/0x676e67/wreq/actions/workflows/ci.yml) [![crates.io](https://img.shields.io/crates/v/wreq.svg?logo=rust)](https://crates.io/crates/wreq)
  * [alexcrichton/curl-rust](https://github.com/alexcrichton/curl-rust) - [libcurl](https://curl.se/libcurl/) 绑定
  * [async-graphql](https://github.com/async-graphql/async-graphql) - 一个 GraphQL 服务器库 [![Build Status](https://dev.azure.com/graphql-rust/GraphQL%20Rust/_apis/build/status/graphql-rust.juniper)](https://dev.azure.com/graphql-rust/GraphQL%20Rust/_build/latest?definitionId=1)
  * [c410-f3r/wtx](https://github.com/c410-f3r/wtx) - HTTP/2 客户端框架
  * [DoumanAsh/yukikaze](https://gitlab.com/Douman/yukikaze) [[yukikaze](https://crates.io/crates/yukikaze)] - 美丽优雅的 Yukikaze 是一个基于 hyper 的小型 HTTP 客户端库。[![build badge](https://gitlab.com/Douman/yukikaze/badges/master/pipeline.svg)](https://gitlab.com/Douman/yukikaze)
  * [ducaale/xh](https://github.com/ducaale/xh) - 友好且快速的 HTTP 请求发送工具 [![crate](https://img.shields.io/crates/v/create-rust-app.svg)](https://crates.io/crates/xh) [![GitHub actions Status](https://github.com/ducaale/xh/workflows/CI/badge.svg?branch=master)](https://github.com/ducaale/xh/actions)
  * [graphql-client](https://github.com/graphql-rust/graphql-client) - 类型化、正确的 GraphQL 请求和响应。[![GitHub actions Status](https://github.com/graphql-rust/graphql-client/workflows/CI/badge.svg?branch=master)](https://github.com/graphql-rust/graphql-client/actions)
  * [hyperium/hyper](https://github.com/hyperium/hyper) - 一个 HTTP 实现 [![CI](https://github.com/hyperium/hyper/workflows/CI/badge.svg?branch=master)](https://github.com/hyperium/hyper/actions?query=workflow%3ACI)
  * [plabayo/rama](https://github.com/plabayo/rama) - 一个模块化服务框架，用于移动和转换你的网络数据包，除其他用途外，还可用于构建具备 TLS、JA3/JA4、H2 和 QUIC/H3 指纹模拟的客户端
  * [seanmonstar/reqwest](https://github.com/seanmonstar/reqwest) - 一个人体工程学的 HTTP 客户端。
* HTTP 服务器
  * [branca](https://crates.io/crates/branca) - 用于认证和加密 API 令牌的 Branca 实现。
  * [c410-f3r/wtx](https://github.com/c410-f3r/wtx) - 低层和高层 HTTP/2 服务器
  * [carllerche/tower-web](https://github.com/carllerche/tower-web) [[tower-web](https://crates.io/crates/tower-web)] - 一个快速、无样板代码的 Web 框架
  * [Cot](https://github.com/cot-rs/cot) - 面向懒惰开发者的 Rust Web 框架。
  * [GildedHonour/frank_jwt](https://github.com/GildedHonour/frank_jwt) - JSON Web Token 实现。
  * [Gotham](https://github.com/gotham-rs/gotham) - 一个不牺牲安全性、安全防护或速度的灵活 Web 框架。
  * [Graphul](https://github.com/graphul-rs/graphul) - 一个受 Express 启发的 Web 框架。[![crate](https://img.shields.io/crates/v/create-rust-app.svg)](https://crates.io/crates/graphul)
  * [handlebars-rust](https://github.com/sunng87/handlebars-rust) - 一个 Iron Web 框架中间件。
  * [hyperium/hyper](https://github.com/hyperium/hyper) - 一个 HTTP 实现 [![CI](https://github.com/hyperium/hyper/workflows/CI/badge.svg?branch=master)](https://github.com/hyperium/hyper/actions?query=workflow%3ACI)
  * [Iron](https://github.com/iron/iron) - 一个基于中间件的服务器框架
  * [Juniper](https://github.com/graphql-rust/juniper) - GraphQL 服务器库
  * [miketang84/sapper](https://github.com/miketang84/sapper) - 一个构建在异步 hyper 之上的轻量级 Web 框架。
  * [Nickel](https://github.com/nickel-org/nickel.rs/) - 受 [Express](https://expressjs.com/) 启发
  * [plabayo/rama](https://github.com/plabayo/rama) - 一个模块化服务框架，用于移动和转换你的网络数据包，也可用于对入站客户端进行指纹识别
  * [poem-web/poem](https://github.com/poem-web/poem) - 一个功能齐全且易于使用的 Web 框架。[![CI](https://github.com/poem-web/poem/actions/workflows/ci.yml/badge.svg)](https://github.com/poem-web/poem/actions/workflows/ci.yml)
  * [Rustless](https://github.com/rustless/rustless) - 一个类 REST API 微框架，受 [Grape](https://github.com/ruby-grape/grape) 和 [Hyper](https://github.com/hyperium/hyper) 启发
  * [Salvo](https://github.com/salvo-rs/salvo) - 一个基于 hyper 和 tokio 的易于使用的 Web 框架。[![build build](https://github.com/salvo-rs/salvo/actions/workflows/release.yml/badge.svg)](https://github.com/salvo-rs/salvo/actions)
  * [Saphir](https://github.com/richerarc/saphir) - 一个具备底层控制力、无痛的渐进式 Web 框架。
  * [seanmonstar/warp](https://github.com/seanmonstar/warp) - 一个超级简单、可组合的 Web 服务器框架，追求 warp 速度。[![crate](https://img.shields.io/crates/v/create-rust-app.svg)](https://crates.io/crates/warp)
  * [tiny-http](https://github.com/tiny-http/tiny-http) - 底层 HTTP 服务器库
  * [tomaka/rouille](https://github.com/tomaka/rouille) - Web 框架
  * [Zino](https://github.com/zino-rs/zino) - 面向可组合应用的下一代框架
* 其他
  * [cargonauts](https://github.com/cargonauts-rs/cargonauts) - 一个旨在构建可维护、结构良好的 Web 应用的 Web 框架。
  * [edezhic/prest](https://github.com/edezhic/prest) [[prest](https://crates.io/crates/prest)] - 渐进式 RESTful 框架，旨在简化全栈开发
  * [Goldziher/spikard](https://github.com/Goldziher/spikard) [[spikard](https://crates.io/crates/spikard)] - 多语言 Web 工具包，具备 Rust 核心和面向 Python、TypeScript、Ruby 和 PHP 的绑定。
  * [hominee/dyer](https://github.com/hominee/dyer) [[dyer](https://crates.io/crates/dyer)] - dyer 专为可靠、灵活且快速的基于请求-响应的服务而设计，包括数据处理、网页抓取等，在不牺牲速度的前提下提供一些友好、灵活、全面的特性。
  * [osohq/oso](https://github.com/osohq/oso) [[oso](https://crates.io/crates/oso)] - 一个嵌入你应用中的授权策略引擎。[![Build Status](https://github.com/osohq/oso/workflows/Development/badge.svg?branch=main)](https://github.com/osohq/oso/actions?query=branch%3Amain+workflow%3ADevelopment)
  * [pwoolcoc/soup](https://gitlab.com/pwoolcoc/soup) [[soup](https://crates.io/crates/soup)] - 一个类似 Python 的 BeautifulSoup 的库，旨在实现 HTML 文档的快速简便操作和查询。[![Build Status](https://gitlab.com/pwoolcoc/soup/badges/master/pipeline.svg)](https://gitlab.com/pwoolcoc/soup/badges/master/pipeline.svg)
  * [pyrossh/rust-embed](https://git.sr.ht/~pyrossh/rust-embed) [[rust-embed](https://crates.io/crates/rust-embed)] - 一个将静态资源嵌入 rust 二进制的宏
  * [rookie](https://github.com/thewh1teagle/rookie) - 从任何平台上的任何浏览器加载 cookie。![crates.io](https://img.shields.io/crates/v/rookie.svg)
  * [rust-scraper/scraper](https://github.com/rust-scraper/scraper) [[scraper](https://crates.io/crates/scraper)] - 使用 CSS 选择器进行 HTML 解析和查询。[![Build Status](https://github.com/rust-scraper/scraper/actions/workflows/test.yml/badge.svg?branch=master)](https://github.com/rust-scraper/scraper/actions)
  * [serenity-rs/serenity](https://github.com/serenity-rs/serenity) [[serenity](https://crates.io/crates/serenity)] - 一个用于 Discord API 的库
  * [softprops/openapi](https://github.com/softprops/openapi) - 一个用于处理 openapi 规范文件的库
  * [svix/svix-webhooks](https://github.com/svix/svix-webhooks) [[svix](https://crates.io/crates/svix)] - 一个用于发送 webhook 和验证签名的库。
  * [tbot](https://gitlab.com/SnejUgal/tbot) [[tbot](https://crates.io/crates/tbot)] - 轻松制作酷炫的 Telegram 机器人 [![pipeline status](https://gitlab.com/SnejUgal/tbot/badges/master/pipeline.svg)](https://gitlab.com/SnejUgal/tbot/-/commits/master)
  * [teloxide/teloxide](https://github.com/teloxide/teloxide/) - 一个优雅的 Telegram 机器人框架 [![Build Status](https://github.com/teloxide/teloxide/actions/workflows/ci.yml/badge.svg)](https://github.com/teloxide/teloxide/actions)
  * [tu6ge/valitron](https://github.com/tu6ge/valitron) [[valitron](https://crates.io/crates/valitron)] - 一个人体工程学、函数式且可配置的验证器
  * [utkarshkukreti/select.rs](https://github.com/utkarshkukreti/select.rs) [[select](https://crates.io/crates/select)] - 一个用于从 HTML 文档中提取有用数据的库，适合网页抓取。
  * [Utoipa](https://github.com/juhaku/utoipa) - 简单、快速、代码优先且编译期生成的 OpenAPI 文档 [![crates.io](https://img.shields.io/crates/v/utoipa.svg?label=crates.io&color=orange&logo=rust)](https://crates.io/crates/utoipa) [![Utoipa build](https://github.com/juhaku/utoipa/actions/workflows/build.yaml/badge.svg)](https://github.com/juhaku/utoipa/actions/workflows/build.yaml)
  * [Utoipauto](https://github.com/ProbablyClem/utoipauto) - 用于自动向 Utoipa 添加 Paths/Schemas 的 Rust 宏 [![crates.io](https://img.shields.io/crates/v/utoipauto.svg?label=crates.io&color=orange&logo=rust)](https://crates.io/crates/utoipauto)
  * [xberg-io/crawlberg](https://github.com/xberg-io/crawlberg) [[crawlberg](https://crates.io/crates/crawlberg)] - 高性能网页抓取和爬取引擎，具备 HTML 转 Markdown 转换、无头 Chrome 回退，以及 11 种语言的绑定。
* 反向代理
  * [sozu-proxy/sozu](https://github.com/sozu-proxy/sozu) [[sozu](https://crates.io/crates/sozu)] - 一个 HTTP 反向代理。[![CI](https://github.com/sozu-proxy/sozu/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/sozu-proxy/sozu/actions/workflows/ci.yml)
* 静态站点生成器
  * [cobalt-org/cobalt.rs](https://github.com/cobalt-org/cobalt.rs) - 静态站点生成器 [![Build Status](https://dev.azure.com/cobalt-org/cobalt-org/_apis/build/status/cobalt.rs?branchName=master)](https://dev.azure.com/cobalt-org/cobalt-org/_build?definitionId=2)
  * [FuGangqiang/mdblog.rs](https://github.com/FuGangqiang/mdblog.rs) [[mdblog](https://crates.io/crates/mdblog)] - 从 markdown 文件生成静态站点。
  * [getzola/zola](https://github.com/getzola/zola) [[zola](https://www.getzola.org/)] - 一个内置一切的有主见静态站点生成器。[![Build Status](https://dev.azure.com/getzola/zola/_apis/build/status/getzola.zola?branchName=master)](https://dev.azure.com/getzola/zola/_build)
  * [grego/blades](https://github.com/grego/blades) [[blades](https://www.getblades.org/)] - 极快的极简静态站点生成器。
  * [leven-the-blog/leven](https://github.com/leven-the-blog/leven) [[leven](https://crates.io/crates/leven)] - 一个简单、并行化的博客生成器。
  * [rochacbruno/marmite](https://github.com/rochacbruno/marmite/) [[Marmite](https://marmite.blog/)] - 零配置博客生成器
  * [zensical/zensical](https://github.com/zensical/zensical) - Material for MkDocs 团队打造的现代静态站点生成器 [![Build](https://github.com/zensical/zensical/actions/workflows/build.yml/badge.svg?branch=master)](https://github.com/zensical/zensical/actions/workflows/build.yml)
* [WebSocket](https://datatracker.ietf.org/doc/rfc6455/)
  * [c410-f3r/wtx](https://github.com/c410-f3r/wtx) - 带加密支持的客户端和服务器。
  * [housleyjk/ws-rs](https://github.com/housleyjk/ws-rs) - 轻量级、事件驱动的 WebSockets
  * [iddm/urlshortener-rs](https://github.com/iddm/urlshortener-rs) - 一个非常简单的 urlshortener 库。[![CI](https://github.com/iddm/urlshortener-rs/actions/workflows/ci.yml/badge.svg)](https://github.com/iddm/urlshortener-rs/actions/workflows/ci.yml) [![Crates badge](https://img.shields.io/crates/v/urlshortener.svg)](https://crates.io/crates/urlshortener)
  * [ratchet](https://github.com/graphform/ratchet) [[ratchet_rs](https://crates.io/crates/ratchet_rs)] - Ratchet 是一个快速、轻量且完全异步的 WebSocket 协议实现，支持扩展和 Deflate。
  * [rerun-io/ewebsock](https://github.com/rerun-io/ewebsock) [[ewebsock](https://crates.io/crates/ewebsock)] - 面向 Rust 的简单 WebSocket 库，可编译为原生和 Web（WASM）。支持以异步友好的 API 发送和接收文本/二进制消息。[![unsafe forbidden](https://img.shields.io/badge/unsafe-forbidden-success.svg)](https://github.com/rust-secure-code/safety-dance/)
  * [rust-websocket](https://github.com/websockets-rs/rust-websocket) - 一个处理 WebSocket 连接（客户端和服务器）的框架
  * [snapview/tungstenite-rs](https://github.com/snapview/tungstenite-rs) - 轻量级的基于流的 WebSocket 实现。
  * [vi/websocat](https://github.com/vi/websocat) - 用于与 WebSockets 交互的 CLI，具备 Netcat、Curl 和 Socat 的功能。

## 注册中心

注册中心允许你将 Rust 库作为 crate 包发布，以公开和私有的方式与他人共享。

* [cenotelie/cratery](https://github.com/cenotelie/cratery) - 一个开箱即用的轻量级私有 cargo 注册中心，为企业构建，包含类似 [docs.rs](https://docs.rs) 和 [deps.rs](https://deps.rs) 的功能。[![CI](https://github.com/cenotelie/cratery/actions/workflows/ci.yml/badge.svg)](https://github.com/cenotelie/cratery/actions/workflows/ci.yml)
* [Cloudsmith :heavy_dollar_sign:](https://cloudsmith.com/product/formats/cargo-registry) - 一个完全托管的包管理 SaaS，对公开和私有 Cargo/Rust 注册中心（以及许多其他）提供一等支持。对开源项目免费。
* [Crates](https://crates.io) - Rust/Cargo 的官方公共注册中心。
* [getnora-io/nora](https://github.com/getnora-io/nora) - 一个轻量级的单二进制制品注册中心，支持 Docker、Maven、npm、PyPI、Cargo、Go 和原始格式。具备带缓存的上游代理和空气隔离模式。
* [RepoFlow :heavy_dollar_sign:](https://www.repoflow.io) - 一个简单现代的仓库平台，可托管 Rust crate 仓库并代理 crates.io。还支持其他包类型，如 Docker、PyPI、Maven、npm 和 RubyGems。可作为云服务或自托管。
* [w4/chartered](https://github.com/w4/chartered) - 一个私有、经过认证、带权限的 Cargo 注册中心 [![CI](https://github.com/w4/chartered/actions/workflows/ci.yml/badge.svg)](https://github.com/w4/chartered/actions/workflows/ci.yml)

## 资源

* [A Brief History of Rust. Part 1](https://medium.com/rustaceans/make-it-mandatory-a-brief-history-of-rust-part-1-805459c60c6b) - 从开发者对软件稳定性的追求，到一个几乎让其创建者陷入困境的项目。[Part 2](https://medium.com/rustaceans/make-it-mandatory-a-brief-history-of-rust-part-2-981d61451aa5)。[Part 3](https://medium.com/rustaceans/make-it-mandatory-a-brief-history-of-rust-part-2-b8c0f7a7e781?sk=c0e7fe5fde11a62edc23f284f125aa18)。
* [ANSSI-FR/rust-guide](https://github.com/ANSSI-FR/rust-guide) - 法国网络安全机构（ANSSI）关于使用 Rust 开发安全应用的建议，附有生成的检查清单
* 艺术
  * [🦀 Free Ferris Pack 🦀](https://github.com/MariaLetta/free-ferris-pack) - 50+ 张免费 Ferris 插画包，包含不同情绪、姿势和情境，提供 PNG 和 SVG，采用 CC0 许可
* 基准测试
  * [c410-f3r/wtx-bench](https://github.com/c410-f3r/wtx-bench) - Web 基准测试
  * [TeXitoi/benchmarksgame-rs](https://github.com/TeXitoi/benchmarksgame-rs) - [The Computer Language Benchmarks Game](https://benchmarksgame-team.pages.debian.net/benchmarksgame/) 的实现
* 幻灯片与演讲
  * [Learning systems programming with Rust](https://speakerdeck.com/jvns/learning-systems-programming-with-rust) - 由 [Julia Evans](https://x.com/b0rk) 在 Rustconf 2016 上演讲。
  * [Rust: Hack Without Fear!](https://www.youtube.com/watch?v=lO1z-7cuRYI) - 由 [Nicholas Matsakis](https://github.com/nikomatsakis) 在 C++Now 2018 上演讲
  * [Shipping a Solid Rust Crate](https://www.youtube.com/watch?v=t4CyEKb-ywA) - 由 [Michael Gattozzi](https://github.com/mgattozzi) 在 RustConf 2017 上演讲
* 学习
  * [100 Exercises To Learn Rust](https://rust-exercises.com) - 通过 100 个动手练习学习 Rust，涵盖语法、类型等
  * [An Introduction to Programming using entity-component-systems and existence-based processing in Rust](https://root-11.github.io/intro-book/) - Bjorn Madsen 所著的书
  * [Aquascope](https://github.com/cognitive-engineering-lab/aquascope) - Rust 在编译期和运行时的交互式可视化
  * [Awesome Rust Streaming](https://github.com/jamesmunns/awesome-rust-streaming) - 社区精选的直播列表。
  * [awesome-rust-mentors](https://rustbeginners.github.io/awesome-rust-mentors/) - 愿意接收学员并教授他们 Rust 和编程的乐于助人的导师列表。
  * [CIS 198: Rust Programming](http://cis198-2016s.github.io/schedule/) - 宾夕法尼亚大学的计算机科学 Rust 编程课程
  * [CodeCrafters.io](https://app.codecrafters.io/tracks/rust) - 构建你自己的 Redis、Git、Docker 或 SQLite
  * [Comprehensive Rust 🦀](https://google.github.io/comprehensive-rust/) - 一个为期 3 天的 Rust 基础课程，加上为期 1 天的 Android、裸机 Rust 和并发课程。提供英语、[巴西葡萄牙语](https://google.github.io/comprehensive-rust/pt-BR/)和[韩语](https://google.github.io/comprehensive-rust/ko/)版本。
  * [Easy Rust](https://github.com/Dhghomon/easy_rust) - 用简单英语学习 Rust。
  * [Embedded Software with Rust](https://www.manning.com/books/embedded-software-with-rust) - 一本关于构建快速、高效且远比用 C 或 C++ 编写的传统嵌入式软件更安全的固件的实用入门书。
  * [exercism.org](https://exercism.org/tracks/rust) - 帮助你学习 Rust 新概念的编程练习。
  * [Hands-on Rust](https://pragprog.com/titles/hwrust/hands-on-rust/) - 一本通过制作游戏学习 Rust 的动手指南 - 作者 [Herbert Wolverson](https://github.com/thebracket/)（付费）
  * [How to Avoid Fighting Rust Borrow Checker](https://qouteall.fun/qouteall-blog/2025/How%20to%20Avoid%20Fighting%20Rust%20Borrow%20Checker) - 一份关于 Rust 中借用如何工作以及如何避免借用错误的指南，作者 [Qouteall](https://github.com/qouteall)
  * [Idiomatic Rust](https://github.com/mre/idiomatic-rust) - 一个经过同行评审的文章/演讲/仓库集合，教授地道的 Rust。
  * [LabEx Rust Skill Tree](https://labex.io/skilltrees/rust) - 一条结构化的 Rust 学习路径，带动手实验，专为初学者逐步掌握 Rust 而设计。
  * [Learn Rust 101](https://rust-lang.guide/) - 一份帮助你在成为 Rustacean（Rust 开发者）之旅中前行的指南
  * [Learn Rust by 500 lines code](https://github.com/cuppar/rtd) - 通过 500 行代码学习 Rust，从零构建一个 Todo Cli 应用。
  * [Learning Rust With Entirely Too Many Linked Lists](https://rust-unofficial.github.io/too-many-lists/) - 通过实现几种不同的链表结构，深入探索 Rust 的内存管理规则。
  * [Little Book of Rust Books](https://lborb.github.io/book/) - Rust 书籍和操作指南的精选列表。
  * [Programming Community Curated Resources for Learning Rust](https://hackr.io/tutorials/learn-rust) - 由编程社区投票推荐的资源列表。
  * [Refactoring to Rust](https://www.manning.com/books/refactoring-to-rust) - 一本介绍 Rust 语言的书。
  * [Rust by Example](https://doc.rust-lang.org/rust-by-example/) - 一组可运行的示例，阐释各种 Rust 概念和标准库。
  * [Rust Cookbook](https://rust-lang-nursery.github.io/rust-cookbook/) - 一组简单示例，演示使用 Rust 生态系统的 crate 完成常见编程任务的良好实践。
  * [Rust Flashcards](https://github.com/ad-si/Rust-Flashcards) - 550+ 张卡片，从第一性原理学习 Rust。
  * [Rust for professionals](https://overexact.com/rust-for-professionals/) - 面向有经验的软件开发者的 Rust 快速入门。
  * [Rust Gym](https://github.com/warycat/rustgym) - 一个用 Rust 解决编码面试问题的大型集合。
  * [Rust in Action](https://www.manning.com/books/rust-in-action) - [Tim McNamara](https://github.com/timClicks) 所著的 Rust 系统编程动手指南（付费）
  * [Rust in Motion](https://www.manning.com/livevideo/rust-in-motion?a_aid=cnichols&a_bid=6a993c2e) - [Carol Nichols](https://github.com/carols10cents) 和 [Jake Goulding](https://github.com/shepmaster) 制作的视频系列（付费）
  * [Rust Language Cheat Sheet](https://cheats.rs/) - Rust 语言速查表
  * [Rust Tiếng Việt](https://rust-tieng-viet.github.io/) - 用越南语学习 Rust。
  * [rust-how-do-i-start](https://github.com/jondot/rust-how-do-i-start) - 一个专门回答以下问题的仓库："那么，Rust。我该如何*开始*？"。一个仅供初学者、精挑细选的资源及学习路线。
  * [rust-learning](https://github.com/ctjhoa/rust-learning) - 一组学习 Rust 的有用资源
  * [Rustfinity](https://www.rustfinity.com) - 通过动手练习和挑战练习 Rust 的交互式平台
  * [Rustlings](https://github.com/rust-lang/rustlings) - 让你习惯于阅读和编写 Rust 代码的小练习
  * [Rusty CS](https://github.com/AbdesamedBendjeddou/Rusty-CS) - 一个计算机科学课程，帮助你在 Rust 中实践所学到的学术知识
  * [stdx](https://github.com/brson/stdx) - 作为 std 的扩展，先学习这些 crate
  * [Tour of Rust](https://tourofrust.com) - 一本旨在作为 Rust 编程语言特性的交互式分步指南。
* 性能
  * [How to avoid bounds checks in Rust (without unsafe!)](https://shnatsel.medium.com/how-to-avoid-bounds-checks-in-rust-without-unsafe-f65e618b4c1e) - 关于优化边界检查你需要知道的一切
  * [Performance of Rust language](https://raw.githubusercontent.com/yugr/rust-slides/main/EN.pdf) - Rust 面向性能的语言特性概览
  * [The Rust Performance Book](https://nnethercote.github.io/perf-book/) - 优化 Rust 程序的技巧
* 播客
  * [New Rustacean](https://newrustacean.com) - 一个关于学习 Rust 的播客
  * [Rustacean Station](https://rustacean-station.org/) - 一个为 Rust 创作播客内容的社区项目
* [Rust Design Patterns](https://github.com/rust-unofficial/patterns) - 一个 Rust 设计模式、反模式和惯用法的目录
* [Rust Guidelines](http://aturon.github.io/) - Aaron Turon 关于 rust 的博客文章
* [Rust Security Handbook](https://github.com/yevh/rust-security-handbook) - 一本 10 章的手册，讲述如何编写真正安全的 Rust：类型安全、防 panic 等。
* [Rust Servers, Services and Apps - MEAP](https://www.manning.com/books/rust-servers-services-and-apps) - 用 Rust 构建后端服务器、服务和前端，以获得快速、可靠且可维护的应用。
* [Rust Subreddit](https://www.reddit.com/r/rust/) - 一个发布和讨论 rust 相关问题、文章和资源的 subreddit（论坛）
* [RustBooks](https://github.com/sger/RustBooks) - Rust 书籍列表
* [RustCamp 2015 Talks](https://www.youtube.com/playlist?list=PLE7tQUdRKcybdIw61JpCoo89i4pWU5f_t) - RustCamp 2015 的演讲录像
* [RustViz](https://github.com/rustviz/rustviz) - 从简单的 Rust 程序生成可视化，帮助用户更好地理解 Rust 的生命周期和借用机制。
* [Watch Jon Gjengset Implement BitTorrent in Rust](https://www.youtube.com/watch?v=jf_ddGnum_4) - 用 Rust 实现（部分）BitTorrent 客户端

## 许可证

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)
