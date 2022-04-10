# Loot Council Helper v1.0.0
It is important to remove `-master` at the end of the folder name in order to function properly.
<BR><BR>

Addon helps to distribute loot according to Loot Council loot distribution rules.<BR><BR>

Raiders will receive custom item frames and options to pick for each item: 
* BIS
* MS
* OS
* Pass/Exit

  
***Note**: Raiders need to get https://github.com/IUChimes/LCFrames addon in order to see frames*
<Br>
   
![loot frame](https://i.imgur.com/UAEWGxd.png)

Item selection period is calculated using this formula: Item count * 30 seconds. Which means that for each item that drops item selection will take 30 more seconds.

Loot council members will have 60 seconds of voting time for each item.
<BR>

![Example](https://i.imgur.com/z1JLQ1R.png)

To view specific player loot history you have to click on the name.<Br>

After the voting phase, Raid Leader can distribute loot according to votes.

Loot can also be given to a specific raider by pressing right click on raider's name 
Loot can also be distributed if you right-click on a raider frame.<Br>

Also it is possible to change players selection.

![distribute loot](https://i.imgur.com/XL5ZbpX.png)

In case after the voting phase there is more than one winner, then it is a tie, and button  `ROLL VOTE TIE` button will show up. Pressing it will ask tie raiders to roll.<BR>

![rollframe](https://i.imgur.com/oT7y9cd.png)

Roll results are being displayed in the voting frame. Afterwards Raid Leader can distribute loot to the winning roll.

![frame](https://i.imgur.com/MqabH9A.png)


Helpful commands:<br>
`/lc add [name]` - Adds `name` to the loot council member list<br>
`/lc rem [name]` - Removes `name` from the loot council member list<br>
`/lc list` - Lists the loot council member list <Br>
`/lc who` - Lists people who have this addon <Br>
`/lc set ttnfactor [sec]` - Sets the time available to players to pick for each item (final duration is number of items * this factor, in seconds). Default value is 30 seconds for each item.<Br>
`/lc set ttvfactor [sec]` - Sets the time available to council members to vote for each item (final duration is number of items * this factor, in seconds). Default value is 60 seconds for each item.<Br>
`/lc set ttr [sec]` - Sets the time available to players to roll in a vote tie case<Br>
`/lc synchistory` - Syncs loot history with other people with the addon.<Br>
`/lc debug` - Toggle debugging on or off<Br>
