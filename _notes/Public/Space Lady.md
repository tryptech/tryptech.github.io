---
title: Space Lady
feed: hide
---
TL;DR:
Dolphin Download | Wii Download

What originally started as a retexture in 2020 and an entirely separate optimization project in 2020 ballooned into ~100 days of work spread over 6 years, ~2.5 GB of files, done in the in between late night moments between 4 jobs. I've learned a lot of thing about 3d modeling and Blender along the way. I enjoyed teaching what I learned via streaming, but then grew a dislike for the ritual of it all. I grew bored of it, and with that boredom came periods of lethargy where I didn't want to think about this project, and where I forgot it even existed at times. But keeping other creatives around with plenty of other projects cooking helps to kick you back into gear eventually. And with the release of a certain v3 *not counting some other v3s I've neglected*, we have crossed the finish line. At least for now. This is the devlog on how this set of costumes came to be.

---
# 2020
I start working on a basic ass retexture of SJSuit ZSS to match the Samus Returns concept art. No screenshots from this period survive.
# June 2020
The original design goals were:

- Reference SR concept art as much as possible,
- Stay within the ballpark of SJS ZSS

The earliest surviving screens I have (rip gfycat) did not look good, and I somehow thought it was okay to call done, and there were ***a lot*** of times I thought I was done; thank goodness I kept working on it.  

![](/assets/img/test.mp4 "")
![](/assets/img/Pasted_image_20240626004038.png "")
![](/assets/img/Animation19.gif "")
![](/assets/img/Pasted_image_20240626004425.png "")
*All of these were around Summer 2020, this is what the ZSSv3 concept was originally was going to release as, but with all of the revision what ended up releasing might as well be called 3.5, or even 4.0*

At the very least, the different colored sections and the textures used for each material technically survived into the final version, but since I had to redo the body mesh anyway, and that had to get the relevant textures projected to new UV maps, nothing was left untouched from back then.

