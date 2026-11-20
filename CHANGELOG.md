# Changelog

Ashes of the Damned, newest version first. Downloads: https://modwith.ai/aotd

<!-- releases, newest first -->

## [0.1.15](https://github.com/SickoHours/aotd-releases/releases/tag/v0.1.15) - 2026-11-20 (early access)

Ashes of the Damned 0.1.15: a Panzer that lost its claw can no longer freeze the game, and a player whose game stalls is no longer kicked because of the wonder weapon HUD.

### Fixed

- A Panzer whose claw was knocked off by a stun (a Jotunn Star swing, a zap or an EMP) could later try to fire the missing claw and freeze the whole match. It now fights on without the claw: it still walks, hits and uses its flamethrower.
- If your game froze or lagged for a while (a hitch, a stall, a network hiccup) while you held a wonder weapon, the server kept queueing wonder weapon HUD updates for you, and that could get you kicked with Connection Interrupted. It now waits until your game answers again, then catches your HUD up.

### Known issues

- On a controller, the knife icon beside D-pad Down hides while you hold a wonder weapon.
- Every Zombie Shield is built from the same parts at the same bench, and the host's pick counts for everyone.
- At night, the Carcass front's beam may not light the road from the driver's seat.
- A grapple pull can end over a spot with no ground, and you fall for a moment.
- A Der Wunderfizz buy in the instant you go down can keep that perk through the revive.
- In solo, a long stay in the pause or loadout pages can bring a short stutter or Connection Interrupted.
- Reznov, Mason, Woods and Menendez don't speak yet.
- Downed while inspecting a wonder weapon, you revive on a pistol.
- Joining from Plutonium's own server browser with Ashes loaded can still freeze on the download after an update. Use the title screen's server list, or restart the game and join again.


## [0.1.14](https://github.com/SickoHours/aotd-releases/releases/tag/v0.1.14) - 2026-11-19 (early access)

Ashes of the Damned 0.1.14: FAST RESTART no longer runs the game out of memory.

### Fixed

- After GAME OVER, picking FAST RESTART could crash the next match with "LUI: Out of memory", most often after you had looked at the scoreboard (Tab) in earlier matches.
- The menu memory no longer grows with each fast restart, however many times you restart.

### Known issues

- On a controller, the knife icon beside D-pad Down hides while you hold a wonder weapon.
- Every Zombie Shield is built from the same parts at the same bench, and the host's pick counts for everyone.
- At night, the Carcass front's beam may not light the road from the driver's seat.
- A grapple pull can end over a spot with no ground, and you fall for a moment.
- A Der Wunderfizz buy in the instant you go down can keep that perk through the revive.
- In solo, a long stay in the pause or loadout pages can bring a short stutter or Connection Interrupted.
- Reznov, Mason, Woods and Menendez don't speak yet.
- Downed while inspecting a wonder weapon, you revive on a pistol.
- Joining from Plutonium's own server browser with Ashes loaded can still freeze on the download after an update. Use the title screen's server list, or restart the game and join again.


## [0.1.13](https://github.com/SickoHours/aotd-releases/releases/tag/v0.1.13) - 2026-11-19 (early access)

Ashes of the Damned 0.1.13: joining a server after an update no longer freezes.

### Fixed

- After an update, joining a server from the title screen's LIVE AOTD SERVERS list could freeze on the download until you restarted the game.
- Joins from that list now unload Ashes first, so the game downloads what changed and loads Ashes fresh. A join takes a little longer, about as long as loading Ashes from the Mods menu.

### Known issues

