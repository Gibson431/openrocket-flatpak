# OpenRocket Flatpak

A flatpak-packaged version of openrocket. All this does is pull the JAR from the official release and package it as a flatpak.

## Installation

```sh
flatpak-builder --user --install --force-clean --install-deps-from=flathub build-dir info.openrocket.OpenRocket.yml
```
