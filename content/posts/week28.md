---
title: "Week 28"
date: 2024-04-04T11:11:52-04:00
draft: False
---

This week was pretty slow, as we were once again unable to make it into the pool. I dove back into CFD trying to analyse and optimize a propeller. 

During my research into this subject, I found a pretty good youtube video on the subject, that showed me what I need to find to find the optimal propeller. These numbers I can then find using CFD analysis. I also wanted to do this with a spinning propeller, in order to give it the most amount of realism. This meant I had to learn how to do this with documentation that was basically non existent. A youtube video in a language I don't understand was way more helpful than the official Autodesk documentation. I then found a seminar, where i found effeciency formulas, that I am going to use to optimize this prop. 

{{< figure src="/img/Week28/Week28Pic1.png" alt="Effecientcy Formula 1" position="center" style="border-radius: 8px;" caption="This is the broad efficiency calculation for propellers" captionPosition="left" height="1080" width="1920" >}}

{{< figure src="/img/Week28/Week28Pic2.png" alt="Effecientcy Formula 2" position="center" style="border-radius: 8px;" caption="This is the more focused and simplified effeciency formula." captionPosition="left" height="1080" width="1920" >}}

Unfortunatly I haven't figured out how to make the propeller spin the right direction in the simulation, which makes me get spagetti like whats below. After that, I just have to figure out how to get all of the variables that are above so I can calculate the effiency, and figure out what I need to change. 

{{< figure src="/img/Week28/Week28Pic3.png" alt="spagett" position="center" style="border-radius: 8px;" caption="I think this is what happens when the propeller is moving the wrong way, creating thrust in the wrong direction." captionPosition="left" height="1080" width="1920" >}}