+++
title = 'Getting Started'
date = 2023-09-28T18:18:03+01:00
draft = false
+++

The following information only applies to Applied Energistics 2 in Minecraft 1.20 and newer.

## Getting The Initial Materials

![Meteor](/mods/ae2/ae2_getting_started.png)

To get started with Applied Energistics 2, one must first find a meteorite. These are fairly common and tend to leave massive holes in the terrain, so you've probably encountered one in your travels. If you haven't, you can craft a Meteorite Compass, which will point toward the nearest Mysterious Cube.

Once you have found a meteorite, mine into its center. You will find certus quartz clusters, certus quartz buds, budding certus blocks of various types, and a Mysterious Cube in the center.

Mine the certus quartz clusters and any certus quartz blocks you find. You can also pick up the budding certus blocks, but without silk touch they will degrade by 1 tier.

Do not break any flawless budding certus, as even with silk touch they will degrade to flawed budding certus, and it is impossible to repair them back to flawless.

Also mine the Mysterious Cube in the center of the meteorite to gain all 4 inscriber presses.

## Growing Certus Quartz

![Growing Certus Quartz 1](/mods/ae2/ae2_growing_certus_quartz_1.png)

Certus quartz buds will sprout from budding certus blocks, similar to amethyst. If you break a bud that is not finished growing, it will drop one Certus Quartz Dust, unchanged by fortune. If you break a fully grown cluster, it will drop four Certus Quartz Crystals, and fortune will increase this number.

There are 4 tiers of budding certus blocks: Flawless, Flawed, Chipped, and Damaged.

![Growing Certus Quartz 2](/mods/ae2/ae2_growing_certus_quartz_2.png)

Every time a bud grows by another stage, the budding block has a chance to degrade by one tier, eventually turning into a plain certus quartz block. They can be repaired (and new budding blocks created) by throwing the budding block (or a certus quartz block) in water with one or more Charged Certus Quartz Crystal.

![Growing Certus Quartz 3](/mods/ae2/ae2_growing_certus_quartz_3.png)

Flawless budding certus blocks will not degrade and will generate certus infinitely. However they cannot be crafted or moved with a pickaxe, even with silk touch. (they can be moved with spatial storage though)

By themselves, certus quartz buds grow very slowly. Luckily the Growth Accelerator massively accelerates this process when placed adjacent to the budding block. You should build a few of these as your first priority.

![Growing Certus Quartz 4](/mods/ae2/ae2_growing_certus_quartz_4.png)

If you don't have enough quartz to also make an Energy Acceptor or Vibration Chamber, you can make a Wooden Crank and stick it on the end of your accelerator.

Harvesting the certus automatically is [described here](example-setups/simple-certus-farm.md).

## A Quick Aside on Fluix

Another material you will need is Fluix, which you have already encountered in making growth accelerators. It is made by throwing charged certus, redstone, and nether quartz in water. Doing this automatically is "left as an exercise for the reader."

The Charger is required to produce Charged Certus Quartz Crystal., if you haven't made one already.

## Inscribing Some Processors

In your looting of a meteorite, you will have found four "presses" from breaking the Mysterious Cube. These are used in the Inscriber to make the three types of processor.

![Inscriber Silicon Press](/mods/ae2/ae2_silicon_press.png)
![Inscriber Logic Press](/mods/ae2/ae2_logic_processor_press.png)
![Inscriber Calculation Press](/mods/ae2/ae2_calculation_press.png)
![Inscriber Engineering Press](/mods/ae2/ae2_engineering_press.png)

The inscriber is a sided machine, much like the vanilla furnace. Inserting from the top or bottom places items in the top or bottom slots, and inserting from the side or back inserts into the center slot. Results can be pulled from the side or back.

To facilitate automation with hoppers (and possibly reduce pipe spaghetti), inscribers can be rotated with a Certus Quartz Wrench.

Produce a few of each type of processor in preparation for the next step, making a very basic ME system. Automating processor production is "left as an exercise for the reader".

## Matter Energy Tech: ME Networks and Storage

### What is ME Storage?

Its pronounced Emm-Eee, and stands for Matter Energy.

Matter Energy is the main component of Applied Energistics 2, it's like a mad scientist version of a Multi-Block chest, and it can revolutionize your storage situation. ME is extremely different than other storage systems in Minecraft, and it might take a little out of the box thinking to get used to; but once you get started vast amounts of storage in tiny space, and multiple access terminals are just the tip of the iceberg of what becomes possible.

### What do I need to know to get started?

First, ME Stores items inside of other items, called Storage cells; there are 5 tiers with ever increasing amounts of storage. In order to use a Storage Cell it must be placed inside either an ME Chest, or an ME Drive.

The ME Chest shows you the contents of the Cell as soon as its placed inside, and you can add and remove items from it as if it were a Chest, with the exception that the items are actually stored in the Storage cells, and not the ME Chest itself.

While the ME Chest is a great way to get introduced to the concept of ME, to really take advantage you need to set up an ME Network.

## Your Very First ME System

Now that you have all of the basic materials and machines for Applied Energistics 2, you can make your first ME (Matter Energy) system. This will be a very basic one, no autocrafting, no logistics, just nice, simple, searchable storage.

- Your ingredients list:
    - 1x ME Drive
    - 1x ME Terminal or ME Crafting Terminal
    - 1x Energy Acceptor
    - A few cables, either glass, covered, or smart, but not dense
    - A few storage cells, recommended of the 4k variety for a good mix of capacity and types (it would be more efficient to partition a mix of 4k and 1k but that's a complexity we won't go into now)

- Place the drive down.
 The energy acceptor (and several other AE2 devices) comes in 2 modes, cube and flat. They can be switched between in a crafting grid. If your energy acceptor is a cube, place it down next to the drive. If it's a flat square, place a cable on the drive and place the acceptor on that.
- Run energy into the energy acceptor with a cable/pipe/conduit from your favorite energy-generation mod.
- Place a cable on top of the drive (or otherwise at eye level) and place your terminal or crafting terminal on it.
- Put your storage cells into the drive
- Profit
- Fiddle with the terminal's settings
- Bask in your ultimate power and ability
- Realize that this network is, in the grand scheme, rather small

### Expanding your Network

So you have some basic storage, and access to that storage, it's a good start, but you'll likely be looking to maybe automate some processing.

A great example of this is to place a ME Export Bus on the top of a furnace to dump in ores, and a ME Import Bus on the bottom of the furance to extract furnaced ores.

The ME Export Bus lets you export items from the network, into the attached inventory, while the ME Import Bus imports items from the attached inventory into the network.

### Overcoming Limits

At this point you probably getting close to 8 or so devices, once you hit 9 devices you'll have to start managing channels. Many devices but not all, require a channel to function.

By default a network can support 8 channels, once you break this limit, you'll have to add an ME Controller to your network. this allows you to expand your network greatly. Smart cables will allow you to see how channels are routed through your network. Use them extensively when starting out to learn how channels act, or if you have a lot of redstone and glowstone.

[Tips and Tricks](tips-and-tricks.md)

[Back to Applied Energistics 2](../Applied-Energistics-2.md)