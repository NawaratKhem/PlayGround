Clearing the GNome extension that is causing the error:

# Reset extension state in dconf
dconf reset -f /org/gnome/shell/extensions/

# Remove cached extension data
rm -rf ~/.cache/gnome-shell/extensions/
rm -rf ~/.cache/gnome-shell/extension-state.*
