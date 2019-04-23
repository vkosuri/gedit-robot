# gedit-robot
Robotframework syntax highlighter for GEdit

## Gedit

``` Shell
sudo cp ./robot.lang  /usr/share/gtksourceview-3.0/language-specs/robot.lang
```
![copy-robot](https://cloud.githubusercontent.com/assets/13664257/12109003/9dfd7f2e-b3a3-11e5-8896-b283186c8242.png)

chmod the file  /usr/share/gtksourceview-3.0/language-specs/robot.lang

``` Shell
sudo chmod 644 /usr/share/gtksourceview-3.0/language-specs/robot.lang
```
or per-user
``` Shell
cp ./robot.lang  ~/.local/share/gtksourceview-3.0/language-specs/robot.lang
```

![disp-robot](https://cloud.githubusercontent.com/assets/13664257/12109041/108b99e0-b3a4-11e5-8770-2e0c1d8235e0.png)

**After import the syntax will work .robot files only**
