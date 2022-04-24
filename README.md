# arma-3-life-spawn-ui

This is a new spawn ui for ArmA 3 RPG Life.

## Installation

A working installation of ArmA Life RPG Framework is required for a successful installation. Modifying the ArmA Life RPG Framework could cause errors – feel free to connect to our discord if you have a problem.

### Step 1

Download the newest release and extract the archive. Copy the folder "spawn" in your “cation” folder that can be found in the  root folder (subsequently called \<mission\>) of your mission.

### Step 2

Open \<mission\>/cation/cation_functions.cpp and insert

`#include "spawn\functions.cpp"`

and save the file.

### Step 3

Open \<mission\>/cation/cation_master.cpp and insert

`#include "spawn\config.cpp"`

and save the file.

### Step 4

Open \<mission\>/cation/cation_remoteExec.cpp and insert

`#include "spawn\remoteExec.cpp"`

and save the file.

### Step 5

Open the files \<mission\>/core/fn_initMedic.sqf, \<mission\>/core/fn_initCop.sqf, \<mission\>/core/fn_initCiv.sqf and \<mission\>/dialog/deathScreen.hpp and replace

`life_fnc_spawnMenu`

with

`cat_spawn_fnc_spawnMenu`

and save the file.

**That’s it!**

You have installed the cationstudio spawnscreen successfully!

## Configuration

You can adjust cam height in \<mission\>/cation/spawn/config.cpp.