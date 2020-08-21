## volumeicon  
  
File Manager  
  
Automatic install/update:  
  
```
bash -c "$(curl -LSs https://github.com/dfmgr/volumeicon/raw/master/install.sh)"
```
  
Manual install:  
requires:  
```apt install volumeicon-alsa```  
```yum install volumeicon```  
```pacman -S volumeicon```  
  
```
mv -fv "$HOME/.config/volumeicon" "$HOME/.config/volumeicon.bak"
git clone https://github.com/dfmgr/caja "$HOME/.config/volumeicon"
```
  
<p align=center>
  <a href="http://nullwise.com/volumeicon.html" target="_blank">volumeicon site</a>
</p>  
