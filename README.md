Magic-Pockets
=============

*Work as an intern in the French video game company Magic Pockets*

*July to October 2012*

![alt text](http://oi41.tinypic.com/2v0n5md.jpg)


I. Introduction.
---

Summer 2012 I had the chance to work for a French video game company. That was awesome! 
There will be no code in this repository. Instead, I will explain what I did.


II. First part: work on the game engine.
---

Magic Pockets created its own game engine. During the first 2 months of my internship, I improved one of its features.
The game engine uses its own picture format:
* it compiles several sprites on 1 sprite sheet, 
* it separates the header from the data,
* depending on the pictures quality, it may encodes the pixel data on less than one byte.

My first task was to develop developed a feature that allows to display one of those spritesheets. Here is the result:

![alt text](http://oi40.tinypic.com/35c4s9f.jpg)

Then I made a feature to help saving some room on the sheet by dividing the pictures into smaller chunks and using the quad tree principle.

![alt text](http://oi43.tinypic.com/2ylwoww.jpg)

I also worked on several small features like the integration of the Flurry app into the game engine.



III. Second part: Gameplay Development.
---

After succeeding my previous missions, I started to work on the project "The House of the Dead Overkill: The Lost Reels" or my last 2 months.
This is an Android/iOS game developed in C/C++ using the company's game engine.
I started the project almost from scratch: there was a camera moving into the world and an inanimate zombie.
Then I made:
* the 3D collision detection between the bullets and the zombies/items/walls
* the zombies dismemberment system
* the zombies IA
* the UI and the controls
* the slow-mo effect
* the game mechanics: life points loss, weapons, scoring, combos, ...

Here is what the game looked like at the end of my internship:

![alt text](http://oi40.tinypic.com/otp8pc.jpg)

I also developed a innovative control system that was deleted before the official release of the game, because it was not included into SEGA's specifications.
For more informations, you can read my internship report (in French).

