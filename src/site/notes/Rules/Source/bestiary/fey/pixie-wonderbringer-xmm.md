---
{"dg-publish":true,"permalink":"/rules/source/bestiary/fey/pixie-wonderbringer-xmm/","tags":["ttrpg-cli/compendium/src/5e/xmm","ttrpg-cli/monster/cr/5","ttrpg-cli/monster/environment/feywild","ttrpg-cli/monster/environment/forest","ttrpg-cli/monster/environment/planar","ttrpg-cli/monster/size/tiny","ttrpg-cli/monster/type/fey"],"noteIcon":"","dg-note-properties":{"obsidianUIMode":"preview","cssclasses":["json5e-monster"],"tags":["ttrpg-cli/compendium/src/5e/xmm","ttrpg-cli/monster/cr/5","ttrpg-cli/monster/environment/feywild","ttrpg-cli/monster/environment/forest","ttrpg-cli/monster/environment/planar","ttrpg-cli/monster/size/tiny","ttrpg-cli/monster/type/fey"],"statblock":"inline","statblock-link":"#^statblock","aliases":["Pixie Wonderbringer"]}}
---

# [Pixie Wonderbringer](Rules\Source\bestiary\fey/pixie-wonderbringer-xmm.md)
*Source: Monster Manual (2024) p. 244*  

Energetic entertainers, wonderbringers use their magic in defense of the wilderness when they must.

## Pixies

*Friends of the Forest*

- **Habitat.** Forest, Planar (Feywild)  
- **Treasure.** [[Rules/Source/tables/random-magic-items-arcana\|Arcana]]  

Barely a foot tall, pixies resemble diminutive elves with gossamer wings. They invisibly observe those who enter their wooded homes, revealing themselves to those with friendly intentions. Those who are unfriendly become the targets of pixies' pranks.

```statblock
"name": "Pixie Wonderbringer (XMM)"
"size": "Tiny"
"type": "fey"
"alignment": "Neutral Good"
"ac": !!int "15"
"hp": !!int "60"
"hit_dice": "24d4"
"modifier": !!int "5"
"stats":
  - !!int "2"
  - !!int "20"
  - !!int "10"
  - !!int "11"
  - !!int "14"
  - !!int "18"
"speed": "10 ft., fly 30 ft."
"skillsaves":
  - "name": "[Arcana](/Rules/Source/skills.md#Arcana)"
    "desc": "+3"
  - "name": "[Perception](/Rules/Source/skills.md#Perception)"
    "desc": "+5"
  - "name": "[Stealth](/Rules/Source/skills.md#Stealth)"
    "desc": "+8"
"senses": "passive Perception 15"
"languages": "Common, Elvish, Sylvan"
"cr": "5"
"traits":
  - "desc": "The pixie has [Advantage](/Rules/Source/variant-rules/advantage-xphb.md)\
      \ on saving throws against spells and other magical effects."
    "name": "Magic Resistance"
"actions":
  - "desc": "The pixie makes two Faerie Dust attacks."
    "name": "Multiattack"
  - "desc": "*Melee  or Ranged Attack Roll:* +7, reach 5 ft. or range 60 ft. *Hit:*\
      \ 15 (2d10 + 4) Radiant damage, and the target has the [Charmed](/Rules/Source/conditions.md#Charmed)\
      \ or [Poisoned](/Rules/Source/conditions.md#Poisoned) condition (pixie's choice)\
      \ until the start of the pixie's next turn."
    "name": "Faerie Dust"
  - "desc": "The pixie casts one of the following spells, requiring no Material components\
      \ and using Charisma as the spellcasting ability (spell save DC 15):\n\n**At\
      \ will:** [Dancing Lights](/Rules/Source/spells/dancing-lights-xphb.md), [Druidcraft](/Rules/Source/spells/druidcraft-xphb.md),\
      \ [Invisibility](/Rules/Source/spells/invisibility-xphb.md) (self only)\n\n\
      **1/day each:** [Detect Thoughts](/Rules/Source/spells/detect-thoughts-xphb.md),\
      \ [Fly](/Rules/Source/spells/fly-xphb.md), [Major Image](/Rules/Source/spells/major-image-xphb.md)"
    "name": "Spellcasting"
"bonus_actions":
  - "desc": "The pixie casts [Entangle](/Rules/Source/spells/entangle-xphb.md), [Polymorph](/Rules/Source/spells/polymorph-xphb.md),\
      \ or [Tasha's Hideous Laughter](/Rules/Source/spells/tashas-hideous-laughter-xphb.md),\
      \ requiring no Material components and using the same spellcasting ability as\
      \ Spellcasting.\n"
    "name": "Burst of Wonder (Recharge 5-6)"
"source":
  - "XMM"
"image": "/Rules/Source/bestiary/fey/token/pixie-wonderbringer-xmm.webp"
```{ #statblock}


## Environment

forest, planar, feywild