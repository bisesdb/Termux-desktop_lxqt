# Termux-desktop_lxqt

pkg update

pkg upgrade


pkg install tigervnc lxqt

pkg install lxqt*


vncserver -geometry 1200x600 -xstartup ../usr/bin/startlxqt


vncserver -kill :1
