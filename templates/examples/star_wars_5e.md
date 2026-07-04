<!-- EXAMPLE: a filled Setting Layer (game_rules.md, Part II) for a Star Wars
campaign set in the late Clone Wars. This is the QUALITY BAR for Session 0:
real numbers, real costs, reskin tables, custom kits where the setting needs them.
In a real campaign this file is written in Russian; the example is kept in
English as reference infrastructure. Part I (Immutable Core) is omitted here —
it never changes and comes straight from templates/game_rules.md. -->

# Example — Star Wars 5e Setting Layer (Clone Wars era)

D&D 5e SRD as the engine, Star Wars as the skin. Where the SRD has a rule, use it. Where this layer says otherwise, this layer wins.

**Setting anchors:** Clone Wars, late stage — months before Order 66. Gritty, morally complicated: the Republic is fraying, the Jedi are exhausted, something is wrong in the Force.

## 1. Attributes

Standard six (STR/DEX/CON/INT/WIS/CHA), unchanged. WIS is the Force-casting stat for Jedi, CHA for dark-side users. Initiative: DEX.

## 2. Resource systems

- **Force points (FP)** replace spell slots. Padawan pool = 2 + WIS mod. Regain all on long rest, half on short rest. Force save DC = 8 + proficiency + WIS mod.
- **Ammo:** energy cells (pistol 50 shots, rifle 30). Reload = bonus action.
- **Dark Side Points (DSP)** — see section 8.

## 3. Weapons, equipment & damage

Reskin map:

| D&D Concept | Star Wars Equivalent |
|---|---|
| Spell / spell slot | Force power / Force point |
| Long sword (magic) | Lightsaber |
| Crossbow / longbow | Blaster pistol / rifle |
| Plate armor | Beskar / heavy battle armor |
| Healing potion | Bacta patch / stim |
| Holy symbol | Jedi crystal / focus |
| Undead | Dark-side abominations, Sith spirits |

| Weapon | Damage | Properties |
|---|---|---|
| Lightsaber | 1d8 radiant (1d10 versatile) | Finesse, ignores non-magical armor |
| Blaster pistol | 1d8 fire | Range 40/120, ammo (cell, 50) |
| Blaster rifle | 1d10 fire | Range 80/240, two-handed, ammo (cell, 30) |
| Heavy blaster | 2d6 fire | Range 60/180, heavy, two-handed, STR 13 |
| Vibroblade | 1d6 slashing | Finesse, light |
| Thermal detonator | 4d6 fire, 10-ft radius | Thrown 30 ft, DEX save DC 15 half |

**Lightsaber specifics:** cuts through most non-magical armor (ignores its AC bonus on a hit); severs limbs on crits (GM call); ~6 inches of durasteel per round of dedicated cutting. **Deflect Blaster Bolts (reaction):** when hit by a blaster attack, reduce damage by 1d10 + DEX + level; if reduced to 0, spend 1 FP to counter-deflect as an attack. No stun setting — a drawn saber means lethal intent.

## 4. Health & healing

- **Bacta patch:** 1d4+2 HP, action, single-use — 25 cr.
- **Stim:** temp HP = half max for 1 minute, then 1 level of exhaustion — 100 cr.
- **Bacta tank:** full HP + conditions removed, 4-hour soak; Republic medical facilities only.
- **Long rest** = 8 hours in a safe place. In a war zone, all long rests count as short unless explicitly safe.

## 5. Classes / archetypes

Clone troopers, officers, scoundrels: Fighter/Rogue as written, gear reskinned. Force users get a custom kit:

### The Jedi Padawan (custom hybrid class)

- **Hit die:** d10 · **Primary:** WIS (Force) + DEX (saber) · **Saves:** WIS, CHA
- **Armor:** none — **Jedi Unarmored Defense:** AC = 10 + DEX + WIS
- **Force Sensitivity:** advantage on Perception to detect living creatures within 30 ft, through walls; sense Force users further with concentration.
- **Lightsaber Mastery:** DEX for attack/damage; ignores non-magical armor bonus.
- **Force Powers:** knows 3 at level 1.

| Power | Cost | Effect |
|---|---|---|
| Force Sense | free | Sense lifeforms 60 ft, 1 min; +1 FP: advantage on initiative 1 min |
| Force Push | 1 FP | 15-ft cone, STR save or pushed 10 ft + prone. Bonus action |
| Force Pull | 1 FP | Creature: STR save or pulled 15 ft. Object ≤25 lbs: to hand. Bonus action |
| Force Jump | 1 FP | Triple jump distance; no fall damage ≤30 ft this round. Bonus action |
| Force Speed | 1 FP | 1 min: double speed, adv. DEX saves, +2 AC; then no bonus action next turn |
| Telekinesis | 2 FP | Action, conc. ≤1 min: move object ≤50 lbs 30 ft/round or throw (+5, 1d8+WIS); creature: WIS check vs their STR/DEX to move/restrain |
| Mind Trick | 1 FP | WIS save or follow a simple harmless suggestion 1 min; WIS 12+ adv., Force-sensitive immune |
| Saber Throw | 1 FP | Bonus action, range 20/60, 1d8 radiant, returns next turn |
| Force Healing | 1 FP | Action, touch: 1d8 + WIS HP |

## 6. Progression

SRD XP thresholds as written. Level-ups grant class features per Fighter/Rogue tables; Padawan gains +1 known power and +2 FP pool per level (full progression table maintained as the campaign reaches those levels).

## 7. Economy

**Credits** replace gold. For SRD-priced goods: 1 sp ≈ 1 cr. Big-ticket canon prices from Wookieepedia: speeder bike ~500 cr, used light freighter 25,000+ cr — usually requisitioned in wartime, not bought. Full price table with sources lives in `world_bible.md`.

## 8. Setting-specific mechanics — Dark Side

Track **DSP** in `character.md`. Gain: acting from fear/anger/hatred (1), killing the helpless with the Force (2), dark-side powers (varies), major Code violations (1–3, GM call).

- 1–2 DSP: unease, dreams, the Master notices something
- 3–5 DSP: disadvantage on the first Force power each encounter
- 6+ DSP: corruption visible to other Jedi; risk of fall

Lose DSP through meditation, atonement, compassion — never freely.

## 9. Opposition & threat tiers

Reskin SRD stat blocks: B1 battle droid = skeleton (minion, CR 1/4); B2 super battle droid = animated armor (CR 1); commando droid = veteran reskin (CR 3); Sith apprentice = custom, built like a mid-CR spellcaster with saber kit. Threat tiers follow the CLAUDE.md pacing rules on the CR scale directly.

**Skills, Star Wars flavor:** Arcana = Force/Sith lore & holocrons; Religion = Force philosophy & the Code; Nature = xenobiology; History = galactic history; Investigation = forensics & slicing; Sleight of Hand = pickpocketing & lock slicing; Insight + Force Sensitivity = read intentions.
