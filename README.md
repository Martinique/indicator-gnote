# indicator-gnote
Indicator menu for Gnote, written in Python

Installing:

    wget https://github.com/Martinique/indicator-gnote/raw/master/indicator-gnote
    chmod +x indicator-gnote
    sudo mv -f indicator-gnote /usr/local/bin

Usage:

     indicator-gnote

To set maximum number of notes displayed (default 10), use -c (or --count):

     indicator-gnote -c 20

If you get "Namespace AppIndicator3 not available", you need an additional package:

     sudo apt install gir1.2-appindicator3-0.1

Recent GNOME desktop versions have indicator icons hidden by default, but you can make them visible again with an extension such as [this one](https://extensions.gnome.org/extension/615/appindicator-support/).
