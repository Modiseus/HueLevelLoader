Please head over to https://github.com/Modiseus/HueLevelLoaderMod for a new level loader that works as a mod inside the game.

# HueLevelLoader
I created HueLevelLoader to help practicing levels for the Hue speedrun.
It allows you to load any level and unlock the necessary colors to beat it.
# Getting Started

## Prerequisits

First download the lastest version of the HueLevelLoader.CETRAINER from the [release page](https://github.com/Modiseus/HueLevelLoader/releases/latest).

To use the HueLevelLoader.CETRAINER you need to install Cheat Engine.
Download it from https://www.cheatengine.org/ and install it.

## Starting HueLevelLoader

* Make sure that the game is running.
* Start Cheat Engine
* Use `File -> Load` or press `Ctrl+O`
* Select the `HueLevelLoader.CETRAINER` file that you downloaded.

## Loading a level

To load a level you first have to find it in the level list. The preview image can help you with this. The levels are sorted into the different regions of the map.

After you have selected a level click the `Select` button to confirm the selection.

If you now go back into the game and hit `start new game` and confirm with `yes` the game will load the selected level.

## Unlocking colors

After you load a level you will not be able to use the color wheel because all the colors are still locked. You can unlock the colors that are necessary for the current level by clicking the button with the text `Set to level default`.

You can also unlock or lock individual colors using their corresponding buttons.

## Some things to note 

* To start a new game like normal after using the HueLevelLoader you have to close and restart the game.

* HueLevelLoader works by changing which level the game loads when you start a new game. This has the side effect that all your progress (colors unlocked, beakers unlocked, map areas unlocked) will be reset.

* The HueLevelLoader also displays the state of the `CurrentLevel` and `LastDoor` variables. This can help you understand how death warps work.
