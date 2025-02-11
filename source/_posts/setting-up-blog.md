---
title: Setting up this blog
---
## Introduction

As disappointing to myself as this is to say, I struggled quite a bit to setup this blog. I've wanted to setup a blog for many months now, but I've kept on running into problems which put me off setting it up, in this post I'll explain why it wasn't as easy as I thought it was going to be, the challenges I faced, how I solved them and my thought process around it.

First I needed to decide on a framework, I decided on [Hexo](https://hexo.io/) because of it's ease of use, speed and minimalism on a surface level. I am not a web developer and I am not particuarly skilled with Web frameworks and things such as Javascript, I can get by, but I am nowehere near good enough to make my own blog website to this quality.

After setting up Hexo with the default theme, I just wanted to get it to run somewhere, I decided on Vercel because it's perfect for my use case and even has a built in Framework preset for it (not too sure what that does though?).

Once I got it hosted on Vercel I could also develop locally with Visual Studio Code and GitHub. I now wanted to add a theme because the defualt Hexo template looked like it was made in 2015. I ended up on the [minimalism](https://github.com/f-dong/hexo-theme-minimalism/tree/master) theme as I loved it's simplicity and it was perfect for my use case, I couldn't really find any others that matched it on [their themes list](https://hexo.io/themes/)

## Challenges

*This is where things got **BAD**.* I was planning on recalling all the issues I went through when I set this site up, but with all the delays I don't quite remember everything, so I'll do my best.

First of all, the theme you pull from isn't nesccessarily a template, it's a live project, meaning you have to tweak it to your needs and remove a lot of unesscarry features and files. Secondly, I've never really touched web frameworks before, so this was all new to me, one slight change and it would break a feature or functionaility and I would have to go back again. This would normally be easy by doing ```git restore .``` however, because I cloned the github project, it had it's own git history etc. This took me some time to figure out how to detatch it from the repository it originated from and integrate it into my project. Eventually I managed it though. Lastly, the final problem I had was that this project was made with a mix of Chinese and English features, there's still lots of analytical and tracking features embeded into the theme which I plan to remove in future, I tried removing them earlier but this would just straight up break the website, to do this I actually need to understand what is going on, which is why I will come back at a later date. 
