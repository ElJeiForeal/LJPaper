# LJPaper
arch linux, hyprpaper wallpaper manager

-------------------------------------MUST HAVE-------------------------------------
>hyprpaper

```
sudo pacman -S hyprpaper
```

------------------------------------- How to set it up -------------------------------------


*1)* downlod **ljpaper** and put it inside any folder
   
*2)* open terminal, go inside the file's directory and make the file executable

```
cd ~/Downloads
```
```
chmod +x ljpaper
```

*3)* copy **ljpaper** to bin

```
cp ljpaper /usr/local/bin/ljpaper
```
   
*4)* delete the downloaded ljpaper

```
rm ljpaper
```
   
**You're ready to go!**



------------------------------------- How to use -------------------------------------

open any terminal and run
```ljpaper -catalog```

inside the pygame display, look above, you should see a **textbox. simply type in the directory of the folder ur pictures are in** and press enter.

this should load all pictures inside the folder.
**clicking any pictures will change ur wallpaper**
*use up and down arrow key to scroll up and down the pictures*

once ur device starts up, you can run
```ljpaper -setmem```
this will change ur wallpaper to whatever wallpaper you had in the last session. **--ONLY IF YOU SET UR WALLPAPER USING ljpaper -catalog BEFORE**
