---
{"dg-publish":true,"permalink":"/rules/source/bestiary/beast/wolf-xmm/","tags":["ttrpg-cli/compendium/src/5e/xmm","ttrpg-cli/monster/cr/1-4","ttrpg-cli/monster/environment/forest","ttrpg-cli/monster/environment/grassland","ttrpg-cli/monster/environment/hill","ttrpg-cli/monster/size/medium","ttrpg-cli/monster/type/beast"],"noteIcon":"","dg-note-properties":{"obsidianUIMode":"preview","cssclasses":["json5e-monster"],"tags":["ttrpg-cli/compendium/src/5e/xmm","ttrpg-cli/monster/cr/1-4","ttrpg-cli/monster/environment/forest","ttrpg-cli/monster/environment/grassland","ttrpg-cli/monster/environment/hill","ttrpg-cli/monster/size/medium","ttrpg-cli/monster/type/beast"],"statblock":"inline","statblock-link":"#^statblock","aliases":["Wolf"]}}
---

# [Wolf](Rules\Source\bestiary\beast/wolf-xmm.md)
*Source: Monster Manual (2024) p. 373, Player's Handbook (2024) p. 359. Available in the <span title='Systems Reference Document (5.2)'>SRD</span> and the Free Rules (2024)*  

## Animals

Use these stat blocks to represent the creatures they're named for or other similar creatures. For example, the [[Rules/Source/bestiary/beast/panther-xmm\|Panther]] stat block can also represent a mountain lion, while the [[Rules/Source/bestiary/beast/giant-goat-xmm\|Giant Goat]] stat block might represent a buffalo. Any of these stat blocks might also serve as fantastical animals with distinctive names and cosmetic details unique to your D&D adventures.

```statblock
"name": "Wolf (XMM)"
"size": "Medium"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "12"
"hp": !!int "11"
"hit_dice": "2d8 + 2"
"modifier": !!int "2"
"stats":
  - !!int "14"
  - !!int "15"
  - !!int "12"
  - !!int "3"
  - !!int "12"
  - !!int "6"
"speed": "40 ft."
"skillsaves":
  - "name": "[Perception](/Rules/Source/skills.md#Perception)"
    "desc": "+5"
  - "name": "[Stealth](/Rules/Source/skills.md#Stealth)"
    "desc": "+4"
"senses": "[Darkvision](/Rules/Source/senses.md#Darkvision) 60 ft., passive Perception\
  \ 15"
"languages": ""
"cr": "1/4"
"traits":
  - "desc": "The wolf has [Advantage](/Rules/Source/variant-rules/advantage-xphb.md)\
      \ on attack rolls against a creature if at least one of the wolf's allies is\
      \ within 5 feet of the creature and the ally doesn't have the [Incapacitated](/Rules/Source/conditions.md#Incapacitated)\
      \ condition."
    "name": "Pack Tactics"
"actions":
  - "desc": "*Melee Attack Roll:* +4, reach 5 ft. *Hit:* 5 (1d6 + 2) Piercing damage.\
      \ If the target is a Medium or smaller creature, it has the [Prone](/Rules/Source/conditions.md#Prone)\
      \ condition."
    "name": "Bite"
"source":
  - "XMM"
  - "XPHB"
"image": "/Rules/Source/bestiary/beast/token/wolf-xmm.webp"
```{ #statblock}


## Environment

forest, grassland, hill