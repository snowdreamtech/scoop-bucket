# Snowdreamtech Scoop Bucket

[English](README.md) | [简体中文](README-zh.md)

这是 [snowdreamtech](https://github.com/snowdreamtech) 提供的自定义 [Scoop](https://scoop.sh/) 软件仓库 (Bucket)。目前主要包含跨平台开发工具链管理器 **UniRTM**。

## 什么是 UniRTM？

**UniRTM** (Uni Runtime and Tools Manager) 是一个跨平台的开发者工具链管理器。它支持在 Windows、macOS 和 Linux 上统一管理你的运行时环境、开发工具以及任务。

## 安装指南

### 前置条件
确保你已经在 Windows 环境中安装了 [Scoop](https://scoop.sh/)。如果未安装，请在 PowerShell 中执行以下命令：
```powershell
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser
Invoke-RestMethod -Uri https://get.scoop.sh | Invoke-Expression
```

### 添加 Bucket 并安装软件

1. **添加本仓库 (Bucket)**
   ```powershell
   scoop bucket add snowdreamtech https://github.com/snowdreamtech/scoop-bucket.git
   ```

2. **更新 Scoop**
   ```powershell
   scoop update
   ```

3. **安装 UniRTM**
   ```powershell
   scoop install unirtm
   ```

## 使用 UniRTM

安装完成后，你可以直接在命令行中使用 `unirtm` 命令：
```bash
unirtm --help
```
有关 UniRTM 的更多详细用法和配置，请参考 [UniRTM 官方主页](https://github.com/snowdreamtech/UniRTM)。

## 开源协议

本项目基于 MIT 协议开源。
