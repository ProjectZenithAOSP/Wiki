# Flags And Configs #

To Add Maintainer Name In Settings
- usage: Add in DT 'overlay/packages/apps/Settings/res/values/zenith_strings.xml'

```bash
<string name="zenith_maintainer">yourname</string>
```

To disable Trasparent/Blured recents in pixel launcher

```bash
TARGET_USES_BLUR_RECENT := false
```

For Face Unlock

```bash
TARGET_FACE_UNLOCK_SUPPORTED := true
```

For Live Wallpaper

```bash
TARGET_INCLUDE_LIVE_WALLPAPERS := true
```
