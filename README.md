# AuraLink Releases

AuraLink 是一款面向 Android 电视、手机、平板、电视盒子和投影设备的音乐播放器，
专注于在大屏与移动设备上统一管理和播放个人音乐库。

它可以读取设备本地文件夹，并连接 WebDAV、Jellyfin、Emby 和 Navidrome
音乐库。界面同时适配遥控器、触控和不同尺寸的屏幕，在不同设备上提供一致的
音乐库浏览、搜索和播放体验。

## 主要特点

- 支持 Android 9 及以上的电视、手机、平板、电视盒子和投影设备
- 面向遥控器与触屏分别优化的自适应界面
- 支持本地文件夹、WebDAV、Jellyfin、Emby 和 Navidrome 音乐源
- 将多个音乐源汇集到统一的音乐库中进行浏览和搜索
- 支持无损、高解析及常见压缩音频格式
- 提供歌词、专辑封面、播放队列和音乐库管理功能
- 可连接电视音响、功放、解码器或耳机进行播放

本仓库是 AuraLink 的公开二进制发布镜像，仅包含签名后的 Android 安装包和版本
说明，不包含应用源代码。

## Download

Open the [latest release](https://github.com/gooff327/auralink-releases/releases/latest)
and choose the package for your device:

| Package | Device |
| --- | --- |
| `arm64-v8a` | Most current TVs, phones, tablets, TV boxes, and projectors |
| `armeabi-v7a` | Older 32-bit Android devices |

AuraLink requires Android 9 or later. The primary download mirror for users in
mainland China is [player.auralink.space](https://player.auralink.space/).

## Verify a download

Every release includes a `SHA256SUMS.txt` file. Verify an APK before installing:

```sh
shasum -a 256 -c auralink-*-SHA256SUMS.txt
```

Android also verifies that an update is signed by the same key as the installed
application.

## Updates

Release announcements are posted to the
[AuraLink Telegram channel](https://t.me/auralink_notify).

This repository is an output of the private AuraLink build and release process.
Issues and pull requests are not used for source contributions.
