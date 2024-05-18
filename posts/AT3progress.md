---
title: Assignment 3 Progress
published_at: 2024-05-18
snippet: The process and challenges I faced throughout AT3
disable_html_sanitization: true
---

During the brainstorming process I was interested in creating an environment that portrayed the feeling of the change, rather than visually representing it. This lead me to think about symbolism and how I could imbue an emotional experience for the player through the progression of the environment. 

The change I decided on was getting more independent, and how it can be uncomfortable or scary. I plan to represent this in my environment by starting out the front of a comfortable, reassuring feeling house and by slowly getting further away there appears to be less human influence until you are alone in the forest. Later in the production I decided that there should be a hopeful ending as being independent is ultimately a good thing, regardless of how unprepared you feel at the time. This manifested in the fireflies at the end.  

I started with a square terrain in unity and just began messing around with the terrain options, trying to parse out what I am capable of making within unity. As you can see i also played around with the tree painting capabilities and ended up making a super rough prototype of an environment similar to my aim. 

![testing](/AT3progress/play.png)

I then moved on to creating a fresh unity file and made a small greybox prototype outlining where fundamental aspects of my environment will be, for me these boxes represent the bridge, the wall, the campfire, and the ending location. 

![greybox](/AT3progress/greybox.png)

At this point I started adding more details to begin turning my greybox into my actual environment. In the images you can see that I lowered the terrain to make a river and filled it with a transparent plane to simulate water. I also started downloading my assets and adding them in, like the trees (Accreditation at the end). I discovered when placing the trees I could switch the perspective mode from ‘persp’ to ‘ISO’, this made it easier for me to visualise the placement to help make it more natural and random. 

![river and trees](/AT3progress/repl.png) 

Then I replaced most of the grey boxes with their counterparts, as seen with the campfire, and the wall I built out of various 3d objects and probuilder assets. In the wall image you can also see that I had added a grass texture to the terrain (I end up changing to a different one later) and placed a random smattering of trees. The two kinds of trees are on either side of the wall, and help to represent the change I am trying to portray. 
The trees at the beginning are more rounded in form, helping to evoke a more organic and welcoming feeling, compared to the end where the trees are of an angular form, which may convey a sense of danger or unpredictability. 

![campfire](/AT3progress/camp.png) 

As I started to add materials to my objects, I started to notice that the pattern would expand as the shape did. This can be seen in the stone wall that I built out of a few different shapes. To fix this problem, I duplicated the material and made the ratio smaller on the texture that was on the larger objects. 

![wall](/AT3progress/wall.png) 

Decorating the starting area I added warm coloured lighting to create a more comfortable feeling. I discovered that colouring the lights with a material that has an emission as well as adding a light source to them helps to bring focus to the colour more. 

![light](/AT3progress/fairyL.png)

Another problem I faced was scale, after playing around in the game window for a while I realised that a lot of the structures I had built were not to scale with the size and viewpoint of the player camera. To solve this, I started to scale down the house individually but ultimately realised I could just scale up the player asset. 

![small](/AT3progress/scale.png)

Trees were also a struggle, I had planned to use the tree painting tool within the terrain menu but it ended up adding the trees very small, and tiny. I tried a few different ways to hopefully rotate and enlarge the trees, however in the end I had to just manually place them around the terrain as nothing was able to fix it. 

![paint tree fail](/AT3progress/tree.png)

At this point I started looking into sound, I wanted to have two different atmosphere sounds as the player moves between the spaces as well as more localised noise coming from objects. I found atmosphere/foley sounds from freesound.com and music for the radio on youtube audio library (Accreditation at the end). The music is coming from an old style radio, so I used Adobe Audition to add an ‘old time radio’ effect. For the object noises I just added audio sources to said object and adjusted the minimum and maximum distances. The atmospheric noises I added audio sources at either end of the terrain and made sure the distances maintained within each side. I made sure all of the audio loops so it'll keep playing despite how long is spent in each area. 

![sound](/AT3progress/sound.png)

Creating the different time zones was more difficult than I anticipated, as there can only be one directional light which I was using for the brighter section. This meant that that light had to be consistent throughout the terrain. To overcome this problem, I added two cubes with the lighting setting set to ‘shadows only’ which essentially made two invisible curtains that blocked all light from hitting the second side of the terrain. To simulate the moon I then added a ‘point light’ and coloured blue-ish and angled it so the shadows had similar angles on both sides. 

