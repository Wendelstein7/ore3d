# Archival repository featuring HydroNitrogen's ore3d
This is an archival repository for the ComputerCraft Plethora program 'ore3d' - an xray-like mining tool made for the pre-3D capable Plethora mod version AR-glasses.

**Please note:** This program was made for a version of Plethora which didn't include a 3D-rendering canvas on the Overlay Glasses, and therefore handles perspective projection itself. This strains server performance, and should not be used anymore.

The contents below are copied (sic) from the original forum-post made on August 12, 2018, [here](https://forums.computercraft.cc/index.php?topic=5.0) by HydroNitrogen.

---

> Hello all!
> 
> I made a *Fully Immersive Augmented Reality X-RAY Vision for Ore Mining using Plethora*, called **ore3d**.
> 
> ## What is ore3d?
> 
> ore3d is a program that will scan for ores around the player using Plethora's[1] block scanner, and then display these ores as quantities of ore groups on the players screen using the overlay glasses.\
> So basically this is a *legal* X-RAY vision!\
> This program basiaclly takes vector3's of all ores in an 17x17x17 area around the player, and uses matrices to perform some transformations, rotations and finally renders it as a perspective projection on the users screen. Because this is *pretty* advanced, there are lot's of tuneable settings such as FOV, aspect ratio, render speeds and more!
> 
> [1] What's Plethora? Plethora is an awesome CC addon created by SquidDev, [check it out here!](http://www.computercraft.info/forums2/index.php?/topic/27321-mc-189-1112-plethora/) (You need this installed for ore3d to work, obviously.)
> 
> **I recommend checking out the screenshot and videos on Ore3D's web page to understand what I am talking about** :)
> 
> ![](https://camo.tmpim.com/5f4e7f7194670bc235606226ec631d0ee3231d87/68747470733a2f2f6d656469612e7468696a6d656e2e78797a2f5337722d582e6a7067)
> 
> Videos:
> [https://media.energetic.pw/RlCSZqvN.webm](https://media.energetic.pw/RlCSZqvN.webm)
> [https://media.energetic.pw/RKxGwD1i.webm](https://media.energetic.pw/RKxGwD1i.webm)
> 
> **VIDEO / WEBM MAY NOT BE WORKING AS AN EMBED, [PLEASE CONTINUE TO THIS PAGE](https://energetic.pw/computercraft/ore3d) TO SEE THE VIDEOS! Sorry for the inconvenience.**
> 
> ## How to install:
> 
> Then add the following modules to your neural setup:\
> Introspection Module, Overlay Glasses, Entity Sensor, Block Scanner
> 
> Now executing the following commands in the shell of your neural interface:
> 
> ```
> wget https://energetic.pw/computercraft/ore3d/assets/ore3d.lua ore3d.lua
> 
> ore3d.lua
> ```
> 
> And enjoy!
> 
> **THIS PROGRAM INDUCES SIRIOUS LOAD ON THE SERVER IT IS RUN ON, PLEASE NOTE THIS BEFORE USING AND STOP USING THE PROGRAM WHEN ASKED FOR BY SERVER ADMINISTRATORS.**
> 
> ## More information:
> Please see:<https://energetic.pw/computercraft/ore3d>
> 
> I suck at making beautiful forum posts, therefore I made the webpage above. Please refer to that page for more information, instructions, videos and all other stuffs. Thanks!
