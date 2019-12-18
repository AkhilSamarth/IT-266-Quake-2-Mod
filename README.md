# Quake Fortress 2 #
## Description ##

This is a mod for Quake 2 inspired by the class-based shooter Team Fortress 2. I hope you enjoy!

**Important info: make sure to copy-paste the contents of the ".misc files" folder (contains a .pak and a config file) into your mod folder, otherwise UIs and key binds will not work correctly!**

## Deliverables ##

I completed all four of the deliverables assigned to me, which were:
* Objective-based victory
* 5 classes
* 3 weapons per class
* Weapons upgrades

#### Objective-based victory ####
For this deliverable, I implemented a capture-the-flag system (note: this was made from scratch and does not use Quake 2's built-in CTF system in any way). In game, there is a translucent, blue backpack which serves as the intelligence ("intel", i.e. the flag). Once picked up, the player then takes the intel to a translucent, green, pyramid-like dropoff point. Upon delivering the intel three times, the player wins and the intel stops spawning. The intel and the dropoff spawn very close to the spawn point by default for easy testing.

#### Classes ####
There are five classes (listed below) in game, each with its own health and speed, similar to TF2's classes. Each class also has three unique, upgradable weapons which are loosely-inspired by TF2's own weapons (more details in "Weapons" section).

* Scout: high speed, low health
* Heavy: low speed, high health
* Soldier: medium-low speed, medium-high health
* Sniper: medium speed, medium health
* Demo: medium speed medium health

#### Weapons ####
There are 16 unique weapons in the game, 3 per class, with an additional modified, weakened blaster given to every class as a fallback for when ammo runs out completely. The following is a list of all the weapons, sorted by class, with a brief description of each:

* Scout
  * Scattergun: each click fires two quick, successive shotgun-like shots.
  * Pistol: semi-automatic blaster that shoots bullets.
  * Panic Attack: shotgun which starts with very high spread, but becomes more accurate as the player's health decreases.
* Heavy
  * Minigun: default chaingun, but with a delay between the mouse button being pressed and the firing starting.
  * Shotgun: tweaked version of default shotgun with higher spread and higher damage.
  * Escape Plan: shotgun which increases the player's speed as health decreases.
* Soldier
  * Rocket Launcher: tweaked default rocket launcher with faster, lower-damage rockets.
  * Bison: modified blaster with higher damage but slower projectiles.
  * Slow Death: rocket launcher that fires very slow but very high damage rockets.
* Sniper
  * Sniper Rifle: click to scope, click again to fire a high damage, high accuracy bullet.
  * SMG: default machine gun but with no recoil.
  * Huntsman: railgun that fires a tweaked blaster projectile.
* Demo
  * Grenade Launcher: tweaked default grenade launcher which fires faster grenades.
  * Direct Hit: launches grenades which do no splash damage, and so must hit a target directly.
  * Sticky Launcher: drops grenades which all explode in-sync after a few seconds.
  
#### Weapons Upgrades ####
Each of the 15 class weapons has an upgrade. Upgrades can be enabled or disabled with the "upgrade" or "downgrade" console commands respectively. The following is a list of all the weapons upgrades, sorted by class:
  
* Scout
  * Scattergun: higher accuracy (lower bullet spread).
  * Pistol: more bullets fired per shot and increased damage.
  * Panic Attack: higher accuracy for all healths.
* Heavy
  * Minigun: more bullets fired per shot and increased spread (to create a "barrage" of bullets).
  * Shotgun: many more bullets (roughly triple) fired per shot.
  * Escape Plan: double movement speed for all healths.
* Soldier
  * Rocket Launcher: faster, higher-damage rockets.
  * Bison: faster projectile.
  * Slow Death: faster, higher-damage rockets.
* Sniper
  * Sniper Rifle: significantly higher zoom on scope.
  * SMG: more bullets per shot.
  * Huntsman: faster projectile.
* Demo
  * Grenade Launcher: fires multiple grenades at once with slighly randomized spread for each.
  * Direct Hit: fires multiple grenades at once with slighly randomized spread for each.
  * Sticky Launcher: drops two grenades at once and has half the fuse.
  
#### Common Deliverables ####
I also completed the four common deliverables:
  
  * Shortcut for launching directly into mod
  * Mod in its own, separate folder in the Quake 2 directory
  * Visual indications
    * Temporary entities appear when the intel is being picked up or submitted.
    * Intel and dropoff models are a translucent blue/green respectively.
    * Some weapons have different models (to allow for differentiation between each weapon of a class).
  * User Interface updates
    * Logo modification on main menu to say "QF2" instead of "Quake 2".
    * F1 menu changed to a custom UI that displays basic instructions.
    * UIs on HUD for when intel is picked up/dropped off, as well as for victory.
