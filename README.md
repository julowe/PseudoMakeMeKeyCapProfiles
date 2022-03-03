# Pseudo Make Me Key Cap Profile

## How to
* make sure OpenSCAD is up to date.
* unzip libraries.zip into your OpenSCAD libraries
  * if using OpenSCAD 2019.5 (or above, likely), comment out line 7 (`function is_undef(x) = len(x) > 0 ? vec_is_undef(x) : x == undef;`) from `tracjectory.scad` from `libraries.zip`. This removes a compilation warning message.
* select keycap you want to render by changing KeyID value
* change KeyID to corresponding Parameter ID
* press F5 to review
* press F6 to render
* press F7 to export as STL

## STL Files
STLs for some keycaps are stored in the `STL` directory. Filenames include some parameter values that are outside of the 'defined' keycap calling function assoicated with the keycap name.

## TODO - Known Errors
* Chicago Steno R2/R4 1.5u renders with no stems
* Chicago Steno R3 1.5u renders with no dish on top of keycap

## Distorted Ellipsoidal Saddle (DES)
High sculpt smooth transition profile
![DES](https://raw.githubusercontent.com/pseudoku/PseudoMakeMeKeyCapProfiles/master/Photo/R1-R5.png)
### Standard
![Neuron v1](https://raw.githubusercontent.com/pseudoku/PseudoMakeMeKeyCapProfiles/master/Photo/DES_cast.jpg)

### Concave
![Corne thumb and Convex Caps](https://raw.githubusercontent.com/pseudoku/PseudoMakeMeKeyCapProfiles/master/Photo/Convex.jpg)

### Thumbs
![IMK Corne v1](https://raw.githubusercontent.com/pseudoku/PseudoMakeMeKeyCapProfiles/master/Photo/DES_corne.jpg)
![Kyria](https://raw.githubusercontent.com/pseudoku/PseudoMakeMeKeyCapProfiles/master/Photo/DES_kyria.png)

### Chicago Stenographer
Subtly sculpted choc spaced low profile
![CS](https://raw.githubusercontent.com/pseudoku/PseudoMakeMeKeyCapProfiles/master/Photo/CS.png)
#### Standard
![Look](https://raw.githubusercontent.com/pseudoku/PseudoMakeMeKeyCapProfiles/master/Photo/CS_gergo.jpg)

#### Convex
![Georgi](https://raw.githubusercontent.com/pseudoku/PseudoMakeMeKeyCapProfiles/master/Photo/CS_convex.jpg)
#### Thumbs
![1.5 + 1](https://raw.githubusercontent.com/pseudoku/PseudoMakeMeKeyCapProfiles/master/Photo/CS_Thumb.png)
Additional sculpt angle and smoother transitions

### Philadelphia Minimalist
![under](https://raw.githubusercontent.com/pseudoku/PseudoMakeMeKeyCapProfiles/master/Photo/Philadelphia_Minimalist.png)
Minimal spacing
Under construction
