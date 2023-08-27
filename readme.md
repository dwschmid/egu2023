# Pen-Man Summer School 2023
In my introduction to numerical modelling we will use several of my github repositories:

- https://github.com/dwschmid/muskhelishvili
- https://github.com/dwschmid/fgt
- https://github.com/dwschmid/folder

Go to those repos, click on the green *<>Code button* and *Download Zip*.
Unpack all of these into one a folder that you call e.g. *model_intro*. You should now have 4 subfolders in model_intro and you're good to go.

**Note:** 
On the Mac you might get a problem with some security issue related to mex files. This can be fixed by running the following code lines in your terminal **before** running any of the tools. 

```
sudo xattr -r -d com.apple.quarantine model_intro
sudo find model_intro -name \*.mexmaci64 -exec spctl --add {} \;
```

On windows you may be asked to install a C++ runtime. Go ahead and do that and the tools should work.

## Images for analysis
![Best Ever](best_ever.jpg)
![Folding](folding.jpg)
![Boudin](boudin.jpg)