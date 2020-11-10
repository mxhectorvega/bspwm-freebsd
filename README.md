# DotfilesFreeBSD

Configuraciones personales en FreeBSD

BSPwm con Polybar y Rofi menu.


<img src="https://github.com/mxhectorvega/dotfilesfreebsd/blob/main/screenshots/photo_2020-10-31_21-12-07.jpg" />

<img src="https://github.com/mxhectorvega/dotfilesfreebsd/blob/main/screenshots/photo_2020-10-31_21-36-21.jpg" />

<img src="https://github.com/mxhectorvega/dotfilesfreebsd/blob/main/screenshots/photo_2020-10-31_21-15-52.jpg" />


**Crear directorios**

Crea el directorio ya que en los BSD normalmente no esta:

```
mkdir .config
```


**Configuracion**

Clonar y copiar los archivos de configuracion:

```
git clone https://github.com/mxhectorvega/dotfilesfreebsd

cp -R ~/dotfiles/.config/* ~/.config

cp ~/dotfiles/.Xresources ~/.Xresources
```


Crear el archivo `.xinitrc` y agregarle la linea `exec bspwm`:

```
vim .xinitrc
```


Otorgar permisos de ejecucion a los archivos:

```
chmod +x .config/bspwm/bspwmrc
chmod +x .xinitrc
```


**Dependencias**

```
pkg install py37-pip python37 ncpamixer ImageMagick7 py27-ranger picom youtube_dl feh sxiv musicpd musicpc ncmpcpp firefox telegram-desktop htop xarchiver neofetch leafpad pcmanfm lxappearane zathura zathura-pdf-mupdf neovim mpv

pip install pywal
```

**Temas**

```
pkg install papirus-icon-theme materia-gtk-theme
```


**Grupo telegram:**

https://t.me/bsdesp

**Canal de tips:**

https://t.me/bsd_tips

**Creditos:**

@mxhectorvega @DtxdF @ozunalexis @AlexHMusique @Lunatic_101
