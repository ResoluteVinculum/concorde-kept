---
{"dg-publish":true,"permalink":"/rules/source/bestiary/humanoid/conjurer-wizard-mpmm/","tags":["ttrpg-cli/compendium/src/5e/mpmm","ttrpg-cli/monster/cr/6","ttrpg-cli/monster/environment/urban","ttrpg-cli/monster/size/medium","ttrpg-cli/monster/type/humanoid"],"noteIcon":"","dg-note-properties":{"obsidianUIMode":"preview","cssclasses":["json5e-monster"],"tags":["ttrpg-cli/compendium/src/5e/mpmm","ttrpg-cli/monster/cr/6","ttrpg-cli/monster/environment/urban","ttrpg-cli/monster/size/medium","ttrpg-cli/monster/type/humanoid"],"statblock":"inline","statblock-link":"#^statblock","aliases":["Conjurer Wizard"]}}
---

# [Conjurer Wizard](Rules\Source\bestiary\humanoid/conjurer-wizard-mpmm.md)
*Source: Mordenkainen Presents: Monsters of the Multiverse p. 260*  

Conjurers summon creatures from other planes of existence and teleport themselves and others in the blink of an eye.

## Wizards

Wizards pursue magical power through the study of arcane texts. Some travel the world searching for esoteric tomes while others train lesser wizards or collaborate with colleagues to create new spells.

```statblock
"name": "Conjurer Wizard (MPMM)"
"size": "Medium"
"type": "humanoid"
"alignment": "Any alignment"
"ac": !!int "12"
"ac_class": "15 with [mage armor](/Rules/Source/spells/mage-armor-xphb.md)"
"hp": !!int "58"
"hit_dice": "13d8"
"modifier": !!int "2"
"stats":
  - !!int "9"
  - !!int "14"
  - !!int "11"
  - !!int "17"
  - !!int "12"
  - !!int "11"
"speed": "30 ft."
"saves":
  - "intelligence": !!int "6"
  - "wisdom": !!int "4"
"skillsaves":
  - "name": "[Arcana](/Rules/Source/skills.md#Arcana)"
    "desc": "+6"
  - "name": "[History](/Rules/Source/skills.md#History)"
    "desc": "+6"
"senses": "passive Perception 11"
"languages": "any four languages"
"cr": "6"
"actions":
  - "desc": "The conjurer makes three Arcane Burst attacks."
    "name": "Multiattack"
  - "desc": "*Melee  or Ranged Spell Attack:* +8 to hit, reach 5 ft. or range 120\
      \ ft., one target. *Hit:* 19 (3d10 + 3) force damage."
    "name": "Arcane Burst"
  - "desc": "The conjurer casts one of the following spells, using Intelligence as\
      \ the spellcasting ability (spell save DC 14):\n\n**At will:** [dancing lights](/Rules/Source/spells/dancing-lights-xphb.md),\
      \ [mage hand](/Rules/Source/spells/mage-hand-xphb.md), [prestidigitation](/Rules/Source/spells/prestidigitation-xphb.md)\n\
      \n**2/day each:** [fireball](/Rules/Source/spells/fireball-xphb.md), [mage armor](/Rules/Source/spells/mage-armor-xphb.md),\
      \ [unseen servant](/Rules/Source/spells/unseen-servant-xphb.md)\n\n**1/day each:**\
      \ [fly](/Rules/Source/spells/fly-xphb.md), [stinking cloud](/Rules/Source/spells/stinking-cloud-xphb.md),\
      \ [web](/Rules/Source/spells/web-xphb.md)"
    "name": "Spellcasting"
"bonus_actions":
  - "desc": "The conjurer teleports, along with any equipment it is wearing or carrying,\
      \ up to 30 feet to an unoccupied space that it can see. If it instead chooses\
      \ a space within range that is occupied by a willing Small or Medium creature,\
      \ they both teleport, swapping places."
    "name": "Benign Transportation (Recharge 4-6)"
  - "desc": "The conjurer magically summons an [air elemental](/Rules/Source/bestiary/elemental/air-elemental-xmm.md),\
      \ an [earth elemental](/Rules/Source/bestiary/elemental/earth-elemental-xmm.md),\
      \ a [fire elemental](/Rules/Source/bestiary/elemental/fire-elemental-xmm.md),\
      \ or a [water elemental](/Rules/Source/bestiary/elemental/water-elemental-xmm.md).\
      \ The elemental appears in an unoccupied space within 60 feet of the conjurer,\
      \ whom it obeys. It takes its turn immediately after the conjurer. It lasts\
      \ for 1 hour, until it or the conjurer dies, or until the conjurer dismisses\
      \ it as a bonus action."
    "name": "Summon Elemental (1/Day)"
"source":
  - "MPMM"
"image": "/Rules/Source/bestiary/humanoid/token/conjurer-wizard-mpmm.webp"
```{ #statblock}


## Environment

urban