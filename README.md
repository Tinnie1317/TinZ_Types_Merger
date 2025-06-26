# TinZ_Types_Merger
Tool to merge separate types.xml files for a local DayZ server. The intention is to speed up the process of adding modded types.xml files to the vanilla DayZ types.xml.

Current build:- v0.1

- Upload separate types.xml files and merge into the vanilla types.xml
- Edit types values (i.e nominal, lifetime, min, etc.)
- Remove items from the game via delete button (sets values for nominal and min to 0 to stop spawns. DOES NOT remove the <type> from the file)
- Search for individual items by name
- Export modified types.xml

Future builds:-

- Bulk edit (edit multiple items at once, e.g. set all nominal values to 10)
- Upload multiple types.xml files at once, and merge all simultaneouly
- Edit individual types.xml files in separate tabs
- Upload/Merge/Edit Spawnabletypes.xml
- Upload/Merge/Edit Events.xml
- Upload/Merge/Edit Eventspawns.xml


---------!! HOW TO USE !!----------
BEFORE CHANGING ANY FILES IT IS ADVISED YOU MAKE A BACKUP OF YOUR ORIGINAL FILES

- Open the .html file or use this link (https://tinnie1317.github.io/TinZ_Types_Merger/)
- Upload vanilla DayZ types.xml file
  (usually located C:\Program Files (x86)\Steam\steamapps\common\DayZServer\mpmissions\dayzOffline.chernarusplus\db)
  ("dayzOffline.chernarus" will change depending on which map your server is hosting)
- Upload the types.xml file you would like to merge
  (this will depend on the mod you are trying to add. be sure only to upload types file, not spawnable types)
- With both uploaded, click the "Merge Files" button
- A notification will show to confirm the merge
- To edit the types, simply click the box you wish to change.
- Once finished, click "Download Merged XML"
- Rename the new file types.xml and copy into the original types folder.
  (C:\Program Files (x86)\Steam\steamapps\common\DayZServer\mpmissions\dayzOffline.chernarusplus\db)



This is a build put together purely for convenience. There is no intention to monetize any part of this project for the foreseeable future. 
If you have any recommendations or feedback, feel free to contact or edit yourself. 


