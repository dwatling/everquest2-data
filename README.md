# EverQuest 2 Data

This is just a collection of data that I've extracted from EQ2 game log files. For me, it's useful as I'm using it to populate data for a website I've recently started working on, https://eq2db.com . I wanted to make it public in case anyone else finds it useful.

I'm not entirely happy with the layout of the files, so they might change at some point in the future. There is also still a lot of data missing. But, for the most part, it does include:

1. Zone data (name, zonerect, shinies, shiny locations, resource nodes, resource node locations)
2. NPC data (name, location, zone data, drops, merchant data)
3. Faction data (name, description)

Known issues:
1. Full dialogs between player and NPC are not captured. NPC dialog is the only thing recorded. 
2. Some NPCs have the same name, but different purpose, and are completely separate entities. The current format doesn't support this. Example: "a mysterious Quellithulian" in Moors of Ykesha (exp05_rgn_innothule)
3. Level and difficulties for NPCs are actually a range and it can even depend on a physical location within a dungeon (i.e. closer to the entrance is easier, but deeper is more difficult). 