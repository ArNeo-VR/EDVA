# [EDVA](../../../EDVA) - Profiles

### [[release] [EDVA]-(version)-Profile](https://github.com/ArNeo-VR/EDVA)  
[Edit profile] > [Options] > [Profile General] > 'Include commands from other profiles'  
[Add ...] select "[release] EDDI-3.7.0-profile"  

### [release] [global profile]-Profile.vap
Set as 'global profile' in VoiceAttack Options (Icon down-right).  

### [release] [Off]-Profile.vap
Set as 'Default Profile on Startup' in VoiceAttack Options (Icon down-right).  

### [release]-2020c-Profile.vap
[Edit profile] > [Options] > [Profile General] > 'Include commands from other profiles'  
[Add ...] select "[Off]"   
  
Set profile load / unload in Profile-options > [Profile Exec] 'Execute a command each time this profile is loaded / unloaded'  

**note:**  
[\[release\] EDDI-(version)-profile](Releases) (is the EDDI.vap file, needs to be imported seperately and included into the main profile)  
Documented [commands exported](commands in plain text) grouped in a profile-file (.vap)  

- [release] [EDVA]-(version)-profile, Main Elite Dangerous Voiceattack profile  
- [release] EDDI-(version)-profile, EDDI default commands needs to be included in the main-profile.
Other [Profiles](Profiles)
- [global profile]-Profile, for switching to other profiles  
- [Off]-Profile(default), Only a Test command and the global profile commands for switching  
- [release]-2020c-Profile, My main profile  


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