- On a controller, the knife icon beside D-pad Down hides while you hold a wonder weapon.
- Every Zombie Shield is built from the same parts at the same bench, and the host's pick counts for everyone.
- At night, the Carcass front's beam may not light the road from the driver's seat.
- A grapple pull can end over a spot with no ground, and you fall for a moment.
- A Der Wunderfizz buy in the instant you go down can keep that perk through the revive.
- In solo, a long stay in the pause or loadout pages can bring a short stutter or Connection Interrupted.
- Reznov, Mason, Woods and Menendez don't speak yet.
- Downed while inspecting a wonder weapon, you revive on a pistol.
- Joining from Plutonium's own server browser with Ashes loaded can still freeze on the download after an update. Use the title screen's server list, or restart the game and join again.


## [0.1.12](https://github.com/SickoHours/aotd-releases/releases/tag/v0.1.12) - 2026-11-19 (early access)

Ashes of the Damned 0.1.12: one out-of-memory crash as a match loads is fixed, and AotD uses less graphics memory.

### Changed

- AotD uses about 150 MB less graphics memory, at the main menu and in a match: textures it stored more than once (wonder weapon effects, the LGM-1, the upgraded Nekomancer and others) are now stored once. Everything looks the same.
- If your game still runs out of memory ("E_OUTOFMEMORY: Ran out of memory"), please tell us when it happened, your graphics card and how much RAM your PC has.

### Fixed

- On PCs with less free memory, a match could fail to load with "E_OUTOFMEMORY: Ran out of memory" while the game set up its animated models. Those buffers are now 16 MB each instead of 24, still more than the busiest 4-player match has needed.

### Known issues

- On a controller, the knife icon beside D-pad Down hides while you hold a wonder weapon.
- Every Zombie Shield is built from the same parts at the same bench, and the host's pick counts for everyone.
- At night, the Carcass front's beam may not light the road from the driver's seat.
- A grapple pull can end over a spot with no ground, and you fall for a moment.
- A Der Wunderfizz buy in the instant you go down can keep that perk through the revive.
- In solo, a long stay in the pause or loadout pages can bring a short stutter or Connection Interrupted.
- Reznov, Mason, Woods and Menendez don't speak yet.
- Downed while inspecting a wonder weapon, you revive on a pistol.


## [0.1.11](https://github.com/SickoHours/aotd-releases/releases/tag/v0.1.11) - 2026-11-19 (early access)

Ashes of the Damned 0.1.11: the Trials countdown and the zombies-left counter wait for a stalled game.

### Fixed

- When your game stalls for a while mid-match, the Trials countdown and the zombies-left counter now wait for it to catch up instead of piling up messages for it. Enough of those piled up could get a player kicked with "Server command overflow".

### Known issues

- On a controller, the knife icon beside D-pad Down hides while you hold a wonder weapon.
- Every Zombie Shield is built from the same parts at the same bench, and the host's pick counts for everyone.
- At night, the Carcass front's beam may not light the road from the driver's seat.
- A grapple pull can end over a spot with no ground, and you fall for a moment.
- A Der Wunderfizz buy in the instant you go down can keep that perk through the revive.
- In solo, a long stay in the pause or loadout pages can bring a short stutter or Connection Interrupted.
- Reznov, Mason, Woods and Menendez don't speak yet.
- Downed while inspecting a wonder weapon, you revive on a pistol.


## [0.1.10](https://github.com/SickoHours/aotd-releases/releases/tag/v0.1.10) - 2026-11-19 (early access)

Ashes of the Damned 0.1.10: AotD uses less graphics memory.

### Changed

- AotD uses about 225 MB less graphics memory at the main menu: its largest textures now stop at Black Ops II's own maximum size. If your game ran out of memory there ("E_OUTOFMEMORY: Ran out of memory"), please try 0.1.10 and tell us how it goes.

### Known issues

- On a controller, the knife icon beside D-pad Down hides while you hold a wonder weapon.
- Every Zombie Shield is built from the same parts at the same bench, and the host's pick counts for everyone.
- At night, the Carcass front's beam may not light the road from the driver's seat.
- A grapple pull can end over a spot with no ground, and you fall for a moment.
- A Der Wunderfizz buy in the instant you go down can keep that perk through the revive.
- In solo, a long stay in the pause or loadout pages can bring a short stutter or Connection Interrupted.
- Reznov, Mason, Woods and Menendez don't speak yet.
- Downed while inspecting a wonder weapon, you revive on a pistol.


