# Aldmere Hardpoint

A Hardpoint game mode for Chivalry 2 Unchained, made for the map [Aldmere Works](https://github.com/chivned/AldmereWorks).

- The first zone opens 20 s after the match starts. Each zone lasts 70 s, in the order Crossing, Great Wheel, Stone Yard, Masons' Lodge, Bell Pit, then repeats.
- The live zone has a glowing band and a tall wall of light: white = nobody holding, blue = Agatha, red = Mason, purple = contested. The next zone shows faintly 10 s before it goes live, and the respawn points move with it.
- A team scores 1 point per second while only its players are inside the live zone. First to 220 wins; otherwise the leader when the 17:00 clock runs out.
- Standing in a zone your team holds alone gives the game's own "+10 Capture" score each second.

Everyone in the match needs this mod: the server keeps the score, each player's copy shows the zone walls. It stays idle on other maps.

Hosting: `--next-map-name TDM_AldmereWorks --server-mods AldmereHardpoint`, or in game `servertravel TDM_AldmereWorks?mods=AldmereHardpoint`.

By Ned.
