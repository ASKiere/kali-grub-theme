## Intro
This repo holds the Kali Linux GRUB theme ripped straight from the files!
## Sources
```/boot/grub/themes/kali``` for the theme files and ```/usr/share/images/desktop-base/desktop-grub.png``` for the background
## How to Install?
Add the kali directory to ```/boot/grub/themes``` (it can be any path but this is the standard)</br>
Edit ```/etc/default/grub``` and find the ```GRUB_THEME="/boot/grub/themes/whatever"```
line</br>and change it to ```GRUB_THEME="/boot/grub/themes/kali"```</br></br>
Then, on apt based systems run ```sudo update-grub```</br></br>
On most other systems you can run ```sudo grub-mkconfig -o /boot/grub/grub.cfg``` to achieve the same effect.
## GRUB Background info
In order to have the Kali background show up, you have two options:</br></br>1) (not reccomended) create the ```/usr/share/images/desktop-base``` directory and add the image there. (this is the path it searches by default)</br></br>2) (optimal) edit the ```grub_background.sh``` script and add your custom path.
