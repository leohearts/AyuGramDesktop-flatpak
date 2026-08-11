AyuGram Flatpak Repository (Unofficial)

This repository hosts Flatpak packages for AyuGram Desktop.

## Installation Instructions

```fish
flatpak remote-add --user --no-gpg-verify ayugram https://leohearts.github.io/AyuGramDesktop-flatpak/
flatpak remote-ls ayugram
flatpak install ayugram com.ayugram.desktop
```

## Update

To update to the latest version:

```fish
flatpak update com.ayugram.desktop
```

## Uninstall

To remove AyuGram:

```fish
flatpak uninstall com.ayugram.desktop
```

To remove the repository:

```fish
flatpak remote-delete ayugram
```

Upstream: 0FL01/AyuGramDesktop-flatpak
Repository: leohearts/AyuGramDesktop-flatpak 
