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

# catalog
open any terminal and run

```
ljpaper -catalog
```

this should open up a pygame display.

inside the pygame display you should see a **textbox**. 


**simply type in the directory of the folder ur pictures are in** and press enter.

this should load all pictures inside the folder.


**clicking any picture will change ur wallpaper**

*use up and down arrow keys to scroll up and down the pictures*

# setmem
once ur device starts up, you can run

```
ljpaper -setmem
```

this will change ur wallpaper to whatever wallpaper you had in the last session. 

**--ONLY IF YOU SET UR WALLPAPER USING ljpaper -catalog BEFORE**


------------------------------------- Config -------------------------------------

to check **ljpaper's config** simply run this command

```
cd ~/.config/ljpaper
```

this will open up a folder where after running **ls** command, you should see
two text files. **LJPaper.conf** and **LJPaper.Mem**
```
ls
```

>```LJPaper.conf    |   LJPaper.Mem```

**if you dont see these files please run ```ljpaper -setmem``` command**

the one we are interested in is the **LJPaper.conf**, we wont be touching the **.Mem** file.

run **```nano LJPaper.conf```** command to check the content of the config file.

the formatting in the file is as following:

--**screen width**,**screen height**
 
 --**images per column**
 
 --**ratio** *(this will affect the size of the texbox aswell as images)*
 
 --**Error msg duration** *(in seconds, must be an int)*
 
 --**.image file type N1**,**.image file type N2** ... ,**.image file type Nk**
