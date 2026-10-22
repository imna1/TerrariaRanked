# Changelog

All notable client changes are listed here.

# 0.8.0

* Improved the "fair enemy spawns" system: enemy type selection is now deterministic and depends on multiple parameters while preserving vanilla spawn logic
* Changed NPC arrival timing: it is now deterministic for all players and depends on the total number of walls in the house instead of the house location
* Optimized match history and statistics calculation for large amounts of data
* Removed the "Encounter Tim" bingo goal
* Made the time between sitting on a toilet and receiving a poo block deterministic
* Removed the "block events" option from room creation
* Minor UI and localization fixes

# 0.7.10

* Added Russian localization
* Added hints for some bingo goals
* Expanded the seed pool for filtered speedrun categories
* UI changes
* Fixed tracking for the "Put X Unique Critters in a Terrarium or Bottle" bingo goal
* Jungle Spores now count as a mushroom for the "Obtain X Unique Mushrooms" bingo goal

# 0.7.8-0.7.9

* Added new unranked speedrun categories:
  * Random Item
  * Full Inventory
  * Edge of the World
  * Torch God
  * Terra Blade
  * Zenith
  * Goblin / Pirate / Martian Invasions
  * Frost / Pumpkin Moon
  * OOA T3
* Plantera's Bulb now spawns within 200 blocks of the Golem Temple door
* Expanded the seed pool for filtered speedrun categories
* Fixed getting stuck in the lobby when changing seeds or loading a new unranked game

# 0.7.7

* Updated to 1.4.5.8
* Added filtered seeds for all ranked speedrun categories
  * **ML**
    * Pyramid with an accessory and at least one gold pile
    * Deep jungle main
    * At least one Life Crystal in main
    * At least one Crimson biome on the Dungeon side
  * **APHBAO**
    * Snow hillcave with Deer Thing
    * Deep jungle main
    * At least two Life Crystals in main
    * Suspicious Looking Eye in main
    * Ruby in the snow hillcave or main
  * **NE**
    * Close hillcave with at least one wooden chest
    * Close Crimson
    * Muramasa in the first Dungeon chest
    * Deep jungle main
  * **EOC**
    * Close hillcave or jungle
    * Suspicious Looking Eye in the hillcave or in main
* Added a seed description before the match starts
* Increased the Bingo World View range to 150 blocks in both directions
* Fixed the fullscreen bingo board hotkey resetting
* Fixed getting stuck in menu
* Fixed FPS affecting ghost movement speed in World View
* Fixed character data carrying over on seed changes
* Fixed unable to use chat after match
* UI fixes

# 0.7.6

- Changed how match history is displayed for matches with 3 or more players
  - In speedruns, you can now compare your splits with a specific player
  - In bingo, completed goals are now highlighted correctly
- Added new bingo goals
  - Spawn an Enemy from a Statue
  - Kill a Ghost
  - Get a Voice Accessory
  - Acquire 5/10 Unique Statues
  - Acquire 3/6/10 Unique Paintings
- Fixed tracking for a couple of bingo goals
- Changed the icons for a couple of bingo goals
- Added more splits to the ML speedrun

# 0.7.5

- Updated to 1.4.5.7

# 0.7.4

- Added an Elo change screen at the end of ranked matches and a standard end game screen for custom matches
- Changed the splits for Night’s Edge
- Minor UI changes and bug fixes

# 0.7.3

- Added discord bot
- Fixed seed changed option doesn't work (probably, I haven't tested it)
- Fixed completed goals don't appear in chat

# 0.7.2

- Fixed an issue with different reforges on starting items
- Fixed an issue that could prevent ranked matches from starting
- Fixed tracking for:
  - Put 5/10 Unique Critters in a Terrarium or Bottle
  - Defeat 3/5 Unique Bosses or Mini-bosses
  - Kill-enemy-related goals being completed by killing critters
- Renamed several goals
- Fixed an issue where no sound would play when an opponent completed a goal

# 0.7.1

- Fixed the character from the previous match being retained after a seed change (hopefully)
- Fixed an issue that prevented World View from opening (hopefully)
- Some goals and their variations can no longer appear in ranked lobbies with low-ranked players

# 0.7.0

