# GlossyBlack Theme

Glossy gradient styled GTK2/3 theme.

See <a href="http://gnome-look.org/content/show.php/?content=162055" target="_blank">gnome-look.org page</a> for a quick preview.

### Requirements

* GTK 2.24 and/or GTK 3.20
* The murrine engine. This has different names depending on your distro.
  * `gtk-engine-murrine` (Arch Linux)
  * `gtk2-engines-murrine` (Debian, Ubuntu, elementary OS)
  * `gtk-murrine-engine` (Fedora)
  * `gtk2-engine-murrine` (openSUSE)
  * `gtk-engines-murrine` (Gentoo)

### Installation

##### Packages

Arch Linux users can install the theme from the AUR:
https://aur.archlinux.org/packages/gtk-theme-glossyblack/

##### Manual Installation

**Important:** Remove all older versions of the theme from your system before you proceed any further (if any).
```
  sudo rm -rf /usr/share/themes/GlossyBlack
  rm -rf ~/.local/share/themes/GlossyBlack
  rm -rf ~/.themes/GlossyBlack
```
then
```cd glossyblack-gtk-theme```

and install per user with:
```cp -r ./GlossyBlack ~/.local/share/themes``` or ```~/.themes/GlossyBlack```

or globally with:
```sudo cp -r ./GlossyBlack /usr/local/themes```

  
