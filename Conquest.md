# Conquest Help

Cog for

# conquest
 - Usage: `[p]conquest `

Base command for conquest cog. Start with `[p]conquest set map` to select a map.

## conquest list
 - Usage: `[p]conquest list `

List currently available maps

## conquest take
 - Usage: `[p]conquest take <regions> <color> `

Claim a territory or list of territories for a specified color<br/><br/>:param regions: List of integer regions<br/>:param color: Color to claim regions

## conquest current
 - Usage: `[p]conquest current `

Send the current map.

## conquest numbered
 - Usage: `[p]conquest numbered `

Print the numbered version of the current map, for reference.

## conquest multitake
 - Usage: `[p]conquest multitake <start_region> <end_region> <color> `



## conquest blank
 - Usage: `[p]conquest blank `

Print the blank version of the current map, for reference.

## conquest set
 - Usage: `[p]conquest set `

Base command for admin actions like selecting a map

### conquest set map
 - Usage: `[p]conquest set map <mapname> [reset=False] `

Select a map from current available maps<br/><br/>To add more maps, see the guide (WIP)

### conquest set load
 - Usage: `[p]conquest set load <save_name> `

Load a saved map to be the current map

### conquest set save
 - Usage: `[p]conquest set save <save_name> `

Save the current map to be loaded later

### conquest set resetzoom
 - Usage: `[p]conquest set resetzoom `

Resets the zoom level of the current map

### conquest set zoomtest
 - Usage: `[p]conquest set zoomtest <x> <y> <zoom> `

Test the zoom level and position of the current map<br/><br/>x: positive integer<br/>y: positive integer<br/>zoom: float greater than or equal to 1

### conquest set zoom
 - Usage: `[p]conquest set zoom <x> <y> <zoom> `

Set the zoom level and position of the current map<br/><br/>x: positive integer<br/>y: positive integer<br/>zoom: float greater than or equal to 1

