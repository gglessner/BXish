# Changelog

All notable changes to the BXish B/X Dungeon Master Skill.

## [2.4.0] -- 2026-02-20

### Added
- New section in SKILL.md: **NPCs & Social Play** -- six rules for running NPCs, social encounters, logistics, and information gathering as meaningful gameplay.
- Rule 1: **One action, not a paragraph.** Define each NPC by one behavior or habit, not backstory. A single defining detail ("She pocketed the gold without counting") establishes more than a paragraph.
- Rule 2: **Information scales with effort.** Random barkeep = surface rumors. Seeking the right expert = identification + tactics + countermeasures. Bribing an observant NPC = specific details. Reward investigation proportionally. Players who research before an encounter earn tangible advantages.
- Rule 3: **Hooks through NPCs, not lists.** Adventure leads come from different NPCs in different contexts (farmer at the inn, watchman overheard, merchant buying a drink). Never present a quest board. Let leads compete and let the player choose.
- Rule 4: **Engage with social tactics.** When players create cover stories or bluffs, play along. Let NPC intelligence create tension -- smart NPCs may see through a lie but play along for the money. Don't break covers immediately, don't let them work perfectly. The gap between lie and truth is where drama lives.
- Rule 5: **Logistics are drama.** Gold weighs something. Moving it requires planning. Security is a resource you buy. Present logistical challenges as problems to solve, not ledger entries.
- Rule 6: **NPC relationships evolve.** Track how reactions shift based on party behavior. Fair dealing moves NPCs from neutral to loyal. Small moments of earned trust (a token, a standing offer, a parting warning) create recurring contacts.

### Fixed
- Sessions 1-4: NPCs were functional but interchangeable (shopkeepers named on introduction, forgotten by next scene). Under the new rules, each NPC gets one defining action that makes them instantly distinct and memorable.
- Sessions 1-4: Adventure hooks were either pre-placed (the tomb existed, party went there) or DM-suggested. Under the new rules, hooks emerge organically from NPC conversations in different social contexts, giving the player a real choice between competing leads.
- Sessions 1-4: Treasure was grabbed, split, and carried out with no logistical challenge. Session 5's gold transport problem (900lbs of coin, cart purchase, escort hiring, overnight security, bank deposit) proved that logistics create entire sessions of engaging play. Rule 5 now codifies this.
- Sessions 1-4: Town visits were transactional (buy gear, leave). Session 5's Thornwall sequence showed that social play (cover stories, bribes, relationship-building with Kael's group) generates more player engagement than any dungeon room. Rules 4 and 6 capture this.

## [2.3.1] -- 2026-02-20

### Changed
- `15-encounters-evasion.md`: Expanded surprise section with tactical guidance. Surprise for position over damage (control doorway, set spears, create missile lanes, back out and spike door). Distance matters (close = contact, far = choices). Surprise doesn't auto-mean combat (roll reaction if intelligent + no attack yet). Surprise as morale trigger (first-round shock breaks morale early).
- Inspired by Tenkar's Tavern (Erik Tenkar), "Stop Running Surprise Wrong in B/X (It's One Round)", 2026-01-18.

## [2.3.0] -- 2026-02-20

### Added
- New reference file: `44-when-to-roll.md` -- general ruling framework for when dice should hit the table and when to just play it out.
- Three-question test: is the outcome uncertain? Is failure interesting? Does time or pressure matter? All three must be yes for a roll.
- Four outcomes: auto-success (specific + plausible), auto-fail with a handle (impossible + redirect), success at time cost (broad + sloppy), roll (uncertain + pressured + failure changes things).
- "Tell me what you're doing, not what you're rolling" -- retrains play from character sheet interaction to world interaction.
- No "try again" rule: if a roll can be repeated with no risk, don't roll. Failed actions must change the situation, cost time, or require a new approach.
- Practical examples: searching rooms (specific vs. broad), stuck doors (fail = time + noise, not permanent), listening, forcing things, climbing, sneaking (graduated failure), trap disarming (links to `34-trap-procedures.md`).
- Clean default table: specific+plausible=works, broad+sloppy=costs time, dangerous+pressured=roll, impossible=doesn't happen.
- Expanded "Rulings over rules" in SKILL.md Core Principles with the three-question test and link.
- Inspired by Tenkar's Tavern (Erik Tenkar), "When Do You Roll? The OSR Answer", 2026-01-12.

