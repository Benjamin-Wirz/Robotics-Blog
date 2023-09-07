---
title: "CustomTheme"
date: 2023-09-06T12:38:45Z
draft: false
---
## Altering a Hugo Theme

Quick disclaimer, I am not an experienced web developer, or programer of any 
kind, there are probably 10 better ways to do this but I am not aware of them.
also excuse my probably incorrect terminology.

As you can see this website is based off of the fairly popular Hugo theme 
hello-friend by panr. I am a large fan of this theme, however I had a want to 
customize it to my wishes, as I didn't like the ommitence of a title seperate
from the header at the top of the page. Thus I went down the fairly simple path
of finding where to put the _index.md file and adding my Title, with a handy
frame around it. This then got me thinking, after watching another video about
shortcodes, that I might be able to alter the position of the posts list, that
is found on the home page to be within the framed box. 

This was not fun. I was searching around the theme for the bit of code that 
creates the list, which happened to be in the layouts/_default/index.html 
folder. I messed around with it for some time, fully deleting it, which did not
help, but eventually I go it to remove the list, without destroying the home 
page. However me being a beginner, i hadn't forked the repo, I had just
cloned it into the themes folder, which meant that I couldn't commit or sync
those changes, thus making it impossible for Netlify to see those changes and
update the public site. This was very frustrating. I forked the repo, and made 
my own variation of the theme, where I imported the new theme, and then made
all of the changes I had made locally. This just left the part of reinstituting 
the list of posts, inside the framed box. 

The initial code was not very difficult to write, however getting it to display
the correct types of content was quite frustrating. I  used shortcodes, 
and a video by Luke Smith to get started, but whenever it would display
them, it would also display the about page, and other pages that were not 
posts. This proved to be a bit of a challenge. I spent the next 2 days on and 
off searching for different solutions, where I eventually just decided to call
it and just display only the first post, buy date, and every time I post a new
Blog post I up the displayed post count till 3 or 5. This is not the solution I
was hoping for, but as I went throught this project I was reading everything 
semi relavant to this on the Hugo documentation, and it seemed like there 
wasn't much to differentiate between each type of content. 

This obviously isn't the solution I was looking for but it will have to do for
now. I do wish Hugo had an easier system to determine different types of
content, so that instead of displaying all of them, it could just display posts
or all lists, etc. This being said it should work for now.