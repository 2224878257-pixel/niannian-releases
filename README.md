# 念念

念念是一款极简、离线优先的 Windows 灵感记录工具。按下 `Ctrl + Shift + Space`，写下一句话，按 Enter 保存，然后继续当前工作。

## 当前版本

`v1.10.0-beta.1` 免费公测版。

[前往 Releases 下载最新版](https://github.com/2224878257-pixel/niannian-releases/releases)

## 功能

- 全局快捷键快速呼出
- Enter 保存、Shift + Enter 换行、Esc 关闭
- 本地 SQLite 存储
- 历史记录、关键词搜索和标签筛选
- 编辑已有记录
- 系统托盘与开机启动
- 可选的个人 Supabase 多电脑同步
- 可选的 AI 整理和内容生成（使用用户自己的 API Key）

## 安装

1. 在 Releases 页面下载 `Niannian-*-win64-portable.zip`。
2. 核对同一版本提供的 `SHA256SUMS.txt`。
3. 解压到固定文件夹，不要直接在压缩包中运行。
4. 双击 `QuickIdea.exe`。

当前 Beta 包尚未进行商业代码签名，Windows 可能显示 SmartScreen 提示。请只从本仓库 Releases 页面下载。

## 数据位置

```text
%LOCALAPPDATA%\QuickIdea\ideas.db
%LOCALAPPDATA%\QuickIdea\settings.json
```

更新或移动 EXE 不会自动删除上述数据。操作前仍建议备份整个 `%LOCALAPPDATA%\QuickIdea` 文件夹。

## 免费公测

当前版本不收费、不需要 License。本地记录无需账号；同步和 AI 均为可选功能，分别使用用户自己的 Supabase 项目和 AI Provider API Key。

后续商业模式如有调整，会提前在版本说明中公布，并确保用户仍能访问和导出已有本地记录。

## 反馈问题

可以通过 GitHub Issues 提交已脱敏的问题。请勿上传 API Key、访问令牌、`settings.json`、`ideas.db` 或私人灵感正文。

安全问题请通过 GitHub Security Advisory 私密报告。

## 文档

- [更新日志](CHANGELOG.md)
- [隐私说明](PRIVACY.md)
- [安全说明](SECURITY.md)
- [使用许可](LICENSE.txt)
