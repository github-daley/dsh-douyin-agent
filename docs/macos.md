# macOS DSH 插件预览

这是 fork 的 macOS 适配分支。目标是 Apple Silicon、DeepSeek Harness Desktop 0.2.2-rc.2，以及安装在 `/Applications/Google Chrome.app` 的 Chrome。Windows 仍使用 Edge；独立桌面 EXE 不适用。

1. 在本源码目录执行 `pnpm install --frozen-lockfile`。
2. 在 DSH 的插件入口添加本源码目录作为本地 bundle。不要运行 Windows 的 `install-native.ps1`，也不要安装上游 npm 版来代替这个目录。
3. 从“设置 → 刷抖音”运行自检，再点“打开抖音”。需要时在专用 Chrome 中手动登录；浏览器使用插件专属资料目录，不接管常用的 Chrome 窗口。
4. 先确认搜索、截图和暂停；要理解画面，再选择已配置且支持图片输入的 DSH 模型。确认后再启用限时自动观看。

音频、QQ 共享和对外发送暂不列入此预览的 macOS 验收。启用观看时仍需遵守设置的时段和每日预算。
