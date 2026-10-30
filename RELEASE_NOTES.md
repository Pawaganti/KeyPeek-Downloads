# 轻键 KeyPeek 0.2.2

轻键 KeyPeek 是一款 Windows 键盘映射与文件速览工具。选中文件后按空格即可预览，按 Tab 查看文件信息；支持图片浏览、音视频播放和透明素材查看。

## 下载与运行

- [安装版 EXE](https://github.com/Pawaganti/KeyPeek-Downloads/releases/download/v0.2.2/KeyPeek_Setup_0.2.2_x64.exe)：双击进入 Windows 安装向导，按提示完成安装。
- [便携版 ZIP](https://github.com/Pawaganti/KeyPeek-Downloads/releases/download/v0.2.2/KeyPeek_Portable_0.2.2_x64.zip)：完整解压后，双击 `KeyPeek_0.2.2/KeyPeek.exe`。
- [SHA-256 校验文件](https://github.com/Pawaganti/KeyPeek-Downloads/releases/download/v0.2.2/SHA256SUMS.txt)

系统要求：Windows 10 2004 及以上的 x64 系统。安装版会检查所需运行组件；便携版已包含运行依赖。

首次启动后，请通过右下角托盘图标打开设置，开启键盘映射或空格速览。关闭设置窗口后程序继续在后台运行。

## 版本更新

- 修复视频首帧显示前可能出现的白色背景。
- 优化播放引擎的后台预热与复用，减少连续打开视频时的等待。
- 将视频探测和初始化移出界面线程，改善加载期间的界面响应。
- 改进透明视频识别；快速探测无法确定透明度时，继续完整探测。
- 切换文件时取消过期的探测任务，避免旧任务影响当前文件。
- 调整本地视频播放缓冲，保留透明画面与音频同步。
- 提供带 Windows 安装向导的 EXE 安装版、解压运行的 ZIP 便携版和 SHA-256 校验文件。

## 使用提示

Office 文档提供内容预览，不还原完整排版；透明视频支持取决于编码。当前发行文件尚未进行代码签名。

完整操作说明与已知限制见 [项目主页](https://github.com/Pawaganti/KeyPeek-Downloads#readme)。
