# AuraLink Releases

This repository is the public binary distribution mirror for AuraLink. It
contains signed Android packages and release notes only; application source code
is not published here.

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