![lighting](/AT3progress/blockmoon.png)

I used particles throughout the second half of the terrain to help enforce my creative intention. I found the fog made the biggest difference in the atmosphere, adding to the unsettling feeling. Using particles for fog was a work-around I found as the inbuilt unity fog system cannot be localised to a certain section of the terrain. The firefly particles are warm coloured in the very cool toned second half of the environment, this colour difference and inherent wonder that comes with fireflies helps to cement the idea of hope or a light at the end of the tunnel. 

![particles](/AT3progress/particles.png)

**Attributions**
Stylized bush by Daniel - License: Creative Commons - https://sketchfab.com/3d-models/stylized-bush-9d9ce79d3ae040619e96d5b22c7de1a6

stylized tree by Daniel - License: Creative Commons - https://sketchfab.com/3d-models/stylized-tree-8daa312234f04a59a216682981af500d
Pine Tree low poly by daniel.2U - License: Creative Commons - https://sketchfab.com/3d-models/pine-tree-low-poly-9cde1025662e4954b1f803c2d4bb719d

Low Poly Campfire by Gudson7 - License: Creative Commons - https://sketchfab.com/3d-models/low-poly-campfire-4d0e13c9b7da40958233b4a551e30522 

Garden Bridge by Anthony Monteagudo - License: Creative Commons - https://sketchfab.com/3d-models/garden-bridge-617cead9ee214a07bfb70b45bf246524

Door by Dogukan - License: Creative Commons - https://sketchfab.com/3d-models/door-35b291c862c04beb8827b1364922ddb0

Saloon Window by michaelroe - License: Creative Commons -  https://sketchfab.com/3d-models/saloon-window-2b83a203232c4ff8a3d59946816066e3

Fairy Lights by freshlybaked - License: Creative Commons -   https://sketchfab.com/3d-models/fairy-lights-6167832a8ea04d0bb637315b45fb2d72

Used tire / tyre by SusanKing - License: Creative Commons - https://sketchfab.com/3d-models/used-tire-tyre-5292252ccddc48019db1b60939020473

Rope by svyART - License: Creative Commons - https://sketchfab.com/3d-models/rope-6429ddecad104f13b45b17062ccb9ed8

Grass Patches by Mitro123 - License: Creative Commons - https://sketchfab.com/3d-models/grass-patches-c6efcb806d894f0fbda098563f170f74

Rock Grouping 14 by BenjiToddArtist  - License: Creative Commons - https://sketchfab.com/3d-models/rock-grouping-14-94c54803bbc0458c8406ca70baccd3e9

Simple picnic table by UlissesVinicios - License: Creative Commons - https://sketchfab.com/3d-models/simple-picnic-table-629fd23c112a4e79ab8470b3e0d2e2b7

Lanterns lowpoly models homework 11 by Bansheeva - License: Creative Commons - https://sketchfab.com/3d-models/lanterns-lowpoly-models-homework-11-e7d36f6ce9824228b787204591f6f356

Road Sign Stylized by Mr. Compotchino - License: Creative Commons -   https://sketchfab.com/3d-models/road-sign-stylized-b4fd747e143e432695edacfcc1d7785c 

PBR Log by EC Developer https://assetstore.unity.com/packages/2d/textures-materials/wood/pbr-log-149788#description

WoodTile Textures Pack by 1441 GAMES https://assetstore.unity.com/packages/2d/textures-materials/wood/woodtile-textures-pack-30049

FREE Stylized PBR Textures Pack by Lumo-Art 3D https://assetstore.unity.com/packages/2d/textures-materials/free-stylized-pbr-textures-pack-111778 

large leaves rustle in the wind sound effect by Garuda1982 -- License: Creative Commons 0 -- https://freesound.org/s/575645/ 

Campfire (24 bit 44.1 kHz) by cagankaya -- License: Creative Commons 0 -- https://freesound.org/s/679007/ 

night_forest_owl.WAV by thom_cookes -- License: Creative Commons 0 -- https://freesound.org/s/475376/ 

ForestDay_BW.66.wav by sonidosreales245 -- License: Creative Commons 0 -- https://freesound.org/s/517042/ 

Mulholland, King Canyon, Youtube Audio Library License https://studio.youtube.com/channel/UCvxTYVHuT3V_EZc8vUpl7Rw/music 