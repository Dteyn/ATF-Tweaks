# ATF Tweaks

Adds various tweaks to After the Fall VR.

>[!NOTE]
> Compatible with **PCVR (Steam and Oculus Rift)** versions of After the Fall. Other platforms are not supported.

**Current version:** 1.0.0

# List of Tweaks

## Gameplay menu

### - Show/Hide Bullet Tracers

By default, the game will show a tracer (highlighted line) for each bullet. Toggling this off will hide bullet tracers.

### - Show/Hide Muzzle Flashes

By default, guns have a muzzle flash when firing. Toggling this off will hide the muzzle flashes.

More tweaks may be added in future releases.

## Requirements

[BepInEx](https://github.com/BepInEx/BepInEx) version [**6.0.0-pre.2**](https://github.com/BepInEx/BepInEx/releases/tag/v6.0.0-pre.2) or higher is required. ATF Tweaks will not work with earlier versions of BepInEx.

For ease of use, **the full release zip file already includes BepInEx** so it's not required to download separately.

A dll-only .zip is also available in the releases section.

# Installation

>[!WARNING]
> **Use at your own risk!**

Generally speaking, After the Fall has not been hostile towards players using BepInEx plugins such as this, so it's commonly accepted to be safe practice as of this plugin's release.

## Disclaimer

While I've made every effort to test this plugin and ensure it's free from bugs and issues, I provide no warranty or guarantees against any issues you may encounter. Use at your own risk.

## Step 1

**Download** the [full release zip file](https://github.com/Dteyn/ATF_Tweaks/releases/download/v1.0.0/ATF_Tweaks-v1.0.0.zip) and **extract** into your After the Fall game folder.

The default game folder location varies depending on version:

### Steam:

`C:\Program Files (x86)\Steam\steamapps\common\After the Fall\`

### Oculus Rift:

`C:\Program Files\Oculus\Software\vertigo-games-snowbreed\`

## Step 2

Start the game (first launch will take longer) and you will have new options in the game menus as per the screenshots below.

>[!NOTE]
> ***The first time launching after install will take a couple minutes as BepInEx creates needed files.*** After the first launch, the game will launch normally.

# Configuration

You can enable or disable tweaks from the in-game menu.

Currently, there are two tweaks available in the Gameplay section:

![Screenshot showing Gameplay menu tweaks](https://github.com/Dteyn/ATF-Tweaks/blob/main/assets/images/gameplay-tweaks.jpg)

- **Show Bullet Tracers:** By default, the game will show a tracer (highlighted line) for each bullet. Toggling this off will hide bullet tracers.

- **Show Muzzle Flash:** By default, guns have a muzzle flash when firing. Toggling this off will hide the muzzle flashes.

More tweaks may be added in future releases.

## Config File

After the game has run once, a configuration file will be created in the game folder, at: **\BepInEx\config\ATF-Tweaks.cfg**

This file retains the settings for the tweaks configured via the in-game menu. You can also edit the file manually to change settings.

Default config:

```cfg
[Gameplay]

## Show muzzle flash effects.
# Setting type: Boolean
# Default value: true
ShowMuzzleFlash = true

## Show bullet tracers.
# Setting type: Boolean
# Default value: true
ShowTracers = true
```

### BepInEx 6.0.0-pre.1 support

If you really need a version that works with BepInEx version 6.0.0-pre.1 (ie. for compatibility with other plugins which require that version), open an Issue on this repo and I can create one.

# Support the Developer

If you want to show some support, I have Ko-Fi page where you can buy me a coffee:

https://ko-fi.com/Dteyn
