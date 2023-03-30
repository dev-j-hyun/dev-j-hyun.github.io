---
title: Graphigs Engine
role: Engine / Tools / Graphics Programmer
image: assets/image-sample.png
alt: Graphigs Engine
categories: C++ OpenGL GLSL ImGui FBXSDK
asset-base: /assets/programming/grapigs/
tags: graphics team-project

priority : 1

caption:
  title: Grapigs Engine
  subtitle: Engine & Tools <br> Shader Effects
  thumbnail: /assets/programming/grapigs/thumbnail.png
  
video:
  title: Video
  url: https://www.youtube.com/embed/HBSMX4QoOrw
  detail:
    title: Grapigs Engine
    desc: Rendering engine using OpenGL

detail:
  - image-path: material.png
    alt: material
    desc: GUIs
  - image-path: import.png
    alt: import texture modal
    desc: import texture modal
  - image-path: rust.png
    alt: rust
    desc: rusted-metal effect
  - image-path: glitch.png
    alt: glitch
    desc: chromatic aberration
  - image-path: blur.png
    alt: blur
    desc: blur effect
---

{% include custom/section-header title="Description" %}
{% include custom/gallery id="detail" %}
Create an engine for rendering objects to implement PBR techniques. Keep the hierarchical structure of the model while loading fbx files using FBXSDK. Create GUI tools to adjust the object and each mesh’s material data. Change the texture of the material by dropping image files into the program or dragging and dropping the texture to the material window from the asset window. Add new uniform variables in runtime without rebuilding the project. Edit shader pipeline in runtime. Apply shader effects to objects or a scene, such as the rusted metal effect using Perlin noise, chromatic aberration, and blur effect.