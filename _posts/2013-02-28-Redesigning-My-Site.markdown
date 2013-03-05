---
layout: post
title: Redesigning My Site
date: February 28th, 2013
---

I recently decided to redesign my website. Instead of completely scrapping what I had, I consider my new design an iteration of the previous version, with a slight shift in focus. My old site was supposed to function as a digital business card - minimal and elegant. I think I more or less achieved that, but I needed something with a little more content. Specifically, I need to be able to sell myself to potential employers or clients as a web professional. 

Designing for My Goals
======================

I have a "blue" problem, in that I always want to design in partially or primarily blue. I liked the mood of the previous site and decided to stick with the blue that I had been using. Further, though I wanted to add more content, I liked the minimalist aesthetic and use of white (or blue) space. Here's how my old site looked before taking it down. 

![My Old Site](../../images/ps/oldsite.png)

The compromise I settled on was adding just a little content to the blue section, and dumping the rest of the content into the white section below. I also elected to get rid of the color switcher that I was so proud of previously. I was too busy to ever implement caching to carry the switch over to other pages, and it was too gimmicky to keep in the new design. 

Another major change was the backend. Previously I had been running the site on some simple, custom PHP and a very tiny MySQL database. I wanted to add a blog, but I also wanted to get rid of the database entirely. I settled on Jekyll as the optimal solution: it's a static site generator - essentially an HTML pre-processor - it creates a set of files that can be dumped onto the web server. It also allows me to write posts in markdown, which I had wanted to try.

Updating My Workflow
=====================

Another major goal of the redesign was to force myself to step out of my comfort zone and update my workflow. These days there's really no excuse for not using CSS preprocessors, so I made a point to start learning SASS while working on the site. Jekyll was also new, as discussed earlier, as well as markdown for quick blogging. Perhaps most importantly, I made a point to work version control into my site, and actually make use of versioning. 

Before this project I had this perverse idea that a website should be *finished* before taking it live, and that kept me from getting much done. I launched with several non-essential pages disabled, and only the content that was necessary to bring it live. Then I worked on implementing and launching one feature at a time. This would undoubtedly be a more complex process for a more complex site, but it was nonetheless a useful experience in escaping my perfectionist tendencies. 

Designing for Mobile
====================

Now a confession: I understand the arguments for mobile first, but I have never been able to make my brain think that way. Or rather, every time I try, I end up moving back to desktop-first and then making it look decent on mobile. This site was designed for a desktop, but I feel like I did a pretty decent job of adapting the layout for smaller resolutions.

I take care to point out that I adapted it for different resolutions instead of different devices, because it would be nearly impossible for me to test it on every device that it may be viewed on. Instead, I attempted make sure that the site looked good at essentially any resolution, which is a much more device-agnostic approach, and hopefully a future best practice.

Typography and Personality
==========================

Though it may show more in some of my other projects, I have spent a lot of time recently thinking about two facets of design: typography and personality. One weakness of my previous work is that I took typography for granted. Really strong typography can make a world of difference in the look and feel of a site, and it's undervalued as an asset, in my opinion. 

I have also been thinking about personality in design. Does an injection of “personality” into my design make me look more or less trustworthy? Is personality inherently unprofessional, or can a fully professional site have personality? I just wanted to note that I spent time thinking about it while working on this iteration of my site. It may be evident that I had it in mind when looking at some of the text, or the ways that I use images of myself. I may blog more on this later. 

In the Future
=============

Every time I launch a new site I absolutely adore it. For about two months. I'm hoping this redesign will keep me contented for longer, so that I can focus on the litany of side projects that I have been neglecting while focusing on this website. 

I also plan on blogging semi-regularly. My past experience with blogging has made me realize that personally, I prefer quality over quantity. So I will be blogging infrequently, but I will make sure that each post is of a high quality. 