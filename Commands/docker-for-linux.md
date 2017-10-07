**Docky**

Software manager

**Plank**

#$ sudo add-apt-repository ppa:ricotz/docky
#$ sudo apt-get update
#$ sudo apt-get install plank

Configure Plank Dock:
Plank doesn’t have graphical configuration interface. To configure Plank Dock enter following command in Terminal:

#$ nano ~/.config/plank/dock1/settings

For Example: edit the configuration file.
HideMode = 1 means auto hide, set to 0 to disable it.
Position = 3 means the dock location. 0 = left, 1= right, 2 = top, 3= bottom.

