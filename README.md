# Stable Diffusion WebUI Tradition Chinese 0411
## 解釋說明

此項目為[Stable Diffusion Web UI](https://github.com/AUTOMATIC1111/stable-diffusion-webui)簡體中文擴展

當前版本為0408，即基於官方webui和自用插件的本地化模板，於4月8日之前的最新版本進行的漢化。

本人精力有限不可能每個功能都體驗過，然後根據具體功能來翻譯，所以有翻譯得不對或者更好的翻譯請聯繫我。

翻譯結果來自chatGPT、有道翻譯和網絡檢索。

## 包含以下擴展翻譯

[ControlNet](https://github.com/Mikubill/sd-webui-controlnet)
版本：241c05f8 (Thu Mar 23 15:18:35 2023)

[openpose-editor](https://github.com/fkunn1326/openpose-editor)
版本：a63fefc3 (Thu Mar 30 08:11:41 2023)

[multidiffusion-upscaler](https://github.com/pkuliyi2015/multidiffusion-upscaler-for-automatic1111)
版本：70ca3c77 (Wed Apr 5 10:57:07 2023)

[dynamic-prompts](https://github.com/adieyal/sd-dynamic-prompts)
版本：707fa9a1 (Thu Apr 6 18:31:57 2023)

[artists-to-study](https://github.com/camenduru/stable-diffusion-webui-artists-to-study)
版本：970d388e (Tue Feb 28 20:52:57 2023)

[dataset-tag-editor](https://github.com/toshiaki1729/stable-diffusion-webui-dataset-tag-editor)
版本：c1c78f59 (Sun Apr 2 11:15:32 2023)

[wd14-tagger](https://github.com/toriato/stable-diffusion-webui-wd14-tagger)
版本：3ba3a735 (Sat Mar 25 20:32:37 2023)

[ultimate-upscale](https://github.com/Coyote-A/ultimate-upscale-for-automatic1111)
版本：0a3d03a4 (Tue Feb 7 06:07:23 2023)

## 安裝說明

### 方法1：通過WebUI拓展進行安裝

1.打開stable diffusion webui，進入"Extensions"選項卡

2.點擊"Install from URL"，注意"URL for extension's git repository"下方的輸入框

3.粘貼或輸入本Git倉庫地址`https://github.com/VinsonLaro/stable-diffusion-webui-chinese`

4.點擊下方的黃色按鈕"Install"即可完成安裝，然後重啟WebUI(點擊"Install from URL"左方的"Installed"，然後點擊黃色按鈕"Apply and restart UI"網頁下方的"Reload UI"完成重啟)

5.點擊"Settings"，左側點擊"User interface"界面，在界面裡最下方的"Localization (requires restart)"，選擇"Chinese-All"或者"Chinese-English"

6.點擊界面最上方的黃色按鈕"Apply settings"，再點擊右側的"Reload UI"即可完成漢化

### 方法2：直接複製翻譯好的本地化模板

1.在任意目錄下使用`git clone https://github.com/VinsonLaro/stable-diffusion-webui-chinese`

2.進入下載好的文件夾,把"localizations"文件夾內的"Chinese-All.json"和"Chinese-English.json"複製到"stable-diffusion-webui\localizations"目錄下

3.點擊"Settings"，左側點擊"User interface"界面，在界面裡最下方的"Localization (requires restart)"，選擇"Chinese-All"或者"Chinese-English"

4.點擊界面最上方的黃色按鈕"Apply settings"，再點擊右側的"Reload UI"即可完成漢化
