# ProduKey 简体中文语言文件 🇨🇳

[![Platform](https://img.shields.io/badge/platform-Windows-blue.svg)](https://www.nirsoft.net/utils/product_key_finder.html)
[![Language](https://img.shields.io/badge/language-%E7%AE%80%E4%BD%93%E4%B8%AD%E6%96%87-brightgreen.svg)](https://github.com/DaXiGua732/produkey-chinese)
[![License](https://img.shields.io/badge/license-MIT-yellow.svg)](LICENSE)

为 [NirSoft](https://www.nirsoft.net/) 出品的 **ProduKey** 制作的简体中文语言文件（非官方汉化）。

- **适用软件**：ProduKey（Nir Sofer 出品）
- **适用版本**：1.97
- **文件**：`ProduKey_lng.ini`
- **编码**：ANSI（GBK，CRLF），中文 Windows 直接可用
- **翻译者**：[DaXiGua732](https://github.com/DaXiGua732)

---

## 软件简介

**ProduKey** 是一款微软产品密钥（Product Key / CD-Key）恢复工具，出自 **Nir Sofer**（NirSoft 作者）。它可从注册表中提取本机以及以下产品安装时使用的密钥：

- **Windows**（含 BIOS OEM 密钥）
- **Office**（2000 / XP / 2003 / 2007 / 2010 / 2013 / 2016）
- **Internet Explorer**、**SQL Server**、**Exchange Server**
- **Visual Studio**、**Adobe / Autodesk** 系列产品

支持从本地计算机、外部 Windows 安装、注册表配置单元、远程计算机（IP 范围/域名/文本列表）等数十种数据源提取密钥，并支持导出为 HTML/XML/CSV 等格式。

官网：<https://www.nirsoft.net/utils/product_key_finder.html>

## 使用方法

1. 从 [Releases](https://github.com/DaXiGua732/produkey-chinese/releases) 或直接下载 `ProduKey_lng.ini`；
2. 将文件放到 `ProduKey.exe` 所在目录；
3. 重新启动 ProduKey，界面即变为简体中文，**关于**窗口中会显示翻译者信息。

> 💡 想恢复英文界面？直接删除或改名该 ini 文件即可。

### 语言文件机制说明

ProduKey 支持 NirSoft 标准语言包机制：运行 `ProduKey.exe /savelangfile` 会生成英文模板 `ProduKey_lng.ini`，将模板中的字符串翻译为目标语言并保持同名同目录，程序启动时自动加载。

## 汉化范围

- ✅ 主菜单、右键菜单（含快捷键）
- ✅ 属性、选择数据源、列设置等对话框
- ✅ 全部状态文本与提示、文件类型列表
- ✅ 产品系列名称（Windows / Office / SQL Server 等）

## 许可与版权说明

### 原软件（ProduKey）

- 作者与版权：**Nir Sofer**（[NirSoft](https://www.nirsoft.net/)），**免费软件（Freeware），非开源**。
- 依据 [NirSoft 免费软件许可协议](https://www.nirsoft.net/nirsoft_license.html)：
  - 允许免费使用与分发（含网络分发）；
  - **禁止**收费、出售或作为商业产品的一部分分发；
  - 分发官方程序包时必须包含全部文件且不得修改。
- 本仓库**不包含**原软件可执行文件，仅分发语言文件。

### 本汉化文件（ProduKey_lng.ini）

第三方翻译作品，按 [MIT License](LICENSE) 授权。与 NirSoft 官方团队无任何关联，使用本补丁即表示你同时接受原软件的许可条款。

### 免责声明

本汉化文件按 "AS IS" 提供，不附带任何明示或隐含的担保。请仅配合正版、官方渠道获取的 ProduKey 使用。

*ProduKey 与 NirSoft 名称归各自权利人所有；本仓库仅提供翻译文件。*
