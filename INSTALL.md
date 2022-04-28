# Installation guide
## Prerequisite
- i3-gap
- picom
- rofi

## Git submodule
The vim color schema and the wallpapers are git submodule.
```
git submodule update --init --recursive
```

## vim
```
```

## Picom
On ubuntu there isn't a package so you need to build it from the [repo](https://github.com/yshui/picom).
The configuration is set in i3 and located at 
```
/dot/picom/picom.conf
```


## Font
On ubuntu `cp` all font to
```
sudo cp font/IBM_nerd/* /usr/share/fonts/truetype/ttf
```
Clear and regenerate your font cache
```
fc-cache -f -v
```
Validate the font is installed
```
fc-list : family style | grep IBM
```
