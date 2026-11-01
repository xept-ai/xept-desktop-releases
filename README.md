# Xept 安装包

Xept 是一个用 AI 写论文的桌面应用：LaTeX 和 Word 都能写，AI 直接改你的论文、编译、核查参考文献、模拟审稿，也能从你的想法和实验结果一口气写出整篇初稿。用你自己的 AI 账号，不需要注册 Xept。

这个仓库只放安装包，在右边的 **Releases** 里下载最新版本。

> **Mac 用户第一次打开前请看**：Mac 版还没有经过苹果公证，第一次打开会被系统拦一下（提示"Apple 无法检查其是否包含恶意软件"），这不是程序坏了。打开一次以后就能正常双击：
> - **macOS 14 及更早**：在「应用程序」里右键点 Xept →「打开」，弹窗里再点「打开」。
> - **macOS 15 及以上**：先双击一次，再到「系统设置 → 隐私与安全性」，拉到最下面点 Xept 旁边的「仍要打开」。
>
> 怎么看系统版本：点左上角苹果菜单 →「关于本机」。

## 下载哪个

| 你的电脑 | 下载 |
|---|---|
| Mac，Apple 芯片（M1–M4） | `Xept-版本号-mac-arm64.dmg` |
| Windows 10 / 11（64 位） | `Xept-版本号-win-x64-setup.exe` |
| Linux（64 位），各发行版通用 | `Xept-版本号-linux-x86_64.AppImage` |
| Ubuntu / Debian（64 位） | `Xept-版本号-linux-amd64.deb` |

从 0.4.0 起只提供 Apple 芯片的 Mac 版。Intel 芯片的 Mac 请继续用 0.3.1（在 Releases 里找 v0.3.1 的 `Xept-0.3.1-mac-x64.dmg`）。

不知道 Mac 是哪种芯片：点左上角苹果菜单 →「关于本机」，「芯片」写 Apple M… 就是 Apple 芯片，写 Intel 就是 Intel。

## 安装

测试版还没有签名，第一次打开 Mac 和 Windows 会拦一下：

**Mac**
1. 双击 dmg，把 **Xept** 拖进「应用程序」。
2. 第一次打开：在「应用程序」里**右键 Xept → 打开**，再点「打开」；或者在「系统设置 → 隐私与安全性」最下面点「仍要打开」。

**Windows**
1. 双击 `setup.exe`。如果出现「Windows 已保护你的电脑」，点「更多信息」→「仍要运行」。
2. 按提示安装，默认只装给当前用户，不需要管理员权限。

**Linux**
- AppImage：先在终端运行 `chmod +x Xept-版本号-linux-x86_64.AppImage`，再双击或在终端运行它。
- Ubuntu / Debian 也可以用 deb：`sudo apt install ./Xept-版本号-linux-amd64.deb`。
- Linux 版暂不自动更新，有新版本时 Xept 会提示，到这里下载新的安装包。

打开后在「设置」里填上你的 AI 账号（Claude、ChatGPT、DeepSeek、Kimi、智谱 GLM 都可以）。第一次打开时系统可能会问 Xept 能不能访问钥匙串（加密保存 AI 账号）、桌面或文稿文件夹（打开放在那里的论文时），都点「允许」。

LaTeX、Python 等需要时 Xept 会自己装，装在 Xept 自己的文件夹里，不影响电脑上原有的软件。

## 反馈

遇到问题或有建议，直接告诉发安装包给你的人。
