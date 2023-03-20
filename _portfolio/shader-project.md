---
title: Shader Project
role: Graphics Programmer
image: assets/image-sample.png
alt: Shader Project
tools: C++ | OpenGL | GLSL | RapidJSON
asset-base: /assets/programming/tessellation/

caption:
  title: Shader Project 
  subtitle: Silhouette <br> Grass
  thumbnail: /assets/programming/tessellation/thumbnail.png
  
video:
  title: Video
  url: https://www.youtube.com/embed/XQzDK7kgjjM
  detail:
    - title: Scene and Resoure Manage
      desc: Load *.obj file with custom obj file loader and find triangle adjacencies to generate silhouette. The user can not only add objects to the scene, but also save or load the save data. The save data is generated using <i>RapidJSON</i>. 
    - title: Geometry Shader
      desc: Wireframe and silhouette is generated by geometry shader. The user can adjust width and color of them. A grass blade is generated in the geometry shader. It calculates position where to locate the blade, how much it should bend, and which direction it should face according to the constrains given the user.
    - title: Tessellation
      desc: Subdivide meshes using tessellation shader. The user can determine how much to tessellate. Or, the level of tessellation can be automatically calculated depending on the distance from the camera. Tessellation shader is used to generate grass blades on the object. Because one face only has one blades, the tessellation can help to make richer grass on the object.
      
detail:
  - image-path: wireframe-cube.png
    alt: wireframe of cube
    desc: wireframe of cube
  - image-path: wireframe-pokeball.png
    alt: wireframe of pokeball
    desc: wireframe of pokeball
  - image-path: silhouette-cube.png
    alt: silhouette of cube
    desc: silhouette of cube
  - image-path: silhouette-torus.png
    alt: silhouette of torus
    desc: silhouette of torus
  - image-path: silhouette-book.png
    alt: silhouette of book
    desc: silhouette of book
  - image-path: tess-quad-default.png
    alt: quad
    desc: quad
  - image-path: tess-quad-inner.png
    alt: inner tessellation
    desc: inner tessellation 
  - image-path: tess-quad-outer.png
    alt: outer tessellation
    desc: outer tessellation
  - image-path: tess-quad.png
    alt: tessellation quad
    desc: tessellation quad
  - image-path: tess-gumbo-default.png
    alt: faraway elephant
    desc: faraway elephant
  - image-path: tess-gumbo.png
    alt: nearby elephant
    desc: nearby elephant
  - image-path: grass-quad.png
    alt: grass blade
    desc: generate grass blades on each face
  - image-path: grass-width.png
    alt: wider grass blade
    desc: wider grass blade
  - image-path: grass-rotation.png
    alt: bended grass blade
    desc: more bended grass blade
  - image-path: grass-torus-small.png
    alt: grass on torus
    desc: apply grass on torus
  - image-path: grass-torus-default.png
    alt: grass on torus
    desc: tessellate and add grass
  - image-path: grass-pokeball.png
    alt: grass on pokeball
    desc: grass on pokeball
  - image-path: grass-book.png
    alt: grass on book
    desc: grass on book
---
<hr/>

{% include gallery title="Detail" id="detail" desc="This is a shader project." %}