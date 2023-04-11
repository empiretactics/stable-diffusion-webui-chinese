# Stable Diffusion WebUI Tradition Chinese 0411
## 解释说明

此项目为[Stable Diffusion Web UI](https://github.com/AUTOMATIC1111/stable-diffusion-webui)简体中文扩展

当前版本为0408，即基于官方webui和自用插件的本地化模板，于4月8日之前的最新版本进行的汉化。

本人精力有限不可能每个功能都体验过，然后根据具体功能来翻译，所以有翻译得不对或者更好的翻译请联系我。

翻译结果来自chatGPT、有道翻译和网络检索。

## 包含以下扩展翻译

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

## 安装说明

### 方法1：通过WebUI拓展进行安装

1.打开stable diffusion webui，进入"Extensions"选项卡

2.点击"Install from URL"，注意"URL for extension's git repository"下方的输入框

3.粘贴或输入本Git仓库地址`https://github.com/VinsonLaro/stable-diffusion-webui-chinese`

4.点击下方的黄色按钮"Install"即可完成安装，然后重启WebUI(点击"Install from URL"左方的"Installed"，然后点击黄色按钮"Apply and restart UI"网页下方的"Reload UI"完成重启)

5.點擊"Settings"，左侧点击"User interface"界面，在界面里最下方的"Localization (requires restart)"，选择"Chinese-All"或者"Chinese-English"

6.點擊界面最上方的黃色按鈕"Apply settings"，再點擊右側的"Reload UI"即可完成漢化

### 方法2：直接複製翻譯好的本地化模板

1.在任意目錄下使用`git clone https://github.com/VinsonLaro/stable-diffusion-webui-chinese`

2.進入下載好的文件夾,把"localizations"文件夹内的"Chinese-All.json"和"Chinese-English.json"复制到"stable-diffusion-webui\localizations"目录下

3.点击"Settings"，左侧点击"User interface"界面，在界面里最下方的"Localization (requires restart)"，选择"Chinese-All"或者"Chinese-English"

4.点击界面最上方的黄色按钮"Apply settings"，再点击右侧的"Reload UI"即可完成汉化