### Changed
- `34-trap-procedures.md` is now a specific application of the general framework in `44-when-to-roll.md`. Both files cross-reference.

### Fixed
- Sessions 1-4: Several moments where rolls were called for situations that should have auto-succeeded (e.g., specific search methods, listening at doors with clear sounds). Under this framework, specific player methods earn auto-results; rolls reserved for pressured uncertainty.

## [2.2.0] -- 2026-02-20

### Added
- New reference file: `43-session-prep.md` -- structured 20-minute pre-session audit that prevents campaign drift and sharpens pacing.
- Step 1: "What are we doing" sentence -- one-line session spine ("Right now, the party is trying to ___"). If you can't finish it in 10 seconds, the campaign is in a fog.
- Step 2: Three active pressures from five categories (time, resource, social, environmental, mystery). "If your campaign feels sleepy, it's because you don't have pressures."
- Step 3: Two doors check -- two playable leads that compete (not cancel). Door A = what they care about, Door B = competing opportunity.
- Step 4: One scene you can run blind -- safety net with three archetypes (bad bargain, misleading help, price of quiet). Prep: who wants what, what if yes, what if no.
- Step 5: Quick pass on treasure and consequences -- sharpen, don't redesign. Links to `40-treasure-design.md` and `42-faction-play.md`.
- Full 20-minute checklist table with time allocations per step.
- Session prep summary added before Session Start in SKILL.md Running the Game.
- Inspired by Tenkar's Tavern (Erik Tenkar), "20 Minute GM Audit: The Forgotten Prep Step Every DM Needs", 2025-12-24.

## [2.1.0] -- 2026-02-20

### Added
- New reference file: `42-faction-play.md` -- full faction procedure for sandbox play across dungeons, towns, and wilderness.
- Faction card template: name, want, have, fear, tell (how players recognize them), ally, enemy, job. Five lines per faction on an index card.
- **Factions must be uneven:** one has muscle, one money, one leverage, one is desperate. Balance kills gameplay.
- **Two faction moves per session:** between sessions, pick two factions, write one sentence each for what they do. Living world without a novel.
- **Reaction rolls as faction engine:** hostile = threaten/demand/escort out, friendly = "we can use you." Let the dice surprise you.
- **Morale rolls for faction behavior:** when factions break, retreat, bargain, or live to fight another day. Creates recurring enemies and shifting alliances.
- **Consequence chains:** help goblins → cult retaliates. Expose cult → goblins turn to banditry. Steal relic → everyone wants the party. Do nothing → factions advance without them.
- **"Clear, not clever" rule:** show faction motives through environment (shaken shopkeeper, sermon, tax notice), not exposition.
- Full worked examples: dungeon (goblins/cult/skeleton patrols) and town (dockside guild/temple/tax man).
- Quick prep checklist: three factions, five lines each, two moves per session, reaction/morale rolls, environmental tells.
- Faction play summary added to Running the Game section in SKILL.md.
- Inspired by Tenkar's Tavern (Erik Tenkar), "Factions: The OSR Sandbox Engine", 2026-02-14.

### Changed
- `39-dungeon-design.md` retains its brief faction ecology section (three questions + ally/enemy/job). The new `42-faction-play.md` expands this into a full procedure with tells, between-session moves, uneven power, reaction/morale framing, and consequence chains.

