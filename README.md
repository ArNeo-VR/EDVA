# [EDVA](https://github.com/ArNeo-VR/EDVA#edva) - VoiceAttack profile for Elite Dangerous  
  
[Elite dangerous](https://www.elitedangerous.com/) is a space simulation game with a vast number of planets among the 1:1 scale recreation of the Milky Way galaxy and with lots of different things to do.  
This is my VA (VoiceAttack) profile that I made over the years, I'm currently using Oddesey release.  
  
This profile has [Commands](ProfileCommands#edva---commands), plugins and soundfiles for the game Elite Dangerous (E:D).  
Some commands are exported to [text files](ProfileCommands) to view its contens, they are manualy exported and not fully up-to-date.  
The profile is shared in a '...-Profile-zippackage.vax' file witch is actualy a zip-file, it contains all items in the profile.  
  
## NOTE !! plug-n-pray, it needs some work to get it going!!  
Some applications and third party plugins are required and need to be installed manualy.  

\
&nbsp;

## EDVA Topics
- [EDVA Profile notes](#edva-profile-notes)

### VoiceAttack application
- [VoiceAttack](#voiceattack) (Voiceattack application)  
- [VoiceAttack Locations](#voiceattack-locations-for-appsplugins-and-sounds-folders) VA Apps, Sounds and other folder locations in windows  
- [VA Commands & Apps (Plugins](#voiceattack--appsplug-ins) (EDVA | EDBinds, Route-plugins, Other)  
### Applications
- [Applications/Tools Elite Dangerous](#elite-dangerous--applicationstools-3rd-party-not-included)  
- [Applications Windows](#applications-windows)  
- [Other Documents](#other-documents)  
### EDVA profile
- [EDVA package installation](#edva-profile-setup)  
- [EDVA manual installation](#edva-profile-manual-installation-notes)  
\- [EDVA profile configuration](#edva-profile-configuration)  
- [EDVA Notes](#notes)  
- [EDVA History](#history)  

\
\
\
&nbsp;

# EDVA Profile notes
The commands are as close to the ingame text/keybindings as in the game.  
In the FSS-mode 'Target current signal', 'enter hangar', 'return to surface' 
Those command does as it says.  

### Commands text
pulls = off :: recognition sometimes is a bit off.  

### The 'Hangar' variable
This variable gets set by the same command, if not set correctly it won't execute.  
Using 'enter hangar', 'return to surface' in the hangar is dependent on a variable 'hangar'  
Some other commands also use/set this variable.  
To correct its value, Say 'Set hangar true' it sets the variable.  

### Board ship (SRV)
It is required to have the handbrakes enable while being under the ship to activate command.  

### Panel Tabs 
The (left) external-panel is required to be on the first tab initialy, commands are referenced to start from that position.  
In the SRV to use the repair and refuel command it needs to be on the inventory tab.  
I've used tab-tracking variables in the past, i'm slowly removing those (sys-tab, nav-tab) variables.  

### Map [ search; route; route system; ... ]
Some commands require to have the 'target system' in the text-clipboard.  

Also see [Profile commands readme](ProfileCommands#edva---commands)

\
\
\
&nbsp;

# Voice Attack
Voice-activated control for your PC games and apps. More information go here [VoiceAttack.com](https://Voiceattack.com)  

## Voiceattack Locations for Apps(Plugins) and Sounds folders
~~~
Applications location "c:\Users\\%USERNAME%\AppData\Local\VoiceAttack\App"
~~~

### VoiceAttack on windows [default] (Program Files (x86) for 32bit)
~~~
Plugins location "c:\Program Files\VoiceAttack\Apps"
Sounds location "c:\Program Files\VoiceAttack\Sounds"
~~~
#### My personal settings are, if you export your computer profile to another computer it will go with the userdata.
~~~
Plugins location "c:\Users\\%USERNAME%\AppData\Local\VoiceAttack\Apps"   
Sounds location "c:\Users\\%USERNAME%\AppData\Local\VoiceAttack\Sounds"
~~~
#### Depending if you want to use the same profile for all the users on the computer place it in:
~~~
Folder 'c:\ProgramData\VoiceAttack' needs to be created 
and security-rights set to Modify for users group.

Plugins location "c:\ProgramData\VoiceAttack\Apps"
Sounds location "c:\ProgramData\VoiceAttack\Sounds"
~~~

## VoiceAttack : Apps/Plug-ins
- [EDDI](https://github.com/EDCD/EDDI) ([releases](https://github.com/EDCD/EDDI/releases)) is a companion application for Elite Dangerous, providing responses to events that occur in-game using data from the game as well as various third-party tools.  
### EDBinds plugin
- [EDBinds original](https://forum.voiceattack.com/smf/index.php?topic=564.0) ([download](http://www.voiceattack.com/bindED)) Reads keybindings from custom.binds file and creates VA variable-hotkeys.  
\- [GitHub(Corysia)](https://github.com/Corysia/bindED) [*license note](https://github.com/Corysia/bindED/blob/master/License.md) EDBinds copied to github by Corysia.
- [EDBinds-3.0](https://forum.voiceattack.com/smf/index.php?topic=3564.0) ([GitHUB](https://github.com/alterNERDtive/bindED)) New forked version.
- [EDBinds tool](https://www.reddit.com/r/EliteDangerous/comments/o4oj3p/a_tiny_app_i_made_to_search_through_key_bindings/) ([GitHUB](https://github.com/ghorsey/edbindings)) Quickly search through Key Bindings.  
### Route plugins
- [ED-NeutronRouter](https://github.com/sc-pulgan/ED-NeutronRouter) ([releases](https://github.com/sc-pulgan/ED-NeutronRouter/releases)) [Neutron router tool] 
- [ED-Router ChrisZero](https://github.com/chriszero/ED-Router) ([releases](https://github.com/chriszero/ED-Router/releases)) [Neutron router tool app] [forum](https://forums.frontier.co.uk/threads/ed-router-a-neutron-router.416021/) 
- [ED-Router dominiquesavoie](https://github.com/dominiquesavoie/ED-Router) - ([releases](https://github.com/dominiquesavoie/ED-Router/releases)) [Neutron router tool app] 
### Other plugins
- ~~[ReadGoogleSpreadsheetVAPlugin](https://github.com/trowgundam/ReadGoogleSpreadsheetVAPlugin) ([releases](https://github.com/trowgundam/ReadGoogleSpreadsheetVAPlugin/releases)) Used for reading data into VoiceAttack~~  
Google spreadsheets are read from within a InLine C# script.  
- [VA Spotify plugin](http://www.litpixi.com/va-spotify/) ([Forum](https://forum.voiceattack.com/smf/index.php?topic=585.0;all))

\
\
&nbsp;

## Elite Dangerous : Applications/Tools (3rd party, not included)
### E:D Market Connector
- [E:D Market Connector](https://github.com/EDCD/EDMarketConnector) ([releases](https://github.com/EDCD/EDMarketConnector/releases)) It utilises the Journal files written by the game on the user's computer, together with data from the API Frontier Developments supplies in order to feed this data to various third party sites that the user may find useful.  
### E:D Market Connector Plugins
- [E:D MC Canonn](https://github.com/canonn-science/EDMC-Canonn) to automatically collect accurate science data from the galaxy and coordinate missions.  
- [E:D MC Habzone](https://github.com/Marginal/HabZone) This plugin helps explorers find high-value planets. It displays the "habitable-zone".  
- [E:D MC Screenshot](https://github.com/NoFoolLikeOne/EDMC-Screenshot) A plugin for EDMC that detects screenshot events are converts them to PNG format.  
### E:D Other applications
- [E:D Engineer](https://github.com/msarilar/EDEngineer) ([releases](https://github.com/msarilar/EDEngineer/releases)) EDEngineer is a basic app I've written to track materials, data and cargo acquired in E:D.
- [E:D Discovery](https://github.com/EDDiscovery/EDDiscovery) ([releases](https://github.com/EDDiscovery/EDDiscovery/releases)) EDDiscovery is a captain's log and 2D/3D map for Elite Dangerous players.
- [E:D PlanetBearing](https://github.com/Uriei/EDPlanetBearing) ([releases](https://github.com/Uriei/EDPlanetBearing/releases)) Calculate the heading you need to follow to reach an specific point giving its coordinates on a planet in Elite Dangerous.

\
\
&nbsp;

## Applications for Windows
- [NIRCMD](https://www.nirsoft.net/utils/nircmd.html) [NirCmd is a small command-line utility that allows you to do some useful tasks without displaying any user interface.]

&nbsp;

### Other documents
- [VoiceAttack : EDBinds](https://docs.google.com/spreadsheets/d/1LesTitHgI9L5cXfF-hgUVSKH4joeWj1AUAZWi--_GSI/edit) (Google sheet) variable-hoykeys used in voice attack for the E:D key-stoke commands.
  
\
\
&nbsp;

# EDVA profile Setup
### **!!! Importing a (.VAX) package file !!!**
### **!!! WILL AUTOMATICALLY OVERWRITE ANY EXISTING SOUNDS OR APP/PLUGIN FILES !!!**
### **!! Installation of the .VAX file is not tested !!**

## EDVA (VAX) profile-package release and VoiceAttack Profiles
EDVA profile (.vax)  package can be found in [the Releases](Releases), the .VAP files and other profiles files in [Profiles folder](Profiles).  
  
*Essentialy the .VAX file is a Zip-file if you rename the extention to .ZIP you can open it and see the files inside.*  
  
## Importing VAX-profile package
\<CODE>[Voiceattack-options] > [General] > 'Enable Plugin Support' must be disabled before importing.</CODE>  
After importing the following is required,  
- Re-enable 'Plugin Support'
- link the 'EDDI-X.X.X-profile' to the EDVA-profile as [described below](#the-eddi-profile-is-required-and-needs-to-be-included-in-the-main-profile)

\
\
&nbsp;

## EDVA profile manual installation Notes.
### Import the (.vap) profiles
<CODE>[More profile actions] > [Import profiles] > (select the file)</CODE>

## The EDDI-profile is required and needs to be included in the main profile.  
<CODE>[Edit profile] > [Options] > [Profile General] > 'Include commands from other profiles'</CODE>  
***The ... at the right***

## Editing the profile to Execute commands at profile (load unload)
<CODE>[Edit profile] > [Options] > [Profile Exec] > 'Execute a command each time this profile is loaded/unloaded'</CODE>   
  
Select the corresponding profile from the 'pull-down' menus.  
- *"(((Elite Dangerous))) Profile Load"*
- *"(((Elite Dangerous))) Profile UnLoad"*

## Optional, Auto-load the Main profile when Elite is started
<CODE>Main profile [Edit profile] > [Options] > [Profile General] ></CODE>  
<CODE>\> 'Enable profile switching for the following windows or processes'</CODE>  
  
Tag the option enabled, Add text 'EliteDangerous64' in the field.

\
\
&nbsp;

## EDVA profile configuration 
### Configure settings
- [Custom / Phonetic name] in > '(((MAIN))) Settings'  
  
## Plugin custom extract/install locations and variables
~~~
[VA_App]      (%LOCALAPPDATA%\VoiceAttack\App) Custom Applications E:D / Windows path  
[VA_Plugins]  (%LOCALAPPDATA%\VoiceAttack\Apps) VoiceAttack Plugins path  
[VA_Logs] & 
[Log_path]    (%LOCALAPPDATA%\VoiceAttack\Logs)  
~~~
  
~~~
[EDDI]        [VA_Profile]\Apps\EDDI\  
[EDbinds]     [VA_Profile]\Plugins\bindEDplugin\  

[ED-NeutronRouter]    [VA_Profile]\Plugins\ED-NeutronRouter\  
~~~
~~\[ReadGoogleSpreadsheetVAPlugin\] \[VA_Profile\]\Plugins\ReadGoogleSheetVAPlugin~~

~~~
[App_EDMC]            (%ProgramFiles(x86)%\EDMarketConnector\EDMarketConnector.exe)  
[App_EDEngineer]      (%APPDATA%\Microsoft\Windows\Start Menu\Programs\Max\EDEngineer.appref-ms)  
[App_EDDiscovery]     (%ProgramFiles%\EDDiscovery\EDDiscovery.exe)  
[App_EDPlanetBearing] (TXT:VA_APP\EDPlanetBearing\EDPlanetBearing.exe)  
~~~
  
## Applications custom extract/install locations
~~~
- [E:D PlanetBearing]    [VA_Profile]\App\EDPlanetBearing\  
- [NirCMD]               [VA_Profile]\App\NirCMD\  
- [E:D Market Connector] [default]   "C:\Program Files (x86)\EDMarketConnector\"
~~~

## Voiceattack log colors
Green - Command recognition
Red - Error or fault
Blue - 
Yellow - Notification
Purple - Profile change
Orange - System notifications
Blank - 
Grey - 
Pink -
Blanc - 
  
# Notes
Managing plugins with GitHub desktop, you can install plugins directly from github with a desktop application.  
If you clone the plugin directly to the use location of the Apps/Plugin locations  

## History
Shortly after playing Elite-Dangerous on a flat-screen I got me an Oculus Rift VR Headset.  
Controlling a keyboard got blindly cumbersome, therefor VoiceAttack (control) became a must for some keyboard commands.  
After I went from keyboard-mouse setup to a HOTAS it even got more needed using voicecommands.

Learning profiles from players on Twitch.tv shared their profile, from there I started.  
Later on I moved the profile notes and vap files to github.

