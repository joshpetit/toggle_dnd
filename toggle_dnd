#!/bin/bash
value=$(gsettings get org.gnome.desktop.notifications show-banners)
if [[ $value == 'true' ]]
then
  notify-send "Notifications are disabled" -i user-busy
  gsettings set org.gnome.desktop.notifications show-banners false
else
  gsettings set org.gnome.desktop.notifications show-banners true
  notify-send "Notifications are enabled" -i user-available
fi
