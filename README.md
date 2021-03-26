# hello-world
Hello World tutorial on Github

Hello Country!<br>
Hello State!<br>
Hello City!<br>
Hello Block!<br>
Hello House!<br>
Hello Room<br>
Hello Closet!<br>

# RetroPie Shader Config Files

This script creates cfg files for optimum shader appearence for use with RetroPie. Works with the following cores:

mame2000-libretro *(based on MAME 0.37b5)*<br>
mame2003-libretro *(based on MAME 0.78)*<br>
mame2003-plus-libretro *(based on MAME 0.78 + additions)*<br>
mame2010-libretro *(based on MAME 0.139)*<br>
mame2015-libretro *(based on MAME 0.160)*<br>
mame2016-libretro *(based on MAME 0.174)*<br>
consoles *(currently only Nestopia/NES)*<br>

### Usage:

python pi_shader_configs.py \<*core*\> \<*shader*\> \<*screen width*\> \<*screen height*\>

## Parameters:

  * core (*mame2000*, *mame2003*, *2003plus*, etc.)
  * shader (*crtpi* or *zfast*)
  * screen width (i.e. *1920* or *curvature*)
  * screen height (i.e. *1080* or *leave blank*)

**Core:**
  * mame2000-libretro **=** *mame2000*
  * mame2003-libretro **=** *mame2003*
  * mame2003-plus-libretro = *2003plus*
  * mame2010-libretro = *mame2010*
  * mame2015-libretro = *mame2015*
  * mame2016-libretro = *mame2016*
  * Nestopia/NES = *consoles*

**Shader:**
  * *crtpi*
  * *zfast*

**Screen Width:**
  * any width or *curvature*

**Screen Height:**
  * any height *or* leave blank (if using *curvature* in width)
