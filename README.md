# YTM-RS

## Build

```sh
flatpak-builder builddir io.github.grapedjuice.ytm-rs.yaml --repo=repo --install-deps-from=flathub --force-clean # Build flatpak app
flatpak build-bundle ./repo ytm-rs.flatpak io.github.grapedjuice.ytm-rs --runtime-repo=https://dl.flathub.org/repo/flathub.flatpakrepo # Build flatpak bundle
```

## Install

```sh
flatpak install ytm-rs.flatpak # You need to build before
```
