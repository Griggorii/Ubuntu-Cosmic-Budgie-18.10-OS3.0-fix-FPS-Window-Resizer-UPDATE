# Ubuntu 16.04 (не для 18.10)

Download etc.zip https://github.com/Griggorii/Ubuntu-Cosmic-Budgie-18.10-OS3.0-fix-FPS-Window-Resizer-UPDATE/blob/master/etc.zip

Run terminal command

sudo rm -rf /etc/X11/xorg.conf.d

sudo rm -rf /etc/xdg/autostart

Replace inpack in / zip etc.zip  

/etc/X11/xorg.conf.failsafe

/etc/default/grub

/etc/xdg/autostart

Firefox fix tutorial https://www.youtube.com/watch?v=nlJFJchdNVI

su

&& update-initramfs -u && update-grub

Reboot

На 16.04 можно поставить самый новый Kodi TV как поставить ниже

Kodi TV 18.0 

sudo apt remove --purge kodi kodi-bin
sudo apt purge kodi kodi.bin
sudo add-apt-repository ppa:team-xbmc/unstable
rm -rf ~/.kodi
rm -rf /usr/lib/x86_64-linux-gnu/kodi/
sudo update && sudo aapt install kodi

Мой конфиг для kodi https://www.youtube.com/watch?v=_p5mTuj_Etc 