## [0.1.9](https://github.com/SickoHours/aotd-releases/releases/tag/v0.1.9) - 2026-11-19 (early access)

Ashes of the Damned 0.1.9: a fix for players on slower PCs.

### Fixed

- Fixed players on slower PCs sometimes being disconnected right after joining a game, with "A reliable command was cycled out".

### Known issues

- On a controller, the knife icon beside D-pad Down hides while you hold a wonder weapon.
- Every Zombie Shield is built from the same parts at the same bench, and the host's pick counts for everyone.
- At night, the Carcass front's beam may not light the road from the driver's seat.
- A grapple pull can end over a spot with no ground, and you fall for a moment.
- A Der Wunderfizz buy in the instant you go down can keep that perk through the revive.
- In solo, a long stay in the pause or loadout pages can bring a short stutter or Connection Interrupted.
- Reznov, Mason, Woods and Menendez don't speak yet.
- Downed while inspecting a wonder weapon, you revive on a pistol.


## [0.1.8](https://github.com/SickoHours/aotd-releases/releases/tag/v0.1.8) - 2026-11-18 (early access)

Ashes of the Damned 0.1.8: server tips and tricks.

### Added

- Added server tips and tricks.

### Known issues

- On a controller, the knife icon beside D-pad Down hides while you hold a wonder weapon.
- Every Zombie Shield is built from the same parts at the same bench, and the host's pick counts for everyone.
- At night, the Carcass front's beam may not light the road from the driver's seat.
- A grapple pull can end over a spot with no ground, and you fall for a moment.
- A Der Wunderfizz buy in the instant you go down can keep that perk through the revive.
- In solo, a long stay in the pause or loadout pages can bring a short stutter or Connection Interrupted.
- Reznov, Mason, Woods and Menendez don't speak yet.
- Downed while inspecting a wonder weapon, you revive on a pistol.


## [0.1.7](https://github.com/SickoHours/aotd-releases/releases/tag/v0.1.7) - 2026-11-18 (early access)

Ashes of the Damned 0.1.7: Pack-a-Punched wonder weapons are now the ones to chase, the Gauntlet's spikes hit harder and tear through whole lines of zombies, and Widow's Wine webs slow zombies down again.

### Added

- The Gauntlet's spikes leave a thin lime tracer from the glove to where they stick, red when Pack-a-Punched.

### Changed

- Wonder Weapon Pack 11t, the AotD-trimmed edition: only its upgrade changes, made on the wonder weapons AotD already ships.
- Warden's Blight: the charged tornado shot is now Pack-a-Punch only. The normal pair fires a bolt on every press.
- Cat Gun: the Hairball charge is now Pack-a-Punch only. Holding aim on the normal Cat Gun does nothing special, and it still fires.
- LGM-1: a normal shot kills its target and up to three zombies beside it, with no chain. The Pack-a-Punched LGM-1 still wipes the crowd and chains.
- Much more ammo: Warden's Blight carries 120 spare (240 Pack-a-Punched) and the Cat Gun 400 (800 Pack-a-Punched).
- Gauntlet: spikes hit harder and pierce up to 4 zombies (6 Pack-a-Punched), so it keeps up in the high rounds.

### Fixed

- Widow's Wine: webbed zombies slow down again, and zombies elsewhere on the map (rising from the ground, at the windows) no longer move in slow motion.

### Known issues

