*GLSL raymarching within TouchDesigner*
------

I'm in process of making templates and video tutorial for helping to do raymarching (RM) in TouchDesigner.

**SDF tests.toe** — Performance test with two different approaches to sampling coordinates and GLSL code from two different RM tutorials

**RM+poly.toe**  — Shows how to combine polygonal geometry with standard rendering setup with raymarching.


**template - basic.toe** — Basic raymarcher template for creating everything using vector uniforms

**template - basic_v2.toe** — Same + shadows and ambient occlusion

**template - basic_v3.toe** — Same, but different approach for a camera. Now you can use arcball camera COMP (or any other camera COMP) instead of tweaking values manually.


**template - array.toe** — Variation of a basic raymarcher template for creating geometry from texture buffer array

**template - array_v2.toe** — Same + shadows and ambient occlusion

**template - array_v2.toe** — Same, but using arcball camera COMP instead of uniforms. And cubes instead of spheres, now it better shows how to feed a lot of parameters for primitive from TOPs.


**tutorial - part 1.toe** — Supplementary file for a Part I of the tutorial. Main covered topic is describing a scene for RM using two approaches: basic uniforms and hard-coded variables for creating a geometry and an texture buffer array for using CHOP data in a loop.

<a href="http://www.youtube.com/watch?feature=player_embedded&v=hZj6jaYNKJo" target="_blank"><img src="http://img.youtube.com/vi/hZj6jaYNKJo/0.jpg" alt="video tutorial 1" width="384" height="216" border="5" /></a>


**tutorial - part 2.toe** — Supplementary file for a Part II of the tutorial. Different approaches to do light setup, coloring, reflections and combining raymarching GLSL with traditional rendering (render TOP) + some info about using color buffers.

<a href="http://www.youtube.com/watch?feature=player_embedded&v=IZUqM9CRjTk" target="_blank"><img src="http://img.youtube.com/vi/IZUqM9CRjTk/0.jpg" alt="video tutorial 2" width="384" height="216" border="5" /></a>


**tutorial - part 3.toe** — Supplementary file for a Part III of the tutorial. This one is about different apporoaches to warping a space as an instrument of modifying geometry: trigonometrical functions, gyroids, endless repetitions, kaleidoscopic iterations, fractals and so on.

<a href="http://www.youtube.com/watch?feature=player_embedded&v=2cMhk_crpY8" target="_blank"><img src="http://img.youtube.com/vi/2cMhk_crpY8/0.jpg" alt="video tutorial 3" width="384" height="216" border="5" /></a>

PS: if you found this repo/tutorials helpful, you can support me on Patreon https://www.patreon.com/exsstas or you can make one-time donation instead of monthly subscription with https://paypal.me/exsstas — it will motivate me to make more tutorials ;)