### Fixed
- Sessions 1-4: The Tomb of Valdros had no factions -- just undead in rooms. Under this framework, even a small dungeon should have competing interests (e.g., ghouls vs. the wight's territory, or scavengers drawn by the party's activity) that create negotiation opportunities and consequences.

## [2.0.0] -- 2026-02-20

### Added
- New reference file: `41-carousing.md` -- complete between-adventure downtime procedure for spending gold, generating rumors, and creating town complications.
- Full carousing procedure: declare stake (light/standard/hard by level), choose intent (rumors/contacts/heat dump/blow off steam), roll 2d6+CHA, apply results by band (trouble/mixed/good/great).
- Spending tiers: light 50gp/lvl (1 rumor), standard 100gp/lvl (2 rumors), hard 200gp/lvl (3 rumors). Money is gone.
- Four intents with distinct outcomes per result band. Base rumors always awarded regardless of roll.
- Trouble table framework (brawl, lost purse, public scene, owed favor, property damage, watch attention). Trouble is hooks, not punishment.
- Rumor table framework (d12-d20, setting-specific adventure leads, not flavor text).
- Optional carousing XP: 10% of gold spent.
- Adventure loop placement: carouse after return to town, before rumor drop, before shopping.
- Running guidance: one sentence of color, don't make it a mini-campaign, keep it to five minutes.
- Carousing summary added to Running the Game section in SKILL.md.
- Inspired by Tenkar's Tavern (Erik Tenkar), "B/X Carousing Rules: Spend Gold, Get Rumors, Start Trouble", 2026-02-15.

### Changed
- Version bumped to 2.0.0: the skill now covers the complete adventure loop -- dungeon, wilderness, town, treasure, downtime, and back again.

### Fixed
- Sessions 1-4: Town visits were pure shopping (buy torches, buy oil, leave). Under carousing rules, returning to town should generate rumors, contacts, complications, and gold drain -- making town a gameplay phase, not a menu screen.

## [1.9.0] -- 2026-02-20

