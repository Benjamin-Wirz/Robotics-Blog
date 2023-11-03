---
title: "Week 9"
date: 2023-11-02T18:08:05-04:00
draft: False
tags: ["Float", "Resin", "Piston Seal", "Battery Holder", "Simulation"]
categories: ["Weekly Blog"]
---

This week I finally got the CFD software to play nice with the new ROV model. to do this I simply just took out all of the hardware in the model, as it was just to much for the CFD software to handle. With this simplified the simulation was able to run over the weekend... if my computer didn't lock itself. I had set it to not sleep, but forgot to set it to not lock. With this fixed it ran over night, and worked perfectly. Using this data I got many pictures, and with a rudementry calculation of the frontal surface area, got a rough idea of the drag coefficent, using wall calulations. According to my calculation the new rov design has a drag coefficeint of 1.4, worse that of a brick. This will not be the last simulation I will run, as this model didn't have the cameras or gripper on it, so therefore was quite inaccurate to the final ROV. Once the backwards facing camera is finish being designed, I can then run the simulation again, and get the proper results that we will use in the technical documentation. 

{{< figure src="/img/Week9/Week9Pic1.png" alt="Picture of traces" position="center" style="border-radius: 8px;" caption="This is what happens when I run traces in the airflow, it is very much disrupted by the model, and in a very turbulent way. " captionPosition="left" height="1080" width="1920" >}}

{{< figure src="/img/Week9/Week9Pic1.png" alt="Picture of Wall Calulation" position="center" style="border-radius: 8px;" caption="Here is the Wall Calulation. Using whatever axis the model is facing, you are able to calculate the force, and then use that in calculating the drag coefficient." captionPosition="left" height="1080" width="1920" >}}


Another thing that happened this week was my restarting of the piston seal project. My battery holder project was given to a softmore, Matt Stricker, which will being his first major design project which is very exciting. I will be helping Matt design and built this part, which will not be easy. If worst comese to worst on this part, we have lots more room, so it is not entirely necssary to have it be cylindrical, and we can simply make another mesh of normal battery holders, wired up in series, and have plenty of room leftover for the pcb, and other things that will be needed. 

All of the piston seal test pieces have to be resin printed, as the fdm printers cannot print to that high accuracy, and also kinda suck. Unfortuantly the resin printers are not working perfectly right now, and make a really fun noise that totally isn't terrifying when reseting the x - axis at the end of a layer. We think this may be due to insufficent lubricant on the x-axis lead screw, so therefore I am currently printing a lead screw cleaner, and lubircant aplicator (why there needs to be a special formlabs lubricant applicator I have no idea). Hopefully this fixes this issue, as I am getting pretty close to a good piston seal. Once I have the right dimentions in resin, I can then order and turn one out of aluminum.