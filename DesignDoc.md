# Design Doc

Feature Requirements:
1. Parse the WoW API for all available quest object (i.e name, description, ID, prereqs ID)
2. Use union find to build a forest of quests -- or topo sort
	-- Will test both
3. Display on screen
4. Save it to file so it only needs to be built once 
5. When user hovers over quest, they can get name of quest and its prereqs and whether or not they have completed it
6. Doubleclicking displays the network



Architecture:
