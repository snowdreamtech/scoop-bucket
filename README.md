# Snowdreamtech Scoop Bucket

[English](README.md) | [简体中文](README-zh.md)

This is a custom [Scoop](https://scoop.sh/) bucket provided by [snowdreamtech](https://github.com/snowdreamtech). It primarily hosts **UniRTM**, a cross-platform developer toolchain manager.

## What is UniRTM?

**UniRTM** (Uni Runtime and Tools Manager) is a cross-platform developer toolchain manager. It helps you manage your runtime environments, development tools, and tasks consistently across Windows, macOS, and Linux.

## Installation Guide

### Prerequisites
Make sure you have [Scoop](https://scoop.sh/) installed on your Windows environment. If not, open PowerShell and run:
```powershell
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser
Invoke-RestMethod -Uri https://get.scoop.sh | Invoke-Expression
```

### Add Bucket and Install

1. **Add this bucket**
   ```powershell
   scoop bucket add snowdreamtech https://github.com/snowdreamtech/scoop-bucket.git
   ```

2. **Update Scoop**
   ```powershell
   scoop update
   ```

3. **Install UniRTM**
   ```powershell
   scoop install unirtm
   ```

## Usage

After installation, you can use the `unirtm` command directly in your terminal:
```bash
unirtm --help
```
For more detailed usage and configuration, please refer to the [UniRTM Official Repository](https://github.com/snowdreamtech/UniRTM).

## License

This project is licensed under the MIT License.
