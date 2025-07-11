# PoE Filters
A repository to keep all of my filters in one spot and easily be able to share them with others.    

## Background
For those who are unfamiliar with Path of Exile (PoE), it is an Action RPG, Dungeon Crawler that has a lot of mechanics and items.    

The purpose of these filters is for players to more easily pick out items that they want. This is particulary useful towards the end of the game where there could be dozens of items in one area at once, and the player only has a 12x5 square grid to hold items.

![](/imgs/inventory.jpg "Example of a players inventory")

Having a filter enables the player to more easily tell if a specific item that dropped from an enemy is worth picking up. This can be done by setting specific thresholds for items.

### Without a filter
![](/imgs/before_filter.jpg "Without any filter being used")
### With a filter
![](/imgs/after_filter.jpg "With a filter being used")

When an item drops, various visual properties can be changed. The most common properties are, and not limited to: the font size and color, the border color, and the background color.

Example:
The following block will show items that match this filter:
- The item has at least three sockets
- There is at least 1 red, 1 green, and 1 blue socket
- There are at least 3 connected sockets
- The red, green, and blue sockets are linked together
How the visual properties change:
- Makes the border color blue
- Makes the text color red
- Makes the background color green
```
Show
    SocketGroup >= 3RGB
    SetBorderColor 0 0 192
    SetTextColor 255 0 0
    SetBackgroundColor 0 99 0
```
![](/imgs/chroma_drop.jpg "A dropped item that will become a chroma orb when sold")
![](/imgs/vendor.jpg "Selling the item to a vendor for a chroma orb")

## More information
My background section was barely even the surface of what I tried to explain. So, I will provide some links to the official game wiki in case more information is needed.
- [Info about the item filters](https://www.poewiki.net/wiki/Item_filter)
- [Documentation for the filters](https://www.poewiki.net/wiki/Guide:Item_filter_guide)

## How to use filters
Simply copy/paste one (or more) of these filters into where ever the location is for your PoE filters.    
By defualt, (on Windows) the directory is `C:\Users\<username>\Documents\My Games\Path of Exile`

## Duelist
- facebreaker (a unique item)
- spinny (Cyclone)

## Witch
- caster
- minion
- witch_level

## Misc Information
### Levels by Act
- Act 1: 1 - 12
- Act 2: 13 - 22
- Act 3: 23 - 32
- Act 4: 33 - 40
- Act 5: 41 - 45
- Act 6: 45 - 50
- Act 7: 50 - 54
- Act 8: 55 - 60
- Act 9: 61 - 64
- Act 10: 64 - 67