---
title: How to Bake
feed: show
date: 2024-06-26
notetype: unfeed
---
## Minimum Requirements:
- Blender 3.6.7+
- Modern dedicated graphics card (recommended)

<img src="/assets/img/How-to-Bake/Pasted_image_20240626155538.png" loading="lazy">
<img src="/assets/img/How-to-Bake/Pasted_image_20240626155112.png" loading="lazy">

## Steps
###### *Refer to the above screenshots*
1. If you have a dedicated graphics card, under Edit > Preferences, enable your gpu: CUDA for Nvidia GTX, OptiX for Nvidia RTX, HIP for AMD, oneAPI for Intel Arc.
2. Use the color pickers to customize the texture. Scrub along the timeline at the bottom to preview the texture on an animated model.
3. In the Shader Editor in the bottom left, click on the *output* Image Node to make sure it is selected.
4. In the 3D Viewport, click on the body mesh to make sure it is selected.
5. In the properties panel on the bottom right, click *Bake*
6. When the image is done baking, in the Image Editor in the top left, select *Image>Save As...* to save your texture.