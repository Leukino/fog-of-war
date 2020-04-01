# FOG OF WAR

Hello, this is a research project of Fog of War implementation in an RTS game. It is made for the Bachelor degree in Game Development and Design in CITM, UPC.

## What is Fog of war?

Fog of war is a term that refers to describe the uncertainty in situation awareness experienced for militars in military operations. However, in video games, the fog of war reffers to giving the player partial information of a certain area, which makes the player re-think the strategy of the gameplay taking in account the leaking information. 

## Early stages

The earliest use of fog of war was in the 1977 game Empire by Walter Bright, and in 1978 in the game Tanktics from Chris Crawford. Later on, in 1982, he said "limit[ing] the amount of information available to the human player" to compensate for the computer's lack of intelligence.
From this moment, games like Age of Empires started to add this functionality and more advanced features, like hidden effects. 

## Types of Fog of War

## Tiled version

A tile based game is when the possible positions of the map are grouped in small areas that can be differenciated between them, instead of pixels. The areas can vary between games, but the most used are squares, hexagons, and distorted squares that create an isometric perspective effect. 

In these games the fog of war is managed with a meta-data information copy of the map that contains the fog information of the tiles (if the tiles are fogged, visited, unvisited,...)

Common games that use tiled version fog of war are RTS based games, like Warcraft II and Age of Empires saga. 

## Masked version

A masked fog of war is made by printing an image overlapping the visible information of the map so that the player can't see it.
The most common usage is to manage the color and the alpha of the overlapping image, so we can allow the player to see the screen through it. 
Common games are 2D RPG games, like Pokemon in dark caves, where you need the HM flash to remove the fog. 

## 2D vision games

Fog of war in these games is a bit more complex than other types. In these games, the program simulates 2D areas from making raycast from a vision emitter to nearby objects, the same way a static light illuminates a room. The most common usage is to create 2D complex forms from the collision of the raycast to the nearby vertexes of the objects surrounding the provider of visibility. This way we can generate an area which will have visibility characteristics, and will pack the whole non-visible area to fogged area. The principal games that use this system are MOBA's like League of Legends and DOTA 2. 

