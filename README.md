## Arch Linux PKGBUILD for the Label Printer Brother QL-710W.md

### Installing the drivers on Arch Linux

Just follow these steps:

    git clone https://github.com/pklaus/brother-ql710w.git
    cd brother-ql710w/brother-ql710w-lpr
    makepkg -s
    pacman -U *.xz
    cd ../brother-ql710w-cupswrapper
    makepkg -s
    pacman -U *.xz

### Acknowledgement

The packages here are largely based on
[brother-ql700-lpr][] and [brother-ql700-cupswrapper][].


[brother-ql700-lpr]: https://aur.archlinux.org/packages/brother-ql700-lpr
[brother-ql700-cupswrapper]: https://aur.archlinux.org/packages/brother-ql700-cupswrapper/

