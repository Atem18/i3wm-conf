# Things to install
To make it work, we need to install some tools.

## The Window Manager
Well, everything is setup inside the i3wm, so it's required.

```bash
    sudo apt-get install i3wm
```

## The Background tool
Used to change the background each minute, if you don't want this, remove it on `config` file.
```bash
    sudo apt-get install feh
```

## Monitor tool
This tool can be used to change the monitor\\display.
It's just a wrapper for `xrandr`, may help you to get used with this.
```bash
    sudo apt-get install arandr
```

## Install font awesome
This is used on the **i3bar**, to add custom icons, if you don't want custom icon on the bar remove it from the `config` file.
```bash
    mkdir ~/.fonts
    wget https://github.com/FortAwesome/Font-Awesome/raw/master/fonts/fontawesome-webfont.ttf
    mv fontawesome-webfont.ttf ~/.fonts/
```
## Install Yosemite SanFrancisco Font
Look on the link on the end of this file to know how to use it, cuz it's a manual task.
```bash
    wget https://github.com/supermarin/YosemiteSanFranciscoFont/archive/master.zip
    unzip YosemiteSanFranciscoFont-master.zip
    mv YosemiteSanFranciscoFont-master/*.ttf ~/.fonts/
    rm -rd YosemiteSanFranciscoFont-master
```
