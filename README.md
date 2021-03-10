# bspwm-wm Setup and Theme for EndeavourOS
Community Edition 
***

## To Install manually

    git clone https://github.com/EndeavourOS-Community-Editions/bspwm.git

    cd bspwm

    bash bspwm-install.sh
   
## Contained In The Script
    cp -R .config/* ~/.config/
        
    cp .gtkrc-2.0 ~/.gtkrc-2.0
    
    chmod -R +x ~/.config/bspwm/scripts
        
    sudo yay -Syu --needed --noconfirm - < packages-repository.txt
    
    dbus-launch dconf load / < xed.dconf
    
## Get involved at our forum:
https://forum.endeavouros.com/t/bspwm-edition/8511/359

## Tutorial for bspwm-wm settings:
- Background handled by nitrogen
- Gtk3 theme handled by lxappearance-gtk3
- Filebrowser = Thunar
- Default Terminal-Emulator = Termite
- Text-Editor = xed
- Application Launcher = Rofi



