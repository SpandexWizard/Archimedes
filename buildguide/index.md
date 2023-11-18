---
layout: default
title: Build Journal
nav_order: 3
has_children: true
---



I'll try to catalog the small changes to the design here until the shape of the keyboard starts to take shape. I imagine there's going to be a LOT of trial and error, particularly with the trackball.

V .01
<img src="https://raw.githubusercontent.com/SpandexWizard/Archimedes/main/archimedes%20v.01.PNG" alt= "">
the first attempt at getting the keys where I want them. I've 3d printed this layout (and lost the print...) and I like the key locations, but it leaves little to no room for the trackball. The keys may have to move to a less than optimal location to fit the ball. 

V .02
<img src="https://raw.githubusercontent.com/SpandexWizard/Archimedes/main/archimedes%20v.02.PNG" alt="">
the next step, trying to place the trackball. I really like the track beast's solution but the number of keys available leaves something to be desired, and I've never liked the manuform thumb cluster. Instead of peeling away from the thumb, I'd rather if it cupped, like a Dmote.

v .021
<img src="https://raw.githubusercontent.com/SpandexWizard/Archimedes/main/key%20plate%20v.02.PNG" alt="">
adjusting the number of rows and columns to match a 3x6. not sure if i will stagger the second pinkey row or not. maybe. might be fine where it is. 

V .03
<img src="https://raw.githubusercontent.com/SpandexWizard/Archimedes/main/archimedes%20v.03.PNG" alt="">
removed top row keys. will have numberpad layer, so they are probably unnessisary. I definitely need some extra side keys though, so that I can have a place for modifiers.
<a href="https://github.com/SpandexWizard/Archimedes/blob/main/stls/mockup%20v.03.stl">mockup v.03 stl</a>

v .04
<img src="https://raw.githubusercontent.com/SpandexWizard/Archimedes/main/archimedes%20v.04.PNG" alt="">
after printing out a mockup, i determined that the tenting was a tad too extreme for my comfort, and lowered it by 5 degrees. the trackball was moved a few milimeters to the right, and the thumb cluster rotated counter clockwise a bit, and moved to the right, to allow for a more comfortable touching of the buttons. testing the second mockup confirms an improvement. i'm not entirely sure it's perfect but it's not horrible. 
<a href="https://github.com/SpandexWizard/Archimedes/blob/main/stls/mockup%20v.04.stl">mockup v.04 stl</a>

v .05
<img src="https://raw.githubusercontent.com/SpandexWizard/Archimedes/main/archimedes%20v.05.PNG" alt="">
With the next update i decided i wasnt confident in the position of the trackball and felt that my control would be limited because of the angle of attack. Taking a tab from the defunct King's Assembly keyboard I tried placing the trackball where their thumbstick was. For me, it works very well.
<a href="https://github.com/SpandexWizard/Archimedes/blob/main/stls/mockup%20v.05.stl">mockup v.05 stl</a>

The Keygrid Physical parts
<img src="https://raw.githubusercontent.com/SpandexWizard/Archimedes/main/keygrid%201%20tree%20supports.jpg" alt="">
<img src="https://raw.githubusercontent.com/SpandexWizard/Archimedes/main/keygrid%201.jpg" alt="">
i've test printed the keygrid in petg using cura's tree supports and i have to say i'm damn impressed. the supports dont use a lot of material and they WORK. i've never gotten a keyboard part to print this clean before, even when i'm NOT printing petg. it's fantastic!

Archimedes V.09
<img src="https://raw.githubusercontent.com/SpandexWizard/Archimedes/main/archimedes%20shell.PNG" alt="">
<img src="https://raw.githubusercontent.com/SpandexWizard/Archimedes/main/archimedes%20v1.PNG" alt="">
it feels like things are moving so fast now. but that'll change when i get to software, i'm sure. i've almost finished designing the housing for the keyboard. all that's needed now is to add the trackball mount and it's ready for me to start fiddling with the hard stuff. i'm concerned about the pegs for the screws fitting into the holes, but that's a minor fix. as it stands? it looks SO good. maybe not gundam exactly, but ... MNN!

Archimedes V.09 Test Prints
<img src="https://github.com/SpandexWizard/Archimedes/blob/main/test%20fit%202.jpg?raw=true" alt="">
<img src="https://github.com/SpandexWizard/Archimedes/blob/main/test%20fit.jpg?raw=true" alt="">
i'm am a little late posting this, i printed these months ago. it came out pretty great but it also showed me i have things to fix, importantly the bearing holes are too small, and that means IF you can get a bearing in, it gets stuck and wont roll at all. conversely, the trackball slides in it like a dream. super awesome. 

Archimedes V.10
<img src="https://github.com/SpandexWizard/Archimedes/blob/main/v.1%20render.jpg?raw=true" alt="">
<img src="https://github.com/SpandexWizard/Archimedes/blob/main/exploded%20view%20right%20hand%20v.1.PNG?raw=true" alt="">
some adjustments to the existing features, and a LOT of new hardware points. the slot for the sensor is in place, as is the scroll wheel slot. screw holes have been added to all the small parts. i dont like cutting it up like this but it's the only way i get the scrollwheel where it belongs. we'll see how it looks once i print it... hopefully the screws keep the seams tight and it still looks professional. assuming this works out, this will be the last major revision! all that's left is to build a mount for the control board and sockets for the usb and connectors. 1.0 here i come!

Archimedes V.20
<img src="https://github.com/SpandexWizard/Archimedes/blob/main/rev%20.2%20a.PNG" alt="">
<img src="https://github.com/SpandexWizard/Archimedes/blob/main/rev%20.2%20b.PNG" alt="">
<img src="https://github.com/SpandexWizard/Archimedes/blob/main/rev%20.2%20c.PNG" alt="">
a pretty major setback led to a large design change. the trackball felt right for every mockup i made, and even the real deal, until i got it working and realized it was way too far to the left. it had to move, and that meant a major design rework. which has stalled a lot of my momentum... i'm back on track now, with a few compromises. moving the trackball means losing two of my thumb keys, which is a pretty heavy blow. i intend to get around these limits by making it so that the end and home keys, and the bottom layer/ layer up keys are the same key. a press for home, a hold for end. a tap for layer up, a hold for home layer.  

i've also realised that i never worked the windows and alt keys into my design properly, which is... a bigger problem. i can get creative with some of my keys, perhaps making a long press on esc be windows, but i use windows shortcuts quite frequently, and not having ready access to the windows or alt keys will be something that absolutely needs remedied. i'll think on it. maybe holding tab can be alt... i'm not sure yet. i may just end up adding two more keys to the left hand side so i can more easily use standard shortcuts. but it feels like cheating.  

then again. i kind of dig the asymetric vibe.  speaking of vibes, do SOMETHING about the trackball housing. it looks glued on. x.x
