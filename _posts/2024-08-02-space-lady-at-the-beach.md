---
title: Space Lady at the Beach
feed: hide
---
Greetings you grotesque gamer gooners.

I started working on this "early" on in the ZSS dev timeline, late summer 2021. I originally made a "Gris" swimsuit, but since I wanted to make something that could be actually used on a tourney stream, regular ol' swim suit it was. This design is very heavily inspired by (eg. almost entirely lifted from) Houshou Marine's swimsuit Live2D outfit, originally revealed July 29, 2021. 

That's right, this is a VTuber cosplay outfit and no one can stop me hahaha.

For your convenience, at the cost of my dwindling sanity, I have provided options for a customizable amount of stream safety consisting of the following (and their associated shorthand code):

- 4 different hair styles (P/B/Hd/Hb),
- a hoodie (Hc/Ho),
- a crop top (Shi),
- some shorts (Sho),
- a hat (if using ponytail) (H),
- and sunglasses (Go/Gu)

Please find the combination of codes that meets your level of family-friendliness out of the 180 different beachwear options. I do not expect this to run at a perfect 60fps in doubles or 4 man free-for-all, but should be fine for singles. The less she has on, the better she performs. *In theory*.

There is only one render scene made in the latest Blender 4.2 LTS. CSP2 style lights are included, but by default the scene is designed around CSP3.

Download
[Main Download](/assets/archive/ZSSBeach.zip) | [Color Atlas Template](/assets/img/Space-Lady-at-the-Beach/ColorAtlasTemplate.png)
[Premade Renders pt. 1](/assets/archive/ZSSBeach-Render.7z.001) | [Premade Renders pt. 2](/assets/archive/ZSSBeach-Render.7z.002) | [Premade Renders pt. 3](/assets/archive/ZSSBeach-Render.7z.003)


---
# July 2021
I started Beach Samus by modeling out her feet. Honestly, it was probably the trickiest bit to not go overboard but still keep plenty of detail to look better than Pit's.
<img src="/assets/img/Space-Lady-at-the-Beach/Pasted_image_20240626052330.png" loading="lazy"/>

# March 2022
Around this time, I finish a basic import of the Gris swimsuit and what I called at the time "[Hot Girl Samus](https://www.youtube.com/watch?v=FbcLcSY2au4)". No where near ready to go, but it was working.

# May 2022
Naively, I think I'm done after finishing the bikini and adding the ability to color it in shader. (Hint: *I wasn't*)
<img src="/assets/img/Space-Lady-at-the-Beach/Pasted_image_20240626052820.png" loading="lazy">

# June 2022
One of my blockout poses ends up being one that would work well for Beach Samus. Not sure if I'll use it yet, but I'm thinking about it.
<img src="/assets/img/Space-Lady-at-the-Beach/Pasted_image_20240626053015.png" loading="lazy">

# May 2024
Seeing Golden Bikini Week on Twitter reminded me of Beach Samus, so I work up the motivation to plan the work out for the rest of the outfit.

# June 2024
I share Golden Week inspiration on CBM, but Nano deletes it.
<img src="/assets/img/Space-Lady-at-the-Beach/Pasted_image_20240626053728.png" loading="lazy">

Out of spite, and because it's funny, I post feet 
<img src="/assets/img/Space-Lady-at-the-Beach/Pasted_image_20240626053754.png" loading="lazy">

