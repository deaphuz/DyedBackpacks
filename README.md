# DyedBackpacks
A brand new Slimefun addon adding the ability to dye your beloved backpacks!

> **Branch `slimefun5`: port to [Slimefun 5](https://github.com/Slimefun5/Slimefun5) (tested on Paper 26.3, Java 25).**
> Changes against the Slimefun 4 version: package `io.github.thebusybiscuit.slimefun5`, Slimefun's own
> `libraries.keys.NamespacedKey`, `CustomItemStack.create(...)`, `SlimefunUtils.getCustomHead(...)` instead of
> `dough.skins`, `SlimefunItemStack#item()` in the recipe, and name/lore read from `getItemMetaSnapshot()`
> (Slimefun 5 items may have no legacy lore).
>
> Build: Slimefun 5 is not published to a Maven repository, so install the jar from the
> [Slimefun 5 releases](https://github.com/Slimefun5/Slimefun5/releases) locally first, then package:
>
> ```
> mvn install:install-file -Dfile=Slimefun-5.3.3.jar -DgroupId=io.github.slimefun -DartifactId=Slimefun -Dversion=5.3.3 -Dpackaging=jar
> mvn package
> ```
- Dye all your backpacks by using the wools with the wanted color.
- Supports all 16 Minecraft default colors.
- Extensive configuration options! Disable/Enable backpack coloring per level.

## Download DyedBackpacks
You can download DyedBackpacks right here: [Development Builds](https://thebusybiscuit.github.io/builds/TheBusyBiscuit/DyedBackpacks/master/)

<p align="center">
  <a href="https://thebusybiscuit.github.io/builds/TheBusyBiscuit/DyedBackpacks/master/">
    <img src="https://thebusybiscuit.github.io/builds/TheBusyBiscuit/DyedBackpacks/master/badge.svg" alt="Build Server"/>
  </a>
</p>

## Discord
You can find Slimefun's community on Discord!
Click the badge down below to join the server for suggestions/questions or other discussions about this plugin.

<p align="center">
  <a href="https://discord.gg/slimefun">
    <img src="https://discordapp.com/api/guilds/565557184348422174/widget.png?style=banner3" alt="Discord Invite"/>
  </a>
</p>

## Open Source
This Project is open-source and licensed under the [MIT License](https://github.com/TheBusyBiscuit/DyedBackpacks/blob/master/LICENSE)