- On a controller, the knife icon beside D-pad Down hides while you hold a wonder weapon.
- Every Zombie Shield is built from the same parts at the same bench, and the host's pick counts for everyone.
- At night, the Carcass front's beam may not light the road from the driver's seat.
- A grapple pull can end over a spot with no ground, and you fall for a moment.
- A Der Wunderfizz buy in the instant you go down can keep that perk through the revive.
- In solo, a long stay in the pause or loadout pages can bring a short stutter or Connection Interrupted.
- Reznov, Mason, Woods and Menendez don't speak yet.
- Downed while inspecting a wonder weapon, you revive on a pistol.


## [0.1.6](https://github.com/SickoHours/aotd-releases/releases/tag/v0.1.6) - 2026-11-18 (early access)

Ashes of the Damned 0.1.6: a player whose game hitched for a long moment while riding Ol' Tessie is no longer kicked from the server.

### Fixed

- A player whose game hitched for a long moment while riding Ol' Tessie could be kicked from the server; the truck HUD now waits for him instead of piling up updates.

### Known issues

- On a controller, the knife icon beside D-pad Down hides while you hold a wonder weapon.
- Every Zombie Shield is built from the same parts at the same bench, and the host's pick counts for everyone.
- At night, the Carcass front's beam may not light the road from the driver's seat.
- A grapple pull can end over a spot with no ground, and you fall for a moment.
- A Der Wunderfizz buy in the instant you go down can keep that perk through the revive.
- In solo, a long stay in the pause or loadout pages can bring a short stutter or Connection Interrupted.
- Reznov, Mason, Woods and Menendez don't speak yet.
- Downed while inspecting a wonder weapon, you revive on a pistol.


## [0.1.5](https://github.com/SickoHours/aotd-releases/releases/tag/v0.1.5) - 2026-11-18 (early access)

Ashes of the Damned 0.1.5: players joining a host's pregame lobby no longer crash with a menu script error.

### Fixed

- Joining a friend's pregame lobby could crash your game with a menu script error (LUI ERROR) while the host was setting up the run. The host's lobby now tells joining players what it is doing in a way the game's own lobby always understands.

### Known issues

- On a controller, the knife icon beside D-pad Down hides while you hold a wonder weapon.
- Every Zombie Shield is built from the same parts at the same bench, and the host's pick counts for everyone.
- At night, the Carcass front's beam may not light the road from the driver's seat.
- A grapple pull can end over a spot with no ground, and you fall for a moment.
- A Der Wunderfizz buy in the instant you go down can keep that perk through the revive.
- In solo, a long stay in the pause or loadout pages can bring a short stutter or Connection Interrupted.
- Reznov, Mason, Woods and Menendez don't speak yet.
- Downed while inspecting a wonder weapon, you revive on a pistol.


## [0.1.4](https://github.com/SickoHours/aotd-releases/releases/tag/v0.1.4) - 2026-11-17 (early access)

Ashes of the Damned 0.1.4: the Cat Gun and the LGM-1 draw in every player's hands again, and no more crash for players joining a host who had picked a gun marked NEXT BUILD.

### Fixed

- The Cat Gun and the LGM-1 now draw in your hands on any PC on their own; before, they relied on a graphics setting the game sent you as you spawned, and some players saw empty hands.
- When a host had picked a gun marked NEXT BUILD, every player who joined crashed. Such a pick now stays out of the match and is kept for a later update.

### Known issues

- On a controller, the knife icon beside D-pad Down hides while you hold a wonder weapon.
- Every Zombie Shield is built from the same parts at the same bench, and the host's pick counts for everyone.
- At night, the Carcass front's beam may not light the road from the driver's seat.
- A grapple pull can end over a spot with no ground, and you fall for a moment.
- A Der Wunderfizz buy in the instant you go down can keep that perk through the revive.
- In solo, a long stay in the pause or loadout pages can bring a short stutter or Connection Interrupted.
- Reznov, Mason, Woods and Menendez don't speak yet.
- Downed while inspecting a wonder weapon, you revive on a pistol.


## [0.1.3](https://github.com/SickoHours/aotd-releases/releases/tag/v0.1.3) - 2026-11-17 (early access)

