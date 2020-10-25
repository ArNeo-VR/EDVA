# EDVA - VoiceAttack CMDs / profiles for Elite Dangerous.

## EDVA profile Notes, VoiceAttack (VA) profile requirements
#### Including other profiles
In the profile options ([Edit profile] > [Options] > [Profile General] > 'Include commands from other profiles'
!"[release] EDDI-3.7.0-profile.vap" is required and needs to be imported as seperate profile.
- 'Include commands from other profiles' [Add ...] select "[release] EDDI-3.7.0-profile"
#### Execute commands at profile [loaded / unloaded]
In the profile options ([Edit profile] > [Options] > [Profile Exec] > 'Execute a command each time this profile is loaded/unloaded'
- Select the corresponding profile from the 'pull-down' menu.
#### Optional, Auto-load profile when Elite is started
In the profile options ([Edit profile] > [Options] > 'Include commands from other profiles'
In the profile options ([Edit profile] > [Options] > [Profile General] > 'Enable profile switching for the following windows or processes'
- Tag the option enabled, Add text 'EliteDangerous64' in the field.

## Where Goes What, 
### VoiceAttack [default] on x64 bit windows
- plugins location "c:\Program Files (x86)\VoiceAttack\Apps"
- sounds location "c:\Program Files (x86)\VoiceAttack\Sounds"
#### My personal settings are, this if you export your profile to another computer it will go with the userdata.
- plugins location "c:\Users\%USERNAME%\AppData\Local\VoiceAttack\Plugins"
- sounds location "c:\Users\%USERNAME%\AppData\Local\VoiceAttack\Sounds"
#### Depending if you want to use the same profile for all the users on the computer place it in:
- plugins location "c:\ProgramData\VoiceAttack\Plugins"
- sounds location "c:\ProgramData\VoiceAttack\Sounds"
Folder 'c:\ProgramData\VoiceAttack' needs to be created and security-rights set to Modify for users group.

## VA_Plugins: Voice attack plugins (3rd party, not included)
- [ReadGoogleSpreadsheetVAPlugin](https://github.com/trowgundam/ReadGoogleSpreadsheetVAPlugin) Used for reading data into VoiceAttack
- [EDDI](https://github.com/EDCD/EDDI) is a companion application for Elite: Dangerous, providing responses to events that occur in-game using data from the game as well as various third-party tools.
- [EDBinds](https://forum.voiceattack.com/smf/index.php?topic=564.0) Reads keybindings from custom.binds file and creates variables
- [ED-NeutronRouter](https://github.com/sc-pulgan/ED-NeutronRouter) [Neutron router tool]
- [ED-Router](https://github.com/chriszero/ED-Router) [Neutron router tool]

## Profiles: Full profiles, needs to be imported seperately
- [release] EDDI-3.7.0-profile 

## VA_Sounds: Sounds to be used in commands
- ED_ThemeSounds-2015.zip
- ED_SFX2018.zip
- Misc other, to be created.

## Notes
...
I've also other profiles [Global profile, Off, Profile default, ...]
- Global profile in VA > [Options] > [General] > 'Global Profiles' > [Add ...]
*In here are VoiceCommands that activate other profiles, i.e. 'profile Elite', 'profile default', 'profile disable'*
- Profile default in VA, included in selected profiles (Profile Elite)
Basic commands used are, Computer(to activate profile default, Computer sleep/reboot/shutdown, abort command.)
- I've also a Base-default profile with basic commands that are used when VA is enabled.


# 1 EDVA
## 2 Commands: VoiceAttack seperate commands
### 3 Test
#### 4 Test
##### 5 Test
