# Curie

A slightly upscaled version of [scientifica](https://github.com/nerdypepper/scientifica).

## Screenshots

![curiebolditalic.png](https://user-images.githubusercontent.com/23706925/40254621-32fa9640-5ab2-11e8-8ad0-d5a5d78badc8.png)
![curieabc.png](https://user-images.githubusercontent.com/23706925/39848353-7c4ef32a-53d4-11e8-8d7e-04f6a950c856.png)

![curiecode.png](https://user-images.githubusercontent.com/23706925/39848352-7c3c59ea-53d4-11e8-825b-1b373ef2f304.png)

## Installation

### Linux

Enable bitmap fonts
```shell
sudo cd /etc/fonts/conf.d/
sudo rm /etc/fonts/conf.d/10* && sudo rm -rf ./70-no-bitmaps.conf && sudo ln -s ../conf.avail/70-yes-bitmaps.conf
sudo dpkg-reconfigure fontconfig
```

Download Curie
```shell
 cd ~
 git clone https://github.com/nerdypepper/curie
 ```
 Symlink it to your fonts folder
 ```shell
ln -fs ~/curie/regular/curieMedium-12.bdf ~/.local/share/fonts/curieMedium-12.bdf
ln -fs ~/curie/bold/curieBold-12.bdf ~/.local/share/fonts/curieBold-12.bdf
ln -fs ~/curie/italic/curieItalic-12.bdf ~/.local/share/fonts/curieItalic-12.bdf
```

### Arch Linux

Curie is available in the AUR as [bdf-curie](https://aur.archlinux.org/packages/bdf-curie)
