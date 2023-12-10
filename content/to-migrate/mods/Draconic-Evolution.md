+++
title = 'Draconic Evolution'
date = 2023-11-30T01:29:32Z
draft = false
+++

This is a mod that adds a lot of high-tier items such as tools and armor as well as some high-tier energy storage and a lot of other random features such as:

- Teleportation
- Mob farming (spawning+killing)
- Player detection
- Time and weather control
- Powerful tools and armor
- High tier energy storage (RF)
- And much more with new features being added in each update.

1.16 is a complete code rewrite from 1.12. Almost everything has changed in one way or another.
Some things still need to be rewritten and others have not been implemented at all yet. 
For now, if you find something is missing then assume it will be added back in a future update. 
Do not open issues because 'item X' or 'feature Y' is missing!

## New 'Modular Item' system

![Draconic Evolution Modular System](https://ss.brandon3055.com/7cc8d)

The way tools and armor work has been completely changed! 
On their own, the tools and armor are now pretty much just fancy paperweights. In order to make them useful you need to install upgrade modules.
If you have played Factorio the new modules system should seem somewhat familiar as it is loosely based on Factorio's modular armor. 
Most modules are pretty self-explanatory but here are some general tips to help you out.

- Most modular items need at least one energy storage module in order to function,
- Higher tier items (Draconic, Chaotic) allow you to install more / higher tier modules.
- Movement speed, Bow draw speed, and melee attack speed can all be increased using speed modules. 
- In order to install a module in a modular item must accept that module type and be of the same tier as the module or higher. 
- The draconic shield requires a shield control module, shield capacity modules, and shield recovery modules. Think of the controller as the main shield generator. The other two should be self-explanatory. 
- The Auto feed module consumes food from your inventory then feeds it to you as required. 
- For creative flight, you need a draconic or chaotic flight module. (There is no longer a way to boost creative flight speed)
- For high-speed flight, the flight modules now include elytra flight functionality with the added advantage of a 'boost function which can be activated by pressing your forward movement key plus your sprint key.
- You are no longer "invincible as long as you have energy" Instead you have "Undying Modules" which are effectively rechargeable totems of undying. These do have a significant energy cost to recharge as well as a minimum recharge time. But on activation, they will give you a health boost, a shield boost, and invulnerability for a very limited amount of time. Higher tier modules can increase the number installable (up to 3), increase the effect power and decrease the minimum recharge time. 

Many module textures are temporary and need to be replaced.

## Armor

For the moment you just have the Modular Chest Piece. This is primarily because implementing this module system across multiple separate armor items would be a significant technical challenge. 
A full armor set May be added later but I'm not yet sure how I will implement it. (Please don't make suggestions, I have already had countless people give suggestions)

## Chaos Guardian

The chaos guardian has been completely rewritten with all-new fight mechanics. The spoiler below gives some details on how to defeat the guardian. If you prefer to be surprised then don't read it. 

## Advanced Dislocator changes

The advanced dislocator now has a "blink" function that allows you to teleport a short distance.
Also optional keybindings for blink, cycle destinations, teleport, and open GUI. 
This is very useful when the dislocator is in a curio slot.
Notes on the chest piece and curio support:

The chart piece is now a curio that can be placed in the "body" slot.
This means you can wear it along with other armor in which case it's specifically designed to render properly on top of the standard vanilla style armor model.
But this may not work too well with custom armor models. There is currently no way to 'hide' the chest piece when it's in a curio slot. 
Also, note the Elytra function of the flight module does not currently work when in a curio slot. I am currently waiting on a forge PR that will let me fix this. 
If you have a question that I did not answer here then, please check the #1-16-questions-answers channel on the Draconic Evolution Discord. If your question has not already been answered then ask. 

## Links

[Curseforge (Source for this article)](https://www.curseforge.com/minecraft/mc-mods/draconic-evolution)

[Source Code](https://github.com/Draconic-Inc/Draconic-Evolution)

[License: All Rights Reserved](https://raw.githubusercontent.com/Draconic-Inc/Draconic-Evolution/master/LICENSE.md)