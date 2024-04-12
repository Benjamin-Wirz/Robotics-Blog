---
title: "Week 29"
date: 2024-04-12T14:12:14Z
draft: false
---

Today was another shortend week, but I kept going with my propeller. This week so far I figured out how to do a rotating region analysis, which is how you are actually supposed to do these sorts of simulations. Instead of rotating the actual propeller geometry, it rotates a set region of the water around the prop. I have no idea why they do this, but they do. 

{{< figure src="/img/Week29/Week29Pic1.png" alt="rotating region analysis " position="center" style="border-radius: 8px;" caption="This is the demo rotating region analysis from Autodesk, the red is the fluid that is being rotated around the geometry being tested." captionPosition="left" height="1080" width="1920" >}}

Unfortunatly Autodesk CFD does not have an easy way to calculate thrust from the prop, but you supposedly can calculate it fairly easily. I disagree. Using a wall calculator it is pretty easy to find torque, which is one main part of the effeciency equation from last week. To find thrust, it is much more difficult, as you need to us a bulk plane calculator, which of course does not want to work for me. I also have no idea what they mean by some of the variable in the equation, so that will be fun to figure out. 

{{< figure src="/img/Week29/Week29Pic2.png" alt="Thrust Equation" position="center" style="border-radius: 8px;" caption="Here is the thrust equation that I found on the Autodesk forums. Unfortunatly I cannot figure out how to get any of the values inside the parenthesis." captionPosition="left" height="1080" width="1920" >}}

Float side, all of the hardware is done for the time being, but electronically we are still chugging. We have a pretty promising setup so far, that should theoretically work while not catching on fire. Yesterday I soldered up the board, and today we will test it on the bench. 