Ashes of the Damned 0.1.3: Alchemical Antithesis turns points into ammo as it should, and nobody can hide in the gaps beside Der Wunderfizz.

### Fixed

- Alchemical Antithesis gave points while it was active. Now, for its 60 seconds, every 10 points you would earn become 1 round of reserve ammo for the gun in your hands, and no points, as in Black Ops III (you keep the points while you hold a grenade, drink a perk or revive).
- A player could squeeze into the narrow gap beside Der Wunderfizz, where zombies stalled in front of the machine instead of attacking. The gaps on both sides are closed; buying from the machine is unchanged.

### Known issues

- On a controller, the knife icon beside D-pad Down hides while you hold a wonder weapon.
- Every Zombie Shield is built from the same parts at the same bench, and the host's pick counts for everyone.
- At night, the Carcass front's beam may not light the road from the driver's seat.
- A grapple pull can end over a spot with no ground, and you fall for a moment.
- A Der Wunderfizz buy in the instant you go down can keep that perk through the revive.
- In solo, a long stay in the pause or loadout pages can bring a short stutter or Connection Interrupted.
- Reznov, Mason, Woods and Menendez don't speak yet.
- Downed while inspecting a wonder weapon, you revive on a pistol.


## [0.1.2](https://github.com/SickoHours/aotd-releases/releases/tag/v0.1.2) - 2026-11-17 (early access)

Ashes of the Damned 0.1.2: the Cat Gun and the LGM-1 show in your hands again, and getting out of Ol' Tessie in the Cornfield no longer kills you.

### Fixed

- The Cat Gun and the LGM-1 could be invisible in your hands: you saw the animation and the ammo but no gun. They now draw for every player, in private matches and on servers.
- Getting out of Ol' Tessie in the Cornfield could kill you within seconds, as if you had left the map. Open ground there that zombies can walk to no longer counts as out of bounds; roofs and spots off the map still do.
- Several fixes to how a server handles chat, ready-up and match settings.

### Known issues

- Alchemical Antithesis still gives points while it is active; the fix comes in the next update.
- Beside Der Wunderfizz a player can squeeze into a gap where zombies stall instead of attacking; the fix comes in the next update.
- On a controller, the knife icon beside D-pad Down hides while you hold a wonder weapon.
- Every Zombie Shield is built from the same parts at the same bench, and the host's pick counts for everyone.
- At night, the Carcass front's beam may not light the road from the driver's seat.
- A grapple pull can end over a spot with no ground, and you fall for a moment.
- A Der Wunderfizz buy in the instant you go down can keep that perk through the revive.
- In solo, a long stay in the pause or loadout pages can bring a short stutter or Connection Interrupted.
- Reznov, Mason, Woods and Menendez don't speak yet.
- Downed while inspecting a wonder weapon, you revive on a pistol.


## [0.1.1](https://github.com/SickoHours/aotd-releases/releases/tag/v0.1.1) - 2026-11-16 (early access)

Ashes of the Damned 0.1.1: a fix for a crash that could come from holding the scoreboard late in a long match.

### Fixed

- Holding the scoreboard open late in a long match could run the menus out of memory and crash the game. The scoreboard no longer builds up memory while you hold it, and it frees what the match left behind when it opens.

### Known issues

- On a controller, the knife icon beside D-pad Down hides while you hold a wonder weapon.
- Every Zombie Shield is built from the same parts at the same bench, and the host's pick counts for everyone.
- At night, the Carcass front's beam may not light the road from the driver's seat.
- A grapple pull can end over a spot with no ground, and you fall for a moment.
- A Der Wunderfizz buy in the instant you go down can keep that perk through the revive.
- In solo, a long stay in the pause or loadout pages can bring a short stutter or Connection Interrupted.
- Reznov, Mason, Woods and Menendez don't speak yet.
- Downed while inspecting a wonder weapon, you revive on a pistol.


