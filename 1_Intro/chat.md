# Chat

- [Chat](#chat)
  - [How Do I Bind All The New VSAY's?](#how-do-i-bind-all-the-new-vsays)
  - [Quick Chat Menu](#quick-chat-menu)
  - [Fire Team Chat Menu](#fire-team-chat-menu)
  - [Bindable Statements Not Available Through Quick Chat](#bindable-statements-not-available-through-quick-chat)

---

## How Do I Bind All The New VSAY's?

Here is how the quick reference, voice text, and bind assignments line up. This list has been updated for Enemy Territory (Final). The format I've used is:

`quick chat key strokes - actual message - bind assigment`

In order to bind a key to a vsay, just do the following:

`bind x "vsay_team bind assignment`"  
`bind x "vsay_team onmyway"`

You have three options:

1. Use `vsay` for a global message - it will show up in cyan to everyone. Example. bind x "vsay onmyway"
2. Use `vsay_team` for a team message - it will show up in green to everyone on your team. Example: `bind x "vsay_team onmyway"`
3. Use `vsay_buddy [class number] [number of players] [list of players' fireteam IDs] [vsay string]` - sends a voice chat to the entire team - it will show up in yellow to the recipients. Example: `bind x "vsay_buddy -1 0 needbackup"`

    - For binds just use 0 for num\_players, and omit the player list
    - Classnumber should be -1 for any class, and 0-4 for the classes in their usual order.

    So, if I wanted to bind a key to say "need back up" to the entire team, it would look like:

    `bind x "vsay_buddy -1 0 needbackup"`

---

## Quick Chat Menu

**1. Statements**  
11 - Path cleared. - PathCleared  
12 - The enemy is weakened. - EnemyWeak  
13 - All clear. - AllClear  
14 - Incoming! - Incoming  
15 - Fire in the hole! - FireInTheHole  
16 - I'm defending. - OnDefense  
17 - I'm attacking. - OnOffense  
18 - Taking fire! - TakingFire  
19 - Mines cleared. - MinesCleared  
10 - Enemy in disguise. - EnemyDisguised  

**2. Requests**  
21 - Medic! - Medic  
22 - I need ammo! - NeedAmmo  
23 - I need backup! - NeedBackup  
24 - We need an engineer! - NeedEngineer  
25 - Cover me! - CoverMe  
26 - Hold fire! - HoldFire  
27 - Where to? - WhereTo  
28 - We need Covert Ops! - NeedOps  

**3 Commands**  
31 - Follow me! - FollowMe  
32 - Let's go! - LetsGo  
33 - Move! - Move  
34 - Clear the path! - ClearPath  
35 - Defend our objective! - DefendObjective  
36 - Disarm the dynamite! - DisarmDynamite  
37 - Clear the mines! - ClearMines  
38 - Reinforce the offense! - ReinforceOffense  
39 - Reinforce the defense! - ReinforceDefense  

**4 Talk**  
41 - Yes! - Affirmative  
42 - No! - Negative  
43 - Thanks a lot! - Thanks  
44 - You're welcome. - Welcome  
45 - Sorry! - Sorry  
46 - Oops! - Oops  

**5 Global**  
51 - Yes! - Affirmative  
52 - No! - Negative  
53 - The enemy is weakened. - EnemyWeak  
54 - Hi! - Hi  
55 - Bye. - Bye  
56 - Great shot! - GreatShot  
57 - Yeah! - Cheer  
581 - Thanks a lot! - Thanks  
582 - You're welcome. - Welcome  
583 - Oops! - Oops  
584 - Sorry! - Sorry  
585 - Hold your fire! - HoldFire  
586 - Good game! - GoodGame  

**6 Function**  
Just defaults to the function of your selected class - cannot choose to say you are a function you are not via the menu.

61 - I'm a soldier. - IamSoldier  
62 - I'm a medic. - IamMedic  
63 - I'm an engineer. - IamEngineer  
64 - I'm a field ops. - IamFieldOps  
65 - I'm a covert ops. - IamCovertOps  

Note: You can also bind a key like this:

bind x "wm\_sayplayerclass"

to replicate choosing "function" from the menu. It will say your current function when you hit the bound key.

**7 Objectives**  
71 - Command acknowledged! - CommandAcknowledged  
72 - Command declined! - CommandDeclined  
73 - Command completed! - CommandCompleted  
74 - Destroy the primary objective! - DestroyPrimary  
75 - Destroy the secondary objective! - DestroySecondary  
76 - Destroy the construction! - DestroyConstruction  
77 - Construction underway! - ConstructionCommencing  
78 - Repair the vehicle! - RepairVehicle  
79 - Destroy the vehicle! - DestroyVehicle  
70 - Escort the vehicle! - EscortVehicle  

---

## Fire Team Chat Menu

(Fire team-specific quick chat)

**6 General**  
Mirrors general chat

61 - Statements  
62 - Requests  
63 - Commands  
64 - Talk  
65 - Global  
66 - Function  
67 - Objectives  

**7 Attack**  
7 - Attack! - FTAttack  

**8 Fire Team**  
8 - Fall back! - FTFallBack  

---

## Bindable Statements Not Available Through Quick Chat

Numbers refer to file names not key strings. Some of these may be available to specific team members via the fire team quick chat.

Cover me! - FTCoverMe  
Disarm the dynamite! - FTDisarmDynamite  
Fall back! - FTFallBack  
Soldier, covering fire! - FTCoveringFire  
Deploy mortar! - FTMortar  
Heal the squad! - FTHealSquad  
Heal me! - FTHealMe (will show a medic icon over head)  
Revive team mate! - FTReviveTeamMate  
Revive me! - FTReviveMe (will show a medic icon over head)  
Destroy objective! - FTDestroyObjective  
Repair objective! - FTRepairObjective  
Construct the objective! - FTConstructObjective  
Deploy landmines! - FTDeployLandmines  
Disarm landmines! - FTDisarmLandmines  
Call airstrike! - FTCallAirStrike  
Call artillery! - FTCallArtillery  
Call mortar barrage! - FTMortarBarrage  
Resupply squad! - FTResupplySquad  
Resupply me! - FTResupplyMe (will show a ammo icon over head)  
Explore area! - FTExploreArea  
Explore at co-ordinates! - FTExploreAtCoordinates  
Destroy satchel objective! - FTSatchelObjective  
Infiltrate! - FTInfiltrate  
Go undercover! - FTGoUndercover  
Provide sniper cover! - FTProvideSniperCover
