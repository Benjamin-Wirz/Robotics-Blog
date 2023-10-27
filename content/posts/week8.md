---
title: "Week 8"
date: 2023-10-26T13:25:02-04:00
draft: false
---

This week the auger in the fish feeder broke. This meant I needed to fix it majorly, and not just reprint the auger. We eventually settled on reducing the length of the auger, by adding a bend in the pipe. This effctively reduces the torque on the auger as it doesn't have to be as long. Another measure I took to reduce the torque was to increase the diameter of the auger, as bits of fishfood were getting caught inbetween the auger blades and the inside of the pipe. Increasing the diameter should reduce this amount of torque altogether. To increase the strength of the auger I also epoxied the two halfs together. 

In much more exiting news I got the Autodesk CFD software working, and was able to do a test simulation. I did my initial tests on a NACA 2412 airfoil I modeled. Unfortuanatly Autodesk had a terrible set of tutorials for this software, so I found another [video](https://www.youtube.com/watch?v=nS9SfKLdkw4) that showed me how to do what I wanted. This was quite the test for the brand new workstation I was on, and showed that it was very very powerful. It was able to rip though 230 itierations in about a minute, which is insanely fast. I then kept following the tutorial on how to view the data that I just collected, which allowed me to create the image and video bellow. Now I will use this to do the same for JONA, and get data on how non hydrodynamic it actually is. In reality this won't really matter, as it is designed purely for manuverablility and won't have to go particually fast anywhere, or be particually efficient, as it gets power from the shore, however, this data is nice to put in our techincal documentation. 

{{< figure src="/img/Week8/Week8Pic1.png" alt="Plane of the CDF results " position="center" style="border-radius: 8px;" caption="Here you can see the side plane view of the test simulation. The results don't really make sense to me, but it still looks kind of cool." captionPosition="left" height="1080" width="1920" >}}

{{< youtube id="ZeI8upOrMGw" autoplay="true" >}}

I have since learned that this simulation was bad, as I didn't set the walls to slip, which heavily affected the results. I have since redone the simulation, and it makes much more sense. 