## [0.1.0](https://github.com/SickoHours/aotd-releases/releases/tag/v0.1.0) - 2026-11-16 (early access)

First public early-access build of Ashes of the Damned for Plutonium T6 Zombies (TranZit).

### Added

- Pick your Zombie Shield on the GEAR page: TranZit's Zombie Shield, the Mob Shield or the Origins Shield. The one you build looks like your pick in your hands, on your back and when you put it down.
- 16 new guns from Zucc's pack to pick for the box: PPSh, SPAS, M1 Garand, Stakeout, Type 100, BAR, MG42, Kar98k, Trench Gun, G11, Peacekeeper, Commando, HK21, RPK, AUG and FAMAS. The box holds 20 guns by default.
- Get a Ray Gun from the box and everyone hears it.
- Der Wunderfizz has a quick buy: turn it on in its menu and a buy goes straight through.
- With her Pack-a-Punch built, Ol' Tessie's side engines glow and her boost fires a jet afterburner.
- An in-game notice tells you when a newer Ashes of the Damned is out, and where to get it.
- REPORT A BUG, the pause menu's last row, shows a code to scan with your phone that opens the bug report page. EARLY ACCESS > WHAT'S NEXT shows the same code.
- MATCH SETUP has BREAK BETWEEN ROUNDS. With no break set, there is no READY-UP TIMER row.
- YOUR HUD in the pause menu has DIRECTOR MODE, which hides the FIND / INSTALL hint.

### Changed

- GEAR has no switches: everything is always on, and the Turret and the Electric Trap are gone from the map, benches and parts included.
- The Panzer: stuck in the fog, it rockets up within about 10 seconds and lands near you. Ol' Tessie can run it over (it goes flat, then gets up), her turret makes it flinch, and one Gauntlet hit takes at most a fifth of its health.
- TranZit's own box guns are out of the box, which rolls only the guns you picked. Wall guns stay, and the Python, KAP-40 and Executioner are still STARTING PISTOL picks.
- Wall guns play stock: each costs the map's own price (the M14 is 500, its ammo 250). The pause menu's MATCH SETTINGS holds RULES and THIS MATCH only.
- The grapple, Monkey Bombs and EMPs share your one tactical slot. Take Monkey Bombs or EMPs from the box and your grapple drops beside you; only you can take it back, and the bombs then float there for 60 seconds. Your grapple never vanishes.
- On a controller, tap D-pad Down to inspect the wonder weapon you hold (the Gauntlet too), then tap it again (or hold B) for your knife. With any other gun, D-pad Down still knifes at once. The keyboard is unchanged.
- The Black Ops 7 Ray Gun reads BO7 RAY GUN in the pregame, on the scoreboard, in the Legendary list, in your hands and at the box; the Ray Gun Mark II in the box keeps its name.
- Wonder weapons play more like Black Ops 7's: the grapple has Black Ops 7's own sounds, the Panzer reacts to wonder weapon hits, the Jotunn Star's souls fill and pay out, and a teammate's wonder weapon sits right in their hands.
- Aim the grapple where there's nothing to stand on and the crosshair says NO FOOTING. Aim at a ceiling and you land standing on the floor below it; on a narrow roof you stop where you land.
- Your GobbleGum sits on D-pad Right with its icon, charges and name; tap Right once to use it.
- T.E.D.D. podiums open once the power is on. Their screen is restyled after Black Ops 7's T.E.D.D. trials: a diamond clock, the trial's name, rule and cost in big type, and the Common to Legendary ladder.
- Trials rewards by tier: Common gives points and a Max Ammo; Uncommon points and a gun; Rare points, a perk and a box gun; Epic points, Pack-a-Punch and a GobbleGum. Every Legendary lets you take any one wonder weapon from its list, or the grapple.
- With a reward waiting, a T.E.D.D. opens the Trials screen with START TRIAL, REROLL and CLAIM REWARD together. START keeps your reward (a higher tier replaces it); CLAIM drops it right there, or opens the wonder weapon list at Legendary.
- Stand in Ol' Tessie's bed while she is parked and grapple to open ground: the claw lifts you out. In a rider seat, LB says IN A SEAT, and your grapple is back when you get off.
- D-pad Up shows your Claymores and how many are left. Carrying the shield or the Turbine, Up raises it, and Left and Right cycle through them, Claymores included.
- The pregame's EARLY ACCESS page matches the website: the four survivors, wonder weapons and perks pictured, and a WHAT'S NEXT tab with what's coming in 1.0 and the known issues.
- The pause menu has no QUIT TO DESKTOP row. INSTANT EXIT asks once, then takes you to the main menu with no game-over screen.
- Ready up in a round break with one tap of D-pad Down (its key on a keyboard); tap again to cancel. It works from Ol' Tessie's seats too, and with a wonder weapon in your hands.
- PLAY ONLINE on the title screen opens Plutonium's server browser over the Ashes of the Damned title; close it to come back to the title. Joining a server works as before.

