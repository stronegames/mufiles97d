# mufiles97d
Mu Server 97d DarkSteam
[Beta 41 Changelog]
Tweaked drop system with ability to use -1 for random skill/luck/add/exc options
Added ability to allow specific characters/symbols in character and guild names
DecreaseElfArrows is now InfiniteElfArrows
Added /ping command
Added ability to clear player skills when resetting
Event manager now respects the year column

[Beta 40.1 Changelog]
Fixed an error in the GoldenArcher.txt file
Golden Archer is now enabled by default
Small corrections

[Beta 40 Changelog]
Added ability to include grand reset points when resetting
Added Golden Archer system
Added ability to change max item level
Added ability to change item duration on the floor

[Beta 39.1 Changelog]
Fixed reset & grand reset systems not working properly
Fixed /skin, /pet and /tracemarry blocked ids/maps

[Beta 39 Changelog]
Added ability to reload most of the customs using /reload 3
Added Dynamic Exp System
Quest system now supports all monsters
Fixed invasion time
Fixed Sky Event pvp before event start
Fixed dupe bug

[Beta 38 Changelog]
Added /resetskills command
Added Lucky Mixes event
Experience calculation tweaked
Added ability to change points per level for each class
Added CalCharacter - you can now balance your characters

[Beta 37.4 Changelog]
Tweaked /vault command & fixed dupe bug

[Beta 37.3 Changelog]
Fixed Sky event not randomizing items
Changing points per level will now also change in Blood Castle

[Beta 37.2 Changelog]
Stability improvements

[Beta 37.1 Changelog]
Fixed /move command not working properly

[Beta 37 Changelog]
Fixed /reset and /grandreset not switching characters if selfdefense is active
Fixed /post command crashing on some systems
Performance improvements

[Beta 36.1 Changelog]
Fixed drop system min/max level
Fixed high cpu usage

[Beta 36 Changelog]
Attempt to fix multi vault dupe
Fixed Sky event not being able to enter in some cases
Quest system tweaks

[Beta 35 Changelog]
Fixed /pet command only for gm check
Added ability to change npc buffers text
Skills min level check now uses item(kor).txt
Fixed starting level up points and zen options

[Beta 34.7 Changelog]
Fixed /pkclear checks
Attempt to fix guild joining issue
Fixed golden archer dupe

[Beta 34.6 Changelog]
Added ability to limit maximum players in a guild
Added ability to set /pkclear's command price * pk count

[Beta 34.5 Changelog]
Fixed npc buffers starts moving when there's a murderer around them

[Beta 34.4 Changelog]
Quest system hotfix
Added ability to clear player kills on reset & grand reset. You'll have to update your Reset & GrandResetSystem.dat files by adding an extra 0 at the end of each line, or use the ones provided with the package

[Beta 34.3 Changelog]
Fixed reset command check for empty inventory
Attempt to fix monster attribute error on start up when npc buffers are enabled

[Beta 34.2 Changelog]
/tracemarry tweaked to work with MoveSystem.dat

[Beta 34.1 Changelog]
Fixed /tracemarry cooldown
Quest system credits reward option added. You'll have to update your Quests file by adding an extra 0 at the end of each quest, or use the one provided with the package

[Beta 34 Changelog]
NPC buffers should no longer start moving after some time
Fixed anti afk punishment type (0 = warp, 1 = disconnect)
Added the missing ZenFormula option to the pkclear command
Blocked all invalid/bad skins & pets by default
Added database for sql 2005 and up to the main package + odbc for win x64 (base package only)
Improved anti afk system. Characters that are chatting but not moving will no longer be considered as afk
Implemented a brand new vault dupe protection - Hot!
Added /tracemarry blocked maps option
Added /tracemarry cooldown option
Added ability to control with how many excellent options the excellent items drops - Hot!
Replaced bor team's connectserver with webzen's one + patched it to work correctly on new operation systems. No more false antivirus alerts due to connectserver being packed (base package only)
Added starting level up points and zen options for newly created characters - Hot!
Fixed quest system first quest being ignored
Fixed a bug where Sky event, Reset & Grand Reset commands would not add credits if the account is missing from MEMB_CREDITS table
Implemented a new, experimental trade dupe protection - Hot!

