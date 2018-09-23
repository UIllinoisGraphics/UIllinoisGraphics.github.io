---
title: MP2
permalink: "/mp2/"
layout: page
---

### <span style="color:blue"> Accelerated Ray Tracing </span>
**Due: October 12, 11:55pm**

For your second programming assignment you will implement:

[4pts] Support for triangle meshes. [Ray Tracing from the Ground Up Chapter 23 Meshes]
Be able to read in a mesh in the OBJ or PLY format. The Stanford 3D Scanning Repository has some meshes you could consider using.
 
[6 pts] A spatial data structure to accelerate intersection testing.  [Ray Tracing from the Ground Up Chapter 22 Regular Grids]
Note: implementing a regular grid will be worth 5pts out of the 6pts. For full credit, implement a different accelration structure, such as one of the following:
​A KD-Tree [wikipedia link]
A Bounding Volume Hierarchy [wikipedia link]
An Octree [wikipedia link]
 
[2 pts] Support for shadows.  [Ray Tracing from the Ground Up Chapter 16 Shadows]
 
[1 pt  ] Support for point lights  [Ray Tracing from the Ground Up Chapter 14 Lights and Materials]
 
[2 pts] Implement a BRDF for materials that uses both diffuse and specular reflection  [Ray Tracing from the Ground Up Chapter 15 Specular Reflection]
         

Hand-in

You will hand in your code and 2 images:

One rendering of a scene with a lot of spheres...feel free to add other stuff if you wish.
One rendering of an interesting triangle mesh...feel free to add other stuff if you wish.
Both images should exhibit
​Shadows
Diffuse and specular reflection
Lighting using point lights
A link to a google doc that briefly describes which acceleration structure you implemented (write one paragraph) and shows times for:
​Rendering the mesh without acceleration
Rendering the mesh with acceleration
Rendering three different scenes with a growing number of spheres (e.g. 100 spheres, 1000 spheres, and 10,000 spheres).
Hand-in will be done on Compass.

Resources

Cow mesh [OBJ]

Bunny mesh [OBJ]

Note that these meshes may need to be scaled and translated to work with easily. You can do so as pre-processing step or you can implement affine transformations in your renderer [Ray Tracing from the Ground Up Chapter 20 Affine Transformations]
