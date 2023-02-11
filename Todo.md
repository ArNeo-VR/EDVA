# Todo Next release / Ideas / notes / wishlist - E:D [EDVA]

## EDVA Modules
Debug EDDI variables
- Firegroup
- Basic EDVA commands



## Basic EDVA commands / mini package
- Return to surface / Enter hangar, (remove Hangar Status requirements)
- Re- load/stock/fuel
- Lights
- Nightvision
- Orbit lines
- Cargo hatch
- Engine/Weapon color
- Landing gear
- Hardpoints
- Landing pads
- Firegroups
- Landing pad [1..45] [;left]


## ...
- Dismiss; Recall ship
- Cockpit
- Deploy SRV
- Disembark
- Board ship *fix disembark/srv*..
- *Firegroup*

#### Publish



# Signal sources
Stars
Asteroid Clusters
Planets and moons
Landfall planets and moons
Settlements
Stations
Fleet Carriers
Points of interest
Signal sources
Systems

# EDVA Commands
Starport market when shipyard is available its in a different position 1 down instead of 1 right.  
  
## EDVA Debug levels
3 Command notifications  
5 [default] (old Debug notifications)  
6 Notifications  
7 (old Debug write)  
  

## Odyssey
- E:D 3.8 [Ship_SRV functions], check in SRV / Ship  
- Scan System | todo, select fixed firegroup and analysis mode, activate d-scanner  

## Bug-issue report


### Further Description

### Step1

### Step2



## Commands
Set target >>> elite back
[] E:D 4.0 [EDVA mappings] Key | Joystick | command+
Launch >> environment check !!! 

## [Galaxy map] Menu structure
Menus differ on selected object (planet/station)

[Functions] Open map  
~~~
- edUI_LEFT > [Bookmarks]  
- edUI_UP > "Highlights Search the galaxy ..."  
- \<space> > Selects highlighted system > opens right menu.  
~~~

[Left]
~~~
Bookmarks [Default]
My Fleet
My active missions (can have no action)
Realistic mode
Map mode
User data mode
Powerplay mode
Population range
Trade Routes
Route Settings
Display options
~~~

[Back]
~~~
~~~

[Right] (only visible when a system gets selected)
~~~
Keybinding \<R-ctrl>-\<T> .. edUI_???? Cam select current system
- top and bottoms stops the scroll pressing up/down

0 System information [default]
1 Market information
	[edUI_Left] > Select a commodity 
2 Powerplay information
3 Stored ships4 System missions
5 Friends
6 Plot Route (when a systsm is selected)
7 Set target (when a systsm is selected)
8 Add to Bookmarks
9 View system mapsd
10 Buy Trending trade data
11 Target focus
12 Copy target name
~~~


## Todo
- Set Filters, change variables to ~LocalVARs
+mnav EDDI jumped
- debug write / notifications [defaults]
? Set: Settings Audio - Recording devices
? Set: Applications
-- note: (backslash is required at end of the path, becouse its used in the profile, needs to be renamed)

#### Find [boom;bust;famine;civil unrest;civil war;election;expansion;lockdown;outbreak;war;none;retreat;investment;civil liberty;incursion]
? >> E:D 3.6 [Help Find] || 
? double/abandoned usage variables mySystemID, VB-script ?! 
? libraries, even used?


# Cleanup Settings Variables / Paths

Navigation filters, 
	[enable; disable]  %filtername% , only enabled does not reset.
Navigation filter, enable filter, only enabled does not reset.

# old EDBinds addon https://github.com/Corysia/bindED

Be quiet;Radio silence;Stop talking [;EDDI] 1

Stand alone commands
- Debug functions (Write to log, Status Text, Vars: EDDI, Custom)
- Lights / Night vision
- Landing pad ##
- Starport 'Controls'
- Panel Functions (Role, External, Internal, Comms)
- Set Filters
- Ship Functions




((EDDI music))

# NoTrack, MainMenu, CQCMenu, SystemMap, GalaxyMap, GalacticPowers, CQC,
# DestinationFromHyperspace, DestinationFromSupercruise, Supercruise, Combat_Unknown, Unknown_Encounter,
# CapitalShip, CombatLargeDogFight, Combat_Dogfight, Combat_SRV, Unknown_Settlement,
# DockingComputer, Starport, Unknown_Exploration, Exploration

Write [Yellow] '... event music creates variables ... {TXT:EDDI music musictrack}' to log

# Music event can identify location and environment state.


{TXT:EDDI music musictrack}

-- IMO Vivo Pro 2
Gets pretty hot on the top front.
Controllers suck
Grabbing the button on the side is not good, sometimes grabbing the front camera with it to get a grip.
Dunno if its steam or vive, the in VR screen text is hardly readable

-- notes
? Landing gear, environment check ?
Some command rely on a custom bool variable "Hangar" this is not supplied by EDDI.
It gets set when you use the 'Enter hangar/Return to surface' command, or manualy 'set hangar true;false'

--- commands
Map [Search; Search system; Route system; Select; Route; Planet; Surface; Bookmark; System; Purchase ; Back] [;Exploration Data; Exploration; System Data; Trade Data; Trade]

--- ideas
- default firegroup plan, weapons, limpet,... enable with direct commands.

- Filter toggle one command.

Catagorize soundfx



