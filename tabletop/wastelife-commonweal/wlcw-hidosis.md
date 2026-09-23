---
title: WLCW Hidosis
description: No description.
---

In Wastelife, there are three ways to interact with the Hidol. 

For spells and enchantments, they all make use of torfol, a sort of magical bubble around every living thing. These torfol have a set of vectors associated with them, as described by planar theory. 

# Spells

Spells are a method of interacting with the hidol by causing a reaction between one or more torfol. This is done by creating a large pressure differential catalysing a movement of the fluid the torfol occupies. The pressure difference is usually achieved by clapping. Torfol for spells are called ingredients. Ingredients can be plants, organs, or small creatures. 

In spellcasting, relevant torfol vectors are called formants. There are 8 primary formants and 4 exotic formats. In theory, there are many more formants that aren't used for common spellcasting. These formats are indexed arbitrarily, and often referred to by their index. The first 8 formants are the primary ones. Each formant has a few axes. Each are loosely associated with some aspect of spell formation. 

| Index | Name                  | Axes            |
| ----- | --------------------- | --------------- |
| F1    | Crombulence           | 3               |
| F2    | Krenbichness          | 5               |
| F3    | Threnic Binding       | 2               |
| F4    | Reduflex Vector       | 4 (+8 not used) |
| F5    | Giyt's Dimension      | 3               |
| F6    | Cord de Quincaillerie | 4               |
| F7    | Cot Drembling Line    | 1               |
| F8    | Morré Herch-ness      | 2               |
| F9    | Sping                 | 1               |
| F10   | Opanctity             | 3               |
| F11   | Redness               | 6               |
| F12   | Leb Lilling           | 2               |


Ingredients have a certain potency in each of these formant axes, often no potency. When ingredients combine in a clap, the difference between their formant-axes values affect spell formation.

To calculate the combined difference between two axes potentcies $A_1$ and $A_2$: $|A_1-A_2|$ if A1 and A2 are the same sign and non-zero, $|A_1+A_2|$ if they are opposing signs and non-zero, and 0 if either $A_1$ or $A_2$ are 0. The "final sign" of the axis is the greatest sign of the two ingredients. You can then lookup what spell corresponds with those axes values. 

Opposing signs cancel, rather than adding potency. 

Ingredient strength is given as an integer number. The combined strength is simply the average of participating ingredient's strengths.

Most mages don't try to research new ingredient combinations themselves, they instead know good existing combinations. 

Clap difficulty is a combination of the combined difference and strength. The exact formula:

$$
\text{DC} = \frac{\text{Sum of all axes' combined difference}}{\text{number of relevant axes}} + \text{combined strength}
$$

To make a clap, roll a D20 + clapping proficiency die to succeed this value.

# Enchanting

Enchanting is the process of consciously changing one's own torfol planar vectors and utilising the energy from the resulting sping movement to cause a solid-fixed manifestation. Sping here is names after Yorhan Berdei Sping, a pioneer in Hidol sciences who published papers related to things mages and wizards felt for milennia finally categorised into theory. 

The adaptive torfol can be conceptualised as a ball, and rotating that ball is changing its vector's values. Each enchantment has a certain path of points that need to be hit in the torfol, before it can be applied to an object. 

Enchantments are temporary but lingering torfol residue on a non-living object. Some materials hold this residue for longer, make it more potent, or influence its effects in some way. Some materials can hold several residues at once. 

Permanent enchantments are extremely hard to make as they need a self-replenishing torfol loop to be baked into the residue. 

Casting enchantments is separated into movements. During each movement, you roll 2d10 and try to get as close to 11 as possible. Each movement has a simplicity, which is how far from 11 your roll can be for the movement to still be valid. You may also roll the enchant type's proficiency skill and correct your roll by the value on your proficiency roll, in attempts to get it close enough to 11 to pass. 

The enchantment skill classes follow:

- **Kinetic**: force and movement. 
- **Thermal**: heat, cold, and fire.
- **Tempering**: improving materials. 
- **Warding**: defence and security. 
- **Vitality**: the body's own processes. 
- **Perception**: what a person perceives, and other detection things.
- **Decay**: erosion and corrosion. 
- **Energy**: Light, lightning, sound
- **Binding**: keeping things together, like locks or projected walls.

# Interface

Interfacing with the hidol describes the process of creating an area in the real world from which Hidol energy can be drawn from freely. Interfacing is then manifesting that hidol energy into matter or energy.

Creating an interface is incredibly difficult for mortals. Manifesting energy from it is even more challenging. Interfacing is a skill essentially reserved for Eternals and Esten.