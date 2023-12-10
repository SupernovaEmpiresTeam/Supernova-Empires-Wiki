+++
title = 'Extreme Reactors'
date = 2023-11-30T01:29:32Z
draft = false
+++

![Extreme Reactors Banner](https://wsrv.nl/?url=https%3A%2F%2Fzerono.it%2Fcurse%2Fer_header.png&n=-1)

You need more energy for your machines? Get an extreme amount of it

Extreme Reactors is the original port of the 1.7.10 mod Big Reactors, by Erogenous Beef, rewritten for MC 1.9.4 / 1.10.x / 1.11 / 1.12.2 and 1.16.3 / 1.16.4 / 1.16.5 / 1.17.1 / 1.18.1 / 1.18.2 / 1.19 / 1.19.1 / 1.19.2 / 1.20 / 1.20.1. The name was changed following Curse Forge deployment rules.

Giants Reactors to harness the power of the atom or mighty Turbines to turn steam into energy? Why not both?

Build huge multiblock machines to produce produce energy in a very efficient way. Extreme Reactor support natively the Forge Energy Power system with the Forge Energy Power Taps so you would be able to power the vast majority of modded machines. The mod is designed in such a way that, if needed, more power system can be supported. Just let me know!

## DEPENDENCIES

Extreme Reactor require ZeroCore to work. Please add the correct version to your mod folder.
To use the in-game manual you need the mod Patchouli in your pack.

## THE EXTREME REACTOR API

The API jar is available on my maven rep: https://maven.zerono.it/

## NOTABLE CHANGES SINCE 1.12.2

Turbine Coils update! (versions 2.0.38 and following)
There are now three new (one is making its comeback) late/end game coils for extracting a huge amount of power from your Turbines: Ludicrite, Ridiculite and Inanite. You should expect around 45K / 75K / 115K FE/t from a full coil in a Reinforced Turbine from each of them.
Mod(-pack) authors can now use the /er coils command to fine tune any new coil they add to ER
The Fluid Fuels update!  (version 1.16.5-2.0.32 / 1.17.1-2.0.32 and following)
Extreme Reactors now support fuels (and wastes) reactants in fluid form that you can insert in your Reactors without any material loss using the new Fuel Injection Port set in inlet mode. Fluid wastes will be ejected into an Injection Port set in outlet mode.
How will you make fluid fuels? With a new multiblock machine: the Fluidizer!
You will need a Controller, a Power Port, an Output Port and the usual mix of Casing and Glass parts (if you like the Glass, right now the fluid is not rendered inside the multiblock). There are two kind of Injector Ports that will let you insert material in the Fluidizer:

- the Fluidizer Solid Injector for solid ingots or blocks
- the Fluidizer Fluid Injector for liquid fuels

One Solid Injector will let you convert your solid fuel to it's fluid form
Two Solid Injectors will let to convert and mix two different solid fuels into a new type of fluid fuel
Two Fluid Injectors will let you convert and mix two different fluid fuels into a new type of fluid fuel
Mixing fuels with usually give you a better fuel than the original ones
Please check in JEI for the recipes (more recipes can be added using Vanilla recipe system)

- All fuels and wastes in fluid form can be placed in the world. It will be probably not a good idea to swim in them

- Added the Verderium fuel. The top tier fuel

- Added the Rossinite waste. It will make you go fast like the GOAT

- Added /er command (op level 2+). Useful for pack authors to fine tune fuel values

**The Fuel Update (version 1.16.5-2.0.29 / 1.17.1-2.0.29 and following)

Extreme Reactors now support fuels reactants that produce fuels with different properties from each other. This allow ER and mods / modpacks to add different kind of fuels using the ER API (FuelProperties / ReactantsRegistry) or the API modpack-wrapper. If no fuel properties are specified for new fuels reactants, the default ones (Yellorium) are used. This will allow the creations of other fuels by mixing existing ones, once liquid fuels are finalized.
Blutonium is back as a full-fledged reactant and fuel, with a better yield than Yellorium (keep in mind that it's properties are not set in stone right now), and it's "crafted" by reprocessing Cyanite.
Blutonium will turn into Magentite, a new waste-type reactant, after being used in the Reactor. There is currently no use for it in the mod, but who knows what will happen in the future.

**The Reprocessor (version 1.16.5-2.0.29 and following)

A new multiblock machine that's able to reprocess wastes into new fuels. You will use it, for example, to craft Blutonium from Cyanite (check the recipe in JEI).
The Reprocessor is a 3x3x7 (x/z/y, external dimiensions) multiblock build using Reprocessor Casing blocks for the frame or faces. Reprocessor Glass blocks can be used instead of Casing on the faces. You need one (and only one) of each of the other Reprocessor parts (Controller, Collector, Waste Injector, Fluid Injector, Output Port, Power Port). The Waste Inject goes in the top face, the Collector on the bottom face. The other ones can go on any vertical face.
The Reprocessor recipes use an item and a fluid to craft another item. Mods and modpacks authors can add they own recipes in the usal ways. The Reprocessor need 1000 FE to process a single recipe. You can check the available recipes in JEI.

**1.16.x / 1.17.x

- In-game documentation is available with the The Extreme Book! (you need Patchouli too)

- The Reactor and Turbine comes in two initial variants: Basic and Reinforced

The Basic variant is your early game choice: cheap and small (5x5x5 max for the Reactor, 5x5x10 for the Turbine)
The Reinforced variant if your heavy duty one: machines as big as you want (check your server config file) and build from steel ingots (or a botload of iron if your pack lack steel)

- The internal buffers (energy / fluids) size of any Reactors and Turbines is a function of the machine size.
- There are now two general tipes of Power Taps and Fluid Ports: active and passive
- an Active one will send out power or fluids (or retrive them) automatically to the block connected to it
- a Passive one will send out power or fluids (or accept them) ony if the block connected to it request it
- using both types allow you to fine tune your energy or fluids distribution network
- The Access Port has gone Solid ... the old girl is not as good as it was in the past at converting fuel ingots to liquid fuel. But it's still does a good jot at it
- The Fuel Rod rendesing is even more FPS friendlier than before. You should have not rendering performance problems even with a huge number of Fuel Rods in your Reactors
- Reactor / Turbine Forge Energy Charging Port. Use it to charge items that use energy (FE) to operate. Open the GUI and put the item in the input slot in the center (more info in the book).
- Turbine Rotor can be build with any combinatios of blades you want (provided that their variant match the Turbine's and, well, it is a valid rotor :)) and will be animated using the shape you build
- New fancy and FPS friendly GUI because i like fancy stuff and you like your FPSs
- The Reinforced Computer Port support CC-Tweaked LUA program to help you manage your Reactors and Turbines
- Modpack authors can use the Creative Water Generator / Steam Generator to create self sustaining Turbines setups or as a rare loot for their players
- Ore-regen: the mod can re-generate it's ores by setting the "enableWorldRegeneration" config option to true.

Worldgen must be enabled too, and so does the specific ore options you want to re-generate. If you need to re-generate chunks again, increate the value of the config option "userWorldGenVersion"

## ABOUT A JEI PLUGIN

As you may have noticed, ER do not come with a JEI plugin that list all the moderators, fuels, coils, etc and their properties. The reason is simple: I don't want to have one. It would be no fun having the answer to "what's work best" outside the game, instead have fun and experiment!
Since there are tons of blocks and items in any modern pack, in 2.0.6 I've added a tooltip to items and blocks that could be used as fuel or moderators for the Reactors or Turbine coils. It's an advanced tooltip so you need to enable them to spoil your fun There is also a client config option to disable them if needed
I'm planning to have an in-game method to test your Reactor designs without having to build a whole one. The key code is already in place and Reactors and Turbines can already run in simulation mod
Also, to my fellow modders: please DO NOT add an external JEI plugin that show fuels, moderators, etc, for my mod, thank you.

## Links

[Modrinth (Source for this article)](https://modrinth.com/mod/extreme-reactors)

[Source Code](https://github.com/ZeroNoRyouki/ExtremeReactors2)

[License: MIT](https://opensource.org/license/mit/)