[Beta 33.1 Changelog]
Fixed news system sending the default messages in some cases
Fixed npc system min/max level usage
Applied some fixes to the reset system
Upgraded the grand reset command to advanced grand reset system
Removed the unused options from Commands.ini which were forgotten in the previous beta

[Beta 33 Changelog - Gold edition]
Fixed disabling trade not working
Completely reworked move system. You can now make some warps available only for vips - Hot!
Added a /charinfo command that will show player's current resets, grand resets, marriage info & vip status expiration time
Added a level up effect to /buyvip command
Quest id variable removed from the quest system. You'll have to update your quests file, or use the new one.
New, experimental party zen bug fix, including in devil square
Improved shadow bug detection. No more skills learning at level one, using the shadow bug - Hot!
Added advanced messages system. You can finally translate all custom command/event/system messages - Hot!
Brand new, never seen before event - Lucky Jewels - Hot!
Added advanced exp system with ability to set different bonus exp on every map. In addition, you can make zones with extra exp - Hot!
VIP system improved with performance in mind
Added advanced zen drop system. You can finally control monster's zen drop - Exclusive!
Experimental syn flood protection - Hot!
Fixed /buy & /sell commands color #3
Added advanced reset system with ability to set different requirements per class/vip/resets, different rewards per class/vip/resets - Hot!
Fixed a bug where Sky event wasn't randomizing the excellent options when rewarding players
Some additional corrections to the gm system. Fixed the expiration date & automated the demotion process without the need of re-logging
Added ability to make the vip system to work per account as well as per character - Hot!
Added advanced anti-afk system with ability to create safe zones per map/coords - Hot!
Fixed map system file reading structure
Added additional security checks to the npc talk protocol
Added /setlevel & /setzen commands
Attempt to finally fix the crash on some server machines when checksum is enabled

[Beta 32 Changelog]
Brand new VIP System - Hot!
Advanced npc buffers configuration file (+ability to add them on different maps, change npc's ids, ability to limit them to vips only, min/max level, resets, grand resets) - Hot!
Added ability to enable/disable /questinfo command
Added ability to change how blood castle award players (all party players or just the player who completes the quest)
All player commands now works with the brand new vip system. You can now limit the commands to vips only.
Advanced map system with safe zones! Yes, you can finally create non pvp, pk free zones. - Hot!
Game Masters can move using /move <map name>
Added a check if the player will exceed the maximum amount of zen (2000000000) when selling, being rewarded in event or when picking up zen). No more bugged zen. - Hot!
NPC's can no longer be killed using hacks
Added ability to set (and show) Sky event's required item name
Fully translated message_kor.wtf file with additional corrections
Completely rewritten GM system. All known bugs fixed
Advanced character stats system. Now you can limit strength, agility, vitality, energy per class - Hot!
Drop system completely recoded. Working way better now
Improved /add command, integrated to work with the new character stats system
Attack Speed is wrong log removed
Added ability to completely disable gameserver logs
Potions usage delay added
Zombie pvp hack blocked
Added ability to allow killers to enter devil square, blood castle and use shops
Anti twisting slash use without weapon check added
In case of missing custom sql columns, the gameserver will attempt to automatically create them
Huge performance improvements

[Beta 31 Changelog]
Webzen Mu Game Server is already Running fixed
- Sub servers support added
Patched all startup error logs

[Beta 30 Changelog]
Option to check if inventory is empty before reset - added (2 types, 1 = check equipment only, 2 = check whole inventory)
Option to clear inventory after reset - added
Elf greater damage & defense buffs duration options - added
Drop command can drop kris
Party exp options fixed (party bonus event should also be working correctly now)
Reduced sql queries

[Beta 29 Changelog]
Minor fixes
Added support for excellent items in shops - Hot!
You'll have to update your shop files by adding an additional 0 on each item

[Beta 28 Changelog]
Checksum crash fixed
More performance improvements

[Beta 27 Changelog]
English translated gameserver
Sky event hotfix

