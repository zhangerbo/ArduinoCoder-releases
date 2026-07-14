# <img src="https://raw.githubusercontent.com/zhangerbo/ArduinoCoder-releases/main/icon.png" width="32" height="32"> ArduinoCoder

新一代 Arduino 集成开发环境，为嵌入式开发打造的专业 IDE。

![Screenshot](https://via.placeholder.com/800x500/0d1117/00979D?text=ArduinoCoder+Screenshot)

---

## 下载

**最新版本：v0.1.0**

| 平台 | 下载 | 大小 |
|------|------|------|
| Windows 10/11 (x64) | [ArduinoCoder Setup 0.1.0.exe](https://github.com/zhangerbo/ArduinoCoder-releases/releases/latest/download/ArduinoCoder%20Setup%200.1.0.exe) | ~109 MB |

> macOS 和 Linux 版本即将推出。

---

## 核心特性

### 专业代码编辑器
集成 **Monaco Editor**（VS Code 同款内核），支持 Arduino C++ 语法高亮、智能代码补全、代码折叠、括号配对着色。

### 极速编译 & 一键上传
基于官方 **Arduino CLI** 构建，支持 gRPC 流式编译反馈、实时进度条、错误精确定位到行列。

### AI 编程助手
支持 **DeepSeek** / **MiniMax** / **Qwen** 三种国产 AI 模型。可直接读写项目文件、编译代码、上传到开发板——在聊天框里完成完整开发流程。

| AI 提供商 | 可用模型 |
|------|------|
| DeepSeek | v4-pro, v4-flash（支持思考模式） |
| MiniMax | M3, M2.7, M2.5（支持自适应思考） |
| Qwen | plus, max, coder |

### 串口监视器 & 绘图仪
实时串口数据收发，支持多种波特率（300 ~ 921600）。内置串口绘图仪，传感器数据可视化调试。

### 板卡与库管理
丰富的开发板支持——Uno / Mega / Nano / MKR / Portenta / ESP32 / STM32 / Raspberry Pi Pico。在线搜索安装第三方库，一键完成。

### 深色 / 浅色主题
精心调校的双主题配色方案，长时间编程不疲劳。支持一键切换。

### 中英文双语界面
完整支持中文和英文界面，一键切换。专为国内开发者优化。

---

## 技术栈

| 层 | 技术 |
|------|------|
| 桌面框架 | Electron 33 |
| 前端 UI | React 18 + TypeScript |
| 代码编辑器 | Monaco Editor 0.52 |
| 状态管理 | Zustand |
| 编译后端 | Arduino CLI + gRPC |
| 语言服务 | clangd LSP |
| 串口通信 | serialport |
| 打包 | electron-builder (NSIS) |

---

## 安装要求

- Windows 10 或 Windows 11（64 位）
- 至少 500MB 可用磁盘空间
- 首次运行时需要联网下载 Arduino AVR 平台（~150MB）

---

## 反馈与建议

- [GitHub Issues](https://github.com/zhangerbo/ArduinoCoder-releases/issues)

---

## 开源协议

本项目采用 [MIT License](LICENSE)。

Arduino 商标归 Arduino AG 所有。ArduinoCoder 为独立社区项目。
