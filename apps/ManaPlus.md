---
layout: app

permalink: /ManaPlus/
description: A 2D MMORPG client

icons:
  - ManaPlus/icons/scalable/manaplus.svg

screenshots:
  - ManaPlus/screenshot.png

authors:

links:

desktop:
  Desktop Entry:
    Version: 1.0
    Name: ManaPlus
    Comment: A 2D MMORPG client
    Exec: manaplus
    StartupNotify: false
    Terminal: false
    Type: Application
    Icon: manaplus
    Categories: Game
    Keywords: MMORPG
  AppImageHub:
    X-AppImage-UpdateInformation: zsync|https://gitlab.com/mana-launcher/mplusbuilder/-/jobs/artifacts/master/raw/ManaPlus-x86_64.AppImage.zsync?job=BuildAppImage
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64
---