<p align="center">
<img src="https://raw.githubusercontent.com/awaSwasA/Grub2-Theme-Breeze-Monokai/master/Screenshot_20170723_035245.png" width="600">
</p>    

# breeze-monokai
A grub theme fork from breeze, extremely simple, with monokai color scheme    

## How to use

Copy the theme folder to /boot/grub/themes    
```
sudo cp -r breeze-monokai  /boot/grub/themes
```    
Change theme in grub config file
```
sudo vim  /etc/default/grub
...
 GRUB_THEME="/boot/grub/themes/breeze-monokai/theme.txt"
...
 ```   
Save, then rebuild grub to /boot
```
grub-update    
or   
grub-mkconfig
```
