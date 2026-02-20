# BXish -- B/X Fantasy RPG AI Skill

**Author:** Garland Glessner (gglessner@gmail.com)
**Version:** 2.4.0

A scaled-down, AI-optimized tabletop RPG ruleset designed to facilitate classic B/X fantasy play through an AI agent skill. The rules have been distilled into compact, machine-readable markdown files that fit within LLM context windows while preserving the full mechanical depth needed for authentic old-school dungeon crawling.

## What This Is

BXish is a Cursor agent skill that turns an AI into a competent, rules-faithful Dungeon Master for B/X-style fantasy RPGs. It handles character creation, combat, spellcasting, exploration, treasure, monsters, and all the procedural systems that make old-school play tick -- wandering monsters, reaction rolls, morale checks, encumbrance, torch tracking, the works.

The skill is split across 33 reference files organized by topic, loaded on demand during play so the DM always has the right rules at hand without blowing out the context window.

## Repository Structure

```
BXish/
  .cursor/skills/bx-dungeon-master/    # The AI Dungeon Master skill
    SKILL.md                           # Skill entry point and core DM procedures
    01-core-rules.md                   # Fundamental mechanics
    02-character-creation.md           # 13-step character creation process
    03-character-classes.md            # All 7 classes with full progression tables
    04-advancement-wealth.md           # XP, leveling, titles
    05-equipment.md                    # Weapons, armor, gear, costs
    06-vehicles-mounts.md              # Transport and mounts
    07-hired-help.md                   # Retainers, specialists, mercenaries
    08-strongholds.md                  # Domain-level play
    09-magic-system.md                 # Spellcasting rules and mechanics
    10-cleric-spells.md                # All cleric spells
    11-mu-spells-1to3.md               # Magic-user spells levels 1-3
    12-mu-spells-4to6.md               # Magic-user spells levels 4-6
    13-adventuring.md                  # Party organization, time, encumbrance, hazards
    14-exploration.md                  # Dungeon, wilderness, and waterborne procedures
    15-encounters-evasion.md           # Encounter distance, surprise, reactions, evasion
    16-combat.md                       # Full combat sequence and special cases
    17-running-adventures.md           # DM guidance for sessions
    18-adventure-design.md             # Dungeon and wilderness design procedures
    19-monster-rules.md                # Monster stat block format and special abilities
    20-monsters-ab.md                  # Monsters A-B
    21-monsters-c.md                   # Monsters C
    22-monsters-d-ge.md                # Monsters D-Ge
    23-monsters-gi-ly.md               # Monsters Gi-Ly
    24-monsters-m-o.md                 # Monsters M-O
    25-monsters-p-s.md                 # Monsters P-S
    26-monsters-t-z.md                 # Monsters T-Z
    27-encounter-tables.md             # Wandering monster tables by level and terrain
    28-treasure.md                     # Treasure types and generation
    29-magic-items-armor-misc.md       # Magic armor, miscellaneous items
    30-magic-items-potions-rings.md    # Potions and rings
    31-magic-items-rods-scrolls.md     # Rods, staves, wands, scrolls
    32-magic-items-swords-weapons.md   # Magic swords and weapons
    33-town-procedures.md              # Town loop, heat track, anchors, pressures
    34-trap-procedures.md              # Intent→Information→Roll, tools, thief role
    35-telegraphing-danger.md          # Escalation ladder, sensory cues, readable risk
    36-hex-crawl-procedures.md         # Purposeful travel, minimal prep, beats not filler
    37-three-layer-encounters.md       # Surface, truth, sideways encounter design
    38-dungeon-restocking.md           # Survivors, intruders, pressure, scars
    39-dungeon-design.md               # Loops, three states, sensory motion, faction ecology
    40-treasure-design.md              # Valuable+inconvenient, four categories, resale, town heat
    41-carousing.md                    # Spend gold, get rumors, start trouble, between-adventure loop
    42-faction-play.md                 # Faction cards, uneven power, two moves/session, consequence chains
    43-session-prep.md                 # 20-minute GM audit, pressures, two doors, safety-net scene
    44-when-to-roll.md                 # Three-question test, four outcomes, no try-again, ruling framework
  adventure-session-1.md               # Session 1: First delve, carcass crawler, 3,100gp
  adventure-session-2.md               # Session 2: Turning ghouls, looting sarcophagi, 2,500gp
  adventure-session-3.md               # Session 3: Valdros the Wight destroyed, magic sword, 3,660gp
  adventure-session-4.md               # Session 4: Ghouls eliminated, Edric found, tomb cleared
  adventure-session-5.md               # Session 5: Road to Thornwall, Kael's escort, quarry investigation
  CHANGELOG.md                         # Version history and skill improvements
  LICENSE                              # GNU General Public License v3
  README.md                            # This file
```

## Usage

### As a Cursor Agent Skill

The skill is installed in `.cursor/skills/bx-dungeon-master/`. When you ask the AI to run a B/X game or act as a Dungeon Master, it reads `SKILL.md` and loads reference files on demand during play.

Just say something like:
- *"Use your B/X Dungeon Master skill"*
- *"Roll me up a character"*
- *"Let's play some classic B/X"*

The AI will handle character creation, dungeon generation, combat, treasure, and all the bookkeeping.

## Design Principles

- **Mechanically complete.** Every table, formula, and procedure needed to run a session is present. Nothing is summarized away if it affects play.
- **Aggressively compact.** Flavor text, examples, and redundant prose are stripped. What remains is the skeleton of the rules in the most token-efficient format possible.
- **Progressive disclosure.** The skill entry point (`SKILL.md`) contains core DM procedures. Detailed reference files are loaded only when needed, keeping the active context lean.
- **Old-school faithful.** XP from treasure, not kills. Descending AC with ascending brackets. THAC0. Morale. Reaction rolls. No fudging, no hand-waving, no modern concessions.

## Example Play

Session transcripts from *The Tomb of Valdros the Pale*, featuring a level 3 party (Elf, Thief, Cleric) clearing a barrow tomb outside the village of Harrow's End:

- `adventure-session-1.md` -- First delve. Spiking ghouls behind a door, fighting a carcass crawler, hauling 3,100gp back to the surface.
- `adventure-session-2.md` -- Return trip. Turning undead, looting the sarcophagi, and getting out clean with another 2,500gp.
- `adventure-session-3.md` -- Hiring a retainer, confronting Valdros the Wight, finding a magic sword, two level-ups. 3,660gp.
- `adventure-session-4.md` -- Burning the ghouls, finding the missing woodcutters, clearing the tomb, donating 3,000sp to the village.
- `adventure-session-5.md` -- Gold logistics, hiring Kael's escort, Thornwall bank and shopping, quarry intelligence gathering, arrival at Greystone Quarry.

## License

This project is licensed under the GNU General Public License v3.0. See [LICENSE](LICENSE) for details.
