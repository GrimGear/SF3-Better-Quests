# SF3-Better-Quests

The main reason I created this was that the simple achievements book doesn't allow multiple people to tick off quests, and at least right now JEI is getting in the way of the simple achievements book.

Right now every quest is just a checkbox that you click, just like the original Sky Factory 3 book. The only things I'm noticing right now is that when you're in a party and click something as completed, it shows completed for the other people, but doesn't change their X to a check mark, this isn't to big of a deal though as they still show up green and completed to everyone in the party. Also the quest being completed in a text splash doesn't seem to show up for everyone.

To do this, the client and server will need Better Questing and Better Questing - Standard Expansion, which are located here:

https://minecraft.curseforge.com/projects/better-questing?gameCategorySlug=mc-mods&projectID=238856 https://minecraft.curseforge.com/projects/better-questing-standard-expansion

The ones I used were BetterQuesting-2.3.198.jar and StandardExpansion-2.3.120.jar, but newer versions should work. If your just running Minecraft as a client, drop these jar files into the mods folder inside "FTB Presents SkyFactory 3". 

Inside the FTB Presents SkyFactory 3/config folder, place the betterquesting folder from here. 

https://github.com/GrimGear/SF3-Better-Quests

Once this is all set, open your world and type in "/bq_admin default load"

If you are running a server, the clients and server will need BetterQuesting-2.3.198.jar and StandardExpansion-2.3.120.jar, but the DefaultQuests file can just go on the server. Same "/bq_admin default load" command will work, just use it through the server.
