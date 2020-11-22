**From KenL's original Tracker Jacker script.**  
  
An attempt to modernize Tracker Jacker and add new functionality as it becomes desired.  
  
**Change Log:**  
* 2020-09-12 - Updated heavily to pull all token markers enabled in the campaign and make them useable for condition/status effects  
* 2020-09-12 - Added -cleanSlate command (!tj -cleanSlate) to completely wipe all persistent state data should not be used lightly but if effects get stuck in the system this will clear them  
* 2020-09-20 - Added EOT link to turn indicator  
* 2020-09-20 - Added mouseover text to token marker selector list  
* 2020-09-25 - Added the ability to display favorites alphabetically, it remains in the first in first out order by default.   To get an alphabetical list change `!tj -listfavs` to `!tj -listfavs 1`  
* 2020-11-18 - Added the ability to save and load favorite.  The save creates a Handout called "TJFavsJSON", the load looks for that handout and loads the JSON from it.
* 2020-11-22 - The first actor's turn is now announced when starting the tracker.
