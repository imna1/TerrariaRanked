# Changelog

All notable client changes are listed here.

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
