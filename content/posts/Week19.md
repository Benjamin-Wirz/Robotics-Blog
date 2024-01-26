---
title: "Week 19"
date: 2024-01-26T13:39:14Z
draft: False
tags: ["Float", "Battery", "Integration Hell"]
---

This week was what we less affectionatly like to call integration hell, or when multiple parts of the project have to start interacting with one another. In this case, we started to run the piston off of the battery and custom PCB. This cause a few problems that we still have to iron out. 

#### Battery Woes 

The custom battery that we designed is great, except it only goes as far as the actual cells inside of it. While accidentally leaving the battery shorted and then going to lunch, one of the cells ruptured and started spilling potasium hydroxide everywhere. This chemical is so basic that it was eating away at the corrosion resistant aluminum and the acrylic. We got the chemical spill under control, but now we had to figure out what happened. To do this we shorted out two cells in a smaller pre made battery holder. This made them very hot, but the cells didn't start leaking. Next we tried prodding at it with an xacto knife, to try to simulate potential damage that occurs during installation. This did nothing. We found that the only way to make the cells leak, was to hit it multiple times with the pointy side of a hammer. This made us chalk the failure up to a bad cell, and we cleaned up the holder and continued our work. This also showed us that we should probably be a lot more careful with the electronics than we have been in the past. 

#### Hall Effect Sensor 

To detect the strokes we use a hall effect sensor mounted on the piston, with magnets in 3d printed holders with set screws on the outside. This so far has been the most frustrating issue, as the sensors detect magnets when they are not there. This would normally be fairly easy to solve, as it is a binary issue, and you can easily see when it works. This issue is a lot more annoying as it will start to work, and just simply stop working at some point. This makes it nearly impossible to trouble shoot and therefore to fix the issue 


