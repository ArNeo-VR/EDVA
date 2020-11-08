# [EDVA](https://github.com/ArNeo-VR/EDVA) - Commands - ED 3.7 L
## EDVA [Main Startup]
**Profile Load** :  on Profile (un)load Command, [see settings](../../../#execute-commands-at-profile-loaded--unloaded)
**Profile UnLoad** :  
**(((MAIN))) Variables** :  
**(((MAIN))) Initialisation** :  
**(((MAIN))) Settings** :  
**(((MAIN))) Settings Audio** :  
**(((MAIN))) Applications** :  
**(((MAIN))) Write to log** :  

## EDVA [MainMenu Elite]
**Continue [solo, open, arena, training]** : Activates the action and goes to the menus and activates.  
*require that the cursor is set at the "Conintue" button of the main menu.*  

**Elite Menu** : Goes to the in game menu or submenus (see below).  
**Elite Audio [;Sound Effects; Music; Voice; Ship; Ships Voice; Playlist; Playlist; Galnet]**
**Elite Grahpics [;Display; Quality; 3D]**
**Elite Controls [;Mouse; Flight rotation; Driving; ...]

**Exit to Elite menu** : Exits to the game main menu.  
**Exit to Desktop, Quit Elite Dangerous** : Exit and closes the game.  

**Center** : Centers mousecursor, stops ship from turning.  
**Reset Rift** : Resets HMD/Rift headset position.  
**Reset Headlook** : Resets headlook mode to center.  

## EDVA [Help Find-Websites]
**Open [Coriolis, EDDB, EDSM, Elite-Forum,Reddit,Store,Support , Engineers, Fuelrats, Galnet, Inara, Ivona, Malics profile, Material trader, Material trader, Neutron plotter, Permits, Road to riches, Thargoid structures, Voiceattack, Twitch status, Sector map, Shipyard, List of Rares]**  
*Opens the webpage in the default browser.*  
  
**Pronounce this system.** *Modified EDDIcmd* : as it states  
**Where can I find [materials / data]** *Modified EDDIcmd* : Describes the location where you can find the item.  
**Open this Station / System in EDDB / Coriolis.** *Modified EDDIcmd* : More command combinations available, opens a webpage  
**Find [System states (boom, bust, famine, ...]** : Opens a page to EDSM and searches.  

## EDVA [App-Plugins]
Used for starting applications, the [app_variables] are set in the startup sequence.  
**note:** Applications are not included.  
*Example is in the Variables.txt file.*  
~~## ED 3.6 [App] NeutronPlotter~~
~~## ED 3.7 [Camera]~~

## EDVA [Ship Flight_Landing]
#### Launch
Docked at station: Starts Launch, moves ship up, retracts landing gear.  
Landed on planet: Starts Launch and activates engines, moves ship up a bit, retracts landing gear.

#### Boost
Closes cargoscoop and Boost upon boost key is pressed is detected.
#### Disengage
Disengages from supercruise.

#### Engage; Engage route; Engage next route; Engage travel jump; Travel jump; Superjump; Engage Superjump
*Command is experimental and buggy*
*rarely drops you out of supercruise if the target is not set correctly*
Engage - Engages supercruise / hyperspace (if there is a route it superjumps).  
Engage route - 
Engage next route - Select the next route in Galaxy map and Engages.  
Travel jump - FSD Cooldown delay and activates hyperspace to destination.  
Superjump - 



## EDVA [Ship_SRV functions]

#### Deploy SRV / Board Ship
Deploys SRV / Board ship requires the 'SRV Handbrake' is enabled.

#### [Lights; Full Beam] [; on; of; off; pulls; twice]
*About the first command I made*  
*- EDDI: {TXT:Status vehicle} , {TXT:Environment} , {BOOL:Status lights on} - Global command variables: {BOOL:full beam}*  
  
Ship/SRV lights, command checks the current lights status. 
If the lights are allready 'On', 'Off' or at 'Full Beam' it does nothing.  
'Lights' toggles the next light status, 'On/Off' lights does go to that status.  
Full-Beam / Lights twice it goes to to the Full-Beam only in the SRV.  

#### Ship/SRV Commands that either toggles or execute action.
Night vision [; on; off; pulls]  
[Analysis; Exploration; Combat; hud mode]  
Cockpit [; on; off; pulls]  
[deploy; retract;] Cargo Scoop; Cargo Hatch; Cargo Hooch  
[deploy; retract;] Landing Gear  
[deploy; retract;] Hardpoints  
Silent running [; on; off; pulls]  
Flightassist [; on; off; pulls]  
Rotational correction [; on; off; pulls]  
Orbit Lines [; on; off; pulls]  
[Engine Color; Weapon Color]  
[Shield cell; Deploy Shield; Shields up; Pop Shields]  
[Next; Previous;] Firegroup  
[deploy; fire;] [Chaff; ECM; Heat sink]  
[Next; Previous;] Firegroup  

#### SRV Commands that either toggles or execute action.
Deploy SRV  
Board ship; SVR Board ship  
[Recall;Dismiss] Ship  
SRV Transfer Cargo  
[Restock; Repair; Refuel] - Requires the system-panel to be on Synthesis
SRV Turret; Turret; Guns; Gun

## EDVA [Ship_SRV Panel Menu functions]
## EDVA [Ship_SRV Panel Menu]
## EDVA [Starport services]
## EDVA EDDI [Actions Modified]
## EDVA EDDI [Actions]
## EDVA [Main Startup Menu]
Continue Open  
Continue Solo  
Continue Private  
Continue Arena  
Continue Training  
Center - Centers mouse  
Continue   
## EDVA [Debug Functions]