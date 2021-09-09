# DraculaGDM
Edited GDM theme to match with Dracula's theme

After cloning this repo you must access downloaded directory and run:

glib-compile-resources gnome-shell-theme.gresources.xml

I recomend you to backup the original gnome-shell-theme.gresource into your home directory with the command

sudo cp /usr/share/gnome-shell/gnome-shell-theme.gresource ~

after backing up you must move the modified .gresource :

sudo mv gnome-shell-theme.gresource /usr/share/gnome-shell

then finish restarting GDM

systemctl restart gdm


And you are ready to go :)