[Beta 26 Changelog]
Character/guild leave without personal id - fixed
Trade hack - blocked
Guild notice sql injection - fixed (directly in gs).
Pk bug - fixed (limit of 100 kills - removed)
Post command delay option - added
Spoof hack - blocked
Disconnect hack detection - improved
Trade with npc crash - fixed
Sky event - improved
Quest system - improved. No more crashes & negative quests, hopefully.
Elf arrows will no longer decrease (and then increase) when DecreaseElfArrows is set to 0
Happy hour event - improved
Performance improved by 80%, sql queries reduced by 60%
2nd level wings success rate option - fixed
Advanced Blood castle reward according to the room level - added (example: bc1 - box+1, bc2 - box+2, bc6 - box+5)
Mana shield maximum percentage option - added
Npc buffers (swell of life, mana shield, elf buffs) - added
/pet command - added
Swell of Life (bk buff) formula options - added
Post command color #3 fixed
Skin command blocked skins option - added

[Beta 25 Changelog]
CheckSum crash - Fixed
Little corrections over the EventManager

[Beta 24 Changelog]
Critical bug fix

[Beta 23 Changelog]
Anti bad symbols in character name - Added - Hot!
Unique map system (pk free, non-pvp maps) - Added - Unique!
Allow/Disallow pvp in sky event option - Added
Little corrections in quest system

[Beta 22.2 Changelog]
Some little corrections

[Beta 22 Changelog]
GM Login notice - Added
[Move System] Required resets to move - Added - Hot!
[Move System] Required grand resets to move - Added - Hot!
F.O Items support in drop system - Added
F.O Items support in Quest reward - Added
F.O Items support in Sky Event Reward - Added
Sky Event Respawn - Fixed
Sky Event Min players option - Added
Sky Event credits reward - Added
Quest System Exp & Levels reward - Fixed
All other reported bugs - Fixed

[Beta 21 Changelog]
New Commands: /skin, /gg, /banpost, /unbanpost, /banchar, /unbanchar, /reload, /evo & /grandreset
Brand new Quest System (with 15 new quests) - Hot!
New sql connection
Unique drop system - Hot!
Updated Event Manager
Sky Event - Hot!
GM System - Hot!
New Move System - Hot!
Blood Castle Ranking
Golden Archer
Auto bugged stats fix on login
Trade System
Anti Disconnect Hack - Hot!
Anti Vault Dupe - Hot!
Anti Guild Crash - Hot!
PvP / NoN PvP Support - Hot!

-----------------------------------------------------------------------------------------------------------------

- :: Custom Commands :: -
/post, /addstr, /addagi, /addvit, /addene, /pkclear, /reset, /grandreset, /marry, /acceptmarry, /tracemarry, /marrystatus, /divorce, /getmarry,
/time, /exit, /buy, /sell, /online, /clearinventory, /moveall, /vault, /questinfo, /skin, /gg, /drop, /banchar, /unbanchar, /banpost, /unbanpost, /reload, /evo, /pet, /buyvip, /vipinfo, /charinfo, /setlevel, /setzen, /resetskills

- :: Custom Events :: -
Happy Hour
Party Exp Bonus
Sky Event
Lucky Jewels - Exclusive!
Lucky Mixes - Exclusive!

- :: Other Customs :: -
Advanced Item Drop System
Game Master System
News System
Unique Quest System
Move System
Trade System
Event Manager
Golden Archer
Blood Castle Ranking
Auto Bugged Stats fix on Login
Advanced Map System with zones - Unique!
Advanced Blood Castle Rewards - New!
NPC Buffers - New!
Support for Excellent items in shops - New!
Ability to completely disable gameserver logs - New!
Advanced Character Stats system - New!
VIP System - New!
Map Exp System - New!
Anti Afk System - New!
Zen Drop System - New!
Advanced Reset & Grand Reset systems - New!
Ability to balance characters (CalCharacter) - Hot!
Dynamic Exp System - Hot!
Golden Archer System - New!
Over 500 Custom Config Options

- :: Security :: -
Anti Disconnect Hack
Anti Guild Crash
Anti Vault Dupe
Anti Bad Symbols in Character Name
Anti Guild Notice Inject
Anti NPC Trade Crash
Anti Trade Hack
Anti Zombie Hack
Anti Twisting Slash Hack
Anti Shadow Bug
Anti Trade Dupe
Anti Syn Flood
Anti Golden Archer Dupe
Anti NPC Dupe

- :: Supported OS :: -
Windows XP
Windows Server 2003/2008/2012/2016
Windows Vista
Windows 7
Windows 8
Windows 10

- :: Supported SQL Servers :: -
2000, 2005, 2008, 2012, 2014, 2016 (All)
