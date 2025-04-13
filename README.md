# BandwidthFix
Fix for UT2004 servers 10kbs bandwidth cap

## Usage
The engine is hardcoded to limit server bandwidth to 10kbs if the number of players is more than 16.  To bypass this limit, bandwidth fix works by setting the MaxPlayers value after this bandwidth check happens.  So to make it work, you must set MaxPlayers=16 or less in any values in UT2004.ini, and only in BandwidthFix set MaxPlayers to your number that you want.

This mutator is not needed if you have max players set to 16 or less.  The MaxPlayers value in BandwidthFix can be set to any value and is not limited to 32 players.  
