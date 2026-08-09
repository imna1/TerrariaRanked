# Changelog

All notable client changes are listed here.

## [0.5.6] - 2026-08-09

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
