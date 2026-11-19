# 安全说明

## 请勿公开的信息

提交问题或截图时，请删除以下内容：

- AI Provider API Key
- Supabase secret、service-role key 或访问令牌
- `settings.json`
- `ideas.db`
- 私人灵感正文
- 邮箱、设备名等个人信息

Supabase publishable key用于客户端访问，但仍应与正确的数据库权限策略配合使用，不应把个人项目的完整连接信息发布到公开 Issue。

## 报告安全问题

请优先通过 GitHub 仓库的 Security Advisory 私密报告安全问题，不要先创建公开 Issue。报告中请提供软件版本、Windows 版本、复现步骤和已脱敏的错误信息。

## 下载校验

只从项目官方 GitHub Releases 页面下载念念，并核对发布页面提供的 SHA-256。当前 Beta 包尚未进行商业代码签名，Windows 可能显示 SmartScreen 提示。
