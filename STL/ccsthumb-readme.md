All Choc Chicago Steno Thumb (ccsthumb) keycaps created with the keycap tester function in `Choc_Chicago_Steno_Thumb.scad`, copied below in case it changes in a future revision. Only the x value of mirror and keyID changes for each key:

```
mirror([1,0,0]) {
keycap(
  keyID   = 3, //change profile refer to KeyParameters Struct
  cutLen  = 0, //Don't change. for chopped caps
  Stem    = true, //turn on shell and stems
  StemRot = 0,//change stem orientation by deg
  Dish    = true, //turn on dish cut
  Stab    = 0, 
  visualizeDish = false, // turn on debug visual of Dish 
  crossSection  = false, // center cut to check internal
  homeDot = false, //turn on homedots
  Legends = false
); 
}
```
