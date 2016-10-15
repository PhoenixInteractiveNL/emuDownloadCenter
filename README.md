## EDC MasterHook

![](https://raw.githubusercontent.com/wiki/PhoenixInteractiveNL/emuControlCenter/images/img_misc_cabinet.png)

emuDownloadCenter (EDC) is a program to download ROM emulators from internet.
Mostly in depots where found emulators on the internet are stored.
Author: Sebastiaan Ebeltjes, Deventer (Netherlands)

EDC is part of emuControlCenter, homepage/download:
https://github.com/PhoenixInteractiveNL/emuControlCenter/wiki
***
### Emulatorlist.ini

To prevent folder names with spaces and give nice emulator names in EDC listings, this ini wil link those names 

Format: `FOLDER=EMULATORNAME`
***
### Emulator Hooks

Every emulator (not versions) is put in in the `downloadhooks\[emulatorfoldername]` folder.

In here 3 files are stored:

2 INI files wich contain data
1 JPG file wich is a screenshot of the emulator (in action)

    [emulatorfoldername]_downloads.ini
    [emulatorfoldername]_info.ini
    [emulatorfoldername]_screen

