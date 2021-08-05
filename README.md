# ubuntu-desktop-file
ubuntu xxx.desktop sample file

## Create an app.desktop file
[sample](./etcher.desktop)

## Edit .desktop file

```plain
[Desktop Entry]
Version=x.y
Name=Your program name
Comment=Your comment
Exec=your execute file or your.sh
Icon=your app icon.png
Terminal=false
Type=Application
Categories=Utility;Application;
```

## Give Authority

Give executable rights to your .desktop file
```console
$ sudo chmod 777 etcher.desktop
```

## Add .desktop file to the Unity Launcher

You can place your `.desktop` file at `/usr/share/applications/` or at `~/.local/share/applications/` 

[reference](https://help.ubuntu.com/community/UnityLaunchersAndDesktopFiles)
