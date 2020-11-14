# [EDVA](../../../../EDVA) - Commands - ED 3.7 M
## EDVA [Main Startup]
**Profile Load** ::  on Profile load Command, [see setup](../../../../EDVA/#execute-commands-at-profile-loaded--unloaded)  
**(((MAIN))) Load Variables** :: Loads variables from profile, set required for Initialisation.  
**(((MAIN))) Initialisation** :: Load Key-binds, set preferences from loaded variables.  
**(((MAIN))) Settings** :: Commander NAME/Phonetic, Path's, Applications.  
**(((MAIN))) Settings Audio** :: Set recording and playback devices / volumes, used sounds.  
**(((MAIN))) Applications** :: START / MOVE Applications.  
**(((MAIN))) Write to log** :: Show variables to log.  
**Profile UnLoad** ::  on Profile unload Command

## EDVA [MainMenu Elite]
**Continue [solo, open, arena, training]** :: Activates the action and goes to the menus and activates.  
*requires that the cursor is set at the "Continue" button of the main menu.*  

Activates the in game menu and goes to the submenu/selection.  
**Elite [Menu; Options; Help; Social; Friends; groups; blocked; report player; ...] [;Menu]**  
**Elite Audio [;Sound Effects; Music; Voice; Ship; and-more...]**  
**Elite Grahpics [;Display; Quality; 3D]**  
**Elite Controls [;Mouse; Flight rotation; Driving; and-more...]**  

**Exit to Elite menu** :: Exits the game to MainMenu.  
**Exit to Desktop, Quit Elite Dangerous** :: Exit and closes the game.  

**Center** :: Centers mousecursor, stops ship from turning.  
**Reset Rift** :: Resets HMD/Rift headset position.  
**Reset Headlook** :: Resets headlook mode to center.  

**[Show; Hide] [Framerate; Connection Status; Graphical debug]** :: Show data in desktop application  
**Show scores**  

## EDVA [Debug Functions]  
**status text** :: Shows EDDI varables  
**[Status] [Hardpoints; Docked; Supercruise; Flight assist; Drive assist; Handbrake; Landinggear; Silent Running; Cargo Scoop; Lights on; Night Vision]** :: *Writes and says(TTS) EDDI variable Status*  

**Used for debuging/setting variables:**  
[Set; Status; Reset] [Hangar; cockpit; orbit lines; Elite Menu; Camera] [;true; false; not set] :: BOOL variables  
[Set; Status; Reset] [Starport services; Full beam] [;true; false; not set] :: BOOL variables  
[Set; Status; Reset] [FrameRate; ConnectionStatus; GraphicalDebug] [;true; false; not set] :: BOOL variables  
[Status; Set; Reset; Get; Put] [Debug Write; Debug Notifications; Vocal mode; EDDIVoice] [;true; false; not set] :: Stored variables in profile.  
[Set; Status; Reset; Get; Put] [nav-tab; sys-tab;galaxy-tab] [;0..6 ; not set] :: Stored variables in profile.  


## EDVA [Apps-Plugins]
## Elite Dangerous - Applications/Tools (3rd party, not included)
*Used for starting applications, the [app_variables] are set in the startup sequence.*  
[Start;Close] [;Elite;] [Discovery] :: [ED Discovery](https://github.com/EDDiscovery/EDDiscovery)  
[Start;Close;Move] [;Elite;] Engineer :: [ED Engineer](https://github.com/msarilar/EDEngineer)  
[Start;Close;Move] [;Elite;] Market Connector :: [ED Market Connector](https://github.com/EDCD/EDMarketConnector)  
[Start;Close;Move;Update] [;Elite;] [PlanetBearing; Compas] :: [ED PlanetBearing](https://github.com/Uriei/EDPlanetBearing)  
*Applications are start from variables (Main Startup), Example is in the Variables.txt file.*  
**note:** Applications are not included.  

~~## ED 3.6 [App] NeutronPlotter~~  
~~## ED 3.7 [Camera]~~  

## EDVA [Help Find-Websites]
**Open [Coriolis, EDDB, EDSM, Elite-Forum-Reddit-Store-Support , Engineers, Fuelrats, Galnet, Inara, Ivona, Malics profile, Material trader, Material trader, Neutron plotter, Permits, Road to riches, Thargoid structures, Voiceattack, Twitch status, Sector map, Shipyard, List of Rares]**  
*Opens the webpage in the default browser.*  
  
**Pronounce this system.** *Modified EDDIcmd* :: as it states  
**Where can I find [materials / data]** *Modified EDDIcmd* :: Describes the location where you can find the item.  
**Open this Station / System in EDDB / Coriolis.** *Modified EDDIcmd* :: More command combinations available, opens a webpage  
**Find [System states (boom, bust, famine, ...]** :: Opens a page to EDSM and searches.  

## EDVA [Ship Flight_Landing]
#### Launch
Ship Docked at station: Starts Launch, moves ship up, retracts landing gear.  
Ship Landed on planet: Starts Launch and activates engines, moves ship up a bit, retracts landing gear.

#### Boost
Closes cargoscoop and Boost upon boost key is pressed is detected.

#### Disengage
Disengages from supercruise.

#### Engage; Engage route; Engage next route; Engage travel jump; Travel jump; Superjump; Engage Superjump
Engage - Engages supercruise / hyperspace (if there is a route it superjumps).  
Engage route - 
Engage next route - Select the next route in Galaxy map and Engages.  
Travel jump - FSD Cooldown delay and activates hyperspace to destination.  
Superjump - 
*Command is experimental, drops you out of supercruise if the target is not set correctly*

## EDVA [Ship_SRV functions]

#### Deploy SRV / Board Ship
Deploys SRV / Board ship requires the 'SRV Handbrake' is enabled.

#### [Lights; Full Beam] [; on; of; off; pulls; twice] 
Ship/SRV lights, command checks the current lights status.  
If the lights are allready 'On', 'Off' or at 'Full Beam' it does nothing.  
'Lights' toggles the next light status, 'On/Off' lights does go to that status.  
Full-Beam / Lights twice it goes to to the Full-Beam only in the SRV.  
*About the first command I made*  

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