### Added
- New reference file: `40-treasure-design.md` -- design philosophy for treasure that creates gameplay decisions instead of accounting.
- Core principle: good treasure is valuable and inconvenient. If it fits in a pocket, you've removed half the game.
- Quick placement test: does treasure change movement, time, risk, or town events? If no to all, it's just payroll.
- Four treasure categories: big bulk (forces logistics), proof/paperwork (social risk), hot items (faction property, everyone wants it), route-changers (can't retreat the safe way).
- Treasure fights resources table: hauling competes with time, light, speed, stealth, spells, free hands.
- Resale as gameplay: sell fast (half value), sell quiet (full value + risk), sell open (full value + heat), return it (favor/ally), keep it (ongoing leverage).
- Town heat from treasure: connects to `33-town-procedures.md` heat track. Flashing loot = +1, selling faction property = +2.
- Fair play rule: say the important parts out loud (heavy, fragile, loud, hard to sell). Let them take part and leave the rest.
- Why hirelings/mules matter: if treasure always fits in pockets, the party never needs labor.
- Treasure design summary added to Running the Game section in SKILL.md.
- Inspired by Tenkar's Tavern (Erik Tenkar), "Treasure That Forces Hard Choices (Not Just Gold)", 2026-02-05.

### Fixed
- Sessions 1-4: Treasure was mostly clean coin (grab gold, split evenly, walk out). Under new framework, at least some treasure should have been bulky, identifiable, or hard to sell -- creating logistics decisions, town consequences, and reasons to hire porters.

## [1.8.0] -- 2026-02-20

### Added
- New reference file: `39-dungeon-design.md` -- structural design principles for dungeons that feel alive during play.
- **Loops:** Linear dungeons (hallways with rooms on sides) kill player agency. Loops provide multiple routes, tactical retreats, flanking, spatial memory. Four methods to add loops: secret doors connecting rooms, same-level staircases, trapped chutes to visited rooms, faction side tunnels.
- **Rule of Three States:** Every room exists as Found → Disturbed → Reacting. Distinct from restocking (which is between sessions) -- this is the dungeon reacting during play. Kill guards → doors barred, patrols double. Make noise → creatures investigate. Set fire → smoke alters navigation.
- **Sensory motion over lore:** Living dungeons have behavior (clanging, dripping, air currents, rats, chanting), not backstory paragraphs.
- **Faction territory as ecology:** Goblins avoid undead rooms, cults control lower levels, beasts deny passage, vermin scatter before bigger trouble. Quick faction setup: want/have/fear + one ally, one enemy, one job.
- Dungeon design summary added to Dungeon line in SKILL.md Running the Game.
- Inspired by Tenkar's Tavern (Erik Tenkar), "Dungeon Design Secrets -- How to Build OSR Dungeons That Feel Alive", 2026.

### Changed
- Dungeon line in SKILL.md now references both `39-dungeon-design.md` (structure during play) and `38-dungeon-restocking.md` (between-session response).

## [1.7.1] -- 2026-02-20

### Changed
- `35-telegraphing-danger.md`: Added three new sections for random encounter telegraphing (non-redundant content only).
- Random Encounter Arrival method: approaching (party careful) / crossing (standard) / already here (party loud). Decide based on party behavior.
- "One signal before initiative" -- give one sentence of warning, then let players act. Roll surprise after they commit.
- When NOT to telegraph: party is loud, loitering, or in known high-traffic areas.
- Type-specific cue table: patrols (boot scruffs, call-response), predators (bones, drag trails, vermin silence), undead (temperature drop, stale air, whispering).
- Inspired by Tenkar's Tavern (Erik Tenkar), "B/X Random Encounters: Telegraph Them or Surprise Them?", 2026-01-31.

## [1.7.0] -- 2026-02-20

### Added
- New reference file: `38-dungeon-restocking.md` -- procedure for making dungeons react between sessions instead of resetting or staying frozen.
- Core rules: empty space gets claimed, survivors learn. Two questions: how long gone, what did the party change.
- Time brackets (day/week/longer) and restocking dial (light/medium/heavy) for scaling response.
- Four-part framework: survivors (adapt, relocate, negotiate), intruders (claim cleared space), pressure (new constraints on movement), scars (evidence of party's last visit).
- Pre-session checklist: 8 steps to run right before play when party returns to a dungeon.
- Treasure rules: loose+obvious+portable = gone; hidden/bulky = still there but harder. Don't take treasure every time.
- "We'll come back with a cart" scenarios: quick return (eyes on it), week (moved deeper / stripped / someone else working on it), long (it's theirs now).
- Dungeon restocking summary added to Dungeon line in SKILL.md Running the Game.
- Inspired by Tenkar's Tavern (Erik Tenkar), "Dungeon Restocking Made Easy (Without 'Resetting' It)", 2026-02-11.

### Fixed
- Sessions 1-4: Tomb of Valdros was mostly static across four visits. Under new framework, ghouls should have reacted between sessions (barricade with deer carcass, crude alarm at door), cleared cavern could have attracted vermin, shrine should have shown signs of disturbance.

## [1.6.0] -- 2026-02-20

### Added
- New reference file: `37-three-layer-encounters.md` -- three-layer encounter design method for keying encounters that feel alive.
- Layer 1 (Surface): what players think is happening -- the immediate sensory hook.
- Layer 2 (Truth): what's actually going on beneath the surface -- rewards observation and curiosity.
- Layer 3 (Sideways): what happens when things go wrong -- one sentence of natural momentum.
- Four worked examples: kobold sack, wounded ogre, chest bait, white flag ambush.
- Prep format: three lines per encounter in a notebook. No novel, no stat block essay.
- Cross-references to telegraphing danger (Layer 1 = sensory hook), trap procedures (Layer 2 = what investigation reveals), and morale/reactions (Layer 3 = what chaos produces).
- Encounter Design reference link added to SKILL.md.
- Inspired by Tenkar's Tavern (Erik Tenkar), "The Three-Layer Encounter: The OSR Trick That Instantly Makes Your Encounters Better", 2025-12-11.

## [1.5.0] -- 2026-02-20

### Added
- New reference file: `36-hex-crawl-procedures.md` -- approach for running wilderness hex crawl travel as meaningful decisions, not slog.
- Core principle: "The hexes don't matter. The decisions matter." Exploration is incidental, not mandatory.
- Purposeful travel: every journey needs a destination or mission. If players wander, drop rumors, signs, NPC requests, or looming threats.
- Minimal map prep: 10-20 points of interest, 3-5 factions, 3-6 rumors, 1-2 big unknowns, 1 major destination.
- Travel pacing: days not minutes. Each day = 1 macro decision, 1 flavorful moment, 1 resource check, 1 encounter roll. Beats, not filler.
- Random encounters reframed as story signals: shifting factions, migrating monsters, rival parties, hints about what lies ahead.
- Wilderness day sequence linking to mechanical procedures in 14-exploration.md.
- Emergent play guidance: hex crawl evolves into strongholds, faction reactions, rival parties, mysteries. Don't force arcs.
- "What NOT to do" quick reference: don't require clearing every hex, don't describe every mile, don't use encounters as filler combat.
- Wilderness summary in SKILL.md Running the Game expanded with approach guidance and link to new reference file.
- Inspired by Tenkar's Tavern (Erik Tenkar), "Hex Crawls Done Right — Why Most People Run Them Wrong", 2025-11-20.

## [1.4.0] -- 2026-02-20

### Added
- New reference file: `35-telegraphing-danger.md` -- framework for giving players readable risk without spoiling surprises.
- Escalation ladder (6 rungs): sensory cues → environmental tells → monster signatures → NPC warnings/rumors → first bite (non-lethal contact) → commitment points (thresholds where retreat gets hard).
- Three anti-spoiler rules: clues not labels, make warnings actionable, keep truth slightly out of focus (accurate but incomplete).
- Quick no-notes method: for any dangerous area give one sensory clue, one piece of evidence, one actionable detail.
- Worked examples: Medusa's chamber, "fight above you" signals, "this area is cursed" signals.
- Guidance on untelegraphed save-or-die: always bad play. Telegraph early, escalate, give the first bite, then full consequences are earned.
- Telegraphing Danger summary line added to Running the Game in SKILL.md with link to reference file.
- Inspired by Tenkar's Tavern (Erik Tenkar), "Telegraph Danger (Without Spoiling It) — The OSR Fairness Rule", 2026-01-05.

### Fixed
- Session 3: Valdros's burial chamber lacked sufficient escalation. The sarcophagus cracking open was presented in the same block as the room description with no intermediate decision points. Under the new framework, the freezing cold, the cracking lead wards, and the flaring gems would each be a rung giving the player a chance to act before full contact.

## [1.3.0] -- 2026-02-20

### Added
- New reference file: `34-trap-procedures.md` -- Intent→Information→Roll method for trap detection and disarmament.
- Core method: Player states where and how they're searching. DM gives clues (not answers). Roll only when time, precision, noise, or danger matter.
- Tool table: 10-foot pole, chalk/flour, mirror, string, iron spikes, water/oil, listening/tapping -- each earns specific information when used appropriately.
- Thief role clarified: everyone can investigate and bypass traps; the thief gets the cleanest/fastest disarm for fine mechanisms. Thief skill is a niche, not a gate.
- Common trap type examples with clues, player options, and roll triggers: pressure plate, needle lock, dart holes, pit trap.
- Trap design principles: traps exist to make the dungeon feel engineered, make time matter, and force trade-offs.
- "Make time visible" guidance: say costs out loud so players choose their own trouble.
- Trap summary line added to Running the Game in SKILL.md with link to reference file.
- Inspired by Tenkar's Tavern (Erik Tenkar), "The OSR Trap Procedure That Actually Works", 2026.

### Fixed
- Session 1: Pit trap was pure slot machine -- Varro rolled Find Traps 20%, failed, trap fired. Under new method, probing with a pole would have revealed the shifting stone, giving the party a decision instead of a gotcha.

## [1.2.0] -- 2026-02-20

### Added
- New reference file: `33-town-procedures.md` -- procedural system for running towns as structured play rather than freeform shopping episodes.
- Town loop: destination, contact/reaction, resolve, tick time, trouble check, update heat, repeat.
- Six reusable anchor locations: inn, market, temple, authority, specialist, shady option. Prep 1 sentence each.
- Three town pressures: faction, law, scarcity. Provide friction and consequences.
- Heat track (0-5): escalating consequence system based on party behavior. Attention rises from crimes, flashing wealth, violence; falls from laying low, quiet spending, faction favors.
- Town turns (~1 hour each): every meaningful action costs a turn, trouble checked each turn at 1-in-6 modified by behavior.
- Town trouble table: complications tied to prepped pressures (guards, rival buyers, rumors, watchers) rather than immediate combat.
- Selling treasure procedure: run through the loop with reaction rolls, buyer questions, and consequences.
- Quick town prep format (index card): name/vibe, law, scarcity, factions, anchors, plus one unique problem.
- Town section added to Running the Game in SKILL.md with summary and link to reference file.
- Inspired by Tenkar's Tavern (Erik Tenkar), "How to Run Towns Without Panicking (OSR-Style)", 2026-02-10.

## [1.1.0] -- 2026-02-20

### Changed
- Refined Player Agency rules from 6 to 10 based on Session 4 playtesting.
- Rule 1 (Describe, then ask) now specifies including 2-3 interactable environmental details in room descriptions to invite player engagement.
- Rule 2 (One combat round per input) now requires showing updated enemy status after each round.

### Added
- Rule 3: **Always ask for targeting.** Never decide which enemy a PC attacks. Ask when orders are ambiguous (e.g., "throw oil at them" -- which target for each person?).
- Rule 4: **Ask, don't assume.** When player orders are ambiguous (resource splits, action sequences, targeting), ask a brief clarifying question rather than guessing.
- Rule 9: **Resource awareness at decision points.** Briefly note relevant supplies, spells, and abilities at moments where they might matter. Don't suggest how to use them.
- Rule 10: **Pacing.** Compress routine travel through known territory. Expand time for new spaces, NPC conversations, and real player choices.
- Adventure Session 4 transcript (adventure-session-4.md).

### Fixed
- Sessions 1-3: DM auto-assigned skill checks (e.g., "Aelindra searches for secret doors") without player input. Rule 8 now prevents this.
- Sessions 1-3: DM resolved multiple combat rounds without asking for player actions each round. Rule 2 now enforces one round per input.
- Session 1: DM chained movement into the cavern directly into the carcass crawler encounter with no pause. Rule 5 now requires a stop before events trigger.
- Session 1: DM decided Round 2 actions for Aelindra (drew sword and attacked) without asking the player. Rules 2-3 now prevent this.
- Session 3: DM triggered Valdros rising from his sarcophagus in the same block as the room description, giving the player no chance to act first. Rule 5 now prevents this.

## [1.0.0] -- 2026-02-20

### Added
- Initial Player Agency section with 6 rules, based on analysis of Sessions 1-3.
- Rules: Describe then ask, one round per input, pause before new areas, downtime checkpoints, NPCs react don't lead, don't assume who does what.

## [0.1.0] -- 2026-02-17

### Added
- Initial skill creation with 33 reference files covering all B/X rules.
- Core DM procedures in SKILL.md: Core Principles, Running the Game, Key Rules.
- Progressive disclosure via linked reference files loaded on demand.
- Adventure Sessions 1-3 transcripts.
