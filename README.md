# [EDVA](https://github.com/ArNeo-VR/EDVA) - VoiceAttack CMDs / profiles for Elite Dangerous
Sharing VoiceAttack (VA) commands as text file and as a single profile release (.vap) file.  
This profile has commands, plugins and soundfiles for the game Elite Dangerous (E:D).
  
# NOTE !! plug-n-pray, it needs some work to get it going!!  
Some applications and third party plugins are required and need to be installed manualy.  
  
[VoiceAttack Commands & Apps (Plugins](#voice-attack) (EDVA | EDBinds, Route-plugins, Other)  
[VoiceAttack Locations](#locations-for-appsplugins-and-sounds-folders) V:A Apps and Sounds folder locations  
  
[Applications Elite Dangerous](#elite-dangerous--applicationstools-3rd-party-not-included)  
[Applications Windows](#applications-windows)  
[Other Documents](#other-documents)  
  
[VoiceAttack EDVA Release and Profiles](#edva-profile-package-release-and-voiceattack-profiles) EDVA package en VAP files.  
  
[EDVA package installation](#edva-profile-package-release-and-voiceattack-profiles)  
[EDVA manual installation](#edva-profile-manual-installation-notes)  
\- [EDVA profile configuration](#edva-profile-configuration)  
  
# Voice Attack
Voice-activated control for your PC games and apps.
### EDVA VoiceAttack [Commands](Commands)
[VoiceAttack.com](https://Voiceattack.com) commands are exported to a [text files](Commands) to view the contense,  
they are manualy exported and not fully up to date.
## VoiceAttack : Apps (plugins)
- [EDDI](https://github.com/EDCD/EDDI) ([releases](https://github.com/EDCD/EDDI/releases)) is a companion application for Elite Dangerous, providing responses to events that occur in-game using data from the game as well as various third-party tools.  
### EDBinds plugin
- [EDBinds original](https://forum.voiceattack.com/smf/index.php?topic=564.0) ([download](http://www.voiceattack.com/bindED)) Reads keybindings from custom.binds file and creates variables.  
\- [GitHub(Corysia)](https://github.com/Corysia/bindED) [*license note](https://github.com/Corysia/bindED/blob/master/License.md) EDBinds copied to github by Corysia.
- [EDBinds-3.0](https://forum.voiceattack.com/smf/index.php?topic=3564.0) ([GitHUB](https://github.com/alterNERDtive/bindED)) New forked version.
### Route plugins
- [ED-NeutronRouter](https://github.com/sc-pulgan/ED-NeutronRouter) ([releases](https://github.com/sc-pulgan/ED-NeutronRouter/releases)) [Neutron router tool] 
- [ED-Router ChrisZero](https://github.com/chriszero/ED-Router) ([releases](https://github.com/chriszero/ED-Router/releases)) [Neutron router tool app] [forum](https://forums.frontier.co.uk/threads/ed-router-a-neutron-router.416021/) 
- [ED-Router dominiquesavoie](https://github.com/dominiquesavoie/ED-Router) - ([releases](https://github.com/dominiquesavoie/ED-Router/releases)) [Neutron router tool app] 
### Other plugins
- ~~[ReadGoogleSpreadsheetVAPlugin](https://github.com/trowgundam/ReadGoogleSpreadsheetVAPlugin) ([releases](https://github.com/trowgundam/ReadGoogleSpreadsheetVAPlugin/releases)) Used for reading data into VoiceAttack~~  
Google spreadsheets are read from within a InLine C# script.  

## Locations for Apps(Plugins) and Sounds folders
### VoiceAttack on x64 bit windows [default]
<code>Plugins location "c:\Program Files (x86)\VoiceAttack\Apps"</code>  
<code>Sounds location "c:\Program Files (x86)\VoiceAttack\Sounds"</code>  
#### My personal settings are, if you export your computer profile to another computer it will go with the userdata.
<code>Plugins location "c:\Users\\%USERNAME%\AppData\Local\VoiceAttack\Apps"</code>   
<code>Sounds location "c:\Users\\%USERNAME%\AppData\Local\VoiceAttack\Sounds"</code>  
#### Depending if you want to use the same profile for all the users on the computer place it in:
*Folder 'c:\ProgramData\VoiceAttack' needs to be created and security-rights set to Modify for users group.*  
<code>Plugins location "c:\ProgramData\VoiceAttack\Apps"</code>  
<code>Sounds location "c:\ProgramData\VoiceAttack\Sounds"</code>  

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

## Applications Windows
<code>Applications location "c:\Users\\%USERNAME%\AppData\Local\VoiceAttack\App"</code>  
- [NIRCMD](https://www.nirsoft.net/utils/nircmd.html) [NirCmd is a small command-line utility that allows you to do some useful tasks without displaying any user interface.]

### Other documents
- [VoiceAttack : EDBinds](https://docs.google.com/spreadsheets/d/1LesTitHgI9L5cXfF-hgUVSKH4joeWj1AUAZWi--_GSI/edit) (Google sheet) Variable key-presses used in voice attack for the E:D key-stoke commands.

# EDVA profile Setup
## EDVA (VAX) profile-package release and VoiceAttack Profiles
The profile package is an all in one package, contents is described in the [releases readme](Releases)  
EDVA profile-package can be found in [the Releases](Releases), the .VAP files and other profiles files in [Profiles folder](Profiles).  
  
Note that Importing the VoiceAttack package file (.VAX),  
<span style="color:red">### **!!! WILL AUTOMATICALLY OVERWRITE !!!**</span>  
any existing sounds or app/plugin files that have the same path and file name.  
  
*Essentialy the .VAX file is a Zip-file if you rename the extention to .ZIP you can open it and see the files inside.*  
***Installation of the .VAX file is not tested !***  
  
### Importing VAX-profile package
The [Voiceattack-options] > [General] > 'Enable Plugin Support' must be disabled before importing.
After importing it is required 
- to link the 'EDDI-profile' as [described below](#the-eddi-profile-is-required-and-needs-to-be-included-in-the-main-profile)
- Re-enable 'Plugin Support'

## EDVA profile manual installation Notes.
### Import the (.vap) profiles
[More profile actions] > [Import profiles] > (select the file)  
- [[EDVA Profile] EDVA-(version)-profile](Profiles)
- [[release] EDDI-(version)-profile](Profiles)

### The EDDI-profile is required and needs to be included in the main profile.  
Main profile - [Edit profile] > [Options] > [Profile General] > 'Include commands from other profiles' ***The ... at the right***

### Editing the profile to Execute commands at profile (load unload)
Main profile [Edit profile] > [Options] > [Profile Exec] > 'Execute a command each time this profile is loaded/unloaded'  
Select the corresponding profile from the 'pull-down' menu.  
- *"(((Elite Dangerous))) Profile Load"*
- *"(((Elite Dangerous))) Profile UnLoad"*

### Optional, Auto-load the Main profile when Elite is started
Main profile [Edit profile] > [Options] > [Profile General] > 'Enable profile switching for the following windows or processes'  
Tag the option enabled, Add text 'EliteDangerous64' in the field.

## EDVA profile configuration 
### Configure settings
- [Custom / Phonetic name] in > '(((MAIN))) Settings'  
  
## Plugin custom extract/install locations and variables
[VA_App] (%LOCALAPPDATA%\VoiceAttack\App) Custom Applications E:D / Windows path  
[VA_Plugins] (%LOCALAPPDATA%\VoiceAttack\Apps) VoiceAttack Plugins path  
[VA_Logs] & [Log_path] (%LOCALAPPDATA%\VoiceAttack\Logs)  
  
[EDDI] [VA_Profile]\Apps\EDDI\  
[EDbinds] [VA_Profile]\Plugins\bindEDplugin\  
[ED-ED-NeutronRouter] [VA_Profile]\Plugins\ED-NeutronRouter\  
[ReadGoogleSpreadsheetVAPlugin] [VA_Profile]\Plugins\ReadGoogleSheetVAPlugin\  
   
[App_EDMC] (%ProgramFiles(x86)%\EDMarketConnector\EDMarketConnector.exe)  
[App_EDEngineer] (%APPDATA%\Microsoft\Windows\Start Menu\Programs\Max\EDEngineer.appref-ms)  
[App_EDDiscovery] (%ProgramFiles%\EDDiscovery\EDDiscovery.exe)  
[App_EDPlanetBearing](TXT:VA_APP\EDPlanetBearing\EDPlanetBearing.exe)  
  
## Applications custom extract/install locations
- [E:D PlanetBearing] [VA_Profile]\App\EDPlanetBearing\  
- [NirCMD] [VA_Profile]\App\NirCMD\  
  
# Notes
Managing plugins with GitHub desktop, you can install plugins directly from github with a desktop application.
If you clone the plugin directly to the use location of the Apps/Plugin locations

## History
Shortly after playing Elite-Dangerous on a flat-screen I got me an Oculus Rift VR Headset.
Therefor VoiceAttack (control) became a must for some keyboard commands.
Learning profiles from players on Twitch.tv shared their profile, from there I started.
