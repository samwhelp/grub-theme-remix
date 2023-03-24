
# grub-theme-monterey-remix


## source

* sandesh236 / [monterey-grub-theme](https://github.com/sandesh236/monterey-grub-theme)


## background source

* [iron man](https://www.reddit.com/r/wallpaper/comments/olengo/3840x2160_iron_man/)
* [https://i.redd.it/1ai3l6g54kb71.jpg](https://i.redd.it/1ai3l6g54kb71.jpg)


## config

edit `/etc/default/grub`

```
GRUB_BACKGROUND='/boot/grub/themes/grub-theme-monterey-remix/background.jpg'
GRUB_THEME="/boot/grub/themes/grub-theme-monterey-remix/theme.txt"
```

then run

``` sh
sudo update-grub
```

or run

``` sh
sudo grub-mkconfig -o /boot/grub/grub.cfg
```



