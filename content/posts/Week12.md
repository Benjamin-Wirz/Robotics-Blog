---
title: "Week 12"
date: 2023-11-30T11:14:42-05:00
draft: False
tags: ["Float", "Resin", "Piston Seal", "Simulation"]
---

This week I started to work on the float again. At this point it was a lot more waiting for prints to finish, then testing them, then reprinting a new version. This meant that I had lots of downtime in the shop. With this time I did a little project for Mr. Christy. 

Mr. Christy is building a herb press that uses an 8 inch C clamp and a steel cup. This is all going to be welded to a steel baseplate. The problem occured when he needed to figure out how thick the baseplate needed to be to withstand the preasure. This was a fairly simple setup, just a static stress simulation, but required many solves, and geometry changes. We started by trying to find how much preasure one of the C clamps could exert, which turned out to be around 60000 newtons on the low end. I quickly realized that the baseplate would be the weakpoint unless we wanted to do some crazy thickness like 3/4". I started by finding the point at which it permanantly deforms and judged the different designs off of that. The design that we landed on was a 1/4" plate with two stiffening rods down the sides, which added over 1000 newtons to the force required to permanantly deform it. 

{{< figure src="/img/Week12/Week12Pic1.png" alt="Image of the simgulation" position="center" style="border-radius: 8px;" caption="This is the winning desing out of the 1/4 inch variations. I used the max psi to determine if the steel permanatly deforms or not." captionPosition="left" height="1080" width="1920" >}}

{{< figure src="/img/Week12/Week12Pic2.png" alt="Image of the simgulation" position="center" style="border-radius: 8px;" caption="This was the first version that I tested. As you can see it is very bent, and well past steels deformation preasure." captionPosition="left" height="1080" width="1920" >}}

Today Mr. Christy found the peice of metal that he is going to use. It is a 3/8ths plate, so it will be stiffer. This added about 2500 newtons to the amount of force it can withstand. 

{{< figure src="/img/Week12/Week12Pic4.png" alt="Image of the new simgulation" position="center" style="border-radius: 8px;" caption="Here is the new stress analysis results." captionPosition="left" height="1080" width="1920" >}}

The float is coming along well. I am pretty close to a good design for the O-ring geometry which I have been working on and off on for about 2 months now. 

{{< figure src="/img/Week12/Week12Pic3.png" alt="Image of o-oring test prints" position="center" style="border-radius: 8px;" caption="These are the prints that I use to test the orings. They are printed on our Form 3 resin printers." captionPosition="left" height="1080" width="1920" >}}
