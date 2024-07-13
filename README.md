## ???
It's the Kali Linux GRUB theme ripped straight from the files!
## What's the Source?
/boot/grub/themes/kali
## How to Install?
Add the kali directory to /boot/grub/themes</br>
Edit /etc/default/grub and find the ```GRUB_THEME="/boot/grub/themes/whatever"```
line</br>and change it to ```GRUB_THEME="/boot/grub/themes/kali"```</br></br>
Then, on apt based systems run ```sudo update-grub```</br></br>
On most other systems you can run ```sudo grub-mkconfig -o /boot/grub/grub.cfg``` to achieve the same effect.
