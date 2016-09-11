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

>"Hold on, Jett. Wait a minute, **what is Git**? I think I have heard about it before. And what is the **difference with GitHub?**"

I got you. Don't worry, we will cover this below. For now all you need to know is that  _**Git** and **GitHub** are different like **Car** and **Carpet**._

Alright here we go.

## The Standard Save: (`Ctrl + S` / `Command + S`)

We all now this. The superhero we call whenever we need to take a break to do other things.
This is a universal desktop language to every computer user out there regardless of what Operating System he or she uses along with `Ctrl + C` / `Command + C` and `Ctrl + V` / `Command + V`.

Let us take note that hitting `Ctrl + S` / `Command + S` only saves the **currently opened file** from a specific location in your computer.

**One** `Ctrl + S` / `Command + S` is to **One file** saved.

## Version Control System (VCS) way with Git

Take a look at this ~~sophisticated phenomenal state-of-the-art~~ simple train map of Manila, Philippines' ~~subway~~ railway transit.

![image](http://2.bp.blogspot.com/-8nneMRhTbLQ/US0OfW0WO7I/AAAAAAAAB3c/dlUgiKdoo-U/s1600/train+route+map++manila+philippines.gif "I did not know it looks like a-...bow with a crooked arrow. :P")

Let us start at Baclaran LRT 1 station below. Imagine each consecutive **station** from Baclaran as a point in time where we hit `Ctrl + S` or `Command + S` on our **single file (LRT 1)** and the **blue (MRT 3)** and **purple (LRT 2)** lines as times we duplicated our file and modified it a bit; also hitting `Ctrl + S` or `Command + S` along the way after renaming them.

**Git** is a type of **_Distributed VCS_** that works in a very similar fashion.

>"What does **Distributed** in this context mean? "

It simply means that anyone who has a copy of our **single file (LRT 1)** will also get a copy of our two other versions called **purple (LRT 2)** and **blue (MRT 3)**.

In VCS, we do not need to duplicate our **single file (LRT 1)** and rename them manually to **purple (LRT 2)** and **blue (MRT 3)**. Pretty cool, huh?

I owe you some explanation with regards to GitHub.

> **GitHub** is simply an online storage to save your files. In Version Control terms, we call this a _Repository_.
  It's like Dropbox / Google Drive but different because it complements some VCS's functionalities. Which VCS? You guessed it! **Git**.  

A **Repository** stores our saved code and makes it accessible anywhere we have an internet on via browser.
While most online storages are only accessible by their respective owner/user with an option to share specific files with a dedicated link,
a Repository can either be **Public** or **Private** depending on the company that is
hosting the service.

 - **Private Repository** can only be accessed by its owner and his selected collaborating users.
 - **Public Repository** can be accessed by **_anyone_** and *gives full consent to anyone to
 make a copy of his own* for modification purposes. A copy can be stored in one's local computer (aka **_Cloning_**) or in his public repository (aka **_Forking_**).

>"[D'oh!](https://youtu.be/g6GuEswXOXo) That's a lot of technical terms, sir. My head is aching..."

Don't panic. I will go more in-depth about the concept of __Cloning__ and __Forking__ later with a simple analogy. Stick with me, guys. For now, let's go on a journey...

**A Little History**

Version Control Systems went through a series of stages in the past that sprouted different methods of saving and retrieving of one's files.

> **Git** is a type of Version Control System (VCS). In the past, there has been a number of

## Bonus

Both saves can work in harmony












<!-- WILL REVISE THE ONES BELOW -->

<!--


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

I will let this is sink in to you for now. In my next post, we shall get our hands dirty and get you started with setting up and embracing Git in your daily programming life. Thanks for reading! -->