### Fixed

- You no longer start a match on lava or burn during MATCH SETUP.
- Spinning the mystery box no longer crashes the game: it shows only the guns you left in.
- While the Death Machine is in your hands, Use no longer buys or opens anything (the box, wall buys, doors, perks or Ol' Tessie); it all works again when it ends.
- A Death Machine pickup no longer fails with "could not be equipped" when a Trials gun and Mule Kick give you five guns: it goes into your hands.
- A wonder weapon's dial name and ammo no longer flicker as you start an inspect.
- The Jotunn Star's FLAME STRIKE label is no longer covered by its lantern marker.
- A charged bolt from the regular Warden's Blight makes the same red fiery tornado as the packed one, and the Wunderwaffe no longer uses up an effect slot each restart.
- Going down while a GobbleGum's animation plays no longer leaves you holding the gum's item after the revive: you get your gun back.
- Zombies caught in Widow's Wine webs walk at normal speed instead of in slow motion, and you can see the web wrapped around them.
- Every perk drinks from its own can and does its own thing, at its machine and at Der Wunderfizz.
- The top-left Trials card names every trial, the new ones included, and its timer drains smoothly with no blink.
- Leaving a Trials podium (Back on its first page, or walking away) lets you move and shoot at once, and Esc opens the pause menu with nothing stuck on screen.
- Trials rewards on the floor say Hold F for ..., the same as the box.
- The Carcass front looks right: lighter in colour, its middle tongue stays inside its mouth, and its mouths no longer tear at the corners when the heads shake.
- Survivor fixes: Menendez's cuff, Weaver's hood, coat and shirt tail, Dempsey's back pad and strap, Maya's hip knife and baton, and everyone's left thumb look right.
- THE ARMORY's box list matches the box: TranZit's own box guns are gone, and the Python, KAP-40 and Executioner show only as STARTING PISTOL picks.
- Past 10,000 points, the grenade and claw icons sit right of your score, and a crowd's +50s no longer cover the gun's name.
- Opening the pause menu, as often as you like and late in a match too, no longer freezes the game.
- In co-op, a GobbleGum reward dropped on the floor for the second player shows its own model.
- In a 4-player match past round 15, gremlins and shades keep coming.

### Known issues

- On a controller, the knife icon beside D-pad Down hides while you hold a wonder weapon.
- Every Zombie Shield is built from the same parts at the same bench, and the host's pick counts for everyone.
- At night, the Carcass front's beam may not light the road from the driver's seat.
- A grapple pull can end over a spot with no ground, and you fall for a moment.
- A Der Wunderfizz buy in the instant you go down can keep that perk through the revive.
- In solo, a long stay in the pause or loadout pages can bring a short stutter or Connection Interrupted.
- Reznov, Mason, Woods and Menendez don't speak yet.
- Downed while inspecting a wonder weapon, you revive on a pistol.

