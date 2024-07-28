- [Introduction](#introduction)
- [Character](#character)
  - [Attributes](#attributes)
    - [Arcana \[Arc\]](#arcana-arc)
  - [Health \& Exhaustion](#health--exhaustion)
    - [Hit Points (HP)](#hit-points-hp)
    - [Condition](#condition)
      - [Bleeding](#bleeding)
      - [Exhausted](#exhausted)
      - [Poisoned](#poisoned)
    - [Scars](#scars)
- [Magic](#magic)
  - [Spell Intensity (SI)](#spell-intensity-si)
  - [Magic Stamina](#magic-stamina)
  - [Spell-Backfire](#spell-backfire)
  - [Concentration Spells](#concentration-spells)
  - [Magic Negation](#magic-negation)
  - [Protection From Magic](#protection-from-magic)
  - [Testing Magic](#testing-magic)
  - [Magic Things](#magic-things)
    - [Abyssalite](#abyssalite)
    - [Amberite](#amberite)
    - [Ambersteel](#ambersteel)
    - [Runes](#runes)
    - [Magic Scrolls](#magic-scrolls)
- [Assets](#assets)
  - [Weapon Properties](#weapon-properties)
- [Appendix](#appendix)
  - [Character Creation](#character-creation)
    - [Determine Abilities](#determine-abilities)
      - [Choosing Attributes](#choosing-attributes)
        - [Manual Attribute Assignment](#manual-attribute-assignment)
        - [Semi-Random Attribute Assignment](#semi-random-attribute-assignment)
      - [Choosing Skills](#choosing-skills)
    - [Determine Magic Stamina](#determine-magic-stamina)
  - [List of Assets](#list-of-assets)
    - [Armor](#armor)
      - [Armor Properties](#armor-properties)
    - [Shield Types](#shield-types)
        - [Buckler](#buckler)
        - [Round Shield](#round-shield)
        - [Heater Shield](#heater-shield)
        - [Kite Shield](#kite-shield)
    - [List of General Assets](#list-of-general-assets)
    - [Weapon Types](#weapon-types)
      - [Dagger (Agi/Awar)](#dagger-agiawar)
      - [Light Blade (Agi/Str)](#light-blade-agistr)
      - [Long Blade (Agi/Str)](#long-blade-agistr)
      - [Great Blade (Str/Tough)](#great-blade-strtough)
      - [Axe (Str/Str)](#axe-strstr)
      - [Great Axe (Str/Str)](#great-axe-strstr)
      - [Spear (Agi/Str)](#spear-agistr)
      - [Lance (Awar/Str)](#lance-awarstr)
      - [Polearm (Str/Tough)](#polearm-strtough)
      - [Club (Str/Str)](#club-strstr)
      - [Small Crusher (Str/Str)](#small-crusher-strstr)
      - [Large Crusher (Str/Tough)](#large-crusher-strtough)
      - [Short-Bow (Awar/Awar)](#short-bow-awarawar)
      - [Longbow (Awar/Str)](#longbow-awarstr)
      - [War-Bow (Str/Tough)](#war-bow-strtough)
      - [Crossbow (Awar/Awar)](#crossbow-awarawar)
      - [Firearm (Awar/Awar)](#firearm-awarawar)
  - [Lists of Skills](#lists-of-skills)
    - [Physical Skills](#physical-skills)
      - [Rune-Using (Agi/Wit)](#rune-using-agiwit)
      - [Sailing (Awar/Wit)](#sailing-awarwit)
    - [Knowledge Skills](#knowledge-skills)
      - [Heraldry (Awar/Wit)](#heraldry-awarwit)
      - [Magic School \< School \> (\< Attribute \>)](#magic-school--school---attribute-)
    - [Craftsmanship Skills](#craftsmanship-skills)
      - [Armor Smithing (Str/Wit)](#armor-smithing-strwit)
      - [Ambersmithing (Str/Wit)](#ambersmithing-strwit)
      - [Alchemy (Arc/Wit)](#alchemy-arcwit)
      - [Brewing (Wit/Wit)](#brewing-witwit)
      - [Blacksmithing (Agi/Str)](#blacksmithing-agistr)
      - [Bow-Making (Agi/Awar)](#bow-making-agiawar)
      - [Carpentry (Agi/Str)](#carpentry-agistr)
      - [Clothesmaking (Agi/Wit)](#clothesmaking-agiwit)
      - [Engineering (Agi/Wit)](#engineering-agiwit)
      - [Fletching (Agi/Awar)](#fletching-agiawar)
      - [Glass-Blowing (Agi/Agi)](#glass-blowing-agiagi)
      - [Goldsmithing (Agi/Agi)](#goldsmithing-agiagi)
      - [Leatherworking (Agi/Wit)](#leatherworking-agiwit)
      - [Masonry (Str/Tough)](#masonry-strtough)
      - [Rune Carving (Arc/Wit)](#rune-carving-arcwit)
      - [Shield-Making (Str/Wit)](#shield-making-strwit)
      - [Tanning/Skinning (Agi/Tough)](#tanningskinning-agitough)
      - [Weapon Smithing (Str/Wit)](#weapon-smithing-strwit)
      - [Woodcarving (Agi/Agi)](#woodcarving-agiagi)
  - [List of Magic Schools](#list-of-magic-schools)
    - [Alteration (Arc/Wit)](#alteration-arcwit)
    - [Cryomancy (Arc/Arc)](#cryomancy-arcarc)
    - [Electromancy (Agi/Arc)](#electromancy-agiarc)
    - [Illusion (Arc/Awar)](#illusion-arcawar)
    - [Psionics (Arc/Wit)](#psionics-arcwit)
    - [Pyromancy (Arc/Arc)](#pyromancy-arcarc)
    - [Restoration (Arc/Awar)](#restoration-arcawar)
    - [Soul-Binding (Arc/Tough)](#soul-binding-arctough)
    - [Telekinesis (Arc/Agi)](#telekinesis-arcagi)
    - [Telepathy (Arc/Wit)](#telepathy-arcwit)
  - [List of Injuries](#list-of-injuries)
  - [List of Illnesses](#list-of-illnesses)

Version 6 (Playtest)

A role-playing game by Nicolas H.

# Introduction
This is the module containing the rules enabling play in a medieval fantasy game world, which includes supernatural monsters and magic. As such, only the differences and additions to the core rules are included in this document. 

This module is best suited for a low to medium fantasy setting. Adapting it to high or heroic fantasy will require extensive additions to the lists of **skills** and **expertises**. 

More details about the module:
* Magic is a **powerful** tool, but comes with great risk, with a chance for a spell to fail and back-fire. The chance of failure is manageable, however. 
  * Magic stamina is a new resource, that mages have to manage. 

# Character
New in this module, is the attribute [arcana](#arcana-arc), which governs a character's capacity for magic. 

## Attributes
Supplements to the [core attributes](./core-rules.md#attributes). 

### Arcana [Arc]
Governs a character's ability to control and sense magic flow, thus casting magic spells or detecting lingering magic. 

This is the only attribute that can have a level of 0. Magical ability is innate and cannot be learned. If a character doesn't have a level of at least 1 in this attribute, they will be unable to advance it, at all. A non-mage will remain a non-mage (usually). 

## Health & Exhaustion
Supplements to specific health and exhaustion. 

### Hit Points (HP)
[Restoration magic](#restoration-arcawar) can restore all currently missing **HP** of a character, without the need for medical supplies. 

### Condition
Supplements to specific **conditions**. 

#### Bleeding
[Restoration magic](#restoration-arcawar) can remove one or more points of **bleeding** at a time. 

#### Exhausted
An **exhausted** mage can no longer attempt to cast any magic. 

#### Poisoned
This **condition** can also be removed with [restoration magic](#restoration-arcawar).

### Scars
Scars may be removed through successful application of [alteration](#alteration-arcwit) magic. 

# Magic
For this supplement, magic is assumed to be a mostly invisible force that runs all throughout, like a magnetosphere. Perhaps it could be called the *arcanosphere*. Individuals gifted with a sensitivity to this force may learn to manipulate and "shape" it. Thus, magical ability is intuitive. Those born without the gift, cannot learn magic. Of course, you may want to relax this rule, if you prefer anyone should have the chance to learn magic. 

Only a character with [arcana](#arcana-arc) can cast intuitive magic. What kind of magic, depends on the [magic schools](#list-of-magic-schools) the character knows. There are offensive, defensive and manipulative [schools of magic](#list-of-magic-schools). 

There may also be magic artifacts that can either cause magical effects on their own, or through character interaction. With such artifacts, it may be possible for non-mages to cast magic. For that, see [runes](#runes) and [scrolls](#magic-scrolls). 

A *magic spell* is the intended effect of using a [magic school's](#magic-school--school---attribute-) [expertise](./core-rules.md#expertise). This is also referred to as *casting magic*, *casting a spell* or other similar wordings. In mechanical terms, every [expertise](./core-rules.md#expertise) noted on a [school of magic](#list-of-magic-schools) is a *magic spell*.

A mage can fail their [test](./core-rules.md#tests) and thus suffer a [spell-backfire](#spell-backfire), which usually results in negative effects for the caster, instead of their intended target. 

[Spell intensity](#spell-intensity-si) adjusts the strength of a magic spell, as well as its cost in [magic stamina](#magic-stamina). 

## Spell Intensity (SI)
**Spell intensity** (shorthand **SI**) is the strength at which a magic spell is being cast. A higher number causes stronger and further reaching effects, at greater [magic stamina](#magic-stamina) cost. A spell's maximum intensity is dictated by the level in the corresponding [magic school skill](#magic-school--school---attribute).

For every point of a spell's chosen **spell intensity**, **1 D4** must be rolled. The sum of these rolls is the resulting [magic stamina](#magic-stamina) cost.

> For a spell at a chosen SI of 3, **3 D4** must be rolled. The sum of these rolls, which is at least 3 and at most could be 9, is the **magic stamina** to deduct after the spell's **test** is made. 

## Magic Stamina
Magic takes a toll on the caster's body, as it takes great mental effort to properly cast magic. **Magic stamina** represents a mage's capacity for casting magic without risk to themselves. It is a replenishable resource that is used up faster with [stronger spells](#spell-intensity-si). 

Mechanically speaking, every mage has two values to track: their **maximum magic stamina** and their **current magic stamina**. 
* The **maximum magic stamina** of a mage is derived from the (**sum** of their [arcana](#arcana-arc) attribute plus the **raw levels** of all their known [magic school skills](#magic-school--school---attribute-) + 4) * 2. 
* The **current magic stamina** can not be less than 0 or more than their **maximum magic stamina**. Every time a mage casts a spell, they incur a **magic stamina** cost, based on the chosen [spell intensity](#spell-intensity-si), which is deducted from this number. 

> If a mage has an **arcana** of 3 and has the **magic school skills** **pyromancy** at level 3, **cryomancy** at level 2 and **illusion** at level 1, that means they have (4 + 3 + 3 + 2 + 1) * 2 = 26 **maximum magic stamina**. 

Once spent, **magic stamina** can only be regained through **active rest or meditation**. For every **half hour** spent in *active rest or meditation*, a mage regains **1 D4** **magic stamina**. Active rest or meditation implies not engaging in any physical or mental strains. If in doubt - if you have to do a test for it, it's probably a strain. 

Reaching negative **magic stamina** while casting a spell, results in an automatic [spell-backfire](#spell-backfire)! 

## Spell-Backfire
A **spell-backfire** causes a spell to affect the caster, instead of their intended target. The mage suffers the negative effects of the spell. In case of an [aoe](./core-rules.md#area-of-effect-aoe) attack spell, anyone or anything nearby the mage, in range, is also affected. Additionally, the mage suffers one point of [exhaustion](./core-rules.md#exhaustion). 

It is possible for another nearby mage to prevent the **spell-backfire**, if they [negate the spell](#magic-negation) as a **reaction**. This also applies even if the spell wouldn't affect them. If the other mage's attempt to negate the spell *also* **backfires**, then both of the mages suffer the effect at one greater [intensity](#spell-intensity-si) level. 

A **spell-backfire** occurs in the following two cases: 
1. The [magic school skill test](#testing-magic) is a **complete failure**. 
2. The spell costs more [magic stamina](#magic-stamina), than the mage has available. 

> A mage has 3 **magic stamina** left, casts a spell at **SI** 1 and rolls a cost of 3 **magic stamina**. They reach 0 **magic stamina**, but do **not** suffer a **spell-backfire**. 

> Another example. This time, the mage has only 2 **magic stamina** left and rolls a cost of 3. This would result in them reaching negative **magic stamina** (= -1) and thus **does** cause a **spell-backfire**! Note, that the current magic stamina cannot be negative and instead is simply set to "0". 

## Concentration Spells
Some magic can be upheld for as long as the casting mage *concentrates* on their spell. Such spells will be marked with **"Concentration"**. The effects of a concentration spell last for as long as the mage *chooses* or *manages* to keep their concentration. They need only test for the spell only *once*, when they first cast it. 

A mage can only upkeep **one** concentration spell at a time. 

Concentration can be broken! Concentration is automatically broken, if the mage is incapacitated, for example by having been knocked unconscious. Otherwise, whenever the mage is *forced* to roll a [test](./core-rules.md#tests), they must **also** succeed another test of their concentration spell's magic school, at the same **Ob** as the test they were just forced to roll. 

## Magic Negation
It is possible to negate a magical attack entirely, by using the same **school of magic** **skill** and achieving more positives, than the attacker. The defender has to perform a [test](#testing-magic) of the same magic school, at the **Ob** equal to the number of **positives + 1** the attacker achieved. The defender does not get to use a [expertise](./core-rules.md#expertise) of the magic school in question. This is a purely defensive action, which benefits everyone who might be hit with the spell of the attacker, as no one will be hit, if the defense is successful. 

If the defense fails, the full effect is applied. If the defense attempt causes a [spell-backfire](#spell-backfire) on the defender, they suffer the attacker's spell at one greater [intensity](#spell-intensity-si) level. 

**Magic negation** can also be used to prevent another mage's [spell-backfire](#spell-backfire).

## Protection From Magic
Armor made from [Ambersteel](#ambersteel) can reduce the damage suffered through magical sources and reduce the [spell intensity](#spell-intensity-si) of non-damaging spells. 

The [quality](./core-rules.md#crafting) of an armor or shield determines how much it protects the wearer. See [ambersmithing](#ambersmithing-strwit) for the specific numbers. 

Damage from magical sources is reduced by the quality level + a number of dice. Non-damaging spells have their [spell intensity](#spell-intensity-si) reduced by *only* the quality level. 

## Testing Magic
[Testing](./core-rules.md#tests) a [magic school skill](#magic-school--school---attribute-), in order to cast a *magic spell*, works as follows:
1. The mage determines the [spell intensity](#spell-intensity-si) they're going to use. Their level in the corresponding [magic school skill](#magic-school--school---attribute-) determines the maximum [spell intensity](#spell-intensity-si) they can pick. 
  1. Note that any spell **must** be cast with a [spell intensity](#spell-intensity-si) of *at least* 1. This includes **learning skills**. 
2. The [magic stamina](#magic-stamina) cost is determined. Roll **1 D4** for every point of the chosen [spell intensity](#spell-intensity-si). 
  1. If more magic stamina is used up, than the mage has left available, they suffer a [spell-backfire](#spell-backfire).
  2. The [magic stamina](#magic-stamina) is reduced by the rolled sum. This happens regardless of a [spell-backfire](#spell-backfire).
3. Proceed only if there was no [spell-backfire](#spell-backfire).
4. Determine the test's **Ob**. Some spells require an [opposed test](./core-rules.md#opposed-test), while others impose a fixed **Ob** and yet others have a dynamic **Ob**, based on some formula. 
5. The dice for the test are rolled. 
  1. If the test is a **complete success**, the spell is cast as intended. 
  2. If the test is a **partial success/failure**, the spell fizzles and nothing happens.
  3. If the test is a **complete failure**, the spell [back-fires](#spell-backfire). 

> A mage wants to cast an [illusion](#illusion-arcawar) spell, at SI 2. Their level in the corresponding magic school skill is 4 and they have 4 magic stamina left. 
>
> They roll **2 D4**, yielding them a 3 and a 2. The sum (5) is one point more magic stamina, than the mage had left. They suffer a spell-backfire and their intended target is left unaffected!

> A mage wants to cast an [illusion](#illusion-arcawar) spell, at SI 2. Their level in the corresponding magic school skill is 4 and they have 4 magic stamina left. 
>
> They roll **2 D4**, yielding them a 1 and a 2. The sum (3) is within their available magic stamina (which is now reduced to 1). 
>
> Now, they determine their **Ob** to be 2. They roll their 4 available D6, but achieve only 1 **positive**. Their spell fizzles and fails without any effect! 

## Magic Things
No fantasy world would be complete without materials with uses for the supernatural or artifacts of immense power. This section introduces the basics of these things. 

Aside from the materials listed below, you are of course free to invent more as desired. 

### Abyssalite
**Abyssalite** is a hard and brittle mineral, that has the ability to *amplify the flow of magic*. It can only be acquired from the depths of the earth and is fairly rare. 

Its surface is unnaturally smooth and covered in a fine, iridescent shine. Underneath the smooth surface, one searches for depth and color in vain. It is as though the void itself is being contained by that iridescent shell. However, the more magic flows through it, the stronger its shell shines. This means that when any magically gifted creature touches **Abyssalite**, it shines stronger. 

**Abyssalite** is a hard and brittle mineral, prone to shattering if too much force is applied. This makes it difficult to shape. It is also fairly heavy, which makes it difficult to carry long. 

A fist-sized **Abyssalite** chunk has a [bulk](./core-rules.md#carrying-capacity) of 2 and grants one greater level in the respective school of magic, without costing any extra [magic stamina](#magic-stamina). In order to use the **Abyssalite**, the caster **must** be touching it. 

### Amberite
As magic is amplified by [Abyssalite](#abyssalite), its antithesis is called **Amberite**, a metal which dulls the effects of magic and slows any magic flow nearby it. The material is also known to affect magic creatures and can cause great pain in magic-users. 

Weapons made from **Amberite** are quite popular with witch and monster hunters alike, although fairly hard to come by, due to the difficulty in **Amberite** processing. 

**Amberite** is a crystalline material, that can be molten down and shaped, like iron. It glows weakly and translucently, in the fiery orange of the name-sharing amber stone. Near the edges, the glow fades to a dull reflection, like cooling molten lava. 

It only occurs naturally in a few select places in the world, where the ground offers the right conditions. **Amberite** grows over time, in the right environment. It can take several decades for a finger-sized crystal to grow to the size of an adult man's forearm. Attempts to cultivate it are met with extreme difficulty. The right conditions for it to thrive are highly dependent on the soil's components, the influence of the *arcanosphere* and proximity to volcanic activity. Due to the slow rate at which it grows, an **Amberite** farmer may not realize the lack of growth until well into a decade later. 

Prolonged exposure to **Amberite** can cause severe ill-effects with nausea and migranes being common symptoms. 

A fist-sized **Amberite** chunk is fairly heavy, with a [bulk](./core-rules.md#carrying-capacity) of 3. 

### Ambersteel
**Ambersteel** is a strictly anti-magic material. It should enjoy great attention in any fantasy world, where magic is a real and recognizable force. Magic is powerful and fearsome and thus, if not under control, can threaten to cause great pain and destruction. **Ambersteel** dampens that power and puts shackles on it. 

[Amberite](#amberite) can be processed into **Ambersteel**, which makes it a hard and flexible metal. The raw material heats slowly and must be heated over the course of several days and nights, without interruption. When it finally reaches the right temperature, it will glow white, with a purple sheen. At that point, it can be hammered into shape. Constant re-heating ensures it stays at the right temperature and a final quenching in oil mixed with powdered [Abyssalite](#abyssalite) ensures it retains its flexibility. If processed outside the optimal temperature, the material quickly grows brittle and will shatter if any stress is put on it. The skill to use is [ambersmithing](#ambersmithing-strwit). 

Due to the length of the process and the difficulty in keeping the right temperature, smiths capable of creating **Ambersteel** are rare. 

**Ambersteel** is also a fairly heavy material, albeit slightly lighter than [Amberite](#amberite). A fist-sized chunk has a [bulk](./core-rules.md#carrying-capacity) of 2. Weapons, shields and armor made from this material are +1 [bulkier](./core-rules.md#carrying-capacity). 

### Runes
Shards of [Abyssalite](#abyssalite) can have **runes** carved into them, which allow magic to flow through the **runes**. This renders **runes** extremely powerful artifacts, as they can allow for near limitless magic-use, even in the hands of a non-mage. 

To activate such a **rune**, is a difficult skill to learn, however. Even if no innate magical ability is required, an understanding of the flow of magic is. The **rune** must be touched in the right spots, at the right intervals, to activate successfully. Mistakes in this procedure can have disastrous results. 

What's more, it takes great skill to carve the right **runes**, as each **rune's** shape and complexity depends in part on the size and shape of the [Abyssalite](#abyssalite) shard. The only way to get it right, is to *feel* the way the **rune** must be shaped. Alternatively, the shard can be adjusted to be of equivalent size and shape as another **rune**, but this requires considerable effort, as [Abyssalite](#abyssalite) is a brittle material, prone to shattering if too much force is applied. Thus, it must be carefully filed down to size. This would double the time it takes to [craft](#rune-carving-arcwit) the **rune**.

Due to how **runes** are always magically charged, they cannot be in the vicinity of any other **runes**. This works a bit like how magnets with the same polarity repulse each other, but a lot more dangerous. This condition applies regardless of the type of magic each of the **runes** hold. 

If two **runes** are brought to a distance of 20m/60' or less to each other, they begin to glow, hum and rumble, as if to warn their bearers. Should they be brought to a distance of 15m/45' or less to each other, they both discharge the magic they hold and repulse each other. This means anyone immediately nearby suffers the [spell-backfire](#spell-backfire) of the respective **rune**, in addition to suffering **3D6 Crushing** damage. The **runes** are flung away from each other far enough to be at least 21m/63' apart. *Also*, the **runes** may be **destroyed** in the process. There is a 1 in 3 chance of this occurring. Roll 1D6 for each of the **runes**. If the result is a 1 or 2, the **rune** is **destroyed**! 

It may be possible to circumvent this repulsion behavior by placing the **runes** in a container made of [Ambersteel](#ambersteel). This requires the container to be of a [quality](./core-rules.md#crafting) level equal to the highest of the **runes'** [spell intensity](#spell-intensity-si).

In order to craft a **rune**:
* A **rune** can only be made to cast one type of magic. So the carver has to pick one of the [magic schools](#list-of-magic-schools). 
* The maximum **level** at which a **rune** can be created, depends on the carver's skill. The **level** of the **rune** dictates the level of the respective magic it will cast at. 
* The carver has to succeed a [rune carving](#rune-carving-arcwit) skill test. 
* Then, the **rune** must be "primed" by a mage. This requires a **complete success** of a test of the same [school of magic](#list-of-magic-schools) as the **rune** holds, with **Ob** equal to the spell's [intensity level](#spell-intensity-si). 
* If any of the tests are not a **complete success**, the **rune** is botched and the material cannot be used for another attempt. There is no room for mistakes. 

In order to invoke a **rune**:
* A **complete success** of a [rune-using](#rune-using-agiwit) skill test will invoke the spell of the **rune** as expected.
* A **partial success** or **complete failure** results in a [spell-backfire](#spell-backfire). 

### Magic Scrolls
**Magic scrolls** allow a single, specific spell to be cast by both mages and non-mages, at no cost of [magic stamina](#magic-stamina). Once used, the **magic scroll** burns up from the flow of magic and cannot be used again (even if the bearer material is fire-proof). Thus, these are single-use tools. 

Due to how **magic scrolls** are always magically charged, they cannot be in the vicinity of any other **magic scrolls**. This works a bit like how magnets with the same polarity repulse each other, but a lot more dangerous. This condition applies *only* to **magic scrolls** of **same the type of magic**. 

If two **magic scrolls** **of the same type** are brought to a distance of 20m/60' or less to each other, they begin to glow, hum and rumble, as if to warn their bearers. Should they be brought to a distance of 15m/45' or less to each other, they both discharge the magic they hold and repulse each other. This means anyone immediately nearby suffers the [spell-backfire](#spell-backfire) of the respective **magic scroll**, in addition to suffering **3D6 Crushing** damage. The **magic scrolls** are destroyed in the process! 

It may be possible to circumvent this repulsion behavior by placing the **magic scrolls** in a container made of [Ambersteel](#ambersteel). This requires the container to be of a [quality](./core-rules.md#crafting) level equal to the highest of the **magic scrolls'** [spell intensity](#spell-intensity-si).

In order to create a **magic scroll**:
* Powdered [Abyssalite](#abyssalite) must be painted onto the parchment, paper or other such material, in a shape specific to the magic spell the **magic scroll** will be able to cast. 
  * This requires a **complete success** of an [artistry](./core-rules.md#artistry-agiawar) test, at **Ob** equal to the spell's [intensity level](#spell-intensity-si). 
* Then, the **magic scroll** must be "primed" by a mage. This requires a **complete success** of a test of the same [school of magic](#list-of-magic-schools) as the **magic scroll** holds, with **Ob** equal to the spell's [intensity level](#spell-intensity-si). 
* If any of the tests are not a **complete success**, the **magic scroll** is botched and the material cannot be used for another attempt. There is no room for mistakes. 

In order to invoke a **magic scroll**:
* One must unfurl and hold it plainly in the direction the spell is to be cast, then trace the painted symbol on the **magic scroll** to "agitate" the primed magic. 
* It costs no [magic stamina](#magic-stamina), but the **magic scroll** is immediately destroyed upon use. It burns up magically (even if the material itself is fire-proof). 

# Assets

## Weapon Properties
Weapon type assets can have the following **properties**:
* **Ambersteel-Lined**: Bonus damage against mages and magical creatures: **+1** for every quality level. **+1D4** for every two **quality levels**, starting at level 1.
* **Ambersteel-Plated**: Bonus damage against mages and magical creatures: **+1** for every quality level. **+1D6** for every two **quality levels**, starting at level 1.
* **Ambersteel-Forged**: Bonus damage against mages and magical creatures: **+2** for every quality level. **+1D8** for every two **quality levels**, starting at level 1.

# Appendix
The appendix contains important and less important lists, for reference only when needed. 

## Character Creation
Character creation is now supplemented by the step to determine [magic stamina](#magic-stamina), which follows determining the **exhaustion threshold**. 

The new procedure of creating a character consists of the following steps:
1. [Determine life path](#determine-life-path). 
2. [Determine species, sex & appearance](#species-sex--appearance).
3. [Determine name](#determine-name).
4. [Determine abilities](#determine-abilities).
6. [Determine **carrying capacity** and **assets**](#determine-assets).
7. [Determine **Max HP** and **Injury Maximum**](#determine-max-hp--injury-maximum)
8. [Determine exhaustion threshold](#determine-exhaustion-threshold).
9. [Determine magic stamina](#determine-magic-stamina).

### Determine Abilities
Supplements to abilities in character creation. 

#### Choosing Attributes
There are two methods for determining your character's attributes: manual and semi-random. 

You'll have to decide on whether your character will be a mage or not. Mages have the new, 6th attribute to spend points on, so this decision can affect your character's initial overall competence. 

Please keep in mind the values here are representative for an ordinary human about to enter an adventuring life. Other species may have modifiers on their attributes, making them better or worse in some of them. But that depends on the world your **GM** is running. 

This section replaces its core rule counter-part. 

##### Manual Attribute Assignment
* You can spend **9 points** on your attributes. 
* All attributes **except arcana** start at level `1`. Arcana starts at `0`. 
* Your attribute-total cannot be greater than **14**.
* No attribute may have a level less than `1` (except **arcana**) nor higher than `4` (including **arcana**).
* Only one attribute may have a level of `4`. 

##### Semi-Random Attribute Assignment
1. Decide if you want to play a mage.
   1. As a mage, roll **6 D4** and **include** **arcana** in the following steps. 
   2. As a non-mage, roll **5 D4** and **exclude** **arcana** in the following steps. 
2. Row up your dice to form a line, then read them from one end to the other and note each value. The order in which they are written down, is the order in which they'll be applied to the attributes. 
3. If there is more than one `4`, start lowering their value by one, starting from the left or the right, until there is only one `4` left. 
4. Count up the total of your values. 
   1. Subtract your total from **14**.
   2. If the number is negative, that's the number of levels you'll have to go down. <br>
   If the number is positive, that's the number of levels you'll have to go up. 
5. Starting from the left or right, start adjusting each value.
   1. If your levels have to go down, subtract one from each value. **But** skip `1`s. 
   2. If your levels have to go up, add one to each value. **But** skip `4`s. 
6. Repeat from the step of counting up your total and adjusting as necessary, until no more adjustments are necessary. 
7. Lastly, apply the adjusted values to your attributes. 

#### Choosing Skills
If playing a **mage**, keep in mind you need to have at least level 1 in a [magic school skill](#magic-school--school---attribute) to be able to cast magic. You are also advised to have your strongest magic be at least level 3 or 4, to be able to reliably use it. 

### Determine Magic Stamina
Determine your character's **maximum magic stamina**, by referring to the [magic stamina](#magic-stamina) section. 

You'll need to track **current magic stamina** separately. To start with, set your current to your maximum **magic stamina**. 

## List of Assets
The following list does not and cannot aim to be a complete listing of all possible assets in game. Adding new assets as necessary will have to be done by the **GM**. 

### Armor

#### Armor Properties
Armor can have the following **properties**:
* **Ambersteel-Lined**: Bonus protection from magic: **+1** for every quality level. **+1D4** for every two **quality levels**, starting at level 1.
* **Ambersteel-Plated**: Bonus protection from magic: **+1** for every quality level. **+1D6** for every two **quality levels**, starting at level 1.
* **Ambersteel-Forged**: Bonus protection from magic: **+2** for every quality level. **+1D8** for every two **quality levels**, starting at level 1.

> An **Ambersteel**-lined armor at quality level 3 would have +(3 + **2D4**) protection from magic. 

### Shield Types
Shields are items that provide passive bonuses to defense against melee and ranged attacks and require one free hand to use. This implies they cannot be used at the same time as a two-handed weapon (unless of course if you have more than two arms). 

##### Buckler
A small, round shield commonly held as far from the body as possible, to deflect small or stabbing weapons with ease. Helps only little against heavy blows, however. And don't expect to deflect arrows with this, either. 

* Bulk: 1

| Defensive Bonus       |
| --------------------- |
| +1D for melee defense. |
| +3D for melee defense against **stabbing** attacks. |

##### Round Shield
A medium-sized, round shield made from tough wood and leather, which offers decent protection against most attacks, while not encumbering the wielder too much. 

* Bulk: 2

| Defensive Bonus      |
| -------------------- |
| +2D for any defense. |

##### Heater Shield
A tough and heavy metal shield, which offers great protection, while still being somewhat manageable to wield. 

* Bulk: 3
* +1 [exhaustion](#exhaustion) while wielded

| Defensive Bonus      |
| -------------------- |
| +3D for any defense. |

##### Kite Shield
A large, kite-shaped shield, which can protect every part of the fighter, from the shoulder down to the feet. Its weight makes it difficult to react to attacks quickly, hoever. 

* Bulk: 4
* +2 [exhaustion](#exhaustion) while wielded

| Defensive Bonus      |
| -------------------- |
| +4D for any defense. |

### List of General Assets
The following is a list of general assets. Of course, the following list is non-exhaustive. Invent more at your own need. 

| Name                   | Bulk | Max. Stack Size | Description                                                              |
| ---------------------- | ---- | --------------- | ------------------------------------------------------------------------ |
| Laudanum Potion        | 1    | 2               | This wonderous substance can quell pain and calm nerves within seconds. Also effective against diarrhea. Upon imbibing, sets one **active** [injury](./core-rules.md#injury) to **patched up**. After 24 hours, the [injury](./core-rules.md#injury) is set back to **active**, even if it was **treated** in the meantime. Also, must succeed a [wit](./core-rules.md#wit-wit) test at **Ob** 2, or else become [addicted](./core-rules.md#drug-addicted) to the stuff. |
| Calming Tea            | 1    | 3               | This herbal tea has the ability to calm nerves. Removes [berserk](./core-rules.md#berserk), [jealous](./core-rules.md#jealous) and [terrified](./core-rules.md#terrified). Best enjoyed steaming hot, but not necessarily. |
| Smoke Bomb             | 1    | 3               | A small fragile shell, filled with a very fine powder which when broken causes an area in a 6'/2m radius to be covered in smoke. It is impossible to see through and ranged attacks within or through the area suffer +2 **Ob**. Victims caught in the smoke may be forced to cough. The smoke lasts 6 turns or 30 seconds. |
| Acid Bomb              | 1    | 2               | A small fragile shell with two compartments, filled with two liquids which, when they combine, act as a powerful acid. When shattered, deals **2D8** **acid** damage to whatever it hits. |
| Blackpowder Bomb       | 1    | 2               | A small iron-shelled bomb, filled with blackpowder. A short fuse sticks out and must be lit to set it off. Once lit, the bomb will detonate after 3 turns or 15 seconds. Deals **2D6** **crushing** + **2D6** **burning** damage to anyone in a 6'/2m radius. |
| Throwing Blade         | 1    | 6               | A small weighted blade, like a knife or star, well suited to being thrown. Can be used in melee and acts like a [dagger](#dagger-agiawar), but with a penalty of **-2D** to attack and defence. **+1D** when [thrown](./core-rules.md#throwing-accuracy) for a ranged attack. Deals **2D4 + Str** **piercing** damage. |

### Weapon Types
Following are fantasy-themed weapon types. 

For ranged weapons there is note made of a value called the "distance increment". This describes the distance within which the weapon can be used optimally, for no penalty to **Ob** and damage. As soon as a shooter wants to hit a target past their initial (= optimal) distance increment, they incur a penalty as noted on the attack in question. This penalty is multiplied by every increment past the initial. 

> For example, when a distance increment of 30'/10m has been noted, then shooting anything within and up to that distance incurs no penalties. But as soon as the shooter wants to hit something at 33'/11m distance, they incur their first penalty. The next penalty is incurred at 63'/21m and so on. 

#### Dagger (Agi/Awar)
Any very short, one-handed blade. Examples: shiv, dagger, rondel-dagger

For all attacks made with a dagger, the following rules apply:
* If the target is unaware or [grappled](./core-rules.md#grappled), then the target's armor does **not** reduce the dagger's damage.
* -1 **Ob** against [proned](./core-rules.md#prone) and/or [grappled](./core-rules.md#grappled) targets.

* Melee
* Bulk: 1
* Ranged (throwable: stab)

| Level | Name                 | AP | **Ob**      | Damage                           | Notes  |
| ----- | -------------------- | -- | ----------- | -------------------------------- | ------ |
| 0     | Slash                | 2  | Opposed     | `1D6 + Agi` Slashing             |  |
| 0     | Stab                 | 2  | Opposed     | `1D6 + Agi` Piercing             |  |
| 0     | Artery Cut           | 2  | Opposed + 1 | `2D6` Slashing                   | +1 [bleeding](#bleeding) to the target (if it can bleed).  |
| 0     | Target Weak-Spot     | 2  | Opposed + 2 | `2D6 + Agi` Piercing             |  |

#### Light Blade (Agi/Str)
Any light blade. Most commonly (but not restricted to) one-handed weapons. Examples: Short-sword, Langes Messer, arming sword, falchion

* Melee
* Bulk: 1
* Ranged (throwable: stab)

| Level | Name                 | AP | **Ob**      | Damage                           | Notes  |
| ----- | -------------------- | -- | ----------- | -------------------------------- | ------ |
| 0     | Slash                | 2  | Opposed     | `1D8 + 2` Slashing               | / |
| 0     | Stab                 | 2  | Opposed     | `1D8 + 1` Piercing               | / |
| 0     | Grappling Feint      | 2  | Opposed - 1 | /                                | Attack with a feint, immediately close the distance and [grapple](./core-rules.md#grappled) your opponent. |

#### Long Blade (Agi/Str)
Any long and heavier blade, including heavy one-handed blades. Examples: Longsword, saber, side-sword, rapier

* Melee
* Bulk: 2

| Level | Name                 | AP | **Ob**      | Damage                           | Notes  |
| ----- | -------------------- | -- | ----------- | -------------------------------- | ------ |
| 0     | Slash                | 2  | Opposed     | `2D8` Slashing                   | / |
| 0     | Stab                 | 2  | Opposed     | `2D8` Piercing                   | / |
| 2     | Mord-Strike          | 2  | Opposed + 2 | `1D6 + 1` Crushing               | / |
| 3     | Fencer-Stance        | 2  | /           | /                                | Enter a defensive fencing stance. Gain **+1D** for melee defense and can [counter-attack](./core-rules.md#defence-stunts) **every** attack. |

#### Great Blade (Str/Tough)
Any very long and heavy two-handed blade. Examples: sword of war, great-sword, Zweihänder, Kriegsmesser

* Melee
* Bulk: 3
* [Long Reach](core-rules.md#weapon-properties)

| Level | Name                 | AP | **Ob**      | Damage                           | Notes  |
| ----- | -------------------- | -- | ----------- | -------------------------------- | ------ |
| 0     | Slash                | 2  | Opposed     | `3D8` Slashing                   | / |
| 0     | Stab                 | 2  | Opposed     | `2D8 + 2` Piercing               | / |
| 2     | Blade Barrier        | 2  | Opposed     | /                                | Whenever any character moves **into** a spot within reach, can attack that character with a **slash** at **Ob** + 1 and always force them back 3'/1m. |
| 3     | Heavy Blow           | 3  | Opposed + 1 | `2D8` Slashing + `1D8` Crushing  | Defending against this attack costs 2 [AP](#action-points-ap). +1 [exhaustion](#exhaustion) to self. |

#### Axe (Str/Str)
Small and light axes. Examples: hatchet, dane axe, woodcutter's axe

* Melee
* Bulk: 1
* Ranged (throwable: hack)

| Level | Name                 | AP | **Ob**      | Damage                           | Notes  |
| ----- | -------------------- | -- | ----------- | -------------------------------- | ------ |
| 0     | Hack                 | 2  | Opposed     |  `1D6 + 2` Slashing + `1D4` Crushing | / |
| 1     | Savage Slash         | 2  | Opposed + 1 |  `1D6 + 2` Slashing              | +1 [bleeding](#bleeding) to the target (if it can bleed). |

#### Great Axe (Str/Str)
Large and heavy axes. Examples: bearded axe, double-sided axe

* Melee
* Bulk: 3

| Level | Name                 | AP | **Ob**      | Damage                           | Notes  |
| ----- | -------------------- | -- | ----------- | -------------------------------- | ------ |
| 0     | Hack                 | 2  | Opposed     | `1D8` Slashing + `2D4` Crushing  | / |
| 2     | Savage Slash         | 2  | Opposed + 2 | `2D8` Slashing                   | +2 [bleeding](#bleeding) to the target (if it can bleed). |
| 3     | Heavy Blow           | 3  | Opposed + 1 | `1D8` Slashing + `1D6 + 2` Crushing | Defending against this attack costs 2 [AP](#action-points-ap). +1 [exhaustion](#exhaustion) to self. |

#### Spear (Agi/Str)
Any one or two-handed short piercing polearms. Examples: short-spear, boar-spear

* Melee
* Bulk: 2
* Ranged (throwable: stab)
* [Long Reach](core-rules.md#weapon-properties)
* [Prefer Range](core-rules.md#weapon-properties)

| Level | Name                 | AP | **Ob**      | Damage                           | Notes  |
| ----- | -------------------- | -- | ----------- | -------------------------------- | ------ |
| 0     | Stab                 | 2  | Opposed     | `2D8` Piercing                   | / |
| 0     | Spear Wall           | 2  | /           | Whenever any character moves **into** a spot within reach, can attack that character with a **stab** and always force them back 3'/1m. | / |

#### Lance (Awar/Str)
Any one or two-handed long piercing polearms. Examples: pike, lance

* Melee
* Bulk: 4
* [Long Reach](core-rules.md#weapon-properties)
* [Prefer Range](core-rules.md#weapon-properties)

| Level | Name                 | AP | **Ob**      | Damage                           | Notes  |
| ----- | -------------------- | -- | ----------- | -------------------------------- | ------ |
| 0     | Stab                 | 2  | Opposed     | `2D6` Piercing                   | / |
| 0     | Couched Lancing      | 2  | Opposed     | `3D10` Piercing                  | Requires self to be mounted on horse-back (or similar creature). Self must move at least 15'/5m in a straight line, past the target. |

#### Polearm (Str/Tough)
Flexible polearms with a focus on slashing. Examples: halberd, bardiche, poleaxe

* Melee
* Bulk: 4
* [Long Reach](core-rules.md#weapon-properties)
* [Prefer Range](core-rules.md#weapon-properties)

| Level | Name                 | AP | **Ob**      | Damage                           | Notes  |
| ----- | -------------------- | -- | ----------- | -------------------------------- | ------ |
| 0     | Slash                | 2  | Opposed     | `3D6` Slashing                   | / |
| 0     | Stab                 | 2  | Opposed     | `2D8` Piercing                   | / |
| 1     | Blade Barrier        | 2  | Opposed     | /                                | Whenever any character moves **into** a spot within reach, can attack that character with a **stab** at **Ob** + 1 and always force them back 3'/1m. |
| 2     | Cleave               | 2  | Opposed + 2 | `3D6` Slashing                   | Deals damage to up to two targets adjacent to each other and within reach. |

#### Club (Str/Str)
Simple, improvised bludgeoning weapons. Examples: wooden club, staff, stick

* Melee
* Bulk: 2

| Level | Name                 | AP | **Ob**      | Damage                           | Notes  |
| ----- | -------------------- | -- | ----------- | -------------------------------- | ------ |
| 0     | Clobber              | 2  | Opposed     | `Str + 2D4` Bludgeoning          | / |
| 0     | Knockout Blow        | 2  | Opposed + 2 | `Str + 2D6 + 2` Bludgeoning      | +1 [exhaustion](./core-rules.md#exhaustion) to target. |
| 0     | Smash                | 2  | Opposed     | `Str + 1D4` Crushing             | / |

#### Small Crusher (Str/Str)
Small, heavy crushing weapons with a dedicated *impact zone* on the weapon head which directs more force into the target. Examples: flanged mace, warhammer, flail, morning star

* Melee
* Bulk: 2

| Level | Name                 | AP | **Ob**      | Damage                           | Notes  |
| ----- | -------------------- | -- | ----------- | -------------------------------- | ------ |
| 0     | Smash                | 2  | Opposed     | `Str + 1D6 + 2` Crushing         | / |

#### Large Crusher (Str/Tough)
Large, heavy crushing weapons with a dedicated *impact zone* on the weapon head which directs more force into the target. Examples: grand-mace, polehammer, two-handed flail

* Melee
* Bulk: 3

| Level | Name                 | AP | **Ob**      | Damage                           | Notes  |
| ----- | -------------------- | -- | ----------- | -------------------------------- | ------ |
| 0     | Smash                | 2  | Opposed     | `Str + 1D8 + 2` **Crushing** | / |
| 1     | Mighty Smash         | 2  | Opposed + 2 | `Str + 2D8 + 1` **Crushing**     | Defending against this attack costs 2 [AP](#action-points-ap). +1 [exhaustion](#exhaustion) to self. |

#### Short-Bow (Awar/Awar)
A short distance ranged weapon, shooting arrows.

* Ranged
  * For every attack: +1 **Ob** and **-1D** damage for every distance increment past the initial.
* Bulk: 1
* [Range Only](core-rules.md#weapon-properties)

| Level | Name                 | AP | **Ob**      | Distance increments | Damage                     | Notes  |
| ----- | -------------------- | -- | ----------- | ------------------- | -------------------------- | ------ |
| 0     | Loose                | 2  | Opposed     | 30'/10m             | `3D4` Piercing             |  |
| 1     | Heavy Shot           | 3  | Opposed + 1 | 30'/10m             | `3D4 + Str` Piercing       |  |
| 2     | Double Shot          | 3  | Opposed     | 30'/10m             | `2D4` Piercing             | Can attack twice and thus deal its damage to two different targets, or the same target twice.  |

#### Longbow (Awar/Str)
A long distance ranged weapon, shooting arrows.

* Ranged
  * For every attack: +1 **Ob** and **-1D** damage for every distance increment past the initial.
* Bulk: 2
* [Range Only](core-rules.md#weapon-properties)

| Level | Name                 | AP | **Ob**      | Distance increments | Damage                     | Notes  |
| ----- | -------------------- | -- | ----------- | ------------------- | -------------------------- | ------ |
| 0     | Loose                | 2  | Opposed     | 45'/15m             | `4D4` Piercing             |  |
| 1     | Heavy Shot           | 3  | Opposed + 1 | 45'/15m             | `4D4 + Str` Piercing       |  +1 [exhaustion](#exhaustion) to self. |

#### War-Bow (Str/Tough)
A very deadly long distance ranged weapon, shooting arrows. Beware its exhausting strength of draw. 

* Ranged
  * For every attack: +1 **Ob** and **-1D** damage for every distance increment past the initial.
* Bulk: 2
* [Range Only](core-rules.md#weapon-properties)

| Level | Name                 | AP | **Ob**      | Distance increments | Damage                     | Notes  |
| ----- | -------------------- | -- | ----------- | ------------------- | -------------------------- | ------ |
| 0     | Loose                | 2  | Opposed     | 60'/20m             | `3D8` Piercing             | +1 [exhaustion](#exhaustion) to self.  |

#### Crossbow (Awar/Awar)
A deadly medium distance ranged weapon, shooting quarrels. Beware its slow reload. 

* Ranged
  * For every attack: +1 **Ob** and **-1D** damage for every distance increment past the initial.
* Bulk: 2
* [Prefer Range](core-rules.md#weapon-properties)
* [Slow Reload](core-rules.md#weapon-properties)

| Level | Name                 | AP | **Ob**      | Distance increments | Damage                     | Notes  |
| ----- | -------------------- | -- | ----------- | ------------------- | -------------------------- | ------ |
| 0     | Loose                | 2  | Opposed     | 60'/20m             | `3D8` Piercing             |  |

#### Firearm (Awar/Awar)
A very deadly short to medium distance ranged weapon, shooting musket balls that are likely to penetrate armor. Beware its slow reload. 

* Ranged
  * For every attack: +2 **Ob** for every distance increment past the initial.
* Bulk: 2
* [Prefer Range](core-rules.md#weapon-properties)
* [Very Slow Reload](core-rules.md#weapon-properties)

| Level | Name                 | AP | **Ob**      | Distance increments | Damage                     | Notes  |
| ----- | -------------------- | -- | ----------- | ------------------- | -------------------------- | ------ |
| 0     | Fire                 | 2  | Opposed     | 30'/10m             | `3D8 + 5` Piercing         |  |

## Lists of Skills
The following list does not and cannot aim to be a complete listing of all possible skills in game. Adding new skills as necessary will have to be done by the **GM**. 

### Physical Skills
These skills have a dominant physical aspect and are directly tied to a character's *physical attributes*. 

#### Rune-Using (Agi/Wit)
Skill at using [magic runes](#runes). 

| Level | Name                 | AP | **Ob** | Effect(s)          | Condition(s) |
| ----- | -------------------- | -- | ------ | ------------------ | ------------ |
| 4     | Hot Potato           | 1  | 3      | If using a rune would fail and result in a [spell-backfire](#spell-backfire), drop the rune, jump away and suffer only half the damage. | Caused a [spell-backfire](#spell-backfire) using a rune; Once per rest. |

#### Sailing (Awar/Wit)
Steering and maintaining a naval vessel. 

### Knowledge Skills
These skills have a dominant mental aspect and are strongly related to a character's *mental attributes*. 

#### Heraldry (Awar/Wit)
The ability to tell noble houses apart and to know their heraldry. 

#### Magic School < School > (< Attribute >)
Knowledge and experience in a specific [magic school](#list-of-magic-schools). 

See also [testing magic](#testing-magic). 

### Craftsmanship Skills
All craftsmanship requires a mix of physical and mental attributes, for the purpose of creating a wide variety of things.

#### Armor Smithing (Str/Wit)
The ability to make armor from conventional materials, such as metal and leather. 

[Crafting](#crafting)
| Product                              | Complexity | Workload  | Materials                              | Quality Bonus   |
| ------------------------------------ | ---------- | --------- | -------------------------------------- | --------------- | 
| 1 [light armor](#light-armor)        | High       | High      | Any shapeable sturdy and flexible material, such as iron, steel, leather or chitin. | Every **positive**: +1 **Slashing**; Every 2 **positives**: +1 **Bludgeoning**; Every 3 **positives**: +1 **Crushing**, +1 **Piercing** |
| 1 [medium armor](#medium-armor)      | High       | Very High | Any shapeable sturdy and flexible material, such as iron, steel, leather or chitin. | Every **positive**: +1 **Slashing**; Every 2 **positives**: +1 **Bludgeoning**; Every 3 **positives**: +1 **Crushing**, +1 **Piercing** |
| 1 [heavy armor](#heavy-armor)        | High       | Very High | Any shapeable sturdy and flexible material, such as iron, steel, leather or chitin. | Every **positive**: +1 **Slashing**; Every 2 **positives**: +1 **Bludgeoning**; Every 3 **positives**: +1 **Crushing**, +1 **Piercing** |

#### Ambersmithing (Str/Wit)
The ability to make things from [Amberite](#amberite). 

Lining or plating an existing object with [Ambersteel](#ambersteel) acts as an improvement, whereas an [Ambersteel](#ambersteel)-forged object is an entirely new object, completely made out of [Ambersteel](#ambersteel). 

The product effects do not stack, but they can be overridden. This means that the same object cannot be lined with [Ambersteel](#ambersteel) twice, for cumulative effects. But it can be upgraded to [Ambersteel](#ambersteel)-plated. 

[Crafting](#crafting)
| Product                              | Complexity | Workload  | Materials                              | Quality Bonus   |
| ------------------------------------ | ---------- | --------- | -------------------------------------- | --------------- | 
| Ambersteel-lined weapon              | High       | High      | [Ambersteel](#ambersteel); A weapon        | Bonus damage against mages and magical creatures: **+1** for every quality level. **+1D4** for every two **quality levels**, starting at level 2. |
| Ambersteel-plated weapon             | High       | Very High | [Ambersteel](#ambersteel); A weapon        | Bonus damage against mages and magical creatures: **+1** for every quality level. **+1D6** for every two **quality levels**, starting at level 2. |
| Ambersteel-forged weapon             | Very High  | Very High | [Ambersteel](#ambersteel)                  | Bonus damage against mages and magical creatures: **+2** for every quality level. **+1D8** for every two **quality levels**, starting at level 2. The weapon is +1 **bulkier** than an equivalent weapon that is not **Ambersteel** forged. |
| Ambersteel-lined armor               | High       | High      | [Ambersteel](#ambersteel); A set of armor  | Bonus protection from magic: **+1** for every quality level. **+1D4** for every two **quality levels**, starting at level 2. |
| Ambersteel-plated armor              | High       | Very High | [Ambersteel](#ambersteel); A set of armor  | Bonus protection from magic: **+1** for every quality level. **+1D6** for every two **quality levels**, starting at level 2. |
| Ambersteel-forged armor              | Very High  | Very High | [Ambersteel](#ambersteel)                  | Bonus protection from magic: **+2** for every quality level. **+1D8** for every two **quality levels**, starting at level 2. The armor is +1 **bulkier** than an equivalent armor that is not **Ambersteel** forged. |
| Ambersteel-lined shield              | High       | High      | [Ambersteel](#ambersteel); A shield        | Bonus protection from magic: **+1** for every quality level. **+1D4** for every two **quality levels**, starting at level 2. |
| Ambersteel-plated shield             | High       | Very High | [Ambersteel](#ambersteel); A shield        | Bonus protection from magic: **+1** for every quality level. **+1D6** for every two **quality levels**, starting at level 2. |
| Ambersteel-forged shield             | Very High  | Very High | [Ambersteel](#ambersteel)                  | Bonus protection from magic: **+2** for every quality level. **+1D8** for every two **quality levels**, starting at level 2. The shield is +1 **bulkier** than an equivalent shield that is not **Ambersteel** forged. |

> An **Ambersteel**-lined weapon at quality level 3 would have +(3 + **2D4**) damage against mages and magical creatures. 

See also [protection from magic](#protection-from-magic). 

> An **Ambersteel**-lined armor at quality level 3 would have +(3 + **2D4**) protection from magic. 
>
> This means damage from magic source will be reduced by 3 + **2D4** and a non-damaging **spell's intensity** is reduced by 3. 

#### Alchemy (Arc/Wit)
The ability to brew alchemical potions, create powders, mixtures and other substances, as well as the ability to tell these things apart. 

Tools: a distillery, mortar and pestle, a fire place

[Crafting](#crafting)
| Product                              | Complexity | Workload  | Materials                              | Quality Bonus   |
| ------------------------------------ | ---------- | --------- | -------------------------------------- | --------------- | 
| A simple alchemical concoction (potion or powder)  | Moderate  | Moderate | Small containers, minerals, metals, herbs and water. | / |
| A complex alchemical concoction (potion or powder) | Very High | High     | Small containers, minerals, metals, herbs and water. | / |

#### Brewing (Wit/Wit)
The brewing of alcoholic beverages. 

Tools: a fire place, a distillery

[Crafting](#crafting)
| Product                              | Complexity | Workload  | Materials                              | Quality Bonus   |
| ------------------------------------ | ---------- | --------- | -------------------------------------- | --------------- | 
| A small keg worth of alcohol         | Moderate   | Very High | Any closeable container; Any fermentable fruit or distillable plant matter. | / |

#### Blacksmithing (Agi/Str)
The ability to create every-day items from metal. 

Tools: a hammer, an anvil or other resilient surface, tongs, a forge

[Crafting](#crafting)
| Product                              | Complexity | Workload  | Materials                              | Quality Bonus   |
| ------------------------------------ | ---------- | --------- | -------------------------------------- | --------------- | 
| A large item, such as a handheld tool               | Moderate | High     | Any shapeable metal; (Wood). | / |
| Several smaller items, such as nails or arrow-heads | Moderate | Moderate | Any shapeable metal. | / |

#### Bow-Making (Agi/Awar)
The ability to craft bows and crossbows. 

Tools: a carving knife

[Crafting](#crafting)
| Product                              | Complexity | Workload  | Materials                              | Quality Bonus   |
| ------------------------------------ | ---------- | --------- | -------------------------------------- | --------------- | 
| Bow                                  | Low        | Moderate  | A piece of sturdy and flexible wood; A piece of string or sinew. | Every 3 **positives**: +1 **Piercing** |
| Crossbow                             | High       | High      | Sturdy pieces of wood; Metal arms; a piece of string or sinew. | Every 3 **positives**: +1 **Piercing** |

#### Carpentry (Agi/Str)
The ability to shape wood to craft predominantly wooden things. 

Tools: an axe, a wood plane, a hand drill, a workbench

[Crafting](#crafting)
| Product                              | Complexity | Workload  | Materials                              | Quality Bonus   |
| ------------------------------------ | ---------- | --------- | -------------------------------------- | --------------- | 
| A small piece of furniture           | Moderate   | Moderate  | Wood                                   | / |
| A large piece of furniture           | Moderate   | High      | Wood                                   | / |

#### Clothesmaking (Agi/Wit)
The ability to make comfortable, well-fitting and decorated clothes. 

Tools: scissors, needles, yarn, thread

[Crafting](#crafting)
| Product                              | Complexity | Workload  | Materials                              | Quality Bonus   |
| ------------------------------------ | ---------- | --------- | -------------------------------------- | --------------- | 
| A piece of clothing                  | Moderate   | Moderate  | Cloth                                  | / |

#### Engineering (Agi/Wit)
The ability to plan and construct complex mechanisms and devices. 

[Crafting](#crafting)
| Product                              | Complexity | Workload  | Materials                              | Quality Bonus   |
| ------------------------------------ | ---------- | --------- | -------------------------------------- | --------------- | 
| A simple mechanism                   | High       | Low       | Any suitable material                  | / |
| A complex mechanism                  | High       | Moderate  | Any suitable material                  | / |

#### Fletching (Agi/Awar)
The ability to efficiently craft arrows, bolts and javelins. 

Tools: a carving knife, a brush

[Crafting](#crafting)
| Product                              | Complexity | Workload  | Materials                              | Quality Bonus   |
| ------------------------------------ | ---------- | --------- | -------------------------------------- | --------------- | 
| 5 Arrow shafts                       | Low        | Moderate  | Wood; feathers; glue                   | / | 

#### Glass-Blowing (Agi/Agi)
The ability to make objects from glass. 

Tools: a fire place, a glass-blower, various shaping tools

[Crafting](#crafting)
| Product                              | Complexity | Workload  | Materials                              | Quality Bonus   |
| ------------------------------------ | ---------- | --------- | -------------------------------------- | --------------- | 
| A small glass object                 | High       | Moderate  | Quartz; sand                           | / | 

#### Goldsmithing (Agi/Agi)
The ability to make jewelry from precious metals and stones. 

Tools: hammers, tweezer, chisels, a workbench, magnifying glasses

[Crafting](#crafting)
| Product                              | Complexity | Workload  | Materials                              | Quality Bonus   |
| ------------------------------------ | ---------- | --------- | -------------------------------------- | --------------- | 
| A small piece of jewelry             | High       | High      | Quartz; sand                           | / | 

#### Leatherworking (Agi/Wit)
The ability to create leather objects. 

Tools: scissors, needles, hole punchers and a hammer

[Crafting](#crafting)
| Product                              | Complexity | Workload  | Materials                              | Quality Bonus   |
| ------------------------------------ | ---------- | --------- | -------------------------------------- | --------------- | 
| 5 Small leather objects              | Low        | Moderate  | A tanned hide                          | / | 
| A large leather object               | Low        | Moderate  | A tanned hide                          | / | 

#### Masonry (Str/Tough)
The ability to shape stone to craft predominantly stone-based things. 

Tools: a hammer and chisels of varying sizes

[Crafting](#crafting)
| Product                              | Complexity | Workload  | Materials                              | Quality Bonus   |
| ------------------------------------ | ---------- | --------- | -------------------------------------- | --------------- | 
| A small stone-hewn object            | Low        | Very High | Stone                                  | / |
| A large stone-hewn object            | Low        | Very High | Stone                                  | / |

#### Rune Carving (Arc/Wit)
The ability to carve [magic runes](#runes).

The level of this skill dictates the maximum intensity level of the respective magic the carved rune can hold. The number of **positives** achieved in a test then sets the actual level the rune will hold, but limited by the maximum. 

Tools: a hammer and chisels of varying sizes, tongs, tweezer, a fine brush

[Crafting](#crafting)
| Product                              | Complexity | Workload  | Ob | Materials                              | Quality Bonus   |
| ------------------------------------ | ---------- | --------- | -- | -------------------------------------- | --------------- | 
| A blank rune                         | High       | Moderate  | /  | [Abyssalite](#abyssalite)              | / |
| A magic rune                         | Very High  | High      | 2  | A blank rune; thin-leaf metal          | +1 [spell intensity level](#magic) |

#### Shield-Making (Str/Wit)
The ability to make shields from conventional materials, such as wood and metal. 

Tools: axes, hammers, tongs, (if metal) a forge and anvil

[Crafting](#crafting)
| Product                              | Complexity | Workload  | Materials                              | Quality Bonus   |
| ------------------------------------ | ---------- | --------- | -------------------------------------- | --------------- | 
| 1 [buckler](#buckler)                | Moderate   | High      | Any shapeable sturdy and flexible material, such as wood, metal or chitin. | / |
| 1 [round shield](#round-shield)      | Moderate   | High      | Any shapeable sturdy and flexible material, such as wood, metal or chitin. | For every 3 quality levels, starting at level 2, reduction of bulk by 1 (to a minimum of 1). |
| 1 [heater shield](#heater-shield)    | Moderate   | High      | Any shapeable sturdy and flexible material, such as wood, metal or chitin. | For every 3 quality levels, starting at level 2, reduction of bulk by 1 (to a minimum of 1). |
| 1 [kite shield](#kite-shield)        | Moderate   | High      | Any shapeable sturdy and flexible material, such as wood, metal or chitin. | For every 3 quality levels, starting at level 2, reduction of bulk by 1 (to a minimum of 2). |

#### Tanning/Skinning (Agi/Tough)
Taking the hide off a creature undamaged. 

Tools: a knife, a scraping blade, a bucket, a brush

[Crafting](#crafting)
| Product                              | Complexity | Workload  | Materials                              | Quality Bonus   |
| ------------------------------------ | ---------- | --------- | -------------------------------------- | --------------- | 
| A small skin                         | Low        | Low       | A skinnable creature                   | / |
| A large skin                         | Moderate   | Moderate  | A skinnable creature                   | / |
| A tanned hide                        | Moderate   | High      | A tannable skin                        | / |

#### Weapon Smithing (Str/Wit)
The ability to make weapons from metal. 

Tools: a hammer, an anvil or other resilient surface, tongs, a forge

[Crafting](#crafting)
| Product                              | Complexity | Workload  | Materials                              | Quality Bonus   |
| ------------------------------------ | ---------- | --------- | -------------------------------------- | --------------- | 
| A weapon                             | High       | High      | Any suitable metal, wood and/or similar material | / |

#### Woodcarving (Agi/Agi)
Creating small things from carved wood. 

Tools: a carving knife

[Crafting](#crafting)
| Product                              | Complexity | Workload  | Materials                              | Quality Bonus   |
| ------------------------------------ | ---------- | --------- | -------------------------------------- | --------------- | 
| A small wood-carved object           | Low        | Moderate  | Wood                                   | / |
| A large wood-carved object           | Low        | High      | Wood                                   | / |

## List of Magic Schools
The capabilities of the various magic schools are described by the [expertise](./core-rules.md#expertise) associated with each of them. The concrete effects are kept vague on purpose, to allow a certain freedom when choosing how the magic is expressed. But the intensity or strength of a casting is tied to the level of the [magic school skill](#magic-school--school---attribute-). 

The levels noted for each magic school represent the effects a mage can achieve, when casting that particular type of magic. Stronger effects generally require a higher level. 

See also [testing magic](#testing-magic). 

In all the following tables, note the following:
* Replace *SI* with the chosen [spell intensity](#spell-intensity-si). 
* *Level* is the prerequisite level of the **magic school skill**, at which a given spell becomes available for use. 
* Whenever distances and radii are concerned, a mage may always choose a *shorter* distance or radius. For example, a `SI * 6'/2m` radius definition, sets the **maximum**. The radius may be at most this large, but can be smaller, if the mage so chooses. 
* Whenever the effect is unleashed in a **cone**, then at every point it has traveled, it is as far as it has traveled. So for example, at 3'/1m, it is 3'/1m wide. At 9'/3m, it is 9'/3m wide. 

### Alteration (Arc/Wit)
The alteration of physical things, to change their shape and purpose, permanently. 

Note that altering the shape of creatures poses a particular challenge. Unless if the test is a **complete success**, the target creature may mutate, horribly. When failing a test, consult the [list of mutations](#list-of-mutations), to determine the type of mutation. 

Creatures can resist the change with [toughness](./core-rules.md#toughness-tough). Inanimate objects don't resist. 

| Level | Name                 | AP | Distance | Ob                           | Effect(s)                      | Backfire Effect(s) |
| ----- | -------------------- | -- | -------- | ---------------------------- | ------------------------------ | ------------------ |
| 0     | Alter Shape          | 3  | 3'/1m    | Opposed + SI                 | A **ST** (object or creature) is altered as the mage desires. The complexity and size of the re-shaping depends on the **SI**. 1-3 are for simple and small, 4-6 for tricky and medium, 7-8 for complex and large and 9+ for very complex and very large alterations. Consult your **GM**! | The intended alteration occurs only on the caster. |

### Cryomancy (Arc/Arc)
The summoning and control of ice. Cryomancer's can freeze things, so they're heavier and harder to break. 

| Level | Name                 | AP | Distance    | Ob                           | Effect(s)                      | Backfire Effect(s) |
| ----- | -------------------- | -- | ----------- | ---------------------------- | ------------------------------ | ------------------ |
| 0     | Freezing Touch       | 2  | 3'/1m       | Opposed - SI                 | A fist-sized spot on a **ST**, that the mage's hand touches, freezes over and deals `SI` **freezing** damage. | The caster is affected, instead. |
| 1     | Cold Finger Gun      | 2  | SI * 15'/5m | Opposed                      | The mage shoots an ice spike at a **ST** from their hand, dealing `1D10 + SI` **freezing** damage. Causes +1 [frostbitten](./core-rules.md#frostbitten). | The caster is affected, instead. |
| 3     | Deep Freeze          | 3  | 3'/1m       | Opposed                      | A man-sized area of whatever the mage's hand is touching freezes over. The frost even penetrates and runs deep in a **ST**, dealing `SI D4` **freezing** damage. Causes +1 [frostbitten](./core-rules.md#frostbitten). | The caster is affected, instead. |
| 5     | Rooting Freeze       | 3  | SI * 15'/5m | 5                            | A spot of the mage's choosing freezes over. Anyone caught within the **AOE** `SI * 6'/2m` radius, will be frozen to the spot and thus [rooted](#rooted) and also suffer `SI D4` **Freezing** damage. They can break free via a successful [strength](./core-rules.md#strength-str) test at **Ob 3**. Or wait, until the ice thaws... | The spot beneath the caster is affected, instead. |

### Electromancy (Agi/Arc)
The summoning and control of lightning. Electricity is fairly versatile - it can injure or stun and power or trigger electrical and electronic devices. 

| Level | Name                  | AP | Distance     | Ob                           | Effect(s)                      | Backfire Effect(s) |
| ----- | --------------------- | -- | ------------ | ---------------------------- | ------------------------------ | ------------------ |
| 0     | Shocking Touch        | 2  | 3'/1m        | Opposed - SI                 | A small area, about the size of the mage's hand is burned on touch by an electrical shock, dealing `SI` **electrical** damage to a **ST**. | The caster is affected, instead. |
| 1     | Shock                 | 2  | SI * 9'/3m   | Opposed                      | An arc of lightning strikes the vulnerable internals of a **ST**, dealing `SI D4` **electrical** damage. | The caster is affected, instead. |
| 1     | Power-Up              | 2  | SI * 3'/1m   | SI                           | An electrical device is powered up for `SI * 5` minutes. | The device breaks or otherwise seizes up and becomes unusable. |
| 2     | Stunning Shock        | 2  | SI * 15'/5m  | Opposed - SI                 | An aimed arc of lightning strikes a **ST** and adds one stack of [stunned](./core-rules.md#stunned). | The caster is affected, instead. |
| 5     | UNLIMITED POWER       | 3  | SI * 30'/10m | Opposed                      | A cone of lightning spews forth from the mage's finger tips. Up to `SI + 1` **MST** can be hit with the shock, dealing `SI D6` **electrical** damage. | The caster and anyone next to them is affected, instead. |
| 5     | Mass Stunning Shock   | 3  | SI * 30'/10m | Opposed                      | Several arcs of aimed lightning spew forth from the mage's finger tips, striking up to `SI + 1` **MST** and adding 3 stacks of [stunned](./core-rules.md#stunned). | The caster and anyone next to them is affected, instead. |

### Illusion (Arc/Awar)
Creation of non-physical influences on the senses. That includes images, sounds and odors. The illusions cannot cause direct harm, although they can drive an individual to acts that may put them in danger. 

A victim reaching their [exhaustion threshold](#exhaustion) by effect of this magic, while [terrified](./core-rules.md#terrified), must succeed a [toughness](./core-rules.md#toughness-tough) test, or else suffer a heart-attack and **die** outright. The **Ob** is a third of the **attribute**, rounded up. 

| Level | Name                 | AP | Distance     | Ob                           | Effect(s)                      | Backfire Effect(s) |
| ----- | -------------------- | -- | ------------ | ---------------------------- | ------------------------------ | ------------------ |
| 0     | Illusion             | 2  | SI * 30'/10m | Opposed by [wit](./core-rules.md#wit-wit) + SI | **Concentration**; The affected **ST** *sees*, *hears* or *smells* an illusory image/sound/odor. The intensity of the illusion is determined by the **SI**. 1 for a weak and small, 2 for a moderate and 3-4 for a large and intense, 5-6 for a giant and 7+ for a titanic illusion. *Can* be used to inflict [terror](./core-rules.md#terrified) or intense [jealousy](./core-rules.md#jealous). The victim suffers +1 [exhaustion](./core-rules.md#exhaustion). | The caster suffers +1 [exhaustion](./core-rules.md#exhaustion). |

### Psionics (Arc/Wit)
Mind over matter! Psionics grants powerful abilities to manipulate objects, influence others and even wield magic as a weapon or shield. 

* Obvious: A purple flame lights within the mage's eyes, when they use their psionic abilities.
* [Prerequisites](./core-rules.md#specialization-skills): [Telepathy](#telepathy-arcwit) (3), [telekinesis](#telekinesis-arcagi) (3)

Only targets within and up to the given *distance* can be moved and only within and up to that *distance* from the mage. 

| Level | Name                 | AP | Distance     | Ob                           | Effect(s)                      | Backfire Effect(s) |
| ----- | -------------------- | -- | ------------ | ---------------------------- | ------------------------------ | ------------------ |
| 0     | Psionic Telekinesis  | 3  | SI * 30'/10m | Opposed                      | Move a **ST** at great velocity (if desired), which allows it to deal `SI D6` **variant** (depends on the type of object, if it is an object) damage upon impact. Alternatively, **crush** or restrain the object or creature. Can target yourself. | The caster is affected, instead. |
| 0     | Psionic Missile      | 2  | SI * 15'/5m  | Opposed                      | Using psionics, extend the force of a punch, to hurl a focused psionic shockwave towards a **ST**, dealing `SI D6` **bludgeoning** damage. | The caster is affected, instead. |
| 1     | Psionic Shield       | 2  | SI * 9'/3m   | SI                           | As a **reaction** to you or an ally being hit with an attack, cast a shield of psionic energy to erupt around yourself or an ally within distance, which absorbs up to `SI * 10` points of any damage. | Instead of absorbing damage, the target instead suffers an additional `SI * 3` points of **bludgeoning** damage. |
| 1     | Psionic Hasten       | 2  | SI * 36'/18m | 3 + SI                       | **Concentration**: [Hasten](./core-rules.md#hasted) up to `SI` creatures of choice. | The caster suffers +1 [exhaustion](./core-rules.md#exhaustion). |
| 1     | Levitate             | 1  | SI * 9'/3m   | Opposed                      | **Concentration**: Cause yourself or one other **ST** of choice, within *distance* to levitate a short distance above the ground. | The caster suffers +1 [exhaustion](./core-rules.md#exhaustion). |
| 3     | Dimensional Shift    | 3  | SI * 30'/10m | Opposed                      | Cause a dimensional rift to open and swallow a **ST** of choice, which another rift releases at a location of your choosing, a moment later. | The caster is instead swallowed by a rift, immediately tossed back out in the same spot and suffers `1D10` points of **crushing** damage. |

### Pyromancy (Arc/Arc)
The summoning and control of fire. The flame being a destructive force, pyromancers enjoy little utility from their magic, beyond the ability to create light and heat. 

| Level | Name                 | AP | Distance     | Ob                           | Effect(s)                      | Backfire Effect(s) |
| ----- | -------------------- | -- | ------------ | ---------------------------- | ------------------------------ | ------------------ |
| 0     | Burning Touch        | 2  | 3'/1m        | Opposed - SI                 | A controlled flame erupts and stays in the mage's hand, inflicting `SI + 2` **burning** damage on touch to a **ST**. | The caster is affected, instead. |
| 1     | Cone of Fire         | 3  | SI * 6'/2m   | Opposed                      | The mage shoots a burst of fire in a short cone in front of them, hitting up to two adjacent **MST**, dealing `SI D4` **burning** damage. | The caster and anyone next to them is affected, instead. |
| 3     | Fire Ball            | 2  | SI * 45'/15m | SI                           | The mage forms a large ball of flame between their hands, ready to be flung at a target location, dealing `SI D6` **burning** damage in a **AOE** `SI * 3'/1m` radius. | The caster and anyone next to them is affected, instead. |
| 7     | Flame Jet            | 3  | SI * 30'/10m | SI + 1                       | A steady stream of flame shoots from the mage's hands, dealing `SI D6` **burning** damage to anything caught by it, in a straight **AOE** line.  | The line of fire erupts backwards, through the mage. They and anyone behind them, in the line's range is affected. |
| 9     | Rain of Fire         | 4  | SI * 60'/20m | SI + 3                       | The mage makes fire rain from the sky. A ball of fire falls from the sky for every `SI`, dealing `6D6 + SI` **burning** damage in a **AOE** `24'/8m` radius, at a location of choice. | No fire falls from the sky, instead the SI number of fire balls erupt in the mage's hands. They and anyone in the radius suffers the damage. |

### Restoration (Arc/Awar)
The mending of [injuries](./core-rules.md#injury) and treatment of [diseases](./core-rules.md#illness). 

| Level | Name                 | AP | Distance | Ob                           | Effect(s)                      | Backfire Effect(s) |
| ----- | -------------------- | -- | -------- | ---------------------------- | ------------------------------ | ------------------ |
| 0     | Patching Touch       | 2  | 3'/1m    | 1                            | A **ST** of the mage's choosing, in hand's reach, is magically healed. Removes **SI** points of [bleeding](#bleeding) and **SI** points of [poisoned](#poisoned). One [injury](#injury) of choice is now **patched up**. Restores **(SI D4) * 2** missing [HP](./core-rules.md#hit-points-hp). | The caster receives +1 point of [bleeding](./core-rules.md#bleeding). |
| 1     | Treating Touch       | 2  | 3'/1m    | 2                            | A **ST** of the mage's choosing, in hand's reach, is magically healed. Up to **SI** [injuries](#injury) of choice are now **treated up** and their time to heal is reduced by **SI D4** days. Restores all missing [HP](./core-rules.md#hit-points-hp). | The caster receives **SI** random [injuries](#injury). |
| 4     | Life Leech           | 3  | 3'/1m    | Opposed by [toughness](./core-rules.md#toughness-tough) | Draw the life from a **ST** creature of choice. Deals **SI D4** points of damage while healing another touched creature's or one's own [HP](./core-rules.md#hit-points-hp) for the same amount. Transfers 1 point of [bleeding](#bleeding) and/or [poisoned](#poisoned) from the healed creature to the damaged one. | The effect triggers in reverse, drawing **SI** [HP](./core-rules.md#hit-points-hp) from the caster and sending them to their victim. Transfers **SI** points of [bleeding](#bleeding) and/or [poisoned](#poisoned) from the target to the caster. |
| 5     | Expel Illness        | 3  | 3'/1m    | 4                            | Removes **SI** number of [illnesses](#illness) of choice from a **ST** of choice, in hand's reach. | The caster contracts **SI** random [illnesses](#illness). | 
| 6     | Revert Mutation      | 4  | 3'/1m    | 6                            | Removes **SI** number of [mutations](#list-of-mutations) of choice from a **ST** of choice, in hand's reach. | The caster receives **SI** random [mutations](#list-of-mutations). |

### Soul-Binding (Arc/Tough)
Also referred to as **necromancy**, this is the art and skill of calling souls from the **plane of the dead** and binding them, to reanimate corpses or animate an otherwise unliving body. 

In order to bind a soul, a **soul-seal** is required. This seal has to take the form of a pentagram. The medium doesn't matter, although if the seal is destroyed, the soul binding is broken. So, if a mage wants to create a lasting soul-binding, an enduring medium for the seal is advisable. 

A mage can only ever issue commands to a soul that they've bound. It is not possible to command souls bound by other mages. 

A **soul-binding** can be broken, but it in order to do so, a **soul-binding** test at **Ob** equal to the strength of the **soul-binding** must be **completely succeeded**. It is possible to lift a **soul-binding** made by another mage. 

An important note about **completely failing** a **soul-binding** attempt - a **complete failure** results in the spell-backfiring and displacing the mage's soul with the one they were trying to bind. Their soul is essentially evicted from their own body and sent to the **plane of the dead**. The soul they tried to bind then takes over their body. 

Another important note about targeting a specific soul. It is easier to recall the soul that previously inhabited a body, the shorter the time of death has been. However, targeting a specific soul is an immensely difficult undertaking and shouldn't be taken lightly. For every day past the original time of death, the difficulty of recalling the soul increases by **1 Ob**. 

| Level | Name                 | AP | Distance   | Ob                           | Effect(s)                      | Backfire Effect(s) |
| ----- | -------------------- | -- | ---------- | ---------------------------- | ------------------------------ | ------------------ |
| 0     | Call and Bind a Soul | 3  | 3'/1m      | SI                           | Create a **soul-binding** at the strength of the chosen level. The larger, heavier and more complex a body is, the harder it is to create a binding. Anything larger than, heavier or more complex than a human will make the **soul-binding** harder. 1-3 for a small and simple, 4-5 for a moderate and 6+ for a large and complex binding. Consult your **GM**. Requires a **soul-seal**. Replacing an existing binding is possible, but the test must exceed the original soul-seals strength. | The caster's soul is evicted from their body and another soul takes place. The caster's character is effectively removed from the world. |
| 1     | Command Bound Soul   | 1  | SI * 6'/3m | Opposed by [wit](./core-rules.md#wit-wit) - SI | Issue a single command that the bound soul **must** follow. | +1 [exhaustion](./core-rules.md#exhaustion) to the caster. |
| 1     | Break Binding        | 3  | 3'/1m      | SI of the seal               | Break a **soul-binding** and send the soul back to the **plane of the dead**, leaving its former body inanimate and soulless. | The caster's soul is evicted from their body and another soul takes place. The caster's character is effectively removed from the world. |
| 5     | Call back a Soul     | 3  | 3'/1m      | SI + days since death        | Target a specific soul and recall them into their prior body. This isn't, strictly speaking, the same as binding a soul. | The caster's soul is evicted from their body and another soul takes place. The caster's character is effectively removed from the world. |

### Telekinesis (Arc/Agi)
The ability to affect things and even creatures from afar, using magic instead of muscles or tools. 

When using objects as projectiles, choose the [damage type](#damage-types) as appropriate. For example, a crossbow bolt might cause **piercing** damage, while a rock might cause **crushing** damage.

The mage can only ever perform *one* movement with a spell cast. So, for example, it is not possible to violently shake things or creatures around, without casting **telekinesis** multiple times, to do so. During combat, every movement takes one turn. Out of combat, about five seconds. A single movement is a displacement from one point to another, in a straight and uninterrupted line. 

Only targets within and up to the given *distance* can be moved and only within and up to that *distance* from the mage. 

| Level | Name                   | AP | Distance     | Ob                           | Effect(s)                      | Backfire Effect(s) |
| ----- | ---------------------- | -- | ------------ | ---------------------------- | ------------------------------ | ------------------ |
| 0     | Telekinesis            | 2  | SI * 15'/5m  | SI                           | Move an inanimate **ST** object at great velocity (if desired), which allows it to deal `SI D4` **variant** (depending on the type of object) damage upon impact. | The caster suffers +1 [exhaustion](./core-rules.md#exhaustion). |
| 3     | Creature Telekinesis   | 3  | SI * 15'/5m  | Opposed                      | Move a **ST** large, or smaller, creature. | The caster is knocked back `SI * 9'/3m` and suffers `SI * 2` **bludgeoning** damage. |

### Telepathy (Arc/Wit)
The ability to communicate wordlessly, to alter emotions and even issue compelling commands against another's will. 

| Level | Name                   | AP | Distance     | Ob                           | Effect(s)                      | Backfire Effect(s) |
| ----- | ---------------------- | -- | ------------ | ---------------------------- | ------------------------------ | ------------------ |
| 0     | Wordless Communication | 2  | SI * 12'/4m  | SI                           | **Concentration**: Communicate wordlessly with **SI** **MST**. | The caster suffers +1 [exhaustion](./core-rules.md#exhaustion). |
| 0     | Read Thoughts          | 2  | SI * 12'/4m  | Opposed by [wit](./core-rules.md#wit-wit) - SI | Glimpse into the thoughts of **ST** for a short time. | The target instead catches a glimpse into the caster's thoughts. The caster suffers +1 [exhaustion](./core-rules.md#exhaustion). |
| 3     | Change a Mind          | 2  | SI * 12'/4m  | Opposed by [wit](./core-rules.md#wit-wit) - SI | Alter a creature's current state of mind and emotion. | The caster is affected, instead. |
| 4     | Pressing Thought       | 3  | SI * 30'/10m | SI + 2                       | [Hasten](./core-rules.md#hasted) up to **SI** **MST** of choice for **SI** turns of combat or **SI** * 5 seconds out of combat. | The caster suffers +1 [exhaustion](./core-rules.md#exhaustion). |
| 6     | Quiet Command          | 3  | SI * 30'/10m | Opposed by [wit](./core-rules.md#wit-wit) - SI | Issue a command to another creature, which they feel **strongly** compelled to follow. | The caster is affected, instead. |
| 7     | Confer Knowledge       | 4  | 3'/1m        | 7 - SI                       | Confer +1 level of a **known skill** to another creature. | The caster loses 1 level in the chosen skill. |

## List of Injuries
* New description of "Tremors": -1 [Arcana](#arcana-arc); -1 [Agility](./core-rules.md#agility-agi)

## List of Illnesses
This list supplements the list of **injuries** of the [core module](./core-rules.md#list-of-injuries). 

| Name              | Duration          | Effect      | Treatment |
| ----------------- | ----------------- | ----------- | --------- |
| Amber Curse       | **2D10** Days     | The victim finds it difficult to feel the flow of magic through their body. **-1D4** [arcana](#arcana-arc); **-1D4** to any magic skills and [rune-using](#rune-using-agiwit). | Conventional methods cannot treat this illness. It can be treated with a potion of powdered [abyssalite](#abyssalite). |
