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
- - ✏️自定義 ***使用者頭像*** ；
- - ✏️自定義 ***裝置名稱*** ；
- - ✏️自定義 ***機主姓名*** 。

- 基於 *Roderick W. Smith* 的 [rEFInd Boot Manager](http://www.rodsbooks.com/refind/)，巢狀 [a1ive](https://github.com/a1ive) 的 [grub2-filemanager](https://github.com/a1ive/grub2-filemanager)。
- - 所以你可以藉助 [grub2-filemanager](https://github.com/a1ive/grub2-filemanager) 來啟動儲存在內建固態硬碟中的 .iso 檔案。
- 為你準備了許多圖示，[icons](https://github.com/M-L-P/icons)。
-----------------------------------------------------------------------------------------------------------------------------------

## 💻️預覽👀
按下鍵盤的 `F10` 或 `\` 可以截圖。<br/>
截圖已摺疊。
<details>
<summary>🖱️點選展開檢視🖱️</summary>
<img src="https://raw.githubusercontent.com/M-L-P/.github/main/screenshots/Yours/B.big.png">
<img src="https://raw.githubusercontent.com/M-L-P/.github/main/screenshots/Yours/B.small.png">
<img src="https://raw.githubusercontent.com/M-L-P/.github/main/screenshots/Yours/M.big.png">
<img src="https://raw.githubusercontent.com/M-L-P/.github/main/screenshots/Yours/M.small.png">
<img src="https://raw.githubusercontent.com/M-L-P/.github/main/screenshots/Yours/1080p.B.big.png">
<img src="https://raw.githubusercontent.com/M-L-P/.github/main/screenshots/Yours/1080p.B.small.png">
<img src="https://raw.githubusercontent.com/M-L-P/.github/main/screenshots/Yours/1080p.M.big.png">
<img src="https://raw.githubusercontent.com/M-L-P/.github/main/screenshots/Yours/1080p.M.small.png">

</details>


## 🧭指南⬇️

### 下載點
<details>
<summary>🖱️點選展開檢視🖱️</summary>

#### 若是 UEFI Firmware
如果你的裝置滿足條件，
- 支援 64位的 UEFI；
- GPU/vBIOS 支援 UEFI；

你應該使用 [Yours-UEFI](https://github.com/M-L-P/Yours-UEFI)。

#### 若是 Legacy BIOS
除非你的裝置滿足以下情況中的一種，
- 不支援 64位的 UEFI，
- - 支援 32位的 UEFI；
- - 僅支援 Legacy BIOS ，不支援 UEFI；
- GPU/vBIOS 不支援 UEFI；(如下圖)

![image](https://user-images.githubusercontent.com/69227436/213923710-120c5a02-30ea-4005-b2fe-c8e9adc7b6d7.png)

你應該使用 [Yours-LegacyBIOS](https://github.com/M-L-P/Yours-LegacyBIOS)。

#### 若是 Hyper-V
從 [Releases](https://github.com/M-L-P/Yours/releases)下載 .vhdx。
</details>

### 編輯你的橫幅

<details>
<summary>🖱️點選展開檢視🖱️</summary>

- 1K 螢幕，用 Microsoft PowerPoint 2021+ 開啟 `EFI\Yours\Settings\display\1K\BannerEditor.pptx` ；
- 2K 螢幕，用 Microsoft PowerPoint 2021+ 開啟 `EFI\Yours\Settings\display\2K\BannerEditor.pptx` ；
- 編輯並且自定義你的 頭像、裝置名稱 和 姓名或暱稱；
- 另存為 PNG；
- 編輯 `EFI\Yours\Settings\display\display.conf` 用以設定顯示新生成的橫幅；

<img src="https://raw.githubusercontent.com/M-L-P/.github/main/screenshots/Yours/Chinese_Simplified/sample.PNG"><br/>
<img src="https://raw.githubusercontent.com/M-L-P/.github/main/screenshots/Yours/Chinese_Simplified/template.PNG">
</details>

## 📝FAQ❓️
常見問題

### 調整圖示尺寸
<details>
<summary>🖱️點選展開檢視🖱️</summary>

- 編輯 `EFI\Yours\Settings\display\display.conf`

圖示尺寸|令牌|螢幕解析度|例子
--|--|--|--
原始尺寸|`small_icon_size 48` `big_icon_size 128`|解析度 < `1024x768`|`800x600` 等
二級尺寸|`small_icon_size 96` `big_icon_size 256`|`1024x768` ≤ 解析度 < `1920x1080`|`1024x768`、`1366x768`、`1440x900` 等
三級尺寸|`small_icon_size 144` `big_icon_size 384`|解析度 ≥ `1920x1080`|`1080P`、`2K`、`4K` 等

</details>

### Windows 的圖示
<details>
<summary>🖱️點選展開檢視🖱️</summary>

無論你使用哪個版本，<br/>
你應該設定它的圖示<br/>
從 `EFI\Yours\Settings\icon\Windows` 中複製到 `EFI\Yours\Settings\icon\showing`，<br/>
並且重新命名為 `os_win8.png`.<br/>
因為 rEFInd 把 `os_win8.png` 當作 `Windows Boot Manager` 的預設圖示。<br/>
</details>

### 黑果 的圖示
為了讓圖形介面銜接得更加緊密，中途沒有程式碼介面，同時支援安全啟動<br/>
<details>
<summary>🖱️點選展開檢視🖱️</summary>

檔名|所在目錄|檔案原理|檔案功能
-|-|-|-
`GRUB_PreLoader_CLOVER.efi`|`EFI\Yours\efi\Hackintosh`|連結到 `EFI\CLOVER\CLOVERX64.efi`|預啟動 CloverBootloader
`GRUB_PreLoader_CLOVER.png`|`EFI\Yours\efi\Hackintosh`|同名顯示圖示|用於顯示 Clover 的啟動圖示
`GRUB_PreLoader_OC.efi`|`EFI\Yours\efi\Hackintosh`|連結到 `EFI\OC\OpenCore.efi`|預啟動 OpenCore
`GRUB_PreLoader_OC.png`|`EFI\Yours\efi\Hackintosh`|同名顯示圖示|用於顯示 OC 的啟動圖示

#### 若是 OpenCore
- 你應該編輯 `config.plist` 設定 `LauncherOption=System` ；

#### 若不用黑果
- 你可以選定 Clover 或 OC 的啟動圖示，按下【Delete】，隱藏對應的入口。
</details>

### Linux 發行版的圖示
為你準備了許多圖示，[icons](https://github.com/M-L-P/icons/tree/main/PNGs/Linux)。

<details>
<summary>🖱️點選展開檢視🖱️</summary>

- 從 [這裡](https://github.com/M-L-P/icons/tree/main/PNGs/Linux) 尋找並下載你需要的圖示；
- 重新命名 PNG 檔案，
- - `os_${NAME}.png` 是 `ESP: \EFI\${NAME}\grubx64.efi` 的圖示；
- 複製到 `ESP: \EFI\Yours\Settings\icon\showing`；
</details>

## ⭐收藏🌟
如果你喜歡並且期待未來的更新，你可以點亮星星。💫

## 🎉來源🎊
- *Roderick W. Smith* 的 [rEFInd Boot Manager](http://www.rodsbooks.com/refind/)；
- [a1ive](https://github.com/a1ive) 的 [grub2-filemanager](https://github.com/a1ive/grub2-filemanager)；
- 更多現代化的圖示；
- - 一些圖示來自 [Iconfont](https://www.iconfont.cn/)，
- - 一些圖示來自 [Iconfinder](https://www.iconfinder.com/)，
- - 一些圖示來自 macOS and [OC](https://github.com/acidanthera/OpenCorePkg)，
- - 其他未知出處；

## [🧁請我吃塊巧克力🍫](https://github.com/M-L-P/.github/blob/main/profile/chocolate/README.md)
