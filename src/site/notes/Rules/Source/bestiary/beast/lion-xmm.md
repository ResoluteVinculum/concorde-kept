---
{"dg-publish":true,"permalink":"/rules/source/bestiary/beast/lion-xmm/","tags":["ttrpg-cli/compendium/src/5e/xmm","ttrpg-cli/monster/cr/1","ttrpg-cli/monster/environment/desert","ttrpg-cli/monster/environment/grassland","ttrpg-cli/monster/environment/hill","ttrpg-cli/monster/environment/mountain","ttrpg-cli/monster/size/large","ttrpg-cli/monster/type/beast"],"noteIcon":"","dg-note-properties":{"obsidianUIMode":"preview","cssclasses":["json5e-monster"],"tags":["ttrpg-cli/compendium/src/5e/xmm","ttrpg-cli/monster/cr/1","ttrpg-cli/monster/environment/desert","ttrpg-cli/monster/environment/grassland","ttrpg-cli/monster/environment/hill","ttrpg-cli/monster/environment/mountain","ttrpg-cli/monster/size/large","ttrpg-cli/monster/type/beast"],"statblock":"inline","statblock-link":"#^statblock","aliases":["Lion"]}}
---

# [Lion](Rules\Source\bestiary\beast/lion-xmm.md)
*Source: Monster Manual (2024) p. 364, Player's Handbook (2024) p. 352. Available in the <span title='Systems Reference Document (5.2)'>SRD</span> and the Free Rules (2024)*  

## Animals

Use these stat blocks to represent the creatures they're named for or other similar creatures. For example, the [[Rules/Source/bestiary/beast/panther-xmm\|Panther]] stat block can also represent a mountain lion, while the [[Rules/Source/bestiary/beast/giant-goat-xmm\|Giant Goat]] stat block might represent a buffalo. Any of these stat blocks might also serve as fantastical animals with distinctive names and cosmetic details unique to your D&D adventures.

```statblock
"name": "Lion (XMM)"
"size": "Large"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "12"
"hp": !!int "22"
"hit_dice": "4d10"
"modifier": !!int "2"
"stats":
  - !!int "17"
  - !!int "15"
  - !!int "11"
  - !!int "3"
  - !!int "12"
  - !!int "8"
"speed": "50 ft."
"skillsaves":
  - "name": "[Perception](/Rules/Source/skills.md#Perception)"
    "desc": "+3"
  - "name": "[Stealth](/Rules/Source/skills.md#Stealth)"
    "desc": "+4"
"senses": "[Darkvision](/Rules/Source/senses.md#Darkvision) 60 ft., passive Perception\
  \ 13"
"languages": ""
"cr": "1"
"traits":
  - "desc": "The lion has [Advantage](/Rules/Source/variant-rules/advantage-xphb.md)\
      \ on an attack roll against a creature if at least one of the lion's allies\
      \ is within 5 feet of the creature and the ally doesn't have the [Incapacitated](/Rules/Source/conditions.md#Incapacitated)\
      \ condition."
    "name": "Pack Tactics"
  - "desc": "With a 10-foot running start, the lion can [Long Jump](/Rules/Source/variant-rules/long-jump-xphb.md)\
      \ up to 25 feet."
    "name": "Running Leap"
"actions":
  - "desc": "The lion makes two Rend attacks. It can replace one attack with a use\
      \ of Roar."
    "name": "Multiattack"
  - "desc": "*Melee Attack Roll:* +5, reach 5 ft. *Hit:* 7 (1d8 + 3) Slashing damage."
    "name": "Rend"
  - "desc": "*Wisdom Saving Throw:* DC 11, one creature within 15 feet. *Failure:*\
      \ The target has the [Frightened](/Rules/Source/conditions.md#Frightened) condition\
      \ until the start of the lion's next turn."
    "name": "Roar"
"source":
  - "XMM"
  - "XPHB"
"image": "/Rules/Source/bestiary/beast/token/lion-xmm.webp"
```{ #statblock}


## Environment

desert, grassland, hill, mountain