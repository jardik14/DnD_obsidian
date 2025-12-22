---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mm
- ttrpg-cli/monster/cr/1-8
- ttrpg-cli/monster/environment/urban
- ttrpg-cli/monster/size/medium
- ttrpg-cli/monster/type/humanoid/any-race
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Cultist"
---
# [Cultist](Mechaniky\CLI\bestiary\humanoid/cultist.md)
*Source: Monster Manual p. 345, Lost Mine of Phandelver. Available in the <span title='Systems Reference Document (5.1)'>SRD</span> and the Basic Rules (2014)*  

Cultists swear allegiance to dark powers such as elemental princes, demon lords, or archdevils. Most conceal their loyalties to avoid being ostracized, imprisoned, or executed for their beliefs. Unlike evil acolytes, cultists often show signs of insanity in their beliefs and practices.

```statblock
"name": "Cultist"
"size": "Medium"
"type": "humanoid"
"subtype": "any race"
"alignment": "Any Non-Good alignment"
"ac": !!int "12"
"ac_class": "[leather armor](/Mechaniky/CLI/items/leather-armor.md)"
"hp": !!int "9"
"hit_dice": "2d8"
"modifier": !!int "1"
"stats":
  - !!int "11"
  - !!int "12"
  - !!int "10"
  - !!int "10"
  - !!int "11"
  - !!int "10"
"speed": "30 ft."
"skillsaves":
  - "name": "[Deception](/Mechaniky/CLI/Rules/skills.md#Deception)"
    "desc": "+2"
  - "name": "[Religion](/Mechaniky/CLI/Rules/skills.md#Religion)"
    "desc": "+2"
"gear":
  - "[scimitar](/Mechaniky/CLI/items/scimitar.md)"
"senses": "passive Perception 10"
"languages": "any one language (usually Common)"
"cr": "1/8"
"traits":
  - "desc": "The cultist has advantage on saving throws against being [charmed](/Mechaniky/CLI/Rules/conditions.md#Charmed)\
      \ or [frightened](/Mechaniky/CLI/Rules/conditions.md#Frightened)."
    "name": "Dark Devotion"
"actions":
  - "desc": "*Melee Weapon Attack:* +3 to hit, reach 5 ft., one creature. *Hit:* 4\
      \ (1d6 + 1) slashing damage."
    "name": "Scimitar"
"source":
  - "MM"
  - "LMoP"
"image": "/Mechaniky/CLI/bestiary/humanoid/token/cultist.webp"
```
^statblock

## Environment

urban