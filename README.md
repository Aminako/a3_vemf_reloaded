#ArmA3_exile_vemf_reloaded
###VEMFr; a mission system for ArmA3 Exile Mod
####Based on VEMF (Vampire's Epoch Mission Framework)
<br />
######INSTALLATION GUIDE<br />
```
Exile.MapName\init.sqf (contents) >> MPmissions\Exile.*nameOfMap*\init.sqf
```
```
Exile.MapName\description.ext (contents) >> MPmissions\Exile.*nameOfMap*\description.ext
```
```
exile_vemf_reloaded (contents) >> @ExileServer\addons\exile_vemf_reloaded.pbo
```
######CONFIGURATION GUIDE
Detailed information on how to modify settings are located in:<br />
```
exile_vemf_reloaded\config_override.cpp
```
*NOTE: do NOT modify any settings in config.cpp because when you update VEMFr, those changes will be overwritten. Use the config_override.cpp to handle your custom settings*
