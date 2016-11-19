## Arch Linux PKGBUILD for the Label Printer Brother QL-710W

### Installing the drivers on Arch Linux

Just follow these steps:

    git clone https://github.com/pklaus/brother-ql710w.git
    cd brother-ql710w/brother-ql710w
    makepkg -s
    pacman -U *.xz

### Acknowledgement

The package is largely based on [brother-ql700][] (a combination
of the previous [brother-ql700-lpr][] and [brother-ql700-cupswrapper][]).


[brother-ql700]: https://aur.archlinux.org/packages/brother-ql700
[brother-ql700-lpr]: https://aur.archlinux.org/packages/brother-ql700-lpr
[brother-ql700-cupswrapper]: https://aur.archlinux.org/packages/brother-ql700-cupswrapper/

