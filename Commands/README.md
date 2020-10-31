# EDVA - Commands - ED 3.7 L

## E:D 3.7 [Ship_SRV functions]+

#### [Lights; Full Beam] [; on; of; off; pulls; twice]
*About the first command I made*
*- EDDI: {TXT:Status vehicle} , {TXT:Environment} , {BOOL:Status lights on} - Global command variables: {BOOL:full beam}*  
Ship/SRV lights, command checks the current lights status. 
If the lights are allready 'On', 'Off' or at 'Full Beam' it does nothing.  
'Lights' toggles the next light status, 'On/Off' lights does go to that status.  
Full-Beam / Lights twice it goes to to the Full-Beam only in the SRV.  

#### Deploy SRV / Board Ship
Deploys SRV / Board ship requires that also the 'SRV Handbrake' is enabled.

## E:D 3.7 [Ship Flight_Landing]+
#### Launch
Docked at station: Starts Launch, moves ship up, retracts landing gear.  
Landed on planet: Starts Launch and activates engines, moves ship up a bit, retracts landing gear.

#### Boost
#### Disengage
#### Engage; Engage route; Engage next route; Engage travel jump; Travel jump; Superjump; Engage Superjump
*Command is experimental*
Engage - Engages supercruise / hyperspace (if there is a route it superjumps).  
Engage route - 
Engage next route - Select the next route in Galaxy map and Engages.  
Travel jump - FSD Cooldown delay and activates hyperspace to destination.  
Superjump - 