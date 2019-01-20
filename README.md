# Raoharu Dark Theme for EmulationStation
A [EmulationStation](https://github.com/Aloshi/EmulationStation) theme optimized for Raspberry Pi.

Based on the following themes:
- [Tronkyfan dark optimized](https://github.com/HerbFargus/es-theme-tronkyfran/tree/dark-optimized)
- [Carbon](https://github.com/RetroPie/es-theme-carbon)

## Installation
1. Close EmulationStation.
2. Create folder `/etc/emulationstation/themes` if it does not exist.
3. Run in a terminal:
```
cd /etc/emulationstation/themes
git clone git@github.com:raohmaru/es-theme-raohmaru-dark.git
```

**Windows users note:** In Windows OS the location of the themes folder is at `%HOMEPATH%\.emulationstation\themes`.

### Update
In order to update your installed theme (if you installed with above instructions), open a terminal and run:
```
cd /etc/emulationstation/themes/es-theme-raohmaru-dark
git pull
```

### Customization

#### System View
By default, system view has vertical scroll. If you prefer the classic horizontal scroll, open [theme.xml](https://github.com/raohmaru/es-theme-raohmaru-dark/blob/master/theme.xml)
with a text editor, then uncomment the following line:
```
<!-- <include>./_inc/templates/carousel-horizontal.xml</include> -->
```
and comment the next line:
```
<include>./_inc/templates/carousel-vertical.xml</include>
```

## Compatibility
This theme is designed for a 16:9 aspect ratio. Currently the theme is not fully compatible with a 4:3 aspect ratio. It has been tested with both 1080p (1920x1080) and 720p (1280x720) resolutions. Other 16:9 resolutions will likely work with no issue due to the scaling that EmulationStation performs.

### Supported Views
Basic, Detailed, Grid, Video.

## License
Creative Commons. Please see [license.txt](license.txt).

### Logo Notice
The used logos and trademarks are copyright of their respective owners.

### Icons
- Cartridge icon made by [Creaticca Creative Agency](http://www.creaticca.com/) from www.flaticon.com
- Folder icon made by [Smashicons](http://www.Smashicons.com/) from www.flaticon.com
