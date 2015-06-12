#Taste the rainbow
https://www.google.com/design/spec/style/color.html#color-color-palette

### install (short version)
```
maven {
  url "https://jitpack.io"
}
```
```
compile 'com.github.mcginty:material-colors:1.0.1'
```
###### See https://jitpack.io/#mcginty/material-colors/1.0.1 if you are unfamiliar with the structure of build.gradle files.

### use
Color resource names are in the form of `material_<colorname><colorvalue>`, ex:
* XML: `@color/material_red500`, `@color/material_deeppurpleA200`
* Java: `R.color.material_red500`, `R.color.material_deeppurpleA200`

### color names
* red
* pink
* purple
* deeppurple
* indigo
* blue
* lightblue
* cyan
* teal
* green
* lightgreen
* lime
* yellow
* amber
* orange
* deeporange
* brown
* grey
* bluegrey
* black and white (with no color values)

### color values
*normal:* 50, 100, 200, 300, 400, 500, 600, 700, 800, 900

*accent:* A100, A200, A400, A700

(note that accent values don't exist for brown, grey, and bluegrey)
