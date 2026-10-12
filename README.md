# Flatpak for Linphone

## Install

```
flatpak install flathub org.freedesktop.Sdk//26.08
flatpak-builder --user --install --default-branch stable --force-clean --sandbox build-dir org.linphone.desktop.yaml
```
