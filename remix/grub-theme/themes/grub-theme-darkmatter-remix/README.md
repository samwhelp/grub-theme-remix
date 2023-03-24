
# grub-theme-monterey-remix


## source

* VandalByte / [darkmatter-grub-theme](https://gitlab.com/VandalByte/darkmatter-grub-theme)
* [Dark Matter GRUB Theme](https://www.gnome-look.org/p/1603282)


## background source

* [iron man](https://www.reddit.com/r/wallpaper/comments/olengo/3840x2160_iron_man/)
* [https://i.redd.it/1ai3l6g54kb71.jpg](https://i.redd.it/1ai3l6g54kb71.jpg)


## config

edit `/etc/default/grub`

```
GRUB_BACKGROUND='/boot/grub/themes/grub-theme-darkmatter-remix/background.jpg'
GRUB_THEME="/boot/grub/themes/grub-theme-darkmatter-remix/theme.txt"
```

then run

``` sh
sudo update-grub
```

or run

``` sh
sudo grub-mkconfig -o /boot/grub/grub.cfg
```

