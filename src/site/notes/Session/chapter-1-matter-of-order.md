---
{"dg-publish":true,"permalink":"/session/chapter-1-matter-of-order/","tags":["story/act-1/chapter-1"],"dg-note-properties":{"aliases":["Chapter 1","A Matter of Order"],"tags":["story/act-1/chapter-1"]}}
---

# Hook
The [[Characters/NPC/Eliana Verdon\|Chief Magistrate]] enlists the party to go bring peace to a village that has recently stopped paying their taxes after a series of mill workers have gone missing. [[Story/Setting/Hargen\|Hargen]]

## Framing
- Chief Magistrate - Eliana
	- Chance for the party to prove their worth
	- Matter of keeping the keeping peace and preserving the Duchy
	- A simple civic duty
- [[Characters/NPC/Thomas Verve\|Thomas Verve]] - Thomas
	- Urges caution and diplomacy
	- Gives them a collection of 6-Way [[Rules/Source/items/sending-stones-xdmg\|Sending Stones]]
	- Gives them badges with [[Characters/NPC/Duke Holun Blither\|The Duke]]'s seal
- Custodian - Georgio
	- informs the players that he sent a courier carrying a letter detailing that the party will be arriving to help the village deal with the threat, but it never arrived.
	- Gives the players 3 [[Rules/Source/items/potion-of-healing-xdmg\|Potions of Healing]]
## Threat
There is a mimic infestation in the mill.


## City as 5 Rooms

