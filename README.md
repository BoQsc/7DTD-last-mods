7 days to die 7dtd

`buffLevelUpTracking` sometimes triggered and sometimes not, tested by using givexp and already existing debug statements of `buffLevelUpTracking`.  
They are printed to the player on level up, by pressing F1. However, the debug statements themselves do not get printed sometimes, leading to a buggy behaviour.



Nighttime scale mod does not work properly, when player re-enters the server, the clientside time gets bugged and fast forward.  
Meanwhile the existing players that do not relogin when fastforwarding happens, they experience clientside time speed but with synced serverside time.  
