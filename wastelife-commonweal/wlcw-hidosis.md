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

Enchanting is the process of consciously changing one's own torfol planar vectors and utilising the energy from the resulting sping movement to cause a solid-fixed manifestation. Sping here is names after Yorhan Berdei Sping, a pioneer in Hidol sciences who published papers related to things mages and wizards felt for millennia finally categorised into theory. 

The adaptive torfol can be conceptualised as a ball, and rotating that ball is changing its vector's values. Each enchantment has a certain path of points that need to be hit in the torfol, before it can be applied to an object. 

Enchantments are temporary but lingering torfol residue on a non-living object. Some materials hold this residue for longer, make it more potent, or influence its effects in some way. Some materials can hold several residues at once. One can only enchant what's within one's torfol, which for most basic wizards only extends half a metre from their bodies.

Permanent enchantments are extremely hard to make as they need a self-replenishing torfol loop to be baked into the residue. 

## Casting Enchantments

Casting enchantments is separated into movements. 

During each movement, you roll 2d10 and try to get as close to 11 as possible. 

Each movement has a simplicity, which is how far from 11 your roll can be for the movement to pass. Simplicity 4 means rolling between 7 and 15.

You may also roll the enchant type's class proficiency and correct your roll by the value on your proficiency roll, in attempts to get it close enough to 11 to pass. 

If any movements fail, the enchantment fails. Advancements can change this. Once an enchantment is cast, deduct it's cost from your torfol energy pool.

Each enchantment's profile details include what enchantment classes it belongs to, how much torfol energy it uses, and a list of its movements and their simplicities. Enchantments may belong to more than one class, in which case the lower of the proficiencies is used. 

The default amount of maximum torfol energy is 4. This replenishes at a rate of one per day.

The enchantment skill classes follow:

- **Aeroesence**, utilisation of the flexible material.
- **Bindermancy**, Hidol binding.
- **Cinderance**, creation of heat and fire.
- **Rotchemy**, corrosion and decomposition.
- **Magnesis**, light, zaps, and magnesis.
- **Mirageing**, perception-altering effects.
- **Pushcraft**, moving objects and projecting force.
- **Crashmancy**, sound and pressure.
- **Vitescence**, potions and health.

They have a few different types of names:

- Original, the words used by the foundational wizards of Nao Techia.
- Classical, from more modern language circles.
- Work of, attempting to describe the actual domain.

| Original    | Classical   | Work of    |
| ----------- | ----------- | ---------- |
| Aeromancy   | Formation   | Aerourgy   |
| Bindermancy | Ligature    | Desmurgy   |
| Cinderance  | Pyrism      | Pyrurgy    |
| Rotchemy    | Putrescence | Sepsurgy   |
| Magnesis    | Fulguration | Galvanurgy |
| Mirageing   | Phantasm    | Glamourgy  |
| Pushcraft   | Kinesis     | Kinurgy    |
| Crashmancy  | Concussion  | Bronturgy  |
| Vitescence  | Vivication  | Zoeurgy    |


## Enchant Duration

Enchanting is temporary. When the enchantment is used, its effects draw from its lingering torfol's energy. This lingering torfol does not replenish: in fact it slowly deteriorates even without active use.

Enchantments then have two additional properties: uses and duration. For simplicity, they don't affect each other in the game. 

Uses is the number of times the effect of the enchantment can be "used", often accompanied with a clarification on what a use means. Duration is how long the enchantment lingers despite uses. 

Some enchantments are meant to be consumed. These will show how many "portions" the enchantment works for. A single portion must be ingested for the effect to happen to the creature that ingested the portion. Consuming more than one portion does not provide additional benefits. Different effect's portions can work at once, but note that chugging litres of enchanted liquid might cause other physical issues. 

An enchantment ends when it runs out of uses or when the duration is over.

## Designing enchantments

This section covers the probabilities behind casting to help me pick simplicities and movement counts.

### Single movement odds

Rolling 2d10 and landing within the simplicity of 11 has these odds, before any proficiency correction:

|Simplicity|Passing range|Chance|
|---|---|---|
|0|11|10%|
|1|10-12|28%|
|2|9-13|44%|
|3|8-14|58%|
|4|7-15|70%|
|5|6-16|80%|
|6|5-17|88%|
|7|4-18|94%|
|8|3-19|98%|
|9+|any|100%|

### Proficiency

Proficiency lets you shift your roll toward 11, so a proficiency roll effectively increases simplicity. A proficiency die is rolled per movement, and you only need it when the 2d10 roll misses.

| Simplicity | No proficiency | d4  | d6  | d8  | d10 | d12 |
| ---------- | -------------- | --- | --- | --- | --- | --- |
| 1          | 28%            | 63% | 72% | 79% | 83% | 86% |
| 2          | 44%            | 74% | 81% | 86% | 89% | 91% |
| 3          | 58%            | 83% | 88% | 91% | 93% | 94% |
| 4          | 70%            | 90% | 93% | 95% | 96% | 97% |
| 5          | 80%            | 95% | 97% | 98% | 98% | 98% |
| 6          | 88%            | 98% | 99% | 99% | 99% | 99% |

Proficiency matters most at low simplicity and fades as the base window grows. It is how a skilled mage turns a hopeless enchantment into a fair one. For multi-class enchantments, the lower proficiency is the one you use.

Proficiency makes enchantments quite reliable.

### Chaining movements

Chaining movements probabilities are simply multiplied together


# Interface

Interfacing with the hidol describes the process of creating an area in the real world from which Hidol energy can be drawn from freely. Interfacing is then manifesting that hidol energy into matter or energy.

Creating an interface is incredibly difficult for mortals. Manifesting energy from it is even more challenging. Interfacing is a skill essentially reserved for Eternals and Esten, for whom it is trivial.