| Act Title                        | Room                  | Description                                                                                                                                                                             |
| -------------------------------- | --------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [[Session/chapter-1-matter-of-order#Act 1: Arrival\|#Act 1: Arrival]]              | Entrance and Guardian | The players arrive to the village                                                                                                                                                       |
| [[Session/chapter-1-matter-of-order#Act 2 Scrutiny\|#Act 2 Scrutiny]]              | Puzzle/RP             | The players can find clues scattered about the village, rumors and physical                                                                                                             |
| [[Session/chapter-1-matter-of-order#Act 3: Protectors\|#Act 3: Protectors]]           | Trick or Setback      | The town has had enough of your medling.<br>They do not trust you:<br>Three guards tell you to leave the village and will not take "no" for an answer.<br><br>Hard Social - Easy Combat |
| [[Session/chapter-1-matter-of-order#Act 4: Disguised Depository\|#Act 4: Disguised Depository]] | Climax                | The Mimics in the mill                                                                                                                                                                  |
| [[Session/chapter-1-matter-of-order#Act 5: Calling Card\|#Act 5: Calling Card]]         | Reward and Revelation | The players                                                                                                                                                                             |


## Act 1: Arrival
- The Villagers are not paying *enough* of their taxes as the mill has been shut down until the threat is dealt with.
Villagers are afraid of the magistrate, **not** the threat
They assume the party is there to punish them
The party must earn trust (or hide their employer)


## Act 2: Scrutiny
1. Shopkeeper Hannah
	- [[Rules/Source/tables/adventuring-gear-xphb\|Adventuring Gear]]
	- [[Rules/Source/tables/armor-xphb\|Armor]]
	- [[Rules/Source/tables/weapons-xphb\|Weapons]]
	- Perpetually stressed, has a twitchy eye
	- Shares that she used to have a grocery store, but the town has been facing supply issues, so she's had to switch to a general store.
	- `"Welcome to the Hannah's Groc... General Store"`
2. Butcher Karler
	- Big, half-orc, sweetheart. has a `<3 Mom` tattoo
	- The Menu shows an increase in sandwich/meat pie prices via a series of crossed out values
	- Raw/Butchered meat remains untouched
	- Willing to share these troubles
3. Town Drunk Yug
	- A genius when sober, never is, sounds insane, but sneaks valuable insights into conversation
	- Amongst his drunken flirting with everyone, he lets in "there's something *freaky* going at the mill"
4. Mayor Osonia 
	- Resistant to the party's intrusion, but when pressed for details `DC 15 Charisma` will reveal the dire nature of the village's economy. 
		- The Mill has been abandoned, the village is frightened of it
		- Without the mill, the village is making a slow and unwise transition from grains to tobacco.

The players should also be able to find sticky residue on storage containers around town and bite marks on some furniture. When townsfolk are asked about these clues, they pretend like it doesn't exist.
## Act 3: Protectors
The village has enough of your medling. They send three guards to confront you.
> [!quote] Guards
> Agents of the Triskelion or not, you’ve brought eyes we cannot survive. This is our home. You will leave it.

This is a very difficult social encounter `AVG DC 18 Charisma` [[Rules/Source/variant-rules/attitude-xphb\|Attitude]]. `DC 25 Charisma` to increase attitude, but only `DC 16 Charisma` to retain current level

```encounter
name: Protectors
creatures:
  - 2:Tough (XMM)
  - 1:Commoner (XMM)
party: 
```

## Act 4: Disguised Depository
After making it passed the town's self-appointed protectors, you make your way into the mill (two floors)

### First Floor: Workshop
The workshop is dilapidated, looks to be hurriedly abandoned.
> [!important] Details
> There are 3 large worktables, two of which have sticky residue on them, the other has shattered pieces of a chest `DC 12 Investigation` reveals that it has exploded, not imploded.
> A corpse is sitting in front of the chest, hands fused to planks of wood from his chest appears to have been crushed, repeatedly.
> In the "chest" `DC 8 Investigation` is 2 [[Rules/Source/items/potions-of-healing-xdmg\|Potions of Healing]] and a [[Rules/Source/items/baba-yagas-dancing-broom-xdmg\|Baba Yaga's Dancing Broom]]
> Stairs on the West Side of the room lead to the second floor.

### Second Floor: Mill
The players find themselves in what appears to be a completely functional mill.
> [!important] Paraphrase
> You enter the second floor of the mill, everything appears to be functional.
> 
> Simple Circular Room
> North Side has the shaft coming in from outside
> Rest of the room contains various containers (buckets, barrels, chests), mostly dust covered.
> Worktable in the middle, with the `Juvenile Mimic` on the table in the form of a notebook
> `Mimic` is a chest on the other side of the brace near the output

`DC 13 Perception To notice two containers with no dust`
`DC 15 Investigation to find them without touching them`
`DC 12 Investigation to find them, but must be touched`

The players can follow mouse tracks `DC 14 Perception` to a [[Rules/Source/items/hat-of-vermin-xdmg\|Hat of Vermin]]
The players can find a bronze coin that always lands on its edge, 

```encounter
name: Mimics in the Mill
creatures:
  - 1:Mimic
  - 1:Juvenile Mimic (TCE)
party: 
```

## Act 5: Calling Card

- 1 Scroll of [[Rules/Source/spells/jump-xphb\|Jumping]]
- 1 Vial of [[Rules/Source/items/dust-of-disappearance-xdmg\|Dust of Disappearance]]
- 1 [[Rules/Source/items/cloak-of-billowing-xdmg\|Cloak of Billowing]]
- 1 [[Rules/Source/items/dread-helm-xdmg\|Dread Helm]]
- 1 [[Rules/Source/items/sword-of-vengeance-xdmg\|Shortsword of Vengeance]]
- 1 [[Rules/Bespoke/Items/Baba Yaga's Mortar and Pestle\|Baba Yaga's Mortar and Pestle]]
In the midst of the perfectly arranged knight's equipment is knotted bunch of vines, seemingly kept from rotting by a green ooze with a [[Rules/Source/items/sending-stones-xdmg\|Sending Stone]] contained within that emits a single word before shattering "Don't"


#idea Loot points to the "removal" of a previous agent that went against the [[Characters/NPC/Eliana Verdon\|Chief Magistrate]]