The next day I finish the mesh for the clothes, the hat, the sunglasses, and some accessories. The glows are separated meshes so that it is "easy" to do custom graphics on the hoodie.
<img src="/assets/img/Space-Lady-at-the-Beach/Pasted_image_20240626053848.png" loading="lazy">
<img src="/assets/img/Space-Lady-at-the-Beach/Pasted_image_20240626053901.png" loading="lazy">
<img src="/assets/img/Space-Lady-at-the-Beach/Pasted_image_20240626053926.png" loading="lazy">
<img src="/assets/img/Space-Lady-at-the-Beach/Pasted_image_20240626053956.png" loading="lazy">
<img src="/assets/img/Space-Lady-at-the-Beach/Pasted_image_20240626054003.png" loading="lazy">
<img src="/assets/img/Space-Lady-at-the-Beach/Pasted_image_20240626054011.png" loading="lazy">
<img src="/assets/img/Space-Lady-at-the-Beach/Pasted_image_20240626054016.png" loading="lazy">
<img src="/assets/img/Space-Lady-at-the-Beach/Pasted_image_20240626054025.png" loading="lazy">
<img src="/assets/img/Space-Lady-at-the-Beach/Pasted_image_20240626054100.png" loading="lazy">

The next day, I finish the accessories.
<img src="/assets/img/Space-Lady-at-the-Beach/Pasted_image_20240626054149.png" loading="lazy">

In the next few days, I texture the clothes and setup a coloring atlas. It's a different coloring method than the other outfits, but for the simpler look of basic ass clothes it works. Technically patterned cloth is also doable; just set the corresponding area on the Atlas to white and then just paint on the texture directly. You'll see this done on a few areas in the release.
<img src="/assets/img/Space-Lady-at-the-Beach/Pasted_image_20240626054247.png" loading="lazy">
<img src="/assets/img/Space-Lady-at-the-Beach/Pasted_image_20240626054253.png" loading="lazy">

I then added references to the hat in what I call the default look.
<img src="/assets/img/Space-Lady-at-the-Beach/Pasted_image_20240626054324.png" loading="lazy">

I make the horrible mistake of finding out Samus has big "boss bitch" energy with the alternate hair styles and I commit to using them.
<img src="/assets/img/Space-Lady-at-the-Beach/Pasted_image_20240626054406.png" loading="lazy">
<img src="/assets/img/Space-Lady-at-the-Beach/Pasted_image_20240626054412.png" loading="lazy">

I did a few exports with mats and did a tease in CBM.
<img src="/assets/img/Space-Lady-at-the-Beach/Pasted_image_20240626054445.png" loading="lazy">

All that's left is to export to *180* different pacs. My plan is to import every object at once in one master pac and then save copies after deleting some objects. This way I can make sure the shaders, materials, and textures, are the same.

More teases.
<img src="/assets/img/Space-Lady-at-the-Beach/Pasted_image_20240802221953.png" loading="lazy">
<img src="/assets/img/Space-Lady-at-the-Beach/Pasted_image_20240802222010.png" loading="lazy">
<img src="/assets/img/Space-Lady-at-the-Beach/Pasted_image_20240802222024.png" loading="lazy">
<img src="/assets/img/Space-Lady-at-the-Beach/Pasted_image_20240802222041.png" loading="lazy">

"Unfortunate for me" was a bit of an understatement.

# July 2024
I spent time during EVO weekend getting all of the pac files exported. Had to redo it partway through because of some mistakes that propagated through all the pacs. All that's left is to create the render scene.

I tried to get it all done by the end of the month, but with my love of procrastination, that wasn't happening. At least I can say I started the model polish in July, the last day of the month counts right?

# August 2024
I finished the polish and posing on the first. I decide to go with a new pose outright. 
<img src="/assets/img/Space-Lady-at-the-Beach/Pasted_image_20240802222147.png" loading="lazy">

One bit of fun was setting up toggles for all the different options, since frame permutations was not going to cut it.
Similar to the pacs, I had to redo the renders a few times because of a mistake that propagated it's way through the renders. They did get finished, but there are 1260 images. I can't be bothered to rename the files to match the renders so you'll have to figure that one out or just rerender the ones you need on the spot.
<video autoplay muted loop>
	<source src="/assets/img/Space-Lady/Screen_Recording_2024-08-01 023152_1.mp4" type="video/mp4">
	Your browser does not support the video tag.
</video>

It's still summer so this is still a period appropriate release right?