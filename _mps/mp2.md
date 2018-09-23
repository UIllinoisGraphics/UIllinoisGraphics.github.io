---
title: MP2
permalink: "/mp2/"
layout: page
---

### <span style="color:blue"> Accelerated Ray Tracing </span>
**Due: October 12, 11:55pm**

For your second programming assignment you will implement:

1. Support for triangle meshes.  
Be able to read in a mesh in the OBJ or PLY format. Links to some meshes in the OBJ format are inlcuded below. The background material for this feature is included in _Ray Tracing from the Ground Up Chapter 23 Meshes_
 
2. A spatial data structure to accelerate intersection testing. // 
   A uniform grid is sufficient, but if you wish you could implement any of the following instead:
   1. A KD-Tree [wikipedia link](https://en.wikipedia.org/wiki/K-d_tree)
   2. A Bounding Volume Hierarchy [wikipedia link](https://en.wikipedia.org/wiki/Bounding_volume_hierarchy)
   3. An Octree [wikipedia link](https://en.wikipedia.org/wiki/Octree)
 
3. Support for shadows. See _Ray Tracing from the Ground Up Chapter 16 Shadows_
 
4. Support for point lights. See _Ray Tracing from the Ground Up Chapter 14 Lights and Materials_
 
5. Implement shading for materials that uses both diffuse and specular reflection
         

### Hand-in

You will hand in your code and 2 images:

+ One rendering of a scene with a lot of spheres...feel free to add other stuff if you wish.
+ One rendering of an interesting triangle mesh...feel free to add other stuff if you wish.

Both images should exhibit:
+ Shadows
+ Diffuse and specular reflection
+ Lighting using point lights

**You also need to write a brief technical report that briefly describes which acceleration structure you implemented.**

Write one paragraph and include a table that shows the time required to render the following:
+ Rendering the mesh without acceleration
+ Rendering the mesh with acceleration
+ Rendering three different scenes with a growing number of spheres \\
(e.g. 100 spheres, 1000 spheres, and 10,000 spheres).

Hand-in will be done on Compass.

### Resources

+ Cow mesh [OBJ](https://raw.githubusercontent.com/UIllinoisGraphics/CS296/master/Meshes/cow.obj)

+ Bunny mesh [OBJ](https://github.com/UIllinoisGraphics/CS296/blob/master/Meshes/bunny.obj?raw=true)

+ Dragon mesh [OBJ](https://raw.githubusercontent.com/UIllinoisGraphics/CS296/master/Meshes/dragon.obj)

+ Teapot mesh [OBJ](https://raw.githubusercontent.com/UIllinoisGraphics/CS296/master/Meshes/teapot.obj)

Note that these meshes may need to be scaled and translated to work with easily. You can do so as pre-processing step or you can implement affine transformations in your renderer...see _Ray Tracing from the Ground Up Chapter 20 Affine Transformations_

### Rubric

|:----------------+------------|
| **Feature**           | **Points** |
|:--------------------------|-------:|
| Acceleration Structure      | 5      |
| Rendering a Mesh    | 4      |
| Point Light | 1      |
| Diffuse and Specular Shading  | 1      |
| Shadows  | 1      |
| Technical Report    | 3      |
| **TOTAL**	                 |15        |
|===
| 

