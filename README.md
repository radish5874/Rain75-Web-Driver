[README.md](https://github.com/user-attachments/files/35484908/README.md)
# Rain75-Web-Driver
Unofficial Web-based Configuration Tool for Rain75 Keyboard.
# Rainy75 Studio
# Rain75 Web Driver

An unofficial, lightweight, web-based configuration tool for the original Rainy 75 mechanical keyboard.

![Version](https://img.shields.io/badge/Version-v0.4.4-blue)
![Protocol](https://img.shields.io/badge/Protocol-VIA%20%2F%20WOB-green)
![Platform](https://img.shields.io/badge/Platform-WebHID-blue)
![Status](https://img.shields.io/badge/Status-Active%20Development-orange)

**[Download Latest Release](https://github.com/radish5874/Rain75-Web-Driver/releases/latest)** | **[Report an Issue](https://github.com/radish5874/Rain75-Web-Driver/issues)**

## Introduction

Rain75 Web Driver, also known as Rainy75 Studio, is an independent keyboard configuration tool designed for the original Rainy 75 RGB mechanical keyboard.

Inspired by Wootility, this project provides a unified interface for both VIA and WOB proprietary protocols, aiming to overcome the limitations of existing configuration software and unlock more of the keyboard's hardware capabilities.

The application is built with HTML, CSS, JavaScript, Python, and the WebHID API.

## Features

- Automatic VIA / WOB protocol detection
- Key remapping and batch key remapping
- Drag-and-drop key assignment
- Individual RGB control for all 81 keys with WOB firmware
- Real-time RGB visualization
- Experimental live hardware RGB synchronization
- HSV and HEX color selection
- 20 WOB lighting modes
- Key testing and input diagnostics
- Configuration backup and restoration
- Firmware identification
- Battery level reporting
- English and Simplified Chinese support
- Dark, light, and system themes
- Local operation without an account

## Firmware Compatibility

| Feature | VIA Firmware | WOB Firmware |
|---|---|---|
| USB Connection | Supported | Supported |
| Base Layer Remapping | Supported | Supported |
| Fn Layer Remapping | Supported | In Development |
| Macro Editor | Supported | In Development |
| Global RGB Control | Supported | Supported |
| Per-Key RGB | Not Verified | Supported |
| Live RGB Synchronization | Limited | Experimental |
| Battery Information | Not Verified | Experimental |
| Physical Matrix Testing | Experimental | In Development |
| 2.4 GHz Configuration | Partial | Planned |
| Bluetooth Configuration | Planned | Planned |

Currently tested on the original Rainy 75 RGB ANSI keyboard.

Rainy 75 RT, Rainy 75 V2, and other keyboard models are not officially supported by this project.

## Getting Started

### Requirements

- Windows
- Python 3
- Google Chrome or Microsoft Edge
- A compatible Rainy 75 keyboard
- USB data cable

### Installation

1. Download the latest release from the Releases page.
2. Extract the ZIP archive.
3. Install Python 3 if necessary.
4. Run `start-windows.bat`.
5. Open `http://localhost:8769` in your browser.
6. Connect your keyboard using USB.
7. Click **Connect Keyboard** and authorize the device.
8. Configure your keyboard and save your changes.

Close VIA and the official WOB driver before connecting to avoid communication conflicts.

## Development Roadmap

- [x] VIA protocol support
- [x] WOB USB protocol support
- [x] Unified VIA / WOB interface
- [x] Per-key RGB control
- [x] Batch key remapping
- [x] Real-time RGB visualization
- [x] Experimental hardware RGB synchronization
- [ ] Complete physical matrix detection
- [ ] Fn key detection
- [ ] WOB Fn layer remapping
- [ ] WOB macro editor
- [ ] USB polling rate configuration
- [ ] Keyboard sleep configuration
- [ ] Full device settings control
- [ ] Accurate dynamic RGB synchronization
- [ ] Independent Fn layer lighting
- [ ] 2.4 GHz wireless configuration
- [ ] Bluetooth configuration

## Known Issues

- Fn and right Shift detection may not function correctly under WOB firmware.
- Dynamic RGB visualization may differ from the physical keyboard.
- WOB Fn layer currently displays reference shortcuts rather than a confirmed device keymap.
- Some device settings are still under protocol investigation.
- Wireless configuration is not fully supported.

## Disclaimer

This is an independent, unofficial project and is not affiliated with WOBKEY, VIA, or Wooting.

Some features are experimental. Back up your keyboard configuration before making changes.

Use this software at your own risk. Firmware updates and unsupported configuration operations may result in unexpected behavior.

---

# 中文介绍

Rain75 Web Driver（Rainy75 Studio）是一款专为原版 Rainy 75 RGB 机械键盘开发的第三方网页驱动。

本项目采用受 Wootility 启发的界面设计，同时兼容 VIA 和 WOB 原厂私有通信协议，旨在突破现有驱动的功能限制，提供更加统一、直观且完整的键盘配置体验。

## 主要功能

- VIA / WOB 双协议自动识别
- 单键及批量改键
- 拖拽改键与框选
- 81 键独立 RGB 配色（WOB 固件）
- 实时网页灯光渲染
- 实验性实体灯光同步
- 自定义灯效
- 按键测试
- 配置备份与恢复
- 固件识别与电量查询
- 中英文界面
- 深色与浅色主题
- 本地运行，无需注册账号

## 使用方法

1. 在 Releases 页面下载最新版本。
2. 解压文件。
3. 安装 Python 3。
4. 双击运行 `start-windows.bat`。
5. 使用 Chrome 或 Edge 访问 `http://localhost:8769`。
6. 通过 USB 连接键盘并授权。
7. 开始配置键盘。

## 后续开发目标

完善物理矩阵检测、Fn 层改键、Fn 层独立灯光、宏编辑、动态 RGB 同步、回报率控制、设备休眠设置以及无线连接配置。

目前项目仍处于积极开发阶段，欢迎提交 Bug、功能建议和硬件测试反馈。

## 免责声明

本项目为非官方独立开发项目，与 WOBKEY、VIA 和 Wooting 无隶属关系。

部分功能仍处于实验阶段，使用前请备份键盘配置。

## Disclaimer / 免责声明

### English

Rain75 Web Driver (Rainy75 Studio) is an independent, unofficial project developed for educational, research, and personal use. This project is not affiliated with, endorsed by, or sponsored by WOBKEY, VIA, or Wooting.

This software is provided **"AS IS"**, without warranties of any kind, express or implied, including but not limited to warranties of merchantability, fitness for a particular purpose, compatibility, reliability, and non-infringement.

Some features are experimental and are based on the analysis of proprietary communication protocols. Compatibility with all hardware revisions, firmware versions, and connection modes is not guaranteed.

By using this software, you acknowledge the potential risks, including but not limited to:

- Hardware damage or malfunction.
- Firmware corruption or device bricking.
- Loss of keyboard configurations, macros, or lighting settings.
- Loss of wireless connectivity or receiver compatibility.
- Unexpected keyboard behavior.
- Potential impact on the manufacturer's warranty.

Users are responsible for verifying hardware and firmware compatibility and backing up their configurations before performing any modifications.

To the maximum extent permitted by applicable law, the developer and contributors shall not be liable for any direct, indirect, incidental, special, or consequential damages arising from the use, misuse, or inability to use this software.

All third-party trademarks, product names, and logos belong to their respective owners.

**USE AT YOUR OWN RISK.**

### 中文

Rain75 Web Driver（Rainy75 Studio）是一个独立开发的非官方项目，仅供学习、技术研究及个人使用。本项目与 WOBKEY、VIA、Wooting 均无隶属、授权、赞助或官方合作关系。

本软件按**现状（AS IS）**提供，不附带任何明示或默示的保证，包括但不限于适销性、特定用途适用性、兼容性、可靠性及非侵权保证。

本项目部分功能仍处于实验阶段，并基于对原厂私有通信协议的分析实现，不保证兼容所有硬件版本、固件版本及连接模式。

使用本软件可能产生以下风险，包括但不限于：

- 键盘硬件损坏或功能异常。
- 固件损坏、刷写失败或设备变砖。
- 键位、宏及灯光配置丢失。
- 无线连接或接收器兼容性异常。
- 键盘出现非预期行为。
- 可能影响原厂保修权益。

用户应自行确认硬件及固件兼容性，并在进行任何修改前备份原始配置。

在适用法律允许的最大范围内，项目开发者及贡献者不对因使用、误用或无法使用本软件而产生的任何直接、间接、附带、特殊或后果性损失承担责任。

本项目涉及的第三方商标、产品名称及标志均归其各自权利人所有。

**请自行评估风险，谨慎使用。**
---

**Made for Rainy 75 enthusiasts.**
