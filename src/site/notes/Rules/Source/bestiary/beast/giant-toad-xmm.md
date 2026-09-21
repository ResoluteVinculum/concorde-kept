---
{"dg-publish":true,"permalink":"/rules/source/bestiary/beast/giant-toad-xmm/","tags":["ttrpg-cli/compendium/src/5e/xmm","ttrpg-cli/monster/cr/1","ttrpg-cli/monster/environment/coastal","ttrpg-cli/monster/environment/forest","ttrpg-cli/monster/environment/swamp","ttrpg-cli/monster/environment/underdark","ttrpg-cli/monster/size/large","ttrpg-cli/monster/type/beast"],"noteIcon":"","dg-note-properties":{"obsidianUIMode":"preview","cssclasses":["json5e-monster"],"tags":["ttrpg-cli/compendium/src/5e/xmm","ttrpg-cli/monster/cr/1","ttrpg-cli/monster/environment/coastal","ttrpg-cli/monster/environment/forest","ttrpg-cli/monster/environment/swamp","ttrpg-cli/monster/environment/underdark","ttrpg-cli/monster/size/large","ttrpg-cli/monster/type/beast"],"statblock":"inline","statblock-link":"#^statblock","aliases":["Giant Toad"]}}
---

# [Giant Toad](Rules\Source\bestiary\beast/giant-toad-xmm.md)
*Source: Monster Manual (2024) p. 360. Available in the <span title='Systems Reference Document (5.2)'>SRD</span> and the Free Rules (2024)*  

## Animals

Use these stat blocks to represent the creatures they're named for or other similar creatures. For example, the [[Rules/Source/bestiary/beast/panther-xmm\|Panther]] stat block can also represent a mountain lion, while the [[Rules/Source/bestiary/beast/giant-goat-xmm\|Giant Goat]] stat block might represent a buffalo. Any of these stat blocks might also serve as fantastical animals with distinctive names and cosmetic details unique to your D&D adventures.

```statblock
"name": "Giant Toad (XMM)"
"size": "Large"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "11"
"hp": !!int "39"
"hit_dice": "6d10 + 6"
"modifier": !!int "1"
"stats":
  - !!int "15"
  - !!int "13"
  - !!int "13"
  - !!int "2"
  - !!int "10"
  - !!int "3"
"speed": "30 ft., swim 30 ft."
"senses": "[Darkvision](/Rules/Source/senses.md#Darkvision) 60 ft., passive Perception\
  \ 10"
"languages": ""
"cr": "1"
"traits":
  - "desc": "The toad can breathe air and water."
    "name": "Amphibious"
  - "desc": "The toad's [Long Jump](/Rules/Source/variant-rules/long-jump-xphb.md)\
      \ is up to 20 feet and its [High Jump](/Rules/Source/variant-rules/high-jump-xphb.md)\
      \ is up to 10 feet with or without a running start."
    "name": "Standing Leap"
"actions":
  - "desc": "*Melee Attack Roll:* +4, reach 5 ft. *Hit:* 5 (1d6 + 2) Piercing damage\
      \ plus 5 (2d4) Poison damage. If the target is a Medium or smaller creature,\
      \ it has the [Grappled](/Rules/Source/conditions.md#Grappled) condition (escape\
      \ DC 12)."
    "name": "Bite"
  - "desc": "The toad swallows a Medium or smaller target it is grappling. While swallowed,\
      \ the target isn't [Grappled](/Rules/Source/conditions.md#Grappled) but has\
      \ the [Blinded](/Rules/Source/conditions.md#Blinded) and [Restrained](/Rules/Source/conditions.md#Restrained)\
      \ conditions, and it has [Total Cover](/Rules/Source/variant-rules/cover-xphb.md)\
      \ against attacks and other effects outside the toad. In addition, the target\
      \ takes 10 (3d6) Acid damage at the end of each of the toad's turns. The toad\
      \ can have only one target swallowed at a time, and it can't use Bite while\
      \ it has a swallowed target. If the toad dies, a swallowed creature is no longer\
      \ [Restrained](/Rules/Source/conditions.md#Restrained) and can escape from the\
      \ corpse using 5 feet of movement, exiting with the [Prone](/Rules/Source/conditions.md#Prone)\
      \ condition."
    "name": "Swallow"
"source":
  - "XMM"
"image": "/Rules/Source/bestiary/beast/token/giant-toad-xmm.webp"
```{ #statblock}


## Environment

coastal, forest, swamp, underdark