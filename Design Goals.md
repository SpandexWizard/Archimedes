---
layout: default
title: Design Goals
nav_order: 2
---


so what makes my baby magic? well nothing yet! but here's my plans for physical features, and software features
- a tented keyboard with a solid base
- a vertically dished set of keys
- a horizontally DOMED set of keys
- vertically staggered keys
- a trackball.
- a scrollwheel, to go with that trackball.
- a 'mouse layer' that activates when you move the ball.
- something that's NOT a trrs cable to connect them.
- a layer with a full numberpad
- arrowkeys that are arrowkeyshaped. LOOKING AT YOU ERGODOX
- a thumbcluster with buttons useful enough for me to remember them
- consideration for blender/other software hotkeys
- feel like a gundam pilot

Tenting is important to match the natural twist of your hand. with most ergonomic keyboards, I feel the tenting is either too subtle and useless, or way WAY too much. It's going to take some trial and error to find the right ammount of tenting. I'm pretty happy with the model as it sits, but it may need adjusting. to this end i want the key grid as a seperate part from the frame, allowing for all the wiring to be left alone when and if i change bases. (a feature already implemented <3) 

By vertically dished keys, I mean that the rows curve towards homerow, upoff the table. This moves them closer to homerow and limits extension of the digits, and, I think, allows for a stronger push with less effort, since you will be pushing more 'straight at the key'. The ammount of curve on the keyboard is subtle, with perhaps a 10-12 inch diameter. 

Horizontally domed keys are the opposite of this. This means the center of either half of the keyboard rises higher than the left and right edges. I find that my hand naturally cups, and that a 'round' shape is both comfortable and gives a sense of control. The keyboard will slide around less if your hand is holding it in place like a ball, from all sides so to speak. 

Vertically staggered keys are pretty self explanitory. Some fingers are longer than others, and moving those fingers' columns forward will allow them to have a more relaxed position. 

A trackball; this wasnt super important to me, but soemthing I've always considered interesting. Plus, i've seen so many of them that just look COOL. so while it's an expensive and probably VERY tricky system to impliment, I'm going to try! The more i work on this system, the more the trackball becomes a need and not a want. being able to hit hotkeys without taking my hand off my mouse is a big deal for me.

A scroll wheel is pretty self explanitory. If there's one big flaw to trackballs is that the scroll wheel has become so important to modern computing. A mouse without one is basically useless. I'd love to make one that includes the middle mouse click, but that's pushing things a bit far. Getting my hands on a mouse encoder is pretty simple, and I'll start there. 

I've seen some pretty nifty things done with the trackball involving mouse layers, and those are useful, I think. To summerize, you want any motion of the ball to trigger the Mouse Layer, allowing you to click without moving your hand and without wasting valuable key space to dedicated keys. You also want this mouse layer to knock it off when it's time to go back to using the keyboard. At it's easiest, a 'home layer' button would allow one to rapidly return to typing, but some kind of smart un-mouse-layer programming might be better? I can imagine it getting pretty complex though ((turns out, qmk already has a feature like this built in that is pretty robust. nice!))

The Connector is honestly a big deal. Hotswapping is a bad idea in general, but accidents happen, and this keyboard is not cheap. The last thing I want is to fry my board because the cable got yanked out. Plus other options look bulkier and more 'professional'. 

A layer with a numberpad is a MUST. The number of times I've been unable to fully utilize a software because it needs a proper numberpad is crazy. And some, like blender, REALLY rely on those keys.

Arrowkeys are more of a gripe about my current setup than anything else. I've been using an ergodox for about two years now, and I dont often need arrow keys, but when I do, it's hell. combining the numberpad layer with the arrows layer may be efficient. wsad for arrows, numbers on the right hand. 

Again an ergodox fueled complaint, but i cant even remember what six of my thumb keys DO, because they're really weird to reach. Ensuring that they are reachable and useful is a big deal, otherwise it's wasted space and keys. 

I use blender heavily, and somewhat professionally, and that means a LOT of hotkey usage. So much hotkey usage in fact that having anything less than a full keyboard is often not good enough. Newer versions of the software have alieviated these concerns somewhat, but the fact remains that they are a problem, and it's not just blender. I want to put consideration into what keys I actually need, and not skimp just because it's popular to trim out as many as possible. Layers are a good alternative to extra keys but if I just need one more key, I should have that one more key. 

and the most important consideration: It needs to transport me into the cockpit of a gundam. These keyboards have the potential to be REALLY cool. IT MUST BE COOL.

***
Inspiration:

A big BIG inspiration for me is the Tractyl ManuForm, by NoahJoseph
<img src="https://preview.redd.it/t2uywp1p19u51.jpg?width=960&crop=smart&auto=webp&s=edf70e68aaf49736964815766064eba41228f066" alt="a picture of the Tractyl ManuForm, a split ergonomic keyboard based on the Dactyl ManuForm with trackball and built in wrist rests.">
I mean LOOK at it! THIS is what I mean by a Gundam Pilot.
read more about the Tractyl here: <a href="https://www.reddit.com/r/ErgoMechKeyboards/comments/jep7c0/tractyl_manuform_dactyl_with_builtin_trackball/">Reddit</a> <a href="https://github.com/noahprince22/tractyl-manuform-keyboard">Github</a>

The Tractyl features dished keys, a trackball, quality tenting. It's nearly perfect. But there's things I'd change, to make it mine. I'm not sold on the thumb cluster, and I'd prefer the trackball look a little more elegant, though it's design is honestly one of the things that makes me think of techy mecha. There's also features that I consider extra, like the hot swap sockets. I dont expect to be replacing keys very often, if ever, so that's just a headache I can avoid. 

The Track Beast, by Dave Kincade.

<img src="https://miro.medium.com/max/1000/1*oaMaxPbLVWpIVhx8sOfnIQ.jpeg" alt="a picture of the track beast, a modified dactyl manuform">

This is what I mean by elegant! look at that puppy and tell me it doesnt scream 'space elves built me'. the bright colors are also attractive. 
read about it here: <a href="https://medium.com/@kincade/track-beast-build-log-a-trackball-dactyl-manuform-19eaa0880222">Medium.com</a>

The Oddball, by atulloh
<img src="https://atulloh.github.io/oddball/assets/images/gallery-v2-small-6.jpg" alt="a picture of the oddball, a custom split keyboard with a trackball and minimal keys">
The oddball honestly was the last push to try this crazy trackball thing out. They use a smaller ball and it just seems to sit there. I'm unsure if it is actually sealed in place or not, but it seems to work well and after so many keyboards with trackballs in them I have to give in and give it a go.
read about it here: <a href="https://atulloh.github.io/oddball/">Github</a> 
the oddball is also what convinced me to document my build, and yes I AM stealing their theme even. guilty.

The Lime40, by eucalyn
<img src="http://xahlee.info/kbd/idiy/lime40_keyboard_qjd4d.jpg" alt="">
<img src="http://xahlee.info/kbd/idiy/lime40_keyboard_wheel_2021-02-07-s850.jpg" alt="">
Honestly I dont know a lot about this one. Finding a source on it is difficult, but it does a LOT of things I like. In fact Archimedes is probably most heavily based on this keyboard. the tenting is perfect, the dishing and domeing and staggering are great. the only problem for me is that the thumb clusters are WAY too close to the rest of the fingers. the lime40 was meant for people with small hands and that's the exact opposite of my problem. I also want more keys. At least one model includes a thumbwheel that likely functions the same way I'd want mine to. There's a lot to love about this machine.
