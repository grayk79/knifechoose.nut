kc.nut
---------------

VScript to use all Knife models on a local server. 

Original Script from https://github.com/serkas001/knifechoose.nut


Installation and Usage
---------------

The kc.nut needs to be placed in `[your CSGO directory]/csgo/scripts/vscripts`
    
To run it ingame start a local server (for example 'Offline with Bots') and write `script_execute kc`
in your console. Then you can:

* Press INS (or Insert) on your keyboard to choose a Knife
* Press DEL (or Delete) on your keyboard to equip the chosen Knife
* Press END (or End) at every Roundstart to actually load the Script again. (It resets every Round)

You dont know which Keys I am talking about? I mean these above your arrowkeys:

![Keys](http://i.imgur.com/80HBEjD.png)
    
This Fork
-----------------

In this fork I plan to add some features like an little menu, and an AutoBind feature that makes it more convenient to give you the knife at every round start. It's most likely wont change core features or fix major bugs unless they are easy to implement but rather adds some Workarounds, remove clutter and add convenience.

Things I already did:

* Removed sv_cheats 1 as its not needed anymore
* Removed some Functions I didnt need
* Added a system that allows the Script to be controlled with Keys instead of the console
* Auto Setup of the Script for the First Round

    
    
