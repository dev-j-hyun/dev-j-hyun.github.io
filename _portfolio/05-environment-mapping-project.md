---
title: Environment Mapping Project
role: Graphics Programmer
image: assets/image-sample.png
alt: Environment Mapping Project
categories: C++ OpenGL GLSL
asset-base: /assets/programming/reflection/
tags: graphics

caption:
  title: Environment Mapping Project
  subtitle: Skybox <br> Reflection & Refraction
  thumbnail: /assets/programming/reflection/thumbnail.png
  
video:
  title: Video
  url: https://www.youtube.com/embed/6Se4ASYQbE8
  detail:
    title: Environment Mapping
    desc: "Skybox + Refraction + Reflection"

enviroment-blending:
  - image-path: blend-phong.png
    alt: phong shading
    desc: phong shading
  - image-path: blend-middle.png
    alt: blend environment mapping and phong shading
    desc: blend environment mapping and phong shading
  - image-path: blend-environment.png
    alt: environment mapping
    desc: environment mapping
reflection-refraction:
  - image-path: reflection-bunny.png
    alt: bunny reflection
    desc: only reflection
  - image-path: refraction-bunny.png
    alt: bunny refraction
    desc: only refraction
  - image-path: fresnel-bunny.png
    alt: bunny fresnel
    desc: fresnel
  - image-path: glitch-bunny.png
    alt: bunny glitch
    desc: chromatic aberration
  - image-path: refraction-cup-diamond.png
    alt: diamond cup refraction
    desc: diamond cup
  - image-path: refraction-cup-oil.png
    alt: oilly cup refraction
    desc: oilly cup

---
<hr/>
The project demonstrates environment mapping. There is a main object in the middle of the scene and a light object rotating along it.

{% include custom/image image-path="blend-phong.png" alt="phong shading" desc="phong shading" %}
{% include custom/image image-path="blend-middle.png" alt="blend environment mapping and phong shading" desc="blend environment mapping and phong shading" %}
{% include custom/image image-path="blend-environment.png" alt="environment mapping" desc="environment mapping" %}
The user can set the blend factor for how to blend the two colors from the Phong shading and environment mapping. 0 means show results from Phong shading and 1 means shows result from environment mapping.


{% include custom/image image-path="reflection-bunny.png" alt="bunny reflection" desc="reflection" %}
{% include custom/image image-path="refraction-bunny.png" alt="bunny refraction" desc="refraction" %}
{% include custom/image image-path="fresnel-bunny.png" alt="bunny fresnel" desc="fresnel" %}
There are three modes for environment mapping: reflection, refraction, Fresnel. If both ‘Reflection’ and ‘Refraction’ checkbox are marked, it means using combination of both using the Fresnel approximation. 


{% include custom/image image-path="refraction-cup-diamond.png" alt="diamond cup refraction" desc="diamond cup" %}
{% include custom/image image-path="refraction-cup-oil.png" alt="oilly cup refraction" desc="oilly cup" %}
There are preset materials for the refraction. If the user chooses the user define material in the material dropdown, the slider bar appears so that the index value can be changed.

{% include custom/image image-path="glitch-bunny.png" alt="bunny glitch" desc="chromatic aberration" %}
Also, there are draggers to adjust ratio of the chromatic aberration effect.
