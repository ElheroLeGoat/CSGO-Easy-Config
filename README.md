<h2 align="center" style="margin:0; padding:0;">
CS:GO Easy Config
</h2>
<p align="center">
The Easy tool for setting up a Local Training or game host in cs:go
</p>

### Installing
1. Download the zip file
2. Navigate to: `Steam\steamapps\common\Counter-Strike Global Offensive\csgo\cfg`
3. extract the contet of the zip file into the cfg folder.
4. Make a quick test by launching cs:go and inter a offline with bots or workshop map.
5. open up your console and type: `exec aim/init`

------------
## Usage
I have tried to make the system easy to navigate. but it do require you to remember some things.

### Getting started
```
exec aim/init
```
This is the starting place, it runs the default gamemode: aim/gm/vs

------------
```
exec aim/help
```
This command will show you the list of all possible commands, that way you'll never need to tab out of the game to check what commands that are possible.

------------
```
exec aim/start
```
This command nulls the freezetime and restarts the game. \
in case you select your weapon you need to run this command to actually begin the game. \
*Note: Running Any of the gamemodes will auto start the game*

------------
### Weapon selection
you are able to select the start gear for all around (this is good if you want to play a 1v1 ak only.)
```
exec aim/wp/prim-*
```
This command is used to set a default weapon for the primary weapon. \
The predefined weapons are:
1. ak
2. aug
3. awp
4. famas
5. galilar
6. m4a1-s
7. m4a4
8. mp7
9. sg
10. ssg

* * Is to be replaced with a name on the list.*

------------

```
exec aim/wp/sec-*
```
This command is used to set a default secondary weapon. \
The predefined weapons are:
1. deagle
2. glock
3. p250
4. usps

*\*Is to be replaced with a name on the list.*

------------
```
exec aim/wp/grenade-*
```
This command is used to set a grenadeset. \
The predefined grenadesets are:
1. **all** \
  Gives the player 2 Flashbangs, 1 HE grenade, 1 Molotov and  1 Smoke grenade
2. **flash** \
  Sets all players to spawn with 2 Flashbangs
3. **he** \
  Sets all players to spawn with a HE Grenade
4. **molo** \
  Sets all players to spawn with a Molotov
5. **smoke** \
  Sets all players to spawn with a Smoke grenade

*\*Is to be replaced with a name on the list.*

------------
```
exec aim/wp/*-reset
```
This command resets a weapon already set. \
The possible resets are:
1. **grenade** \
   the grenade setting.
2. **prim** \
  the primary weapon setting.
3. **sec** \
  the secondary weapon setting.

*\*Is to be replaced with a name on the list.*

------------
#### Different Gamemodes.
the systems default gamemode is Versus, but i have added multiple other gamemodes: Free For All Deathmatch, Team Deathmatch, training, kz, bhop and vs

```
exec aim/gm/ffadm
```
Executes the Free for all deathmatch, no need to do anything else.\
*Note: running `exec aim/init` again will reset the gamemode to default*

------------
```
exec aim/gm/tdm
```
Executes the Free for all deathmatch, no need to do anything else.\
*Note: running `exec aim/init` again will reset the gamemode to default*

------------
```
exec aim/gm/training
```
Executes the Training, no need to do anything else.\
*Note: running `exec aim/init` again will reset the gamemode to default*

------------
```
exec aim/gm/kz
```
Executes the KZ gamemode, no need to do anything else.\
*Note: running `exec aim/init` again will reset the gamemode to default*

------------
```
exec aim/gm/bhop
```
Executes the Bhop gamemode, no need to do anything else.\
*Note: running `exec aim/init` again will reset the gamemode to default*

------------
```
exec aim/gm/vs
```
Executes the default gamemode without resetting values from the previous modes.\
*Note: running `exec aim/init` again will reset the gamemode to default*