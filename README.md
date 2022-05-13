# brax_mw2_package by @mp_rust

# Main Features
This mod was inspired by @plugwalker47 & requires IW4X 0.7.1
- Snipers, FAL, and Throwing Knife's do damage.
    - Any other weapons do not apply any damage.
- Host can move around before the match fully starts.
- Wallbang everything within the game utilizing the bg_surfacePenetration Dvar.
    - You may also adjust the allowed bullet range via 
- Always class changing with controllable class_change Dvar.
- Disable/Enable first blood with first_blood Dvar.
- Meter requirement to kill (prevents barrelstuff's) via level.pers["meters"].
- Ends game if it is NOT S&D.
- Always Ghillie regardless of current class.
    - Overkill classes are allowed.
    - Righthand TK + Glowstick sticks throughout rounds + class changes.
- ui_mp required for fixed xpbar.
    - images for blue arrows (teammates).
- Marathon Pro, Lightweight Pro, Steady Aim Pro, and Commando Pro are all assigned given automatically.
- Bots Spawn with No Perks & Weapons and Riot Shields Detached.
- Auto Bomb Plants (If you hit while on opposite team, it auto defuses and shows killcam).
- Tons of unique + useful features and much more - Please see #In-game Binds & #In-game Commands.

# In-game Binds
- Crouch + Knife refills everything (equipment, stuns, ammo).
- Prone + ADS + Knife will drop a stinger for canswaps (Host Only).

# In-game Commands [All Settings Stick Between Rounds]
- +tele = Teleport + Saves Bot's position (Host Only).
- +afm = Enable/Disable's Fast Mantle.
- +soh = Enable/Disable's Fast Reload.
- +die = Suicides.
- +as = Enables/Disable's Alt-Swap.
- +sl = Enables/Disable's Softland (HOST Only).
- +rh = Righthand TK (Can be weapon cancelled now).
- +glow = Glowstick (Can be weapon cancelled now).
- +tv = Enables/Disable's Thermal Vision Scope
- +is = Enables/Disable's Instashoots
- +ch = Enables/Disable's Console Like HUD
- +ks = Give random killstreak (3 to choose from).
- +ah = Enable/Disable's Almost Hit message (Must be 10m or more away in order for it to show).
- spawnBot 1 = Spawns 1 Bot.
    - These are all bindable with /bind [key] +command.

# DVAR Modifiers
/* Custom DVARS */
- level.pers["meters"] = 10; //Meters required to kill.
- setDvarIfUninitialized("first_blood", 0); //Enables/Disables First Blood
- setDvarIfUninitialized("class_change", 1); //Enables/Disables Always Class Change

/* Normal Client Dvars */
- setDvar("jump_slowdownEnable", 1); //Removes Jump Fatigue 
- setDvar("bg_surfacePenetration", 9999); //Wallbang Everything 
- setDvar("bg_bulletRange", 99999); //No Bullet Trail Limit
- setDvar("testClients_doMove", 0); //Bots do NOT Move
- setDvar("sv_allowAimAssist", 1); //Aim Assist Enable/Disable 
- setDvar("bg_bounces", 1); //Allow Bouncing 
- setDvar("bg_elevators", 1); //Allow Elevators 
- setDvar("bg_rocketJump", 1); //Allow Rocket Jumps 
- setDvar("bg_bouncesAllAngles", 1); //Allow Multi Bouncing 
- setDvar( "g_playerCollision", 0); //Removes Collision 
- setDvar( "g_playerEjection", 0); //Removes Ejection

/* Leave These Here */
- setDvar("cg_newcolors", 0); 
- setDvar("intro", 0); 
- setDvar("cl_autorecord", 0); 
- setDvar("snd_enable3D" , 1); 
- setDvar("bg_fallDamageMaxHeight", 300); 
- setDvar("bg_fallDamageMinHeight", 128);

# Setup Guide
- https://www.youtube.com/watch?v=Kp6z54jomVI&lc=UgxS07umS3znrIHryH14AaABAg
