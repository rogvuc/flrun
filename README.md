WHAT IS FLRUN
-
flrun is a bash wrapper for `flatpak run` and `flatpak list`, it makes it easy for you to start your flatpak from the terminal without knowing long dot names, it can give you a list of all installed flatpaks from which you can choos one you want or you can just call it by its regular name, by default it does not tie flatpak to the terminal it was called from and you can close the terminal, but it has a flag for tying flatpak to the terminal same way as "flatpak run" does. Flrun expects that flatpak is installed and working on the system, it does not install nor try to fix any problems with flatpak. I made flun for personal use at first but i found it very useful so i decided to share, hope it will be useful to you, feel free to modify it and adapt it to your needs.

 USAGE
-
Just call flrun from the terminal and it will give you a list of all installed flatpaks on your system, then you can pick the one you want with arrow keys and enter. If you know name of the app you want to install just call it with `flrun <app name>` (with no <>). You can use -s flag to tie the app to the terminal.


https://user-images.githubusercontent.com/55914028/205493690-d99cac3a-2ef9-4dce-8292-ab85d72f1c29.mp4



INSTALLING
-
#### MANUAL:

1. Download flrun and copy it to your `/usr/local/bin/` dir
3. Make it executable (for example using 'chmod 755')


DISCLAIMER
-
This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.
