# Dvorak alternative international no dead keys

![Image of dvorak alternative international no dead keys layout](https://raw.githubusercontent.com/soywod/dvorak-alt-intl/master/img/dvorak-alt-intl.png)

This keyboard layout is included by default in unix distributions like `Debian`. This repo aims to export it to `Mac OS` and `Windows`.

I've only set up dead keys and special characters I learned from my native languages, like `~ ^ ç é` but a lot are missing, like `ˇ ˙ ˝`... Your help would be appreciated ;)

## How it works

- `/src` contains source layout files
- `/dist` contains all binairies to install the layout

Each folder contains a `/mac` folder for `Mac OS` systems and a `win` folder for `Windows`.

Update : no binaries are required anymore for MacOS. To install the layout, just put the `.keylayout` file from `src` into your `/Library/Keyboard Layouts/` and reboot.

## How to edit layout from sources

Just open source layout files with the correct tool :

- Mac OS : [Ukelele](http://scripts.sil.org/cms/scripts/page.php?site_id=nrsi&id=ukelele)
- Windows : [Keyboard Layout Creator](https://msdn.microsoft.com/en-us/globalization/keyboardlayouts.aspx) v1.4
