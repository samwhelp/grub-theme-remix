
# grub-theme-deepin-remix


## source

* martyr-deepin / [deepin-grub2-themes](https://github.com/martyr-deepin/deepin-grub2-themes)


## background source

* [iron man](https://www.reddit.com/r/wallpaper/comments/olengo/3840x2160_iron_man/)
* [https://i.redd.it/1ai3l6g54kb71.jpg](https://i.redd.it/1ai3l6g54kb71.jpg)


## config

edit `/etc/default/grub`

```
GRUB_BACKGROUND='/boot/grub/themes/grub-theme-deepin-remix/background.jpg'
GRUB_THEME="/boot/grub/themes/grub-theme-deepin-remix/theme.txt"
```

then run

``` sh
sudo update-grub
```

or run

``` sh
sudo grub-mkconfig -o /boot/grub/grub.cfg
```