- Added a **World View** feature during the draft phase. The world is completely frozen, you spawn as a ghost, and you can fly up to 100 blocks to the left and right
- Increased the countdown before bingo matches start
- Added a **seed change** button. It can be used once per match. In Draftout, the board stays the same after changing the seed
- Added **Discord Rich Presence**. If you have game activity enabled, others can see when you’re searching for an opponent, as well as match information such as your opponent and progress
- Changed the starting Elo from 1000 to 800. Every player’s Elo has also been reduced by 200
- Removed the following bingo goals:
  - Purchase an item from the Traveling Merchant
  - Acquire the Peddler's Hat
  - Run an item through an Extractinator
  - Acquire a Boss Trophy
  - Fish up 4 Unique Fishing Crates (only the 4 crate variation was removed, 2 and 3 crate versions remain)
- Fixed tracking for Pink Maid Vanity Set


# 0.6.3

- Falling Stars are now deterministic
- Added reconnection attempts if your internet connection drops during a match
- Changed the Elo formula again
- Removed "Craft 70 Unique Walls" goal variation


# 0.6.2

- Added an in-game timer
- Changed the client download and update system
- Several bug fixes:
  - Fixed the Elo calculation for draws
  - Fixed some UI issues
  - Fixed tracking for a few bingo goals
  - Renamed goblin tinkerer goal
  - Fixed tracking for several speedrun splits


# 0.6.1

- Added the ability to manually edit quests in Normal Bingo mode and view them before game starts
- Changed how match history is displayed for 2 player speedruns. Splits are now shown in two columns, making them easier to compare


# 0.6.0

- Added 3 categories in ranked speedrun mode:
  - Eye of Chtulhu
  - Night's Edge
  - All Prehardmode Bosses Any Order
  - Moonlord
- The harder the category, the more Elo you get
- Added an outline to completed bingo goals
- Slightly changed stats in profile


# 0.5.12

- Remove goals logging
- Fixed elo formula
- Fixed "Shimmer an Item for a Permanent Buff" goal not tracking vital crystal


# 0.5.10

- Added a deterministic system for angler quests. Angler now gives the same quests to every player
- Renamed bingo modes and match outcomes
- Added 4 new bingo quests and reworked 1 existing


# 0.5.7 - 0.5.9

- Added a leaderboard
- Added the ability to view other players’ profiles
- Server improvements
- Several bug fixes, most notably:
  - Fixed Esc key interactions
  - Fixed icons for a couple of quests


# 0.5.6

### Added

- Online race rooms for Speedrun and Bingo, with room codes, lobby chat, player readiness, and synchronized starts.
- Ranked 1v1 matchmaking for Speedrun and Bingo, separate Elo ratings, calibration, ranks and match history.
- Automatic generation of a shared seeded world for every race participant.
- Open Bingo boards and 1v1 Lockout Bingo draft, goal tracking, completion times, winner announcements, and in-game board display.
- Race lobby controls for custom rooms: privacy, room code, player limit, goals, seed mode, difficulty, world size and evil.
- Player profile with statistics and ranked/custom match-history filters.
- Client version display, update check and download.

### Changed

- Race worlds use deterministic systems where needed for fair competitive play. The same seed now produces consistent outcomes for:
  - enemy drops;
  - drops from shaking trees;
  - tile drops from coin piles, pots, shadow orbs, pigronatas and fairy logs;
  - plantera's bulb locations;
  - alchemy table crafting and decrafting with shimmer;
  - hardmode ore type and placement;
  - teleportation potion destinations;
  - the hardmode V-strip location;
  - opened bags and containers, including cans of worms, herb bags, treasure bags, and crates;
  - the first NPC check after entering a world;
  - tile-update order;
  - traveling merchant and homeless-NPC arrival chances;
  - natural events, including invasions, boss spawns, blood Moons, eclipses, rain, and parties;
  - item reforging;
  - starting-tool modifiers;
  - fishing catches;
  - lunar pillar positions;
  - the stardust pillar enemy-spawn sequence.
- Luck uses an accumulator instead of a random roll.
- Race rooms can use fair enemy spawns. The system keeps enemy spawn timing, position, environment checks, and enemy selection consistent (spawnrate can differ from vanilla up to 5%); ranked matches enforce it.
- Halloween and Christmas calendar effects no longer activate from the computer clock during race play.
- Race lobby and character/world selection flows were adapted for automated world generation and returning to an active lobby.
