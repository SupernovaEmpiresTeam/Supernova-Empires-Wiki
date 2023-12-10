+++
title = 'Silent Gear'
date = 2023-09-28T19:00:53+01:00
draft = false
+++

Silent Gear is a mod that focuses on tools, weapon, and armor (collectively called "gear".) Gear can be crafted from any material used to make tools and armor in vanilla Minecraft, plus many more. Silent Gear also adds a couple of ores and several new metals that can also be used as gear materials.

## Key Features

### Tools, Weapons, and Armor

- Tools - Includes pickaxes, shovels, axes, paxels, hoes, mattocks, sickles, prospector hammers (searches for ores), hammers (AOE pickaxe), excavators (AOE shovel), saw (cuts down whole trees).
- Weapons - Includes swords, tridents, machetes, katana, daggers, knives, bow, crossbow, and slingshot
- Armor
- Elytra

### Materials

Materials are the things used to craft the parts of gear (tools, weapons, and armor.)

- Basic "vanilla" materials include wood, stone, flint, netherrack, copper, iron, gold, diamond, emerald, obsidian, netherite, and more.
- A few unique Silent Gear materials including crimson steel, azure electrum, and tyrian steel.
- Metals commonly added by mods such as tin, silver, lead, and many more are supported. The items required to use these materials are not added by Silent Gear.

## Crafting Gear

Almost all recipes are shapeless and can be made in any vanilla crafting grid. Check JEI if you are unsure of a recipe!
Blueprints and templates are essential for crafting any gear item. A blueprint can be reused infinitely. A template is consumed with one use. They are identical otherwise.
Every item requires a main part. Tools and weapons requires a rod and some require a cord.
If you need to check stats and trais [Click Here](silent-gear/stats.md)

### Tools and Melee Weapons

Combine the blueprint (or template) for the tool with the correct number of materials to make the main part (tool head, blade, etc.) The materials must all be the same, but may have different grades or other modifiers. Then craft the main part with a rod. You can craft a rod using a rod blueprint, or just use a plain ol' stick if you have nothing else.

