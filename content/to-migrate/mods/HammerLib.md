+++
title = 'HammerLib'
date = 2023-11-30T01:29:32Z
draft = false
+++

Utility mod that contains really useful code for quite a few mods.

## This library provides

- Simple, annotation-based content registration.
    - For Blocks, HammerLib automagically registers BlockItem(s). If you want to disable BlockItem(s), let your block implement INoItemBlock, ICustomBlockItem, or ICreativeTabBlock, depending on what you want to achieve.
    - For BlockEntity rendering, custom BlockEntityType constants may have additional @TileRenderer, pointing to an IBESR<Tile> class.
- Old-styled language parsers in format of "key=value", instead of JSONs (the file names and format is like in older game versions, but you need to call LanguageAdapter.registerMod(MOD_ID); inside your mod's constructor for it to register.
- Mod Source checks, that allow you to check if the mod was downloaded from adware/malware sites, AND warn users about it.
- Java-based recipe registration with a simple RegisterRecipesEvent, that runs on HammerLib.EVENT_BUS, allowing you, as a developer, to register crafting recipes like before, with code.
- Java-based tag population, with BuildTagsEvent, that runs on HammerLib.EVENT_BUS.
- Vastly simplified networking, using Network class, and IPacket + INBTPacket to allow for flawless and intuitive packet code development.
- Wrappers for block harvesting, that has been moved over to tags - BlockHarvestAdapter
- Field-based NBT serialization, so that you don't make a typo/forget to write serialization/deserialization code.
- Good old TileEntity wrappers, with TileSyncable and TileSyncableTickable, that allow synchronization of initial state, as well as registering properties that will be synchronized independently.
- ContainerAPI for BlockEntities, allowing to avoid MenuType<?> altogether (no need to register screen providers, menu types etc)
- ItemStack -> Color[] API, with TexturePixelGetter.getAllColors
- Annotation-based custom model loaders (@LoadUnbakedGeometry on IUnbakedGeometry<SELF>), avoids using the geometry loader class by making a common wrapper.
- ...And a whole lot more!
 

And a lot of rich features for mod devs.

## Links

[Modrinth (Source for this article)](https://modrinth.com/mod/hammer-lib)

[Source Code](https://github.com/dragon-forge/HammerLib)

License: ARR