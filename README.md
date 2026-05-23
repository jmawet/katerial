# Katerial (KDE Material Design Theme)

The goal of this project is to create a modern theme for KDE Plasma based on Material Design, updated for Plasma 6. 

Started as a fork of [Nova suite for Plasma Desktop](https://github.com/varlesh/nova-kde). Plasma style is changed the least, I just tweaked the taskbar item backgrounds. Kvantum theme is using the same base svg file, but recolored to match the new color scheme. The SDDM and lookandfeel themes in this repo are untouched since I forked from Nova. I am planning to update those, I just haven't gotten to it. 

Aurorae window decorations are a mix of [Materia KDE](https://github.com/PapirusDevelopmentTeam/materia-kde) icons (except the app menu icon I had to make from scratch) plus [Utterly Round](https://github.com/HimDek/Utterly-Round-Plasma-Style) decoration. 

The color scheme I recreated from scratch. 

I didn't even bother with icons, [Papirus](https://github.com/PapirusDevelopmentTeam/papirus-icon-theme) is *chef's kiss*. 

## Screenshot:

![katerial_latest](screenshots/katerial_050225.png)

- Color scheme: Katerial Light Red/Pink
- Application Style: Kvantum (Katerial Light Red/Pink)
- Plasma Style: Katerial Light
- Window Decorations: Katerial Light
- Icons: Papirus
- Cursor: Breeze Light
- Wallpaper: Katerial

## To install:

### KDE Store
You can download the elements of this theme in KDE Settings. Just click "get new" under Colors&Themes for Color, Plasma Style, or Window Decorations.

You can also download from pling/kde store:
- Color scheme: https://store.kde.org/p/2286301
- Kvantum theme: https://store.kde.org/p/2286303
- Window decorations: https://store.kde.org/p/2286304
- Plasma Style: https://store.kde.org/p/2286305

### From source
- Clone this repo
- Copy the directory: aurorae/themes/Katerial/ to ~/.local/share/aurorae/themes/, then set 'window decorations'
- Copy the directory: plasma/desktoptheme/Katerial/ to ~/.local/share/plasmaqa/desktoptheme/, then set 'plasma style'
- Copy the file: Katerial.colors to ~/.local/share/color-schemes/, then set 'color scheme'
- Install Kvantum, set as application style. In Kvantum, install and load Kvantum/Katerial/ directory
- Download and install Papirus icon set
- (Optional) set wallpaper included in this repo

## Available color schemes:
Plasma style and Aurorae window decorations will adapt based on the color scheme, the rest will use your system color scheme. Colorscheme and Kvantum theme need individual variants. Available variants are:

- Light
    - Red/Pink (255,218,212)(#ffdad4)
    - More planned in future but not available yet
- Dark
    - Red/Pink (217,65,65)(#d94141)
    - More planned in future but not available yet
    

## To be updated:
- Cursor (I don't hate breeze, but I don't love it)
- SDDM (kde is not behaving so I can't test)
- Alternate color schemes (if anyone wants a specific color scheme, feel free to raise an issue or PR)
