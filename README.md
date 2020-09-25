# Captains-ContextMenu-FiveM
### About <br/>
A Raytrace & Entity based context menu for GTA V FiveM.
<br/>
Perform actions based off the Entity you are interacting with in the world. Such as Vehicles, ATMs, Phonebooths, Trashcans, Doors, Cashregisters and all other Entities that the game offers. <br/>
<br/>
**NOTE:** This is a context menu Shell meaning features such as the Police menu are just an Empty menu buttons that do nothing. It's there as an Example on how **YOU** can add your own actions to it. It is a system to be build on and have it work how **YOU** want it to.<br/>
**READ THE HOW TO MODIFY AT THE BOTTOM**
<br/>

### How to Install
- Clone or Download the contextmenu and hashtomenu folders.
- Drop the two folders in your FiveM Server Resources folder.
- Add the Resources to your FiveM server.cfg file. (To be safe start the hashtoname resource BEFORE the contextmenu)
<br/>

### How to Use
- Toggle NUI via the assigned key (Default: Z(Can be changed))
- Cursor appears on the screen. 
- Right click on an Entity. (Cars, Peds, obejcts)
- Select the option/task you want to perform.
<br/>

### Screenshots
**Car Menu** <br/>
![Car Menu](https://i.imgur.com/mSZqLTF.png)
![Car sub Menu](https://i.imgur.com/Vc49IHX.png)<br/>
**Object Menu** <br/>
![Object Menu](https://i.imgur.com/9eUX1pn.png)<br/>
**Job Menu** <br/>
![Tow Menu](https://i.imgur.com/KEHRadi.png)
![Police Menu](https://i.imgur.com/JdhwKl6.png)<br/>
**Illegal options** <br/>
![Steal Menu](https://i.imgur.com/G7gGzzV.png)
![Lockpick Menu](https://i.imgur.com/zG1PcrQ.png)<br/>
**Export Entity** <br/>
![Steal Menu](https://i.imgur.com/C5Q9HkB.png)
<br/>

### How to Modify
In the code itself i've written comments on how everything works and how **YOU** can add your own functionality to the resource. <br/>
The code contains Examples on how you can implement your own options as well as some features, such as the Doors menu which is fully operational. <br/>
Every action (button) in the menu leads to somewhere. Meaning you can easily add the code you want and the actions you want to happen when X button on the menu is pressed.
<br/>

## Shout outs:
- Simu, for code related to Screen to world coords.
- Taso, Frontend assistance with bugs (CSS/JS)
- VenomXNL, for Object name from Hash -> https://github.com/VenomXNL/ObjectNameFromHash <br/>
(The version of HashToName is a Modified version of VenomXNL's repo to allow for Exports instead of prints)
