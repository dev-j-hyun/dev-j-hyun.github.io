---
title: Environment Mapping Project
role: Graphics Programmer
image: assets/image-sample.png
alt: Environment Mapping Project
tools: C++ | OpenGL | GLSL
asset-base: /assets/programming/reflection/
tag: graphics

caption:
  title: Environment Mapping Project
  subtitle: Skybox <br> Reflection & Refraction
  thumbnail: /assets/programming/reflection/thumbnail.png
  
video:
  title: Video
  url: https://www.youtube.com/embed/6Se4ASYQbE8
  detail:
    - title: Environment Mapping
      desc: "- Blending: Phong <-> Environment Mapping Sliderbar : The ratio of combination of two colors (phong shading and environment mapping). 0 means only shows phong shading color and 1 means only shows environment mapping color.
        <br> - Environment Mapping Mode  : You can choose three mode for the environment mapping. Check the box which you want to do. If both 'Reflection' and 'Refraction' checkbos checks, it means using combination of both using the frensnel approximation.
        <br> - Reflection Material dropdown : You can choose the material for the refraction. If you choose the user define material in the dropdown, the slider bar appears so that the index value can be changed.
        <br> - Frensel Power Sliderbar : You can change the frensel power value. The default valus is 5.
        <br> - Chormatic Aberraion Drag bars: The ratio for the chormatic Abberation. The first drag bar indicates red, the second one is green, and the third one is for blue value."

detail:
  - image-path: blend-phong.png
    alt: phong shading
    desc: phong shading
  - image-path: blend-middle.png
    alt: blend environment mapping and phong shading
    desc: blend environment mapping and phong shading
  - image-path: blend-environment.png
    alt: environment mapping
    desc: environment mapping
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

{% include custom/gallery title="Detail" id="detail" desc="This is a environment mapping project." %}