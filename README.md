# fedora
Customize font size:
```bash
gsettings set org.gnome.desktop.interface font-name 'Adwaita Sans 16'
gsettings set org.gnome.desktop.interface document-font-name 'Adwaita Sans 20'
gsettings set org.gnome.desktop.interface monospace-font-name 'Adwaita Mono 18'
```
Unset prompt:
```bash
echo "unset PROMPT_COMMAND" >> ~/.bashrc
```
