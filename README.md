# **EXPLANATION**
## Major Concepts and Tools used  

+ C programming
  + Libraries

+ Mathematics
  + Parametric(torus)
  + 3-D Geometry
  + rotational matrices

+ Terminal & display tools
  + ANSI escape codes(`\x1b[2j,\x1b[h`) : clear screen and move cursor to top-left to render new frames in-place.
  + Terminal emulator — the characters, width/height and font affect perceived aspect ratio
  + memset : for fast clearing
+ Rendring technique & algorithms
  + Z-buffer(depth buffer) ->z[0]  prevents farther points from overwriting nearer ones.
  + ASCII shading(.,-~:;=!*#$@)
### Short concept (overview)  

+ **Parametric torus** → two angles (θ, φ).

+ **Rotate** → apply rotation matrices (or algebraic equivalent).

+ **Project** → divide x,y by depth to produce perspective.

+ **Shade** → dot(normal, light_dir) → char ramp.

+ **Z-buffer** → keep closest D per cell.

+ **Performance** → precompute, small memory, optimize compiler flags.


  

