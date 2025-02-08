[icons](https://github.com/M-L-P/icons)|[rEFInd-theme-Yours](https://github.com/M-L-P/rEFInd-theme-Yours)|[Yours-LegacyBIOS](https://github.com/M-L-P/Yours-LegacyBIOS)|[Yours-UEFI](https://github.com/M-L-P/Yours-UEFI)
-|-|-|-

<div align="center">

[![GitHub release (latest by date)](https://img.shields.io/github/v/release/M-L-P/rEFInd-theme-Yours)](https://github.com/M-L-P/rEFInd-theme-Yours/releases/latest)
[![GitHub all releases](https://img.shields.io/github/downloads/M-L-P/rEFInd-theme-Yours/total)](https://github.com/M-L-P/rEFInd-theme-Yours/releases)
[![GitHub Discussions](https://img.shields.io/github/discussions/M-L-P/rEFInd-theme-Yours)](https://github.com/M-L-P/rEFInd-theme-Yours/discussions)
[![GitHub Repo stars](https://img.shields.io/github/stars/M-L-P/rEFInd-theme-Yours?style=social)](https://github.com/M-L-P/rEFInd-theme-Yours/stargazers)

</div>

[English](README.md)|[简体中文](README-自述文件.md)|[繁體中文](README-繁體中文.md)|...
--|--|--|--

<h1 align="center">Yours</h1>
Y-o-u-r-s,<br/>
Your own usual rEFInd's sign.

- 你可以
- - ✏️自定义 ***用户头像*** ；
- - ✏️自定义 ***设备名称*** ；
- - ✏️自定义 ***机主姓名*** 。

- 基于 *Roderick W. Smith* 的 [rEFInd Boot Manager](http://www.rodsbooks.com/refind/)，嵌套 [a1ive](https://github.com/a1ive) 的 [grub2-filemanager](https://github.com/a1ive/grub2-filemanager)。
- - 所以你可以借助 [grub2-filemanager](https://github.com/a1ive/grub2-filemanager) 来启动存储在内置固态硬盘中的 .iso 文件。
- 为你准备了许多图标，[icons](https://github.com/M-L-P/icons)。
-----------------------------------------------------------------------------------------------------------------------------------

## 💻️预览👀
按下键盘的 `F10` 或 `\` 可以截屏。<br/>
截图已折叠。
<details>
<summary>🖱️点击展开查看🖱️</summary>
<img src="https://gh.sixyin.com/https://raw.githubusercontent.com/M-L-P/.github/main/screenshots/Yours/B.big.png">
<img src="https://gh.sixyin.com/https://raw.githubusercontent.com/M-L-P/.github/main/screenshots/Yours/B.small.png">
<img src="https://gh.sixyin.com/https://raw.githubusercontent.com/M-L-P/.github/main/screenshots/Yours/M.big.png">
<img src="https://gh.sixyin.com/https://raw.githubusercontent.com/M-L-P/.github/main/screenshots/Yours/M.small.png">
<img src="https://gh.sixyin.com/https://raw.githubusercontent.com/M-L-P/.github/main/screenshots/Yours/1080p.B.big.png">
<img src="https://gh.sixyin.com/https://raw.githubusercontent.com/M-L-P/.github/main/screenshots/Yours/1080p.B.small.png">
<img src="https://gh.sixyin.com/https://raw.githubusercontent.com/M-L-P/.github/main/screenshots/Yours/1080p.M.big.png">
<img src="https://gh.sixyin.com/https://raw.githubusercontent.com/M-L-P/.github/main/screenshots/Yours/1080p.M.small.png">

</details>


## 🧭指南⬇️

### 下载点
<details>
<summary>🖱️点击展开查看🖱️</summary>

#### 若是 UEFI Firmware
如果你的设备满足条件，
- 支持 64位的 UEFI；
- GPU/vBIOS 支持 UEFI；

你应该使用 [Yours-UEFI](https://github.com/M-L-P/Yours-UEFI)。

#### 若是 Legacy BIOS
除非你的设备满足以下情况中的一种，
- 不支持 64位的 UEFI，
- - 支持 32位的 UEFI；
- - 仅支持 Legacy BIOS ，不支持 UEFI；
- GPU/vBIOS 不支持 UEFI；(如下图)

![image](https://user-images.githubusercontent.com/69227436/213923710-120c5a02-30ea-4005-b2fe-c8e9adc7b6d7.png)

你应该使用 [Yours-LegacyBIOS](https://github.com/M-L-P/Yours-LegacyBIOS)。

#### 若是 Hyper-V
从 [Releases](https://github.com/M-L-P/Yours/releases)下载 .vhdx。
</details>

### 编辑你的横幅

<details>
<summary>🖱️点击展开查看🖱️</summary>

- 打开 `BannerEditor.pptx` ，
- - 1K 屏幕，用 Microsoft PowerPoint 2021+ 打开 `EFI\Yours\Settings\display\1K\BannerEditor.pptx` ；
- - 2K 屏幕，用 Microsoft PowerPoint 2021+ 打开 `EFI\Yours\Settings\display\2K\BannerEditor.pptx` ；
- - 3K 屏幕，用 Microsoft PowerPoint 2021+ 打开 `EFI\Yours\Settings\display\3K\BannerEditor.pptx` ；
- - 4K 屏幕，用 Microsoft PowerPoint 2021+ 打开 `EFI\Yours\Settings\display\4K\BannerEditor.pptx` ；
- 编辑并且自定义你的 头像、设备名称 和 姓名或昵称；
- 另存为 PNG；
- 设置显示新生成的横幅，
- - 1K 屏幕，编辑 `EFI\Yours\Settings\display\1K\resolution-1K.conf` ；
- - 2K 屏幕，编辑 `EFI\Yours\Settings\display\2K\resolution-2K.conf` ；
- - 3K 屏幕，编辑 `EFI\Yours\Settings\display\3K\resolution-3K.conf` ；
- - 4K 屏幕，编辑 `EFI\Yours\Settings\display\4K\resolution-4K.conf` ；

<img src="https://gh.sixyin.com/https://raw.githubusercontent.com/M-L-P/.github/main/screenshots/Yours/Chinese_Simplified/sample.PNG"><br/>
<img src="https://gh.sixyin.com/https://raw.githubusercontent.com/M-L-P/.github/main/screenshots/Yours/Chinese_Simplified/template.PNG">
</details>

## 📝FAQ❓️
常见问题

### 调整图标尺寸
<details>
<summary>🖱️点击展开查看🖱️</summary>

- 打开文件，根据下方表格中的信息进行调整，
- - `EFI\Yours\refind.conf` ;

图标尺寸|令牌|条件|例子
--|--|--|--
原始尺寸|`small_icon_size 48` `big_icon_size 128`|384 ≤ 垂直像素数 < 768|SVGA(800×600),720P/WXGA(1280×720) 等
二级尺寸|`small_icon_size 96` `big_icon_size 256`|768 ≤ 垂直像素数 < 960|XGA(1024×768),WXGA+(1366×768),WSXGA(1440×900) 等
三级尺寸|`small_icon_size 144` `big_icon_size 384`|960 ≤ 垂直像素数 < 1536|WSXGA+(1680×1050),1080P/WSUVGA+/FHD(1920×1080),2K/1440P/QHD/WQHD(2560×1440) 等
四级尺寸|`small_icon_size 192` `big_icon_size 512`|1536 ≤ 垂直像素数 ＜ 1728|WQXGA(2560×1600) 等
五级尺寸|`small_icon_size 240` `big_icon_size 640`|1728 ≤ 垂直像素数 ＜ 1920|QWXGA+(2880×1880) 等
六级尺寸|`small_icon_size 288` `big_icon_size 768`|1920 ≤ 垂直像素数 ＜ 2880|4K/2160P/UHD(3840×2160),WQUXGA(3840×2400) 等
七级尺寸|`small_icon_size 336` `big_icon_size 896`|垂直像素数 ≥ 2880|WQUSXGA(3840×2880) 等

</details>

### Windows 的图标
<details>
<summary>🖱️点击展开查看🖱️</summary>

无论你使用哪个版本，<br/>
你应该设置它的图标<br/>
从 `EFI\Yours\Settings\icon\Windows` 中复制到 `EFI\Yours\Settings\icon\showing`，<br/>
并且重命名为 `os_win8.png`.<br/>
因为 rEFInd 把 `os_win8.png` 当作 `Windows Boot Manager` 的默认图标。<br/>
</details>

### 黑果 的图标
为了让图形界面衔接得更加紧密，中途没有代码界面，同时支持安全启动<br/>
<details>
<summary>🖱️点击展开查看🖱️</summary>

文件名|所在目录|文件原理|文件功能
-|-|-|-
`GRUB_PreLoader_CLOVER.efi`|`EFI\Yours\efi\Hackintosh`|链接到 `EFI\CLOVER\CLOVERX64.efi`|预启动 CloverBootloader
`GRUB_PreLoader_CLOVER.png`|`EFI\Yours\efi\Hackintosh`|同名显示图标|用于显示 Clover 的启动图标
`GRUB_PreLoader_OC.efi`|`EFI\Yours\efi\Hackintosh`|链接到 `EFI\OC\OpenCore.efi`|预启动 OpenCore
`GRUB_PreLoader_OC.png`|`EFI\Yours\efi\Hackintosh`|同名显示图标|用于显示 OC 的启动图标

#### 若是 OpenCore
- 你应该编辑 `config.plist` 设置 `LauncherOption=System` ；

#### 若不用黑果
- 你可以选定 Clover 或 OC 的启动图标，按下【Delete】，隐藏对应的入口。
</details>

### Linux 发行版的图标
为你准备了许多图标，[icons](https://github.com/M-L-P/icons/tree/main/PNGs/Linux)。

<details>
<summary>🖱️点击展开查看🖱️</summary>

- 从 [这里](https://github.com/M-L-P/icons/tree/main/PNGs/Linux) 寻找并下载你需要的图标；
- 重命名 PNG 文件，
- - `os_${NAME}.png` 是 `ESP: \EFI\${NAME}\grubx64.efi` 的图标；
- 复制到 `ESP: \EFI\Yours\Settings\icon\showing`；
</details>

## ⭐收藏🌟
如果你喜欢并且期待未来的更新，你可以点亮星星。💫

## 🎉来源🎊
- *Roderick W. Smith* 的 [rEFInd Boot Manager](http://www.rodsbooks.com/refind/)；
- [a1ive](https://github.com/a1ive) 的 [grub2-filemanager](https://github.com/a1ive/grub2-filemanager)；
- 更多现代化的图标；
- - 一些图标来自 [Iconfont](https://www.iconfont.cn/)，
- - 一些图标来自 [Iconfinder](https://www.iconfinder.com/)，
- - 一些图标来自 macOS and [OC](https://github.com/acidanthera/OpenCorePkg)，
- - 其他未知出处；
- 六音的 github 加速器，用于显示图片，https://gh.sixyin.com/ ；

## [🧁请我吃块巧克力🍫](https://github.com/M-L-P/.github/blob/main/profile/chocolate/README.md)