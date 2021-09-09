# DraculaGDM
Modified GDM theme to match with Dracula's colors

### INSTALLATION
```
git clone https://github.com/xaeioux/DraculaGDM/
glib-compile-resources gnome-shell-theme.gresources.xml
```
***You must install glib2-devel to run 'glib-compile-resources'***

_I recomend you to backup the original gnome-shell-theme.gresource into your home directory with the command_

```
sudo cp /usr/share/gnome-shell/gnome-shell-theme.gresource ~
```

After backing up you must move the modified .gresource:
```
sudo mv gnome-shell-theme.gresource /usr/share/gnome-shell
```
Then finish restarting GDM:

```
systemctl restart gdm
```
And you are ready to go :)
