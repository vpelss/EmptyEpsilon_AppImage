# EmptyEpsilon AppImage

https://daid.github.io/EmptyEpsilon


EmptyEpsilon is a space bridge simulator.

You can build it yourself here:

I have created a Linux AppImage for EmptyEpsilon.

My AppImage version is here: https://github.com/vpelss/EmptyEpsilon_AppImage/releases/tag/download

Note: It is easiest to start in a Linux terminal. Making a launchable icon is possible, but will vary depending on your gui. 

- Download
- in a terminal run the following

  
```
chmod +x EmptyEpsilon-x86_64.AppImage
./EmptyEpsilon-x86_64.AppImage

```

#Make a Desktop Icon

If you save EmptyEpsilon-x86_64.AppImage in ~/AppImages/EmptyEpsilon-x86_64.AppImage, then you would place a desttop file here: ~/.local/share/applications/emptyepsilon.desktop and your emptyepsilon.desktop file might contain the following. Also if you want the icon, download it also. Note that the paths MUST be absolute.

```
[Desktop Entry]
Name=Space Nerds in Space
GenericName=Space Nerds in Space
Comment=Networked spaceship bridge simulator
Exec=/home/{your login name}/AppImages/ EmptyEpsilon-x86_64.AppImage
Icon=/home/{your login name}/AppImages/icon.svg
Terminal=false
Type=Application
Categories=Game;
```
Your game icon should now show in your gui menu under Game
