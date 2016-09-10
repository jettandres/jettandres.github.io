---
layout: single
title:  "Version Control System (VCS): Saving"
date:   2016-09-10
categories: VCS
gallery:
  - url: stardew-menu.png
    image_path: stardew-menu.png
    title: "Stardew Valley - Main Menu"
  - url: stardew-load.png
    image_path: stardew-load.png
    title: "Stardew Valley - Load"

gallery2:
  - url: a-simple-notepad-save.png
    image_path: a-simple-notepad-save.png
    title: "Saving A Simple Notepad"
  - url: stardew-load-2.jpg
    image_path: stardew-load-2.jpg
    title: "Stardew Valley - New Character Created"
---

In my [previous post](../vcs-why-should-i-use-one "Version Conrol System: Why Should I Use One?"), we talked about *Dark Souls* and its similarity with *Version Control System* or *VCS*. Today we are going to discuss about the difference between a *standard save* `Ctrl + S` or `Command + S` and the **VCS** *way of saving* with **Git**.

>Hold on. Wait a minute, **what is Git**? I think I have heard about it before. And what is the **difference with GitHub?**

I got you. We will cover this later on. For now, all you need to know is that  _**Git** and **GitHub** are different like **Car** and **Carpet**._

Below are screenshots from one of the games I play for leisure. The game is called **Stardew Valley**. *(Check it out on Steam if you miss playing __Harvest Moon__ or any similar farming simulator game)*

{% include gallery caption="_Please don't mind my character looking like a hobo... He used to be handsome until he started farming. Now he is rocking a bearded hipster look with sailor hat and purple shoes for bonus health and agility_" %}

In the **Main Menu**, we have *three buttons* namely `New`, `Load`, and `Exit`. When I click on `Load`, we are presented with a list of characters that I have made in the past. These are my **Save files**.

Clicking the `New` button from the **Main Menu** would allow me to create and add another new character to the list.

*Normally when we play video games, some games (like RPGs) would allow us to __create multiple Save files for a single character__. Unfortunately for Stardew Valley, the developer did not allow that. Instead, we are left with __a single character per save that can be overwritten by the same respective character__ as we progress through the game.*

## This perfectly demonstrates what I want to show you next:  

Here we have a simple notepad.

![image](/images/a-simple-notepad.png)

We can change its content and type in anything we have in mind. *This is like my in-game character.* We can play our character or update our content while we have it opened.

![image](/images/stardew-town.png)

After awhile, we then hit our trusty old pal `Ctrl + S` or `Command + S` to **Save** it. *In Stardew Valley, we save by going to bed for the next day.*

On my first time of saving, my computer will ask me where I want to save my file so that I can come back at a later time in case I would like update my content again or simply view it.

*Some games would let you choose a __save slot__ after creating your character. For Stardew Valley, the slot is automatically assigned for the player.*

{% include gallery id="gallery2" %}

*This is the standard way of saving files*. From hereon everytime we press `Ctrl + S` or `Command + S`, we save our changes and update file found in the save location.  

>But what if I would like to update my content but keep the old one just in case I am not really sure with the new one?

In a development environment, normally we would Copy-Paste our file from its Save location but for the sake of simplicity and keeping the context of my example, we are going to rely to the Save As... feature of our Notepad found under File menu.

<<Insert Save As - Simple Notepad Here>>

This will prompt us again like our first time and ask where we want to Save the old one.

<<Insert Save As - Simple Notepad - 2 Here>>

Perfect! Now we have two copies of the same file with different filenames to distinguish them. This process is called Software Versioning or Versioning for short. Derived from the word 'Version' a particular form of something differing in certain respects from an earlier form or other forms of the same type of thing. (Thanks Google Dictionary)

Versioning with Git also works this way but in a cleaner fashion without duplicating and renaming files. It will also allow us to take note of the changes and updates we have made to the old file better than describing/putting them in the file name itself.

I will let this is sink in to you for now. In my next post, we shall get our hands dirty and get you started with setting up and embracing Git in your daily programming life. Thanks for reading!
