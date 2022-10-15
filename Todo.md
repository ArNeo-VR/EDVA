# Todo / wishlist notes E:D [EDVA]

# EDVA Commands
Firegroup commands add variable-keypress commands for SRV (Buggy)  
  
  
## EDVA Debug levels
3 Command notifications  
5 [default] (old Debug notifications)  
6 Notifications  
7 (old Debug write)  
  
  

## Odyssey
- E:D 3.8 [Ship_SRV functions], check in SRV / Ship
- Scan System | todo, select fixed firegroup and analysis mode, activate d-scanner

## Commands
Set target >>> elite back
[] E:D 4.0 [EDVA mappings] Key | Joystick | command+
Launch, Hud >> environment check !!! 

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

# Find [boom;bust;famine;civil unrest;civil war;election;expansion;lockdown;outbreak;war;none;retreat;investment;civil liberty;incursion]
? >> E:D 3.6 [Help Find] || 
? double/abandoned usage variables mySystemID, VB-script ?! 
? libraries, even used?


# Cleanup Settings Variables / Paths

Navigation filters, 
	[enable; disable]  %filtername% , only enabled does not reset.
~~Navigation filter, enable **** filter, only enabled does not reset.~~

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