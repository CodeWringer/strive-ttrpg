<div style="text-align: center; font-size: 6rem; line-height: 4rem; margin-top: 2.5rem;">STRIVE</div>
<div style="text-align: center; font-size: 4rem">Fantasy Module</div>
<div style="text-align: center; font-size: 1rem">Version 11 (Playtest)</div>

# Introduction
This is the module containing the rules enabling play in a medieval fantasy game world, which includes supernatural monsters and magic. Only the differences and additions to the core rules are included in this document. 

This module is best suited for a medium fantasy setting. It introduces magic, which is a **powerful** tool, that comes with great risk. Mages who exert themselves too much may fail their spell cast, which results in a back-fire. But the likelihood of failure is manageable.

The module introduces:
* The [Arcana](#arcana-arc) attribute.
* [Magic](#magic) rules.
* Medieval/fantasy themed [armors](#armor), [shields](#shield-types), [general assets](#list-of-general-assets), [weapons](#weapon-types) and [skills](#lists-of-skills).

There is a [compendium document](./strive-fantasy-game-masters-resource.md) reserved solely for the **GM**, containing additional resources for them to draw from.

# Table of Contents
- [Introduction](#introduction)
- [Table of Contents](#table-of-contents)
- [Glossary](#glossary)
- [Credits](#credits)
- [License](#license)
- [Character](#character)
  - [Attributes](#attributes)
    - [Arcana \[Arc\]](#arcana-arc)
- [Magic](#magic)
  - [Testing Magic](#testing-magic)
  - [Spell Intensity (SI)](#spell-intensity-si)
  - [Arcane Overheat](#arcane-overheat)
  - [Arcane Slag](#arcane-slag)
  - [Casting Time](#casting-time)
  - [Spell-Backfire](#spell-backfire)
  - [Concentration Spells](#concentration-spells)
  - [Magic Negation](#magic-negation)
  - [Protection From Magic](#protection-from-magic)
  - [Magic Echoes](#magic-echoes)
  - [Magic Things](#magic-things)
    - [Abyssalite](#abyssalite)
    - [Amberite](#amberite)
    - [Ambersteel](#ambersteel)
    - [Arcane Engine](#arcane-engine)
    - [Cerebillium](#cerebillium)
    - [Runes](#runes)
    - [Magic Scrolls](#magic-scrolls)
    - [Malevite](#malevite)
      - [Malevite Side-Effects](#malevite-side-effects)
  - [Memorum](#memorum)
- [The Veil](#the-veil)
- [Assets](#assets)
  - [Weapon Properties](#weapon-properties)
- [Appendix](#appendix)
  - [Character Creation](#character-creation)
    - [Determine Abilities](#determine-abilities)
      - [Choosing Attributes](#choosing-attributes)
        - [Manual Attribute Assignment](#manual-attribute-assignment)
        - [Semi-Random Attribute Assignment](#semi-random-attribute-assignment)
      - [Choosing Skills](#choosing-skills)
    - [Determine Arcane Overheat Thresholds](#determine-arcane-overheat-thresholds)
  - [List of Assets](#list-of-assets)
    - [Armor](#armor)
      - [Armor Properties](#armor-properties)
      - [Light Armor](#light-armor)
      - [Medium Armor](#medium-armor)
      - [Heavy Armor](#heavy-armor)
    - [Shield Types](#shield-types)
        - [Light Shield](#light-shield)
        - [Medium Shield](#medium-shield)
        - [Heavy Shield](#heavy-shield)
    - [List of General Assets](#list-of-general-assets)
    - [Weapon Types](#weapon-types)
      - [Dagger (Agi/Awar)](#dagger-agiawar)
      - [Light Blade (Agi/Str)](#light-blade-agistr)
      - [Long Blade (Agi/Str)](#long-blade-agistr)
      - [Great Blade (Str/Tough)](#great-blade-strtough)
      - [Chained-Blade (Agi)](#chained-blade-agi)
      - [Axe (Str/Str)](#axe-strstr)
      - [Great Axe (Str/Str)](#great-axe-strstr)
      - [Spear (Agi/Str)](#spear-agistr)
      - [Lance (Awar/Str)](#lance-awarstr)
      - [Polearm (Str/Tough)](#polearm-strtough)
      - [Small Crusher (Str/Tough)](#small-crusher-strtough)
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
      - [Rune-Smithing (Arc/Wit)](#rune-smithing-arcwit)
      - [Shield-Making (Str/Wit)](#shield-making-strwit)
      - [Tanning/Skinning (Agi/Tough)](#tanningskinning-agitough)
      - [Weapon Smithing (Str/Wit)](#weapon-smithing-strwit)
      - [Woodcarving (Agi/Agi)](#woodcarving-agiagi)
    - [Special Skills](#special-skills)
      - [Psionics (Arc/Wit)](#psionics-arcwit)
  - [List of Magic Schools](#list-of-magic-schools)
    - [Aeromancy (Arc/Agi)](#aeromancy-arcagi)
    - [Artificing (Arc/Wit)](#artificing-arcwit)
    - [Alteration (Arc/Wit)](#alteration-arcwit)
      - [Werewolf-Shape](#werewolf-shape)
      - [Werebear-Shape](#werebear-shape)
    - [Cryomancy (Arc/Arc)](#cryomancy-arcarc)
    - [Electromancy (Agi/Arc)](#electromancy-agiarc)
    - [Hexing (Arc/Arc)](#hexing-arcarc)
    - [Hydromancy (Agi/Arc)](#hydromancy-agiarc)
    - [Illusion (Arc/Awar)](#illusion-arcawar)
    - [Pyromancy (Arc/Arc)](#pyromancy-arcarc)
    - [Restoration (Arc/Awar)](#restoration-arcawar)
    - [Sanguinomancy (Arc/Tough)](#sanguinomancy-arctough)
    - [Soul-Binding (Arc/Tough)](#soul-binding-arctough)
    - [Telekinesis (Arc/Agi)](#telekinesis-arcagi)
    - [Telepathy (Arc/Wit)](#telepathy-arcwit)
  - [List of Illnesses](#list-of-illnesses)
  - [Archetype Characters](#archetype-characters)
    - [The Arcaenologist](#the-arcaenologist)
    - [The Performer](#the-performer)
    - [The Surgeon](#the-surgeon)
    - [The Tired Monster Hunter](#the-tired-monster-hunter)
    - [The Warboss](#the-warboss)
- [Fantasy Game-Masters Resource](#fantasy-game-masters-resource)
- [Creature Compendium](#creature-compendium)
  - [Swine-Beasts](#swine-beasts)
    - [Swine Hostility](#swine-hostility)
      - [Demonic Blood](#demonic-blood)
      - [Filth \& Darkness](#filth--darkness)
    - [Swine Belcher](#swine-belcher)
    - [Swine Champion](#swine-champion)
    - [Swine Lunger](#swine-lunger)
    - [Swine Ogre](#swine-ogre)
    - [Swine Shaman](#swine-shaman)
    - [Swine Skewerer](#swine-skewerer)
    - [Swine Slasher](#swine-slasher)
    - [Swine Stomper](#swine-stomper)
  - [Veil Entities](#veil-entities)
    - [The Monolith](#the-monolith)
    - [Perfection](#perfection)
    - [The Tar Mycelium](#the-tar-mycelium)
    - [Cacophony of Flesh](#cacophony-of-flesh)
    - [The Puppeteer](#the-puppeteer)
  - [Undead](#undead)
    - [Alp](#alp)
  - [Void Demons](#void-demons)
    - [Void Stalker](#void-stalker)

# Glossary

| Term                                         | Meaning / Description  |
| -------------------------------------------- | ---------------------- |
| [Arc](#arcana-arc)                           | The Arcana attribute   |
| [OPN](#psionics-arcwit)                      | Openness to [The Veil](#the-veil) |
| [SI](#spell-intensity-si)                    | Spell Intensity        |

# Credits
**Designer**: Nicolas 'Krubi' H.

My two small, yet inexorable groups of playtesters, whose feedback has been invaluable, without whom this game would not be any where near where it is now and who keep me motivated!

# License
This official STRIVE Fantasy Module is licensed unter the same license as the STRIVE Core rules, which can be found at the following link. 
* https://github.com/CodeWringer/strive-ttrpg/blob/develop/documents/en/strive-core.md#license

# Character
New in this module, is the attribute [arcana](#arcana-arc), which governs a character's capacity for magic. 

## Attributes
Supplements to the [core attribute rules](./strive-core.md#attributes). 

### Arcana [Arc]
<img src="../../img/arcana.svg" style="width: 3rem; height: 3rem;"></img> Governs a character's ability to control and sense magic flow, casting magic spells or detecting lingering magic. 

This is the only attribute that can have a level of `0`, meaning playing a mage is a deliberate choice. 

# Magic
For this supplement, magic is assumed to be a mostly invisible supernatural force that runs all throughout, like a magnetosphere. Perhaps it could be called the *Arcanosphere*. How magic manifests itself, is up to the world the **GM** is running. Is there a verbal component? Must the mage trace arcane symbols into the air or onto some surface? Are the magical currents visible and glow eerily? This supplement makes no assumptions in this regard. 

Only a character with [Arcana](#arcana-arc) can cast magic at will. What kind of magic, depends on the [magic schools](#list-of-magic-schools) the character knows. There are offensive, defensive and manipulative [schools of magic](#list-of-magic-schools). 

There may also be magic artifacts that can either cause magical effects on their own, or through character interaction. With such artifacts, it may be possible for non-mages to cast magic. For that, see [runes](#runes) and [scrolls](#magic-scrolls). 

A *magic spell* is the intended effect of using a [magic school's](#magic-school--school---attribute-) [Expertises](./strive-core.md#expertise). Using such an Expertise is also referred to as *casting magic*, *casting a spell* or other similar wordings. In mechanical terms, the [Expertises](./strive-core.md#expertise) are the *spells* of a [school of magic](#list-of-magic-schools).

A mage can fail their [test](./strive-core.md#tests) and thus suffer a [spell-backfire](#spell-backfire), which usually results in negative effects for the caster, instead of their intended target. 

[Spell Intensity](#spell-intensity-si) sets the strength of a magic spell and how much [Arcane Slag](#arcane-slag) and [Arcane Overheat](#arcane-overheat) it causes. 

## Testing Magic
[Testing](./strive-core.md#tests) a [magic school skill](#magic-school--school---attribute-), in order to cast a *magic spell*, works as follows:

1. Determine the [Spell Intensity](#spell-intensity-si) (SI) to use. 
   1. The level in the corresponding [magic school skill](#magic-school--school---attribute-) determines the maximum [SI](#spell-intensity-si) that can be picked. 
   1. Note that any spell **must** be cast with a [SI](#spell-intensity-si) of *at least* `1`. This includes **learning skills**. 
2. Determine the test's **Ob**. 
   1. Some spells require an [opposed test](./strive-core.md#opposed-test), while others impose a fixed **Ob** and yet others have a dynamic **Ob**, based on some formula. 
3. The dice for the test are rolled. 
4. Convert the [SI](#spell-intensity-si) to [Arcane Slag](#arcane-slag) and [Arcane Overheat](#arcane-overheat). This **always** happens *after* the spell is cast!
   1. If this brings the mage to a new [Arcane Overheat](#arcane-overheat) threshold, its effects now apply. 
5. Once the [time to cast](#casting-time) is up, the spell is cast!

## Spell Intensity (SI)
**Spell Intensity (SI)** is the strength at which a magic spell is being cast. A higher number causes stronger and further reaching effects, but also more [Arcane Slag](#arcane-slag) and [Arcane Overheat](#arcane-overheat). 

A spell's **maximum intensity** is dictated by the level in the corresponding [magic school skill](#magic-school--school---attribute-). However, the minimum **SI** for a spell cast is **always** `1`. 

When a mage casts magic, **one third** (RD and minimum `1`) of the [Spell Intensity](#spell-intensity-si) they choose equals the amount of [Arcane Slag](#arcane-slag) that builds up within them. The other half turns into [Arcane Overheat](#arcane-overheat). 

> = A spell cast at **SI** `1` causes `+1` **Arcane Slag** and *no* **Arcane Overheat**. 
> 
> = A spell cast at **SI** `3` causes `+1` **Arcane Slag** and `+2` **Arcane Overheat**. 
> 
> = A spell cast at **SI** `6` causes `+3` **Arcane Slag** and `+3` **Arcane Overheat**. 

## Arcane Overheat
Magic takes a toll on the caster's body and mind. As magic currents flow through their body, **Arcane Overheat** and [Arcane Slag](#arcane-slag) build up within them. Too much **Arcane Overheat**, and the mage will suffer various negative effects! 

When a mage casts magic, **one third** (RD and minimum `1`) of the [Spell Intensity](#spell-intensity-si) they choose equals the amount of [Arcane Slag](#arcane-slag) that builds up within them. The other half turns into [Arcane Overheat](#arcane-overheat). 

> = A spell cast at **SI** `1` causes `+1` **Arcane Slag** and *no* **Arcane Overheat**. 
> 
> = A spell cast at **SI** `3` causes `+1` **Arcane Slag** and `+2` **Arcane Overheat**. 
> 
> = A spell cast at **SI** `6` causes `+3` **Arcane Slag** and `+3` **Arcane Overheat**. 

[Arcane Slag](#arcane-slag) represents the base **Arcane Overheat** of a character, which can not be reduced as quickly as the more fleeting **Arcane Overheat**. Note that non-mages may be affected by this, too!

> A character with an **Arcane Slag** of `3`, always has at least `3` **Arcane Overheat**!

The [Arcana](#arcana-arc) attribute determines several thresholds. If the character has an [Arcana](#arcana-arc) level of less than `1`, calculate the thresholds as if it was level `1`. 

* **Cold**: Up to and including the `modified Arcana` is **mostly safe**. 
  * Every time the mage casts a spell, if they don't achieve at least `1` **hit**, a [Spell-Backfire](#spell-backfire) occurs. In other words, only a **complete failure** of the [test](#testing-magic) results in a [Spell-Backfire](#spell-backfire). 
* **Smoldering**: Up to and including the `modified Arcana * 2` is **risky**. 
  * Every time the mage casts a spell, their **Ob** is always increased by `+1`. Less than `2` **hits** causes a [Spell-Backfire](#spell-backfire). 
  * All spells are super-charged, with an automatic and free `+1` SI. 
* **Broiling**: Up to and including the `modified Arcana * 3` is **perilous**. 
  * The **Ob** for **all** tests is always increased by `+1`. Less than `3` **hits** causes a [Spell-Backfire](#spell-backfire). 
  * All spells are super-charged, with an automatic and free `+2` SI. 
* **Consuming**: Anything past the point of **Broiling** is **mortally perilous**. 
  * Suffer `1D8 + 2` [Pure damage](./strive-core.md#damage-types) every [Tick](./strive-core.md#ticks). At the end of every tick, reduces [Arcane Slag](#arcane-slag) and [Arcane Overheat](#arcane-overheat) by `-1` point, each. 
  * The **Ob** for **all** tests is always increased by `+2`. Less than `4` **hits** causes a [Spell-Backfire](#spell-backfire). 
  * All spells are super-charged, with an automatic and free `+3` SI. 

> The thresholds of a mage with an Arcana of `3` are: `0-3` Cold, `4-6` Smoldering, `7-9` Broiling and `10+` Consuming. 

At the start of every turn, or every `5` seconds outside combat, a mage automatically reduces their **Arcane Overheat** by one point. They can actively **vent** their **Arcane Overheat** further - one point per [AP](./strive-core.md#action-points-ap) spent. 

## Arcane Slag
**Arcane Slag** is the build-up of residual magical currents within the character's body. You can think of these like residual radioactive particles, that only slowly escape the body, albeit less immediately harmful. 

For every point of **Arcane Slag** that has built up within a character, their base [Arcane Overheat](#arcane-overheat) is increased by the same amount. They cannot reduce their [Arcane Overheat](#arcane-overheat) to less than this amount. 

When a mage casts magic, **one third** (RD and minimum `1`) of the [Spell Intensity](#spell-intensity-si) they choose equals the amount of [Arcane Slag](#arcane-slag) that builds up within them. The other two thirds turn into [Arcane Overheat](#arcane-overheat). 

> = A spell cast at **SI** `1` causes `+1` **Arcane Slag** and *no* **Arcane Overheat**. 
> 
> = A spell cast at **SI** `3` causes `+1` **Arcane Slag** and `+2` **Arcane Overheat**. 
> 
> = A spell cast at **SI** `6` causes `+2` **Arcane Slag** and `+4` **Arcane Overheat**. 

`1` point of **Arcane Slag** automatically leaves the character's body, every `6` hours. If that time is spent in active rest or meditation - that means doing *nothing* besides rest -, then `2` points leave the body, instead. 

**Arcane Slag** *can* affect non-mages, too! That implies they can also suffer [Arcane Overheat](#arcane-overheat) (although that does not make them mages)! 

## Casting Time
Usually, spells are cast immediately. Some spells may have an increased casting time, noted as `Time(+N)`, where *N* is the increase, in rounds. 

At the start of the mage's next turn, one increment of the casting time is considered elapsed. If by this, the time has elapsed fully and the spell is cast, the mage may still choose a different target, location or direction for their spell, as a means to adjust for changed battlefield conditions.

The casting of spells can be interrupted! Either automatically, if the mage is incapacitated, or when the mage is successfully *attacked*. If interrupted thusly, the spell fizzles harmlessly. 

## Spell-Backfire
A **Spell-Backfire** is a critical blunder of a mage! They suffer negative effects and their spell does not get cast the way they intended!

Usually, a spell notes the effects that happen when a Backfire occurs. In case there are no specific effects, the mage suffers `+1` point of [exhaustion](./strive-core.md#exhaustion). 

It is possible for another nearby mage to prevent the **spell-backfire**, if they [negate the spell](#magic-negation) as a **reaction**. This also applies even if the spell wouldn't affect them. If the other mage's attempt to negate the spell *also* **backfires**, then both of the mages suffer the spell's effect at one greater [intensity](#spell-intensity-si) level. 

A **spell-backfire** occurs in the following two cases: 
1. The [magic school skill test](#testing-magic) is a **complete failure**. 
2. The mage suffers from [Arcane Overheat](#arcane-overheat) and rolls a failure. 

## Concentration Spells
Some magic can be upheld for as long as the casting mage *concentrates* on their spell. Such spells will be marked with **"Concentration"**. The effects of a concentration spell last for as long as the mage *chooses* or *manages* to keep their concentration. They need only test for the spell only *once*, when they first cast it. 

Under normal circumstances, a mage can only upkeep **one** concentration spell at a time. 

Concentration can be broken! Either automatically, if the mage is incapacitated, or when the mage is *attacked*, they must succeed another test of their spell's magic school, at **Ob** equal to half (RU) of the chosen [SI](#spell-intensity-si). If concentration is broken, the spell ends. 

## Magic Negation
It is possible to negate a magical attack entirely, by using the same **school of magic** **skill** and achieving more **hits**, than the attacker. The defender has to perform a [test](#testing-magic) of the same magic school, at the **Ob** equal to the number of **hits + 1** the attacker achieved. The defender does not get to use a [expertise](./strive-core.md#expertise) of the magic school in question. This is a purely defensive action, which benefits everyone who might be hit with the spell of the attacker, as no one will be hit, if the defense is successful. 

If the defense fails, the full effect is applied. If the defense attempt causes a [spell-backfire](#spell-backfire) on the defender, they suffer the attacker's spell at one greater [intensity](#spell-intensity-si) level. 

**Magic negation** can also be used to prevent another mage's [spell-backfire](#spell-backfire).

## Protection From Magic
Armor made from [Ambersteel](#ambersteel) can reduce the damage suffered through magical sources and reduce the [SI](#spell-intensity-si) of non-damaging spells. 

The [Quality level](./strive-core.md#crafting--research-projects) of an armor or shield determines how much it protects the wearer. See [Ambersmithing](#ambersmithing-strwit) for the specific numbers. 

Damage from magical sources is reduced by the quality level + a number of dice. Non-damaging spells have their [SI](#spell-intensity-si) reduced by *only* the quality level. 

## Magic Echoes
Whenever magic is cast, a pale reflection of it remains, invisible to the naked eye, lingering for `SI * 4` hours, based on the magic spell's [intensity](#spell-intensity-si) when it was cast. 

Those sensitive to magic can detect it and if they know the [magic school](#magic-school--school---attribute-) whence the spell stems, they instinctively recognize the echo. Otherwise, they may need to succeed an [Arcana](#arcana-arc) test at Ob `2` to determine the type of magic that was cast. With another test, also at Ob `2`, they may also determine a rough estimate of how old the echo is. 

Each echo has a unique aspect to it, like a finger-print. It is possible to capture a magic echo's finger-print, as well as some of the context when it was cast, in special devices, called [Magic Recorders](#list-of-general-assets). 

## Magic Things
No fantasy world would be complete without materials with uses for the supernatural or artifacts of immense power. This section introduces the basics of these things. 

Aside from the materials listed below, you are of course free to invent more as desired. 

### Abyssalite
**Abyssalite** is a hard and brittle mineral, that has the ability to *amplify the flow of magic*. It can only be acquired from the depths of the earth and is fairly rare. 

Its surface is unnaturally smooth and covered in a fine, iridescent shine. Underneath the smooth surface, one searches for depth and color in vain. It is as though the void itself is being contained by that iridescent shell. However, the more magic flows through it, the stronger its shell shines. This means that when any magically gifted creature touches **Abyssalite**, it shines stronger. 

**Abyssalite** is a hard and brittle mineral, prone to shattering if too much force is applied. This makes it difficult to shape. It is also fairly heavy, which makes it difficult to carry. 

A fist-sized **Abyssalite** chunk has a [bulk](./strive-core.md#carrying-capacity) of 2 and grants one greater level in the respective [school of magic](#magic-school--school---attribute-), without causing any additional [Arcane Overheat](#arcane-overheat). In order to use the **Abyssalite**, the caster **must** be touching it. 

### Amberite
As magic is amplified by [Abyssalite](#abyssalite), its antithesis is called **Amberite**, a metal which dulls the effects of magic and slows any magic flow nearby it. The material is also known to affect magic creatures and can cause great pain in magic-users. 

Weapons made from **Amberite** are quite popular with witch and monster hunters alike, although fairly hard to come by, due to the difficulty in **Amberite** processing. 

**Amberite** is a crystalline material, that can be molten down and shaped, like iron. It glows weakly and translucently, in the fiery orange of the name-sharing amber stone. Near the edges, the glow fades to a dull reflection, like cooling molten lava. 

It only occurs naturally in a few select places in the world, where the ground offers the right conditions. **Amberite** grows over time, in the right environment. It can take several decades for a finger-sized crystal to grow to the size of an adult man's forearm. Attempts to cultivate it are met with extreme difficulty. The right conditions for it to thrive are highly dependent on the soil's components, the influence of the *arcanosphere* and proximity to volcanic activity. Due to the slow rate at which it grows, an **Amberite** farmer may not realize the lack of growth until well into a decade later. 

Prolonged exposure to **Amberite** can cause severe ill-effects with nausea and migranes being common symptoms. 

A fist-sized **Amberite** chunk is fairly heavy, with a [bulk](./strive-core.md#carrying-capacity) of 3. 

### Ambersteel
**Ambersteel** is a strictly anti-magic material. It should enjoy great attention in any fantasy world, where magic is a real and recognizable force. Magic is powerful and fearsome and thus, if not under control, can threaten to cause great pain and destruction. **Ambersteel** dampens that power and puts shackles on it. 

[Amberite](#amberite) can be processed into **Ambersteel**, which makes it a hard and flexible metal. The raw material heats slowly and must be heated over the course of several days and nights, without interruption. When it finally reaches the right temperature, it will glow white, with a purple sheen. At that point, it can be hammered into shape. Constant re-heating ensures it stays at the right temperature and a final quenching in oil mixed with powdered [Abyssalite](#abyssalite) ensures it retains its flexibility. If processed outside the optimal temperature, the material quickly grows brittle and will shatter if any stress is put on it. The skill to use is [ambersmithing](#ambersmithing-strwit). 

Due to the length of the process and the difficulty in keeping the right temperature, smiths capable of creating **Ambersteel** are rare. 

**Ambersteel** is also a fairly heavy material, albeit slightly lighter than [Amberite](#amberite). A fist-sized chunk has a [bulk](./strive-core.md#carrying-capacity) of 2. Weapons, shields and armor made from this material are +1 [bulkier](./strive-core.md#carrying-capacity). 

### Arcane Engine
A man-sized device that can channel and direct the power of a [Malevite Orb](#malevite) or [rune](#runes). Can be activated through [rune-using](#rune-using-agiwit). 

Arcane Engines are mostly useful either as siege engines or as stationary constant magic casters. 

### Cerebillium
**Cerebillium** is an odd material, that resembles white marble, with faintly glowing veins of green and turqoise running through it. This material is unique in that it always creates a small magical current on its own, which flows back and forth through the veins. 

These veins tend to grow more numerous over time and to "connect" with each other, forming an intricate web. This process is slow, however. It may take years for any significant change to become noticeable. 

These webs eventually become complex enough to form something of a "consciousness". Some of the oldest examples of **Cerebillium** slabs are said to have the intelligence of a small child!

When sufficient magic is sent flowing through it, the veins glow strongly and change shape, following the current. This can be used to alter the "brain". Alternate methods of altering the brain include scratching out veins, trimming the slab or - most difficult - "teaching". This process is difficult, as the **Cerebillium** consciousness is rarely advanced enough to understand morals or other subtle implications. Direct commands may work, but that depends on the density of the web. 

The veins do not spread to other materials. Only the bright marble-like substance seems to find their favor. Thus, cultivating greater amounts of **Cerebillium** is very difficult and requires synthesization of a very unique chemical compound, which is then left to crystallize over a long time. 

### Runes
Shards of [Abyssalite](#abyssalite) can be carved into **runes**, which allow magic to flow through them in particular ways. Mechanically, they allow the casting of a particular spell of one of the [schools of magic](#list-of-magic-schools), at a constant [Spell Intensity](#spell-intensity-si). 

To activate such a **rune**, is a difficult skill to learn, however. The **rune** must be touched in the right spots, at the right intervals, to activate successfully. Mistakes in this procedure can have disastrous results. 

It also takes great skill to carve **runes**, as each **rune's** shape and complexity depends in part on the size and shape of the [Abyssalite](#abyssalite) shard. The only way to get it right, is to *feel* the way the **rune** must be shaped. Alternatively, the shard can be adjusted to be of equivalent size and shape as another **rune**, but this requires considerable effort, as [Abyssalite](#abyssalite) is a brittle material, prone to shattering if too much force is applied. Thus, it must be carefully filed down to size. This would double the time it takes to [craft](#rune-smithing-arcwit) the **rune**.

Due to how **runes** are always magically charged, they cannot be in the vicinity of any other **runes**. This works a bit like how magnets with the same polarity repulse each other, but a lot more dangerous. This condition applies regardless of the type of magic each of the **runes** hold. If two **runes** are brought to a distance of `20` or less to each other, they begin to glow, hum and rumble, as if to warn their bearers. Should they be brought to a distance of `15` or less to each other, they both discharge the magic they hold and repulse each other. This means anyone immediately nearby suffers `3D6` **Bludgeoning** damage. The **runes** are flung away from each other far enough to be at least `21` apart. *Also*, the **runes** may be **destroyed** in the process. Roll a `D6` for each of the **runes** - if the result is a `1` or `2`, the **rune** is **destroyed**! 

It may be possible to circumvent this repulsion behavior by placing the **runes** in a container made of [Ambersteel](#ambersteel). This requires the container to be of a [Quality level](./strive-core.md#crafting--research-projects) equal to the highest of the **runes'** [Spell Intensity](#spell-intensity-si).

In order to craft a **rune**:
* A **rune** can only be made to cast one type of magic. So the carver has to pick one of the [magic schools](#list-of-magic-schools). 
* The maximum **level** at which a **rune** can be created, depends on the carver's skill. The **level** of the **rune** dictates the level of the respective magic it will cast at. 
* The carver has to succeed a [rune smithing](#rune-smithing-arcwit) skill test. 
* Then, the **rune** must be "primed" by a mage. This requires a **complete success** of a test of the same [school of magic](#list-of-magic-schools) as the **rune** holds, with **Ob** equal to the [Spell Intensity](#spell-intensity-si) of the **rune**. 
* If any of the tests are not a **complete success**, the **rune** is botched and the material cannot be used for another attempt. There is no room for mistakes. 

In order to invoke a **rune**:
* A **complete success** of a [rune-using](#rune-using-agiwit) skill test will invoke the spell of the **rune** as expected. This costs `2` AP in combat. 
* A **partial success** or **complete failure** results in a [spell-backfire](#spell-backfire). 
* The user accumulates one third (RD, but to no less than `1`) of the rune's [Spell Intensity](#spell-intensity-si) as [Arcane Slag](#arcane-slag). 

### Magic Scrolls
**Magic scrolls** allow a single, specific spell to be cast by both mages and non-mages. Once used, the **magic scroll** burns up from the flow of magic and cannot be used again (even if the bearer material is fire-proof). Thus, these are single-use tools. 

Due to how **magic scrolls** are always magically charged, they cannot be in the vicinity of any other **magic scrolls**. This works a bit like how magnets with the same polarity repulse each other, but a lot more dangerous. This condition applies *only* to **magic scrolls** of **same the type of magic**. 

If two **magic scrolls** **of the same type** are brought to a distance of `20` or less to each other, they begin to glow, hum and rumble, as if to warn their bearers. Should they be brought to a distance of `15` or less to each other, they both discharge the magic they hold and repulse each other. This means anyone immediately nearby suffers `3D6` **Bludgeoning** damage. The **magic scrolls** are destroyed in the process! 

It may be possible to circumvent this repulsion behavior by placing the **magic scrolls** in a container made of [Ambersteel](#ambersteel). This requires the container to be of a [Quality level](./strive-core.md#crafting--research-projects) equal to the highest of the **magic scrolls'** [Spell Intensity](#spell-intensity-si).

In order to create a **magic scroll**:
* Powdered [Abyssalite](#abyssalite) must be painted onto the parchment, paper or other such material, in a shape specific to the magic spell the **magic scroll** will be able to cast. 
  * This requires a **complete success** of an [artistry](./strive-core.md#artistry-agiawar) or [artificing](#artificing-arcwit) test, at **Ob** equal to the intended [Spell Intensity](#spell-intensity-si) of the **magic scroll**. 
* Then, the **magic scroll** must be "primed" by a mage. This requires a **complete success** of a test of the same [school of magic](#list-of-magic-schools) as the **magic scroll** holds, with **Ob** equal to the [Spell Intensity](#spell-intensity-si) of the **magic scroll**. 
* If any of the tests are not a **complete success**, the **magic scroll** is botched and the material cannot be used for another attempt. There is no room for mistakes. 

In order to invoke a **magic scroll**:
* One must unfurl and hold it plainly in the direction the spell is to be cast, then trace the painted symbol on the **magic scroll** to "agitate" the primed magic. This costs `2` AP in combat. 
* This causes no [Arcane Overheat](#arcane-overheat), but the **magic scroll** is immediately destroyed upon use. It burns up magically (even if the material itself is fire-proof). 

### Malevite
Also known as blood jewel, Malevite is an entirely artificial material, made from the blood of mages, by use of great pressure, a constant arcanic charge and much patience. The more blood it is infused with, the purer the color and more powerful the artifact. 

A blood jewel is a perfectly smooth sphere, with coloration ranging from a foggy and muddy black, to a swirly crimson or at its purest, to a radiant crimson.

Once formed, a Malevite orb can not be infused further. It rejects any more mage blood. 

Destroying such an artifact is not an easy feat. It requires a spike of pure [Ambersteel](#ambersteel) driven through it with great force. Doing so *may* tear a temporary hole in the fabric of reality. 

A Malevite orb is an artifact of very great power that can change the laws of physics and warp reality around it. To direct this power, requires an arcane apparatus, wherein the orb functions like a super-charged battery. To build such a device require a deep understanding of the arcane. When destroyed, the Malevite Orb de-compresses, releasing the blood it was made from in a spectacular hurricane of crimson. 

There are four quality levels. Impure Malevite has side-effects and is not nearly as powerful as a purer blood jewel. 

| Quality | Description | Side-Effects |
| ------- | ----------- | ------------ |
| Foggy   | Contains a single spell, at `SI 10`, which can only be controlled with an [Arcane Engine](#arcane-engine). | 3 |
| Murky   | Contains up to two spells, at `SI 30`, which can only be controlled with an [Arcane Engine](#arcane-engine). | 2 |
| Swirly  | Contains a weak reality-altering power, which can only be controlled with an [Arcane Engine](#arcane-engine). Can be almost anything, within reason. Things such as a low gravity field, anti-magic field, constant fog-emitter, elemental spewer and similar. | 1 |
| Pure    | Contains a reality-altering power. Practically anything is possible. The crowning achievement the power hungry and the insane. The closest you can get to god-hood. Requires no [Arcane Engine](#arcane-engine). It has transcended the need for such a paltry shackle. | 0 |

#### Malevite Side-Effects

All of the following is kept vague, because it would be hard to list all possible combinations in a way that makes sense while remaining concise. See the following as inspiration for the **GM**, who will finalize the side-effects. 

Side-effects (`2D6`):

| Roll | 1 Gravity               | 2 Time                   | 3 Souls                  | 4 Elemental              | 5 Psychic                | 6 Alteration             |
| ---- | ----------------------- | ------------------------ | ------------------------ | ------------------------ | ------------------------ | ------------------------ |
| 1    | High Gravity            | Slowed                   | Evicted                  | Acid                     | Terror                   | Create mutations         |
| 2    | Low Gravity             | Accelerated              | Attracted                | Frost                    | Confusion                | Restore purity           |
| 3    | Sideways Gravity        | Repeating                | Bound                    | Lightning                | Madness                  | Imbue with magic         |
| 4    | Attraction (Black-Hole) | Jump forward             | Evicted                  | Fire                     | Clairvoyance             | Nullify magic            |
| 5    | Repulsion               | Jump backward            | Attracted                | Light                    | Emotion cleanse          | Remove magic             |
| 6    | Anti-Gravity            | From alternate dimension | Bound                    | Sound                    | Pacified                 | Alter shape              |

Area of Effect (`1D4`): 

1. radius
2. wall
3. cone
4. line

Distance/radius `1D20 * 3`

Trigger (`1D6`):

1. Constant (no trigger, always active)
2. Periodic
   1. `1D4`: 1: Minutes, 2: Hours, 3: Days, 4: Weeks
   2. `1D100`: how many of the above
3. Vicinity `1D10 * 3` radius
4. Sound `1D4`: 1: Perfectly still, 2: Quiet, 3: Loud, 4: Deafening
5. Light `1D4`: 1: Perfectly dark, 2: Dim, 3: Bright, 4: Blinding
6. Blood

## Memorum
A unique material, grown by a very specific family of fungus that thrives only in the deepest recesses of the world. 

It has found practical use as a means of preserving the immaterial - thoughts, emotions, [magic echoes](#magic-echoes) and even raw knowledge. 

# The Veil
Whenever a psion uses their ability, they mentally reach out to the forces *beyond* The Veil, which causes **Veil Degradation**. When Veil Degradation becomes too great, strange and horrible things ensue. 

The limits for Veil Degradation are `0` and `100`. Unlike mages, who manage only their own resource, Veil Degradation is shared by **all** characters in the current scene and follows the psion wherever they go. It automatically lowers by `10` every `6` hour interval or resets to `0` when The Veil *shatters*. 

Whenever the psion uses their ability and Veil Degradation is above `0`, roll a percentile die (`2D10`, of which one is the "tenth" die and one is the "singles" die). If the result is above the current Veil Degradation, nothing happens. You were fortunate! But if it was below or equal to the current Veil Degradation, The Veil is lifted, momentarily. When that happens, one of the following effects ensue, based on the current Veil Degradation. Afterwards, Veil Degradation is lowered by `20`. However, if Veil Degradation reaches `100+`, the Veil *shatters*, causing it to reset to `0` and always results in a **Veil Entity** following the psion into their world.

As The Veil degrades, the very air begins to hum and buzz. There are voices on the wind, spoken in unfamiliar tongue and too subtle to hear. The light twists and occasionally shows visions from The Beyond, but too alien to comprehend. 

| Veil Degradation | Effect                              | 
| ---------------- | ----------------------------------- |
| 0-10             | Foreign doubts gnaw at the mind. All psions in the scene suffer `-1D` for their next test. |
| 11-20            | All psions in the scene are overcome with terror and rendered [Terrified](./strive-core.md#terrified). |
| 21-30            | Every creature in the scene is force moved in a random direction by `5`. |
| 31-40            | All psions in the scene suffer `+3` [Arcane Slag](#arcane-slag)! |
| 41-50            | Every creature in the scene suffers a random [illness](strive-core.md#illness). |
| 51-60            | Every creature in the scene suffers `+1` [Bleeding](strive-core.md#bleeding). |
| 61-70            | All characters in the scene suffer `+3` [Arcane Slag](#arcane-slag)! |
| 71-80            | Time reverses momentarily. The current round's initiative order reverses. Or outside combat, the last few minutes play back in reverse. |
| 81-90            | The flesh is malleable. All creatures in the scene suffer a random mutation. Or they could resist the transformation, and instead suffer `20` [pure](strive-core.md#damage-types) damage and `+2` [Bleeding](strive-core.md#bleeding)! |
| 91-100           | A *thing* from beyond The Veil is pulled through to your world. As a **GM**, see [Veil Entities](./strive-fantasy-game-masters-resource.md#veil-entities). |

# Assets
This section complements the same section from the [core rules](strive-core.md#assets).

## Weapon Properties
Weapon type assets can have the following **properties**:
* **Ambersteel-Lined**: Bonus damage against mages and magical creatures: **+1** for every quality level. **+1D4** for every two **quality levels**, starting at level 1.
* **Ambersteel-Plated**: Bonus damage against mages and magical creatures: **+1** for every quality level. **+1D6** for every two **quality levels**, starting at level 1.
* **Ambersteel-Forged**: Bonus damage against mages and magical creatures: **+2** for every quality level. **+1D8** for every two **quality levels**, starting at level 1.

# Appendix
The appendix contains important and less important lists, for reference only when needed. 

## Character Creation
Character creation is now supplemented by step `9` - [Determine Arcane Overheat thresholds](#arcane-overheat). 

The new procedure of creating a character consists of the following steps:
1. [Determine life path](./strive-core.md#determine-life-path). 
2. [Determine species, sex & appearance](./strive-core.md#species-sex--appearance).
3. [Determine name](./strive-core.md#determine-name).
4. [Determine abilities](./strive-core.md#determine-abilities).
6. [Determine **carrying capacity** and **assets**](./strive-core.md#determine-assets).
7. [Determine **Max HP** and **Injury Maximum**](./strive-core.md#determine-max-hp--injury-maximum)
8. [Determine exhaustion limit](./strive-core.md#determine-exhaustion-threshold).
9. [Determine Arcane Overheat thresholds](#determine-magic-overheat-thresholds).

### Determine Abilities
Supplements to abilities in character creation. 

#### Choosing Attributes
There are two methods for determining your character's attributes: manual and semi-random. 

You'll have to decide on whether your character will be a mage or not. Mages have the new, 6th attribute to spend points on, so this decision can affect your character's initial overall competence. 

Please keep in mind the values here are representative for an ordinary human about to enter an adventuring life. Other species may have modifiers on their attributes, making them better or worse in some of them. But that depends on the world your **GM** is running. 

This section replaces its core rule counter-part. 

##### Manual Attribute Assignment
1. Decide if you want to play a mage.
   1. As a mage, you **must** put at least `1` point into Arcana.
   2. As a non-mage, you **may not** put *any* points into Arcana.
2. The rest of the procedure follows the same steps as outlined in the [core rules](strive-core.md#manual-attribute-assignment), starting from step `1` therein. 

##### Semi-Random Attribute Assignment
1. Decide if you want to play a mage.
   1. As a mage, roll `6 D4` and **include** Arcana in the following steps. 
   2. As a non-mage, roll `5 D4` and **exclude** Arcana in the following steps. 
2. The rest of the procedure follows the same steps as outlined in the [core rules](strive-core.md#semi-random-attribute-assignment), starting from step `2` therein. 

#### Choosing Skills
If playing a **mage**, keep in mind you need to have at least level 1 in a [magic school skill](#magic-school--school---attribute-) to be able to cast magic. You are also advised to have your strongest magic be at least level 3 or 4, to be able to reliably use it. 

### Determine Arcane Overheat Thresholds
Determine your character's [Arcane Overheat thresholds](#arcane-overheat). 

## List of Assets
The following list does not and cannot aim to be a complete listing of all possible assets in game. Adding new assets as necessary will have to be done by the **GM**. 

### Armor

#### Armor Properties
Armor can have the following **properties**:
* **Ambersteel-Lined**: Bonus protection against magic. `+1` **Ob** for the attacker and reduces magic damage by `+1D4` for every quality level. 
* **Ambersteel-Plated**: Bonus protection against magic. `+1` **Ob** for the attacker and reduces magic damage by `+1D6` for every quality level. 
* **Ambersteel-Forged**: Bonus protection against magic. `+2` **Ob** for the attacker and reduces magic damage by `+1D8` for every quality level. 

> An **Ambersteel**-lined armor at quality level 3 would make magic attacks `+3` **Ob** harder for the attacker and reduces incoming magical damage by `3D4`. 

#### Light Armor
A set of light armor that doesn't impede the wearer much. Example: cloth armor like a gambeson. Might also be leather armor, if the leather comes from a creature whose skin is particularly tough and well suited to being used as armor. 

* Bulk: 2

| Protections          | Unthreatened | Flanked | Surrounded | Overwhelmed | 
| -------------------- | ------------ | ------- | ---------- | ----------- | 
| **Slashing**         | 8            | 4       | 2          | 0           | 
| **Piercing**         | 6            | 3       | 2          | 0           | 
| **Bludgeoning**      | 4            | 2       | 1          | 0           | 
| **Acid**             | 4            | 2       | 1          | 0           | 

#### Medium Armor
A set of medium armor with a good balance of protection and weight. Example: full chain mail armor, with or without a helmet. 

* Bulk: 3
* `+1` permanent [exhaustion](./strive-core.md#exhaustion) while worn. 
* `-1` to [stealth](./strive-core.md#stealth-agiawar) while worn. 
* `-1D` to any defense tests while worn. 

| Protections          | Unthreatened | Flanked | Surrounded | Overwhelmed | 
| -------------------- | ------------ | ------- | ---------- | ----------- | 
| **Slashing**         | 11           | 6       | 3          | 0           | 
| **Piercing**         | 9            | 5       | 3          | 0           | 
| **Bludgeoning**      | 7            | 4       | 2          | 0           | 
| **Acid**             | 7            | 4       | 2          | 0           | 
| **Electrical**       | 12           | 6       | 3          | 0           |

#### Heavy Armor
A set of heavy armor with excellent protection, at the cost of encumbering the wearer greatly. Example: full plate armor. 

* Bulk: 4
* `+2` permanent [exhaustion](./strive-core.md#exhaustion) while worn. 
* `-3` to [stealth](./strive-core.md#stealth-agiawar) while worn. 
* `-2D` to any defense tests while worn. 

| Protections          | Unthreatened | Flanked | Surrounded | Overwhelmed | 
| -------------------- | ------------ | ------- | ---------- | ----------- | 
| **Slashing**         | 15           | 8       | 4          | 0           | 
| **Piercing**         | 13           | 7       | 4          | 0           | 
| **Bludgeoning**      | 11           | 6       | 3          | 0           | 
| **Acid**             | 11           | 6       | 3          | 0           | 
| **Electrical**       | 12           | 6       | 3          | 0           | 

### Shield Types
Shields are items that provide passive bonuses to defense against melee and ranged attacks and require one free hand to use. This implies they cannot be used at the same time as a two-handed weapon (unless of course if you have more than two arms). 

Shields can only be used in defense tests via the [shield](core-rules.md#shield-strtough) skill.

##### Light Shield
A small round or oblong shield commonly held as far from the body as possible, to deflect small or stabbing weapons with ease. Helps only little against heavy blows and don't expect to deflect arrows with this, either. 

* Bulk: 1

| Unthreatened           | Flanked           | Surrounded           | Overwhelmed           |
| ---------------------- | ----------------- | -------------------- | --------------------- |
| `+1` [compensation point](core-rules.md#compensation-points) for melee defense. | `+1D` for melee defense. | / | / |
| `+2` [compensation points](core-rules.md#compensation-points) for melee defense against **stabbing** attacks. | `+2D` for melee defense against **stabbing** attacks. | `+1D` for melee defense against **stabbing** attacks. | / |
| `-1D` for ranged defense. | `-2D` for ranged defense. | `-2D` for ranged defense. | `-2D` for ranged defense. |

##### Medium Shield
A medium-sized, round or kite-shaped shield made from tough wood and leather or even metal, which offers good protection against most attacks, while not encumbering the wielder too much. 

* Bulk: 2
* `+1` permanent [exhaustion](./strive-core.md#exhaustion) while wielded. 

| Unthreatened           | Flanked           | Surrounded           | Overwhelmed           |
| ---------------------- | ----------------- | -------------------- | --------------------- |
| `+1` [compensation point](core-rules.md#compensation-points) for any defense. | `+1D` for any defense. | / | `-1D` for any defense. |

##### Heavy Shield
A large, kite-shaped or rectangular shield, which can protect every part of the fighter, from the shoulder down to the feet. Its weight is very tiring. 

* Bulk: 4
* `+2` permanent [exhaustion](./strive-core.md#exhaustion) while wielded. 

| Unthreatened           | Flanked           | Surrounded           | Overwhelmed           |
| ---------------------- | ----------------- | -------------------- | --------------------- |
| `+2` [compensation points](core-rules.md#compensation-points) for any defense. | `+1` [compensation point](core-rules.md#compensation-points) for any defense. | `+1D` for any defense. | / |

### List of General Assets
In the following table, `Q` refers to the quality grade of the asset. See also the [crafting](./strive-core.md#crafting--research-projects) rules. When in a hurry (as a **GM**), substitute the `Q` with `2`.

| Name                     | Bulk | Max. Stack Size | Description                                                              |
| ------------------------ | ---- | --------------- | ------------------------------------------------------------------------ |
| Acid Bomb                | 1    | 3               | A small fragile shell with two compartments, filled with two liquids which, when they combine, act as a powerful acid. When shattered, deals `QD6 Acid` damage to whatever it hits. |
| Blackpowder Bomb         | 1    | 2               | A small iron-shelled bomb, filled with blackpowder. A short fuse sticks out and must be lit to set it off. Once lit, the bomb will detonate after 3 turns or 15 seconds. Deals `QD4 Bludgeoning + QD4 Burning` damage to anyone in a `2` radius. |
| Calming Tea              | 1    | 3               | This herbal tea has the ability to calm nerves. Removes [berserk](./strive-core.md#berserk), [jealous](./strive-core.md#jealous) and [terrified](./strive-core.md#terrified). Best enjoyed steaming hot, but not necessarily. |
| Dragon's Breath Potion   | 1    | 3               | Upon drinking this potion, the orange liquid combines with the stomach acid and bursts out of the drinker's throat, igniting and thus causing them to spew fire! Causes `1D8 - Q Burning` damage to the user and `QD6 Burning` damage in a `6` cone in front of the user. |
| Death Fog                | 1    | 1               | An extremely rare and deadly gas. Once exposed to air, covers an area of `Q * 2` squares in impenetrable, eerily glowing, blue fog. Deals `6D10 + 40` **pure** damage to all **organic** things it touches, per tick. Metal and mineral are unaffected, while plant and flesh are struck from existence. |
| Fire Pot (Potion)        | 1    | 3               | An ancient recipe, this concoction bursts into flame when exposed to air for several seconds. It causes severe burns for `QD6 Burning` damage in a `2` radius. Consumed on use. |
| Illusionist's Powder     | 1    | 2               | A small amount of weakly iridescently shimmering powder. When scattered, the dust remains suspended in mid-air and settles in an image of the making alchemist's choosing, which at a distance can seem perfectly real. It takes a successful test at `Ob Q + 1` to see through the ruse. This image lasts `QD10` minutes. |
| Invigorating Potion      | 1    | 3               | The drinker of this potion feels refreshed and invigorated! Reduces exhaustion by `Q` and clears the [exhausted](./strive-core.md#exhausted) condition. Beware this potion can only be safely imbibed twice in a 24 hour cycle. If drunk more, roll a `D6`. If it is a **hit**, you're in luck! But if not, you instead suffer `+2` points of [exhaustion](./strive-core.md#exhaustion). |
| Laudanum Potion          | 1    | 2               | This wonderous substance can quell pain and calm nerves within seconds. Also effective against diarrhea. Upon imbibing, sets one **active** [injury](./strive-core.md#injury) to **treated**. After 24 hours, the [injury](./strive-core.md#injury) is set back to **active**, even if it was also properly **treated** in the meantime. Also, must succeed a [self-control](./strive-core.md#self-control-toughtough) test at `Ob 3`, or else become [addicted](./strive-core.md#drug-addicted) to the stuff. |
| Love Potion              | 1    | 2               | Anyone drinking this potion will become virtually irresistible to anyone close enough to smell their air. Victims have to succeed a [self-control](./strive-core.md#self-control-toughtough) test at **Ob** `Q` or else feel **very strongly compelled** to fulfill the user's every wish and desire (provided this wouldn't obviously cause harm to the victim). |
| Magic Recorder           | 1    | 3               | A small spherical device, overtly made from various metals with intricate patterns on its surface. This device can capture [Magic Echoes](#magic-echoes) and record magic as it is being cast. Also captures fragments of thoughts from its bearer while it is active. |
| Night-Eye Potion         | 1    | 3               | Grants the ability to see reasonably well under low-light conditions, up to `Q * 3` around them, for an hour. Beware that under the influence of this potion, exposure to bright light is extremely difficult to endure and will cause `+1` [exhaustion](./strive-core.md#exhaustion) for every **minute** of exposure. |
| Paralyzing Poison        | 1    | 2               | Causes a victim's muscles to seize up. They suffer `-1 AP` each turn and are forced to move sluggishly. If this poison is suffered twice, the victim seizes up completely and is unable to move. This poison can be resisted once upon suffering it, with [toughness](./strive-core.md#toughness-tough), at `Ob Q`. If unsuccessful, the effect will last `Q` hours. |
| Poison Resistance Potion | 1    | 2               | Once imbibed, halves all incurred poison damage, for up to `Q` hours. |
| Sleeping Poison          | 1    | 3               | Causes a victim to feel incredibly sleepy. Unless they succeed a [self-control](./strive-core.md#self-control-toughtough) test at `Ob Q`, they will fall asleep the first chance they get. They cannot be woken from this state for at least `6` hours. |
| Smoke Bomb               | 1    | 3               | A small fragile shell, filled with a very fine powder which when broken causes an area in a `Q * 1` radius to be covered in smoke. It is impossible to see through and ranged attacks within or through the smoke-covered area suffer `+2` **Ob**. Victims caught in the smoke may be forced to cough. The smoke lasts `6` turns or `30` seconds. |
| Throwing Blade           | 1    | 6               | A small weighted blade, like a knife or star, well suited to being thrown. Can be used in melee and acts like a [dagger](#dagger-agiawar), but with a penalty of `-2D` to attack and defense. `+1D` when [thrown](./strive-core.md#throwing-accuracy) for a ranged attack. Deals `2D4 + Str piercing` damage. |

### Weapon Types
Following are fantasy-themed weapon types. 

For ranged weapons there is note made of a value called the "distance increment". This describes the distance within which the weapon can be used optimally, for no penalty to **Ob** and damage. As soon as a shooter wants to hit a target past their initial (= optimal) distance increment, they incur a penalty as noted on the attack in question. This penalty is multiplied by every increment past the initial. 

> For example, when a distance increment of 10 has been noted, then shooting anything within and up to that distance incurs no penalties. But as soon as the shooter wants to hit something at 11 distance, they incur their first penalty. The next penalty is incurred at 21 and so on. 

#### Dagger (Agi/Awar)
Any very short, one-handed blade. Examples: shiv, dagger, rondel-dagger

For all attacks made with a dagger, the following rules apply:
* If the target is unaware or [grappled](./strive-core.md#grappled), then the target's armor does **not** reduce the dagger's damage.
* `-1 Ob` against [proned](./strive-core.md#prone) and/or [grappled](./strive-core.md#grappled) targets.

* Melee
* Bulk: 1
* Ranged (throwable: stab)

| Level | Name                 | AP | **Ob**      | Damage                           | Notes  |
| ----- | -------------------- | -- | ----------- | -------------------------------- | ------ |
| 0     | Slash                | 2  | Opposed     | `1D4 + Agi` Slashing             | / |
| 0     | Stab                 | 2  | Opposed     | `1D6 + Agi` Piercing             | / |
| 0     | Artery Cut           | 2  | Opposed + 1 | `1D6 + Agi` Slashing             | +2 [bleeding](./strive-core.md#bleeding) to the target (if it can bleed).  |
| 0     | Target Weak-Spot     | 2  | Opposed + 2 | `1D8 + Agi` Pure                 | / |

#### Light Blade (Agi/Str)
Any light blade. Most commonly (but not restricted to) one-handed weapons. Examples: short-sword, Langes Messer, arming sword, falchion, saber

* Melee
* Bulk: 1
* Ranged (throwable: stab)

| Level | Name                 | AP | **Ob**      | Damage                           | Notes  |
| ----- | -------------------- | -- | ----------- | -------------------------------- | ------ |
| 0     | Slash                | 2  | Opposed     | `1D6 + 2 + Str` Slashing             | / |
| 0     | Stab                 | 2  | Opposed     | `1D4 + 2 + Agi` Piercing             | / |
| 0     | Grappling Feint      | 2  | Opposed - 1 | /                                | Attack with a feint, immediately close the distance and [grapple](./strive-core.md#grappled) your opponent. |

#### Long Blade (Agi/Str)
Any long and heavier blade, including heavy one-handed blades. Examples: longsword, rapier, Kriegsmesser

* Melee
* Bulk: 2

| Level | Name                 | AP | **Ob**      | Damage                           | Notes  |
| ----- | -------------------- | -- | ----------- | -------------------------------- | ------ |
| 0     | Slash                | 2  | Opposed     | `1D8 + Str` Slashing             | / |
| 0     | Stab                 | 2  | Opposed     | `1D6 + Agi` Piercing             | / |
| 2     | Mord-Strike          | 2  | Opposed     | `1D6 + Str` Bludgeoning          | / |
| 3     | Fencer-Stance        | 3  | /           | /                                | Enter a defensive fencing stance. Gain `+1D` for melee defense and can [counter-attack](./strive-core.md#defense-stunts) **every** attack, until the start of your next turn, at no additional AP cost. |

#### Great Blade (Str/Tough)
Any very long and heavy two-handed blade. Examples: great-sword, sword of war, great-saber

* Melee
* Bulk: 3
* [Long Reach](core-rules.md#weapon-properties)

| Level | Name                 | AP | **Ob**      | Damage                           | Notes  |
| ----- | -------------------- | -- | ----------- | -------------------------------- | ------ |
| 0     | Slash                | 2  | Opposed     | `2D6 + Str` Slashing             | / |
| 0     | Stab                 | 2  | Opposed     | `1D8 + Agi` Piercing             | / |
| 2     | Blade Barrier        | 2  | Opposed     | /                                | Whenever any character moves **into** a spot within reach, can attack that character with a **slash** at `Ob + 1` and always force them back `1`, until the start of your next turn. These attacks do not cost any additional **AP**. |
| 3     | Heavy Blow           | 3  | Opposed + 2 | `1D6` Slashing + `Strength` Bludgeoning | Defending against this attack costs 2 [AP](./strive-core.md#action-points-ap). Causes `+1` Exhaustion to self. If successful, the target is knocked Prone. |

#### Chained-Blade (Agi)
A down-angled, weighted blade, with a spike forwards, perfect for throwing and connected to a very light chain or rope, for easy retrieval. 

This weapon requires masterful precision and rewards its user with great versatility. 

Requires knowing [Acrobatics](#acrobatics-agistr) and another bladed [weapon skill](#weapon--weapon-type---attribute-), each at least at level 3. 

* Melee
* Ranged
* Bulk: 3
* All ranged attacks [Prefer Range](core-rules.md#weapon-properties)

| Level | Name                 | AP | **Ob**      | Max. Distance       | Damage                           | Notes  |
| ----- | -------------------- | -- | ----------- | ------------------- | -------------------------------- | ------ |
| 0     | Curved Toss          | 2  | Opposed     | 8              | `1D6 + Agi` Slashing    | Throw the weapon just past a target and then with a flick, make it jump at their back and upon impact, immediately retrieve it. |
| 0     | Slash                | 2  | Opposed     | 1               | `1D4 + Str` Slashing    | Slash at an adjacent **ST**. |
| 0     | Whip                 | 2  | Opposed     | 8              | `1D4 + Str` Bludgeoning | Swing the chain at a target and whip it with it, then immediately retrieve it. Causes `+1` [Exhaustion](strive-core.md#exhaustion) in the target. |
| 1     | Come Closer          | 2  | Opposed     | 8              | `1D4` Slashing          | Throw the weapon just past a target and then yank it back, catching them with it and pulling them `3` closer to you. If the target is much larger and/or heavier than you, then you may pull *yourself* closer to them, for the same distance. Then immediately retrieve your weapon. |
| 3     | Leg Sweep            | 2  | Opposed     | 8              | /                       | Swing the weapon at length and low, to sweep for an opponent's legs. Upon impact, yank the chain to sweep them off their feet, rendering them [prone](./strive-core.md#prone) and then immediately retrieve your weapon. |
| 4     | Think Twice          | 1  | /           | 8              | `Agi` Piercing    | **Reaction**: Upon one of your allies attacking an enemy, you also throw your weapon straight at that enemy. Your ally's attack is `-1` Ob easier as the enemy is confused by the two simultaneous attacks! Your attack does **not** cost the enemy any additional AP to defend and is successful only if your ally's attack is successful. Upon impact, immediately retrieve your weapon. Only possible once per round. |

#### Axe (Str/Str)
Small and light axes. Examples: hatchet, woodcutter's axe

* Melee
* Bulk: 1
* Ranged (throwable: hack)

| Level | Name                 | AP | **Ob**      | Damage                                    | Notes  |
| ----- | -------------------- | -- | ----------- | ----------------------------------------- | ------ |
| 0     | Hack                 | 2  | Opposed     |  `1D6` Slashing + `1D4 + Str` Bludgeoning | / |
| 1     | Savage Slash         | 2  | Opposed + 1 |  `1D8` Slashing                    | `+2` [Bleeding](./strive-core.md#bleeding) to the target (if it can bleed). |

#### Great Axe (Str/Str)
Large and heavy axes. Examples: bearded axe, double-sided axe

* Melee
* Bulk: 3

| Level | Name                 | AP | **Ob**      | Damage                                           | Notes  |
| ----- | -------------------- | -- | ----------- | ------------------------------------------------ | ------ |
| 0     | Hack                 | 2  | Opposed     | `1D6` Slashing + `1D6 + Str` Bludgeoning        | / |
| 1     | Heavy Blow           | 3  | Opposed + 2 | `1D10` Slashing + `Str` Bludgeoning  | Defending against this attack costs 2 [AP](./strive-core.md#action-points-ap). Causes `+1` Exhaustion to self. If successful, the target is knocked Prone. |

#### Spear (Agi/Str)
Any one or two-handed short piercing polearms. Examples: short-spear, boar-spear

* Melee
* Bulk: 2
* Ranged (throwable: stab)
* [Long Reach](core-rules.md#weapon-properties)

| Level | Name                 | AP | **Ob**      | Damage                           | Notes  |
| ----- | -------------------- | -- | ----------- | -------------------------------- | ------ |
| 0     | Stab                 | 2  | Opposed     | `2D4 + Agi` Piercing             | / |
| 0     | Spear Wall           | 2  | /           | /                                | Whenever any character moves **into** a spot within reach, can attack that character with a **Stab** at `Ob + 1` and if successful, force them back `1`, until the start of your next turn. The attacks cost no additional **AP**. |

#### Lance (Awar/Str)
Any one or two-handed long piercing polearms. Examples: pike, lance

* Melee
* Bulk: 4
* [Long Reach](core-rules.md#weapon-properties)
* [Prefer Range](core-rules.md#weapon-properties)

| Level | Name                 | AP | **Ob**      | Damage                           | Notes  |
| ----- | -------------------- | -- | ----------- | -------------------------------- | ------ |
| 0     | Stab                 | 2  | Opposed     | `2D4 + Agi` Piercing             | / |
| 0     | Couched Lancing      | 2  | Opposed     | `3D10` Piercing                  | Requires self to be mounted on horse-back (or similar creature). Self must move at least 5 in a straight line, past the target. |

#### Polearm (Str/Tough)
Flexible polearms with a focus on slashing. Examples: halberd, bardiche, poleaxe

* Melee
* Bulk: 4
* [Long Reach](core-rules.md#weapon-properties)
* [Prefer Range](core-rules.md#weapon-properties)

| Level | Name                 | AP | **Ob**      | Damage                           | Notes  |
| ----- | -------------------- | -- | ----------- | -------------------------------- | ------ |
| 0     | Slash                | 2  | Opposed     | `2D6 + Str` Slashing             | / |
| 0     | Stab                 | 2  | Opposed     | `2D4 + Agi` Piercing             | / |
| 1     | Blade Barrier        | 2  | /           | /                                | Whenever any character moves **into** a spot within reach, can attack that character with a **stab** at `Ob + 1` and always force them back `1`, until the start of your next turn. The attacks cost no additional **AP**. |
| 2     | Cleave               | 2  | Opposed + 2 | `2D8 + Str` Slashing             | Deals damage to up to two targets adjacent to each other and within reach. |

#### Small Crusher (Str/Tough)
Small bludgeoning weapons. Examples: any improvised weapon, any club, any mace

* Melee
* Bulk: 2

| Level | Name                 | AP | **Ob**      | Damage                           | Notes  |
| ----- | -------------------- | -- | ----------- | -------------------------------- | ------ |
| 0     | Smash                | 2  | Opposed     | `1D6 + Str` Bludgeoning          | / |
| 0     | Knockout Blow        | 2  | Opposed + 1 | `1D4 + Str` Bludgeoning          | If successful, causes `+2` [exhaustion](./strive-core.md#exhaustion) to the target. |

#### Large Crusher (Str/Tough)
Large bludgeoning weapons with a dedicated *impact zone* on the weapon head which directs more force into the target. Examples: grand-mace, polehammer, two-handed flail

* Melee
* Bulk: 3

| Level | Name                 | AP | **Ob**      | Damage                           | Notes  |
| ----- | -------------------- | -- | ----------- | -------------------------------- | ------ |
| 0     | Smash                | 2  | Opposed     | `1D8 + Str` Bludgeoning     | / |
| 0     | Mighty Smash         | 2  | Opposed + 2 | `1D10 + Str` Bludgeoning     | Defending against this attack costs `2` [AP](./strive-core.md#action-points-ap) and causes `+1` [Exhaustion](./strive-core.md#exhaustion) to the target. |

#### Short-Bow (Awar/Awar)
A short distance ranged weapon, shooting arrows.

* Ranged: For every attack: `+1` **Ob** and `-1` damage for every distance increment past the initial.
* Bulk: 1
* [Range Only](core-rules.md#weapon-properties)

| Level | Name                 | AP | **Ob**      | Distance increments | Damage                     | Notes  |
| ----- | -------------------- | -- | ----------- | ------------------- | -------------------------- | ------ |
| 0     | Loose                | 2  | Opposed     | 10             | `2D4` Piercing             | / |
| 1     | Pin                  | 2  | Opposed     | 10             | `1D4 + 2` Piercing             | Shoot the enemy in their foot. If the attack is successful, they target is considered [Rooted](./strive-core.md#rooted) until the end of their next turn. |
| 2     | Double Shot          | 3  | Opposed + 1 | 10             | `2D4` Piercing             | Can attack twice and thus deal its damage to two different targets, or the same target twice.  |

#### Longbow (Awar/Str)
A long distance ranged weapon, shooting arrows.

* Ranged: For every attack: `+1` **Ob** and `-1` damage for every distance increment past the initial.
* Bulk: 2
* [Range Only](core-rules.md#weapon-properties)

| Level | Name                 | AP | **Ob**      | Distance increments | Damage                     | Notes  |
| ----- | -------------------- | -- | ----------- | ------------------- | -------------------------- | ------ |
| 0     | Loose                | 2  | Opposed     | 15             | `2D6` Piercing             | / |
| 1     | Heavy Shot           | 3  | Opposed     | 15             | `2D6 + Str` Piercing       | Causes `+1` [Exhaustion](./strive-core.md#exhaustion) to self. |

#### War-Bow (Str/Tough)
A very deadly long distance ranged weapon, shooting arrows. Beware its exhausting strength of draw. 

* Ranged: For every attack: `+1` **Ob** and `-1` damage for every distance increment past the initial.
* Bulk: 2
* [Range Only](core-rules.md#weapon-properties)

| Level | Name                 | AP | **Ob**      | Distance increments | Damage                     | Notes  |
| ----- | -------------------- | -- | ----------- | ------------------- | -------------------------- | ------ |
| 0     | Loose                | 2  | Opposed     | 20             | `2D10` Piercing            | Causes `+1` [Exhaustion](./strive-core.md#exhaustion) to self.  |

#### Crossbow (Awar/Awar)
A deadly medium distance ranged weapon, shooting quarrels. Beware its slow reload. 

* Ranged: For every attack: `+1` **Ob** and `-1` damage for every distance increment past the initial.
* Bulk: 2
* [Prefer Range](core-rules.md#weapon-properties)
* [Slow Reload](core-rules.md#weapon-properties)

| Level | Name                 | AP | **Ob**      | Distance increments | Damage                     | Notes  |
| ----- | -------------------- | -- | ----------- | ------------------- | -------------------------- | ------ |
| 0     | Loose                | 2  | Opposed     | 20             | `3D8` Piercing             | / |

#### Firearm (Awar/Awar)
A very deadly short to medium distance ranged weapon, shooting musket balls that are likely to penetrate armor. Beware its slow reload. 

* Ranged: For every attack: `+1` **Ob** and `-1` damage for every distance increment past the initial.
* Bulk: 2
* [Prefer Range](core-rules.md#weapon-properties)
* [Very Slow Reload](core-rules.md#weapon-properties)

| Level | Name                 | AP | **Ob**      | Distance increments | Damage                     | Notes  |
| ----- | -------------------- | -- | ----------- | ------------------- | -------------------------- | ------ |
| 0     | Fire                 | 2  | Opposed     | 10             | `2D10 + Awar` Piercing     | / |

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

[Crafting](./strive-core.md#crafting--research-projects)

| Product                              | Progress Increment | Time Increment |
| ------------------------------------ | ------------------ | -------------- |
| 1 [light armor](#light-armor)        | 20                 | 6 Hours        |
| 1 [medium armor](#medium-armor)      | 30                 | 6 Hours        |
| 1 [heavy armor](#heavy-armor)        | 40                 | 6 Hours        |

#### Ambersmithing (Str/Wit)
The ability to make things from [Amberite](#amberite). 

[Crafting](./strive-core.md#crafting--research-projects)

**Tools**: Specialized

Plating an existing object with [Ambersteel](#ambersteel) acts as an improvement, whereas an [Ambersteel](#ambersteel)-forged object is an entirely new object, completely made out of this material. Improvement effects do not stack. 

| Product                              | Progress Increment | Time Increment | Materials                                 | Quality Bonus   |
| ------------------------------------ | ------------------ | -------------- | ----------------------------------------- | --------------- | 
| Ambersteel-plated weapon             | 40                 | 6 Hours        | [Ambersteel](#ambersteel); A weapon       | Bonus damage against mages and magical creatures: **+1** for every quality level. **+1D6** for every two **quality levels**, starting at level 2. |
| Ambersteel-forged weapon             | 50                 | 6 Hours        | [Ambersteel](#ambersteel)                 | Bonus damage against mages and magical creatures: **+2** for every quality level. **+1D8** for every two **quality levels**, starting at level 2. The weapon is +1 **bulkier** than an equivalent weapon that is not **Ambersteel** forged. |
| Ambersteel-plated armor              | 60                 | 6 Hours        | [Ambersteel](#ambersteel); A set of armor | Bonus protection from magic: **+1** for every quality level. **+1D6** for every two **quality levels**, starting at level 2. |
| Ambersteel-forged armor              | 85                 | 6 Hours        | [Ambersteel](#ambersteel)                 | Bonus protection from magic: **+2** for every quality level. **+1D8** for every two **quality levels**, starting at level 2. The armor is +1 **bulkier** than an equivalent armor that is not **Ambersteel** forged. |
| Ambersteel-plated shield             | 50                 | 6 Hours        | [Ambersteel](#ambersteel); A shield       | Bonus protection from magic: **+1** for every quality level. **+1D6** for every two **quality levels**, starting at level 2. |
| Ambersteel-forged shield             | 70                 | 6 Hours        | [Ambersteel](#ambersteel)                 | Bonus protection from magic: **+2** for every quality level. **+1D8** for every two **quality levels**, starting at level 2. The shield is +1 **bulkier** than an equivalent shield that is not **Ambersteel** forged. |

#### Alchemy (Arc/Wit)
The ability to brew alchemical potions, create powders, mixtures and other substances, as well as the ability to tell these things apart. 

[Crafting](./strive-core.md#crafting--research-projects)

**Tools**: a distillery, mortar and pestle, a heat source, beakers

For every `Q` past `2`, choose one of the following:
* Gain `+1` amount of your product. 
* Gain a secondary product whose Progress Increment is smaller, with amount `1`. 

| Product                              | Progress Increment | Time Increment | Ob |
| ------------------------------------ | ------------------ | -------------- | -- |
| Acid Bomb (3)                        | 10                 | 1 Hour         |    |
| Blackpowder Bomb (2)                 | 20                 | 1 Hour         | +1 |
| Calming Tea (3)                      | 10                 | 10 Minutes     |    |
| Death Fog (1)                        | 50                 | 6 Hours        | +2 |
| Dragon's Breath Potion (2)           | 20                 | 1 Hour         | +1 |
| Fire Pot (2)                         | 20                 | 1 Hour         | +1 |
| Illusionist's Powder (2)             | 30                 | 10 Minutes     | +1 |
| Invigorating Potion (2)              | 20                 | 1 Hour         |    |
| Laudanum Potion (3)                  | 10                 | 1 Hour         |    |
| Love Potion (1)                      | 20                 | 1 Hour         | +1 |
| Night-Eye Potion (2)                 | 10                 | 1 Hour         |    |
| Paralyzing Poison (1)                | 50                 | 6 Hours        | +1 |
| Poison Resistance Potion (2)         | 20                 | 1 Hour         | +1 |
| Sleeping Poison (1)                  | 30                 | 1 Hour         | +1 |
| Smoke Bomb (3)                       | 10                 | 10 Minutes     |    |

#### Brewing (Wit/Wit)
The brewing of alcoholic beverages. 

[Crafting](./strive-core.md#crafting--research-projects)

**Tools**: a heat source, a distillery, barrels or caskets for fermenting

| Product                              | Progress Increment | Time Increment |
| ------------------------------------ | ------------------ | -------------- |
| A small keg worth of alcohol         | 30                 | 1 Day          |

#### Blacksmithing (Agi/Str)
The ability to create every-day items from metal. 

[Crafting](./strive-core.md#crafting--research-projects)

**Tools**: a hammer, an anvil or other resilient surface, tongs, a forge

The achieved `Q` dictates the possible size, amount and complexity of the crafted object(s). 

| Product                              | Progress Increment | Time Increment |
| ------------------------------------ | ------------------ | -------------- |
| Metal product(s)                     | 20                 | 6 Hours        |

#### Bow-Making (Agi/Awar)
The ability to craft bows and crossbows. 

[Crafting](./strive-core.md#crafting--research-projects)

**Tools**: a carving knife

| Product                              | Progress Increment | Time Increment |
| ------------------------------------ | ------------------ | -------------- |
| Bow                                  | 20                 | 1 Hour         |
| Crossbow                             | 30                 | 1 Hour         |

#### Carpentry (Agi/Str)
The ability to shape wood to craft predominantly wooden things. 

[Crafting](./strive-core.md#crafting--research-projects)

**Tools**: an axe, a wood plane, a hand drill, a workbench

The achieved `Q` dictates the possible size, amount and complexity of the crafted object(s). 

| Product                              | Progress Increment | Time Increment |
| ------------------------------------ | ------------------ | -------------- |
| A piece of furniture                 | 30                 | 6 Hours        |

#### Clothesmaking (Agi/Wit)
The ability to make comfortable, well-fitting and decorated clothes. 

[Crafting](./strive-core.md#crafting--research-projects)

**Tools**: scissors, needles, yarn, thread

| Product                              | Progress Increment | Time Increment |
| ------------------------------------ | ------------------ | -------------- |
| A piece of clothing                  | 30                 | 6 Hours        |

#### Engineering (Agi/Wit)
The ability to plan and construct complex mechanisms and devices. 

[Crafting](./strive-core.md#crafting--research-projects)

The achieved `Q` dictates the possible size, amount and complexity of the crafted object(s). 

| Product                              | Progress Increment | Time Increment |
| ------------------------------------ | ------------------ | -------------- |
| A mechanism                          | 40                 | 1 Hour         |

#### Fletching (Agi/Awar)
The ability to efficiently craft arrows, bolts and javelins. 

[Crafting](./strive-core.md#crafting--research-projects)

**Tools**: a carving knife, a brush

For every `Q` past `1`, you get the amount of ammunition you already produced, as *additional* products. 

| Product                              | Progress Increment | Time Increment |
| ------------------------------------ | ------------------ | -------------- |
| 10 Arrows/Bolts                      | 30                 | 10 Minutes     |

#### Glass-Blowing (Agi/Agi)
The ability to make objects from glass. 

[Crafting](./strive-core.md#crafting--research-projects)

**Tools**: a fire place, a glass-blower, various shaping tools

| Product                              | Progress Increment | Time Increment |
| ------------------------------------ | ------------------ | -------------- |
| A glass object                       | 50                 | 1 Hour         |

#### Goldsmithing (Agi/Agi)
The ability to make jewelry from precious metals and stones. 

[Crafting](./strive-core.md#crafting--research-projects)

**Tools**: hammers, tweezer, chisels, a workbench, magnifying glasses

| Product                              | Progress Increment | Time Increment |
| ------------------------------------ | ------------------ | -------------- |
| Jewelry                              | 50                 | 1 Hour         |

#### Leatherworking (Agi/Wit)
The ability to create leather objects. 

[Crafting](./strive-core.md#crafting--research-projects)

**Tools**: scissors, needles, hole punchers and a hammer

| Product                              | Progress Increment | Time Increment |
| ------------------------------------ | ------------------ | -------------- |
| Leather object                       | 20                 | 1 Hour         |

#### Masonry (Str/Tough)
The ability to shape stone to craft predominantly stone-based things. 

[Crafting](./strive-core.md#crafting--research-projects)

**Tools**: a hammer and chisels of varying sizes

| Product                              | Progress Increment | Time Increment |
| ------------------------------------ | ------------------ | -------------- |
| A stone-hewn object                  | 50                 | 1 Hour         |

#### Rune-Smithing (Arc/Wit)
The ability to carve [magic runes](#runes) and embed them in arcane devices.

The level of this skill dictates the maximum [intensity](#spell-intensity-si) of the respective magic the carved rune can hold. The number of **hits** achieved in a test then sets the actual level the rune will hold, but limited by the maximum. 

[Crafting](./strive-core.md#crafting--research-projects)

**Tools**: a hammer and chisels of varying sizes, tongs, tweezer, a fine brush

| Product                                   | Progress Increment | Time Increment | Ob | Materials                              | Quality Bonus   |
| ----------------------------------------- | ------------------ | -------------- | -- | -------------------------------------- | --------------- | 
| A blank rune                              | 50                 | 1 Hour         | /  | [Abyssalite](#abyssalite)              | / |
| A magic rune                              | 50                 | 1 Hour         | +1 | A blank rune; thin-leaf metal          | +1 [spell intensity level](#magic) |
| [Magic Recorder](#list-of-general-assets) | 50                 | 1 Hour         | +1 | 1 bulk of [Abyssalite](#abyssalite); 1 bulk of [Ambersteel](#ambersteel); 1 bulk of [Memorum](#memorum); any other, malleable metal | / |

#### Shield-Making (Str/Wit)
The ability to make shields from conventional materials, such as wood and metal. 

[Crafting](./strive-core.md#crafting--research-projects)

**Tools**: axes, hammers, tongs, (if metal) a forge and anvil

**Resources**: Any shapeable sturdy and flexible material

| Product                              | Progress Increment | Time Increment | Quality Bonus   |
| ------------------------------------ | ------------------ | -------------- | --------------- | 
| 1 [light shield](#light-shield)      | 30                 | 1 Hour         | / |
| 1 [medium shield](#medium-shield)    | 40                 | 1 Hour         | For every 3 quality levels, starting at level 2, reduction of bulk by 1 (to a minimum of 1). |
| 1 [heavy shield](#heavy-shield)      | 50                 | 1 Hour         | For every 3 quality levels, starting at level 2, reduction of bulk by 1 (to a minimum of 2). |

#### Tanning/Skinning (Agi/Tough)
Taking the hide off a creature undamaged. 

[Crafting](./strive-core.md#crafting--research-projects)

**Tools**: a knife, a scraping blade, a bucket, a brush

| Product                              | Progress Increment | Time Increment | Materials                              | Quality Bonus   |
| ------------------------------------ | ------------------ | -------------- | -------------------------------------- | --------------- | 
| A small skin                         | 10                 | 10 Minutes     | A skinnable creature                   | / |
| A large skin                         | 20                 | 10 Minutes     | A skinnable creature                   | / |
| A tanned hide                        | 20                 | 6 Hours        | A tannable skin                        | / |

#### Weapon Smithing (Str/Wit)
The ability to make weapons from metal. 

[Crafting](./strive-core.md#crafting--research-projects)

**Tools**: a hammer, an anvil or other resilient surface, tongs, a forge

| Product                              | Progress Increment | Time Increment | Materials                              | Quality Bonus   |
| ------------------------------------ | ------------------ | -------------- | -------------------------------------- | --------------- | 
| A weapon                             | 50                 | 1 Hour         | Any suitable metal, wood and/or similar material | / |

#### Woodcarving (Agi/Agi)
Creating small things from carved wood. 

[Crafting](./strive-core.md#crafting--research-projects)

**Tools**: a carving knife

| Product                              | Progress Increment | Time Increment | Materials                              | Quality Bonus   |
| ------------------------------------ | ------------------ | -------------- | -------------------------------------- | --------------- | 
| A wood-carved object                 | 30                 | 10 Minutes     | Wood                                   | / |

### Special Skills
The skills listed in this chapter cannot be learned *by just anyone*. Special requirements are made of those who aspire to learn them.

#### Psionics (Arc/Wit)
A psionic awareness grants access to supernatural abilities beyond those of mere magics. See also [The Veil](#the-veil). 

The psion may choose how much they wish to open up to The Veil. This is represented by their Openness, abbreviated as **OPN**. The OPN they choose may be at most their level in Psionics. 

* Obvious: The psion's eyes glow with the inscrutable light of the stars, when they use their psionic abilities.
* Prerequisites:
  * Wit `5+` OR innate.
  * Arcana `5+` OR innate.
  * An event that causes a psychic awakening. Consult your **GM**. 

| Level | Name                 | AP | Distance        | Ob                              | Veil Degradation | Effect(s)                      |
| ----- | -------------------- | -- | --------------- | ------------------------------- | ---------------- | ------------------------------ |
| 0     | Emotional Connection | 1  | `OPN * 10` | Opposed by `Self-Control - OPN` | `OPN * 2`        | Read and/or alter another creature's emotional state. |
| 0     | Telekinesis          | 2  | `OPN * 5`  | Opposed by `Self-Control - OPN` | `OPN * 2`        | Force move a **ST** by `OPN * 2`. |
| 0     | Telepathy            | 1  | `OPN * 15` | `OPN`                           | `OPN * 2`        | **Concentration**: Communicate wordlessly with `OPN` targets. Language barriers do not apply to this form of communication. |
| 0     | Slow Down            | 2  | `OPN * 6`  | `OPN`                           | `OPN * 2`        | **Concentration**: Up to `OPN` targets are slowed. They move `2` less per **AP** spent! |
| 1     | Repulse              | 1  | `20`       | `OPN`                           | `OPN * 3`        | **Reaction**: Upon having been attacked successfully, repulse your attacker psionically. They are force moved backwards by `OPN * 2`. |
| 1     | Levitate             | 1  | `OPN * 6`  | `OPN`                           | `OPN * 3`        | **Concentration**: Cause yourself or one other **ST** of choice, within *distance* to levitate up to `OPN * 6` above the ground. |
| 1     | "Vanish"             | 1  | `OPN * 6`  | `OPN`                           | `OPN * 4`        | **Concentration**: Cause up to `OPN` targets of choice, within *distance* to become *unperceivable* to `OPN` other targets of choice, within distance. |
| 3     | Veil Hop             | 3  | `OPN * 3`   | `OPN`                           | `OPN * 5`        | Cause a dimensional rift to open and swallow a **ST** of choice, which another rift releases at a location of your choosing, a moment later. |
| 3     | Join The Veil        | 2  | `OPN * 3`   | Opposed by `Self-Control - OPN` | `OPN * 3`        | Shroud a **ST** in the inscrutable darkness of The Beyond. They become [Terrified](strive-core.md#terrified) of the psion and [Marked](./strive-core.md#marked). |
| 4     | Try Again            | 1  | /               | /                               | `25`             | **Reaction**: When you or someone else resolves a test, create a minute overlap of timelines, and displace a snippet of your own timeline with a hopefully better one. You or they must now repeat the test. The new result is final. This can only be attempted once for a given test. |
| 4     | Memory Re-write      | 3  | `OPN * 3`   | Opposed by `Self-Control - OPN` | `OPN * 3`        | **Time(+1)**: Re-write the memory of a **ST**. Make them forget, or implant in them a memory they never had. |

## List of Magic Schools
The capabilities of the various magic schools are described by the [expertise](./strive-core.md#expertise) associated with each of them. The concrete effects are kept vague on purpose, to allow a certain freedom when choosing how the magic is expressed. But the intensity or strength of a casting is tied to the level of the [magic school skill](#magic-school--school---attribute-). 

The levels noted for each magic school represent the effects a mage can achieve, when casting that particular type of magic. Stronger effects generally require a higher level. 

See also [testing magic](#testing-magic). 

In all the following tables, note the following:
* Replace *SI* with the chosen [spell intensity](#spell-intensity-si). 
* *Level* is the prerequisite level of the **magic school skill**, at which a given spell becomes available for use. 
* Whenever distances and radii are concerned, a mage may always choose a *shorter* distance or radius. For example, a `SI * 2` radius definition, sets the **maximum**. The radius may be at most this large, but can be smaller, if the mage so chooses. 
* Whenever the effect is unleashed in a **cone**, then at every point it has traveled, it is as wide as far as it has traveled. So for example, at 1 distance, it is 1 wide. At 3 distance, it is 3 wide. 

### Aeromancy (Arc/Agi)
The control of air, to create and change its flow, for benefit and detriment. 

| Level | Name                 | AP | Distance      | Ob          | Effect(s)                      | Backfire Effect(s) |
| ----- | -------------------- | -- | ------------- | ----------- | ------------------------------ | ------------------ |
| 0     | Wind Tunnel          | 2  | `SI * 3`  | `SI`        | Conjures up a stream of air that [force moves](strive-core.md#forced-movement) all creatures and objects of bulk less than `SI * 2` in its direction, by `SI * 3`. This gust originates from the caster. The wind tunnel can also point up, down or any other direction. Can clear away gases and the like. | The caster loses control and is tossed `SI * 3` in a random direction! |
| 0     | Wind Lance           | 2  | `SI * 3`  | `Opposed`   | Hurls a directed, compacted bolt of air towards a target, dealing `1D10 + (SI * 2)` points of Bludgeoning damage. Upon impact, creates a loud whipping noise. | The attack is launched in a random direction, instead. |
| 1     | Breathing Bubble     | 2  | `1`       | `SI`        | **Concentration**: Form a stationary bubble of clean air, up to `SI * 1` large in diameter, that will last for as long as you concentrate on it. | The air is displaced from the caster's lungs for `1` round, making them unable to speak and they suffer `+1` [Exhaustion](./strive-core.md#exhaustion)! |
| 2     | Vacuumize            | 2  | `8`      | `SI`        | **Concentration**: Drive all air out of a stationary area of choice, within *distance*, up to `SI * 1` large in diameter. All creatures caught in the anti-air bubble start suffocating, as all air is driven from their lungs, as well. | The air around the caster is displaced, instead of the spot of their choosing. The effect lasts `1` round and the caster cannot concentrate on any other spell, for as long as it lasts. |
| 3     | Crushing Compression | 2  | `SI * 6` | `SI`        | Compress the air around a target, crushing it with `SI D6` points of Bludgeoning damage. | The air compresses around the caster instead. |
| 4     | Tornado              | 2  | `SI * 6` | `SI`        | **Concentration, Time(+1)**: Call forth a tornado and control its movements. It is up to `SI * 1` wide and tall, and can displace creatures and objects up to `SI * 2` bulk, throwing them up to `SI * 2` far, in a random direction. The tornado can clear away gases and the like. | The tornado forms at the caster's location and moves randomly. It lasts `1` round and the caster cannot concentrate on any other spell until the tornado expires. |

### Artificing (Arc/Wit)
The setting of arcane traps and creation of arcane artifacts and materials. 

[Crafting](./strive-core.md#crafting--research-projects)

| Product                                               | Progress Increment | Time Increment | Ob | Materials                              | Quality Bonus   |
| ----------------------------------------------------- | ------------------ | -------------- | -- | -------------------------------------- | --------------- | 
| Imbued Object - works just like "Place Arcane Charge" | 50                 | 1 Hour         |    | An object to "enchant".                | / |
| [Arcane Engine](#arcane-engine)                       | 100                | 1 Day          | +1 | 3 bulk of [Abyssalite](#abyssalite); A sturdy frame-material, like steel. | -1 side-effect for [Malevite Orbs](#malevite). |
| [Malevite Orb](#malevite)                             | 300                | 1 Day          | +2 | A lot of Mage blood; 3 or 9 or 27 or 81 bulk of [Abyssalite](#abyssalite) (graded per purity level) | / |
| [Magic Scroll](#magic-scrolls)                        | 50                 | 1 Hour         |    | A lot of Mage blood; 1 bulk of [Abyssalite](#abyssalite) | The imbued/primed spell can have at most the same [SI](#spell-intensity-si), as the achieved `Q`. |

| Level | Name                 | AP | Distance                | Ob                             | Effect(s)                      | Backfire Effect(s) |
| ----- | -------------------- | -- | ----------------------- | ------------------------------ | ------------------------------ | ------------------ |
| 0     | Place Arcane Charge  | 2  | `1`                 | `SI`                           | Focus arcane energy on a point in hand's reach. The surface begins to glow and become magically receptive. Any other spell that is then cast at the same spot, fills the arcane charge. A trigger defined by the mage will then unleash the stored spell. Note only simple triggers are possible. The charge cannot make distinctions like friend or foe. Example triggers: on touch, on detection of movement in front of the charge, on detection of sound, on the utterance of a specific word. The arcane charge lasts `SI * 4` hours. After that, it harmlessly dissipates. The charge is stationary. It cannot be moved. For every `3 SI` of the Arcane Charge, the spell it holds may be `+1 SI` stronger. | The arcane charge becomes unstable. Roll a `D4` to determine in what way. On a 1: the stored spell loses half its `SI` in strength. 2: the charge triggers in `1D6` minutes. 3: the charge immediately dissipates. 4: the stored spell is overriden. Instead, upon triggering, the charge now emits an excruciatingly loud noise. |
| 0     | Imitate Arcane Echo  | 2  | `10`               | `Imitated spell's SI / 2 (RU)` | Draw from a [magic echo](#magic-echoes) located up to `10` away and re-new it, casting it again at the SI it once had when it was originally cast. This can only be done once per Echo and cannot be used to re-cast *this* spell. The Echo is destroyed by this action. | The caster suffers the full back-fire of the spell that was imitated. |
| 1     | Elemental Shield     | 2  | `1`                 | `SI`                           | **Concentration**: Arcane energy envelops your skin, to counter one specific element of your choosing. You or a **ST** of your choice, within hand's reach, suffer `SI * 2` less damage of that element's type of damage. Available elements are: [Acid, Bleeding, Burning, Electrical, Freezing, Poison](./strive-core.md#damage-types). | You instead become twice as vulnerable to the element you chose, causing you to take twice as much damage! This effect lasts `3` turns, or `15` seconds. |
| 1     | Slag Bomb            | 2  | `6 + (SI * 1)` | `SI`                           | Cause `+SI` [Arcane Slag](#arcane-slag) to all targets within a `3` radius at a spot of your choosing. | Instead of the intended spot, the Slag Bomb detonates right in your face. |
| 1     | Detonate Slag        | 2  | `6 + (SI * 1)` | `SI`                           | Remove `SI` points of [Arcane Slag](#arcane-slag) from a **ST**, within reach and cause them to explode with arcane energy, dealing `N D4` points of Pure damage, where *N* is the number of [Arcane Slag](#arcane-slag) points that were removed. | Instead of the intended target, your own [Arcane Slag](#arcane-slag) detonates! |

### Alteration (Arc/Wit)
The alteration of physical things, to change their shape and purpose. And the ability to transform yourself, temporarily. 

| Level | Name                 | AP | Distance       | Ob              | Effect(s)                      | Backfire Effect(s) |
| ----- | -------------------- | -- | -------------- | --------------- | ------------------------------ | ------------------ |
| 0     | Shape Earth          | 2  | `SI * 3`   | `SI`            | Cause earth in a `SI * 2` radius, at a spot of the mage's choosing to change shape, as the mage wills it. The shape cannot exceed the radius in size. Could be used to create or tear down an earthen wall, close up a door way, quickly create a trench and so on. | Instead of the intended shape, the earth takes on an "inverse" form of what they want. If they wanted a wall, they get a trench. If they wanted a stair leading up, they get one leading down, and so on. |
| 1     | Arm Blade            | 2  | /              | `SI`            | **Concentration**: Change your arm into a sharp blade of bone, in a disgusting and painful transformation. All unarmed attacks may now deal an additional `SI * 2` Slashing damage. | You suffer a random mutation, instead! |
| 1     | Wings                | 2  | /              | `SI`            | **Concentration**: Grow wings! You may now fly up to `SI * 10` high at a speed of `SI * 2`. | You suffer a random mutation, instead! |
| 1     | Feel the Shape       | 1  | `SI * 20` | `SI`            | Place a hand to a surface. You can feel the faintest vibrations and reverberations within and beneath. Can be used to detect underground caves and structures and imprecisely detect the movements of creatures along a given surface, such as the ground. | / |
| 2     | Alter Shape          | 3  | `1`        | `SI`            | **Time(+1)**: A **ST** (object or creature) is altered as the mage desires, permanently. The Ob depends on the complexity and size of the re-shaping. Ob `2` for simple and small, `3` for tricky and medium, `4` for complex and large and `5+` for very complex and very large alterations. Consult your **GM**! | Instead of the intended alteration, a random mutation occurs! |
| 2     | Earth Spike Trail    | 3  | `SI * 3`   | `SI`            | Cause spikes of earth to shoot out of a surface that they can lay their hands on. Everyone caught in a straight line of up to `SI * 3` in length, originating from the mage, suffers `1D8 + SI` points of Piercing damage. The area of the spikes is then considered Difficult Terrain. The spikes crumble after `3` turns. | The mage loses control and the spell unleashes in a random direction. |
| 2     | Aspect of the Bull   | 2  | /              | `SI`            | **Concentration**: Grow bull horns and bestial legs! You may now run at a speed of `4 + (SI * 1)`. You may now charge at targets and gore them for `SI D6` points of Piercing damage, but you must run at least `4` in order to make use of this ability. | You suffer a random mutation, instead! |
| 4     | Wereshape            | 3  | /              | `4`             | **Concentration, Time(+1)**: Assume a were-beast shape. See the list below. Your attributes will be **modified** as noted on each were-shape. | Instead of transforming, your body goes into shock! You are [Stunned](./strive-core.md#stunned)! |

#### Werewolf-Shape
A bipedal wolf armed with wicked claws and deadly teeth!

Attributes: `+2` Agi, `+4` Str, `+2` Tough, `-2` Wit

| Skill                | Level | AP | **Ob**      | Damage                           | Notes  |
| -------------------- | ----- | -- | ----------- | -------------------------------- | ------ |
| Bite(Agi /Str)       | 2     | 2  | `Opposed`   | `1D6 + Str` Piercing             | Tear into a victim with wicked fangs! Causes `+1` [Bleeding](./strive-core.md#bleeding)! |
| Rend (Agi/Str)       | 3     | 2  | `Opposed`   | `1D10 + Str` Slashing            | Tear a victim to shreds! Causes `+1` [Bleeding](./strive-core.md#bleeding)! |

#### Werebear-Shape
A bipedal bear armed with massive claws and protected by a mass of muscle!

Attributes: `-1` Agi, `+4` Str, `+5` Tough, `-2` Wit

| Skill                | Level | AP | **Ob**        | Damage                           | Notes  |
| -------------------- | ----- | -- | ------------- | -------------------------------- | ------ |
| Rend (Agi/Str)       | 1     | 2  | `Opposed`     | `1D10 + Str` Slashing            | Tear a victim to shreds! |
| Bear-Hug (Tough/Str) | 2     | 2  | `Opposed + 1` | `Str * 2` Bludgeoning            | Bear-hug and squeeze the life out of a victim! If successful, the victim is considered [Grappled](./strive-core.md#grappled)! |

### Cryomancy (Arc/Arc)
The summoning and control of ice. Cryomancer's can freeze things, so they're heavier and harder to break. 

| Level | Name                  | AP | Distance      | Ob                           | Effect(s)                      | Backfire Effect(s) |
| ----- | --------------------- | -- | ------------- | ---------------------------- | ------------------------------ | ------------------ |
| 0     | Freezing Touch        | 2  | `1`       | `Opposed - SI`               | A fist-sized spot on a **ST**, that the mage's hand touches, freezes over and deals `SI * 3` points of Freezing damage. Causes `+1` [frostbitten](./strive-core.md#frostbitten) | The caster is affected, instead. |
| 1     | Cold Finger Gun       | 2  | `SI * 5` | `Opposed`                    | The mage shoots an ice spike at a **ST** from their hand, dealing `1D10 + SI` points of Freezing damage. Causes `+1` [frostbitten](./strive-core.md#frostbitten). | The caster is affected, instead. |
| 2     | Ice Shape             | 2  | `SI * 5` | `SI`                         | Turn humidity into ice, in the shape of your choosing, in an area the size of up to `SI * 3`. | The caster suffers `+1` [frostbitten](./strive-core.md#frostbitten)! |
| 3     | Ice Armor             | 1  | /             | `SI`                         | **Reaction**: Upon being successfully attacked, turn surrounding humidity into armor, that absorbs up to `SI * 3` points of Slashing, Piercing, Bludgeoning and Burning damage, before shattering immediately afterwards! The damage the armor absorbs, is the damage you do not suffer! | The caster suffers `+1` [frostbitten](./strive-core.md#frostbitten)! |
| 4     | Rooting Freeze        | 3  | `SI * 5` | `SI + 1`                     | **Time(+1)**: A spot of the mage's choosing freezes over. Anyone caught within the **AOE** radius of up to `SI * 3`, will be frozen to the spot and thus [Rooted](./strive-core.md#rooted) and also suffer `SI D4` points of Freezing damage. They can break free via a successful [strength](./strive-core.md#strength-str) test at Ob `SI`. Or wait, until the ice thaws, which, under normal conditions, will take `SI` rounds. | The spot beneath the caster is affected, instead. |

### Electromancy (Agi/Arc)
The summoning and control of lightning. Electricity is fairly versatile - it can injure or stun and power or trigger electrical and electronic devices. 

| Level | Name                  | AP | Distance       | Ob                           | Effect(s)                      | Backfire Effect(s) |
| ----- | --------------------- | -- | -------------- | ---------------------------- | ------------------------------ | ------------------ |
| 0     | Shocking Touch        | 2  | `1`        | `Opposed - SI`               | A small area, about the size of the mage's hand is burned on touch by an electrical shock, dealing `SI * 3` points of Electrical damage to a **ST**. Causes [Electrified](./strive-core.md#electrified) in the victim. | The caster is affected, instead. |
| 1     | Shock                 | 2  | `SI * 3`   | `Opposed`                    | An arc of lightning strikes the vulnerable internals of a **ST**, dealing `SI D4` points of Electrical damage. Causes [Electrified](./strive-core.md#electrified) in the victim. | The caster is affected, instead. |
| 1     | Power-Up              | 2  | `SI * 1`   | `SI`                         | An electrical device is powered up for `SI * 5` minutes. | The device breaks or otherwise seizes up and becomes unusable. |
| 3     | Stunning Shock        | 2  | `SI * 3`   | `Opposed`                    | **Time(+1)**: An aimed arc of lightning strikes a **ST**'s nervous system and makes them [Stunned](./strive-core.md#stunned). | The caster is affected, instead. |
| 4     | UNLIMITED POWER       | 2  | `SI * 10` | `SI + 1`                     | A cone of lightning spews forth from the mage's finger tips. Up to `SI + 1` **MST** can be hit with the shock, dealing `SI D8` points of Electrical damage. Causes [Electrified](./strive-core.md#electrified) in the victims. | The caster and anyone next to them is affected, instead. |

### Hexing (Arc/Arc)
The casting of curses to weaken others. 

| Level | Name                  | AP | Distance      | Ob                        | Effect(s)                      | Backfire Effect(s) |
| ----- | --------------------- | -- | ------------- | ------------------------- | ------------------------------ | ------------------ |
| 0     | Instill Fear          | 2  | `SI * 5` | Opposed by `Self-Control` | **Time(+1)**: [Terrify](strive-core.md#terrified) a victim for `SI` turns. | The caster is affected, instead. |
| 0     | Slow Down             | 2  | `SI * 3`  | Opposed by `Self-Control` | Reduce a target's [AP](./strive-core.md#action-points-ap) regain per turn by `1` for `SI` turns and reduce their current [AP](./strive-core.md#action-points-ap) by `1`. Does not stack. | The caster is affected, instead. |
| 1     | Weaken                | 2  | `SI * 5` | Opposed by `Toughness`    | **Concentration**: Cause a target to take `SI * 2` more points of damage from a chosen damage type. | The caster is affected, instead. The effect lasts for `1` round and the mage **cannot** concentrate on any other spell for that duration. |
| 2     | Atrophy               | 2  | `SI * 3`  | Opposed by `Toughness`    | **Concentration**: Weaken a target's Strength by `SI` levels. Also, they deal `SI * 2` fewer points of damage per physical attack. | The caster is affected, instead. The effect lasts for `1` round and the mage **cannot** concentrate on any other spell for that duration. |
| 2     | Spray Acid            | 2  | `SI * 3`  | `SI`                      | Spray acid in a cone, for `SI D4` points of Acid damage. | The effect triggers in reverse, pointing the cone straight through the caster and backwards. They and anyone in the cone behind them suffers the damage! |
| 3     | Slag to Acid          | 2  | `SI * 5` | Opposed by `Toughness`    | Convert the [Arcane Slag](#arcane-slag) of a **ST** within reach into acid! They lose `SI` points of [Arcane Slag](#arcane-slag), which convert into `N D6` points of Acid damage, where *N* is the number of [Arcane Slag](#arcane-slag) points removed! | The caster is affected, instead! |

### Hydromancy (Agi/Arc)
The control of directly accessible water. Blood and creatures cannot be affected by this school. 

Contact with **magically fouled water** will always cause [illness](./strive-core.md#illness)! Fortunately, fouled water does not mix with pure water. But it also cannot be purified - it is, under normal circumstances, **irreversibly** fouled! 

| Level | Name                 | AP | Distance      | Ob                        | Effect(s)                      | Backfire Effect(s) |
| ----- | -------------------- | -- | ------------- | ------------------------- | ------------------------------ | ------------------ |
| 0     | Purify Water         | 2  | `SI * 5` | `SI`                      | Cleanse a body of water in up to a `SI * 3` radius to rid itself of all unhealthy impurities, *except* when **magically fouled**! | The water turns magically foul! |
| 0     | Evaporate Surface    | 2  | `SI * 5` | `SI`                      | Instantaneously cause all water to evaporate, in up to a `SI * 3` radius. | The water turns magically foul! |
| 0     | Separate Fluids      | 1  | `SI * 5` | `SI`                      | Turn one liquid into two distinct liquids, each containing a specific aspect, and which **cannot mix**, in a `SI * 3` radius. Could be used to separate foul water from pure water. | / |
| 1     | Fluid Whip           | 2  | `SI * 3`  | `Opposed`                 | Cause a fluid to lash out at a target, like a whip, dealing `SI D6` points of Slashing damage. | The caster loses control and the whip strikes in a random direction. |
| 2     | Harden Fluid         | 2  | `SI * 3`  | `SI`                      | **Concentration**: Cause a fluid in a radius or line of up to `SI * 5` to become semi-solid. Solid enough to walk on it and for it to keep its current shape! | The water turns magically foul! |
| 3     | Conjure Rain         | 3  | `SI * 5` | `SI`                      | **Concentration, Time(+1)**: Cause rain to fall in a radius or line of up to `SI * 5`. | Foul water rains from the sky! Anyone caught in it will suffer an [illness](./strive-core.md#illness)! |
| 3     | Conjure Fog          | 3  | `SI * 5` | `SI`                      | **Concentration, Time(+1)**: Cause fog to form in a radius or line of up to `SI * 3`. The fog imposes a `-2` penalty to all tests through or within it that rely on sight. | The fog forms around the mage, instead of their chosen location and lasts for `1` round. The mage **cannot** concentrate on any other spell for that duration. |

### Illusion (Arc/Awar)
Creation of non-physical influences on the senses. That includes images, sounds and odors. The illusions cannot cause direct harm, although they can drive an individual to acts that may put them in danger. 

| Level | Name                 | AP | Distance       | Ob                        | Effect(s)                      | Backfire Effect(s) |
| ----- | -------------------- | -- | -------------- | ------------------------- | ------------------------------ | ------------------ |
| 0     | Stationary Illusion  | 2  | `SI * 10` | `SI`                      | **Concentration**: Create a stationary illusory image, sound and/or smell in a radius of up to `SI * 3`. The illusion can be debunked, with an [Observation](./strive-core.md#observation-awarawar) test at Ob equal to `SI + 1`. | The mage loses control and their worst fear manifests in front of them. They become [Terrified](./strive-core.md#terrified) of this errant illusion, for `1` round! |
| 0     | Disguise             | 2  | `10`      | `SI`                      | **Concentration**: Up to `SI` **MST** creatures' appearance, sound of voice, even smell, is changed as the mage desires. Note this is only an illusion and represents no *actual* change! The illusion can be debunked, with an [Observation](./strive-core.md#observation-awarawar) test at Ob equal to `SI + 1`. | The mage loses control and their worst fear manifests in front of them. They become [Terrified](./strive-core.md#terrified) of this errant illusion, for `1` round! |
| 0     | Illusory Duplicates  | 2  | `5`       | `SI`                      | **Concentration**: `SI` number of illusory copies of a **ST** emerge. The distracting images move around the the **ST** and make it `SI Ob` harder to hit them. Every time the **ST** is attacked, one of the illusory duplicates is removed. When no duplicates remain, the spell ends automatically. | The mage loses control and their worst fear manifests in front of them. They become [Terrified](./strive-core.md#terrified) of this errant illusion, for `1` round! |

### Pyromancy (Arc/Arc)
The summoning and control of fire. The flame being a destructive force, pyromancers enjoy little utility from their magic, beyond the ability to create light and heat. 

| Level | Name                 | AP | Distance       | Ob                        | Effect(s)                      | Backfire Effect(s) |
| ----- | -------------------- | -- | -------------- | ------------------------- | ------------------------------ | ------------------ |
| 0     | Burning Touch        | 2  | `1`        | `Opposed - SI`            | A controlled flame erupts and stays in the mage's hand, inflicting `SI * 3` points of Burning damage and `+1` [Burning](./strive-core.md#burning) on touch, to a **ST**. | The caster is affected, instead. |
| 1     | Flame Whip           | 2  | `SI * 3`   | `Opposed`                 | Lash out at a **ST** with a whip made of pure fire, dealing `SI D6` points of Burning damage and `+1` [Burning](./strive-core.md#burning) to them! | The caster loses control and the whip lashes out in a random direction, instead! |
| 1     | Imbue Flame          | 2  | `SI * 3`   | `SI`                      | **Concentration**: Cover an object in flames that do not burn it, but rather anything else! All attacks made with that object deal an additional `SI * 2` points of Burning damage! | The flames *do* consume the object they cover! The object *can* still be carried or wielded, but will deal `SI * 2` points of Burning damage to whoever does, at the start of their every turn! |
| 2     | Cone of Fire         | 3  | `SI * 2`   | `SI`                      | The mage shoots a burst of fire in a cone in front of them, dealing `SI D6` points of Burning damage and inflicting `+1` [Burning](./strive-core.md#burning) to all in the victims in the cone. | The effect triggers in reverse, pointing the cone backwards, through the mage's face. |
| 3     | Fire Ball            | 2  | `SI * 15` | `SI`                      | **Time(+1)**: The mage forms a large ball of flame between their hands, ready to be flung at a target location, dealing `SI D6 + 4` points of Burning damage and inflicting `+1` [Burning](./strive-core.md#burning) in a radius of up to `SI * 1`. | The fire ball instead launches in a random direction, impacting with the first obstacle it comes across! |
| 4     | Flame Jet            | 3  | `SI * 3`   | `SI + 1`                  | A steady stream of flame shoots from the mage's hands, dealing `SI D6` points of Burning damage and inflicting `+2` [Burning](./strive-core.md#burning) to anything caught by it, in a straight line.  | The line of fire erupts backwards, through the mage. They and anyone behind them, in the line's range is affected. |
| 5     | Rain of Fire         | 4  | `SI * 20` | `SI + 2`                  | **Concentration, Time(+1)**: The mage makes fire rain from the sky! At the start of every turn, a ball of fire falls from the sky, dealing `(SI D6) + (SI * 2)` points of Burning damage and inflicting `+2` [burning](./strive-core.md#burning) in a `SI * 2` radius, at a location of choice. | No fire falls from the sky, instead the fire explodes in the caster's hands, dealing `SI D6` points of Burning damage and `+2` [Burning](./strive-core.md#burning) to themselves and anything in a `8` radius around them! |

### Restoration (Arc/Awar)
The mending of the body and mind.

| Level | Name                 | AP | Distance   | Ob                           | Effect(s)                      | Backfire Effect(s) |
| ----- | -------------------- | -- | ---------- | ---------------------------- | ------------------------------ | ------------------ |
| 0     | Treating Touch       | 2  | `1`    | `Injury Ob - SI`             | An [injury](./strive-core.md#injury) of a **ST** of the mage's choosing, in hand's reach, is magically healed and removed. It may still leave a [scar](./strive-core.md#scar). Also restores `SI D10` missing [HP](./strive-core.md#hit-points-hp). Only one such treatment can safely be made, per creature, every `6` hours. If a treatment is made before the waiting time is up, roll a `D6` - a `1` will cause the patient to suffer a mutation, while a `2` through `5` will cause them and the mage `+2` [Arcane Slag](#arcane-slag). A `6` is lucky and will cause no negative effects. | The caster suffers `SI D10` points of [Bleeding](./strive-core.md#damage-types) damage. |
| 2     | Clear Mind           | 2  | `SI 3` | `2`                          | Removes the [Terrified](strive-core.md#terrified), [Jealous](strive-core.md#jealous), [Pacified](./strive-core.md#pacified), [Marked](./strive-core.md#marked) and [Stunned](./strive-core.md#stunned) Conditions from a **ST** in reach. | The caster becomes [Stunned](./strive-core.md#stunned)! |
| 2     | Life Leech           | 2  | `1`    | Opposed by `Toughness`       | Draw the life from a **ST** creature of choice. Deals `SI D4` points of bleeding damage while healing the caster's [HP](./strive-core.md#hit-points-hp) for the same amount. May transfer `SI` points of [Bleeding](./strive-core.md#bleeding) or [Poisoned](./strive-core.md#poisoned) from the healed creature to the damaged one, if the mage so chooses. | The effect triggers in reverse. |
| 2     | Expel Illness        | 3  | `1`    | `Illness Ob - SI`            | Removes one [Illness](./strive-core.md#illness) of choice from a **ST** of choice, in hand's reach. | The caster contracts a random [Illness](./strive-core.md#illness). | 
| 4     | Reduce Slag          | 3  | `1`    | `SI + 1`                     | Remove `SI` points of [Arcane Slag](#arcane-slag) from a **ST**! If successful, this spell does not cause [Arcane Slag](#arcane-slag). | Instead of removing any [Arcane Slag](#arcane-slag), you gain `+2` points of it and suffer `6` points of [Bleeding](./strive-core.md#damage-types) damage! |
| 4     | Revert Mutation      | 4  | `1`    | `6 - SI`                     | Removes one [Mutation](./strive-core.md#list-of-mutations) of choice from a **ST** of choice, in hand's reach. | The caster suffers a random [Mutation](./strive-core.md#list-of-mutations). |

### Sanguinomancy (Arc/Tough)
In the common tongue, blood magic, utilizes mage blood to control a deeply unsettling power. The used blood must be fresh, although not necessarily from the caster. 

| Level | Name                 | AP | Distance        | Ob                         | Effect(s)                      | Backfire Effect(s) |
| ----- | -------------------- | -- | --------------- | -------------------------- | ------------------------------ | ------------------ |
| 0     | Infusion             | 1  | /               | `SI`                       | **Concentration**: Suffer `1D4` [Bleeding](./strive-core.md#damage-types) damage, as you cut a nasty gash into your flesh to draw blood. This spell causes `SI` less [Arcane Overheat](#arcane-overheat) (down to at most `1`). Arcanically charge the blood and smear it on something (like a weapon). The blood begins to boil, causing it to deal an additional `SI * 3` [Burning](./strive-core.md#damage-types) damage. | The caster suffers `SI D4` points of [Bleeding](./strive-core.md#damage-types) damage. |
| 0     | Snap                 | 2  | `10`       | Opposed by `Toughness + 1` | Snap a twig or similar and channel the destructive power into a victim. They suffer a random [bludgeoning injury](./strive-core.md#bludgeoning-injuries) and `SI * 3` points of [Bleeding](./strive-core.md#damage-types) damage. | The caster suffers the injury, instead. |
| 1     | Blood Whip           | 2  | `SI * 5`   | `Opposed`                  | Suffer `1D8` [Bleeding](./strive-core.md#damage-types) damage, as you cut a nasty gash into your flesh to draw blood. This spell causes `SI` less [Arcane Overheat](#arcane-overheat) (down to at most `1`). Have your blood lash out at a target, dealing `1D8 + SI` [Slashing](./strive-core.md#damage-types) and `SI D6` [Bleeding](./strive-core.md#damage-types) damage. | The caster suffers `1D10` points of [Bleeding](./strive-core.md#damage-types) damage. |
| 2     | Blood Boil           | 2  | `SI * 2`    | Opposed by `Toughness + 1` | Bring a victim's blood to a boil. They suffer `SI D6 burning` damage, that [armor](./strive-core.md#armor--shields) cannot reduce. | The caster suffers `1D10 burning` damage, instead. |
| 2     | Bond of Suffering    | 1  | `SI * 5`   | `SI`                       | **Concentration**: Suffer `2D6` [Bleeding](./strive-core.md#damage-types) damage, as you cut a nasty gash into your flesh to draw blood. This spell causes `SI` less [Arcane Overheat](#arcane-overheat) (down to at most `1`). Your blood forms a bond between two designated creatures, who then share all damage and healing. | The caster suffers twice as much damage from all physical sources, until the start of their next turn. |
| 2     | Life Leech           | 2  | `1`         | Opposed by `Toughness`     | Draw the life from a **ST** creature of choice. Deals `SI D4` points of [Bleeding](./strive-core.md#damage-types) damage while healing the caster's [HP](./strive-core.md#hit-points-hp) for the same amount. May transfer `SI` points of [Bleeding](./strive-core.md#bleeding) or [Poisoned](./strive-core.md#poisoned) from the healed creature to the damaged one, if the mage so chooses. | The effect triggers in reverse. |
| 3     | Crimson Tracks       | 1  | `SI * 150` | `SI`                       | If you have someone's blood, use it to track them. If successful, you get a general sense of how far away and in what direction relative to your facing they are. You also glimpse a momentary fragment of their current emotional state. | The victim is overcome with an odd premonition and becomes aware someone attempted to track them. |
| 4     | Slagletting          | 2  | /               | `SI + 1`                   | Remove `SI` points of [Arcane Slag](#arcane-slag) from yourself, but suffer `3` points of [Bleeding](./strive-core.md#damage-types) damage for each point of [Arcane Slag](#arcane-slag) that is removed! If successful, this spell does not cause [Arcane Slag](#arcane-slag). | Instead of removing any [Arcane Slag](#arcane-slag), you gain `+2` points of it and suffer `6` points of bleeding damage! |
| 5     | Puppeteer            | 3  | `SI * 5`   | Opposed by `Self-Control`  | **Concentration, Time(+1)**: Command the blood of a victim to obey you. You control their actions, like a puppeteer. Any action you make them take, costs *their* AP. They may try to resist at the beginning of their every turn, or once every minute. | You lose control and are [Stunned](./strive-core.md#stunned)! |

### Soul-Binding (Arc/Tough)
Also referred to as **necromancy**, this is the art and skill of calling souls from the **plane of the dead** and binding them, to reanimate corpses or animate an otherwise unliving body. 

In order to bind a soul, a **soul-seal** is required. This seal has to take the form of a pentagram. The medium doesn't matter, although if the seal is destroyed, the soul binding is broken. So, if a mage wants to create a lasting soul-binding, an enduring medium for the seal is advisable. 

A mage can only ever issue commands to a soul that they've bound. It is not possible to command souls bound by other mages. 

A **soul-binding** can be broken, but it in order to do so, a **soul-binding** test at **Ob** equal to the strength of the **soul-binding** must be **completely succeeded**. It is possible to lift a **soul-binding** made by another mage. 

An important note about **completely failing** a **soul-binding** attempt - a **complete failure** results in the spell-backfiring and displacing the mage's soul with the one they were trying to bind. Their soul is essentially evicted from their own body and sent to the **plane of the dead**. The soul they tried to bind then takes over their body. 

Another important note about targeting a specific soul. It is easier to recall the soul that previously inhabited a body, the shorter the time of death has been. However, targeting a specific soul is an immensely difficult undertaking and shouldn't be taken lightly. For every day past the original time of death, the Ob of recalling the soul increases by `+1`. 

| Level | Name                 | AP | Distance      | Ob                           | Effect(s)                      | Backfire Effect(s) |
| ----- | -------------------- | -- | ------------- | ---------------------------- | ------------------------------ | ------------------ |
| 0     | Call and Bind a Soul | 3  | `1`       | `SI`                         | Create a **soul-binding** at the strength of the chosen level. The larger, heavier and more complex a body is, the harder it is to create a binding. Anything larger than, heavier or more complex than a human will make the **soul-binding** harder. `2` for a small and simple, `3` for a moderate and `4` for a large and `5+` for a huge and complex binding. Consult your **GM**. Requires a **soul-seal**. Replacing an existing binding is possible, but the test must exceed the original soul-seals strength. | The caster's soul is displaced from their body. They suffer `1D10 + 5` points of Pure damage! |
| 0     | Soul Blast           | 2  | `SI * 10`| `Opposed - SI`               | Blast the soul from a **ST**'s body. They suffer `SI D4` [Pure](strive-core.md#damage-types) damage. The experience weakens them, rendering them [Marked](strive-core.md#marked). | The caster is affected, instead. |
| 1     | Command Bound Soul   | 1  | `SI * 3`  | Opposed by `Wit - SI`        | Issue a single command that the bound soul **must** follow. | / |
| 1     | Break Binding        | 3  | `1`       | `SI of the seal`             | Break a **soul-binding** and send the soul back to the **plane of the dead**, leaving its former body inanimate and soulless. | The caster's soul is displaced from their body. They suffer `1D10 + 5` points of Pure damage! |
| 5     | Call back a Soul     | 3  | `1`       | `SI + days since death`      | Target a specific soul and recall them into their prior body. This isn't, strictly speaking, the same as binding a soul. | The caster's soul is evicted from their body and another soul takes place. The caster's character is effectively removed from the world. |

### Telekinesis (Arc/Agi)
The ability to affect things and even creatures from afar, using magic instead of muscles or tools. 

When using objects as projectiles, choose the [damage type](./strive-core.md#damage-types) as appropriate. For example, a crossbow bolt might cause Piercing damage, while a rock might cause Bludgeoning damage.

The mage can only ever perform *one* movement with a spell cast. So, for example, it is not possible to violently shake things or creatures around, without casting **telekinesis** multiple times, to do so. During combat, every movement takes one turn. Out of combat, about five seconds. A single movement is a displacement from one point to another, in a straight and uninterrupted line. 

Only targets within and up to the given *distance* can be moved and only within and up to that *distance* from the mage. 

| Level | Name                   | AP | Distance      | Ob                           | Effect(s)                      | Backfire Effect(s) |
| ----- | ---------------------- | -- | ------------- | ---------------------------- | ------------------------------ | ------------------ |
| 0     | Telekinesis            | 2  | `SI * 5` | `SI`                         | Move an inanimate **ST** object at great velocity (if desired), up to `SI * 5` far. | The caster loses control! The object is instead flung in a random direction! |
| 1     | Hold Fluid             | 2  | `SI * 5` | `SI`                         | **Concentration**: Cause an up to `SI * 3` large body of water to levitate. | / |
| 3     | Creature Telekinesis   | 3  | `SI * 5` | `Opposed`                    | Force move a **ST** creature up to `SI * 3`. | The caster is thrown backwards by `SI * 3`. |

### Telepathy (Arc/Wit)
The ability to communicate wordlessly, to alter emotions and even issue compelling commands against another's will. 

| Level | Name                   | AP | Distance       | Ob                           | Effect(s)                      | Backfire Effect(s) |
| ----- | ---------------------- | -- | -------------- | ---------------------------- | ------------------------------ | ------------------ |
| 0     | Wordless Communication | 2  | `SI * 4`  | `SI`                         | **Concentration**: Communicate wordlessly with `SI` **MST**. Language barriers do not apply to this form of communication. | / |
| 0     | Read Thoughts          | 2  | `SI * 4`  | Opposed by `Wit - SI`        | Glimpse into the thoughts of **ST** for a short time. | The target instead catches a glimpse into the caster's thoughts. |
| 2     | Change a Mind          | 2  | `SI * 4`  | Opposed by `Wit - SI`        | Alter a creature's current state of mind and emotion. | The caster is affected, instead. |
| 3     | Pressing Thought       | 2  | `SI * 10` | `SI + 1`                     | **Concentration**: [Hasten](./strive-core.md#hasted) up to `SI` **MST** of choice. | The caster and their targets suffer `+1` [Exhaustion](./strive-core.md#exhaustion). |
| 4     | Quiet Command          | 2  | `SI * 10` | Opposed by `Wit - SI`        | Issue a command to another creature, which they feel **strongly** compelled to follow. | `+1` [Exhaustion](./strive-core.md#exhaustion) to self. |
| 5     | Confer Knowledge       | 4  | `1`        | `6 - SI`                     | **Time(+1)**: Confer `+1` level of a **known skill** to another creature. | The caster loses `1` level in the chosen skill, for `24` hours! |

## List of Illnesses
This list supplements the list of **injuries** of the [core module](./strive-core.md#list-of-injuries). 

| Name              | Duration          | Effect      | Treatment |
| ----------------- | ----------------- | ----------- | --------- |
| Amber Curse       | **2D10** Days     | The victim finds it difficult to feel the flow of magic through their body. **-1D4** [arcana](#arcana-arc); **-1D4** to any magic skills and [rune-using](#rune-using-agiwit). | Conventional methods cannot treat this illness. It can be treated with a potion of powdered [abyssalite](#abyssalite). |

## Archetype Characters
This section contains some pre-defined archetypal characters. These are mostly ready to play and serve as instructional references on how to build your own characters. 

Their name, species, gender, age and other details are left up to you to fill out, with the help of your GM, as such details must fit their world and cannot be predicted here. Also, the initial drivers are designed you get these characters to come together and co-operate. There is no point in playing lone wolves. You are very much expected to replace the drivers and come up with your own after the first session of play. 

### The Arcaenologist
After so many years of study and dedication to dusty tomes and repeated lectures, you realize the world cannot be found in books and scrolls - it is *out there*. Perhaps it is not yet too late to experience it all?

Ambition: Perhaps I could leave a lasting legacy, as well? I will craft a legendary magical artifact!

Drivers:
1. I wish to see all the world's wonders! 
2. I know there are many private collections full of magical marvels. I will gain access to them!
3. I have never traveled much before. I will need guidance and perhaps a group to tag along to my next destination.

Reactions:
1. Troublemaker: When frightened, I tend to have outbursts of my pyromanic magic. 
2. Troublemaker: I tend to drone on and ramble, testing the patience of others, especially in negotiations. 
3. Assurance: The world of magic practicioners is small enough and well connected - I know most others who engage in my craft. 

| Agi          | Awar         | Str          | Tough        | Wit          | Arc (Core)   |
| ------------ | ------------ | ------------ | ------------ | ------------ | ------------ |
| 1            | 3            | 1            | 1            | 3            | 4            |

| BI     | Sprint | Stabil | HP  | Exhaustion |
| ------ | ------ | ------ | --- | ---------- |
| 7      | 1      | 0      | 20  | 2          |

Titles of Renown:
* Loremaster of *X* (3) - at the cost of `2` points that would have gone to Skills. Replace *X* with something befitting your GM's world - make sure to consult them!

Skills:
* Alchemy, Level `3`
* History, Level `3`
* Magic School \<Artificing\>, Level `4`
* Magic School \<Pyromancy\>, Level `3`
* Magic School \<Restoration\>, Level `3`
* Reading and Writing, Level `2`
* Rune-Smithing, Level `1`

Assets:
* 1x Scholar's noble garb
* 2x Illusionist's Powder
* 3x Dragon's Breath Potion

### The Performer
All the world's a stage! Life is a performance! And yours will be the greatest performance of all, in one way or another! You live for the stage - whether it be made of wood and curtains, or dust and blood. You seek to be excited, to excite and to support those who do either. After all, a good actor knows when to leave the stage to others...

The Performer may seem like a chaotic troublemaker, but if you pick them, don't play them like a nuisance. They're a **connoisseur of art and drama**, not some hateful *idiot*. Fan the flames only when it is *really dramatic*. And be supportive of others - they have a part in this play, too, after all!

Ambition: Become world renowned, in any way I might! If all life is to end, then I shall make mine **such** an end!

Drivers:
1. Renown doesn't come from inaction - I will fulfill a job that is sure to make me known to the world!
2. I seek thrill and excitement! And what greater thrill is there to be found, than in blood sport? I will participate!
3. Great works live on - I will invent the world's most outrageous, exciting and inspiring stage play! 

Reactions:
1. Troublemaker: I cannot help but fan the flames - a heated situation is always *so much more interesting*!
2. Troublemaker: I love when the blood pumps - and I seek such moments voraciously!
3. Assurance/Troublemaker: It takes one to know one - I can always recognize an actor, a charlatan and a visionary. But I *might* keep such wisdom to myself...

| Agi (Core)   | Awar         | Str          | Tough        | Wit          | Arc          |
| ------------ | ------------ | ------------ | ------------ | ------------ | ------------ |
| 4            | 3            | 3            | 2            | 1            | 0            |

| BI     | Sprint | Stabil | HP  | Exhaustion |
| ------ | ------ | ------ | --- | ---------- |
| 8      | 3      | 1      | 30  | 3          |

Traits:
* Warcrobat - at the cost of `2` points that would have gone to Skills.

Skills:
* Acrobatics, Level: `3`
* Acting, Level: `3`
* Entertainment, Level: `3`
* History, Level: `1`
* Self-Control, Level: `2`
* Throwing, Level: `3`
* Weapon \<Chained-Blade\>, Level `4`

Assets:
* 1x Performer's garb
* 1x Chained-Blade
* 6x Throwing Blade

### The Surgeon
Everyone needs a good doctor and everyone wants to be friends with one. Whether out of altruistic instinct, or for coin, your skills with a short blade and your academic expertise will always come in useful. 

Ambition: Establish a hospital and make it house the world's finest medics and surgeons. My name shall live on through it!

Drivers:
1. I will travel the world and seek out the most renowned medics and surgeons, to convince them of my hospital. 
2. I will find a group of foolhardy adventurers to travel with, as I will need protection and coin. And to keep honing my art. 
3. A hospital is expensive - I will convince someone influential and wealthy to fund my hospital for me. 

Reactions:
1. Troublemaker: If someone is in need, I will always help. Afterwards I may still ask to be paid, though.
2. Troublemaker: If someone else tries to treat Injuries, I will always push them aside and take over. Can't have the laity play doctor!
3. Troublemaker: I do not kill people. I may hurt them, though.

| Agi (Core)   | Awar         | Str          | Tough        | Wit          | Arc          |
| ------------ | ------------ | ------------ | ------------ | ------------ | ------------ |
| 4            | 1            | 2            | 2            | 4            | 0            |

| BI     | Sprint | Stabil | HP  | Exhaustion |
| ------ | ------ | ------ | --- | ---------- |
| 9      | 3      | 0      | 30  | 3          |

Skills:
* History, Level: `3`
* Medicine, Level: `3`
* Reading and Writing, Level: `2`
* Observation, Level: `2`
* Self-Control, Level: `2`
* Surgery, Level: `4`
* Unarmed Combat, Level: `2`
* Weapon \<Dagger\>, Level: `3`

Assets:
* 1x Dagger
* 1x Surgeon's apron above fine white clothes
* 5x Medical Supplies

### The Tired Monster Hunter
The many years of crawling through mud, delving into filth-filled sewers, getting lost in treacherous caverns and ambushed in haunted forests have left their marks on you. Countless scars each have a story to tell, but you are far too tired to recount them all. You would love nothing more than to settle down and retire, but you also realize the world needs you to keep up the good work, for there are still many monsters more, but not enough of *your* kind to oppose them. 

Ambition: Learn a simple craft and ultimately retire. But only after making sure there are enough others to follow in your foot-steps. 

Drivers:
1. The world is perilous and in need of heroes. I will ensure many others will successfully take up my profession. 
2. My current quarry is a particular threat. I will find allies to help me track and ultimately take it down. 
3. Others view me with unjust suspicion. I will earn the trust of a community I wish to settle down in!

Reactions:
1. Troublemaker: I must help others in need - life is tough enough as it is. But I refuse coin for good deeds. 
2. Assurance: I have a reputation. Others know my work and will gladly point me towards more, even offer supplies and financial aid, albeit no helping hand. 
3. Troublemaker/Assurance: Whenever I am unsure of my path, I take out my - supposedly broken - compass. Its needle always points where I am needed. I think. 

| Agi          | Awar (Core)  | Str          | Tough        | Wit          | Arc          |
| ------------ | ------------ | ------------ | ------------ | ------------ | ------------ |
| 2            | 4            | 1            | 3            | 3            | 0            |

| BI     | Sprint | Stabil | HP  | Exhaustion |
| ------ | ------ | ------ | --- | ---------- |
| 9      | 3      | 0      | 40  | 4          |

Titles of Renown:
* Monster Hunter - at the cost of `2` points that would have gone to Skills. Consult your GM to determine which three kinds of beasts you have slain before. 

Skills:
* Creature-Lore, Level `3` - Consult your GM to determine the category of creature. 
* Nature, Level `3`
* Observation, Level `3`
* Path-Finding, Level `3`
* Stealth, Level `2`
* Trapping, Level `3`
* Weapon \<Crossbow\>, Level `4`

Assets:
* 1x Light Armor
* 1x Crossbow
* 2x Blackpowder Bomb

### The Warboss
Times may have been tough for you, but you'll come back from your setbacks. Thanks to your wit and skill, you always do. That usurper who took over your mercenary company won't even know what hit him once you get to him! Those many long years with your company have been the best of your life. The bonds forged in war and feasts *should* have been unbreakable. But perhaps, such bonds could be forged anew?

Ambition: That usurper may have my mercenary company for now, but I will take it back!

Drivers:
1. I need capable allies to aid my quest for revenge. I hear adventurers are always ready to work for coin, as am I. I will make friends with some of them. 
2. My allies are spent and stolen. I will earn a favor from someone influential and wealthy, to call upon later. 
3. My old company has made themselves scarce. I know they fear me. I will find out where they currently are and what their plans are.

Reactions:
1. Troublemaker: Whenever I get the chance, I will boast wholeheartedly of my exploits and those of my company! Who cares if not everything we did was *legal*?
2. Assurance: Many negotiations in the past have taught me valuable people skills. I can always tell if *something* seems off in an offered deal. 
3. Troublemaker/Assurance: You never know where the enemy lurks. I always have a weapon and my armor ready. 

| Agi          | Awar         | Str          | Tough        | Wit (Core)   | Arc          |
| ------------ | ------------ | ------------ | ------------ | ------------ | ------------ |
| 2            | 1            | 2            | 4            | 4            | 0            |

| BI     | Sprint | Stabil | HP  | Exhaustion |
| ------ | ------ | ------ | --- | ---------- |
| 7      | 3      | 0      | 50  | 5          |

Skills:
* Commanding, Level: `3`
* Medicine, Level: `2`
* Mercantilism, Level: `2`
* Path-Finding, Level: `2`
* Self-Control, Level: `2`
* Shield, Level: `3`
* Warfare, Level: `4`
* Weapon \<Light Blade\>, Level: `3`

Assets:
* 1x Light Blade
* 1x Shield
* 1x Medium Armor

# Fantasy Game-Masters Resource
This and the following sections are reserved solely for the **GM**'s eyes. Reading on as a player may spoil many surprises and the fun of discovery for you. 

# Creature Compendium
A by no means exhaustive list of medieval-fantasy themed creatures for the **GM** to draw from. 

## Swine-Beasts
Created in a vain and immoral conjuring of demons from another place, the Swine-Beasts themselves represent a cruel parody of man, molded from the flesh of pigs. All the worst properties of humanity are manifested in these unsavory creatures. 

A morphed and twisted union of human and swine flesh which stands on two legs, shorter than humans and in a perpetual hunch. They have boney claws instead of fingers and cloven swine-hooves instead of feet. Large tusks protrude aggressively from the jaw, as if reaching for victims. Red glowing, narrowed eyes glinting in the dark with malice. 

Beware the cesspits, the sewers, the bogs and marshes - any place where filth is abundant, for this is where the Swine thrive. They themselves are either impervious to the filth, or die too fast for it to matter, and will eat *anything*, with a particular appetite for flesh. They make it a particular point to bleed their victims, while skinning them alive and gloating at their pain. They are semi-demonic and live out the inherent cruelty that stems from that. 

They multiply quickly and often stay localized to their den. But they occasionally venture into more civilized areas to acquire food - which is often the inhabitants of those places - and plunder. They keep regular pigs as both livestock and as a means of reproducing, as when they have need of more of their foul kind, their shamans will perform the same wicked rituals to turn those harmless pigs into Swine-Beasts. 

Due to the demon bound inside them, they are inherently and irredeemably evil. Cruelty amuses them, injustice means nothing to them. They exist solely to mulitply, feed and destroy. 

### Swine Hostility

#### Demonic Blood
**`-20` Hostility**: Suddenly, a Swine stops dead in its tracks, clawing at its skull and squealing in distorted pain, as demon horns spring from its forehead and the veins beneath its skin begin to glow in bright crimson. It grows to twice its size and hungrily peers around. 
* It gains `+30` maximum and current HP.
* It becomes [Berserked](strive-core.md#berserk).
* Its attacks deal an additional `+6` points of Bleeding damage. 

#### Filth & Darkness
**`-10` Hostility**: The foul Swine have prepared a trap! The battlefield is flooded with a nauseating miasma and covered in unnatural darkness! 
* All non-Swine with normal vision can only see up to `3` far.
* All non-Swine suffer `-1D` to all tests.

### Swine Belcher
This variant is small and stunted. Its legs are too short and deformed to be useful, so it stands on and walks with its hands, instead. But don't be fooled, this creature is not defenceless. Vile residue runs down its maw, hinting at its repugnant weaponry. 

* Power: Feeble, CR: `2`
* Roles: Sentry, Artillery
  * These disgusting little things are the sentries of the den. They are the ones who watch out for approaching enemies and will cause a terrible noise when they notice anything out of the ordinary, calling allies over to come take a look. 
  * By itself, this creature is a very low challenge. Employ it with allies nearby who it can alert, should the PCs fail to eliminate it quickly. 
* Behavior: 
  * Curious and investigative. 
  * Noisy - squeals and grunts to itself frequently. 
  * Underdog - avoids other Swine and tends to get pushed around by them. 
  * Dislikes bright light and can see well in the dark.

| Agi   | Awar  | Str   | Tough | Wit   | Arc   |
| ----- | ----- | ----- | ----- | ----- | ----- |
| 4     | 4     | 2     | 1     | 1     | 0     |

| BI     | Sprint | Stabil | Def    | FS     | HP  | Exhaustion |
| ------ | ------ | ------ | ------ | ------ | --- | ---------- |
| 9      | 3      | 0      | 2      | 2 Acid | 10  | 2          |

Traits: [Disease-Ridden](strive-core.md#disease-ridden--1-point-1-cr), [Light-weight](strive-core.md#light-weight-2-points--1-cr), [Vulnerable](strive-core.md#vulnerable-2-points--2-cr) to Bleeding `+6`

Assets: Tattered Rags (Clothing)

Skills:
* Observation, level: `3`
* Bite (Agi/Str):
  * Chomp down on a target. 
  * Level: `2`, AP: `2`, Ob: Opposed, Melee, `1D4 + Strength` Piercing damage, Innate
* Putrid Vomit (Agi/Awar):
  * Throw up a projectile of lumpy stomach acid and 'shoot' it at a target. 
  * Level: `4`, AP: `2`, Ob: Opposed, Ranged: `10`, `2D4` Acid damage, [Prefer Range](strive-core.md#weapon-properties), Innate

### Swine Champion
This variant stands tall and proud, its wrinkled skin riddled with scars. Its tusks curl proudly, like a jaw-borne crest. 

* Power: Elite, CR: `7`
* Roles: Commander, Guardian
  * The strongest and toughest of the swine. A defender and conqueror. It has grit and wit at its disposal. Very rare and a very dangerous creature that will defend allies and inspire confidence in them. 
  * Employ this enemy to guard high value allies, like a shaman. 
* Behavior: 
  * Roams around whomever it is protecting, which is usually expected to be a shaman. 
  * Noisy - squeals and grunts to itself frequently. 
  * Usually the second in command, it demands respect from its lesser brethren, and will enforce its will if necessary. 
  * Dislikes bright light and can see well in the dark.

| Agi   | Awar  | Str   | Tough | Wit   | Arc   |
| ----- | ----- | ----- | ----- | ----- | ----- |
| 3     | 2     | 4     | 5     | 3     | 0     |

| BI     | Sprint | Stabil | Def    | FS         | HP  | Exhaustion |
| ------ | ------ | ------ | ------ | ---------- | --- | ---------- |
| 8      | 4      | 2      | 4      | 3 Piercing | 50  | 5          |

Traits: [Vulnerable](strive-core.md#vulnerable-2-points--2-cr) to Bleeding `+6`, [Hyperactive](strive-core.md#hyperactive--7-points-4-cr) + Disruptive

Assets: Spear, Medium Shield, Light Armor

Skills:
* Shield, level: `5`
* Unarmed Combat, level: `3`
* Weapon \<Spear\>, level: `5`
* Tusked Maw (Agi/Str):
  * As a last ditch defence, teeth and strength of jaw may serve. 
  * Level: `3`, Innate
    * Bite:
      * Chomp down on a target. 
      * AP: `2`, Ob: Opposed, Melee, `1D4 + Strength` Piercing damage
    * Gore:
      * Slam into a target with your massive tusks. 
      * AP: `2`, Ob: Opposed, Melee, `1D6 + Strength` Bludgeoning damage
* Swine Commanding (Tough/Wit):
  * A champion commands respect and obedience.
  * Level: `4`, Innate
    * Bestial Roar:
      * Instill fear and doubt into your victims' hearts. All within `10` of you suffer `-1` AP and are Terrified of you.
      * AP: `2`, Ob: Opposed by [Self-Control](strive-core.md#self-control-toughtough), Ranged, Vocal
    * Hit That One!:
      * [Mark](strive-core.md#marked) a ST of choice, for `2` rounds, up to `10` away.
      * AP: `1`, Ob: 2, Ranged, Vocal
    * You Die When I Let You!:
      * **Reaction**: Once in a battle, when an ally's HP are reduced to `0`, they are instead reduced to your achieved number of hits. 
      * AP: `1`, Ranged, Vocal

### Swine Lunger
This variant is as almost as small as a Belcher, and has atypically short tusks. Perhaps a youngling? It is also quite lean and moves with uncanny precision, for a Swine. 

* Power: Regular, CR: `3`
* Roles: Ambusher, Disruptor, Shock-Trooper
  * A reckless fighter who will happily leap into a group of enemies and begin causing chaos amidst their ranks. 
  * Employ as a disruptor of tight formations. 
* Behavior: 
  * Tends to stick to the shadows, from which to jump enemies. 
  * Noisy - squeals and grunts to itself frequently. 
  * Dislikes bright light and can see well in the dark.

| Agi   | Awar  | Str   | Tough | Wit   | Arc   |
| ----- | ----- | ----- | ----- | ----- | ----- |
| 6     | 2     | 3     | 2     | 2     | 0     |

| BI     | Sprint | Stabil | Def    | FS         | HP  | Exhaustion |
| ------ | ------ | ------ | ------ | ---------- | --- | ---------- |
| 10     | 4      | 0      | 3      | 4 Slashing | 20  | 1          |

Traits: [Vulnerable](strive-core.md#vulnerable-2-points--2-cr) to Bleeding `+6`

Assets: Tattered Rags (Clothing), Dagger x2

Skills:
* Stealth, level: `4`
* Weapon \<Dagger\>, level: `5`
* Lunge (Agi/Agi):
  * Lunge up to `7`, dealing damage to all foes in your path with your weapons. Does not provoke [Opportunity Attacks](strive-core.md#opportunity-attacks). Causes `+1` Exhaustion to self. 
  * Level: `5`, AP: `3`, Ob: Opposed, Melee, MST, `1D4 + Strength` Slashing damage, Innate
* Vault & Jab (Agi/Agi):
  * Jump over an adjacent enemy, landing behind them, and attack them. Does not provoke [Opportunity Attacks](strive-core.md#opportunity-attacks). Causes `+1` Exhaustion to self. 
  * Level: `4`, AP: `3`, Ob: Opposed, Melee, ST, `1D6 + Strength` Slashing damage, Innate

### Swine Ogre
A hulking mass of Swine and muscle, towering above all around. Despite its imposing nature, it frequently looks to the other Swine for guidance. It almost looks sleepy, except in moments of violence. 

* Power: Regular, CR: `5`
* Roles: Disruptor, Tank
  * Too dumb to realize any peril it might be in, it will happily stride straight into the middle of an enemy formation and is quite capable of staying there for a while. 
  * Employ as a distraction - a meat shield to draw the fire of enemies. 
* Behavior: 
  * Tends to sit around lazily, almost absent-mindedly. A dullard only excited by the prospects of violence. 
  * Noisy - squeals and grunts to itself frequently. 
  * Dislikes bright light and can see well in the dark.

| Agi   | Awar  | Str   | Tough | Wit   | Arc   |
| ----- | ----- | ----- | ----- | ----- | ----- |
| 1     | 1     | 6     | 6     | 1     | 0     |

| BI     | Sprint | Stabil | Def    | FS         | HP  | Exhaustion |
| ------ | ------ | ------ | ------ | ---------- | --- | ---------- |
| 3      | 4      | 4      | 1      | 2 Bludgeoning | 60  | 7          |

Traits: [Vulnerable](strive-core.md#vulnerable-2-points--2-cr) to Bleeding `+6`

Assets: Tattered Rags (Clothing), Large Crusher

Skills:
* Weapon \<Large Crusher\>, level: `2`
* Slam (Str/Tough):
  * Slam into a victim, knocking them `Strength * 1` backwards.
  * Level: `4`, AP: `2`, Ob: Opposed, Melee, ST, `Strength` Bludgeoning damage, Innate
* Tusk Thrust (Agi/Str):
  * Slam into a **ST** with your enormous tusks, imapling your victim upon them. 
  * Level: `3`, AP: `2`, Ob: Opposed, Melee, ST, `1D6 + Agility` Piercing damage, Innate

### Swine Shaman
An intelligent and cruel leader among the Swine. Its gaze attentively surveys all, as it stands proudly, in relatively clean clothes and at the center of Swine society. The bright crimson in its surface-level veins glows faintly. Elaborate arrangements of bones sewn to its clothes lend it an air of dark majesty. 

* Power: Regular, CR: `7`
* Roles: Commander, Supporter
  * It hangs back and lets its lesser brethren do the dirty work for it. But it will also ensure they succeed, as you cannot trust those buffoons with anything on their own.
  * Employ as a boss encounter, coupled with several other Swine, most notably at least one Swine Champion. 
* Behavior: 
  * Can usually be found in its den, scheming and plotting, mistreating 'life-stock' and making clothes from 'people-skin'. Or, found leading raids on the territories of 'civilized' folk. 
  * Noisy - squeals and grunts to itself frequently. 
  * Dislikes bright light and can see well in the dark.

| Agi   | Awar  | Str   | Tough | Wit   | Arc   |
| ----- | ----- | ----- | ----- | ----- | ----- |
| 2     | 2     | 3     | 4     | 5     | 6     |

| BI     | Sprint | Stabil | Def    | FS         | HP  | Exhaustion |
| ------ | ------ | ------ | ------ | ---------- | --- | ---------- |
| 9      | 3      | 0      | 2      | 2 Piercing | 40  | 4          |

Traits: [Vulnerable](strive-core.md#vulnerable-2-points--2-cr) to Bleeding `+6`

Assets: Fine Rags (Clothing), Large Crusher

Skills:
* Magic School \<Hexing\>, level: `5`
* Medicine, level: `3`
* Bite (Str/Tough):
  * Chomp down on a target. 
  * Level `2`, AP: `2`, Ob: Opposed, ST, Melee, `1D4 + Strength` Piercing damage, Innate
* A Leader Of Swine (Wit/Wit):
  * A shaman commands respect and terror.
  * Level: `5`, Innate
    * Fire Up The Blood:
      * Strike up a haunting chant, in demonic language, stirring the blood of your fellow Swine. One of of them, up to `15` away is enraged, and overwhelmed with their demoic blood, which starts leaking out of their eyes and nostrils. Until the end of combat, every tick, they suffer `5` points of bleeding damage (the Swine's vulnerability to bleeding damage does not get triggered by this), but also deal an additional `8` points of bludgeoning damage on every successful attack. 
      * AP: `3`, Ob: `2`, ST (ally Swine), Ranged: `15`, Vocal
    * Drums Of Terror:
      * Beating on a drum with a... face... stretched across it, instill terror in your foes. Every non-Swine in a `15` radius around must succeed a Self-Control test, or else become [Terrified](strive-core.md#terrified) of the shaman. 
      * AP: `2`, Ob: Opposed by Self-Control + 1, MST, Ranged: `15`, Auditory
    * You Die When I Let You!:
      * **Reaction**: Once in a battle, when an ally's HP are reduced to `0`, they are instead reduced to your achieved number of hits. 
      * AP: `1`, Ranged, Vocal

### Swine Skewerer
This variant has full dark-red fur and much shorter tusks. It moves deftly, albeit sloppily. 

* Power: Regular, CR: `5`
* Roles: Artillery, Trapper
  * A hunter and trapper, it tends to prefer indirect confrontation. 
  * Employ as a back-liner and ambusher, who will prepare the battlefield with dangerous traps ahead of time. 
* Behavior: 
  * Usually looking for and stalking prey, until finally striking from concealment. 
  * Dislikes bright light and can see well in the dark.

| Agi   | Awar  | Str   | Tough | Wit   | Arc   |
| ----- | ----- | ----- | ----- | ----- | ----- |
| 5     | 3     | 4     | 3     | 2     | 0     |

| BI     | Sprint | Stabil | Def    | FS         | HP  | Exhaustion |
| ------ | ------ | ------ | ------ | ---------- | --- | ---------- |
| 10     | 4      | 0      | 2      | 4 Piercing | 30  | 4          |

Traits: [Vulnerable](strive-core.md#vulnerable-2-points--2-cr) to Bleeding `+6`, [Poisoner](strive-core.md#poisoner--4-points-2-cr)

Assets: Tattered Rags (Clothing), Javelin x8, Bear Trap x3

Skills:
* Observation, level: `3`
* Stealth, level: `5`
* Throw Javelin (Agi/Str):
  * Throw a javelin at a **ST**. 
  * Level: `4`, Ob: Opposed, Ranged: `10`, ST, `1D8` Piercing damage, Innate

### Swine Slasher
This variant is lanky and sways a little. 

* Power: Regular, CR: `4`
* Roles: Brawler, Shock-Trooper
  * Employ as a front line fighter and cannon-fodder. Not meant to be particularly challenging, but rather as a wall of flesh in the way of high value targets. 
* Behavior: 
  * Noisy - squeals and grunts to itself frequently. 
  * Dislikes bright light and can see well in the dark.

| Agi   | Awar  | Str   | Tough | Wit   | Arc   |
| ----- | ----- | ----- | ----- | ----- | ----- |
| 2     | 2     | 4     | 3     | 1     | 0     |

| BI     | Sprint | Stabil | Def    | FS         | HP  | Exhaustion |
| ------ | ------ | ------ | ------ | ---------- | --- | ---------- |
| 5      | 3      | 1      | 2      | 3 Slashing | 30  | 4          |

Traits: [Vulnerable](strive-core.md#vulnerable-2-points--2-cr) to Bleeding `+6`

Assets: Tattered Rags (Clothing), Axe, Light Shield

Skills:
* Shield, level: `3`
* Weapon \<Axe\>, level: `3`

### Swine Stomper
This variant is massive and strong. Most of its body is covered in dark, dirty clumped up fur. The tusks are menacing weapons of their own. 

* Power: Regular, CR: `5`
* Roles: Brawler, Disruptor
  * These hulking beasts represent the swine-folks front line fighters. They protect the squalid den and stomp intruders who threaten the shaman. 
  * Employ as a front line fighter. May be taken down quickly, as it will not dodge, so consider using more than one in a fight. Intended to be a wall of flesh in the way toward high value targets. 
* Behavior: 
  * Very aggressively pushes enemies around. 
  * Bullies other Swine who aren't champions or shamans. 
  * Noisy - squeals and grunts to itself frequently. 
  * Dislikes bright light and can see well in the dark.

| Agi   | Awar  | Str   | Tough | Wit   | Arc   |
| ----- | ----- | ----- | ----- | ----- | ----- |
| 2     | 1     | 6     | 4     | 1     | 0     |

| BI     | Sprint | Stabil | Def    | FS         | HP  | Exhaustion |
| ------ | ------ | ------ | ------ | ---------- | --- | ---------- |
| 4      | 3      | 3      | 1      | 3 Slashing | 40  | 5          |

Traits: [Vulnerable](strive-core.md#vulnerable-2-points--2-cr) to Bleeding `+6`

Assets:
* Clothing: Swine Armored Rags, Large Crusher

Swine Armored Rags: Slashing `6`, Piercing `4`, Bludgeoning `3`, Acid `6`

Skills:
* Unarmed Combat, level: `4`
* Weapon \<Large Crusher\>, level: `3`
* Tusked Maw (Agi/Str):
  * As a last ditch defence, teeth and strength of jaw may serve. 
  * Level: `3`, Innate
* Bite:
  * Chomp down on a target. 
  * AP: `2`, Ob: Opposed, Melee, `1D4 + Strength` Piercing damage, Innate
* Gore:
  * Slam into a target with your massive tusks. 
  * AP: `2`, Ob: Opposed, Melee, `1D6 + Strength` Bludgeoning damage, Innate

## Veil Entities
Veil Entities are unlike any other. They are strange and unfathomable things from a dimension, or other form of existence unlike any we know. These entities aren't necessarily evil, nor are they particularly interested in causing harm, if indeed they are capable of sentience at all. It is their very nature that is harmful to ours. Fortunately, The Veil reclaims its denizens diligently. 

### The Monolith
A rough-hewn, crystalline monolith of obsidian color. Crimson veins pulsate gently, just beneath the surface. It draws every gaze towards it, whispering unknowable secrets and beckoning with malignity. Everyone within a `30` radius around it is affected and suffers `+1` [Bleeding](strive-core.md#bleeding) at the start of their turn and **cannot** look away, for as long as they have line of sight to it. The Monolith lasts for `5` rounds or `5` minutes, before The Veil reclaims it. When that happens, it explodes, dealing `1D8` [bludgeoning](strive-core.md#damage-types) damage and inflicting `+2` [Bleeding](strive-core.md#bleeding) to all within its radius.

### Perfection
A giant sphere of pure white light. Its surface is infinitely smooth. Nothing can stick to it, nothing can touch it. Everything that touches it, is thrown back, by `8`. And yet, every living thing in a `30` radius around it desires nothing more than to touch it, unless they succeed a Self-Control test at Ob `4` at the start of their turn. The Sphere lasts for `5` rounds or `5` minutes, before it vanishes, leaving behind darkness and emptiness that fills all hearts with unconsolable sorrow. Every creature in range is [Pacified](strive-core.md#pacified) for `1` round or minute.

### The Tar Mycelium
The entire scene is covered in a black, slimy web of tiny pulsating strands of a massive mycelium. This fungus grows quickly, rapidly enveloping everything it touches. The entire scene is considered Difficult Terrain. If a creature stands still for `2` turns, the fungus envelops them and begins devouring them alive. They suffer `1D4` [Acid](strive-core.md#damage-types) damage at the end of their second turn and after that, at the start of every turn they haven't yet moved.

### Cacophony of Flesh
An abominable mound of misshapen flesh, with countless tiny and several massive ragged tentacles protruding from it. As soon as it is able, it will violently thrash about, trying *desperately* to inflict vengeful violence upon all in its path. Lasts for `5` rounds or `5` minutes, before it melts away gruesomely. 

* Power: Regular, CR: `20`
* Roles: Tank, Brawler
  * This aberration is not your average foe. It is not to be engaged, as trying to slay it would be far too perilous.
* Behavior: 
  * Hungrily seeks and lurches towards victims to devour. 

| Agi   | Awar  | Str   | Tough | Wit   | Arc   |
| ----- | ----- | ----- | ----- | ----- | ----- |
| 5     | 5     | 20    | 20    | 1     | 0     |

| BI     | Sprint | Stabil | Def    | FS         | HP  | Exhaustion |
| ------ | ------ | ------ | ------ | ---------- | --- | ---------- |
| 4      | 1      | 5      | 1      | 5 Bludgeoning | 200 | 5          |

Traits: [Climber + Sticky](strive-core.md#climber--2-points-1-cr)

Skills: 
* Unarmed Combat: Level `5`, Innate
* Cacophony of Flesh (Agi/Agi):
  * Countless tiny and several massive ragged tentacles writhe and twitch with violent intent and an indescribable mound of flesh stands suspended above the ground, menacingly. 
    * Slam:
      * Slam down on a target with your entire body, enveloping them in a tentacled mass. They are rendered [Prone](./strive-core.md#prone) and [Grappled](./strive-core.md#grappled).
      * AP: 2, Ob: Opposed, `Strength` bludgeoning damage
    * Thrash:
      * Everything in a `3` radius around you is thrown backwards by `10` as your tentacles flail about, wildly.
      * AP:2
    * Devour:
      * Devour a **ST** creature in one swoop. As they enter your stomach, they are considered [Grappled](./strive-core.md#grappled) and cannot move on their own. They suffer `1D10` Acid damage at the start of your every turn. Only one creature may be devoured, at a time. You can spit out a creature you devoured, at no AP cost.
      * AP: 2, Ob: Opposed

### The Puppeteer
A giant stick-figure, shrouded in swirling darkness and blurred edges. All corpses, no matter how old, within `300` squares around the Puppeteer begin to move again. They arise from their tombs, graves and battlefields, to enact terrible vengeance on the living. The Puppeteer lasts for several days. Should The Puppeteer be called again from The Veil in the time it is already present, then several more days will be added to the time it may escape The Veil. 

## Undead
Whether they occur naturally or unnaturally, both your typical undead and some more unusual specimen may haunt your world. While the Fantasy Module assumes them to be mindless monsters, you may of course decide for your world that they may in fact retain some if not all of their sapience. 

### Alp
The Alp is a predator, yet it preys not on flesh, but on raw fear itself. For this reason, it often encroaches on civilization, where it causes streaks of never ending nightmares for the people. They can take this spiel so far as to drive their victims insane. Suicides in villages haunted by Alps are not uncommon.

This hunched humanoid is pale and haggard. Its face is featureless, devoid of eyes and mouth. Long claws at the ends of its three fingers clarify its hostile intent. 

Alps are a fairly common occurence throughout the world. How they reproduce is a bit of a mystery, though it is assumed to be related victims taking their own lives. In a way, the Alp's condition might be carried like a self-perpetuating curse. Fact is that the graves of suicides often end up empty just a few days later. Although such graves are often regarded as sacrilegious and are ill-favored by the locals, which may simply have decided they have a better use for the space or valuables the victim was buried with. 

* Power: Regular, CR: `6`
* Roles: Ambusher
  * Employ as an investigation and moderate combat challenge. 
  * If you want to ramp up the challenge, have the encounter begin near a civilian victim which the Alp is about to or already has put to sleep, so it can immediately use "Nightmare". 
* Behavior: 
  * Stays close to civilization. May sometimes even hide inside towns and cities. 
  * Only active at night. Tends to hibernate during the day, in a well hidden location. 

| Agi   | Awar  | Str   | Tough | Wit   | Arc   |
| ----- | ----- | ----- | ----- | ----- | ----- |
| 4     | 3     | 3     | 3     | 3     | 5     |

| BI     | Sprint | Stabil | Def    | FS         | HP  | Exhaustion |
| ------ | ------ | ------ | ------ | ---------- | --- | ---------- |
| 10     | 4      | 0      | 3      | 2 Slashing | 30  | 2          |

Skills: 
* Stealth: Level `3`
* Alp Powers (Wit/Arc):
  * Level: `7`
  * Innate telepathic powers that only an Alp has. 
    * Induce Nightmare:
      * Induces nightmares on all nearby (`20` radius around the Alp) sleeping characters. This strengthens the Alp, removing any active Injuries from it and granting it unnatural strength and toughness. It gains `+3` strength, `+3` toughness and `+2` bonus dice to "Rend" and regains `1D10` HP for every nightmare it induces, for `6` turns or `6` minutes. Any creature with a nightmare can be woken up (in any way you like), at Ob `3`. 
      * Does not stack: Every sleeping character can only be affected once. This resets when they wake up.
      * AP: `1`
    * Induce Sleep:
      * Forces the victim to fall asleep, on the spot. They become unconscious, but can be woken through physical harm or a very strong shaking. The number of `hits + 1` achieved over the victim dictates the Ob for tests to wake them up. 
      * AP: `1`, Ob: Opposed by Self-Control, ST, Ranged: `20`, Psionic
* Rend (Agi/Str): 
  * Tear a victim to shreds. 
  * Level: `3`, AP: `2`, Ob: Opposed, ST, Melee, `1D8 + Strength` Slashing damage

## Void Demons
When a soul is thrust into the void between realities, it is stretched infinitely thin. Unable to fill the void, it snaps and implodes, bouncing back into reality, but broken. It cannot function as it once did and furthermore, keeps open a tear to the void. It apparates as a monster of swirling shadow, not quite corporeal, yet not fully ethereal. 

Desperate to fill the void within them, they seek out any source of heat and light and try to absorb them. The souls of living things are of particular interest, as a Void Demon desires to be made whole again. The only way it knows how, is by trying to merge its soul with another. As souls generally occupy a host and will not budge, the host must first be eliminated. As such, Void Demons act with utmost hostility towards living things and will stop at nothing to kill them. 

A Void Demon does not speak and is neither sapient, nor sentient. Trying to reason with such a thing would be folly, as it would not answer with anything but violence. 

### Void Stalker
This variant of Void Demon is vaguely humanoid, its amorphous face stretched out like a beak and its arms ending in spikes of hardened darkness. 

* Power: Feeble, CR: `1`
* Roles: Ambusher, Multiplier
  * A simple, yet tricky foe, which is difficult to harm with mundane means and which will try to spawn more of its own kind, by inflicting damage to its victims. A challenge for the careless. Employ as a challenge that can increase its own intensity if left alive too long. 
* Behavior: 
  * Curious and investigative. 
  * Noisy - squeals and grunts to itself frequently. 
  * Underdog - avoids other Swine and tends to get pushed around by them. 

| Agi   | Awar  | Str   | Tough | Wit   | Arc   |
| ----- | ----- | ----- | ----- | ----- | ----- |
| 4     | 4     | 2     | 1     | 0     | 0     |

| BI     | Sprint | Stabil | Def    | FS     |
| ------ | ------ | ------ | ------ | ------ |
| 9      | 3      | 0      | 1      | 2 Acid |

Traits: 

Skills:
* 
