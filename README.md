## screen  
  
full-screen window manager that multiplexes a physical terminal between several processes, typically interactive shells  
  
requires:    
```
apt install screen
```  
```
yum install screen
```  
```
pacman -S screen
```  
  
Automatic install/update:
```
bash -c "$(curl -LSs https://github.com/dfmgr/screen/raw/master/install.sh)"
```
Manual install:
```
mv -fv "$HOME/.config/screen" "$HOME/.config/screen.bak"
git clone https://github.com/dfmgr/screen "$HOME/.config/screen"
ln -sf $HOME/.config/screen/.screenrc $HOME/.screenrc
```
  
  
<p align=center>
  <a href="https://wiki.archlinux.org/index.php/GNU_Screen" target="_blank">screen wiki</a>  |  
  <a href="https://www.gnu.org/software/screen/" target="_blank">screen site</a>
</p>  
