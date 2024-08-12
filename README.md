# LibreTrack

Project Page: [https://github.com/proninyaroslav/libretrack](https://github.com/proninyaroslav/libretrack)

## Install

Note: for support system tray in GNOME, please install [gnome-shell-extension-appindicator](https://extensions.gnome.org/extension/615/appindicator-support/) or similar extension.

```
flatpak install flathub ru.proninyaroslav.libretrack
```

## Build

Before building, make sure that the `flatpak` and `flatpak-builder` dependencies are installed on the system.

Then run the following commands:

 ```
 flatpak install org.freedesktop.Sdk
 ```

 ```
 cd flatpak
 ```

 ```
 flatpak-builder --user --install builddir ru.proninyaroslav.libretrack.yaml --force-clean
 ```
