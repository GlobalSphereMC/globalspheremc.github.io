---
layout: page
title: Towns
parent: Towns and War
nav_order: 1
---

# **Towns**
---
Towns are a group of plots (which can each have different access permissions) that are controlled by a leader (the mayor).  

To create a town, go to an unclaimed chunk and do `/t new <townName>`.  

Each day, towns are taxed money (based on the amount of residents in your town) from their town bank for upkeep. They can also lose money if they lose a war. If a town does not have any money in it's bank, it will go bankrupt and turn into ruins (all permissions in the town are turned on). After 24 hours, anyone can do `/t reclaim` to pay a fee and recover the town. After 3 days of being in ruins, the town will be permanently deleted. To prevent the town from ruining, you can do `/t deposit <amount>`. To take money out, you can do `/t withdraw <amount>`.  

When you create a town, you initially only claim the chunk that you are standing in. To increase your town size, do `/t claim` on an adjacent chunk (costs the town bank) or `/t claim outpost` if it is not an adjacent chunk (costs more to claim, and a maximum 2000 chunk distance). Note that for every chunk you claim, the claim cost increases by 0.1%.

Do note that each town has a claim limit. This is 12 chunks per resident in the town. It can be increased by joining a nation or by buying more with `/t buy bonus`.  

To add people to your town, you can do `/t add <playerName>`. To remove someone from your town, you can do `/t kick <playerName>`.  

By default, only residents can do things in your town. You can give full permission to anyone by doing `/t trust add <playerName>`, but make sure that they won't steal from you!  

To teleport back to your town's spawn, do `/t spawn`. You can also teleport to towns in your nation, or towns you are trusted in by doing `/t spawn <townName>`.  

You can check out more town settings by doing `/t toggle` and `/t set`.  

# **Prices**
---
You can see all towny prices in-game by doing `/towny prices`.
