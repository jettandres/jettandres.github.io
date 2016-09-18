---
layout: single
title:  "Version Control System (VCS): Saving"
date:   2016-09-11
categories: [VCS, Git]
---

In my [previous post](../vcs-why-should-i-use-one "Version Conrol System: Why Should I Use One?"), we talked about *Dark Souls* and its similarity with *Version Control System* or *VCS*. Today we are going to discuss about the difference between a *standard save* `Ctrl + S` or `Command + S` and the **VCS** *way of saving* with **Git**.

>"Hold on, Jett. Wait a minute, **what is Git**? I think I have heard about it before. And what is the **difference with GitHub?**"

I got you. Don't worry, we will cover this soon. For now all you need to know is that  _**Git** and **GitHub** are different like **Car** and **Carpet**._

Alright here we go.

## The Standard Save: (`Ctrl + S` / `Command + S`)

We all know this. The superhero we call whenever we need to take a break to do other things.
This is a universal desktop language to every computer user out there regardless of what Operating System he or she uses along with `Ctrl + C` / `Command + C` and `Ctrl + V` / `Command + V`.

Let us take note that hitting `Ctrl + S` / `Command + S` only saves the **currently opened file** from a specific location in your computer.

**One** `Ctrl + S` / `Command + S` is to **One file saved**.

## Version Control System (VCS) way with Git

Take a look at this ~~sophisticated phenomenal state-of-the-art~~ simple train map of Manila, Philippines' ~~subway~~ railway transit.

![image](http://2.bp.blogspot.com/-8nneMRhTbLQ/US0OfW0WO7I/AAAAAAAAB3c/dlUgiKdoo-U/s1600/train+route+map++manila+philippines.gif "I did not know it looks like a-...bow with a crooked arrow. :P")

Let us start at Baclaran LRT 1 station below. Imagine each consecutive **station** from Baclaran as a point in time where we hit `Ctrl + S` or `Command + S` on our **single file (LRT 1)** and the **blue (MRT 3)** and **purple (LRT 2)** lines as times we duplicated our file and modified it a bit; also hitting `Ctrl + S` or `Command + S` along the way after renaming them.

**Git** is a type of **_Distributed VCS_** that works in a very similar fashion.

>"What does **Distributed** in this context mean? "

It simply means that anyone who has a copy of our **single file (LRT 1)** will also get a copy of our two other versions called **purple (LRT 2)** and **blue (MRT 3)**.

 **With a Distributed VCS like Git, we do not need to duplicate our *single file (LRT 1)* and rename them manually to *purple (LRT 2)* and *blue (MRT 3)*. It manages all that work for us neatly. And any changes we commit to the file would only persist in our own copy until pushed/uploaded to a centralized Repository!**

**Bonus fact:** Both saves can actually work in harmony!

*I hope you are still with me. Thank you for reading! Leave a comment below if you are having a hard time understanding __VCS__ and __Git__. I will be discussing __Repository__ on my next post. Until then!*
