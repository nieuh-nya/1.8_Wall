How to setup:

- put instanceNumber.txt in your .minecrafts
- press F3+P on all of your instances so they don't automatically pause after losing focus
- window titles are different from macros for other versions, so configure your OBS scenes accordingly
- you can use "Window title must match", so you don't have to reload scenes
- uses Numpad + instanceNumber to switch to scenes
- F12 for Wall-Scene

General things:

- NO SPACES IN YOUR FILE PATHS
- YOU WILL PROBABLY HAVE TO CHANGE DELAYS, increasing settingsDelay and guiDelay will most likely help if the macro is fucking up
- if renderDistance is set, you can only exit a world while unpaused
- don't reset right after unpausing, it will not work (only way to fix this would be a huge delay for every reset)
- settings changes will stil get ruined by lag spikes (for example: if you have renderDistance enabled, you might not want to reset all instantly after exiting a world)