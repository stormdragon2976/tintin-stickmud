# tintin-base-pack

To use this, create a pack for your MUD, then put the files from this into that. You can expand it as needed. Please follow the steps in the setup section after you have created the pack for yourr MUD.


## Setup


* rename mud.tin to something meaningful for your mud. You may want to call it something like "gamename.tin". You then would launch it with ./gamename.tin

* Find the line at the end of the file that reads #VARIABLE         {tintinPackName} {} and set your pack name in the second set of braces. Replace spaces with - or _.

* Update the MOTD file with whatever information you want displayed when the pack starts.

* Configure the information in modules/mud_info.tin
