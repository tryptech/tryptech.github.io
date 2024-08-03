---
title: Space Lady at the Beach
feed: hide
---
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

Download

---
# July 2021
I started Beach Samus by modeling out her feet. Honestly, it was probably the trickiest bit to not go overboard but still keep plenty of detail to look better than Pit's.
<img src="/assets/img/Space-Lady/Pasted_image_20240626012631.png" loading="lazy"/>

# March 2022
Around this time, I finish a basic import of the Gris swimsuit and what I called at the time "[Hot Girl Samus](https://www.youtube.com/watch?v=FbcLcSY2au4)". No where near ready to go, but it was working.

# May 2022
Naively, I think I'm done after finishing the bikini and adding the ability to color it in shader. (Hint: *I wasn't*)
![[Pasted image 20240626052820.png]]

# June 2022
One of my blockout poses ends up being one that would work well for Beach Samus.
![[Pasted image 20240626053015.png]]

# May 2024
Seeing Golden Bikini Week on Twitter reminded me of Beach Samus, so I work up the motivation to plan the work out for the rest of the outfit.

# June 2024
I share Golden Week inspiration on CBM, but Nano deletes it.
![[Pasted image 20240626053728.png]]

Out of spite, and because it's funny, I post feet 
![[Pasted image 20240626053754.png]]

The next day I finish the mesh for the clothes, the hat, the sunglasses, and some accessories. The glows are separated meshes so that it is "easy" to do custom graphics on the hoodie.
![[Pasted image 20240626053848.png]]
![[Pasted image 20240626053901.png]]
![[Pasted image 20240626053926.png]]
![[Pasted image 20240626053956.png]]
![[Pasted image 20240626054003.png]]
![[Pasted image 20240626054011.png]]
![[Pasted image 20240626054016.png]]
![[Pasted image 20240626054025.png]]
![[Pasted image 20240626054100.png]]

The next day, I finish the accessories.
![[Pasted image 20240626054149.png]]

In the next few days, I texture the clothes and setup a coloring atlas. It's a different coloring method than the other outfits, but for the simpler look of basic ass clothes it works. Technically patterned cloth is also doable; just set the corresponding area on the Atlas to white and then just paint on the texture directly. You'll see this done on a few areas in the release.
![[Pasted image 20240626054247.png]]
![[Pasted image 20240626054253.png]]

I then added references to the hat in what I call the default look.
![[Pasted image 20240626054324.png]]

I make the horrible mistake of finding out Samus has big "boss bitch" energy with the alternate hair styles and I commit to using them.
![[Pasted image 20240626054406.png]]
![[Pasted image 20240626054412.png]]

I did a few exports with mats and did a tease in CBM.
![[Pasted image 20240626054445.png]]

All that's left is to export to *180* different pacs. My plan is to import every object at once in one master pac and then save copies after deleting some objects. This way I can make sure the shaders, materials, and textures, are the same.

# July 2024
I spent time during EVO weekend getting all of the pac files exported. All that's left is to create the render scene.