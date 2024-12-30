# AigcPanel

![](./screenshots/cn/home.png)

## Introduction

`AigcPanel` is a user-friendly all-in-one AI digital human system that's easy enough for beginners to use.
It supports video synthesis, voice synthesis, voice cloning, and simplifies local model management with one-click model import and usage.

> It is prohibited to use this product for illegal activities. Please comply with the laws and regulations of the People's Republic of China when using this software.

## Features

- Supports digital human video synthesis, including video visuals and lip-sync matching
- Supports text-to-speech and voice cloning with multiple adjustable voice parameters
- Supports multiple model imports, one-click startup, model settings, and model log viewing
- Supports internationalization with Japanese, Simplified Chinese, and English
- Supports various one-click startup model packages: `MuseTalk`, `cosyvoice`

## Demo

Check out the video files in the [demo](demo/) folder.

## Feature Preview

### Video Synthesis

![](./screenshots/cn/video-gen.png)

### Voice Cloning

![](./screenshots/cn/sound-clone.png)

### Text-to-Speech

![](./screenshots/cn/sound-tts.png)

### Model Management

![](./screenshots/cn/server.png)

### Add Model

![](./screenshots/cn/server-add.png)

### Model Logs

![](./screenshots/cn/server-log.png)

### About

![](./screenshots/cn/setting.png)

## Installation and Usage

### Windows

- Visit [https://aigcpanel.com](https://aigcpanel.com) to download the Windows installer package and install with one click

After installation, open the software and download the model startup packages to begin using.

## Tech Stack

- `electron`
- `vue3`
- `typescript`

## Local Development

> Only tested with Node 20

```shell
# Install dependencies
npm install
# Run in debug mode
npm run dev
# Build
npm run build
```

## Join Discussion Groups

<table width="100%">
    <thead>
        <tr>
            <th width="50%">WeChat Group</th>
            <th>QQ Group</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>
                <img style="width:100%;"
                     src="https://aigcpanel.com/app_manager/image/wechat" />
            </td>
            <td>
                <img style="width:100%;" 
                     src="https://aigcpanel.com/app_manager/image/qq" />
            </td>
        </tr>
    </tbody>
</table>

## Acknowledgments

This program uses the following open source projects:

- [CosyVoice](https://github.com/FunAudioLLM/CosyVoice)
- [MuseTalk](https://github.com/TMElyralab/MuseTalk)

## License

AGPL-3.0