---
title: Graphics Project
role: Graphics Programmer
image: assets/image-sample.png
alt: Graphics Project
categories: C++ OpenGL GLSL
asset-base: /assets/programming/graphics/
tags: graphics

priority : 2

caption:
  title: Graphics Project
  subtitle: Point/Directional/Spotlight <br> Deferred Shading <br> Bounding Volumes & BVH
  thumbnail: /assets/programming/graphics/thumbnail.png
  
video:
  title: Video
  url: https://www.youtube.com/embed/bF_bET01fDI
  detail:
    title: Graphics
    desc: Developed graphics engine with deferred shading and BVH.

detail:
  - image-path: deferred.png
    alt: deferred shading
    desc: deferred shading and multiple lights
  - image-path: bvh.png
    alt: bvh
    desc: BVH construction
  - image-path: collision.png
    alt: collision detection
    desc: collision detection
---

{% include custom/section-header title="Description" %}
{% include custom/gallery id="detail" %}
Develop custom obj file loader to render model and apply Blinn-Phong lighting, multiple lighting with point light, directional light, spotlight, deferred shading. Detect collision between AABB, sphere, ray, triangle, plane, and point and generate BVH when loading models. Save and load scene data including lighting information.