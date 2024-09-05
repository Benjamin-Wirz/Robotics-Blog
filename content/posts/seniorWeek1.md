---
title: "Senior Week 1"
date: 2024-09-05T16:31:52Z
draft: False
---

Its the first week of senior year, and so far its going pretty well. This year I am going to be working on the autonomous golfcart that [Roman](https://romanriceengineeri.wixsite.com/engineering-blog/personal-engineering-blog) got working last year. Although it was working, he only got the throttle to be automously controlable. This year I am going to try to get the steering to be autonmously controllable. This is what I have been working on the past week. I will be mainly focusing on the hardware for this, as i'm not very knowledgeable on the other sides of this project.

### Option 1 

The first thing that I wanted to do to steer the golfcart, was to attach a motor onto the steering column with a belt. This is the method that is preferable in my opinion, but comes with its downsides. The motors that are ment for this are really expensive. This means we would have to find a way to use a bushed DC motor, and an Encoder somewhere in the steering system to get accurate steering data. This is not that bad though. The main issuse that I found, was it was really difficult to find motors that would both be powerful enough, cheap enough, and fast enough to work for this aplication. This is why I looked at the next option. 

### Option 2 

The next thing that I though of was using a linear actuator to push and pull on the actual wheels steering knuckle to do the turning. The benifit to doing this, is that powerful linear actuators are much cheaper, because they are used in many things, as well as the fact that actuators in this range exist, and aren't very expensive at all. 

{{< figure src="/img/SeniorWeek1/SeniorWeek1Pic2.jpg" alt="Golfcart front end" position="center" style="border-radius: 8px;" caption="the steering rack is the long tube thing, and it connects to the knuckle. This is where I would mount a linear actuator to steer. Above it you can see the steering column, which would have the motor attached to it. " captionPosition="left" height="4032" width="3024" >}}

Luckily Mr. Christy found a motor that looks really good and is a good price, so at the moment we will go with option 1. The next steps will be to order the motor, and start modeling up a mounting solution in CAD. 

{{< figure src="/img/SeniorWeek1/SeniorWeek1Pic1.png" alt="Steering Motor " position="center" style="border-radius: 8px;" caption="This is the motor I will be using to steer the golfcart with. There will be two timing pulleys that attach to the output shaft, and the steering column, and a belt to attach them." captionPosition="left" height="4032" width="3024" >}}
