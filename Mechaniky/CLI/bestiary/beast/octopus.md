---
obsidianUIMode: preview
cssclasses:
- json5e-monster
tags:
- ttrpg-cli/compendium/src/5e/mm
- ttrpg-cli/monster/cr/0
- ttrpg-cli/monster/size/small
- ttrpg-cli/monster/type/beast
statblock: inline
statblock-link: "#^statblock"
aliases:
- "Octopus"
---
# [Octopus](Mechaniky\CLI\bestiary\beast/octopus.md)
*Source: Monster Manual p. 333. Available in the <span title='Systems Reference Document (5.1)'>SRD</span> and the Basic Rules (2014)*  

```statblock
"name": "Octopus"
"size": "Small"
"type": "beast"
"alignment": "Unaligned"
"ac": !!int "12"
"hp": !!int "3"
"hit_dice": "1d6"
"modifier": !!int "2"
"stats":
  - !!int "4"
  - !!int "15"
  - !!int "11"
  - !!int "3"
  - !!int "10"
  - !!int "4"
"speed": "5 ft., swim 30 ft."
"skillsaves":
  - "name": "[Perception](/Mechaniky/CLI/Rules/skills.md#Perception)"
    "desc": "+2"
  - "name": "[Stealth](/Mechaniky/CLI/Rules/skills.md#Stealth)"
    "desc": "+4"
"senses": "[darkvision](/Mechaniky/CLI/Rules/senses.md#Darkvision) 30 ft., passive\
  \ Perception 12"
"languages": ""
"cr": "0"
"traits":
  - "desc": "While out of water, the octopus can hold its breath for 30 minutes."
    "name": "Hold Breath"
  - "desc": "The octopus has advantage on Dexterity ([Stealth](/Mechaniky/CLI/Rules/skills.md#Stealth))\
      \ checks made while underwater."
    "name": "Underwater Camouflage"
  - "desc": "The octopus can breathe only underwater."
    "name": "Water Breathing"
"actions":
  - "desc": "*Melee Weapon Attack:* +4 to hit, reach 5 ft., one target. *Hit:* 1 bludgeoning\
      \ damage, and the target is [grappled](/Mechaniky/CLI/Rules/conditions.md#Grappled)\
      \ (escape DC 10). Until this grapple ends, the octopus can't use its tentacles\
      \ on another target."
    "name": "Tentacles"
  - "desc": "A 5-foot-radius cloud of ink extends all around the octopus if it is\
      \ underwater. The area is heavily obscured for 1 minute, although a significant\
      \ current can disperse the ink. After releasing the ink, the octopus can use\
      \ the Dash action as a bonus action."
    "name": "Ink Cloud (Recharges after a Short or Long Rest)"
"source":
  - "MM"
"image": "/Mechaniky/CLI/bestiary/beast/token/octopus.webp"
```
^statblock