# TIEFGANG – Changelog

Every test build is listed under [Releases](https://github.com/OsuGerman/Tiefgang-Releases/releases). If you have the game installed,
new versions are offered to you at start-up in the main menu. The version number is shown bottom right in the main menu.
Please send feedback as an [issue](https://github.com/OsuGerman/Tiefgang-Releases/issues) – with the version number, area and depth.

German version: [CHANGELOG.de.md](https://github.com/OsuGerman/Tiefgang-Releases/blob/main/CHANGELOG.de.md)

---

## 25.10.2026 – Sharper image, more fps, no more chests in walls (v2026.10.25.1602-01a50e6c)

### Improved
- **Much less shimmer and more fps:** most world textures were missing mipmaps. With them, floors and ceilings shimmer far less, and the game runs about **15 % faster** on the same settings. High and Ultra also use SMAA now. ([#120](https://github.com/OsuGerman/Tiefgang-Releases/issues/120))
- **Calmer, richer image:** caustics only shine strongly under light shafts, marine snow is subtler and varied, less bloom and warmer highlights against teal shadows. ([#120](https://github.com/OsuGerman/Tiefgang-Releases/issues/120))
- **Boss fights are easier to read:** while a phase banner is shown, the radio box and side elements fade back. ([#120](https://github.com/OsuGerman/Tiefgang-Releases/issues/120))
- **Report a Bug** in the pause menu: opens the bug form already filled with your version, area and system, plus your log folder. ([#124](https://github.com/OsuGerman/Tiefgang-Releases/issues/124))
- **Helmet breathing is audible now, casing clinks are much quieter** until better recordings are in. ([#132](https://github.com/OsuGerman/Tiefgang-Releases/issues/132), [#133](https://github.com/OsuGerman/Tiefgang-Releases/issues/133))

### Fixed
- **Chests, altars and valves no longer stand inside walls or pillars**, and opened chest lids no longer clip through walls. ([#134](https://github.com/OsuGerman/Tiefgang-Releases/issues/134))


---

## 25.10.2026 – Brass casings, breathing in the helmet, faster first dive (v2026.10.25.1034-3ca8526c)

### New
- **Brass casings:** the Shipyard Song ejects a cartridge with every shot, and the Governor and Keelbreaker drop their spent shells when you reload. They bounce, settle on the floor and clink differently on stone, metal, wood and sand. ([#119](https://github.com/OsuGerman/Tiefgang-Releases/issues/119))
- **Breathing in the brass helmet:** a slow, muffled breath with a hissing valve and bubbles outside. It gets faster after a dash and when you're low on health. You can turn it off under Audio → Helmet Breathing. ([#119](https://github.com/OsuGerman/Tiefgang-Releases/issues/119))

### Improved
- **Faster first dive:** the first expedition after starting the game is revealed about 1.3 seconds earlier, and the remaining load now happens behind the finished title card instead of a black screen. ([#106](https://github.com/OsuGerman/Tiefgang-Releases/issues/106))


---

## 24.10.2026 – Xal-Tuun's Otherworld, punchier effects, smoother loading (v2026.10.24.2321-dbccc819)

### New
- **Xal-Tuun gets a signature attack:** In his last phase his third eye opens and drags you (and your whole co-op team) into a shadow otherworld high above the arena. Destroy three soul shards and jump over shadow waves within 14 seconds. Make it and he crashes down and staggers, taking 50 % more damage. Fail and he hardens his armor. ([#116](https://github.com/OsuGerman/Tiefgang-Releases/issues/116))

### Improved
- **Black holes feel huge:** your view is pulled in and shakes while the singularity sucks you in, and the collapse hits with a hard kick, a short freeze frame and a lens flash. Up close the hole no longer turns the whole screen black, the glowing ring stays visible. ([#118](https://github.com/OsuGerman/Tiefgang-Releases/issues/118))
- **Chain lightning reads as a chain:** thicker white-hot arcs that jump from enemy to enemy one after another and get weaker with every hop. ([#118](https://github.com/OsuGerman/Tiefgang-Releases/issues/118))
- **Smoother room transitions:** rooms are drawn once behind the loading screen, the next room shows up earlier, and the stutter in the corridors between rooms is cut by more than half. ([#106](https://github.com/OsuGerman/Tiefgang-Releases/issues/106))
- **Easier start for new players:** until your first dive, the submarine shows where to go (straight down the main hall to the diving chamber). ([#99](https://github.com/OsuGerman/Tiefgang-Releases/issues/99))
- **New graphics options:** SMAA anti-aliasing (sharper than before) and FSR 2.2 upscaling for more fps on weaker graphics cards. The defaults stay the same. ([#100](https://github.com/OsuGerman/Tiefgang-Releases/issues/100), [#101](https://github.com/OsuGerman/Tiefgang-Releases/issues/101))
- **Faster first start after an update:** shaders are now prepared when the build is made instead of on your PC. ([#106](https://github.com/OsuGerman/Tiefgang-Releases/issues/106))
- **Enemies stand out better in dark rooms** with a crisp cold edge of light along their silhouette.


---

## 24.10.2026 – Smoother first load, crosshair editor, clearer rewards (v2026.10.24.1816-10cb1cc1)

### Fixed
- **No more black submarine after starting the game:** The loading screen now stays until the submarine is fully lit and drawn, and the HUD numbers (pearls, cores, ammo) are there right away. The submarine is preloaded in the background while you are in the main menu. ([#105](https://github.com/OsuGerman/Tiefgang-Releases/issues/105), [#108](https://github.com/OsuGerman/Tiefgang-Releases/issues/108))
- **Bosses and elites face you when they appear** instead of spawning with their back to you. ([#98](https://github.com/OsuGerman/Tiefgang-Releases/issues/98))
- **Grave worms are less tanky:** less health and a longer window to hit them after they surface. ([#113](https://github.com/OsuGerman/Tiefgang-Releases/issues/113))

### Improved
- **Crosshair editor:** thickness, length, gap, center dot, outline, opacity, spread on/off and more colors, with a live preview in the settings (Gameplay). ([#111](https://github.com/OsuGerman/Tiefgang-Releases/issues/111))
- **Less muffled combat sound underwater:** weapons, hits and explosions keep their crack, the ambience still sounds like water. ([#115](https://github.com/OsuGerman/Tiefgang-Releases/issues/115))
- **Clearer texts and rewards:** ([#112](https://github.com/OsuGerman/Tiefgang-Releases/issues/112))
  - The loot carrier objective explains that it flees three times and loses loot each time.
  - The Quartermaster shows what his blessing actually does.
  - Legendary boss drops get a big label and a sound.
  - After clearing a room, you're told when an altar, chest or valve is still unused.


---

## 24.10.2026 – Playtest fixes: shards, breather, portals, settings (v2026.10.24.1716-2c4b2bbe)

### Fixed
- **No more surprise card selection while walking:** The third charm shard used to open the charm selection on the spot, even mid-fight. Now it places a charm drop at your feet ("3 SHARDS: CHARM READY") that you open with interact when you're ready. ([#110](https://github.com/OsuGerman/Tiefgang-Releases/issues/110))
- **Breather between the heralds counts down:** The timer showed 10 s the whole time, now it counts down every second. ([#109](https://github.com/OsuGerman/Tiefgang-Releases/issues/109))

### Improved
- **Jump into portals:** Jumping or dashing into a portal's vortex now takes you through, no key needed. Standing in front of it still needs interact. ([#114](https://github.com/OsuGerman/Tiefgang-Releases/issues/114))
- **Key bindings are easier to find:** The Key Bindings tab now sits right next to Controls instead of hiding behind the tab arrows.
- **New setting "Reload with Fire Button"** (Controls): turn it off and the fire button no longer starts a reload on an empty magazine or a reload attempt during a reload. ([#111](https://github.com/OsuGerman/Tiefgang-Releases/issues/111))


---

## 24.10.2026 – Much faster updates (v2026.10.24.0011-a37c20d1)

### Improved
- **Updates only download what changed:** usually just a few MB instead of more than 600 MB every time. This kicks in from the next update on; this one downloads in full one last time.
- **Installs in seconds:** When you quit, files are simply swapped instead of everything being unpacked again.
- **"Restart now":** Instead of a small Windows window you get a fullscreen screen in the game's style, and the game comes straight back in your display mode.


---

## 23.10.2026 – New main menu, new HUD, logbook instead of the Tab list (v2026.10.23.2102-8552dda0)

### New
- **Main menu:**
  - cinematic scene with light rays, depth of field and a passing leviathan
  - The logo rises from the deep (any key skips it).
  - The menu items hang from a depth gauge with a gliding depth meter.
- **Submarine menus:**
  - Every station, the pause menu, settings and dialogs are dark glass with a brass edge.
  - In the diving chamber you set the pressure level on a manometer and game modes on lever switches.
  - The settings have index-card tabs.
- **HUD:**
  - brass instrument panel with rolling counters for shells, keys, shards and pearls
  - blessings and buffs in portholes
  - weapon plate with a counter and a clearly visible active reload
  - Dr. Marsh's radio messages as paper strips from the radio
- **Tab overview as a logbook:**
  - weapon, ability and stats as gauges
  - element compass with every reaction
  - charms as medallions with a detail card
- **New settings:** HUD size and HUD opacity under Settings › Interface.

### Fixed
- **Co-op:** Your own co-op name was replaced by the automatic leaderboard name.


---

## 23.10.2026 – Runs count automatically, English as fallback language (v2026.10.23.1946-85b4722d)

### New
- **Online leaderboard without a prompt:**
  - Valid single-player runs now count automatically.
  - Without a name of your own you appear as "Diver-1234".
  - The first time, the results screen shows a notice with a "Change name" button.
  - You can switch it off at any time under Settings › Online.
  - If you declined earlier, you stay out.
- **Language:** Systems set to a language other than German or English now start in English.


---

## 20 Oct 2026 – Sunken Archives with new lighting and real fog (v2026.10.20.2021-591fd0a7)

### New
- **A new look for the Archives:**
  - candle gold against ink-blue water light, candelabra on the glyph pillars, candles on shelves and stacks of books
  - pages drifting in the light shaft, wisps of ink along the floor
  - the Reading Room and the Glyph Rotunda with baked lighting

### Fixed
- **Fog in the Archives** (Depths 5–8): it now actually looks like fog instead of a flat blue layer. It only scatters in the light, and the distance sinks into ink blue.


---

## 20 Oct 2026 – New enemy attacks, new reward cards, no more flickering walls (v2026.10.20.2003-a3f96143)

### New
- **Enemies with new attacks:** 25 enemies in the existing areas have new signature attacks.
  - **Coral:** coral spurs block your path and can be shot down. Plus reef quakes, spore nets and the Brood Matron’s reef cage.
  - **Archives:** ink splatters, seal stamps, page storms, leaf fans and the Seal Breaker’s seal sequence.
  - **Temple:** the Kraklings’ pack leap, ember fans, glyph traps and the Ember Colossus’s ember grid.
  - **Drilling Station:** sludge splatters, rivet rams, pressure valves and the Steam Hammer’s overpressure cross.
  - **Teamwork:** a player who’s been snared is briefly exposed to the marksmen. After that, a short grace period protects you from being snared over and over.
  - **Fairness:** every attack has a clear warning and a window to dodge and counter.
- **Drowned Fleet reworked** (for the upcoming Ship Graveyard): 16 new attacks, including Musketeer volleys in formation, a shield wall, chain shot and a second phase for the Figurehead Warden. New models too.
- **New reward cards:**
  - Charms, blessings, the anvil, chests, boss rewards, the trader, Biome Choice and the Diving Chamber all have their own TIEFGANG look: riveted metal cards, with rarity shown by the metal (copper, brass, gold, silver, rust).
  - The icon sits in a porthole, the text on old paper.
  - Cards slide in with an animation, tilt when you hover over them and lock in with a seal stamp when you pick one.
- **Creatures above the ceiling openings:** in the Temple and the Coral Cathedral, a creature now and then glides past above the light shaft. Very rarely there’s something stranger to spot up there …

### Improved
- **Memory:** data from areas you’ve already left is freed, saving 120–380 MB of video memory.
- **Combat performance:** slightly lower CPU load with lots of enemies.

### Fixed
- **Flickering walls** (z-fighting) and bright frames around doors in corridors.
- **Whaler:** an error when reeled-in harpoons had already disappeared.
- **Elites with “Sturdy”:** their armour kept recharging, even when it wasn’t broken.
- **Co-op – new weapon mechanics:** Throw, Tooth Leap, Reel In, Discharge, the tidal wave and Resonance were sometimes rejected for teammates. Now every hit lands. Sticky shells and barbs are visible to both players.
- **Important for co-op:** the co-op version has gone up. Both players need this test build.


---

## 20 Oct 2026 – New weapon mechanics, a new look for the Coral Cathedral (v2026.10.20.1855-8d277f28)

### New
- **Weapons reworked:** every weapon has its own mechanic.
  - **Keelbreaker:** impact chain. Heavy hits make the next shot stronger. Plus wall slams and blast jumps.
  - **Whaler:** barbs stay stuck in enemies. Reel In drags them all to you, stuns them and rips the barbs out for bonus damage.
  - **Beacon:** the focus arcs over as a chain beam. Plus a charged shot with a perfect timing window.
  - **Depth Bomb:** lay sticky shells and set them off as a chain. Direct hits deal more damage.
  - **Sleeper’s Tooth:** the thrown spear lodges in the enemy, then comes the Tooth Leap.
  - **Tide Blade:** a perfect parry against projectiles sends a tidal wave back at the shooter.
  - **Voice of the Deep:** ring on the beat to build harmony until the Great Toll comes.
  - Damage has been rebalanced so every weapon is worth taking. Shipyard Song and the Governor are unchanged.
- **Coral Cathedral in the new graphics standard:**
  - 10 rooms with baked lighting
  - dancing caustics on floors and walls
  - glowing magenta and cyan coral, growth on the walls
  - a manta ray glides past in the light shaft.
- **Biome Choice:** the cards now show real images of the areas.

### Fixed
- **Depth Bomb:** its explosions didn’t get crits, blessings or charm effects. Fixed.
- **Slow weapons** (harpoon, mortar, bell, spear) now trigger “on hit” blessings fairly.
- **Elites with “Sturdy”:** their armour recharged far too often – on high pressure levels these elites were almost impossible to beat.


---

## 20 Oct 2026 – New water effects and a look for Duo Blessings (v2026.10.20.1612-1042a35c)

### New
- **Tide:**
  - Tide waves are now real water waves with a foamy crest, and you can see the distorted background through them.
  - Soaked enemies gleam wet, with trickles running down them.
  - Splashes and puddles on the floor.
  - The Maelstrom is a whirlpool with a funnel.
- **Duo Blessings with their own look:**
  - Event Horizon discharges lightning out of the black hole.
  - With Red Tide the water turns red.
  - Abyssal Drain has its own curse pulse.
- **Conduction (Tide + Lightning):** a big surge of water with a lightning edge.
- **Boss Admiral Varrow** for the upcoming Ship Graveyard is built. He isn’t in the game yet.


---

## 20 Oct 2026 – Try the new game mode “Biome Choice (Acts)” (v2026.10.20.1501-e4f78a1b)

### New
- **Biome Choice (Acts):**
  - A new game mode in the Diving Chamber under Game Modes.
  - The run consists of 4 acts of 3 depths each plus the Abyss – 14 depths in total, as before.
  - After every act boss you pick the next area from two cards at the portal.
  - Every run visits all four areas and fights four bosses.
  - The same seed and the same choices give you the same run.
  - In co-op the host chooses.
  - The normal mode is unchanged, and the 10 pressure levels stay the same.
- **Important for co-op:** the co-op version has gone up. Both players need this test build.


---

## 20 Oct 2026 – The whole Temple in its new look (v2026.10.20.1353-3cdf2d52)

### New
- **The entire Temple in the new graphics standard:** 13 more combat and elite rooms now have baked lighting, decals and fog.
  - The entrance to the Basin Plaza is no longer a flat wash of orange.
  - The fallen pillar in the Collapsed Hall is now a proper fluted column.
  - Glyphs and crystals glow 30 % brighter.
- **Ship Graveyard (work in progress, not playable yet):**
  - 5 more rooms: Hospital Ship, Ballast Shaft, Ram Arena, Captain’s Cabin and Chart Room
  - bulkhead doors
  - the “rotten planks” hazard: they give way after a warning, even under enemies.


---

## 20 Oct 2026 – Co-op: teammates see every attack warning (v2026.10.20.1316-25ae2224)

### Fixed
- **Co-op – attack warnings missing for teammates:**
  - Until now, teammates only saw about a third of the warnings from nearby enemies and almost none from enemies further away.
  - Now they all come through, even on a poor connection.
- **Co-op – short attacks missed:** short attacks such as mortar impacts or shockwaves were sometimes missing entirely for teammates.
- **Important:** the co-op version has gone up. Both players need this test build.


---

## 20 Oct 2026 – Real lightning, a new Drowned Fleet, 7 Temple rooms in the new look (v2026.10.20.1115-23f48e8d)

### New
- **Lightning, completely redone:**
  - thin, sharply jagged arcs with side branches
  - strobe flicker and a brief afterglow
  - impacts with a starburst and sparks that bounce off
  - Chain lightning visibly jumps from target to target.
  - Storm Pulse and Conduction: jagged arcs that crawl across the floor
- **Temple in the new graphics standard:**
  - Great Hall, Pillared Hall, Warden’s Pit, Collapsed Hall, Basin Plaza, Cloister and Terraces with baked lighting, decals and fog
  - A leviathan drifts past in the Great Hall’s light shaft.
- **Drowned Fleet complete:**
  - Barnacle Brood (a swarm bursting from the hull wall), Cannoneer (mortar, vulnerable while reloading) and Figurehead Warden (elite)
  - They arrive with the Ship Graveyard and can’t be seen in the game yet.


---

## 20 Oct 2026 – Lightning overlay and smoother status effects (v2026.10.20.1009-aaaf8665)

### New
- **Electrified enemies** show twitching veins of lightning across their models.
- **Lightning:**
  - Chain lightning visibly jumps from target to target, one after another.
  - Impacts with a starburst, lingering sparks and a brief flash of light.
  - Light flashes and lingering sparks only from the “High” quality preset up.
- **Storm Pulse around the player** is now just a ring on the floor instead of a glowing wall.
- **Drowned Fleet:**
  - The first three enemies for the upcoming Ship Graveyard are built: a Sailor with a grappling hook, a Musketeer wreathed in powder smoke and a Boatswain with a plank shield.
  - They don’t appear in the normal game yet.

### Improved
- **Status overlays** (frost, blood, void, lightning) cost less performance: they’re attached over several frames and share one material.
- The overlay patterns are now the right size on every enemy model.


---

## 20 Oct 2026 – New effects for frost, blood and void, lots of fixes (v2026.10.20.0816-f9882203)

### New
- **Frost:**
  - When an enemy freezes, ice crystals grow and hoarfrost creeps up from its feet – starting at 3 stacks of Soaked as an early warning.
  - A frost patch on the floor slowly melts, and cold mist sinks down.
  - Frozen enemies shatter into shards of ice when they die.
  - Frost Surge makes ice spikes shoot out of the floor along your dash path.
- **Blood:**
  - Drops fall with gravity and leave splatters and pools on the floor that slowly dry.
  - Bloodletting draws threads of blood towards the player.
  - Bleeding enemies are covered in pulsing veins.
- **Void:**
  - Hits first contract, then discharge with a shock ring that warps the room.
  - The Singularity is now a real black hole with a photon ring, gravitational lensing and a tilted disc.
  - Shadow tendrils and a dark overlay with a violet core.
- **Status overlay:** status effects are shown directly on the enemy model.
- **Ship Graveyard:** the model kit for an upcoming area is built. It isn’t in the game yet.

### Fixed
- **Phase Jump through walls:** in tough rooms, Phase Jump could carry you its full distance through a wall.
- **Floating charms:** an unopened charm drop followed you into the next depths and got stuck in walls there.
- **A resonance stone in one Archives room** sat under a walkway and was barely possible to hit. Stones, brood sacs and anemones are now always placed in the open.
- **Charm texts in the Tab menu** are no longer cut off.
- **The Codex notification** no longer covers the Tab overview.


---

## 20 Oct 2026 – Duo Blessings, and no more stutter on your first ability use (v2026.10.20.0704-e9deee46)

### New
- **6 Duo Blessings:** Superconductor, Red Tide, Abyssal Drain, Overheat, Dark Pact and Event Horizon. Each one changes an element reaction.
  - A Duo shows up at the blessing altar once you have 2 blessings each from two elements – at the latest by the third altar.
  - It doesn’t take up a slot. At most one Duo per element pair.
  - Its own card in both element colours, a fifth “DUO” field in the slot bar, icons in the HUD, in the Tab menu and on the run summary, plus a Codex entry.
  - Works in co-op too.

### Fixed
- **Stutter on the first use of an ability:** projectiles, materials and effects are now prepared behind the loading screen. The first use no longer stutters (previously up to 20 ms).


---

## 20 Oct 2026 – New lighting in the Temple and important fixes (v2026.10.20.0625-9926e129)

### New
- **The Temple’s Great Hall in the new graphics standard:**
  - baked lighting with warm and cold pools of light
  - a light shaft falling on the throne
  - colour grading and depth absorption
  - grime, algae and cracks as decals
  - ground fog
  - This is the template room for the rooms to come.

### Fixed
- **Room wouldn’t open (e.g. Depth 11):**
  - If an enemy vanished without dying, the room stayed locked forever.
  - The enemy list is now cleaned up continuously.
  - A safety net opens a room after 8 s once there’s demonstrably nothing left to do.
- **Permanently slowed:** ink puddles, affix debuffs, the kill rush and Overpressure could get stuck forever. You were then permanently at 65 % speed, or couldn’t get through the door after the Archivist.
- **Error with ground warnings:** a mine from an enemy that was already dead caused a script error, and the warning circle was missing.


---
## 18 Oct 2026 – Smarter charm offers (v2026.10.18.1729-15c7c148)

### Improved
- **Element charms only with a matching element source:**
  - Red Glow, Storm Battery, Hungering Tide, Tide Mark, Void Hunger, Saturation, Abyssal Catalyst, Critical Mass, Reactive Plating and Chain Reaction only show up once you have a matching blessing, an element charm, Prism of the Deep or Phase Jump.
  - Reaction charms need two elements.
- **No more cards that switch off one of your own blessings:** with Coolant Jacket you won’t be offered Eternal Magazine, with Last Blood no Glass Heart.
- **Berserker Valve** isn’t offered while the Sleeper’s Tooth is equipped.
- **The research starting charm** now matches your weapons and ability.
- **Resonance Core** shows that extra stacks shorten the interval. Glass Heart now says plainly: healing no longer works.


---

## 18 Oct 2026 – New ability effects (v2026.10.18.1710-0fe4fc1f)

### Improved
- **Pressure Mine:** it glows in flight. A countdown ring shows the radius and pulses faster and faster until it goes off, with a ring contracting just before. The blast is a whirl of water with hit-stop, leaving a ring of foam and a column of bubbles behind.
- **Sentry:**
  - A swirl appears on the ground as it deploys.
  - Every time it picks a new target, its aiming beam and crosshair flash.
  - The muzzle flash is a star.
  - When it runs out, the sentry flickers and retracts.
- **Life Pulse:** a brief pull at your feet announces it, followed by the heartbeat waves and an afterglow on the ground.
- **Call of the Deep eel:** a calling ring comes before it surfaces, its bites splash, and at the end the eel dives into a whirlpool in the floor.
- **Co-op:** teammates see the same effects. Life Pulse now shows the real waves on a teammate instead of a sphere.
- Slightly higher FPS during sustained fire: unused hit sparks are hidden.


---

## 18 Oct 2026 – Charm fixes (v2026.10.18.1022-51189a3a)

### Fixed
- **Hollow Vow:** healing orbs, ampoules, merchant healing and the healing shrine now really stop healing you. Healing from kills, lifesteal, Life Pulse and your co-op partner is still allowed. The description now spells this out.
- **A second Sentry with Sixfold Watch:** the two now add up (7 turrets) instead of the second charm doing nothing.
- **Deep Current** wrongly counted Time Dilation’s slow motion as +150 % damage.
- **Vampire Brass** and **Little Spark** now work correctly.

### Improved
- **No more useless cards:**
  - Reload charms only appear while you carry a ranged weapon.
  - Healing and low-health charms don’t appear alongside Glass Heart, shield charms don’t appear alongside Berserker Valve.
  - Blessings whose trigger can never fire are no longer offered.
- The build overview shows the real stacked value for chance-based charms.


---

## 18 Oct 2026 – New element and legendary effects (v2026.10.18.0211-17047554)

### Improved
- **Element effects completely redone (#76):**
  - **Element hits** are visible, with a shape for each element: blood drops, a lightning star, a void hole, tide bubbles.
  - **Links:** branching, flickering lightning, sagging threads of blood, flying shards.
  - **Waves per element:** a whirl of water with foam, a ring of blood spatter, a crackling lightning ring with forks, a void ring that collapses inwards. They appear on kill spread, ability waves, dash blessings and dash charge.
- **All 6 reactions** have their own effect with a short hit-stop and screen shake instead of the generic explosion.
- **A golden signature for legendaries:** Anchor Mines, Gravity Core, Fan Discharge, Prism of the Deep, Counterpressure Mantle, Mirror Shards, Kinetic Fist, Time Dilation, Blood Engine, Storm Crown, Chain Reaction.
- **Abilities:** Anchor Slam gets a ring on take-off, Phase Jump a ring on arrival.
- The new effects cost no FPS. Measured by switching back and forth with the old effects.


---

## 18 Oct 2026 – New attack telegraphs (v2026.10.18.0111-7461a0e4)

### Improved
- **Ground attack telegraphs completely redone (#77):**
  - Circles, lines and cones visibly fill up until impact.
  - The ground beneath darkens and the edge glows, so they read well on both light and dark floors.
  - Every faction has its own pattern: glyphs in the Temple, hazard stripes and rivets in the Drilling Station, veins among the corals, script and seals in the Archives, thorns in the Abyss.
  - **Elites** get a second ring, **bosses** a rotating crown of runes.
  - On impact there is a brief flash with a pressure ring.
  - Ink puddles and damage zones use the same style.


---

## 17 Oct 2026 – Controller and credits (v2026.10.17.1309-56a497c0)

### Fixed
- **Controller stuck at the end of a run:** after the leaderboard prompt, focus never came back. On a gamepad it now works like this: Y = New Dive, B/Start = To the Submarine, the right stick scrolls through the columns.
- **B closes the pause menu.** Hold prompts (research, pause) give focus back after you cancel.
- **Flaky test** stabilised (internal only).

### New
- **On-screen keyboard for your leaderboard name:** the “Keyboard” button or A on the field, in the opt-in prompt and under Settings → Online.
- **“Credits & Licences”** in the main menu and under Settings → Info: everyone who contributed, the Godot licence, the co-op networking libraries and the fonts.
- **More controller comfort:**
  - In the settings, LB and RB switch tabs, and long tabs scroll along with the focus.
  - On a gamepad, the explanation for the selected element appears as a small card.
  - In key bindings, a short press of B cancels; holding it binds B itself.
  - If nothing is selected in a menu, the next button press brings the focus back.


---

## 17 Oct 2026 – How many are diving right now? (v2026.10.17.0137-92e8ecd7)

### New
- **Live player count in the main menu:** “23 divers in the deep right now”, broken down by area and co-op groups. It updates every minute and is also shown on the website.
  - The game only sends an **anonymous heartbeat**: a random session ID, the area, and whether you’re playing solo or co-op. No names or IP addresses are stored.
  - Can be turned off under Settings → Online → “Share online player count”.


---

## 17 Oct 2026 – Run end hotfix (v2026.10.17.0002-39406e70)

### Fixed
- **The run end screen ran off the edge:**
  - On corrupted runs with several modes (e.g. Corrupted · Maelstrom Trench · Pressure 3), the “Portals & Modifiers” column was cut off on the right.
  - With lots of charms, the “New Dive” and “To the Submarine” buttons ended up below the edge of the screen.
  - Now everything stays on screen. The columns scroll when needed, and the buttons are always visible.
- **Leaderboard badges at the end of a run:** they now only show categories this run actually counts for. So no more “Fastest Victory” after you die.


---

## 15 Oct 2026 – CO-OP is here (v2026.10.15.2118-32bdde5d)

### New
- **Co-op for 1–4 players** (main menu → Co-op). Dive together through every area: enemies, bosses, trials and objectives play out the same for everyone.
  - Every player picks their **own charms and blessings**. **Shells** are shared.
  - **Downed:** you crawl, and teammates hold E to revive you. The run only ends once everyone is down.
  - **“Jump to Group”** brings stragglers back to the group.
  - **Pings** with the middle mouse button mark enemies, places and items.
- **Connecting:**
  - The host gets a **room code** (e.g. `ABC-123`). Teammates enter it and usually connect **without port forwarding**, even on DS-Lite.
  - On the same network, the lobby code is enough. IP, UPnP or a VPN work as alternatives.
  - A guide is included (`KOOP_ANLEITUNG.md`).
- **Co-op lobby in the submarine:** a player list with name, loadout, ping and ready status. The code is hidden by default and can be copied. The host can remove players. Everything works with a controller and the on-screen keyboard too.
- **Teammates as real divers:** a brass suit with a copper helmet, accents in the player’s colour, and helmet metal matching the diver chosen in the Wardrobe. They hold their weapons in both hands. Running, shooting, reloading, sword combos, crawling and reviving are all animated.
- **Co-op HUD:**
  - Teammate panels with health, shield and **live damage, DPS and kills**.
  - Name tags, arrows pointing to teammates off screen, a revive ring and an overlay with the bleed-out timer.
  - A comparison of all players at the end of the run.
- **Hear your teammates:** their own weapon sounds, footsteps per surface, reloads, shield breaks, calls for help.
- **Abilities are visible to everyone:** turrets (including “Sixfold Watch”), mines, Anchor Mines, the pull, Anchor Slam, the eel, Life Pulse.

### Notes
- Co-op runs don’t count towards the solo leaderboard. A separate co-op ranking will follow.
- Time Dilation (legendary) is solo only.
- Please report co-op feedback as an issue with “Co-op” in the title.


---

## 14 Oct 2026 – Online leaderboard (v2026.10.14.1956-674cb99f)

### New
- **Online leaderboard** (main menu → Leaderboard) with four rankings:
  - **Fastest Victory**
  - **Deepest Pressure** (corrupted runs)
  - **Damage Master**
  - **Daily Run**: everyone plays the same seed on the same day (card in the Diving Chamber).
- **Layout:** a podium for the top 3, places down to 100 with build icons, and your own row always visible. At the end of a run you see your place or “NEW RANK #X”.
- **Opt-in:** at the end of your first run, the game asks whether you want to take part. Under Settings → Online you can change your name or turn participation off. Only your name, the run stats and a random player ID are sent.
- **Your past runs count too:** when you opt in, you can upload your old runs from the Run History and your records.

### Improved
- **Enemy growls no longer nonstop:** each attack warning plays loudly at most every 2 s – nearby enemies and bosses always do. Purely atmospheric sounds come less often and more quietly. Your own weapon is a bit louder again as a result.


---

## 13 Oct 2026 – Night – big update (v2026.10.13.2110-18d62a60)

### New
- **13 legendary charms with their own mechanics.** For example:
  - **Anchor Mines:** every 3rd dash drops a mine.
  - **Gravity Core:** every 5th kill opens a vortex.
  - **Last Round:** the last shot hits ×3.
  - **Fan Discharge:** leftover rounds fire as a fan.
  - **Time Dilation:** below 30 % health, a kill slows down the world.
  - More: Prism of the Deep, Counterpressure Mantle, Storm Crown, Mirror Shards, Kinetic Fist, Blood Engine and others.
  - At most one legendary per offer, from Depth 2.
- **16 new blessings:** they now also trigger in the air, on melee, on reload, at low health, on ability use and after a dash.
- **24 new charms:** they boost abilities, shields and critical hits. Also new: the **RISK** category with cursed cards such as Blood Oath and Cursed Coin.
- **Every charm and every blessing now has its own icon.** Abilities get new icons in a hexagonal frame and a new Q slot with a cooldown display.
- **Hands-on reloads for every weapon:** the Keelbreaker, Shipyard Song, Whaler, Beacon, Depth Bomb and Voice of the Deep now use the moving support hand. Every weapon has a perfect reload and a jammed reload.
- **Hit feedback:**
  - Every hit throws sparks – ice blue on shields, yellow on weak points and orange on crits.
  - Explosions have a glowing core.
  - The muzzle flash no longer hides your target.
- **New enemy models for the Drowned Crew:** divers in canvas suits, Sludge Crawlers with eyestalks, a Rust Drone with a ducted propeller.
- **New sounds:**
  - picking up charms
  - merchant greeting and buying
  - reading stone tablets
  - switching weapons
  - a horn from wave 2
  - a pull before an enemy appears
- **Ambient sound of its own** in every area.

### Improved
- **Rooms:**
  - The Cloister and the Fountain Circle in the Temple have been redesigned.
  - Halls and galleries have loops and platforms.
  - Enemies no longer spawn right in front of or next to the entrance door.
- **Combat audio:**
  - Your own weapon keeps its punch.
  - Boss attacks can be heard across the whole arena.
  - The boss music is louder.
- **Performance with lots of enemies:** the enemy AI is more economical, enemy models are made of fewer parts, and reloading costs less processing time.
- **Interface:**
  - The shrine as a card view.
  - Codex tabs.
  - Icons on the death screen and in the main menu.
  - Close prompt with a key icon.
- **Logbook page (radio contract):** the golden card on the floor is now recognisable as a logbook page with a seal and lettering.

### Fixed
- **Tab overview:** nothing overlaps any more, even with lots of charms and at 4:3 or 21:9.
- **Ink Shade:** while camouflaged, it no longer gives itself away through affix icons, its elite name or its health bar.
- **Cleaner floating particles:** the pull no longer shows white squares, and the healing ring is thinner.


---

## 13 Oct 2026 – Evening (v2026.10.13.1609-7a45aa68)

### New
- **New Shipyard Song reload:** The hand rests on the side grip while the drum is swapped and the pressure valve is cranked open.
- **New room doors:** Instead of smooth blocks, there are now hewn stone doors with a seal disc. Their seams glow in the seal’s colour: red when locked, gold when a key opens them.
- **Abyss:** Behind the doors of the Herald and final boss arenas there is now a floating basalt cliff with a gate instead of a flat wall.
- **Lots of new sounds:** room doors opening and closing, urns shattering, the luck valve, a dedicated “can’t do that” sound, research, treasure locks, ability ready, and distinct warning cues for laser and steam enemies. The settings and pause menus now click.

### Improved
- **Sound mix in big fights:** With lots of enemies around, the audio no longer clips. Enemy warning cues cut through your own gunfire clearly. The music is a little louder.
- **Interface:**
  - Tooltips in the game’s own style.
  - Controller focus is easy to see on the station cards.
  - Boss bar with a brass frame.
  - The objective line stays readable on bright backgrounds.
  - Real button icons for interactions and reward choices.
  - More opaque HUD plaques.
  - A tidier pause menu.
- **Visuals:**
  - The glyph walls in the Temple glow inside the glyphs instead of as an orange grid.
  - Cover walls come in fitting lengths instead of being stretched.
  - The machine block in the Drilling Station now has a back side.
  - Corals without zigzag edges.
  - Giant clam without harsh stripes.
- **Performance:**
  - Up to 45 % more FPS with 80 enemies (Archives, Abyss).
  - Reloading costs far less processing time.
- **Archives:** The Copyist no longer paces back and forth at the map pit. Enemies are no longer reset into the platform corner of the Glyph Rotunda.


---

## 13 Oct 2026 – Midday (v2026.10.13.1330-fec547ba)

### New
- **New Keelbreaker reload:** The hand grips the fore-end, slides in a pair of shells and turns the valve wheel. A perfect reload and a jam now look clearly different.

### Improved
- **Boss fights in English too:** Every boss shout, phase announcement and the Archivist’s rules (“LECTURE: …”) is translated.
- **Enemies in the Archives:** The Copyist no longer paces back and forth at the book stack, and the Grave Worm no longer gets stuck in the wall after bursting out.

### Fixed
- Research Desk: Esc or controller B in the purchase prompt closed the whole station instead of just the prompt.
- Charm find: The prompt always showed “[V] smash”. It now shows your actual key, on controller too.


---

## 13 Oct 2026 – Hotfix (v2026.10.13.1053-d5254fa2)

### Fixed
- **Trial room:** If a trial enemy was removed in an unusual way, the trial could no longer be completed (the doors stayed shut). This is now detected properly. (As a fallback you can still hold E at the trial chest to give up.)


---

## 13 Oct 2026 – Night (v2026.10.13.1040-c2ff8406)

### New
- **Fully playable in English:** weapons, abilities, every charm and blessing, enemy and boss names, Dr. Marsh’s radio messages, the Codex and lore, hints and the loading screen – Settings → Gameplay → “Sprache · Language”.
- **Dedicated reload sounds for the Governor:** latch, steam, casings, loading, snap and ratchet; a perfect reload sounds solid, a jam sounds scratchy.
- **Readable states:** stunned enemies show silvery-white stars; large enemies and elites glow orange as they wind up; consistent colours for elites, weak points and affixes; the Governor’s cylinder glows after Fan the Hammer, and the Shipyard Song shows overpressure and overheating clearly apart.

### Fixed
- Medium-sized enemies (Tablet Bearer, Shield Warden, Leaper, Spike Runner) got stuck on straight staircases.


---

## 13 Oct 2026 – Evening (v2026.10.13.0837-9611357d)

### New
- **English language (Stage A):** Settings → Gameplay → “Sprache · Language” – menus, settings, HUD, objectives, run end and submarine stations in English, switchable live. Weapons, charms, enemies, radio and codex follow in the next updates.
- **Completely new revolver reload (Governor):** The hand really works the gun now – latch, the cylinder swings out (steam), casings eject, speedloader in and twist, cylinder snapped shut, the pressure gauge rises. Perfect reload: the cylinder snaps shut on its own in a puff of golden steam; jam: the loader tilts and has to be straightened.

### Improved
- **Less bloom:** fire bowls glow orange instead of white, smaller glow halos around doors and portals; room lights no longer shine through walls into neighbouring rooms.

### Fixed
- The boss announcement sometimes didn’t fade out.
- The Bestiary showed too much health for the laser fliers.


---

## 13 Oct 2026 – Update (v2026.10.13.0657-029fd9c7)

### New
- **Laser fliers from the third depth of every area:** Burning-Glass Moth, Cutter Drone, Lantern Jelly and Burning Page – low health, but powerful lasers. A targeting line follows you, locks on and flashes, then the beam fires – one sidestep dodges it; never more than two beams at once, and never from behind.
- **Sound in the submarine and underwater:** Inside the submarine everything sounds like a metal hull, underwater it’s muffled; when you dive, the chamber audibly floods and the sound crossfades.
- **More intense boss music:** drives from phase 1, thickens with every phase, has its own climax below 15 % boss health, plus stingers on phase changes and victory.

### Fixed
- **Settings:** Windowed mode now fits the window including its title bar on screen; V-Sync also caps correctly on secondary monitors with a different refresh rate; resolution is greyed out in fullscreen (with a hint); quality levels Medium/High/Ultra look visibly different; “High-Contrast Enemies” is much stronger; a second controller and stick deadzone now work; “Download Updates Automatically” takes effect immediately.

---

## 12 Oct 2026 – Evening (v2026.10.11.2026-f70be013)

### New
- **Shield break “Visor Crack”:** When your shield breaks, the helmet glass stars outward from the side you were hit – flash, short jolt, cracking glass, bubbles, and the shield arc shatters. Without a shield a subtle crack stays at the edge (the crosshair stays clear); it heals turquoise as the shield recharges. Can be turned off under Accessibility.
- **More visible healing:** a green surge from the screen edge, sparks on your hands, and the health arc visibly fills up.

### Improved
- **Redesigned abilities:** Anchor Slam (no more white screen; ground cracks, chunks of rock, ghostly chains), Phase Jump (violet pull, arrival ring, void rift), Pressure Mine (a proper naval mine that blinks before it explodes).
- **Glyph walls of the Archives’ Herald:** a wall of glowing glyph cards, the gap clearly marked with golden pillars of light, and it shatters against walls.
- **Hands:** fingertips are rounded instead of cut off, and the bump on the thumb is gone.

---

## 12 Oct 2026 – Update (v2026.10.11.1540-fc65643e)

### New
- **Resources explained:** During a dive the HUD shows the pearls you’ve already earned (“+N”); **hold Tab** to bring up an explanation of shells, pearls and cores; Workbench, Research Desk and Reliquary Shrine show pearls and cores with icons; new Codex entry under “Basics” and a hint from Dr. Marsh at your first shell.

### Improved
- **New Life Pulse:** The screen edge pulses twice like a heartbeat, a wave of life rolls across the floor and motes of light rise up.

### Fixed
- The planetarium in the Glyph Rotunda (Archives) poked into the ceiling beams while rotating.

---

## 11 Oct 2026 – Evening (v2026.10.11.1032-ab5a15f9)

### Improved
- **New Call of the Deep:** instead of a thin line, a 5 m ghost moray emerges from a ring in front of you, circles in curves and bites with its jaws wide open (ghostly jaws on the enemy).
- **Smoother Tide Blade:** no more jumps between combo strikes, guard and counter; no second blade flashing up while you guard, and the blade comes into view cleanly when drawn.
- **Objective pop-up:** Objectives, trials and radio contracts briefly appear large in the centre of the screen, then fly into the objective line; all objective texts state the next step more clearly.
- **Revolver reload:** The support hand now arcs around the gun and clips far less into the grip (not quite perfect yet).

---

## 11 Oct 2026 – Update (v2026.10.10.2338-3d33be1f)

### New
- **Run end for corrupted runs:** a new “Portals & modifiers” column – which portal you took at each depth, whether it was the hard one and which modifiers it carried (in the Run History too).

### Improved
- **Keelbreaker:** much punchier up close (fixed shot pattern, less spread, more damage at short range, beefier sound and recoil).
- **Governor:** left click = precision (higher weak-point bonus), right click = Fan the Hammer with spread and a longer reload afterwards (“CYLINDER HOT”).
- **Shipyard Song:** hold right click = overpressure with 30 rapid shots, then 2 s of overheating; clearly visible (glowing barrels, “OVERPRESSURE n/30” readout).
- **HUD:** dedicated icons for shells and keys; ability display with a large cooldown ring and an easy-to-read key.
- Causes of death on the run end screen are readable; “Most-used weapon” only lists actual weapons.

### Fixed
- Boss objects (seals, rift rings, egg sacs, coolant tanks, temple stones) stayed behind in the next depth after the boss fight.

---

## 10 Oct 2026 – Evening (v2026.10.10.1820-5f2ec06a)

### Improved
- **Unmistakable pickups:** shells are now golden scallops, keys are proper brass bit keys – easy to spot even from 10 m in a dark room.
- **Redesigned luck valve:** a copper boiler with a handwheel, a dial and a spinning lucky pearl.
- **Enemies stand on the ground:** On 21 enemy types, parts sank into the floor during animations (more than 2 m on death) – now it’s a few centimetres at most.

### Fixed
- The merchant stood with his back to the player – he now faces the entrance.

---

## 10 Oct 2026 – Update (v2026.10.10.1015-2318e3fa)

### Improved
- **Knights (Shield Warden, Stone Biter Veteran):** bigger shields; while guarding, the shield visibly blocks hits from the front, and the weak point is then hidden and can’t be hit.
- **Auto-updater:** downloads updates automatically in the background (can be turned off under Gameplay), verifies the download, installs only in the main menu, on quitting or at the next start – never mid-run – and reports success or failure. The new system kicks in from the update after next.

### Fixed
- Chests in treasure vaults stood crooked or inside walls (52 cases) – now properly aligned and clear.
- Decorations sat on pipes, stairs and ledges (281 cases → 7).
- The Drill Mother’s valves stayed behind in the rooms of the next depth after the boss fight.
- Octopus (Krakling): legs poked into the floor – they now stay on the ground.
- Sword push: small enemies flew up to 20 m and slanted into the ground – now they all fly the same distance (6 m) and level.

---

## 9 Oct 2026 – Update (v2026.10.09.2250-ec874f2a)

### New
- **Save & resume your run:** “Save & Quit” in the pause menu, “Resume Run · Depth N” in the main menu. The run restarts at the beginning of the saved depth with the same build; after death, abandoning or victory the save is gone.
- **Run History in the main menu:** your last 30 runs with time, depth, damage, biggest hit, resources, cause of death and build.
- **Perfect reload with left click too** (controller: right trigger), freely rebindable under Settings → Key Bindings. The click doesn’t fire a shot.

### Improved
- **Reliable active reload:** The perfect window is fixed at the start and always the same for the same weapon. A miss jams briefly (pointer red, window grey) instead of resetting the pointer; reflex presses right after an auto-reload no longer count; hit-stop no longer pauses the reload.

### In progress
- Knight guard/shield, octopus arms, chests in walls, a more reliable auto-updater.

---

## 8 Oct 2026 – Evening (v2026.10.08.1932-19fa964f)

### Improved
- **Governor reload:** The left hand clips far less into the grip while holding the cylinder and the speedloader (clipping roughly halved). One very brief moment while pushing in isn’t quite clean yet.
- **Research Desk:** Pearls and Abyssalite Cores stay visible at the top while scrolling; research only starts after confirmation (hold the button) – no more accidental spending.

### Fixed
- Invisible Ink Shades took area damage (explosions, mines) and gave away their position.

---

## 8 Oct 2026 – Addendum (v2026.10.08.1811-d277d31b)

### New
- **FPS display:** Settings → Graphics → “Show FPS” – frame rate and frame time in the top right (turquoise = smooth, yellow, red = low). Works in the main menu, the submarine and on expeditions.

---

## 8 Oct 2026 – Playtester update (v2026.10.08.1755-1cae1bb6)

### New / Improved
- **Abandoning a run now asks for confirmation:** no more accidentally giving up with the space bar – “Abandon” has to be held, and focus starts on “Cancel”.
- **Q abilities with a fixed minimum cooldown:** charms can no longer push cooldowns down to almost 0 s. Anchor Slam 20 s (but more damage: 200), Sentry 22 s; “Second Sentry” now deploys an additional turret.
- **Turrets and aim assist ignore invisible enemies** (they no longer give away cloaked Ink Shades/Paper Ghosts).
- **Urns can be smashed with a dash.**
- **Luck valve:** hold longer, plus a short lockout after every spin – no more paying twice.
- **New models:** valves (“vent the emergency pressure”, with handwheel, pressure gauge and bubbles) and the drilling rig (“protect the drill”, its core light shows its health).
- **New Weapon Rack in the submarine:** weapon list with icons and a detail card with stats.
- **The drilling rig in the Drilling Station** is no longer see-through.

### Fixed
- The crosshair partly turned black at small sizes.
- A room’s status (e.g. “TRIAL”) lingered in other rooms – now it only shows in that room.
- Field of view (FOV) is visible immediately in the pause menu; subtitle size changes live; Fog Quality is greyed out on “Low”.

### Known issues / in progress
- The hand on the revolver briefly clips during reload (cause found, fix coming), save & resume run, knight guard, octopus arms, chests in walls, a more reliable auto-updater.

---

## 7 Oct 2026 – Hotfix (v2026.10.07.1724-bebfbd8f)

### Fixed
- **Trial rooms: you could get locked in.** If the trial enemies died very quickly (right as they spawned),
  the trial never ended and the door stayed shut – forever on “Take no damage” and “Melee only”. The trial
  now detects this reliably.
- **New: give up a trial.** During a trial, **hold E** at the trial chest – the trial counts as
  failed and the doors open. You can always get out this way.
- Pump Hall (Drilling Station): the control desk and pressure gauge stood in front of / inside the exit door – now they’re to the right of it.

---

## 6 Oct 2026 – Evening update (v2026.10.06.1900-00541a6)

### New
- **Seven new enemy variants** from the second depth of every area, each with its own attack, look, weak point
  and Bestiary entry:
  - Temple: **Stone Biter Veteran** (shield blocks from the front, shield charge – afterwards its head is exposed) and
    **Shard Spitter** (shard fan; when enraged, a ring of shards to jump over)
  - Drilling Station: **Foreman** (triple strike, his whistle speeds up his allies) and **Overpressure Boiler Bearer**
    (steam ring up close, steam bombs at range)
  - Coral: **Brood Larva** (splits into two larvae on death)
  - Archives: **Snare Copyist** (lays seal traps you can shoot) and **Hex Reader** (slow homing orbs you can shoot down)
- **Boss deaths as proper sequences:** Xal-Tuun breaks apart into glowing stone blocks, the Drill Mother overheats and sputters
  out, Ysmera sinks down as her corals go dark, the Archivist dissolves into pages and glyphs, the Sleeper’s
  Ear topples into the Abyss – and then light rises. Heralds get their own, shorter version.
- **Bosses feel more alive:** a visible reaction at every phase change (staggering, roaring, armour plates breaking off),
  struck parts twitch on heavy hits, the chest breathes, the head follows you.
- **Eye-catchers in every large hall** of the Archives and the Drilling Station: a celestial globe, a seal organ,
  a chandelier cascade, a sunken reading rotunda, a wall of shelves with a toppled bookcase; derrick gearworks, a gantry crane with
  a giant drill bit, a boiler battery, an ore conveyor, a pressure lock, a cooling tower.
- **Impacts per surface:** stone, metal, wood, coral, sand and crystal each have their own particles, bullet holes and
  sounds; buckshot leaves lots of small holes, the harpoon a crack, the Depth Bomb a scorch mark, the
  Beacon a glowing trail. Bubbles rise from the holes.

### Improved
- **Balance (please test this specifically!):** Difficulty was re-measured without hardware load. From area 2 on, the
  combat rooms were too easy – enemies there now have roughly double (area 2) or almost triple (areas 3 and 4) the health.
  With a normal build, bosses should take roughly 1–1.5 minutes; Xal-Tuun, the Drill Mother, Ysmera, the Archivist and the Ear were
  tuned accordingly. **Feedback on depths 5–11 is especially important.**
- **Submarine stations open without stutter:** the Diving Chamber used to take up to 100 ms, now around 5 ms; the same goes for the Workbench, Codex,
  Research, Firing Range, Shrine and Wardrobe.
- **Coral ship:** enemies no longer get stuck in the hollow hull or on the railing; fliers rise over low
  walls.

### Fixed
- Loot carrier: the golden elite name and “◆ LOOT” overlapped – now only the loot marker is shown.
- Removed a rubble pile right in front of the portal platform.

### Known issues
- With lots of enemies in the Drilling Station, the frame rate can drop a little (being re-measured).
- Co-op is still in its own test build and not yet in the main game.

---

## 6 Oct 2026 – Afternoon (v2026.10.06.1636-7aef2ef)
- **Smarter enemy groups:** melee enemies attack from several sides instead of in a line, extras wait in a
  semicircle; at most one attack from behind at a time; marksmen change position after a few volleys and look for
  cover; support enemies stay behind the front line; some dodge mines and Sentries or briefly retreat when wounded;
  groups “wake up” with a shout.
- **Livelier first-person view:** weapon bob in step with your stride, tilt when strafing, landings cushion according to fall height,
  breathing while standing still, the weapon lowers in front of walls, heavy weapons respond more sluggishly. Can be turned off via “Camera Bob”.
- **Negative effects in the HUD** (Malicious, Crippling, Toxic, Ink) with icon and remaining time; Singularities no longer
  stack.
- **Balance:** a smoother difficulty curve, more healing in the middle stretch, **a healing shrine before the final boss** (portal room,
  depth 13), healing orbs scale with the area, charm rarity rises with depth again (that was a bug).
- **Faster menus:** reward choice, pause menu, merchant and settings open in stages and without stutter.
- **Fixed:** Anchor Slam threw enemies into ceilings; Codex pop-up during the Herald pause; Herald lore locked on old
  saves; Codex list with a controller; the salvage drone blocked the view; the Stone Worm could burrow in invulnerable under
  bridges (softlock).

## 6 Oct 2026 – Midday (v2026.10.06.1404-484f4bf)
- **First-time hints from Dr. Marsh** for new players (can be turned off), “NEW” markers on the submarine stations, a “Basics”
  tab in the Codex.
- **Codex and lore:** 72 lore entries, a Bestiary for every enemy, 217 radio messages instead of around 60, with callbacks
  (“Back in …”), 12 stone tablets; a “New Codex entry” pop-up.
- **A submarine full of detail:** depth gauge (last dive/record), a trophy board of defeated bosses, a crew board,
  logbook, wall pipes with steam and condensation, fish and a leviathan outside the portholes, swinging lamps – and its
  own ambient soundscape.
- **New sounds** for chests, portals, fire bowls, wildlife, objectives and radio contracts.
- **5 new charms** (Ramming Spur, Abyssal Catalyst, Pressure Release, Executioner, Overpressure), more frequent element reactions,
  Anchor Slam with a pull, a buff bar in the HUD.
- **Weapon lighting:** no more mint sheen on the Governor; support hand on the cylinders, slimmer cuff.
- **Stutter-free boss entrances** (under 16 ms); lit boss arenas, a glow rising from the Abyss.

## 6 Oct 2026 – Morning (v2026.10.06.1027-2e55750 and v2026.10.06.0825-bf3062b)
- New chests (planks, fittings, contents, opening animation), a portal with a rune ring, a vault door, a trial chest with an ember seal.
- Wall and fill lighting for large halls; more readable enemies (distance outline, affix icons, golden elite names).
- Boss polish: new feet for Xal-Tuun, the Drill Mother’s combustion chamber, a tentacle arc for Ysmera, the Archivist’s distance;
  enemy parts right in front of the camera are hidden.
- Inspect any weapon with F, headshots on the training dummy, enemies’ feet stay on the ground.
- Gentler start (depths 1–3), recognisable drops, large enemies no longer walk through the ship.

## 5 Oct 2026 (v2026.10.05.0533-34027b5)
- Revolver with visible rounds, and a reload with casings and a speedloader.
- New walk cycles for 14 enemies, music per boss and room type with its own victory theme.
- Four new objectives (sonar buoy, Abyssalite Cores, salvage drone, loot carrier) and radio contracts per depth.
- Wildlife: schools of fish, jellyfish, plankton, crabs, shells, a distant leviathan.

## 4 Oct 2026 – Evening (v2026.10.04.2100-1f2e090)
- New hand and a second hand, a fluid blade combo; Ysmera’s tentacles, a floating Xal-Tuun, the drill head.
- 3D kelp, sea urchin mines, the throne of the Great Hall; an end screen after victory and a records board in the main menu.
- Snappier dash, visible status effects, livelier enemy animations, card-style menus with their own icons.

## 4 Oct 2026 – first test build (v2026.10.04.1128-68aba1d)
- First public test version with auto-updater.
