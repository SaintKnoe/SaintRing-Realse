<p align="center"><img src="assets/SaintRing.png" width="128" alt="SaintRing"></p>

# SaintRing

macOS 圆环应用与窗口切换器。仅支持 Apple Silicon（arm64），macOS 13 或更新版本。

[下载最新 DMG](https://github.com/SaintKnoe/SaintRing-Realse/releases/latest)

将 DMG 中的 SaintRing 拖到“应用程序”，启动后在系统设置中授予辅助功能权限。

- ⌘Tab：选择应用，松开 Command 确认；Shift 反向，Esc 取消。
- ⌘←／→：指针所在窗口占左／右半屏；⌘↑ 填满可用区域；⌘↓ 最小化。
- ⌘⌥←／→：两个可见窗口左右分屏。
- 标题栏双指滑动操作单个窗口；Dock 上下滑动恢复或隐藏应用。
- 窗口快捷键仅在指针停在标题栏／标签栏空白处时生效，正文和按钮上保留原应用快捷键。
- 自动检测更新，支持应用内下载和安装；菜单栏可手动“检查更新”。

此仓库保存发布包和更新订阅，源码仓库为 [SaintRing](https://github.com/SaintKnoe/SaintRing)（需要访问权限）。

本版本使用本地应用签名，尚未经过 Apple Developer ID 公证。DMG 提供 SHA-256 校验；应用内更新额外使用 Ed25519 签名验证。

当前 0.2.0 是首个内置更新器的版本，旧的本地开发版需要先手动安装一次。后续更新可在应用内完成。
