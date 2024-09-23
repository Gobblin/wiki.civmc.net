---
title: Item Exchange
description: Item Exchange plugin
---

# Item Exchange
Item Exchange is one of the core plugins of CivMC. It allows for players to complete trades without needing to be at the same location at the same time.
This plugin is similar to plugins that may be seen on other servers which allow players to setup trades within chests that can be interacted with by others, but 
is unique in that it is fully integrated with the other core Civ plugins such as [NameLayer](essential/namelayer.md), [Citadel](essential/citadel.md) and [JukeAlert](unique/jukealert.md). 

You will most frequently encounter Item Exchange when entering cities, where players will often have setup in-game shops and businesses selling a wide assortment
of items and blocks. Trade is a key part of the player-run economy, and Item Exchange facilitates this. 

## Interacting with an Exchange

To interact with an exchange, simply punch the shop container. 

(PICTURE OF EXCHANGE)

In the chat, a set of messages will display detailing the trade. They will often contain the following components:
1. The number of unique exchanges in the container (Example - `(1/3) exchanges present.` indicates that there are three different trades available within this container).
2. The item that you will be trading (Example - `Input: 32 diamonds` indicates that you will be giving 32 diamonds).
3. The item you will receive (Example: `Output: 1 Netherite Pickaxe` indicates that you will receive one Netherrite Pickaxe in return for your 32 diamonds).
4. The condition, or enchantments attached to the item you will receive. (Example: `Condition: Undamaged` means that you can be ensured that the item you receieve will have full durability).
5. The number of exchanges available for this trade. (Example: `38 exchanges available` indicates that you can complete this trade 38 times before the chest no longer contains any of the output items.

> [!TIP]
> When buying tools or armor from an exchange, you should check that the enchantments align with what you're expecting. Keep an eye out for Undamaged items to ensure you're buying something unused.
> Some merchants may elect to also include the repair status in their trade, which can give you confidence that the item has never been repaired before as items can only be repaired a few times on CivMC.

To view the other exchanges in the container, simply punch the chest again. Once you reach the last exchange, the first will be displayed again.

If you find a trade that interests you, and you have enough of the Input item to satisfy the trade, punch the chest again while holding the Input item to complete the trade.
This will move the input item from your inventory into the chest, and give you the output item. 

Continue punching the chest to complete the trade again if desired.

## Creating your own Exchange



## Security

### Chest Relays

## Containers

The following containers are supported by Item Exchange: 
* Chests (Single or double),
* Ender Chests (when used as part of a Chest Relay),
* Barrels,
* Trapped Chests

## Command Summary







To make a group simply perform the command **/nlcreategroup** (or /nlcg) and then the name for the group you’d like to make. 

![Creating a group](./media/Creategroup.png)

This is also possible with the GUI which you can access by performing the command **/nl**

![Creating a group using Gui](./media/GuiCreategroup.png)

To start typing in a group use **/g** followed by the group name. 

![Using /g](./media/Groupchat.png)

Now only those in the group with the right permissions can see your messages. And if you’d like to return to local chat simply do **/g** on its own. 

![/g to Local Chat](./media/LocalChat.png)

## Changing group permissons

To edit permissions use the GUI by performing **/nl** then click on the group you’d like to change. 

![List of namelayer groups](./media/Namelayergroups.png)

Now on the fence gate top right. There are 5 different layers of permissions.

![Open permissons screen](./media/GroupPermissions.png)

The first is for anyone not blacklisted, meaning that even people not on the group can use these permissions. 
From then on it’s member, mod, admin and owner. All have preset permissions on group creation, but each can be changed simply by clicking on them and changing it from green to red to disallow, or red to green to allow for that rank. 

![Managing group permissons](./media/Changingperms.png)
