# brave-bin package for Void Linux

<b>HOW TO INSTALL</b></br></br>
0-Download the xbps<br>
1-xbps-rindex -a brave-bin-1.41.96_1.x86_64.xbps<br>
2-sudo xbps-install -R $PWD brave-bin-1.41.96<br>


This package provides Brave Browser, the browser based on Chromium with privacy in mind and a built in ad blocker. This package merely takes the .deb release version from the authors, extracts and installs the files as is. Plus, ensures the dependencies are there. **Note:** This IS a building binaries from source as a proper package should. Hence the `-bin` shuffix.

**Help from:**

- [reback00 -thanks for create de template and the instructions how to build the xbps](https://notabug.org/reback00/void-goodies/src/master/srcpkgs/brave-bin)
- [Brave PR for Void Linux](https://github.com/void-linux/void-packages/pull/5511/files)
- [iridium-deb PKGBUILD (AUR)](https://aur.archlinux.org/cgit/aur.git/tree/PKGBUILD?h=iridium-deb)
