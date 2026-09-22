---
{"dg-publish":true,"permalink":"/rules/source/bestiary/fiend/spirit-naga-xmm/","tags":["ttrpg-cli/compendium/src/5e/xmm","ttrpg-cli/monster/cr/8","ttrpg-cli/monster/environment/lower","ttrpg-cli/monster/environment/planar","ttrpg-cli/monster/environment/underdark","ttrpg-cli/monster/size/large","ttrpg-cli/monster/type/fiend"],"noteIcon":"","dg-note-properties":{"obsidianUIMode":"preview","cssclasses":["json5e-monster"],"tags":["ttrpg-cli/compendium/src/5e/xmm","ttrpg-cli/monster/cr/8","ttrpg-cli/monster/environment/lower","ttrpg-cli/monster/environment/planar","ttrpg-cli/monster/environment/underdark","ttrpg-cli/monster/size/large","ttrpg-cli/monster/type/fiend"],"statblock":"inline","statblock-link":"#^statblock","aliases":["Spirit Naga"]}}
---

# [Spirit Naga](Rules\Source\bestiary\fiend/spirit-naga-xmm.md)
*Source: Monster Manual (2024) p. 297. Available in the <span title='Systems Reference Document (5.2)'>SRD</span> and the Free Rules (2024)*  

## Spirit Naga

*Spiteful Serpentine Grudge Keeper*

- **Habitat.** Planar (Lower Planes), Underdark  
- **Treasure.** [[Rules/Source/tables/random-magic-items-arcana\|Arcana]]  

Spirit nagas loathe the world and all creatures. Possessing perfect memories, these venomous, cobra-like creatures recall every slight committed against them during their immortal existences. In their dank, joyless lairs, they create vicious plots to avenge themselves against even petty offenses.

Spirit nagas seek to claim what they believe they deserve. Their schemes often involve poisons, vile spells, cursed objects, or magical compulsions, eventually making them wellsprings of diabolical knowledge and evil inspiration. Other villains often seek out spirit nagas as advisers and allies. Roll on or choose a result from the Spirit Naga Grievances table to inspire what motivates a spirit naga's schemes.

**Spirit Naga Grievances**

| dice: 1d6 | The Spirit Naga Believes... |
|-----------|-----------------------------|
| 1 | A character is to blame for its recent failures. |
| 2 | It has been evicted from its rightful home. |
| 3 | Locals have reneged on an age-old bargain. |
| 4 | Other creatures are mocking it. |
| 5 | A rival is spying on it. |
| 6 | Someone's treasure rightfully belongs to it. |{ #spirit-naga-grievances}


```statblock
"name": "Spirit Naga (XMM)"
"size": "Large"
"type": "fiend"
"alignment": "Chaotic Evil"
"ac": !!int "17"
"hp": !!int "135"
"hit_dice": "18d10 + 36"
"modifier": !!int "3"
"stats":
  - !!int "18"
  - !!int "17"
  - !!int "14"
  - !!int "16"
  - !!int "15"
  - !!int "16"
"speed": "40 ft."
"saves":
  - "dexterity": !!int "6"
  - "constitution": !!int "5"
  - "wisdom": !!int "5"
  - "charisma": !!int "6"
"damage_immunities": "poison"
"condition_immunities": "[charmed](/Rules/Source/conditions.md#Charmed), [poisoned](/Rules/Source/conditions.md#Poisoned)"
"senses": "[Darkvision](/Rules/Source/senses.md#Darkvision) 60 ft., passive Perception\
  \ 12"
"languages": "Abyssal, Common"
"cr": "8"
"traits":
  - "desc": "If it dies, the naga returns to life in 1d6 days and regains all its\
      \ [Hit Points](/Rules/Source/variant-rules/hit-points-xphb.md). Only a [Wish](/Rules/Source/spells/wish-xphb.md)\
      \ spell can prevent this trait from functioning."
    "name": "Fiendish Restoration"
"actions":
  - "desc": "The naga makes three attacks, using Bite or Necrotic Ray in any combination."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +7, reach 10 ft. *Hit:* 7 (1d6 + 4) Piercing damage\
      \ plus 14 (4d6) Poison damage."
    "name": "Bite"
  - "desc": "*Ranged Attack Roll:* +6, range 60 ft. *Hit:* 21 (6d6) Necrotic damage."
    "name": "Necrotic Ray"
  - "desc": "The naga casts one of the following spells, requiring no Somatic or Material\
      \ components and using Intelligence as the spellcasting ability (spell save\
      \ DC 14):\n\n**At will:** [Detect Magic](/Rules/Source/spells/detect-magic-xphb.md),\
      \ [Mage Hand](/Rules/Source/spells/mage-hand-xphb.md), [Minor Illusion](/Rules/Source/spells/minor-illusion-xphb.md),\
      \ [Water Breathing](/Rules/Source/spells/water-breathing-xphb.md)\n\n**2/day\
      \ each:** [Detect Thoughts](/Rules/Source/spells/detect-thoughts-xphb.md), [Dimension\
      \ Door](/Rules/Source/spells/dimension-door-xphb.md), [Hold Person](/Rules/Source/spells/hold-person-xphb.md)\
      \ (level 3 version), [Lightning Bolt](/Rules/Source/spells/lightning-bolt-xphb.md)\
      \ (level 4 version)"
    "name": "Spellcasting"
"source":
  - "XMM"
"image": "/Rules/Source/bestiary/fiend/token/spirit-naga-xmm.webp"
```{ #statblock}


## Environment

planar, lower, underdark