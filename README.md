Newt One talk
=============
https://www.facebook.com/devnari

https://twitter.com/DNANewtOne

Contact us about beta testing and Slack channel access

Intro & overview
================
* classic 3d-platformer
* (truly) non-violent
* enjoyable and approachable by all ages
* levels should be succinct (about 3-5 min for experienced players)
* highly replayable (parrots, notes, achievements, narrative unlocks, etc)
* non-linear
* multiple platforms (console launch first XBOne, hopefully)
* increase happiness and well-being... possible? We'd like to try and find out

![overview1](http://i.imgur.com/MpIJKl1.png)
![overview2](http://i.imgur.com/Oixz9bp.png)
![overview3](http://i.imgur.com/JLFom32.png)
![overview4](http://i.imgur.com/oRAPyaJ.png)
![overview5](http://i.imgur.com/BzJid9S.png)

Inro Play through
====================
* Level 1: Forest 1 (no power ups, focus on environment and music changes)
* Level 2: Clouds 3 (Burst and Wand)

Art
===

![art1](slides/art1.png)
![art2](slides/art2.png)
![art3](slides/art3.png)
![art4](slides/art4.png)
![art5](slides/art5.png)
![art6](slides/art6.png)
![art7](slides/art7.png)
![art8](slides/art8.png)
![art9](slides/art9.png)
![art10](slides/art10.png)

Level Design
============

![ld0](slides/LD0.png)
![ld1](slides/LD1.png)
![ld2](slides/LD2.png)
![ld3](slides/LD3.png)
![ld4](slides/LD4.png)
![ld5](slides/LD5.png)
![ld6](slides/LD6.png)
![ld7](slides/LD7.png)
![ld8](slides/LD8.png)
![ld9](slides/LD9.png)
![ld10](slides/LD10.png)

Systems
=======
![systems](http://i.imgur.com/MAmIL20.png)

* Level (percentage, drone/music, aesthetics)
* Realm (wand, parrots, time)
* World

* music level system
![level music system](http://i.imgur.com/xkYgI2E.png)

![taxonomy](slides/taxonomy.png)

![achievements](slides/achievementsPlan.png)
![realmAchievements](slides/realmAchievements.jpg)
![worldAchievements](slides/worldAchievementsPlan.jpg)

Testing Analytics System
========================
![testing SQL](http://i.imgur.com/G2FvnRj.png)

[![video](http://i.imgur.com/ybjPXn1.png)](https://youtu.be/NrIpgW_MOdE)

Other programming tidbits
====

RNG for non-gameplay stuff
Language selection

![languageSelection](slides/languageOptions.png)

Other Systems/Features
======================
* Scale Outs

![scale outs](http://i.giphy.com/6NFa2QCk5kcSc.gif)

* wave platforms

![wave platforms](http://i.giphy.com/iIr3m6MgfUjPG.gif)


Adding New Features/Course Adjusting During Development
=======================================================
movers-path movers-stopping path mover
-------------------------------------
* originally thought only back-forth movers would be enough

![simple mover](http://i.giphy.com/wJBvOcuQGQ4wM.gif)

* started using movers in creative ways in level editors

![ice platforms](http://i.giphy.com/ao8jlGusmfFPq.gif)

* evoled to pathing movers

![path mover](http://i.giphy.com/12VgkJtVNatuhi.gif)

* one level needs path a mover that stops at last position


outfits/lives/notes/coins
-------------------------
* started as coins

![coins](http://i.imgur.com/IzUyEZX.gif)

* 30/level
* became notes

![notes](http://i.giphy.com/zmgRgFI3Xtvj2.gif)

* 50 for an extra life

![extra life](http://i.giphy.com/cB4ukcrbK9lfi.gif)

* asked "why do you have lives?" at MinneBar 2016
* observed many players stop playing when out of lives at TEDx Minne 2016
* now 50 for an outfit upgrade

![first in-game outfits](http://i.imgur.com/YWOoPvt.png)

* when player "dies" the respawn sound is more happy (respawn, not death)

Disruptors
----------
* started as Krystal's idea
* prototyped and iterated
* started as crystals only

![disruptor prototype](http://i.giphy.com/1O56HXGkmcNUI.gif)
* evolved in a Slack convo

![disruptors convo](http://i.imgur.com/EYEMZZh.png)

![updated model](http://i.giphy.com/PqKEG8xOsARva.gif)
* juiced it

![juice](http://i.giphy.com/whuC8e1GX7xx6.gif)
* added bubble
* play thru of Glaciers 4

parented animated objects
-------------------------
* worked fine in editor when manipulating by hand

![scale working in editor](http://i.giphy.com/RBpLTzTUL0b6M.gif)

* no worky when scaled by a parent in game

![scale problem](http://i.giphy.com/GpWpa0Tt08xaM.gif)

*fixed by proportionally setting scale if parented (simple boolean)

![stay scaled parented animated](http://i.giphy.com/DfqrrS1ZR3ZC.gif)

Leaderboards
------------
* still up from Alpha (http://devnari.com/newtOne/)
* too competitive for the game's philosophy

Enemies/NPCs
------------
* originally standard 3D platformer (jump on enemies)

![oldschool](http://i.giphy.com/kMKAzu88RozbW.gif)

* we tried a bunch of them

![enemy projectile](http://i.giphy.com/ypsGwe0VutBHG.gif)

* first 'ghost story'

Hub Level
---------
* show old versions

![2016 world menu](http://i.imgur.com/bD1A4RX.png)

* show sketches of new

![hub world sketches](http://i.imgur.com/B8R6jv7.jpg)

Final Demo
==========
* Hub
* Forest 6 playthrough

Q&A
===
