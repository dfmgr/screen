## screen  
  
full-screen window manager that multiplexes a physical terminal between several processes, typically interactive shells  
  
Automatic install/update:

```shell
bash -c "$(curl -LSs https://github.com/dfmgr/screen/raw/main/install.sh)"
```

Manual install:
  
requires:

Debian based:

```shell
apt install screen
```  

Fedora Based:

```shell
yum install screen
```  

Arch Based:

```shell
pacman -S screen
```  

MacOS:  

```shell
brew install screen
```
  
```shell
mv -fv "$HOME/.config/screen" "$HOME/.config/screen.bak"
git clone https://github.com/dfmgr/screen "$HOME/.config/screen"
ln -sf $HOME/.config/screen/.screenrc $HOME/.screenrc
```
  
<p align=center>
  <a href="https://wiki.archlinux.org/index.php/GNU_Screen" target="_blank" rel="noopener noreferrer">screen wiki</a>  |  
  <a href="https://www.gnu.org/software/screen" target="_blank" rel="noopener noreferrer">screen site</a>
</p>  