![Pickaxe Recipe](https://imgur.com/Vvvafsy.png)

Or just use the quick recipe (available for most tools)

![Pickaxe Recipe](https://imgur.com/4HAzQ7C.png)

### Ranged Weapons and Fishing Rods

Ranged weapons such as bows and crossbows, as well as fishing rods, require a cord part in addition to a main part and a rod. The crafting process is identical, except that you must add both the cord and the rod at the same time.

![Bow Recipe](https://imgur.com/tYEqvd6.png)

### Armor

Armor requires only a main part, called plates. There is no quick crafting recipe. Craft the armor plates first, then craft the plates into armor. You can optionally add a lining part during crafting.

![helmet Recipe](https://imgur.com/YZtn49T.png)

### Elytra

Elytra require both wings (the main part) and a binding part to craft. The wings are non-functional by themselves and must be crafted with a binding. The wings may only be crafted with materials in the "cloth" and "sheet" categories, which includes sheet metal made in the metal press.

![elytra Recipe](https://imgur.com/4Tgf4vq.png)

### Curios

Curios (such as rings and bracelets) are a little different. They still require a blueprint for the main part, but also require jeweler's tools during the crafting process.

First, make the main part with the blueprint. Unlike most items, this will only accept metal materials (determined by material category). Second, use the jeweler's tools to craft an adornment. Finally, use the jeweler's tools to combine the parts into a finished curio item.

![Curios Recipe](https://imgur.com/E69fDZ8.png)

### Vanilla Conversion

Most vanilla items can be converted into a Silent Gear equivalent by simply placing it into a crafting grid by itself.

![Vanilla Conversion Recipe](https://imgur.com/5LStiJx.png)

### Grades and the Material Grader

Grades are material modifiers which apply an additional multiplier on some, but not all stats. Possible grades are, from lowest to highest: E, D, C, B, A, S, SS, SSS, and MAX. Materials can be graded in the material grader block. The grader requires catalysts to function, and consumes one catalyst per grading attempt. Grades are assigned randomly, based on a normal distribution.

![Material Grader](https://imgur.com/owiVyfN.png)

#### Catalysts

Catalysts are consumed when grading. The average grade depends on the tier of the catalyst, meaning that higher tier catalysts are more likely to give better grades.

There are five possible catalyst tiers, defined by item tags, but only three have items in them by default. The default catalysts are:

- Glowing dust (tier 1)
- Blazing dust (tier 2)
- Glittery dust (tier 3)

#### Re-grading

Materials that are already graded can be placed back into the grader to re-grade them. If the material grader rolls a higher grader, the material gets the new grade. If it rolls the same grade or lower, nothing changes but catalyst is still consumed.

### Compound Making (Alloys)

Certain blocks can be used to craft compound material items (often called "alloys" by the community!) These blocks include the metal alloyer, recrystallizer, and refabricator. These blocks are more mid/late game, so don't expect to be able to craft them right away. They can combine up to four materials into a single compound. Place two or more unique, simple (not compound) materials into the input slots, then toggle the "Work" button when you are happy with the result preview.

## Repairing

There are a couple of ways to repair gear, outlined below. Note that you cannot simply craft two similar gear items together to repair them.

### Repair Kits (Quick Repairs)

Repair kits allow gear items to be quickly repaired in any crafting grid. The repair kit can either be filled with materials ahead of time, or place the gear item, repair kit, and materials into any crafting grid. But the tier of the material must be the same or higher than that of the gear's primary part. No repairing your emerald pickaxe with cobblestone, that would be silly!

There are several tiers of repair kits. Each has a different capacity and efficiency modifier. Higher efficiency means you get more out of the materials used during repairs. Both values can be controlled in the config file.

![Repair Kit](https://imgur.com/lj3xCsP.png)

### Anvil Repairs

Anvils can be used to repair gear. You may get more out of the materials used for the repair, but it will also cost XP levels.

## Upgrade Parts

Some parts serve as upgrades for existing gear items. Some can be applied in any crafting grid, while others require a smithing table. Note that items can only have one upgrade of each type. Trying to add a new tip upgrade to an item that already has one will replace the existing upgrade, and possibly return the old one to you.

### Tip Upgrades

Tip upgrades apply stat bonuses and often useful traits to tools.

### Coatings

Coatings are upgrades which usually apply substantial stat bonuses. They can only be applied in a smithing table. The number of materials which can be used as coatings is very limited, and includes gold and netherite.

### Bindings and Grips

These are more minor upgrades which usually apply small stat bonuses (if any) and durability-improving traits.

### Miscellaneous Upgrades

- Red Card - Allows the item to break permanently, regardless of config settings.
- Spoon - Allows pickaxes (and only pickaxes) to mine anything a shovel can.

## World Generation

Silent Gear adds a few new things to the world, although it tries to be as unobtrusive as possible, keeping new ores and such to a minimum. These are some things you may find in the world, where to find them, and what you can do with them.

Note the new ores are named for the color of their alloy, rather than the base metal.

### Wild Flax

Wild flax plants can be found in some biomes, usually mountainous and plains-like biomes. Breaking wild plants will yield seeds, but not fibers or flowers. The seeds will grow normal flax plants which drop fibers, flowers, and seeds.

### Wild Fluffy Plants

Wild fluffy plants are found in less dry biomes, such as forests. Breaking wild plants will yield only seeds. The seeds will grow normal fluffy plants which will drop fluffy puffs and seed.

### Bort

Bort ore can be found deep underground in single blocks, not clusters. Mining yields one bort, or more with Fortune. Bort is required to craft adornments.

### Crimson Iron

Crimson iron ore can be found in all Nether biomes at most heights. Mining requires a pickaxe with a harvest level of 2 or higher (iron, etc.) Smelting raw crimson iron will yield crimson iron ingots, which can be used to make crimson steel (please use JEI to check recipes).

### Azure Silver

Azure silver ore can be found in the End at most heights. Mining requires a pickaxe with a harvest level of 4 (crimson steel, netherite-coated, etc.) Smelting raw azure silver yields azure silver ingots, which can be used to make azure electrum (use JEI for recipes).

### Netherwood

Netherwood saplings can be found in certain loot chests, mostly in the Nether. All Netherwood blocks (planks, etc.) are fire-proof. The leaves will drop saplings, netherwood sticks, and nether bananas. Smelting a log yields netherwood charcoal, instead of vanilla charcoal.
