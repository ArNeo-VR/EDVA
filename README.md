# [EDVA](https://github.com/ArNeo-VR/EDVA) - VoiceAttack CMDs / profiles for Elite Dangerous.
Sharing VoiceAttack commands as text file and as a single profile release (.vap) file.  
This profile has only the commands, all third party plugins and applications required need to be installed manualy.  

# NOTE !! 
This profile is not plug-n-play it needs some work to get it going.  
I've not tested it on a clean computer.  
Applications and VoiceAttack plugins are **not** included.

## [VoiceAttack Commands](Commands)
Commands are exported to a text file, they are manualy exported and not fully up to date.
For the time beeing catagories are exported as a voiceattack profile (.vap) file. Until the full profile is tested and published.  
[List of commands can be found here](Commands#edva---commands)  

## [Profiles](Profiles) - [Releases](releases)
[[EDVA Profile] E:D EDVA-3.7.x(version)-profile](releases) *to be tested*  
Seperate [commands exported](Commands) to Text and Grouped in a profile-file (.vap)  
**note:** [\[release\] EDDI-3.7.2-profile](releases) (is the EDDI.vap file, needs to be imported seperately and included into the main profile)  

Other [Profiles](Profiles), 
- [global profile]-Profile, for switching to other profiles.
- [Off]-Profile(default), Only a Test command and the global profile commands for switching.
- [release]-2020c-Profile, My main profile 
- 'EDDI 3.x.x'(required to include in this profile)

## Voice Attack locations for Apps/Plugins and Sounds
### VoiceAttack [default] on x64 bit windows
<code>Plugins location "c:\Program Files (x86)\VoiceAttack\Apps"</code>  
<code>Sounds location "c:\Program Files (x86)\VoiceAttack\Sounds"</code>
#### My personal settings are, if you export your computer profile to another computer it will go with the userdata.
<code>Plugins location "c:\Users\\%USERNAME%\AppData\Local\VoiceAttack\Apps"</code>  
<code>Sounds location "c:\Users\\%USERNAME%\AppData\Local\VoiceAttack\Sounds"</code>
#### Depending if you want to use the same profile for all the users on the computer place it in:
*Folder 'c:\ProgramData\VoiceAttack' needs to be created and security-rights set to Modify for users group.*  
<code>Plugins location "c:\ProgramData\VoiceAttack\Apps"</code>  
<code>Sounds location "c:\ProgramData\VoiceAttack\Sounds"</code>

## [VA_Plugins](VA_Plugins) Voice attack plugins
- [EDDI](https://github.com/EDCD/EDDI) ([releases](https://github.com/EDCD/EDDI/releases)) is a companion application for Elite: Dangerous, providing responses to events that occur in-game using data from the game as well as various third-party tools.  
- [EDBinds](https://forum.voiceattack.com/smf/index.php?topic=564.0) ([download](http://www.voiceattack.com/bindED)) Reads keybindings from custom.binds file and creates variables  
- [EDBinds-3.0](https://forum.voiceattack.com/smf/index.php?topic=3564.0) ([GitHUB](https://github.com/alterNERDtive/bindED)) New forked version, not tested/checked it out.
- [ED-NeutronRouter](https://github.com/sc-pulgan/ED-NeutronRouter) ([releases](https://github.com/sc-pulgan/ED-NeutronRouter/releases)) [Neutron router tool] [forum](https://forums.frontier.co.uk/threads/ed-router-a-neutron-router.416021/)  
- [ED-Router ChrisZero](https://github.com/chriszero/ED-Router) ([releases](https://github.com/chriszero/ED-Router/releases)) [Neutron router tool app]  
- [ED-Router dominiquesavoie](https://github.com/dominiquesavoie/ED-Router) - ([releases](https://github.com/dominiquesavoie/ED-Router/releases)) [Neutron router tool app]  
- ~~[ReadGoogleSpreadsheetVAPlugin](https://github.com/trowgundam/ReadGoogleSpreadsheetVAPlugin) ([releases](https://github.com/trowgundam/ReadGoogleSpreadsheetVAPlugin/releases)) Used for reading data into VoiceAttack~~  
- Google spreadsheets are read from within a InLine C# script.  

- [ED Google sheet for variable key-presses](https://docs.google.com/spreadsheets/d/1LesTitHgI9L5cXfF-hgUVSKH4joeWj1AUAZWi--_GSI/edit) Used in voice attack for the key-stoke commands in voice-attack.

## Elite Dangerous - Applications/Tools (3rd party, not included)
- [ED Market Connector](https://github.com/EDCD/EDMarketConnector) ([releases](https://github.com/EDCD/EDMarketConnector/releases)) [It utilises the Journal files written by the game on the user's computer, together with data from the API Frontier Developments supplies in order to feed this data to various third party sites that the user may find useful.]
- [ED Engineer](https://github.com/msarilar/EDEngineer) ([releases](https://github.com/msarilar/EDEngineer/releases)) [EDEngineer is a basic app I've written to track materials, data and cargo acquired in Elite Dangerous. That way, we can also track progress of blueprints available from the Engineers.]
- [ED Discovery](https://github.com/EDDiscovery/EDDiscovery) ([releases](https://github.com/EDDiscovery/EDDiscovery/releases)) [EDDiscovery is a captain's log and 2D/3D map for Elite Dangerous players.]
- [ED PlanetBearing](https://github.com/Uriei/EDPlanetBearing) ([releases](https://github.com/Uriei/EDPlanetBearing/releases)) [Calculate the heading you need to follow to reach an specific point giving its coordinates on a planet in Elite Dangerous.]

## Windows applications
<code>Applications location "c:\Users\\%USERNAME%\AppData\Local\VoiceAttack\App"</code>  
- [NIRCMD](https://www.nirsoft.net/utils/nircmd.html) [NirCmd is a small command-line utility that allows you to do some useful tasks without displaying any user interface.]

## [VA_Sounds](VA_Sounds): Sounds used in commands
- ED_ThemeSounds-2015.zip - Elite themed sounds
- ED_SFX2018.zip - SFX miscellaneous 

# Setup using the profile
## EDVA profile Notes, VoiceAttack (VA) profile requirements

### Import Main profile
[More profile actions] > [Import profiles] > (select ~~[[EDVA Profile] EDVA-3.7-(version)-profile](Profiles)~~ file)  

### Include: [[release] EDDI-3.x.x-profile](Profiles)
Import profile: "[release] EDDI-3.x.x-profile.vap"  
- is required and needs to be included in the main profile.  
Main profile - [Edit profile] > [Options] > [Profile General] > 'Include commands from other profiles'  
[Add ...] select "[release] EDDI-3.x.x-profile"

### Execute commands at profile [loaded / unloaded]
Main profile [Edit profile] > [Options] > [Profile Exec] > 'Execute a command each time this profile is loaded/unloaded'  
Select the corresponding profile from the 'pull-down' menu.  
*"(((Elite Dangerous))) Profile Load"  ,  "(((Elite Dangerous))) Profile UnLoad"*

### Optional, Auto-load the Main profile when Elite is started
Main profile [Edit profile] > [Options] > [Profile General] > 'Enable profile switching for the following windows or processes'  
Tag the option enabled, Add text 'EliteDangerous64' in the field.

### Configure settings
- [Custom / Phonetic name] in > '(((MAIN))) Settings'

## Plugin custo extract/install locations
- [EDDI] [VA_Profile]\Plugins\EDDI\
- [EDbinds] [VA_Profile]\Plugins\bindEDplugin\
- [ED-ED-NeutronRouter] [VA_Profile]\Plugins\ED-NeutronRouter\
- [ReadGoogleSpreadsheetVAPlugin] [VA_Profile]\Plugins\ReadGoogleSheetVAPlugin\

## Applications custom extract/install locations
- [ED PlanetBearing] [VA_Profile]\App\EDPlanetBearing\
- [NirCMD] [VA_Profile]\App\NirCMD\

# Notes
...

# Other profiles
I've also other profiles: a 'Global profile', 'Off', 'Profile default', 'Profile default include', ...]

### 'Global profile'
In here are VoiceCommands that activate other profiles,  
*i.e. 'profile Elite', 'profile default', 'profile disable', 'Computer off'*  
You can add the 'Global profile' in VoiceAttack > [Options] > [General] > 'Global Profiles' > [Add ...]

### Profile 'Off' 
Is very limited and has a small set of commands. *Test, Exit voiceattack*

### 'Profile default' 
Has (Computer [Sleep; Restart; Shutdown now]) commands and 'Profile default include' is included.

### 'Profile default include'
Contains basic commands, start/stop/focus/show programs, text-functions copy/paste, playback/recording devices.
is used for including in selected profiles (Profile Elite) and not enable Computer shutdown commands from (Profile default).

---

# 1 EDVA
## 2 Commands:
Text line bla bla.
Secondline bla bla.

Third with blank line above. bla bla  
Fouth line with two spaces behind the third line.
### 3 Test

#### 4 Test

##### 5 Test