If you take a look at the [ZSS concept art from the MSR artbook](https://metroid.fandom.com/wiki/Zero_Suit/Gallery?file=MSR_Artbook_Zero_Suit_Samus.jpg#Metroid:_Samus_Returns), you'll find that she's both A) muscular, and B) double-cheeked up on a Thursday afternoon. So I added another goal to the list:

- tastefully **THICC**

Naturally, I also used some of the classics for reference, Chun-li and Cammy. But I did end up having to tone it down: a larger waist and smaller chest (still larger overall than SJSuit), thighs not clipping into each other, etc.

# November 2020
By the end of the year, I had found the time to get most of the reproportion done and I was feeling much better about it then. It felt less lanky, and the significant increase in mass around her core and hips made sense with how I utility-focused I imagined her muscles were.
![](/assets/img/Pasted_image_20240626004619.png "")

Once I had the final proportions locked in, I started working on the alts Fusion, ZM, Chozo/Training, and Super soon after in that order.

![](/assets/img/Pasted_image_20240626004807.png "")
![](/assets/img/Pasted_image_20240626004820.png "")
![](/assets/img/Pasted_image_20240626004911.png "")
![](/assets/img/Pasted_image_20240626004931.png "")

# December 2020
By the end of the year SJS jumped on to do the textures for the alts. I did the modeling, gave him a base skin texture to detail (yes, I have a fully body skin textured ZSS) and the modeling and texturing of the bodies could have been considered complete by the end of 2020. All that was left was hair, and then all of the other technical nonsense like rigging and optimization.

In my explorations on how to approach new hair, I tried a few things, like using the Alucard assist trophy from SSBU as a point of reference, 
![](/assets/img/Pasted_image_20240626005756.png "")
debated short hair,
![](/assets/img/Pasted_image_20240626005830.png "")
and went many different ways for hair ideas.
![](/assets/img/Pasted_image_20240626010018.png "")
![](/assets/img/Pasted_image_20240626010035.png "")
![](/assets/img/Pasted_image_20240626010045.png "")
![](/assets/img/Pasted_image_20240626010050.png "")
![](/assets/img/img.webp "")

Eventually I settled here for the hair used for Super and most of the alts:
![](/assets/img/Pasted_image_20240626010435.png "")
![](/assets/img/Pasted_image_20240626010445.png "")
![](/assets/img/Pasted_image_20240626010500.png "")
![](/assets/img/Pasted_image_20240626010504.png "")

And just like that, I remeshed the hair, and had a poorly optimized, untextured hair model to wrap up 2020.

---
# January 2021
In 2021, I took about a month going back and forth about how to do teased and feathered late-80s/early-90s hair, but I ultimately gave up on the idea and just went with a slicked back design that was somewhat common in the time period of the first Metroid game, and wouldn't be too bad to model out with abusing hair cards.
![](/assets/img/Pasted_image_20240626011142.png "")

I spent some time working on the UVs, textures, and materials for the hair and came up with a way to fake an anisotropic effect on the hair. I'm particularly proud of this extremely subtle detail. And with that being wrapped up, I shelved work on ZSS while I wasted my time away on other things while waiting on SJS to finish the Chozo/Training and skin textures ![](/assets/img/Pasted_image_20240626011347.png "")

# June 20201
5 months go by. I start a new job. I quit that job and start another job. Monster Hunter Rise becomes my time sink. Eventually in June I get back to working on ZSS again. Here I came up with the preliminary simple recolor node setup.
![](/assets/img/Pasted_image_20240626012157.png "")

In doing so, I end up adjusting the lighting and shadows of my auto texturing process to account for different colors better and it is at this point the tones of the texture are generally locked in. Here's a before and after:
![](/assets/img/Pasted_image_20240626012345.png "")
![](/assets/img/Pasted_image_20240626012357.png "")

# July 2021
I tweaked the holster to add a 3rd strap. My thinking at the time was that SJSuit had 2 straps being the v2 for ZSS, so I should have 3 for v3.
![](/assets/img/Pasted_image_20240626012533.png "")

# August 2021
I started doing minor tweaks here and there leading into August. After a basic skinwrap of the base mesh, I made adjustments here and there on the rigging and scaling of parts to clean up certain key poses in her animations. I upped the polycount on her assets to make them more round and less blocky.
![](/assets/img/Pasted_image_20240626013108.png "")
![](/assets/img/Pasted_image_20240626013328.png "")

By this point we went from piss poor effort to reasonably Brawl 2, the thicc-ening.
![](/assets/img/Pasted_image_20240626013249.png "")
![](/assets/img/Pasted_image_20240626013255.png "")

Unfortunately, my quest for fidelity led to some insane numbers.
![](/assets/img/Pasted_image_20240626013422.png "")

It was difficult to cut it down to achieve good performance on a Wii and keep everything I wanted: clean smooth silhouette, reasonable/non-extreme deforms in animation, fancy shader details that no one would notice. And so not wanting to compromise, ZSS work goes on another hiatus.

# September 2021
SJS finishes up the skin texture I can use for reprojecting.

# December 2021
I remember that I still have to do the textures for JB/Retro and so I decide to mostly reuse what I did for v3 and and just use different color block sections to make it.
![](/assets/img/Pasted_image_20240626013911.png "")
![](/assets/img/Pasted_image_20240626014049.png "")

I remembered how Sm4sh did their hair textures for ZSS and I get inspired to do the same. Her new hair is textured on a trim sheet of hair that tiles seamlessly, so all of her hair UVs are aligned vertically to have the hair detail make sense. I then compressed the texture vertically since the UVs will stretch it out long enough that any loss of vertical fidelity is unimportant.
![](/assets/img/Pasted_image_20240626015035.png "")
![](/assets/img/Pasted_image_20240626015059.png "")

SJS and I finally get the Training/Chozo texture done, and I finalize the recolors for JB/Retro as we head into the New Year thinking I'm done with all of the model and texture work.

---
# 2022
Sometime around here we decide to have ZSS coincide with the balance patch so the increased hurtbox lines up with the notably larger model.

# May 2022
We start testing ZSS for rigging errors and optimizations. SJS finishes the boot textures so they aren't boring.

# June 2022
I get a reminder of the v1 ZSS alts.
![](/assets/img/Pasted_image_20240626015721.png "")
Thankfully we're in the 2020s now.

I also do a Gris Swimsuit ZSS since it's relevant at the time, but since this ZSS wasn't out yet at the time, it remains hidden away in the vault of my computer.

# July 2022
I get the pose done for v3 and it's kinda accidentally the hardest thing I've done yet (as in this pose goes so damn hard). I was originally going to use this for Fusion, but the boys Xen and Flam talked me into using it for default, so here we are.
![](/assets/img/Pasted_image_20240626020122.png "")

I originally wanted to use this one which (if memory serves) I shamelessly lifted from Overwatch/D.Va, but this is now lost in my files somewhere
![](/assets/img/Pasted_image_20240626020429.png "")

And I blocked out this pose when I considered unique poses for the semi-alts, which ultimately became Fusion's pose.
![](/assets/img/Pasted_image_20240626020735.png "")

JB/Retro also gets a cute, sassy pose that I think fits the 80s/90s period I'm aiming for.
![](/assets/img/Pasted_image_20240626020323.png "")

I also do CSP3 renders and honestly, they came out so good, I rethought the approach to CSP3 altogether. *(Unfortunately CSP3 is still my Half-Life 3)*

Console testing showed that these were still far from release in terms of deformations, especially when I tried simplifying the rigging for better performance
![](/assets/img/Pasted_image_20240626020851.png "")

Apparently, this was also an issue with the old ZSS models, but the significantly lower poly count did not exacerbate the issue unlike my new dense meshes.

Some design pushback from dev around this time also made me exasperated the hell out of me since the console testing issues have been wearing me down.

# October 2022
I added very slight definition to the abs so the belly button doesn't feel too high and to add some detail to that area of the model, even if only slightly.
![](/assets/img/Pasted_image_20240626030617.png "")

The first ZSS Art+ goes out. Little did we know the ride we were in for.

# November 2022
I finally decide to do some model nerfs for performance and quality. I only nerf the cheeks since there's a lot of deformation there so the less mesh density, the better.
![](/assets/img/Pasted_image_20240626021642.png "")

I couldn't reduce chest too much since it ruined the straight lines I had made on v3 and JB/Retro. That, and the chest is all bound to one bone anyway so it wouldn't have helped performance much.
![](/assets/img/Pasted_image_20240626021726.png "")

---
# May 2023
After recovering from the burnout from having a finished model but it being too laggy to be finished, I manned up and remeshed, reweighted, and repacked every single model; I redid all of the renders to account for any notable model changes, and I adjusted Super since apparently the old mesh was too close to having a repeat of the 2B butthole rumor. I also started to get aggressively snarky in response to feedback at this time since I was feeling a bit fed up with the whole process.

Also I still took the feedback seriously and added fingernails to every model and figured out where to squeeze the unused toe nail textures on the existing UVs as the nail textures.
![](/assets/img/Pasted_image_20240626030815.png "")

# October 2023
I go over every model and render to find where I missed adding the fingernails in.

SJS makes a pair of eye textures.

# November 2023
We go over every asset used in making this new ZSS to determine who to credit.
Turns out, everything old remaining was done by SJS. Everything new is just me and him.

I also remake the recolor baking blends to clean/simplify them.

Filesize is an issue so we shrink textures down, but we need to find other optimizations. We try to use as many mipmaps as possible to improve performance. And the glows get separated out into their own models.

With how much iteration I have to do to get an acceptable compromise between performance and quality, I end up adding functions to Brawl Render Toolkit just because of this. 

# December 2023
Layell does face object optimizations.

I remove one of my pride and joy, the hair fake anisotropic specular from the shader, as well as simplify the body shader to help performance.

I severely nerf the mesh density of the new hair.

# April 2024
tyle and AZ try their hand at optimizing for performance and filesize.

Going off of their attempts at optimization, I redo my optimization from scratch, nerfing materials, textures, and shaders as much as I can to just hit a stable 60fps on Wii.

I separate out and simplify the eyelash texture on the models that have new hair.

A lot of the optimization broke the mats/shaders so I had to again redo them to fix the issue.

At this point, I separate out these optimized versions as Wii versions since they are so scaled down to what I originally wanted. Dolphin reverts back to pre nerfs since any computer running P+ on dolphin at a stable 60fps can handle it.

I spend the rest of the month tweaking small things like gaps, clipping, and weird normals.

# May 2024
At this point, I am once again burnt out on the hyperfixation of extremely minor issues with the model.

But we're at the finish line and I clean up the metal materials, and call it a day.

# June 2024
The second and third ZSS Art+ post go out. What a time gap, huh?

As of writing, I don't think anyone has anything bad to say about the new ZSS. At least publicly. Reception is good. All that's left is to write up the devlog.

---

If you made it this far, I thank you for taking the time to follow my loss of sanity as I get hyperfixated on and then get annoyed and frustrated on the hyperfixation of a certain alien-hybrid space lady.

Dolphin Download | Wii Download