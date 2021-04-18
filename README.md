# ![CC: ReTweaked](logo.png)
This is an WIP [fork](https://github.com/Merith-TK/cc-restitched) of a [fork](https://github.com/Zundrel/cc-tweaked-fabric) of a [fork](https://github.com/ArchivedProjects/cc-tweaked-fabric)  of a [fork/port](https://github.com/mystiacraft/cc-tweaked-fabric) of an [update/port/fork](https://github.com/SquidDev-CC/CC-Tweaked) of [ComputerCraft](https://github.com/dan200/ComputerCraft), adding programmable computers,
turtles and more to Minecraft.

*it runs and works-ish*

PRs welcome

## What?
ComputerCraft is the first mod that I have ever used and also one of my favorite mods.
The only problem I have with is... the old textures so I manually am fixing and tweaking them along with some other things.

## Contributing
Any contribution is welcome, be that using the mod, reporting bugs or contributing code. In order to start helping
develop CC:T, you'll need to follow these steps:
-**Fork the repository:** Make a github account press the fork button.
-**Edit the code** Edit the code and make your changes.
-**Turn on github actions* Press the 'Enable Workflows' button or set up a new gradle workflow and copy-paste [this](https://github.com/3prm3/cc-retweaked/blob/v1.94.2/.github/workflows/gradle.yml) into your worklow's yml, dowload the artifacts and put in your mods folder and check for bugs.
-**Make a pull request** press the 'New Pull Request' button and set the repository on the left to 3prm3/cc-retweaked and set the repository on the right to your repository.

## Bleeding Edge Builds
Bleeding edge builds can be found [here](https://github.com/3prm3/cc-retweaked/actions) at github actions to simplify things 

## Community
If you need help getting started with CC: Tweaked, want to show off your latest project, or just want to chat about
ComputerCraft, here is the [forum](https://forums.computercraft.cc/) 

## Relation to CCTweaks?
This mod has nothing to do with CCTweaks, though there is no denying the name is a throwback to it. That being said,
several features have been included, such as full block modems, the Cobalt runtime and map-like rendering for pocket
computers.


## Known Issues
Main Known issue
* Mods that add blocks that can be used as peripherals for CC:T On forge, dont work with CC:R.
	* This is because of the differences between forge and fabric, and that mod devs, to my knowledge have not agreed upon a standard method in which to implement cross compatibility between mods,
* Storage Peripherals throw a java "StackOverflowError" when using `pushItems()`, 
    * Work around, you are probably using `pushItems(chest, 1)` or simular. please use `pushItems(chest, 1, nil, 1)`. 

## Known Working mods that add Peripherals
* Please let me know of other mods that work with this one
	* Better End
	* Better Nether
