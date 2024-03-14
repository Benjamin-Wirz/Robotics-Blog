---
title: "Week25"
date: 2024-03-14T11:37:54-04:00
draft: false
---

This week has been fairly uneventful, as all of the necessary float hardware stuff is done. Now we just have to make the elctronics work properly, and I have started a new branch of the Float. 

Last year for the science fair Scott and I decided to try and make an underwater glider, which did not work well, but we were still able to study different wing progile shapes. This topic has always interested me since then, as it blends what I am currently doing now, with the aviation side of me. this year I want to actually get the float to work as a glider. So far I have just started to focus on the wing hub, which I have specified a few design requirements. 

1. Modular Wings. I want to be able to decently quickly swap different airfoil shapes on and off, to allow for the research that we want to do. This shouldn't be too hard 
2. Angle Adjustability. I would like to be able to fly the glider while the main float tube is both horizontal and vertical.
3. Stable Flight Characteristics. This is to generally allow the float to be able to handle some instability in balance and still fly level. I am planning on acheiving this by biasing the wing towards the top of the tube while horizontal, which makes the angle adjustability a little more complicated. 
4. Complete independance. I want this to be a bolt on attachment to the float, allowing it to still act as float for competition and its normal profiling duties, but still have this capability.  

So far I have startd working on the mechanism that allows me to pivot the wings. This will be very similar to the ratcheting mechanisms that hold two discs with teeth on them together to hold position. This will give me the 90 degrees of rotation that I am looking for, while being quite solid. The other design challenge with this is to get the placement of the pivot point right so that the wing is above the centerline while horizonatal, giving us more stability, but still positions the center of lift in the correct spot for flying while vertical. 

{{< figure src="/img/Week25/Week25Pic1.png" alt="ratchet test" position="center" style="border-radius: 8px;" caption="Here is a test peice of the ratchet. It is wrong and I now need to redo the model so that it properly interfaces with eachother." captionPosition="left" height="1080" width="1920" >}}

On the actual float front we were planning on getting the float in the water, but nothing was really quite working correctly. The largest advance we made was to get the float software working on a laptop. 

{{< figure src="/img/Week25/Week25Pic2.jpg" alt="Computer setup" position="center" style="border-radius: 8px;" caption="This took way too long than it should have. We first started to do it on a windows computer, which was a royal pain, and didn't even work. We then switched to a Linux laptop, and it worked without fail." captionPosition="left" height="1080" width="1920" >}}