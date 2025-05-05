# Flatpak for Linphone

## Install

```
flatpak install flathub org.freedesktop.Sdk//24.08
flatpak-builder --user --install --default-branch stable --force-clean build-dir --sandbox org.linphone.desktop.yaml
```
