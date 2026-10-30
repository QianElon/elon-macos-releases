# 一龙工作台 Mac 测试版

本仓库仅分发安装包和验证说明，不存放应用源码。源码和构建仓库保持私有。

macOS 14+；一个通用包同时包含 Apple Silicon（M 系列）和 Intel。

## 下载

安装包通过云 Mac 构建、测试、架构及签名完整性检查后发布：

- [最新通用 DMG](https://github.com/QianElon/elon-macos-releases/releases/download/macos-preview-latest/elon-macos-preview-universal.dmg)
- [最新应用 ZIP](https://github.com/QianElon/elon-macos-releases/releases/download/macos-preview-latest/elon-macos-preview-universal.app.zip)
- [版本、来源与架构清单](https://github.com/QianElon/elon-macos-releases/releases/download/macos-preview-latest/release-manifest.json)
- [SHA256 校验文件](https://github.com/QianElon/elon-macos-releases/releases/download/macos-preview-latest/SHA256SUMS.txt)
- [安装说明与已知限制](https://github.com/QianElon/elon-macos-releases/releases/download/macos-preview-latest/TESTING.md)
- [全部历史预览版本](https://github.com/QianElon/elon-macos-releases/releases)

## 验收边界

这是 ad-hoc 签名预览版，未 Apple Developer ID 签名或公证。
云端构建和本地页面 WKWebView 检查不能代替用户 Mac 的真实账号与业务验收。
本包连接现有工作台，不包含本地 Windows 节点服务；具体限制见每个版本的安装与验收说明。
