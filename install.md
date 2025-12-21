 sudo update-alternatives --install /usr/share/plymouth/themes/default.plymouth default.plymouth /usr/share/plymouth/themes/linux-penguin/linux-penguin.plymouth 800
 
 sudo update-alternatives --set default.plymouth /usr/share/plymouth/themes/linux-penguin/linux-penguin.plymouth 
 
 sudo update-initramfs -u