---
{"dg-publish":true,"permalink":"/rules/source/bestiary/construct/construct-spirit-stone-xphb/","tags":["ttrpg-cli/compendium/src/5e/xphb","ttrpg-cli/monster/cr/","ttrpg-cli/monster/size/medium","ttrpg-cli/monster/type/construct"],"noteIcon":"","dg-note-properties":{"obsidianUIMode":"preview","cssclasses":["json5e-monster"],"tags":["ttrpg-cli/compendium/src/5e/xphb","ttrpg-cli/monster/cr/","ttrpg-cli/monster/size/medium","ttrpg-cli/monster/type/construct"],"statblock":"inline","statblock-link":"#^statblock","aliases":["Construct Spirit (Stone)"]}}
---

# [Construct Spirit (Stone)](Rules\Source\bestiary\construct/construct-spirit-stone-xphb.md)
*Source: Player's Handbook (2024) p. 324*  

```statblock
"name": "Construct Spirit (Stone) (XPHB)"
"size": "Medium"
"type": "construct"
"alignment": "Neutral"
"ac_class": "13 + the spell's level"
"modifier": !!int "0"
"stats":
  - !!int "18"
  - !!int "10"
  - !!int "18"
  - !!int "14"
  - !!int "11"
  - !!int "5"
"speed": "30 ft."
"damage_resistances": "poison"
"condition_immunities": "[charmed](/Rules/Source/conditions.md#Charmed), [exhaustion](/Rules/Source/conditions.md#Exhaustion),\
  \ [frightened](/Rules/Source/conditions.md#Frightened), [paralyzed](/Rules/Source/conditions.md#Paralyzed),\
  \ [poisoned](/Rules/Source/conditions.md#Poisoned)"
"senses": "[Darkvision](/Rules/Source/senses.md#Darkvision) 60 ft., passive Perception\
  \ 10"
"languages": "Understands the languages you know"
"traits":
  - "desc": "When a creature starts its turn within 10 feet of the spirit, the spirit\
      \ can target it with magical energy if the spirit can see it. *Wisdom Saving\
      \ Throw:* DC equals your spell save DC, the target. *Failure:* Until the start\
      \ of its next turn, the target can't make [Opportunity Attacks](/Rules/Source/actions.md#Opportunity%20Attack),\
      \ and its [Speed](/Rules/Source/variant-rules/speed-xphb.md) is halved."
    "name": "Stony Lethargy"
"actions":
  - "desc": "The spirit makes a number of Slam attacks equal to half this spell's\
      \ level (round down)."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* Bonus equals your spell attack modifier, reach 5\
      \ ft. *Hit:* 1d8 + 4 + the spell's level Bludgeoning damage."
    "name": "Slam"
"source":
  - "XPHB"
"image": "/Rules/Source/bestiary/construct/token/construct-spirit-stone-xphb.webp"
```
^statblock