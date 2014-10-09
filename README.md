Installation
=====================================

Copy FAR_Revive folder into your mission folder. Add this to the top of your init.sqf:

call compileFinal preprocessFileLineNumbers "FAR_revive\FAR_revive_init.sqf";

If you want to disable respawn and allow players to spectate, add "respawn=4;" to your description.ext.

Features
=====================================

* Revive Modes. 
  * 0 = Only medics can revive.
  * 1 = All units can revive.
  * 2 = Same as 1 but a medikit will be required. 0 is default.
* Death messages. Teamkills are shown as "x was injured by y"
* Ability to drag injured units
* Suicide option which you can use to respawn (if it's enabled) or just to kill yourself
* Bleedout. If a timeout is specified and you are not revived within the given time you will bleed out and die.
* Mute ACRE for unconscious units

Changelog
=====================================

v1.5
* [NEW] Unconscious units will not be able to use ACRE radio, hear other people or use proximity chat

v1.4d
* [NEW] Revive Modes. 0 = Only medics can revive, 1 = All units can revive, 2 = Same as 1 but a Medikit will be required
* [Fixed] Random black screens
* [Fixed] People dying randomly
* Code improvements

v1.4a
* Compatible with latest version of Arma 3
* [NEW] Casual mode. If enabled, all units will be able to revive (not just medics)

v1.4
* [NEW] Identifies medics without class names. You don't have to manually add class names
* [NEW] Bleedout
* [NEW] Death Messages

v1.3a
* [Fixed] Continuous beeping

v1.3
* [Fixed] Revive not working for some medics
* [Fixed] Medic not detected when inside a vehicle

v1.2
* [NEW] Dragging
* [Fixed] Revive not working if you died in a vehicle

v1.1
* Zero division error fixed

v1.0
* Initial version
