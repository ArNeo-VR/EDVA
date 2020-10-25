# EDVA - VoiceAttack CMDs / profiles for Elite Dangerous.

## EDVA profile Notes, VoiceAttack (VA) profile requirements
## Including other profiles,
### Include: [release] EDDI-3.7.0-profile
Import profile: "[release] EDDI-3.7.0-profile.vap" is required and needs to be imported as seperate profile.  
In the profile options ([Edit profile] > [Options] > [Profile General] > 'Include commands from other profiles':  
[Add ...] select "[release] EDDI-3.7.0-profile"

### Execute commands at profile [loaded / unloaded]
In the profile options ([Edit profile] > [Options] > [Profile Exec] > 'Execute a command each time this profile is loaded/unloaded':  
Select the corresponding profile from the 'pull-down' menu.
### Optional, Auto-load profile when Elite is started
In the profile options ([Edit profile] > [Options] > 'Include commands from other profiles'  
In the profile options ([Edit profile] > [Options] > [Profile General] > 'Enable profile switching for the following windows or processes'  
Tag the option enabled, Add text 'EliteDangerous64' in the field.

## Where Goes What, 
### VoiceAttack [default] on x64 bit windows
<code>Plugins location "c:\Program Files (x86)\VoiceAttack\Apps"</code>  
<code>Sounds location "c:\Program Files (x86)\VoiceAttack\Sounds"</code>

#### My personal settings are, this if you export your profile to another computer it will go with the userdata.
<code>Plugins location "c:\Users\%USERNAME%\AppData\Local\VoiceAttack\Plugins"</code>  
<code>Sounds location "c:\Users\%USERNAME%\AppData\Local\VoiceAttack\Sounds"</code>
#### Depending if you want to use the same profile for all the users on the computer place it in:
*Folder 'c:\ProgramData\VoiceAttack' needs to be created and security-rights set to Modify for users group.*  
<code>Plugins location "c:\ProgramData\VoiceAttack\Plugins"</code>  
<code>Sounds location "c:\ProgramData\VoiceAttack\Sounds"</code>


## [VA_Plugins](VA_Plugins) Voice attack plugins (3rd party, not included)
- [ReadGoogleSpreadsheetVAPlugin](https://github.com/trowgundam/ReadGoogleSpreadsheetVAPlugin) Used for reading data into VoiceAttack
- [EDDI](https://github.com/EDCD/EDDI) is a companion application for Elite: Dangerous, providing responses to events that occur in-game using data from the game as well as various third-party tools.
- [EDBinds](https://forum.voiceattack.com/smf/index.php?topic=564.0) Reads keybindings from custom.binds file and creates variables
- [ED-NeutronRouter](https://github.com/sc-pulgan/ED-NeutronRouter) [Neutron router tool]
- [ED-Router](https://github.com/chriszero/ED-Router) [Neutron router tool]

## [Profiles](Profiles) Full profiles, needs to be imported seperately
- [release] EDDI-3.7.0-profile 
[Profile commands](Commands) Commands exported to text and Grouped in a profile-file (.vap)

## [VA_Sounds](VA_Sounds): Sounds used in commands
- ED_ThemeSounds-2015.zip - Elite themed sounds
- ED_SFX2018.zip - SFX miscellaneous 

# Notes
...

### Other profiles
I've also other profiles: a 'Global profile', 'Off', 'Profile default', 'Profile default include', ...]

#### 'Global profile'
In here are VoiceCommands that activate other profiles,  
*i.e. 'profile Elite', 'profile default', 'profile disable', 'Computer off'*  
You can add the 'Global profile' in VA > [Options] > [General] > 'Global Profiles' > [Add ...]

#### Profile 'Off' 
Is very limited and has a small set of commands.  
#### 'Profile default' 
Has [Computer Sleep; Restart; Shutdown now] commands and 'Profile default include' is included.
#### 'Profile default include'
in VA, 
is used for including in selected profiles (Profile Elite) and not enable Computer shutdown commands.

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
