---
layout: hw
title: Homework 16b - Stuyablo rules
published: true
---

We will be using the rules for [The Fantasy Trip](http://en.wikipedia.org/wiki/The_Fantasy_Trip) - a role playing system designed by Steve Jackson.

You can see a writeup on the rules here: [http://rdushay.home.mindspring.com/Museum/Fantasy/TFTrevw.html](http://rdushay.home.mindspring.com/Museum/Fantasy/TFTrevw.html).

Here are the basics:

**Attributes**

For a human, each attribute starts at 8 and you have 8 additional points to distribute. A PC can use user input to generate the characters or you can do it randomly. An NPC should randomly set the attributes. Other races can have different starting points and point allotments. Likewise you can start specific characters with certain strengths and weaknesses.

**Combat**

To hit an opponent, you have to roll your dexterity or less on three
six sided dice.

For distance weapons, the in the real game you subtracted 1 from your dexterity for the purposes of the roll per grid space travelled. You would make the adjustment based on the distance between the two characters.

Damage is based on the weapon you use and the weapons you can use are based on strength,
k.

See the link above for more details and how to deal with experience and leveling up.

Feel free to tweak the rules a but but if you do, please email what you're doing to the mailing list. If it's a good idea other people will want to steal it.

For later enhancements we'll finalize on one single system, but for now, this should be enough so that everyones programs can interoperate.

**Notes**

Remember that you should extend Character for each player type you create and you should override the attack, flee, and encounter (plus whatever else you want to do).

Your Driver should simulate a meeting between two characters. It should call enounter for one, then the other in a loop until the encounter ends.





