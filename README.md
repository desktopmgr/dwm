## dwm  

 Source files to build a patched version of DWM  
 This is based off of [DistroTubes DWM](http://gitlab.com/dwt1)  
  
### Requires scripts to be installed

```shell
sudo bash -c "$(curl -LSs <https://github.com/desktopmgr/installer/raw/main/install.sh>)" && sudo desktopmgr install installer
```

### Automatic install/update

```shell
desktopmgr install dwm
```

OR

```shell
bash -c "$(curl -LSs https://github.com/desktopmgr/dwm/raw/main/install.sh)"
```
  
requirements:
  
Debian based:

```shell
apt install dwm
```  

Fedora Based:

```shell
yum install dwm
```  

Arch Based:

```shell
pacman -S dwm
```  

MacOS:  

```shell
brew install dwm
```
  
Manual install:  

  ```shell
APPDIR="$HOME/.local/share/CasjaysDev/desktopmgr/dwm"
mv -fv "$HOME/.config/dwm" "$HOME/.config/dwm.bak"
git clone https://github.com/desktopmgr/dwm "$APPDIR"
cp -Rfv "$APPDIR/etc/." "$HOME/.config/dwm/"
[ -d "$APPDIR/bin" ] && cp -Rfv "$APPDIR/bin/." "$HOME/.local/bin/"
```
  
<p align=center>
   <a href="https://travis-ci.com/github/desktopmgr/dwm" target="_blank" rel="noopener noreferrer">
     <img src="https://travis-ci.com/desktopmgr/dwm.svg?branch=master" alt="Build Status"></a><br />
  <a href="https://wiki.archlinux.org/index.php/dwm" target="_blank" rel="noopener noreferrer">dwm wiki</a>  |  
  <a href="dwm" target="_blank" rel="noopener noreferrer">dwm site</a>
</p>  
