---
{"dg-publish":true,"permalink":"/rules/source/bestiary/elemental/air-elemental-myrmidon-mpmm/","tags":["ttrpg-cli/compendium/src/5e/mpmm","ttrpg-cli/monster/cr/7","ttrpg-cli/monster/size/medium","ttrpg-cli/monster/type/elemental"],"noteIcon":"","dg-note-properties":{"obsidianUIMode":"preview","cssclasses":["json5e-monster"],"tags":["ttrpg-cli/compendium/src/5e/mpmm","ttrpg-cli/monster/cr/7","ttrpg-cli/monster/size/medium","ttrpg-cli/monster/type/elemental"],"statblock":"inline","statblock-link":"#^statblock","aliases":["Air Elemental Myrmidon"]}}
---

# [Air Elemental Myrmidon](Rules\Source\bestiary\elemental/air-elemental-myrmidon-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 122*  

## Elemental Myrmidons

Elemental myrmidons are Elementals conjured and bound by magic into ritually created suits of plate armor. In this form, they possess no recollection of their former existence as free Elementals. They exist only to follow the commands of their creators.

```statblock
"name": "Air Elemental Myrmidon (MPMM)"
"size": "Medium"
"type": "elemental"
"alignment": "Typically  Neutral"
"ac": !!int "18"
"ac_class": "[plate](/Rules/Source/items/plate-armor-xphb.md)"
"hp": !!int "117"
"hit_dice": "18d8 + 36"
"modifier": !!int "2"
"stats":
  - !!int "18"
  - !!int "14"
  - !!int "14"
  - !!int "9"
  - !!int "10"
  - !!int "10"
"speed": "30 ft., fly 30 ft. (hover)"
"damage_resistances": "lightning; thunder; bludgeoning, piercing, slashing from nonmagical\
  \ attacks"
"damage_immunities": "poison"
"condition_immunities": "[paralyzed](/Rules/Source/conditions.md#Paralyzed), [petrified](/Rules/Source/conditions.md#Petrified),\
  \ [poisoned](/Rules/Source/conditions.md#Poisoned), [prone](/Rules/Source/conditions.md#Prone)"
"gear":
  - "[flail](/Rules/Source/items/flail-xphb.md)"
"senses": "[darkvision](/Rules/Source/senses.md#Darkvision) 60 ft., passive Perception\
  \ 10"
"languages": "Auran, one language of its creator's choice"
"cr": "7"
"actions":
  - "desc": "The myrmidon makes three Flail attacks."
    "name": "Multiattack"
  - "desc": "*Melee Weapon Attack:* +7 to hit, reach 5 ft., one target. *Hit:* 8 (1d8\
      \ + 4) force damage."
    "name": "Flail"
  - "desc": "The myrmidon makes one Flail attack. On a hit, the target takes an extra\
      \ 18 (4d8) lightning damage, and the target must succeed on a DC 13 Constitution\
      \ saving throw or be [stunned](/Rules/Source/conditions.md#Stunned) until the\
      \ end of the myrmidon's next turn."
    "name": "Lightning Strike (Recharge 6)"
"source":
  - "MPMM"
"image": "/Rules/Source/bestiary/elemental/token/air-elemental-myrmidon-mpmm.webp"
```
^statblock