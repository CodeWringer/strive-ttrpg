<div style="text-align: center; font-size: 6rem; line-height: 4rem; margin-top: 2.5rem;">STRIVE</div>
<div style="text-align: center; font-size: 4rem">Fantasy Module</div>
<div style="text-align: center; font-size: 1rem">Version 11 (Playtest)</div>

# Introduction
This is the Module containing the rules enabling play in a medieval fantasy game world, which includes supernatural monsters and magic. Only the differences and additions to the core rules are included in this document. 

This Module is best suited for a medium fantasy setting. It introduces magic, which is a **powerful** tool, that comes with great risk. Mages who exert themselves too much may fail their spell cast, which results in a Backfire. But the likelihood of failure is manageable.

The Module introduces:
* The [Arcana](#arcana-arc) Attribute.
* [Magic](#magic) rules.
* Medieval/fantasy themed [Armors](#armor), [Shields](#shield-types), [General Assets](#general-assets), [Weapons](#weapon-types) and [Skills](#lists-of-skills).

There is a [compendium document](./strive-fantasy-game-masters-resource.md) reserved solely for the GM, containing additional resources for them to draw from.

# Table of Contents
- [Introduction](#introduction)
- [Table of Contents](#table-of-contents)
- [Glossary](#glossary)
- [Credits](#credits)
- [License](#license)
- [Character](#character)
  - [Attributes](#attributes)
    - [Arcana (Arc)](#arcana-arc)
  - [Corruption](#corruption)
- [Magic](#magic)
  - [Testing Magic](#testing-magic)
  - [Spell Intensity (SI)](#spell-intensity-si)
  - [Arcane Overheat \& Slag](#arcane-overheat--slag)
  - [Rituals](#rituals)
  - [Spell-Backfire](#spell-backfire)
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
      - [Using Runes](#using-runes)
      - [Creating Runes](#creating-runes)
    - [Magic Scrolls](#magic-scrolls)
      - [Using Magic Scrolls](#using-magic-scrolls)
      - [Creating Magic Scrolls](#creating-magic-scrolls)
    - [Malevite](#malevite)
      - [Malevite Side-Effects](#malevite-side-effects)
  - [Memorum](#memorum)
  - [Magic Momentum Actions](#magic-momentum-actions)
- [The Veil](#the-veil)
- [Appendix](#appendix)
  - [Character Creation](#character-creation)
    - [Determine Abilities](#determine-abilities)
      - [Choosing Attributes](#choosing-attributes)
        - [Manual Attribute Assignment](#manual-attribute-assignment)
        - [Semi-Random Attribute Assignment](#semi-random-attribute-assignment)
      - [Choosing Skills](#choosing-skills)
  - [Assets Appendix](#assets-appendix)
    - [General Assets](#general-assets)
    - [Armor](#armor)
      - [Armor Traits](#armor-traits)
      - [Light Armor](#light-armor)
      - [Medium Armor](#medium-armor)
      - [Heavy Armor](#heavy-armor)
    - [Shield Types](#shield-types)
      - [Shield Traits](#shield-traits)
      - [Light Shield](#light-shield)
      - [Medium Shield](#medium-shield)
      - [Heavy Shield](#heavy-shield)
    - [Weapon Types](#weapon-types)
      - [Weapon Traits](#weapon-traits)
      - [Axe](#axe)
      - [Chained Blade](#chained-blade)
      - [Crusher](#crusher)
      - [Light Blade](#light-blade)
      - [Long Blade](#long-blade)
      - [Polearm](#polearm)
      - [Short-Bow](#short-bow)
      - [Longbow](#longbow)
      - [Crossbow](#crossbow)
      - [Firearm](#firearm)
  - [Lists of Skills](#lists-of-skills)
    - [Physical Skills](#physical-skills)
      - [Rune-Using (Agi/Wit)](#rune-using-agiwit)
      - [Sailing (Awar/Wit)](#sailing-awarwit)
      - [Weapon \<Axe\> (Str/Str)](#weapon-axe-strstr)
      - [Weapon \<Light Blade\> (Agi/Str)](#weapon-light-blade-agistr)
      - [Weapon \<Long Blade\> (Agi/Str)](#weapon-long-blade-agistr)
      - [Weapon \<Chained Blade\> (Agi/Agi)](#weapon-chained-blade-agiagi)
      - [Weapon \<Crusher\> (Str/Tough)](#weapon-crusher-strtough)
      - [Weapon \<Polearm\> (Str/Tough)](#weapon-polearm-strtough)
      - [Weapon \<Short-Bow\> (Agi/Awar)](#weapon-short-bow-agiawar)
      - [Weapon \<Longbow\> (Awar/Str)](#weapon-longbow-awarstr)
      - [Weapon \<Crossbow\> (Awar/Awar)](#weapon-crossbow-awarawar)
      - [Weapon \<Firearm\> (Awar/Tough)](#weapon-firearm-awartough)
    - [Knowledge Skills](#knowledge-skills)
      - [Heraldry (Awar/Wit)](#heraldry-awarwit)
      - [Magic School \< School \> (\< Attribute \>)](#magic-school--school---attribute-)
    - [Artisan Skills](#artisan-skills)
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
    - [Demonology (Arc/Wit)](#demonology-arcwit)
    - [Divination (Arc/Wit)](#divination-arcwit)
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
  - [List of Character Traits](#list-of-character-traits)
    - [Anti-Mage](#anti-mage)
    - [Armored Confidence](#armored-confidence)
    - [Breath Weapon](#breath-weapon)
    - [Hot-Head](#hot-head)
    - [Hyperattentive](#hyperattentive)
    - [Radiator](#radiator)
    - [Tempered](#tempered)
  - [Archetype Characters](#archetype-characters)
    - [The Arcaenologist](#the-arcaenologist)
    - [The Performer](#the-performer)
    - [The Surgeon](#the-surgeon)
    - [The Tired Monster Hunter](#the-tired-monster-hunter)
    - [The Warboss](#the-warboss)
- [Fantasy Game-Masters Resource](#fantasy-game-masters-resource)
- [Creature Compendium](#creature-compendium)
  - [Cursed](#cursed)
    - [Werewolf](#werewolf)
  - [Corruptions](#corruptions)
    - [Hunched Dread](#hunched-dread)
    - [Huskfallen](#huskfallen)
    - [Tentacled Tarbeast](#tentacled-tarbeast)
      - [The Flesh is Malleable](#the-flesh-is-malleable)
    - [Threaded Terror](#threaded-terror)
    - [Time-Eater](#time-eater)
  - [Demons](#demons)
    - [Demon Hostility](#demon-hostility)
      - [Consuming Rage](#consuming-rage)
      - [Molten Envy](#molten-envy)
    - [Major Demon Hostility](#major-demon-hostility)
      - [Hell On Earth](#hell-on-earth)
      - [Darkness Is Coming!](#darkness-is-coming)
      - [Drown In Grief!](#drown-in-grief)
    - [Lesser Demons](#lesser-demons)
      - [Lesser Demon of Hatred](#lesser-demon-of-hatred)
      - [Dread Guard](#dread-guard)
      - [Faceless Hunter](#faceless-hunter)
      - [Lesser Wendigo](#lesser-wendigo)
      - [Possessed Zombie](#possessed-zombie)
      - [Spineling](#spineling)
      - [Taskmaster](#taskmaster)
    - [Greater Demons](#greater-demons)
      - [Greater Demon Of Hatred](#greater-demon-of-hatred)
        - [First Stage](#first-stage)
        - [Second Stage](#second-stage)
          - [Unstoppable Hatred](#unstoppable-hatred)
      - [Greater Wendigo](#greater-wendigo)
      - [Greater Demon of Engorgement](#greater-demon-of-engorgement)
      - [Doom Bringer](#doom-bringer)
      - [Hollow Gazer](#hollow-gazer)
      - [Preacher](#preacher)
  - [Swine-Beasts](#swine-beasts)
    - [Swine Do Not Negotiate](#swine-do-not-negotiate)
    - [Swine Tactics](#swine-tactics)
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
    - [Undead Hostility](#undead-hostility)
      - [Rise Again](#rise-again)
    - [Alp](#alp)
    - [Bloated Shambler](#bloated-shambler)
    - [Bone Spider](#bone-spider)
    - [Ghoul](#ghoul)
    - [Revenant](#revenant)
    - [Spine Thresher](#spine-thresher)
    - [Terrorghast](#terrorghast)
    - [Zombie](#zombie)
  - [Voidlings](#voidlings)
    - [Void's Breath](#voids-breath)
    - [Void's Hunger](#voids-hunger)
    - [Void's Lament](#voids-lament)

# Glossary

| Term                                                        | Meaning / Description  |
| ----------------------------------------------------------- | ---------------------- |
| [Abyssalite](#abyssalite)                                   | A material that amplifies the flow of magic. Can be processed into Runes and Magic Scrolls. |
| [Amberite](#amberite)                                       | A material that dampens the flow of magic. Can be processed into Ambersteel. |
| [Ambersteel](#ambersteel)                                   | A material that strongly dampens the flow of magic. |
| [Arcana (Arc)](#arcana-arc)                                 | An Attribute that describes a Character's innate mastery of magic. Finds use in determining Arcane Overheat thresholds. |
| [Arcane Engine](#arcane-engine)                             | Enables the use of impure Malevite Orbs. |
| [Arcane Overheat](#arcane-overheat--slag)                   | A number that builds up within a Character as they utilize magic, which is easily reduced. |
| [Arcane Slag](#arcane-overheat--slag)                       | A number that builds up within a Character as they utilize magic, which lowers only slowly. |
| [Arcanosphere](#magic)                                      | An invisible force that spans the world, which enables the use of magic. |
| [Broiling Arcane Overheat](#arcane-overheat--slag)          | The third Arcane Overheat threshold, which is *perilous*. |
| [Cerebillium](#cerebillium)                                 | A material that can *think*. Commonly used as the brains of golems and other such constructs. |
| [Cold Arcane Overheat](#arcane-overheat--slag)              | The first Arcane Overheat threshold, which is *mostly safe*. |
| [Consuming Arcane Overheat](#arcane-overheat--slag)         | The fourth and final Arcane Overheat threshold, which is *mortally perilous*. |
| [Magic Echo](#magic-echoes)                                 | The residual disturbance of the Arcanosphere after the use of a Spell. |
| [Magic Negation](#magic-negation)                           | The ability to negate another mage's Spell. |
| [Magic School](#magic-school--school---attribute-)          | A special Skill that enables one type of magic use. |
| [Magic Scroll](#magic-scrolls)                              | An one-time use Asset that allows even non-mages to cast magic. |
| [Magic Spell](#magic)                                       | The name of a Magic School Skill's Expertises. Basically: magic Expertise -> Spell. |
| [Malevite](#arcane-engine)                                  | An artificial material made from the blood of mages or magical creatures. Allows very strong manipulation of the Arcanosphere. |
| [maximum Intensity](#spell-intensity-si)                    | A Magic School's Level sets the maximum Spell Intensity that a Spell can have. |
| [Memorum](#memorum)                                         | A fungus that can capture and preserve thoughts, emotions, Magic Echoes and even raw knowledge. |
| [OPN](#psionics-arcwit)                                     | Openness to [The Veil](#the-veil). |
| [Rune](#runes)                                              | An Asset that allows even non-mages to cast magic at will. |
| [SI](#spell-intensity-si)                                   | Spell Intensity dictates the strength of magic use. |
| [Smoldering Arcane Overheat](#arcane-overheat--slag)        | The second Arcane Overheat threshold, which is *risky*. |
| [Spell-Backfire](#spell-backfire)                           | Magic is risky. Failing a Test of a Magic School may result in a Spell-Backfire, which always causes some penalty for the mage, instead of their intended target(s). |
| [The Veil](#the-veil)                                       | The place that transcends this, or any, universe. The path to true enlightenment and absolute madness. |

# Credits
**Designer**: Nicolas 'Krubi' H.

My two small, yet inexorable groups of playtesters, whose feedback has been invaluable, without whom this game would not be any where near where it is now and who keep me motivated!

# License
This official STRIVE Module is licensed unter the same license as the STRIVE Core rules, which can be found at the following link. 
* https://github.com/CodeWringer/strive-ttrpg/blob/develop/documents/en/strive-core.md#license

# Character
New in this Module, is the Attribute [Arcana](#arcana-arc), which governs a Character's capacity for magic. 

## Attributes
Supplements to the [Core Attribute rules](./strive-core.md#attributes). 

### Arcana (Arc)
<img src="../../img/arcana.svg" style="width: 3rem; height: 3rem;"></img> Governs a Character's ability to control and sense magic flow, casting magic Spells or detecting lingering magic. 

This is the only Attribute that can have a Level of `0`, meaning playing a mage is a deliberate choice. 

Used to determine the [Arcane Overheat](#arcane-overheat--slag) thresholds.

## Corruption
A [Health Condition](./strive-core.md#condition) that, when it reaches `5`, causes the victim to mutate into a [Corruption monster](#corruptions)!

* Graded
* Shrug Off: `-1` point with a [Medicine](./strive-core.md#medicine-agiwit) [Test](#tests) with Ob `2`. 

# Magic
For this supplement, magic is assumed to be a mostly invisible supernatural force that runs all throughout, like a magnetosphere. Perhaps it could be called the *Arcanosphere*. How magic manifests itself, is up to the world the GM is running. Is there a verbal component? Must the mage trace arcane symbols into the air or onto some surface? Are the magical currents visible and glow eerily? This supplement makes no assumptions in this regard. 

Only a Character with [Arcana](#arcana-arc) can cast magic at will. What kind of magic, depends on the [Magic Schools](#list-of-magic-schools) the Character knows. There are offensive, defensive and manipulative [Schools Of Magic](#list-of-magic-schools). 

There may also be magic artifacts that can either cause magical effects on their own, or through Character interaction. With such artifacts, it may be possible for non-mages to cast magic. For that, see [Runes](#runes) and [Scrolls](#magic-scrolls). 

A *magic Spell* is the intended effect of using a [Magic School's](#magic-school--school---attribute-) [Expertises](./strive-core.md#expertise). Using such an Expertise is also referred to as *casting magic*, *casting a Spell* or other similar wordings. In mechanical terms, the [Expertises](./strive-core.md#expertise) are the **Spells** of a [School Of Magic](#list-of-magic-schools).

A mage can fail their [Test](./strive-core.md#tests) and thus suffer a [Spell-Backfire](#spell-backfire), which usually results in negative effects for the caster, instead of their intended target. 

[Spell Intensity](#spell-intensity-si) sets the strength of a magic Spell and how much [Arcane Overheat & Slag](#arcane-overheat--slag) it causes. 

## Testing Magic
[Testing](./strive-core.md#tests) a [Magic School Skill](#magic-school--school---attribute-), in order to cast a *magic Spell*, works as follows:

1. Determine the [Spell Intensity](#spell-intensity-si) (SI) to use. 
   1. The Level in the corresponding [Magic School Skill](#magic-school--school---attribute-) determines the maximum [SI](#spell-intensity-si) that can be picked. 
   1. Note that any Spell **must** be cast with a SI of *at least* `1`. This includes Learning Skills. 
2. Determine the Test's Ob. 
   1. Some Spells require an [Opposed Test](./strive-core.md#opposed-test), while others have a fixed or dynamic Ob, based on some formula. 
3. The dice for the Test are rolled. 
4. The Arcane Overheat dice are rolled, if necessary. They may cause [Spell-Backfires](#spell-backfire). 
5. Convert the SI to [Arcane Overheat & Slag](#arcane-overheat--slag). This **always** happens *after* the Spell is cast!
   1. If this brings the mage to a new [Arcane Overheat](#arcane-overheat--slag) threshold, its effects now apply. 

## Spell Intensity (SI)
**Spell Intensity (SI)** is the strength at which a magic spell is being cast. A higher number causes stronger and further reaching effects, but also more [Arcane Overheat & Slag](#arcane-overheat--slag). 

A spell's **maximum Intensity** is dictated by the Level in the corresponding [Magic School Skill](#magic-school--school---attribute-). However, the minimum SI for a spell cast is **always** `1`. 

## Arcane Overheat & Slag
Magic takes a toll on the caster's body and mind. As magic currents flow through their body, **Arcane Overheat** and **Arcane Slag** build up within them. Too much Arcane Overheat, and the mage will suffer various negative effects! 

**Arcane Slag** is the build-up of residual magical currents within the Character's body. You can think of these like residual radioactive particles, that only slowly escape the body, albeit less immediately harmful. 

A Character's base Arcance Overheat can never be less than their current Arcane Slag.

> A Character with an Arcane Slag of `3`, always has at least `3` Arcane Overheat!

When a mage casts magic, **one third** (RD and minimum `1`) of the [Spell Intensity](#spell-intensity-si) they choose equals the amount of Arcane Slag that builds up within them. The other two thirds turn into [Arcane Overheat](#arcane-overheat--slag). 

> = A spell cast at SI `1` causes `+1` Arcane Slag and *no* Arcane Overheat. 
> 
> = A spell cast at SI `3` causes `+1` Arcane Slag and `+2` Arcane Overheat. 
> 
> = A spell cast at SI `7` causes `+2` Arcane Slag and `+5` Arcane Overheat. 

The [Arcana](#arcana-arc) Attribute determines several thresholds. If the Character has an [Arcana](#arcana-arc) Level of less than `1`, calculate the thresholds as if it was Level `1`. That means non-mages have such thresholds, too! 

* **Cold**: Up to and including the `Arcana Level` is **safe**. 
  * [Spell-Backfires](#spell-backfire) cannot occur. 
* **Smoldering**: Up to and including the `Arcana Level * 2` is **risky**. 
  * For every Spell, you must roll `1D6`, if the die comes up as a `1`, you suffer a Spell-Backfire!
  * All spells are super-charged, with an automatic and free `+1` SI. 
* **Broiling**: Up to and including the `Arcana Level * 3` is **perilous**. 
  * For every Spell, you must roll `2D6`, if any die comes up as a `1`, you suffer a Spell-Backfire!
  * All spells are super-charged, with an automatic and free `+2` SI. 
* **Consuming**: Anything past the point of Broiling is **mortally perilous**. 
  * For every Spell, you must roll `3D6`, if any die comes up as a `1`, you suffer a Spell-Backfire!
  * All spells are super-charged, with an automatic and free `+3` SI. 
  * Suffer `1D8 + 2` [Pure damage](./strive-core.md#damage-types) every [Tick](./strive-core.md#ticks). At the end of every tick, reduces [Arcane Overheat & Slag](#arcane-overheat--slag) by `-1` point, each. 

> The thresholds of a mage with an Arcana of `3` are: `0-3` Cold, `4-6` Smoldering, `7-9` Broiling and `10+` Consuming. 

At the start of every Turn, or every `5` seconds outside combat, a mage automatically reduces their Arcane Overheat by `-1` point. They can actively **vent** their Arcane Overheat further - one point per [AP](./strive-core.md#action-points-ap) spent. 

`-1` point of Arcane Slag automatically leaves the Character's body, every `6` hours. If that time is spent in active rest or meditation - that means doing *nothing* besides rest -, then `-2` points leave the body, instead. 

Arcane Slag *can* affect non-mages, too! That implies they can also suffer Arcane Overheat (although that does not make them mages)! 

## Rituals
While most magic may be cast instantaneously, some requires special preparation and an investment of time. Such Ritual magic is often particularly powerful and requires uninterrupted focus to succeed. 

Some Rituals may require a minimum number of mages to take part, if it is to stand any chance of succeeding, while others may impose a limit of how many may join. Every mage that joins in the Ritual is considered a **Ritualist**, and for each of them, the Ritual's SI automatically increases by `+1`, at no additional cost. However, for Rituals with a minimum number of Ritualists, the SI increase only starts with the next Ritualist after the minimum. Every Ritual has a head Ritualist through whom the magic ultimately flows. They're the one in control of the Ritual's magic. 

All Ritual magic is stationary and must be performed uninterrupted for a certain time in order to succeed. Once the Ritual's time is up, a Test is required, to unleash its magic. If the Test is failed, the Ritual's magic still works, but may be weaker or have **side-effects**. If any Ritualist's [Concentration](./strive-core.md#concentration) is broken, the Ritual fails and **Backfires** catastrophically!

When starting the Ritual, the SI you choose dictates how many time increments it will take. 

Once a Ritual is fulfilled, its magic is released and all Ritualists who partook in the Ritual suffer [Arcane Slag and Overheat](#arcane-overheat--slag), same as for normal magic use.

Rituals may be strengthened by [Abyssalite](#abyssalite) and [Malevite Orbs](#malevite), or even require these things to work, at all. Whether a Ritual requires arcane symbols drawn onto a surface or some other medium, is up to the GM and their world. 

## Spell-Backfire
A **Spell-Backfire** is a critical blunder of a mage! They suffer negative effects and their spell does not get cast the way they intended!

Usually, a spell notes the effects that happen when a Backfire occurs. In case there are no specific effects, the mage suffers `+1` [Strain](./strive-core.md#stamina--strain). 

It is possible for another nearby mage to prevent the Spell-Backfire, if they [negate the Spell](#magic-negation) as a Reaction. This also applies even if the spell wouldn't affect them. If the other mage's attempt to negate the spell *also* Backfires, then both of the mages suffer the spell's effect at one greater [Intensity](#spell-intensity-si) level. 

A Spell-Backfire may occur when a mage suffers from [Arcane Overheat](#arcane-overheat--slag). 

## Magic Negation
It is possible to negate a Spell entirely, by absorbing it. The absorbing mage suffers the Spell's [Arcane Slag & Overheat](#arcane-overheat--slag), as if it was `+1` [SI](#spell-intensity-si) *and* they suffer Pure damage equal to the actual `SI * 2` (meaning, without the `+1` modification of the SI). No Test is made. 

Another mage's [Spell-Backfire](#spell-backfire) can be negated in the same way.

## Protection From Magic
Armor made from [Ambersteel](#ambersteel) can reduce the damage suffered through magical sources and reduce the [SI](#spell-intensity-si) of non-damaging spells. 

The [Quality Level](./strive-core.md#crafting--research-projects) of an armor or shield determines how much it protects the wearer. See [Ambersmithing](#ambersmithing-strwit) for the specific numbers. 

## Magic Echoes
Whenever magic is cast, a pale reflection of it remains, invisible to the naked eye, lingering for `SI * 4` hours, based on the magic spell's [Intensity](#spell-intensity-si) when it was cast. 

Those sensitive to magic can detect it and if they know the [Magic School](#magic-school--school---attribute-) whence the spell stems, they instinctively recognize the echo. Otherwise, they may need to succeed an [Arcana](#arcana-arc) Test at Ob `2` to determine the type of magic that was cast. The same Test may also determine an estimate of how old the echo is. 

Each echo has a unique aspect to it, like a finger-print. It is possible to capture a magic echo's finger-print, as well as some of the context when it was cast, in special devices, called [Magic Recorders](#general-assets). 

## Magic Things
No fantasy world would be complete without materials with uses for the supernatural or artifacts of immense power. This section introduces the basics of these things. 

Aside from the materials listed below, you are of course free to invent more as desired. 

### Abyssalite
**Abyssalite** is a hard and brittle mineral, that has the ability to *amplify the flow of magic*. It can only be acquired from the depths of the earth and is fairly rare. 

Its surface is unnaturally smooth and covered in a fine, iridescent shine. Underneath the smooth surface, one searches for depth and color in vain. It is as though the void itself is being contained by that iridescent shell. However, the more magic flows through it, the stronger its shell shines. This means that when any magically gifted creature touches Abyssalite, it shines stronger. 

Abyssalite is a hard and brittle mineral, prone to shattering if too much force is applied. This makes it difficult to shape. It is also fairly heavy, which makes it difficult to carry. A fist-sized Abyssalite chunk has a [Bulk](./strive-core.md#carrying-capacity) of `2`.

A chunk of the stuff grants one greater SI, without causing any additional [Arcane Overheat](#arcane-overheat--slag). In order to use the Abyssalite, the caster **must** be touching it. 

### Amberite
As magic is amplified by [Abyssalite](#abyssalite), its antithesis is called **Amberite**, a metal which dulls the effects of magic and slows any magic flow nearby it. 

Weapons made from Amberite are quite popular with witch and monster hunters alike, although fairly hard to come by, due to the difficulty in Amberite processing. 

Amberite is a crystalline material, that can be molten down and shaped, like iron. It glows weakly and translucently, in the fiery orange of the name-sharing amber stone. Near the edges, the glow fades to a dull reflection, like cooling molten lava. 

It only occurs naturally in a few select places in the world, where the ground offers the right conditions. Amberite grows over time, in the right environment. It can take several decades for a finger-sized crystal to grow to the size of an adult man's forearm. Attempts to cultivate it are met with extreme difficulty. The right conditions for it to thrive are highly dependent on the soil's components, the influence of the Arcanosphere and proximity to volcanic activity. Due to the slow rate at which it grows, an Amberite farmer may not realize the lack of growth until well into a decade later. 

Prolonged exposure to Amberite can cause severe ill-effects with nausea and migranes being common symptoms. 

A fist-sized Amberite chunk is fairly heavy, with a [Bulk](./strive-core.md#carrying-capacity) of `3`. 

### Ambersteel
**Ambersteel** is a strictly anti-magic material. It should enjoy great attention in any fantasy world, where magic is a real and recognizable force. Magic is powerful and fearsome and thus, if not under control, can threaten to cause great pain and destruction. Ambersteel dampens that power and puts shackles on it. 

[Amberite](#amberite) can be processed into Ambersteel, which makes it a hard and flexible metal. The raw material heats slowly and must be kept in the fire for several days and nights, without interruption. When it finally reaches the right temperature, it will glow white, with a purple sheen. At that point, it can be hammered into shape. Constant re-heating ensures it stays at the right temperature and a final quenching in oil mixed with powdered [Abyssalite](#abyssalite) ensures it retains its flexibility and potency. If processed outside the optimal temperature, the material quickly grows brittle and will shatter if any stress is put on it. The Skill to use is [Ambersmithing](#ambersmithing-strwit). 

Due to the length of the process and the difficulty in keeping the right temperature, smiths capable of creating Ambersteel are rare. 

Ambersteel is also a fairly heavy material, albeit slightly lighter than [Amberite](#amberite). A fist-sized chunk has a [Bulk](./strive-core.md#carrying-capacity) of `1`. Weapons, shields and armor made from this material are `+1` [Bulkier](./strive-core.md#carrying-capacity). 

### Arcane Engine
A device that can channel and direct the power of a [Malevite Orb](#malevite) or [Rune](#runes). Can be activated through [Rune-Using](#rune-using-agiwit). 

Arcane Engines are mostly useful either as siege engines or as stationary constant magic casters. The more powerful the used [Malevite Orb](#malevite), the larger the engine. 

PI: `30`, TI: `1` Day, Ob: `+1`, requires:
* [Abyssalite](#abyssalite)
* A sturdy frame-material, like steel

The engine negates `Q` side-effect of the [Malevite Orb](#malevite).

### Cerebillium
**Cerebillium** is an odd material, that resembles white marble, with faintly glowing veins of green and turqoise running through it. This material is unique in that it always creates a small magical current on its own, which flows back and forth through the veins. 

These veins tend to grow more numerous over time and to "connect" with each other, forming an intricate web. This process is slow and it may take years for any significant change to become noticeable. 

These webs eventually become complex enough to form something of a "consciousness". Some of the oldest examples of Cerebillium slabs are said to have the intelligence of a small child!

When sufficient magic is sent flowing through it, the veins glow strongly and change shape, following the current. This can be used to alter the "brain". Alternate methods of altering the brain include scratching out veins, trimming the slab or - most difficult - "teaching". The Cerebillium consciousness is rarely advanced enough to understand morals or other subtle implications. Direct commands may work, but that depends on the density of the web. 

The veins do not spread to other materials. Only the bright marble-like substance seems to find their favor. Thus, cultivating greater amounts of Cerebillium is very difficult and requires synthesization of a very unique chemical compound, which is then left to crystallize over a long time. 

However, if done right, a well-trained Cerebillium core can be employed to animate mechanisms, even entire artifical bodies, enabling the creation of golems.

### Runes
Shards of [Abyssalite](#abyssalite) can be carved into **Runes**, which allow magic to flow through them in particular ways. Mechanically, they allow the casting of a particular spell of one of the [Schools Of Magic](#list-of-magic-schools), at a constant [Spell Intensity](#spell-intensity-si). 

Due to how Runes are always magically charged, they cannot be in the vicinity of **any other Runes**. This works a bit like how magnets with the same polarity repulse each other, but a lot more dangerous. This condition applies regardless of the type of magic each of the Runes hold. If two Runes are brought to a distance of `10` Squares or less to each other, they begin to glow, hum and rumble, as if to warn their bearers. Should they be brought to a distance of `8` Squares or less to each other, they both discharge the magic they hold and repulse each other. This means anyone immediately nearby suffers `3D6` Bludgeoning damage. The Runes are flung away from each other far enough to be at least `11` Squares apart. The Runes *may* be **destroyed** in the process. Roll a `D6` for each of the Runes - if the result is a `1` or `2`, the Rune is **destroyed**! 

It may be possible to circumvent this repulsion behavior by placing the Runes in a container made of [Ambersteel](#ambersteel). This requires the container to be of a [Quality Level](./strive-core.md#crafting--research-projects) equal to the highest of the Runes' [Spell Intensity](#spell-intensity-si).

#### Using Runes
To activate a Rune, it must be touched in the right spots and at the right intervals. Mistakes in the procedure can have disastrous results. 

In order to invoke a Rune:
* A [Rune-Using](#rune-using-agiwit) Test will invoke the spell of the Rune as expected. This costs `2` AP. 
* Failure in the Test results in a [Spell-Backfire](#spell-backfire). 
* The user accumulates one third (RD, but to no less than `1`) of the Rune's [Spell Intensity](#spell-intensity-si) as [Arcane Slag](#arcane-overheat--slag). 

#### Creating Runes
It takes great skill to carve Runes, as each Rune's shape and complexity depends in part on the size and shape of the [Abyssalite](#abyssalite) shard. The only way to get it right, is to *feel* the way the Rune must be shaped. Alternatively, the shard can be adjusted to be of equivalent size and shape as another Rune, but this requires considerable effort, as [Abyssalite](#abyssalite) is a brittle material, prone to shattering if too much force is applied. Thus, it must be carefully filed down to size. 

In order to craft a Rune:
* A Rune can only be made to cast one type of magic. So the carver has to pick one of the [Magic Schools](#list-of-magic-schools). 
* The carver has to succeed a [Rune Smithing](#rune-smithing-arcwit) Skill Test. 
  * The maximum Level at which a Rune can be created, depends on the carver's Skill Level. The Level of the Rune dictates the Level of the respective magic it will cast at. 
* After the carving, the Rune must be "primed" by a mage. This requires a success of a Test of the same [School Of Magic](#list-of-magic-schools) as the Rune holds, with Ob equal to the [Spell Intensity](#spell-intensity-si) of the Rune. 

If any of the Tests are not a success, the Rune is botched and the material cannot be used for another attempt. There is no room for mistakes. 

### Magic Scrolls
**Magic Scrolls** allow a single, specific spell to be cast by both mages and non-mages. Once used, the Magic Scroll burns up from the flow of magic and cannot be used again (even if the bearer material is fire-proof). Thus, these are single-use tools. 

Due to how Magic Scrolls are always magically charged, they cannot be in the vicinity of any other Magic Scrolls. This works a bit like how magnets with the same polarity repulse each other, but a lot more dangerous. This condition applies *only* to Magic Scrolls of **same the type of magic**. 

If two Magic Scrolls **of the same type** are brought to a distance of `10` Squares or less to each other, they begin to glow, hum and rumble, as if to warn their bearers. Should they be brought to a distance of `8` Squares or less to each other, they both discharge the magic they hold and repulse each other. This means anyone immediately nearby suffers `3D6` Bludgeoning damage. The Magic Scrolls are destroyed in the process! 

It may be possible to circumvent this repulsion behavior by placing the Magic Scrolls in a container made of [Ambersteel](#ambersteel). This requires the container to be of a [Quality Level](./strive-core.md#crafting--research-projects) equal to the highest of the Magic Scrolls' [Spell Intensity](#spell-intensity-si).

#### Using Magic Scrolls
In order to invoke a Magic Scroll:
* One must unfurl and hold it plainly in the direction the spell is to be cast, then trace the painted symbol on the Magic Scroll to "agitate" the primed magic. This costs `2` AP. 
* This causes no [Arcane Overheat](#arcane-overheat--slag), but the Magic Scroll is immediately destroyed upon use. It burns up magically (even if the material itself is fire-proof). 

#### Creating Magic Scrolls
In order to create a Magic Scroll:
* PI: `30`, TI: `1` Hour
* Powdered [Abyssalite](#abyssalite) must be painted onto the parchment, paper or other such material, in a shape specific to the magic spell the Magic Scroll will be able to cast. 
  * This requires a success of an [Artistry](./strive-core.md#artistry-agiawar) or [Artificing](#artificing-arcwit) Test, at Ob equal to the intended [Spell Intensity](#spell-intensity-si) of the Magic Scroll. 
* Then, the Magic Scroll must be "primed" by a mage. This requires a success of a Test of the same [School Of Magic](#list-of-magic-schools) as the Magic Scroll holds, with Ob equal to the [Spell Intensity](#spell-intensity-si) of the Magic Scroll. 

If any of the Tests are not a success, the Magic Scroll is botched and the material cannot be used for another attempt. There is no room for mistakes. 

### Malevite
Also known as blood jewel, Malevite is an entirely artificial material, made from the blood of mages or magical creatures, by use of great pressure, a constant arcanic charge and much patience. The more blood it is infused with, the purer the color and more powerful the artifact. 

A blood jewel is a perfectly smooth sphere, with coloration ranging from a foggy and muddy black, to a swirly crimson or at its purest, to a radiant crimson.

Once formed, a Malevite orb cannot be infused further. It rejects any more blood. 

Destroying such an artifact is not an easy feat. It requires a spike of pure [Ambersteel](#ambersteel) driven through it with great force. Doing so *may* tear a temporary hole in the fabric of reality. Also, when destroyed, the Malevite Orb de-compresses, releasing the blood it was made from in a spectacular hurricane of crimson. 

A Malevite orb is an artifact of very great power that can change the laws of physics and warp reality around it. To direct this power, requires an [Arcane Engine](#arcane-engine), wherein the orb functions like a super-charged battery. To build such a device requires a deep understanding of the arcane. 

There are four Quality Levels. Impure Malevite has side-effects and is not nearly as powerful as a purer blood jewel. 

PI: `100`, TI: `1` Day, Ob: `+2`, requires:
* A lot of Mage blood
* `3`, `9`, `27` or `81` Bulk of [Abyssalite](#abyssalite) (graded per purity level)

| Quality | Description | Side-Effects |
| ------- | ----------- | ------------ |
| Foggy   | Contains a single spell, at `SI 10`, which can only be controlled with an [Arcane Engine](#arcane-engine). | 5 |
| Murky   | Contains up to two spells, at `SI 30`, which can only be controlled with an [Arcane Engine](#arcane-engine). | 4 |
| Swirly  | Contains a weak reality-altering power, which can only be controlled with an [Arcane Engine](#arcane-engine). Can be almost anything, within reason. Things such as a low gravity field, anti-magic field, constant fog-emitter, elemental spewer and similar. | 3 |
| Pure    | Contains a reality-altering power. Practically anything is possible. The crowning achievement the power hungry and the insane. The closest you can get to god-hood. Requires no [Arcane Engine](#arcane-engine). It has transcended the need for such a paltry shackle. | 0 |

#### Malevite Side-Effects
All of the following is kept vague, because it would be hard to list all possible combinations in a way that makes sense while remaining concise. See the following as inspiration for the GM, who will finalize the side-effects. 

Side-effects (`2D6`):

| Roll | 1 Gravity               | 2 Time                   | 3 Souls                  | 4 Elemental              | 5 Psychic                | 6 Alteration             |
| ---- | ----------------------- | ------------------------ | ------------------------ | ------------------------ | ------------------------ | ------------------------ |
| 1    | High Gravity            | Slowed                   | Evicted                  | Acid                     | Terror                   | Create mutations         |
| 2    | Low Gravity             | Accelerated              | Attracted                | Frost                    | Confusion                | Restore purity           |
| 3    | Sideways Gravity        | Repeating                | Bound                    | Lightning                | Madness                  | Imbue with magic         |
| 4    | Attraction (Black-Hole) | Jumping forward          | Switched                 | Fire                     | Clairvoyance             | Nullify magic            |
| 5    | Repulsion               | Jumping backward         | Duplicated               | Light                    | Emotional cleansing      | Remove magic             |
| 6    | Anti-Gravity            | From alternate dimension | Burned                   | Sound                    | Pacified                 | Alter shape              |

Area of Effect (`1D4`): 

1. radius
2. wall
3. cone
4. line

Distance/radius: `3D20` Squares

Trigger (`1D6`):

1. Constant (no trigger, always active)
2. Periodic
   1. `1D4`: 1: Minutes, 2: Hours, 3: Days, 4: Weeks
   2. `1D100`: how many of the above
3. Vicinity `3D10` Square AoE radius
4. Sound `1D4`: 1: Perfectly still, 2: Quiet, 3: Loud, 4: Deafening
5. Light `1D4`: 1: Perfectly dark, 2: Dim, 3: Bright, 4: Blinding
6. Blood

## Memorum
A unique material, grown by a very specific family of fungus that thrives only in the deepest recesses of the world. 

It has found practical use as a means of preserving the immaterial - thoughts, emotions, [Magic Echoes](#magic-echoes) and even raw knowledge. 

## Magic Momentum Actions
These magic-themed Momentum Actions complement the [Core Momentum Actions](./strive-core.md#momentum-actions). 

| Heroic Act <br><img src="../../img/heroic-acts.svg" width="64px" height="64px"></img> | Heroic Act Momentum Shift | Heroic Act Description | Desperate Measure Description | Desperate Measure Momentum Shift | Desperate Measure <br><img src="../../img/desperate-measures.svg" width="64px" height="64px"></img> |
| ------------------------------------------------------------------------------------- | ------------------------- | ---------------------- | ----------------------------- | -------------------------------- | --------------------------------------------------------------------------------------------------- |
| Cool Down <br><img src="../../img/heroic-acts.svg" width="64px" height="64px"></img> | `-15` | Reduces a single PC's Arcane Overheat and Slag by `4` points, each. | Convert up to `10` points of a single PC's current Arcane Slag into `N * 3` Burning damage to all foes around them, in a `2` Square radius. The Slag is then removed. The PC suffers `1` point of Burning damage for each removed Slag point. | `+15` | Sizzling Eruption <br><img src="../../img/desperate-measures.svg" width="64px" height="64px"></img> |
| Tempered Arcane Overdrive <br><img src="../../img/heroic-acts.svg" width="64px" height="64px"></img> | `-30` | A single PC mage's spells are `+2` SI stronger, and generate no Arcane Slag, for `2` Rounds! | A single PC mage's spells are `+3` SI stronger, and generate neither Arcane Overheat nor Slag, for `2` Rounds! However, after those Rounds have passed, the mage always suffers `1D10 + 3` Arcane Slag (Combat ending early **doesn't** prevent this)! | `+30` | Strained Arcane Overdrive <br><img src="../../img/desperate-measures.svg" width="64px" height="64px"></img> |
| Spellbreaker <br><img src="../../img/heroic-acts.svg" width="64px" height="64px"></img> | `-20` | A chosen single PC mage may now [Negate Spells](#magic-negation) cast within `10` Squares of them without suffering any Arcane Slag or Overheat, for `3` Rounds! Note the mage *does* still suffer the damage. | All Spells cast within `10` Squares of a chosen single PC **must** now always target that PC. Positive Spells gain `+1` SI, while negative Spells lose `-1` SI. This effect lasts `3` Rounds. | `+15` | Arcane Lightning Rod <br><img src="../../img/desperate-measures.svg" width="64px" height="64px"></img> |
| Heat Reflector <br><img src="../../img/heroic-acts.svg" width="64px" height="64px"></img> | `-15` | Until the end of Combat, whenever a foe inflicts Arcane Overheat or Arcane Slag on a chosen single PC, reflect half (RU) of it to the foe. | Until the end of Combat, whenever a foe inflicts Arcane Overheat or Arcane Slag on a chosen single PC, they suffer `+1` of each, but then double the amount of Arcane Slag and Overheat is also dealt to the foe. | `+20` | Arcane Reprisal <br><img src="../../img/desperate-measures.svg" width="64px" height="64px"></img> |
| Perfect Spell <br><img src="../../img/heroic-acts.svg" width="64px" height="64px"></img> | `-25` | A single chosen PC mage's next Spell automatically succeeds and cannot [Backfire](#spell-backfire)! However, they do still suffer Arcane Slag and Overheat from it. | For `1` Round, a single chosen enemy mage's Spells may additionally [Backfire](#spell-backfire), regardless of their Test result. Roll `1D6`: on a Miss, a Backfire occurs, on a Hit, no Backfire occurs. Not these Backfires are additional effects, that trigger *after* the Spell's normal resolution. Yes, this may in fact also result in a double Backfire! | `+30` | Negative Feedback <br><img src="../../img/desperate-measures.svg" width="64px" height="64px"></img> |
| Backfire Dodger <br><img src="../../img/heroic-acts.svg" width="64px" height="64px"></img> | `-15` | The current or next Spell-Backfire of a chosen PC mage is re-directed onto a willing ally, who suffers it at `-1` SI (reduced to no less than `1` SI). | The current or next Spell-Backfire of a chosen PC mage is duplicated onto a chosen enemy, who also suffers it, and at `+1` SI. | `+20` | You Should See The Other Guy <br><img src="../../img/desperate-measures.svg" width="64px" height="64px"></img> |

# The Veil
Whenever a psion uses their ability, they mentally reach out to the forces *beyond* The Veil, which causes **Veil Degradation**. When Veil Degradation becomes too great, strange and horrible things ensue. 

The limits for Veil Degradation are `0` and `100`. Unlike mages, who manage only their own resource, Veil Degradation is shared by **all** Characters in the current scene and follows the psion wherever they go. It automatically lowers by `10` every `6` hour interval or resets to `0` when The Veil *shatters*. 

Whenever the psion uses their ability and Veil Degradation is above `0`, roll a percentile die (`2D10`, of which one is the "tenth" die and one is the "singles" die). If the result is above the current Veil Degradation, nothing happens. You were fortunate! But if it was below or equal to the current Veil Degradation, The Veil is lifted, momentarily. When that happens, one of the following effects ensue, based on the current Veil Degradation. Afterwards, Veil Degradation is lowered by `20`. However, if Veil Degradation reaches `100+`, the Veil *shatters*, causing it to reset to `0` and always results in a **Veil Entity** following the psion into their world.

As The Veil degrades, the very air begins to hum and buzz. There are voices on the wind, spoken in unfamiliar tongue and too subtle to hear. The light twists and occasionally shows visions from The Beyond, but too alien to comprehend. 

| Veil Degradation | Effect                              | 
| ---------------- | ----------------------------------- |
| 0-10             | Foreign doubts gnaw at the mind. All psions in the scene suffer `-1D` for their next Test. |
| 11-20            | All psions in the scene are overcome with terror and rendered [Terrified](./strive-core.md#terrified). |
| 21-30            | Every creature in the scene is force moved in a random direction by `5` Squares. |
| 31-40            | All psions in the scene suffer `+3` [Arcane Slag](#arcane-overheat--slag)! |
| 41-50            | Every creature in the scene suffers a random [Illness](strive-core.md#illness). |
| 51-60            | Every creature in the scene suffers `+1` [Bleeding](strive-core.md#bleeding). |
| 61-70            | All Characters in the scene suffer `+3` [Arcane Slag](#arcane-overheat--slag)! |
| 71-80            | Time reverses momentarily. The current Round's initiative order reverses. Or outside combat, the last few minutes play back in reverse. |
| 81-90            | The flesh is malleable. All creatures in the scene suffer a random mutation. Or they could resist the transformation, and instead suffer `20` [Pure](strive-core.md#damage-types) damage and `+2` [Bleeding](strive-core.md#bleeding)! |
| 91-100           | A *thing* from beyond The Veil is pulled through to your world. As a GM, see [Veil Entities](./strive-fantasy-game-masters-resource.md#veil-entities). |

# Appendix
The appendix contains important and less important lists, for reference only when needed. 

## Character Creation
Character creation is now supplemented by a step to determine your Character's [Arcane Overheat thresholds](#arcane-overheat--slag). 

### Determine Abilities
Supplements to abilities in Character creation. 

#### Choosing Attributes
There are two methods for determining your Character's Attributes: manual and semi-random. 

You'll have to decide on whether your Character will be a mage or not. Mages have the new, 6th Attribute to spend points on, so this decision can affect your Character's initial overall competence. 

Please keep in mind the values here are representative for an ordinary human about to enter an adventuring life. Other species may have modifiers on their Attributes, making them better or worse in some of them. But that depends on the world your GM is running. 

This section replaces its core rule counter-part. 

##### Manual Attribute Assignment
1. Decide if you want to play a mage.
   1. As a mage, you **must** put at least `1` point into Arcana.
   2. As a non-mage, you **may not** put *any* points into Arcana.
2. The rest of the procedure follows the same steps as outlined in the [Core rules](./strive-core.md#manual-attribute-assignment), starting from step `1` therein. 

##### Semi-Random Attribute Assignment
1. Decide if you want to play a mage.
   1. As a mage, roll `6D4` and **include** Arcana in the following steps. 
   2. As a non-mage, roll `5D4` and **exclude** Arcana in the following steps. 
2. The rest of the procedure follows the same steps as outlined in the [Core rules](./strive-core.md#semi-random-attribute-assignment), starting from step `2` therein. 

#### Choosing Skills
If playing a **mage**, keep in mind you need to have at least Level `1` in a [Magic School Skill](#magic-school--school---attribute-) to be able to cast magic. You are also advised to have your strongest magic be at least Level `3` or `4`, to be able to reliably use it. 

## Assets Appendix
The following list does not and cannot aim to be a complete listing of all possible Assets in game. Adding new Assets as necessary will have to be done by the GM. 

### General Assets
The following is a non-exhaustive list of general Assets. Just because an Asset you're looking for isn't listed here, doesn't mean it cannot exist! You are encouraged to think creatively and [Invent](./strive-core.md#invention-projects) your own!

See also the [Core rule's Asset appendix](./strive-core.md#assets-appendix). 

| Name                     | Bulk | Max. Stack Size | PI  | TI         | Crafting Ob | Description                                                              |
| ------------------------ | ---- | --------------- | --- | ---------- | ----------- | ------------------------------------------------------------------------ |
| Acid Arrows              | 1    | 20              | 15  | 30 Minutes |             | Ammunition for a bow that deals `Q * 2` additional points of Acid damge. A small acid-filled vial tips these arrows, ready to burst upon impact. |
| Acid Bomb                | 1    | 3               | 15  | 10 Minutes |             | A small fragile shell with two compartments, filled with two liquids which, when they combine, act as a powerful acid. When shattered, deals `QD6 Acid` damage to whatever it hits. |
| Arrows                   | 1    | 20              | 20  | 10 Minutes |             | Ammunition for a bow. |
| Blackpowder Bomb         | 1    | 2               | 20  | 1 Hour     | +1          | A small iron-shelled bomb, filled with blackpowder. A short fuse sticks out and must be lit to set it off. Once lit, the bomb will detonate after `3` Turns or `15` seconds. Deals `QD4 Bludgeoning + QD4 Burning` damage to anyone in a `2` Square AoE radius. |
| Bolts                    | 1    | 20              | 10  | 10 Minutes |             | Ammunition for a crossbow. |
| Calming Tea              | 1    | 3               | 5   | 10 Minutes |             | This herbal tea has the ability to calm nerves. Removes [Berserk](./strive-core.md#berserk), [Jealous](./strive-core.md#jealous) and [Terrified](./strive-core.md#terrified). Best enjoyed steaming hot, but not necessarily. |
| Clothing                 | 1    | 2               | 20  | 1 Hour     |             | A full set of clothes, head to toe. |
| Death Fog                | 1    | 1               | 50  | 6 Hours    | +1          | An extremely rare and deadly gas. Once exposed to air, covers an area of `Q * 2` Squares in impenetrable, eerily glowing, blue fog. Deals `QD10 + 10` Pure damage to all **organic** things it touches, per tick. Metal and mineral are unaffected, while plant and flesh are struck from existence. |
| Dragon's Breath Potion   | 1    | 3               | 20  | 1 Hour     | +1          | Upon drinking this potion, the orange liquid combines with the stomach acid and bursts out of the drinker's throat, igniting and thus causing them to spew fire! Causes `5 - Q Burning` damage to the user and `Q * 3 Burning` damage in a `5` Squares cone in front of the user. |
| Explosive Arrows         | 1    | 10              | 20  | 1 Hour     |             | Ammunition for a bow that deal `1D4 Bludgeoning + (1D4 + Q) Burning` damage. |
| Fire Pot (Potion)        | 1    | 3               | 20  | 1 Hour     |             | An ancient recipe, this concoction bursts into flame when exposed to air for several seconds. It causes severe burns for `QD6 Burning` damage in a `2` Square AoE adius. Consumed on use. |
| Illusionist's Powder     | 1    | 2               | 15  | 1 Hour     |             | A small amount of weakly iridescently shimmering powder. When scattered, the dust remains suspended in mid-air and settles in an image of the making alchemist's choosing, which at a distance can seem perfectly real. It takes a successful Test at Ob `Q + 1` to see through the ruse. This image lasts `QD10` minutes. |
| Invigorating Potion      | 1    | 3               | 10  | 1 Hour     |             | The drinker of this potion feels refreshed and invigorated! Increases [Stamina](./strive-core.md#stamina--strain) by `Q` and clears the [Exhausted](./strive-core.md#exhausted) condition. Beware this potion can only be safely imbibed twice in a `24` hour cycle. If drunk more, roll a `D6`. If it is a Hit, you're in luck! But if not, you instead suffer `+1` [Strain](./strive-core.md#stamina--strain). |
| Jewelry                  | 1    | 2               | 20  | 1 Hour     |             | Precious apparel. |
| Keg Of Alcohol           | 2    | 1               | 20  | 1 Day      |             | A keg of alcohol. Highly flammable. If set fire to, will explode in a small torrent of flame, dealing `Q * 3` Burning damage to all in a `2` Square AoE radius. |
| Laudanum Potion          | 1    | 2               | 20  | 1 Hour     |             | This wonderous substance can quell pain and calm nerves within seconds. Also effective against diarrhea. Upon imbibing, sets one Active [Injury](./strive-core.md#injury) to Treated. After `24` hours, the [Injury](./strive-core.md#injury) is set back to Active, even if it was also properly Treated in the meantime. Also, must succeed a [Self-Control](./strive-core.md#self-control-toughwit) Test at Ob `3`, or else become [Addicted](./strive-core.md#drug-addicted) to the stuff. |
| Love Potion              | 1    | 2               | 25  | 1 Hour     | +1          | Anyone drinking this potion will become virtually irresistible to anyone close enough to smell their air. Victims have to succeed a [Self-Control](./strive-core.md#self-control-toughwit) Test at Ob `Q` or else feel **very strongly compelled** to fulfill the user's every wish and desire (provided this wouldn't obviously cause harm to the victim). |
| Magic Recorder           | 1    | 3               | 30  | 6 Hours    |             | A small spherical device, made from various metals with intricate patterns on its surface. This device can capture [Magic Echoes](#magic-echoes) and record magic as it is being cast. Also captures fragments of thoughts from its bearer while it is active. |
| Night-Eye Potion         | 1    | 3               | 15  | 1 Hour     |             | Grants the ability to see reasonably well under low-light conditions, up to `Q * 3` Squares around them, for an hour. Beware that under the influence of this potion, exposure to bright light is extremely difficult to endure and will cause `-1` [Stamina](./strive-core.md#stamina--strain) for every **minute** of exposure. |
| Paralyzing Poison        | 1    | 2               | 50  | 1 Hour     | +2          | Causes a victim's muscles to seize up. They suffer `-1` AP each Turn and are forced to move sluggishly, at only half their usual movement speed. If this poison is suffered twice, the victim seizes up completely and is unable to move, at all. This poison can be resisted once upon suffering it, with [Toughness](./strive-core.md#toughness-tough), at Ob `Q`. If unsuccessful, the effect will last `Q` hours. |
| Poison Arrows            | 1    | 20              | 15  | 30 Minutes |             | Ammunition for a bow that deals `Q * 2` additional points of Poison damge. A small poison-filled vial tips these arrows, ready to burst upon impact. |
| Poison Resistance Potion | 1    | 2               | 15  | 1 Hour     |             | Once imbibed, reduces all incurred poison damage by `Q * 2`, for up to `Q` hours. |
| Sleeping Poison          | 1    | 3               | 40  | 1 Hour     | +1          | Causes a victim to feel incredibly sleepy. Unless they succeed a [Self-Control](./strive-core.md#self-control-toughwit) Test at Ob `Q`, they will fall asleep the first chance they get. They cannot be woken from this state for at least `6` hours, except through the use of harmful force. |
| Smoke Bomb               | 1    | 3               | 10  | 10 Minutes |             | A small fragile shell, filled with a very fine powder which when broken causes an area in a `Q` Square AoE radius to be covered in smoke. It is impossible to see through and ranged attacks within or through the smoke-covered area suffer `+2` Ob. Victims caught in the smoke may be forced to cough. The smoke lasts `6` Turns or `30` seconds. |
| Throwing Blade           | 1    | 6               | 10  | 1 Hour     |             | A small weighted blade, like a knife or star, well suited to being thrown. Can be used in melee and acts like a [Dagger](#light-blade), but with a penalty of `-2D` to attack and Defense. `+1D` when [Thrown](./strive-core.md#throwing) for a ranged attack. <br> `≤ 1` Hit: `4 + Str` Piercing <br> `= 2` Hits: `6 + Str` Piercing <br> `≥ 3` Hits: `8 + Str` Piercing |
| Tools                    | 1    | 2               | 10  | 1 Hour     |             | Various metal-made, proper tools. |
| Trap: Acid               | 1    | 3               | 15  | 1 Hour     |             | A small metal frame with a central pressure pad which, when stepped on, sprays acid upwards at the victim. Causes `(Q * 2) + 6` Acid damage. |
| Trap: Bear               | 1    | 3               | 15  | 1 Hour     |             | A metal-jawed trap, capable of breaking bone and flesh. Deals `Q * 2` Bludgeoning and `Q * 2` Piercing damage. Causes [Rooted](./strive-core.md#rooted) in the victim, which costs `3` AP to clear. |
| Trap: Cage/Net           | 1    | 1               | 15  | 1 Hour     |             | When tripped, a cage springs up around, or a net pulls up over the victim. They are trapped within until they can manage to free themselves. `Q` equals the Ob for Tests to cut or break the cage or net. |
| Trap: Powder             | 1    | 3               | 15  | 1 Hour     |             | When tripped, coughs up a cloud of powder in a up to `Q` Square radius, which will impede all vision through it at a Ob `+2` penalty. The powder may also be flammable, poisonous or Illusionist's Powder. |
| Trap: Rune/Scroll        | 1    | 3               | 15  | 1 Hour     |             | When tripped, a complex mechanism pours vial of mage blood onto the Rune or Scroll, in precise intervals to agitate the magic within. |
| Trap: Shooter            | 1    | 3               | 15  | 5 Minutes  |             | A crossbow or firearm is wired to shoot in a set direction by a careless trespasser. The bolt or bullet will travel up to `20` Squares far and deal `Q * 3` Piercing damage. May also shoot poison darts or other types of ammo. |
| Trap: Windfist           | 1    | 2               | 15  | 1 Hour     |             | A pressure plate or wire opens the seal on a pressurized container. The escaping gas hits the victim with an enormous force, throwing them `Q * 2` Squares far. |

### Armor

#### Armor Traits
Armor can have the following **Armor Traits**:

* **Ambersteel**: Bonus protection against magic. `+Q` Ob for the attacker and reduces damage by `Q * 2` from a magic source. 

#### Light Armor
A set of light armor that doesn't impede the wearer much. Example: cloth armor like a gambeson. Might also be leather armor, if the leather comes from a creature whose skin is particularly tough and well suited to being used as armor. 

* Bulk: `2`
* PI: `30`, TI: `6 Hours`

| Protections          | Unthreatened | Flanked | Surrounded | Overwhelmed | 
| -------------------- | ------------ | ------- | ---------- | ----------- | 
| **Slashing**         | 5            | 3       | 2          | 0           | 
| **Piercing**         | 4            | 2       | 1          | 0           | 
| **Bludgeoning**      | 4            | 2       | 1          | 0           | 
| **Acid**             | 6            | 3       | 2          | 0           | 

#### Medium Armor
A set of medium armor with a good balance of protection and weight. Example: full chain mail armor, with or without a helmet. 

* `+1` [Strain](./strive-core.md#stamina--strain) while worn. 
* `+1` [Stability](./strive-core.md#stability-stabil) while worn.
* `-1` to [Stealth](./strive-core.md#stealth-agiawar) while worn. 
* `-1D` to any Defense Tests while worn. 
* Bulk: `3`
* PI: `40`, TI: `6 Hours`

| Protections          | Unthreatened | Flanked | Surrounded | Overwhelmed | 
| -------------------- | ------------ | ------- | ---------- | ----------- | 
| **Slashing**         | 6            | 3       | 2          | 0           | 
| **Piercing**         | 6            | 3       | 2          | 0           | 
| **Bludgeoning**      | 4            | 2       | 1          | 0           | 
| **Acid**             | 4            | 2       | 1          | 0           | 
| **Electrical**       | 6            | 3       | 2          | 0           |

#### Heavy Armor
A set of heavy armor with excellent protection, at the cost of encumbering the wearer greatly. Example: full plate armor. 

* `+2` [Strain](./strive-core.md#stamina--strain) while worn.
* `+2` [Stability](./strive-core.md#stability-stabil) while worn.
* `-3` to [Stealth](./strive-core.md#stealth-agiawar) while worn. 
* `-2D` to any Defense Tests while worn. 
* Bulk: `4`
* PI: `50`, TI: `6 Hours`

| Protections          | Unthreatened | Flanked | Surrounded | Overwhelmed | 
| -------------------- | ------------ | ------- | ---------- | ----------- | 
| **Slashing**         | 8            | 4       | 2          | 0           | 
| **Piercing**         | 8            | 4       | 2          | 0           | 
| **Bludgeoning**      | 6            | 3       | 2          | 0           | 
| **Acid**             | 6            | 3       | 2          | 0           | 
| **Electrical**       | 6            | 3       | 2          | 0           | 

### Shield Types
Shields are items that provide passive bonuses to Defense against melee and ranged attacks and require one free hand to use. This implies they cannot be used at the same time as a two-handed weapon (unless of course if you have more than two arms). 

Shields can only be used in Defense Tests via the [Shield](./strive-core.md#shield-strtough) Skill.

#### Shield Traits
Shields can have the following **Shield Traits**:

* **Ambersteel**: Bonus protection against magic. `+Q` Ob for the attacker and reduces damage by `Q * 2` from a magic source. 

#### Light Shield
A small round or oblong shield commonly held as far from the body as possible, to deflect small or stabbing weapons with ease. Helps only little against heavy blows and don't expect to deflect arrows with this, either. 

* Bulk: `1`
* PI: `20`, TI: `6 Hours`

| Unthreatened           | Flanked           | Surrounded           | Overwhelmed           |
| ---------------------- | ----------------- | -------------------- | --------------------- |
| `+1` [Compensation Point](./strive-core.md#compensation-points) for melee Defense. | `+1D` for melee Defense. | / | / |
| `+2` [Compensation Points](./strive-core.md#compensation-points) for melee Defense against Piercing attacks. | `+2D` for melee Defense against Piercing attacks. | `+1D` for melee Defense against Piercing attacks. | / |
| `-1D` for ranged Defense. | `-2D` for ranged Defense. | `-2D` for ranged Defense. | `-2D` for ranged Defense. |

#### Medium Shield
A medium-sized, round or kite-shaped shield made from tough wood and leather or even metal, which offers good protection against most attacks, while not encumbering the wielder too much. 

* `+1` [Strain](./strive-core.md#stamina--strain) while wielded. 
* `+1` [Stability](./strive-core.md#stability-stabil) while wielded.
* Bulk: `2`
* PI: `30`, TI: `6 Hours`

| Unthreatened           | Flanked           | Surrounded           | Overwhelmed           |
| ---------------------- | ----------------- | -------------------- | --------------------- |
| `+1` [Compensation Point](./strive-core.md#compensation-points) for any Defense. | `+1D` for any Defense. | / | `-1D` for any Defense. |

#### Heavy Shield
A large, kite-shaped or rectangular shield, which can protect every part of the fighter, from the shoulder down to the feet. Its weight is very tiring. 

* `+2` [Strain](./strive-core.md#stamina--strain) while wielded.
* `+2` [Stability](./strive-core.md#stability-stabil) while wielded.
* Bulk: `4`
* PI: `40`, TI: `6 Hours`

| Unthreatened           | Flanked           | Surrounded           | Overwhelmed           |
| ---------------------- | ----------------- | -------------------- | --------------------- |
| `+2` [Compensation Points](./strive-core.md#compensation-points) for any Defense. | `+1` [Compensation Point](./strive-core.md#compensation-points) for any Defense. | `+1D` for any Defense. | / |

### Weapon Types
Following are fantasy-themed weapon types. 

#### Weapon Traits
Weapons can have the following **Weapon Traits** (see also the [Core Weapon Traits](./strive-core.md#weapon-traits)):

* **Ambersteel**: Bonus `+(Q * 2)` Pure damage against mages and magical creatures. 

#### Axe
One and two-handed axes. See also its corresponding [Skill](#weapon-axe-strstr).

* [Melee](./strive-core.md#melee)
* Bulk: `2`, PI: `15`, TI: `1 Hour`

#### Chained Blade 
An exotic weighted, down-angled blade, perfect for throwing and connected to a very light chain or rope, for easy retrieval. Such a weapon requires masterful precision and rewards its user with great versatility. See also its corresponding [Skill](#weapon-chained-blade-agiagi).

Requires knowing [Acrobatics](#acrobatics-agistr) and [Throwing](./strive-core.md#throwing), each at Level `3+`. 

* [Melee](./strive-core.md#melee), [Ranged (max. 8)](./strive-core.md#ranged), [Prefer Range](./strive-core.md#prefer-range)
* Bulk: `3`, PI: `25`, TI: `1 Hour`

#### Crusher
Small bludgeoning weapons. Examples: any improvised weapon, any club, any mace. See also its corresponding [Skill](#weapon-crusher-strtough).

* [Melee](./strive-core.md#melee)
* Bulk: `3`, PI: `15`, TI: `1 Hour`

#### Light Blade
Any short and/or light blade, such as daggers and one-handed swords. See also its corresponding [Skill](#weapon-light-blade-agistr).

* [Melee](./strive-core.md#melee)
* Bulk: `1`, PI: `15`, TI: `1 Hour`

#### Long Blade
Any long and heavier blade, such as longswords and great-swords. See also its corresponding [Skill](#weapon-long-blade-agistr).

* [Melee](./strive-core.md#melee), [Long Reach](./strive-core.md#weapon-traits)
* Bulk: `3`, PI: `20`, TI: `1 Hour`

#### Polearm
Polearms and spears. Examples: boar-spear, halberd, bardiche, poleaxe. See also its corresponding [Skill](#weapon-polearm-strtough).

* [Melee](./strive-core.md#melee), [Long Reach](./strive-core.md#weapon-traits), [Prefer Range](./strive-core.md#weapon-traits)
* Bulk: `4`, PI: `20`, TI: `1 Hour`

#### Short-Bow
A short distance ranged weapon, shooting arrows. See also its corresponding [Skill](#weapon-short-bow-agiawar).

* [Ranged (10 DI)](./strive-core.md#ranged), [Range Only](./strive-core.md#weapon-traits)
* Bulk: `1`, PI: `15`, TI: `1 Hour`

#### Longbow
A long distance ranged weapon, shooting arrows. See also its corresponding [Skill](#weapon-longbow-awarstr).

* [Ranged (20 DI)](./strive-core.md#ranged), [Range Only](./strive-core.md#weapon-traits)
* Bulk: `2`, PI: `20`, TI: `1 Hour`

#### Crossbow
A deadly medium distance ranged weapon, shooting bolts. Beware its slow reload. See also its corresponding [Skill](#weapon-crossbow-awarawar).

* [Ranged (15 DI)](./strive-core.md#ranged), [Prefer Range](./strive-core.md#weapon-traits), [Slow Reload](./strive-core.md#weapon-traits)
* Bulk: `2`, PI: `25`, TI: `1 Hour`

#### Firearm
A very deadly short to medium distance ranged weapon, shooting small metal balls that are partially able to penetrate armor. Beware its slow reload. See also its corresponding [Skill](#weapon-firearm-awartough).

* [Ranged (10 DI)](./strive-core.md#ranged), [Prefer Range](./strive-core.md#weapon-traits), [Very Slow Reload](./strive-core.md#weapon-traits)
* Bulk: `3`, PI: `30`, TI: `1 Hour`

## Lists of Skills
The following list does not and cannot aim to be a complete listing of all possible Skills in game. Adding new Skills as necessary will have to be done by the GM. 

### Physical Skills
These Skills have a dominant physical aspect and are directly tied to a Character's *physical Attributes*. 

#### Rune-Using (Agi/Wit)
Skill at using [Magic Runes](#runes). 

| Level | Name                 | AP | Ob     | Descripti          |
| ----- | -------------------- | -- | ------ | ------------------ |
| 4     | Hot Potato           | 1  | 3      | If using a Rune would fail and result in a [Spell-Backfire](#spell-backfire), drop the Rune, causing it to fire at...<br> `≤ 1` Hit: `-1` SI. <br> `= 2` Hits: `-2` SI. <br> `≥ 3` Hits: `-3` SI. |

#### Sailing (Awar/Wit)
Steering and maintaining a naval vessel. 

#### Weapon \<Axe\> (Str/Str)
Skill for [Axe](#axe) type weapons, both one and two-handed. A straight-forward solution to your problems, that combines cutting and impact force and can viciously bleed your enemies. 

Traits: [Melee](./strive-core.md#melee), [FS](./strive-core.md#free-strike-fs): `2` Slashing + `2` Bludgeoning

| Level | Name                 | AP | Ob          | Description <br> Damage                   |
| ----- | -------------------- | -- | ----------- | ----------------------------------------- |
| 0     | Hack                 | 2  | Opposed     | Strike a ST. <br> `≤ 1` Hit: `4` Slashing + `2` Bludgeoning <br> `= 2` Hits: `5` Slashing + `3` Bludgeoning <br> `≥ 3` Hits:  `6` Slashing + `2 + Str` Bludgeoning |
| 0     | Savage Slash         | 2  | Opposed + 1 | Strike a ST. <br> `≤ 1` Hit: `3` Slashing; `+1` [Bleeding](./strive-core.md#bleeding) to the target (if it can bleed) <br> `= 2` Hits: `3` Slashing; `+2` [Bleeding](./strive-core.md#bleeding) to the target (if it can bleed) <br> `≥ 3` Hits:  `4` Slashing; `+3` [Bleeding](./strive-core.md#bleeding) to the target (if it can bleed) |
| 2     | Cleave               | 3  | 2           | Attack up to `3` targets at once, in a `2` Square AoE cone in front of you. <br> `≤ 1` Hit: `4` Slashing <br> `= 2` Hits: `5` Slashing <br> `≥ 3` Hits:  `6` Slashing |

#### Weapon \<Light Blade\> (Agi/Str)
Skill for any [Light Blade](#light-blade) type weapons, such as daggers and one-handed swords. Versatile, but best used against inconvenienced foes, with an emphasis on Piercing damage. 

Traits: [Melee](./strive-core.md#melee), [FS](./strive-core.md#free-strike-fs): `3` Piercing

| Level | Name                 | AP | Ob          | Description <br> Damage                   |
| ----- | -------------------- | -- | ----------- | ----------------------------------------- |
| 0     | Slash                | 2  | Opposed     | Strike a ST. <br> `≤ 1` Hit: `4` Slashing <br> `= 2` Hits: `6` Slashing <br> `≥ 3` Hits: `7` Slashing |
| 0     | Stab                 | 2  | Opposed     | Strike a ST. <br> `≤ 1` Hit: `5` Piercing <br> `= 2` Hits: `6` Piercing <br> `≥ 3` Hits: `8` Piercing |
| 1     | Artery Cut           | 2  | Opposed + 1 | Strike a ST. <br> `≤ 1` Hit: `2` Slashing; `+1` [Bleeding](./strive-core.md#bleeding) to the target (if it can bleed). <br> `= 2` Hits: `3` Slashing; `+2` [Bleeding](./strive-core.md#bleeding) to the target (if it can bleed). <br> `≥ 3` Hits: `5` Slashing; `+2` [Bleeding](./strive-core.md#bleeding) to the target (if it can bleed). |
| 1     | Grappling Feint      | 2  | Opposed - 1 | Attack a ST with a feint, immediately close the distance and [Grapple](./strive-core.md#grappled) them. |
| 2     | Target Weak-Spot     | 2  | Opposed + 2 | Strike a ST. `-2 Ob` against [Proned](./strive-core.md#prone) and/or [Grappled](./strive-core.md#grappled) targets. <br> `≤ 1` Hit: `5` Pure <br> `= 2` Hits: `6` Pure <br> `≥ 3` Hits: `8` Pure |

#### Weapon \<Long Blade\> (Agi/Str)
Skill for any [Long Blade](#long-blade) type weapons, such as longswords and great-swords. Versatile and powerful with an emphasis on Slashing damage. 

Traits: [Melee](./strive-core.md#melee), [Long Reach](./strive-core.md#weapon-traits), [FS](./strive-core.md#free-strike-fs): `3` Slashing

| Level | Name                 | AP | Ob          | Description <br> Damage                   |
| ----- | -------------------- | -- | ----------- | ----------------------------------------- |
| 0     | Slash                | 2  | Opposed     | `≤ 1` Hit: `5` Slashing <br> `= 2` Hits: `7` Slashing <br> `≥ 3` Hits: `10` Slashing |
| 0     | Stab                 | 2  | Opposed     | `≤ 1` Hit: `5` Piercing <br> `= 2` Hits: `6` Piercing <br> `≥ 3` Hits: `7` Piercing |
| 1     | Cleave               | 3  | 2           | Attack up to `2` targets at once, in a `2` Square AoE cone in front of you. <br> `≤ 1` Hit: `3` Slashing <br> `= 2` Hits: `4` Slashing <br> `≥ 3` Hits:  `6` Slashing |
| 2     | Mord-Strike          | 2  | Opposed + 1 | Flip your weapon around and strike a ST on the head with the weight of the pommel. <br> `≤ 1` Hit: `3` Bludgeoning <br> `= 2` Hits: `4` Bludgeoning <br> `≥ 3` Hits: `3 + Str` Bludgeoning |
| 3     | Whirlwind            | 3  | 2           | With far reaching swings of your weapon, let yourself be turned around by the flying blade, spinning like a carroussel and moving in a direction of your choosing, up to `4` Squares far. All other Characters are forced back by your onslaught. This does not provoke Opportunity Attacks. <br> `≤ 1` Hit: `1` Square <br> `= 2` Hits: `2` Squares <br> `≥ 3` Hits: `3` Squares |

#### Weapon \<Chained Blade\> (Agi/Agi)
Skill for [Chained Blade](#chained-blade) type weapons, an exotic and fantastical weapon type that uses an angled blade at the end of a light chain. A very versatile weapon that can move yourself and foes around and support an ally's attacks. 

Traits: [Melee](./strive-core.md#melee), [Ranged (max. `8`)](./strive-core.md#ranged), [Prefer Range](./strive-core.md#weapon-traits), [FS](./strive-core.md#free-strike-fs): `4` Slashing

| Level | Name                 | AP | Ob          | Description <br> Damage                   |
| ----- | -------------------- | -- | ----------- | ----------------------------------------- |
| 0     | Curved Toss          | 2  | Opposed     | Throw the weapon just past a ST and then with a flick, make it jump at their back. <br> `≤ 1` Hit: `4` Slashing <br> `= 2` Hits: `5` Slashing <br> `≥ 3` Hits: `6` Slashing |
| 0     | Come Closer          | 2  | Opposed     | Throw the weapon just past a ST and then yank it back, catching them with it and pulling them closer to you. If the target is much larger and/or heavier than you, then you may pull *yourself* closer to them, for the same distance. <br> `≤ 1` Hit: `2` Squares; `2` Slashing <br> `= 2` Hits: `3` Squares; `3` Slashing <br> `≥ 3` Hits: `4` Squares; `4` Slashing |
| 2     | Leg Sweep            | 2  | Opposed     | Swing the weapon at length and low, to sweep for an opponent's legs. Upon impact, yank the chain to sweep them off their feet, rendering them [Prone](./strive-core.md#prone). |
| 4     | Think Twice          | 1  |             | **Reaction**: Upon one of your allies attacking an enemy, you also throw your weapon straight at that enemy. Your ally's attack is `-1` Ob easier as the enemy is confused by the two simultaneous attacks! Your attack does **not** cost the enemy any additional AP to defend against and is successful only if your ally's attack is successful. Only possible once per Round. |

#### Weapon \<Crusher\> (Str/Tough)
Skill for [Crusher](#crusher) type weapons, with a dedicated *impact zone*, such as clubs and maces. Benefits from your Strength and is good for tiring out foes. 

Traits: [Melee](./strive-core.md#melee), [FS](./strive-core.md#free-strike-fs): `4` Bludgeoning

| Level | Name                 | AP | Ob          | Description <br> Damage                   |
| ----- | -------------------- | -- | ----------- | ----------------------------------------- |
| 0     | Smash                | 2  | Opposed     | Strike a ST. <br> `≤ 1` Hit: `4` Bludgeoning <br> `= 2` Hits: `5` Bludgeoning <br> `≥ 3` Hits: `5 + Str` Bludgeoning |
| 0     | Knockout Blow        | 2  | Oppose      | Strike a ST. <br> `≤ 1` Hit: `3` Bludgeoning; `-2` [Stamina](./strive-core.md#stamina--strain) to the target. <br> `= 2` Hits: `4` Bludgeoning; `-2` [Stamina](./strive-core.md#stamina--strain) to the target. <br> `≥ 3` Hits: `5` Bludgeoning; `-3` [Stamina](./strive-core.md#stamina--strain) to the target. |
| 0     | Mighty Smash         | 2  | Opposed + 1 | Strike a ST. Costs `2` AP to defend against! <br> `≤ 1` Hit: `5 + Str` Bludgeoning <br> `= 2` Hits: `6 + Str` Bludgeoning <br> `≥ 3` Hits: `7 + Str` Bludgeoning |

#### Weapon \<Polearm\> (Str/Tough)
Skill for [Polearm](#polearm) type weapons, like halberds, voulges, bardiches and pollaxes. An ideal support weapon, that can be used from the back-row. 

Traits: [Melee](./strive-core.md#melee), [Long Reach](./strive-core.md#weapon-traits), [Prefer Range](./strive-core.md#weapon-traits), [FS](./strive-core.md#free-strike-fs): `3` Piercing

| Level | Name                 | AP | Ob          | Description <br> Damage                   |
| ----- | -------------------- | -- | ----------- | ----------------------------------------- |
| 0     | Slash                | 2  | Opposed     | Strike a ST. <br> `≤ 1` Hit: `4` Slashing <br> `= 2` Hits: `5` Slashing <br> `≥ 3` Hits: `6` Slashing |
| 0     | Stab                 | 2  | Opposed     | Strike a ST. <br> `≤ 1` Hit: `6` Piercing <br> `= 2` Hits: `7` Piercing <br> `≥ 3` Hits: `8` Piercing |
| 2     | Blade Barrier        | 3  |             | Until the start of your next Turn, whenever any Character moves **into** a spot within reach, can **freely** attack that Character with a **Stab** at Ob `+1` and if successful, force them back `1` Square. |
| 2     | Breakthrough         | 3  | Opposed     | Charge at a ST, up to `4` Squares away. <br> `≤ 1` Hit: `4` Piercing; Knock-back `1` Square <br> `= 2` Hits: `4` Piercing; Knock-back `2` Squares <br> `≥ 3` Hits:  `5` Piercing; Knock-back `3` Squares |
| 2     | Cleave               | 3  | 2           | Attack up to `4` targets at once, in a `3` Square AoE cone in front of you. <br> `≤ 1` Hit: `3` Slashing <br> `= 2` Hits: `4` Slashing <br> `≥ 3` Hits:  `5` Slashing |

#### Weapon \<Short-Bow\> (Agi/Awar)
Skill for [Short-Bow](#short-bow) type weapons. Versatile, but light on damage. 

Traits: [Ranged (10 DI)](./strive-core.md#ranged), [Range Only](./strive-core.md#weapon-traits), [FS](./strive-core.md#free-strike-fs): `3` Piercing

| Level | Name                 | AP | Ob          | Description <br> Damage                   |
| ----- | -------------------- | -- | ----------- | ----------------------------------------- |
| 0     | Loose                | 2  | Opposed     | Shoot a ST. <br> `≤ 1` Hit: `4` Piercing <br> `= 2` Hits: `5` Piercing <br> `≥ 3` Hits: `6 + Awar` Piercing  |
| 1     | Pin                  | 2  | Opposed     | Shoot a ST in their foot, [Rooting](./strive-core.md#rooted) them in-place until the end of their next Turn. <br> `≤ 1` Hit: `2` Piercing <br> `= 2` Hits: `3` Piercing <br> `≥ 3` Hits: `4` Piercing |
| 2     | Double Shot          | 2  | Opposed + 1 | Shoot up to `2` MST at once. <br> `≤ 1` Hit: `3` Piercing <br> `= 2` Hits: `4` Piercing <br> `≥ 3` Hits: `5` Piercing |

#### Weapon \<Longbow\> (Awar/Str)
Skill for [Longbow](#longbow) type weapons. Great damage, but no utility. 

Traits: [Ranged (20 DI)](./strive-core.md#ranged), [Range Only](./strive-core.md#weapon-traits), [FS](./strive-core.md#free-strike-fs): `4` Piercing

| Level | Name                 | AP | Ob          | Description <br> Damage                   |
| ----- | -------------------- | -- | ----------- | ----------------------------------------- |
| 0     | Loose                | 2  | Opposed     | Shoot a ST. <br> `≤ 1` Hit: `5` Piercing <br> `= 2` Hits: `6` Piercing <br> `≥ 3` Hits: `8` Piercing |
| 2     | Heavy Shot           | 2  | Opposed + 1 | Shoot a ST. `+1` [Strain](./strive-core.md#strain) to self. <br> `≤ 1` Hit: `5 + Str` Piercing <br> `= 2` Hits: `6 + Str` Piercing <br> `≥ 3` Hits: `8 + Str` Piercing   |

#### Weapon \<Crossbow\> (Awar/Awar)
Skill for [Crossbow](#crossbow) type weapons. Deadly, but slow to reload and without any utility. 

Traits: [Ranged (15 DI)](./strive-core.md#ranged), [Prefer Range](./strive-core.md#weapon-traits), [Slow Reload](./strive-core.md#weapon-traits), [FS](./strive-core.md#free-strike-fs): `5` Piercing

| Level | Name                 | AP | Ob          | Description <br> Damage                   |
| ----- | -------------------- | -- | ----------- | ----------------------------------------- |
| 0     | Loose                | 2  | Opposed     | Shoot a ST. <br> `≤ 1` Hit: `6` Piercing <br> `= 2` Hits: `8` Piercing <br> `≥ 3` Hits: `10` Piercing |

#### Weapon \<Firearm\> (Awar/Tough)
Skill for [Firearm](#firearm) type weapons. It takes great discipline to not flinch at the sparks and smoke upon ignition. Very deadly, but also very slow to reload and without any utility. 

Traits: [Ranged (10 DI)](./strive-core.md#ranged), [Prefer Range](./strive-core.md#weapon-traits), [Very Slow Reload](./strive-core.md#weapon-traits), [FS](./strive-core.md#free-strike-fs): `8` Piercing

| Level | Name                 | AP | Ob          | Description <br> Damage                   |
| ----- | -------------------- | -- | ----------- | ----------------------------------------- |
| 0     | Fire                 | 2  | Opposed + 1 | Shoot a ST. <br> `≤ 1` Hit: `8` Piercing + `2` Pure <br> `= 2` Hits: `10` Piercing + `3` Pure <br> `≥ 3` Hits: `12` Piercing + `4` Pure |

### Knowledge Skills
These Skills have a dominant mental aspect and are strongly related to a Character's *mental Attributes*. 

#### Heraldry (Awar/Wit)
The ability to tell noble houses apart and to know their heraldry. 

#### Magic School < School > (< Attribute >)
Knowledge and experience in a specific [Magic School](#list-of-magic-schools). 

See also [Testing Magic](#testing-magic). 

### Artisan Skills
All artisan Skills require a mix of physical and mental Attributes, for the purpose of creating a wide variety of things. Mechanically speaking, these are [Crafting](#crafting--research-projects) Skills.

#### Armor Smithing (Str/Wit)
The ability to make armor from conventional materials, such as metal and leather. 

[Crafting](./strive-core.md#crafting--research-projects):
* [Light Armor](#light-armor) (1x)
* [Medium Armor](#medium-armor) (1x)
* [Heavy Armor](#heavy-armor) (1x)

#### Ambersmithing (Str/Wit)
The ability to make things from [Amberite](#amberite) and [Ambersteel](#ambersteel). 

[Crafting](./strive-core.md#crafting--research-projects):
* Adding [Ambersteel](#ambersteel) to [Armor](#armor-traits) and [Weapons](#weapon-traits).

#### Alchemy (Arc/Wit)
The ability to brew alchemical potions, create powders, mixtures and other substances, as well as the ability to tell these things apart. 

[Crafting](./strive-core.md#crafting--research-projects):
* For every `Q` past `2`, choose one of the following:
  * Gain `+1` amount of your product. 
  * Gain a secondary product whose Progress Increment is smaller, with amount `1`. 
* [Acid Bomb](#general-assets) (3x)
* [Calming Tea](#general-assets) (3x)
* [Dragon's Breath Potion](#general-assets) (2x)
* [Fire Pot](#general-assets) (2x)
* [Invigorating Potion](#general-assets) (2x)
* [Laudanum Potion](#general-assets) (3x)
* [Night-Eye Potion](#general-assets) (2x)
* [Poison Resistance Potion](#general-assets) (2x)
* [Smoke Bomb](#general-assets) (3x)

At Level `4+`, you may also craft the following:
* [Blackpowder Bomb](#general-assets) (2x)
* [Illusionist's Powder](#general-assets) (2x)
* [Love Potion](#general-assets) (1x)

At Level `5+`, you may also craft the following:
* [Sleeping Poison](#general-assets) (1x)

At Level `6+`, you may also craft the following:
* [Death Fog](#general-assets) (1x)
* [Paralyzing Poison](#general-assets) (1x)

#### Brewing (Wit/Wit)
The brewing of alcoholic beverages. 

[Crafting](./strive-core.md#crafting--research-projects):
* [Keg Of Alcohol](#general-assets) (1x)

#### Blacksmithing (Agi/Str)
The ability to create every-day items and tools from metal. 

[Crafting](./strive-core.md#crafting--research-projects):
* [Tools](#general-assets) (2x)
* [Trap: Bear](#general-assets) (1x)

#### Bow-Making (Agi/Awar)
The ability to craft bows and crossbows. 

[Crafting](./strive-core.md#crafting--research-projects):
* [Short-Bow](#short-bow) (1x)
* [Longbow](#longbow) (1x)
* [Crossbow](#crossbow) (1x)

#### Carpentry (Agi/Str)
The ability to shape wood to craft predominantly wooden things. 

[Crafting](./strive-core.md#crafting--research-projects):
* Furniture (1x): A unique piece, PI: `20`, TI: `1` Hour

#### Clothesmaking (Agi/Wit)
The ability to make comfortable, well-fitting and decorated clothes. 

[Crafting](./strive-core.md#crafting--research-projects):
* [Clothing](#general-assets) (1x)

#### Engineering (Agi/Wit)
The ability to plan and construct complex mechanisms and devices. 

[Crafting](./strive-core.md#crafting--research-projects):
* [Trap: Acid](#general-assets) (1x)
* [Trap: Bear](#general-assets) (1x)
* [Trap: Cage/Net](#general-assets) (1x)
* [Trap: Powder](#general-assets) (1x)
* [Trap: Rune/Scroll](#general-assets) (1x)
* [Trap: Shooter](#general-assets) (1x)
* [Trap: Windfist](#general-assets) (1x)
* [Magic Recorder](#general-assets) (1x)

#### Fletching (Agi/Awar)
The ability to efficiently craft arrows, bolts and javelins. 

[Crafting](./strive-core.md#crafting--research-projects):
* [Arrows](#general-assets) (20x)
* [Bolts](#general-assets) (20x)

At Level `4+`, you may also craft the following:
* [Acid Arrows](#general-assets) (10x)
* [Explosive Arrows](#general-assets) (5x)
* [Poison Arrows](#general-assets) (10x)

#### Glass-Blowing (Agi/Agi)
The ability to make objects from glass. 

[Crafting](./strive-core.md#crafting--research-projects)

#### Goldsmithing (Agi/Agi)
The ability to make jewelry from precious metals and stones. 

[Crafting](./strive-core.md#crafting--research-projects):
* [Objet d'art](strive-core.md#general-assets)
* [Jewelry](#general-assets)

#### Leatherworking (Agi/Wit)
The ability to create leather objects. 

[Crafting](./strive-core.md#crafting--research-projects):
* [Light Armor](#light-armor) (1x)

#### Masonry (Str/Tough)
The ability to shape stone to craft predominantly stone-based things. 

[Crafting](./strive-core.md#crafting--research-projects)

#### Rune-Smithing (Arc/Wit)
The ability to carve [Magic Runes](#runes) and embed them in arcane devices.

The Level of this Skill dictates the maximum [Intensity](#spell-intensity-si) of the respective magic the carved rune can hold. The number of Hits achieved in a Test then sets the actual Level the rune will hold, but limited by the maximum. 

[Crafting](./strive-core.md#crafting--research-projects):
* [Rune](#runes) (1x)
* [Magic Recorder](#general-assets) (1x)

#### Shield-Making (Str/Wit)
The ability to make shields from conventional materials, such as wood and metal. 

[Crafting](./strive-core.md#crafting--research-projects):
* [Light Shield](#light-shield) (1x)
* [Medium Shield](#medium-shield) (1x)
* [Heavy Shield](#heavy-shield) (1x)

#### Tanning/Skinning (Agi/Tough)
Taking the hide off a creature undamaged. 

[Crafting](./strive-core.md#crafting--research-projects)

#### Weapon Smithing (Str/Wit)
The ability to make weapons from metal. 

[Crafting](./strive-core.md#crafting--research-projects):
* [Axe](#axe) (1x)
* [Crusher](#crusher) (1x)
* [Light Blade](#light-blade) (1x)
* [Long Blade](#long-blade) (1x)
* [Polearm](#polearm) (1x)

At Level `4+`, you may also craft the following:
* At the cost one `-1 Q`, it is possible to add each of the following to a weapon (the weapon **must** have at least `Q 2`):
  * [Serrated](./strive-core.md#serrated)
  * [Poison-Chamber](./strive-core.md#poison-chamber)

At Level `5+`, you may also craft the following:
* [Chained-Blade](#chained-blade) (1x)
* [Firearm](#firearm) (1x)

#### Woodcarving (Agi/Agi)
Creating small things from carved wood. 

[Crafting](./strive-core.md#crafting--research-projects):
* [Objet d'art](strive-core.md#general-assets) (1x)

### Special Skills
The Skills listed in this chapter cannot be learned *by just anyone*. Special requirements are made of those who aspire to learn them.

#### Psionics (Arc/Wit)
A psionic awareness grants access to supernatural abilities beyond those of mere magics. See also [The Veil](#the-veil). 

The psion may choose how much they wish to open up to The Veil. This is represented by their Openness, abbreviated as **OPN**. The OPN they choose may be at most their Level in Psionics. 

* Obvious: The psion's eyes glow with the inscrutable light of the stars, when they use their psionic abilities.
* Prerequisites:
  * Wit `5+` OR innate.
  * Arcana `5+` OR innate.
  * An event that causes a psychic awakening. Consult your GM. 

| Level | Name                 | AP | Distance | Ob                              | Veil Degradation | Effect(s)                      |
| ----- | -------------------- | -- | -------- | ------------------------------- | ---------------- | ------------------------------ |
| 0     | Emotional Connection | 1  | OPN * 10 | Opposed by Self-Control - OPN   | OPN * 2          | Read and/or alter another creature's emotional state. |
| 0     | Telekinesis          | 2  | OPN * 5  | Opposed by Self-Control - OPN   | OPN * 2          | Force move a ST by `OPN * 2`. |
| 0     | Telepathy            | 1  | OPN * 15 | OPN                             | OPN * 2          | **Concentration**: Communicate wordlessly with `OPN` targets. Language barriers do not apply to this form of communication. |
| 0     | Slow Down            | 2  | OPN * 6  | OPN                             | OPN * 2          | **Concentration**: Up to `OPN` targets are slowed. They move `-2` Squares per AP spent! |
| 1     | Repulse              | 1  | 20       | OPN                             | OPN * 3          | **Reaction**: Upon having been attacked successfully, repulse your Attacker psionically. They are force moved backwards by `OPN * 2`. |
| 1     | Levitate             | 1  | OPN * 6  | OPN                             | OPN * 3          | **Concentration**: Cause yourself or one other ST of choice, within *distance* to levitate up to `OPN * 6` Squares above the ground. |
| 1     | "Vanish"             | 1  | OPN * 6  | OPN                             | OPN * 4          | **Concentration**: Cause up to `OPN` targets of choice, within *distance* to become *unperceivable* to `OPN` other targets of choice, within distance. |
| 3     | Veil Hop             | 3  | OPN * 3  | OPN                             | OPN * 5          | Cause a dimensional rift to open and swallow a ST of choice, which another rift releases at a location of your choosing, a moment later. |
| 3     | Join The Veil        | 2  | OPN * 3  | Opposed by Self-Control - OPN   | OPN * 3          | Shroud a ST in the inscrutable darkness of The Beyond. They become [Terrified](strive-core.md#terrified) of the psion and [Marked](./strive-core.md#marked). |
| 4     | Try Again            | 1  |          |                                 | 25               | **Reaction**: When you or someone else resolves a Test, create a minute overlap of timelines, and displace a snippet of your own timeline with a hopefully better one. You or they must now repeat the Test. The new result is final. This can only be attempted once for a given Test. |

**Rituals**

| Level | Name                 | Time Increment | Ob                              | Veil Degradation | Effect(s)                      |
| ----- | -------------------- | -------------- | ------------------------------- | ---------------- | ------------------------------ |
| 4     | Memory Re-write      | 3 Hours        | Opposed by Self-Control - OPN   | OPN * 3          | Re-write the memory of a ST, up to `OPN * 3` Squares away. Make them forget, or implant in them a memory they never had. |

## List of Magic Schools
The capabilities of the various magic schools are described by the [Expertise](./strive-core.md#expertise) associated with each of them. The concrete effects are kept vague on purpose, to allow a certain freedom when choosing how the magic is expressed. But the intensity or strength of a casting is tied to the Level of the [Magic School Skill](#magic-school--school---attribute-). 

The Levels noted for each magic school represent the effects a mage can achieve, when casting that particular type of magic. Stronger effects generally require a higher Level. 

See also [Testing Magic](#testing-magic). 

In all the following tables, note the following:
* Replace *SI* with the chosen [Spell Intensity](#spell-intensity-si). 
* *Level* is the prerequisite Level of the Magic School Skill, at which a given spell becomes available for use. 
* Whenever distances and radii are concerned, a mage may always choose a *shorter* distance or radius. For example, a `SI * 2` radius definition, sets the **maximum**. The radius may be **at most** this large, but can also be smaller, if the mage so chooses. 
* Whenever the effect is unleashed in a cone, then at every point it has traveled, it is as wide as far as it has traveled. So for example, at `2` Squares distance, it is `2` Squares wide. At `3` Squares distance, it is `3` Squares wide. 

### Aeromancy (Arc/Agi)
The control of air, to create and change its flow, for benefit and detriment. 

| Level | Name                 | AP | Distance      | Ob          | Effect(s)                      | Backfire Effect(s) |
| ----- | -------------------- | -- | ------------- | ----------- | ------------------------------ | ------------------ |
| 0     | Wind Tunnel          | 2  | `SI * 3`      | `SI`        | Conjure up a stream of air, that [Force Moves](strive-core.md#forced-movement) all creatures and objects of Bulk less than `SI * 2` in its direction, by `SI * 3` Squares. This gust originates from you. The wind tunnel can also point up, down or any other direction. Can clear away gases and the like. | You lose control and are tossed `SI * 3` Squares in a random direction! |
| 0     | Wind Lance           | 2  | `SI * 3`      | `Opposed`   | Hurl a directed, compacted bolt of air towards a ST. Upon impact, creates a loud whipping noise. <br> `≤ 1` Hit: `2 + SI` Bludgeoning <br> `= 2` Hits: `5 + (SI * 2)` Bludgeoning <br> `≥ 3` Hits: `10 + (SI * 2)` Bludgeoning | The attack is launched in a random direction, instead. |
| 1     | Breathing Bubble     | 2  | `1`           | `SI`        | **Concentration**: Form a stationary bubble of clean air, in a `SI * 2` Squares AoE diameter. | The air is displaced from your lungs for `1` Round, making you unable to speak and you suffer `+1` [Strain](./strive-core.md#stamina--strain)! |
| 2     | Vacuumize            | 2  | `8`           | `SI`        | **Concentration**: Drive all air out of a stationary `SI * 2` Square AoE radius. All creatures caught in the anti-air bubble start suffocating, as all air is driven from their lungs. They suffer `+1` [Strain](strive-core.md#stamina--strain) at the start of every Turn. | The air around you is displaced, instead of the spot of their choosing. The effect lasts `1` Round and you cannot concentrate on any other spell, for as long as it lasts. |
| 3     | Crushing Compression | 2  | `SI * 6`      | `SI`        | Compress the air around a ST, crushing it with `SI * 5` points of Bludgeoning damage. | The air compresses around you instead. |

**Rituals**

| Level | Name                 | Time Increment | Ob          | Ritualists | Effect(s)                      | Side-Effect(s)     | Backfire Effect(s) |
| ----- | -------------------- | -------------- | ----------- | ---------- | ------------------------------ | ------------------ | ------------------ |
| 4     | Tornado              | 1 Hour         | `SI`        | 1+         | **Concentration**: Call forth a tornado, up to `SI * 6` Squares away, and control its movements. It is up to `SI` AoE radius wide and tall, and can displace creatures and objects up to `SI * 2` Bulk, throwing them up to `SI * 2` Squares far, in a random direction. The tornado can clear away gases and the like. | The Tornado forms, but you lose control. It moves unpredictably and randomly. | The air displaces in a `SI * 2` radius around you. Everyone in the AoE is sucked into the vaccuum, which they cannot escape from, for `SI` Rounds. Every turn, they suffer `4` Pure damage and `+1` [Strain](./strive-core.md#stamina--strain) as they suffocate! |

### Artificing (Arc/Wit)
The setting of arcane traps and creation of arcane artifacts and materials. 

[Crafting](./strive-core.md#crafting--research-projects):
* [Arcane Engine](#arcane-engine) (1x)
* [Magic Recorder](#general-assets) (1x)
* [Magic Scroll](#magic-scrolls) (1x)

| Level | Name                 | AP | Distance                | Ob                             | Effect(s)                      | Backfire Effect(s) |
| ----- | -------------------- | -- | ----------------------- | ------------------------------ | ------------------------------ | ------------------ |
| 0     | Place Arcane Charge  | 2  | `1`            | `SI`                 | Focus arcane energy on a point in hand's reach. The surface begins to glow and become magically receptive. Any other spell that is then cast at the same spot, fills the arcane charge. A trigger defined by you will then unleash the stored spell. Note only simple triggers are possible. The charge cannot make distinctions like friend or foe. Example triggers: on touch, on detection of movement in front of the charge, on detection of sound, on the utterance of a specific word. The arcane charge lasts `SI * 4` hours. After that, it harmlessly dissipates. The charge is stationary - it cannot be moved. For every `3 SI` of the Arcane Charge, the spell it holds may be `+1 SI` stronger. | The arcane charge becomes unstable. Roll a `D4` to determine in what way. On a `1`: the stored spell loses half (RD) its `SI` in strength. `2`: the charge triggers in `1D10` minutes. `3`: the charge now only triggers on touch. `4`: the stored spell is overriden. Instead, upon triggering, the charge now emits an excruciatingly loud noise. |
| 0     | Imitate Arcane Echo  | 2  | `10`           | `SI`                 | Draw from a [Magic Echo](#magic-echoes) located up to `10` Squares away and re-new it, casting it again at SI `+1`. This can only be done once per Echo and cannot be used to re-cast *this* spell. The Echo is destroyed by this action. | You suffer the full Backfire of the spell that was imitated. |
| 1     | Elemental Shield     | 2  | `1`            | `SI`                 | **Concentration**: Arcane energy envelops your skin, to counter one specific element of your choosing. You or a ST of your choice, within hand's reach, suffer `SI * 2` less damage of that element's type of damage. Available elements are: [Acid, Burning, Electrical, Freezing, Poison](./strive-core.md#damage-types). | You instead become vulnerable to the element you chose, causing you to take twice as much damage from it! This effect lasts `2` Rounds. |
| 1     | Slag Bomb            | 2  | `6 + SI`       | `SI`                 | Cause `+SI` [Arcane Slag](#arcane-overheat--slag) to all targets within a `3` Square AoE radius at a spot of your choosing. | Instead of the intended spot, the Slag Bomb detonates right in your face. |
| 1     | Detonate Slag        | 2  | `6 + SI`       | `SI`                 | Remove `SI` points of [Arcane Slag](#arcane-overheat--slag) from a ST, within reach and cause them to explode with arcane energy, dealing `N * 4` points of Pure damage to the ST, and `N` points of Pure damage to all adjacent creatures behind it, where *N* is the number of [Arcane Slag](#arcane-overheat--slag) points that were actually removed. | Instead of the intended target's, your own [Arcane Slag](#arcane-overheat--slag) detonates! |

**Rituals**

| Level | Name                 | Time Increment | Ob          | Ritualists | Effect(s)                      | Side-Effect(s)     | Backfire Effect(s) |
| ----- | -------------------- | -------------- | ----------- | ---------- | ------------------------------ | ------------------ | ------------------ |
| 4     | Echo-Chamber         | 1 Hour         | `SI`        | 1+         | **Concentration**: All Magic Echoes may be freely re-cast at full strength in a `SI * 5` Square radius. | In the wake of every Magic Echo an Arcane Disturbance forms, which lasts `2` Rounds and causes `+1` Arcane Slag to all who stand within it every Turn. | Ancient Magic Echoes are re-forged and overwhelm you, causing `SI * 5` Pure damage. |

### Alteration (Arc/Wit)
The alteration of physical things, to change their shape and purpose. And the ability to transform yourself, temporarily. 

| Level | Name                 | AP | Distance       | Ob              | Effect(s)                      | Backfire Effect(s) |
| ----- | -------------------- | -- | -------------- | --------------- | ------------------------------ | ------------------ |
| 0     | Arm Blade            | 2  |                | `SI`            | **Concentration**: Change your arm into a sharp blade of bone. All unarmed attacks may now deal an additional `SI * 5` Slashing damage. | You suffer a random mutation, instead! |
| 0     | Shape Earth          | 2  | `SI * 3`       | `SI`            | Cause earth in a `SI * 2` Square AoE radius, at a spot of the mage's choosing to change shape, as the mage wills it. The shape cannot exceed the radius in size. Could be used to create or tear down an earthen wall, close up a door way, quickly create a trench and so on.<br>If the shaped earth would cause a creature to be crushed, it may stop the earth with an Opposed Strength Test at Ob equal to your chosen SI. Every additional creature being crushed can [assist in the Test](./strive-core.md#providing-assistance). If its Test fails or it cannot resist, it will be pushed aside and suffer `SI * 4` Bludgeoning damage. | Instead of the intended shape, the earth takes on an "inverse" form of what they want. If they wanted a wall, they get a trench. If they wanted a stair leading up, they get one leading down, and so on. |
| 1     | Wings                | 2  |                | `SI`            | **Concentration**: Grow wings! You may now fly up to `SI * 5` Squares high at a speed of `SI * 2` Squares per AP spent. | You suffer a random mutation, instead! |
| 1     | Feel the Shape       | 1  | `SI * 20`      | `SI`            | Place a hand to a surface. You can feel the faintest vibrations and reverberations within and beneath. Can be used to detect underground caves and structures and imprecisely detect the movements of creatures along a given surface, such as the ground. | You become numb and cannot feel anything for `2` Rounds. `-1D` to all Tests and `-1` [Stamina](./strive-core.md#stamina--strain) |
| 2     | Earth Spike Trail    | 3  | `SI * 3`       | `SI`            | Cause spikes of earth to shoot out of a surface that you can lay your hands on. Everyone caught in a straight AoE line of up to `SI * 3` Squares in length, originating from you, suffers `SI * 3` points of Piercing damage. The area of the spikes is then considered Difficult Terrain. The spikes crumble after `1` Round. | You lose control and the spell unleashes in a random direction. |
| 2     | Aspect of the Bull   | 2  |                | `SI`            | **Concentration**: Grow bull horns and bestial legs! You may now run at a speed of `4 + SI` Squares per AP spent. You may now charge at targets and gore them for `SI * 3` points of Piercing damage, but you must run at least `2` Squares in order to make use of this ability. | You suffer a random mutation, instead! |
| 4     | Wereshape            | 3  |                | `3`             | **Concentration**: Assume a were-beast shape. See the were-beasts below. Your Attributes will be modified as noted on each were-beast shape. | Instead of transforming, your body goes into shock! You are [Stunned](./strive-core.md#stunned)! |

**Rituals**

| Level | Name                 | Time Increment | Ob          | Ritualists | Effect(s)                      | Side-Effect(s)     | Backfire Effect(s) |
| ----- | -------------------- | -------------- | ----------- | ---------- | ------------------------------ | ------------------ | ------------------ |
| 0     | Alter Shape          | 10 Minutes     | `SI`        | 1+         | A ST **object** is altered as you desire, **permanently**. Your Ob and SI depend on the complexity and size of the re-shaping. Ob `2` for simple and small, `3` for tricky and medium, `4` for complex and large and `5+` for very complex and very large alterations. Consult your GM! | The shape is altered as intended, but has some flaw or aberration. Consult your GM! | The object arcanically melts. |
| 2     | Alter Flesh          | 1 Hour         | `SI`        | 1+         | A ST **creature** is altered as you desire, **permanently**. Your Ob and SI depend on the complexity and size of the re-shaping. Ob `2` for simple and small, `3` for tricky and medium, `4` for complex and large and `5+` for very complex and very large alterations. Consult your GM! | In addition to the intended alteration, a random [Mutation](./strive-core.md#list-of-mutations) occurs! | You suffer `+3` random Mutations! |
| 4     | Shatter Earth        | 2 Hours        | `SI`        | 1+         | Make earth and rock tremble and shatter in a `SI * 4` Squares radius or `SI * 8` Squares line, up to `SI * 10` Squares away. Can be used to create massive sinkholes and make fortifications crumble. | Half of the AoE, instead of shattering the earth, re-shapes it. Roll `1D4`: On a `1`: The earth transforms into a solid sphere. On a `2`: The surface of the area becomes a thorny ridge of spear-like spikes. On a `3`: The earth forms into a tunnel. On a `4`: The earth rises to form a solid plateau. | You suffer `+3` Bludgeoning Injuries as the tremors rattle your innards! |

#### Werewolf-Shape
A bipedal wolf armed with wicked claws and deadly teeth!

Attributes: `+2` Agi, `+3` Str, `+1` Tough, `-2` Wit; Below, *Level* is the Level of the Skill you get.

| Skill                | Level | AP | Ob          | Description <br> Damage                |
| -------------------- | ----- | -- | ----------- | -------------------------------------- |
| Bite (Agi /Str)      | 3     | 2  | Opposed     | Bite a ST. <br> `≤ 1` Hit: `4` Piercing <br> `= 2` Hits: `6` Piercing <br> `≥ 3` Hits: `8` Piercing |
| Rend (Agi/Str)       | 4     | 2  | Opposed     | Tear a ST to shreds! <br> `≤ 1` Hit: `Str + 3` Slashing; `+1` [Bleeding](./strive-core.md#bleeding) <br> `= 2` Hits: `Str + 4` Slashing; `+2` [Bleeding](./strive-core.md#bleeding) <br> `≥ 3` Hits: `Str + 6` Slashing; `+3` [Bleeding](./strive-core.md#bleeding) |

#### Werebear-Shape
A bipedal bear armed with terrifying claws and protected by a mass of muscle!

Attributes: `-1` Agi, `+4` Str, `+3` Tough, `-2` Wit; Below, *Level* is the Level of the Skill you get.

| Skill                | Level | AP | Ob            | Description <br> Damage          |
| -------------------- | ----- | -- | ------------- | -------------------------------- |
| Rend (Agi/Str)       | 3     | 2  | Opposed       | Tear a ST to shreds! <br> `≤ 1` Hit: `Str` Slashing <br> `= 2` Hits: `Str + 2` Slashing <br> `≥ 3` Hits: `Str + 4` Slashing |
| Bear-Hug (Tough/Str) | 4     | 2  | Opposed + 1   | Bear-hug and squeeze the life out of a ST, who is considered [Grappled](./strive-core.md#grappled)! <br> `≤ 1` Hit: `Str * 2` Bludgeoning <br> `= 2` Hits: `(Str * 2) + 2` Bludgeoning <br> `≥ 3` Hits: `(Str * 2) + 4` Bludgeoning |

### Cryomancy (Arc/Arc)
The summoning and control of ice. Cryomancer's can freeze things, so they're heavier and harder to break. 

| Level | Name                  | AP | Distance      | Ob                           | Effect(s)                      | Backfire Effect(s) |
| ----- | --------------------- | -- | ------------- | ---------------------------- | ------------------------------ | ------------------ |
| 0     | Freezing Touch        | 2  | `1`           | `Opposed - SI`               | A fist-sized spot on a ST, in hand's reach, freezes over and deals `SI * 3` points of Freezing damage. Causes `+1` [Frostbitten](./strive-core.md#frostbitten) | You are affected, instead. |
| 1     | Cold Finger Gun       | 2  | `SI * 5`      | `Opposed`                    | Shoot an ice spike at a ST from your hand. <br> `≤ 1` Hit: `2 + SI` Freezing; `+1` [Frostbitten](./strive-core.md#frostbitten) <br> `= 2` Hits: `6 + SI` Freezing; `+2` [Frostbitten](./strive-core.md#frostbitten) <br> `≥ 3` Hits: `10 + SI` Freezing; `+3` [Frostbitten](./strive-core.md#frostbitten) | The attack is launched in a random direction, instead. |
| 2     | Ice Shape             | 2  | `SI * 5`      | `SI`                         | Turn humidity into ice, in the shape of your choosing, in an AoE radius of up to `SI` Squares. | You suffer `+1` [Frostbitten](./strive-core.md#frostbitten)! |
| 3     | Ice Armor             | 1  |               | `SI`                         | **Reaction**: Upon you or an adjacent target being successfully attacked, turn the surrounding humidity into armor, that absorbs up to `SI * 3` points of damage, before shattering immediately afterwards! The damage the armor absorbs, is the damage you do not suffer! | You suffer `+1` [Frostbitten](./strive-core.md#frostbitten)! |
| 3     | Ice Heart             | 3  |               | `SI`                         | **Concentration**: Up to `SI` MST are protected from the cold and its effects. They do not suffer any Frostbitten and `SI * 2` less Freezing damage. | You suffer `+1` [Frostbitten](./strive-core.md#frostbitten)! |
| 4     | Rooting Freeze        | 3  | `SI * 5`      | `SI + 1`                     | A spot of your choosing freezes over. Anyone caught within the AoE radius of up to `SI * 3` Squares will be frozen to the spot and thus [Rooted](./strive-core.md#rooted) and also suffer <br> `≤ 1` Hit: `SI * 2` points of Freezing damage. <br> `= 2` Hits: `SI * 3` points of Freezing damage. <br> `≥ 3` Hits: `SI * 4` points of Freezing damage. <br> They can break free via a successful [Strength](./strive-core.md#strength-str) Test at Ob `SI`. Or wait, until the ice thaws, which, under normal conditions, will take `2` Rounds. | The spot beneath your own feet is affected, instead. |

**Rituals**

| Level | Name                 | Time Increment | Ob          | Ritualists | Effect(s)                      | Side-Effect(s)     | Backfire Effect(s) |
| ----- | -------------------- | -------------- | ----------- | ---------- | ------------------------------ | ------------------ | ------------------ |
| 4     | Blizzard             | 3 Hours        | `SI`        | 1+         | **Concentration**: Cause a freezing blizzard in a `SI * 10` Squares radius, up to `SI * 10` Squares away. All creatures caught in the blizzard suffer `+1` [Frostbitten](./strive-core.md#frostbitten) per Tick and suffer `SI * 2` Freezing damage. | Pockets form within the blizzard, within which its effects are nullified. | You are frozen solid for `SI` Rounds, rendering you [Rooted](./strive-core.md#rooted) and [Stunned](./strive-core.md#stunned)! |

### Demonology (Arc/Wit)
The study, summoning and control of [Demons](#demons) - as far as they *can* be controlled. 

At level `3`, your [Concentration](./strive-core.md#concentration) limit increases by `+1`!

| Level | Name                  | AP | Distance      | Ob                           | Effect(s)                      | Backfire Effect(s) |
| ----- | --------------------- | -- | ------------- | ---------------------------- | ------------------------------ | ------------------ |
| 0     | Dominate Demon        | 2  | `9 + SI`      | `Opposed by Toughness`       | **Concentration**: Bind a Demon to your will. An ethereal magical chain forms a bond from you to it. The Demon can no longer act independently and will follow every command you give to the letter, but is only capable of *simple* commands, like 'kill that', 'go there', 'fetch that' and so on. The Demon can only distance itself from you by up to `30` Squares. Any farther, and the ethereal chain flickers and breaks. | You are instead bound to the Demon's will, for `1D3` Rounds. |
| 1     | Bolster Demon         | 1  | `SI * 3`      | `SI`                         | **Concentration**: Suffer a penalty of `-SI` to one of your Attributes - but only if that Attribute's level is at least `2` - and award a chosen Demon a boon of `+SI` to **all** its Attributes! This effect lasts `SI` rounds. | The Demon **loses** `-SI` points to **all** Attributes, instead! This effect lasts `3` Rounds. |
| 2     | Assimilate Demon      | 1  | `SI * 3`      | `2`                          | Destroy a Dominated Demon in a violent zap of magic, and in doing so, regain HP equal to its `Toughness * 2` and gain a `+1` boon to an Attribute of choice, for `SI` rounds! | Instead of assimilating the Demon, it splits in two! Both halves re-form to a complete form, but each of them now only have half their Attributes and HP! Also, neither copy is Dominated by you, nor overly thrilled by your existence. |
| 3     | Lock Demon            | 3  | `SI * 3`      | `Opposed by Toughness`       | Lock a Dominated Demon into an object. An arcane seal forms across its surface. If the seal is destroyed, the Demon is released. However, it is no longer Dominated and will fully re-awaken in one Round. You have that much time to Dominate it again. | Instead of locking the Demon, it is no longer Dominated and you instead become bound to its will, for `1D3` Rounds. |

**Rituals**

| Level | Name                 | Time Increment | Ob          | Ritualists | Effect(s)                      | Side-Effect(s)     | Backfire Effect(s) |
| ----- | -------------------- | -------------- | ----------- | ---------- | ------------------------------ | ------------------ | ------------------ |
| 0     | Summon Minor Demon   | 1 Hour         | Determined by Demon | 1+         | Your Ob is your SI. Summon a minor Demon to a chosen location. This requires an [Abyssalite chunk](#abyssalite) the bulk of which depends on the Demon. Note it is not yet Dominated - it may act unpredictably, yet certainly violently. You have one Round to bind it, before it will properly awaken. | A minor Demon also crosses the threshold. Once it awakens in one Round, its blind rage shall be terrible. | You are briefly consumed by the rift to the Demon's world, before it spits you back out. The ordeal causes you `1D10` Pure damage and `+3` [Strain](./strive-core.md#stamina--strain)! |
| 3     | Summon Major Demon   | 3 Hours        | Determined by Demon | 1+         | Your Ob is your SI. Summon a major Demon to a chosen location. This requires a [Malevite Orb](#malevite), the purity of which depends on the Demon. Note it is not yet Dominated - it may act unpredictably, yet certainly violently. You have one Round to bind it, before it will properly awaken. | A minor Demon also crosses the threshold. Once it awakens in one Round, its blind rage shall be terrible. | You are briefly consumed by the rift to the Demon's world, before it spits you back out. The ordeal causes you `1D10` Pure damage and `+3` [Strain](./strive-core.md#stamina--strain)! |

### Divination (Arc/Wit)
Catching glimpses of the unknowable and nudging fate. A Divination mage prefers to stay out of harms way - which their power facilitates. 

| Level | Name                       | AP | Distance      | Ob                           | Effect(s)                      | Backfire Effect(s) |
| ----- | -------------------------- | -- | ------------- | ---------------------------- | ------------------------------ | ------------------ |
| 0     | I Saw It Coming            | 1  | `9`           | `SI`                         | **Reaction**: When you or an ally is successfully attacked, subtract `SI` Hits from the Attacker's roll. This may cause the attack to fail. | The Attacker instead gains `SI` Hits to their roll! |
| 0     | Direct Success             | 2  | `9`           | `SI`                         | **Reaction**: When an ally rolls a Test, add `SI` dice to it, and raise their Hit Limit by `+1`. | Your ally instead loses `SI` dice! |
| 1     | Boost Project              | 4  |               | `SI`                         | Once a day, boost the progress of a [Project](./strive-core.md#crafting--research-projects), by `SI * 3` points! | The Project instead loses `SI * 2` points! |
| 2     | Watch Defense              | 4  |               | `SI`                         | **Concentration**: Up to `SI` MST cannot be Watched. |  |
| 2     | Watch                      | 4  |               | `3`                          | Glimpse a short vision of a person or object, no matter where they are. But only your target is clearly visible. Your peripheral vision is blurred and foggy. | The target becomes aware that the winds of magic swirled in agitation around them. They might not know *who* Watched them, but they may figure out *that* they were Watched. |
| 4     | Calamitous Prognostication | 3  | `SI * 3`      | `3`                          | In one Round, something bad happens to a ST. Choose: `1`: Something falls on their head or they stumble and fall prone. `2`: They are mistaken for a foe by their allies or they might mistake their allies for foes. `3`: They drop something they are holding or which is on their person. `4`: The winds of magic are agitated, causing `+1` [Arcane Slag](#arcane-overheat--slag). | You are affected, instead! |

**Rituals**

| Level | Name                 | Time Increment | Ob          | Ritualists | Effect(s)                      | Side-Effect(s)     | Backfire Effect(s) |
| ----- | -------------------- | -------------- | ----------- | ---------- | ------------------------------ | ------------------ | ------------------ |
| 2     | Look Ahead           | 1 Hour         | `2`         | 1+         | Your Ob is your SI. Glimpse into the future. Causes `+2` [Strain](./strive-core.md#stamina--strain). Consult your GM: <br> `≤ 1` Hit: A momentary glimpse into the immediate future. <br> `= 2` Hits: A brief glimpse of a near future. <br> `≥ 3` Hits: A detailed vision of a *possible* future event. | You glimpse a vision, but you cannot be certain of whether it is the future or past or even from which universe. | Instead of a vision of the future, your mind is brought before the attention of an ancient horror, which overwhelms your senses and sends you into shock! You are [Stunned](./strive-core.md#stunned) for `3` hours! |

### Electromancy (Agi/Arc)
The summoning and control of lightning. Electricity is fairly versatile - it can injure, revive and power or trigger electrical and electronic devices. 

| Level | Name                  | AP | Distance       | Ob                           | Effect(s)                      | Backfire Effect(s) |
| ----- | --------------------- | -- | -------------- | ---------------------------- | ------------------------------ | ------------------ |
| 0     | Shocking Touch        | 2  | `1`            | `Opposed - SI`               | A small area, about the size of your hand is burned on touch by an electrical shock, dealing `SI * 3` points of Electrical damage to a ST. Causes [Electrified](./strive-core.md#electrified) in the victim. | You are affected, instead. |
| 1     | Shock                 | 2  | `SI * 3`       | `Opposed`                    | An arc of lightning strikes the vulnerable internals of a ST, and may arc around corners, dealing `SI * 4` points of Electrical damage. Causes [Electrified](./strive-core.md#electrified) in the victim. | You are affected, instead. |
| 1     | Power-Up              | 2  | `SI * 2`       | `SI`                         | An electrical device is powered up for `SI * 5` minutes. | The device breaks or otherwise seizes up and becomes unusable. |
| 2     | Defibrillate          | 2  | `SI * 2`       | `Opposed`                    | An [Unconscious](./strive-core.md#unconscious) ST is jolted back to consciousness! This includes Characters at [Death's Door](./strive-core.md#deaths-door). They still have to succeed Tests to end the [Death's Door](./strive-core.md#deaths-door) Condition. | You are [Stunned](./strive-core.md#stunned) for `1` Round. |
| 4     | UNLIMITED POWER       | 2  | `SI * 5`       | `SI + 1`                     | An AoE cone of lightning spews forth from your finger tips. Up to `SI + 1` targets can be hit with the shock. Causes [Electrified](./strive-core.md#electrified) in the victims. <br> `≤ 1` Hit: `3` Electrical <br> `= 2` Hits: `5` Electrical <br> `≥ 3` Hits: `8` Electrical | You and anyone next to you is affected, instead. |

**Rituals**

| Level | Name                 | Time Increment | Ob          | Ritualists | Effect(s)                      | Side-Effect(s)     | Backfire Effect(s) |
| ----- | -------------------- | -------------- | ----------- | ---------- | ------------------------------ | ------------------ | ------------------ |
| 2     | Electric Wall        | 10 Minutes     | `SI`        | 1+         | **Concentration**: Creates a wall of pure electricity, up to `SI * 3` Squares in diameter and up to `SI * 3` Squares away. Anything that passes through it is zapped with `SI * 4` Electrical damage. | Occasionally, gaps form in the wall, which the lightning bends around. | You are struck with lightning that bounces between you and the environment. You suffer `SI * 4` Electrical damage. |

### Hexing (Arc/Arc)
The casting of curses to weaken others. 

| Level | Name                  | AP | Distance      | Ob                        | Effect(s)                      | Backfire Effect(s) |
| ----- | --------------------- | -- | ------------- | ------------------------- | ------------------------------ | ------------------ |
| 0     | Instill Fear          | 2  | `SI * 5`      | Opposed by `Self-Control` | **Concentration**: [Terrify](strive-core.md#terrified) `SI` MST. | You are affected, instead. |
| 0     | Slow Down             | 2  | `SI * 3`      | Opposed by `Self-Control` | Reduce a ST's [AP](./strive-core.md#action-points-ap) regain per Turn by `-1` for `SI` Turns and reduce their current AP by `-1`. Does not stack. | You are affected, instead. |
| 1     | Weaken                | 2  | `SI * 5`      | Opposed by `Toughness`    | **Concentration**: Cause a ST to take `SI * 2` more points of damage from a chosen damage type. | You are affected, instead. The effect lasts for `1` Round and you **cannot** concentrate on any other spell for that duration. |
| 2     | Atrophy               | 2  | `SI * 3`      | Opposed by `Toughness`    | **Concentration**: Weaken a ST's Strength by `SI` Levels. Also, they deal `SI * 2` fewer points of damage per physical attack. | You are affected, instead. The effect lasts for `1` Round and you **cannot** concentrate on any other spell for that duration. |
| 2     | Spray Acid            | 2  | `SI * 3`      | `SI`                      | Spray acid in an AoE cone. <br> `≤ 1` Hit: `SI * 2` Acid <br> `= 2` Hits: `SI * 3` Acid <br> `≥ 3` Hits: `SI * 4` Acid | The effect triggers in reverse, pointing the cone straight through you and backwards! |
| 3     | Slag to Acid          | 2  | `SI * 5`      | Opposed by `Toughness`    | Convert the [Arcane Slag](#arcane-overheat--slag) of a ST within reach into acid! They lose `SI` points of [Arcane Slag](#arcane-overheat--slag), which convert into `N * 6` points of Acid damage, where *N* is the number of [Arcane Slag](#arcane-overheat--slag) points removed! | You are affected, instead! |

**Rituals**

| Level | Name                 | Time Increment | Ob          | Ritualists | Effect(s)                      | Side-Effect(s)     | Backfire Effect(s) |
| ----- | -------------------- | -------------- | ----------- | ---------- | ------------------------------ | ------------------ | ------------------ |
| 2     | Lumbago              | 1 Hour         | `SI`        | 1 - 1      | Cause a ST to become paralyzed and [Stunned](./strive-core.md#stunned) with pain for `SI` hours. | The effect alternates between hours of pain and hours of normality. | You instead suffer the Lumbago. |
| 3     | Acid Tide            | 1 Hour         | `SI`        | 1+         | Create a tidal wave of acid, up to `SI * 5` Squares in diameter and send it up to `SI * 10` Squares far. It causes `SI * 3` Acid damage to all it touches. The acid remains once settled and can be used to fill pits and trenches. | The Ritual loses half its SI. | The acid forms in a tornado around you and sucks all within the AoE into it, for `SI` Rounds! |

### Hydromancy (Agi/Arc)
The control of directly accessible water. Blood and creatures cannot be affected by this school. 

Contact with **magically fouled water** will always cause [Illnesses](./strive-core.md#illness)! Fortunately, fouled water does not mix with pure water. But it also cannot be purified - it is, under normal circumstances, **irreversibly** fouled! 

| Level | Name                 | AP | Distance      | Ob                        | Effect(s)                      | Backfire Effect(s) |
| ----- | -------------------- | -- | ------------- | ------------------------- | ------------------------------ | ------------------ |
| 0     | Alter Liquid         | 2  | `SI * 5`      | `SI`                      | Change a non-blood body of liquid in up to a `SI * 3` Square AoE radius to change into pure water, acid or poison. | The liquid instead evaporates. |
| 0     | Shape Water          | 2  | `SI * 5`      | `SI`                      | **Concentration**: Cause water in a `SI * 3` Square diameter or line to assume any shape you desire. | You lose control and the water instead becomes hyper-dense and shoots bullet-like droplets in every direction! All in a `SI` Square radius around the intended spot suffer `SI * 2` Piercing damage. |
| 1     | Fluid Whip           | 2  | `SI * 3`      | `Opposed`                 | Cause a fluid to lash out at a ST, like a whip. <br> `≤ 1` Hit: `SI * 4` Slashing <br> `= 2` Hits: `SI * 6` Slashing <br> `≥ 3` Hits: `SI * 8` Slashing | You lose control and the whip strikes in a random direction! |
| 2     | Harden Fluid         | 2  | `SI * 3`      | `SI`                      | **Concentration**: Cause a fluid in an AoE diameter or line of up to `SI * 5` Squares to become as solid as rock and sturdy enough to walk on and prevent all movement hrough it. | You lose control and the water instead gets sucked onto your body, where it hardens, rendering you [Rooted](./strive-core.md#rooted) for `3` Rounds! |
| 2     | Water Bullet         | 2  | `SI * 5`      | `Opposed`                 | Cause a fluid to become hyper-dense and shoot towards a ST, like a bullet. <br> `≤ 1` Hit: `SI * 5` Piercing <br> `= 2` Hits: `SI * 6` Piercing <br> `≥ 3` Hits: `SI * 7` Piercing | You lose control and the bullet shoots in a random direction! |
| 3     | Desiccate            | 2  | `SI * 5`      | `Opposed`                 | Draw the water right out of a ST! They suffer `+3` [Strain](./strive-core.md#stamina--strain) and `SI * 2` Pure damage. Only works on bodies that actually contain water. | You are affected, instead! |
| 3     | Explosive Evaporation| 3  | `SI * 10`     | `SI`                      | Cause non-blood liquid in a `SI` Square AoE diameter to instantaneously evaporate, separating out the hydrogen, some of which explodes, dealing `SI * 3` Bludgeoning damage! | You are instead Desiccated! |

**Rituals**

| Level | Name                 | Time Increment | Ob          | Ritualists | Effect(s)                      | Side-Effect(s)     | Backfire Effect(s) |
| ----- | -------------------- | -------------- | ----------- | ---------- | ------------------------------ | ------------------ | ------------------ |
| 2     | Conjure Rain         | 10 Minutes     | `SI`        | 1+         | **Concentration**: Cause rain to fall in an AoE diameter or line of up to `SI * 10` Squares, up to `SI * 10` Squares away. | Foul water rains from the sky! Anyone caught in it will suffer an [Illness](./strive-core.md#illness)! | Water is drawn from your body and you dehydrate dangerously. You suffer `+3` [Strain](./strive-core.md#stamina--strain) and `6` Pure damage. |
| 2     | Conjure Fog          | 10 Minutes     | `SI`        | 1+         | **Concentration**: Cause fog to form in an AoE diameter or line of up to `SI * 10` Squares, up to `SI * 10` Squares away. The fog imposes a `-2` penalty to all Tests through or within it that rely on sight. | The fog forms, but has pockets of within it where there is no fog, at all. | Water is drawn from your body and you dehydrate dangerously. You suffer `+3` [Strain](./strive-core.md#stamina--strain) and `6` Pure damage. |

### Illusion (Arc/Awar)
Creation of non-physical influences on the senses. That includes images, sounds and odors. The illusions cannot cause direct harm, although they can drive an individual to acts that may put them in danger. 

| Level | Name                 | AP | Distance       | Ob                        | Effect(s)                      | Backfire Effect(s) |
| ----- | -------------------- | -- | -------------- | ------------------------- | ------------------------------ | ------------------ |
| 0     | Stationary Illusion  | 2  | `SI * 10`      | `SI`                      | **Concentration**: Create a stationary illusory image, sound and/or smell in a radius of up to `SI * 3` Squares. The illusion can be debunked, with an [Observation](./strive-core.md#observation-awarawar) Test at Ob equal to `SI + 1`. | You lose control and your worst fear manifests in front of you! You become [Terrified](./strive-core.md#terrified) of this errant illusion, for `1` Round! |
| 0     | Disguise             | 2  | `10`           | `SI`                      | **Concentration**: Up to `SI` MST creatures' appearance, sound of voice, even smell, is changed as you desire. Note this is only an illusion and represents no *actual* change! The illusion can be debunked, with an [Observation](./strive-core.md#observation-awarawar) Test at Ob equal to `SI + 1`. | You lose control and instead of the intended change, the creatures change into your worst fear! You become [Terrified](./strive-core.md#terrified) of them, for `1` Round! |
| 1     | Illusory Duplicates  | 2  | `SI * 3`       | `SI`                      | **Concentration**: `SI` number of illusory copies of a ST emerge. The distracting images move around the the ST and each of them makes it `+1` Ob harder to hit the ST. Every time the ST is attacked, one of the illusory duplicates is removed. When no duplicates remain, the spell ends automatically. | Instead of making it harder to hit the ST, the illusory duplicates are faulty and easily debunked. But they are distracting to the ST, making it `-1` Ob easier to hit them! |
| 2     | Conceal              | 3  | `SI * 3`       | `SI`                      | **Concentration**: Up to `SI` targets become invisible. The light bends around them, but doesn't make them ethereal. | You lose control and instead of becoming invisible, a terrible noise emanates from you and your targets, for `SI` Rounds! |

**Rituals**

| Level | Name                 | Time Increment | Ob          | Ritualists | Effect(s)                      | Side-Effect(s)     | Backfire Effect(s) |
| ----- | -------------------- | -------------- | ----------- | ---------- | ------------------------------ | ------------------ | ------------------ |
| 3     | Fake World           | 1 Hour         | `SI`        | 1+         | **Concentration**: Create a stationary illusion of image, sound and smell in a radius of up to `SI * 10` Squares around you. The illusion is flawless and can only be debunked with an Observation Test at Ob `SI + 1`. | The illusion is faulty in places. | Your worst fears manifest, haunting and [Terrifying](./strive-core.md#terrified) you for `SI` Rounds. |

### Pyromancy (Arc/Arc)
The summoning and control of fire. The flame being a destructive force, pyromancers enjoy little utility from their magic, beyond the ability to create light and heat. 

| Level | Name                 | AP | Distance       | Ob                        | Effect(s)                      | Backfire Effect(s) |
| ----- | -------------------- | -- | -------------- | ------------------------- | ------------------------------ | ------------------ |
| 0     | Burning Touch        | 2  | `1`        | `Opposed - SI`            | A controlled flame erupts and stays in your hand, inflicting `SI * 3` points of Burning damage and `+1` [Burning](./strive-core.md#burning) on touch, to a ST. | You are affected, instead. |
| 1     | Flame Whip           | 2  | `SI * 3`   | `Opposed`                 | Lash out at a ST with a whip made of pure fire. <br> `≤ 1` Hit: `SI * 2` Burning; `+1` [Burning](./strive-core.md#burning) <br> `= 2` Hits: `SI * 4` Burning; `+2` [Burning](./strive-core.md#burning) <br> `≥ 3` Hits: `SI * 6` Burning; `+3` [Burning](./strive-core.md#burning) | You lose control and the whip lashes out in a random direction, instead! |
| 1     | Imbue Flame          | 2  | `SI * 3`   | `SI`                      | **Concentration**: Cover an object in flames that do not burn it! All attacks made with that object deal an additional `SI * 2` points of Burning damage! | The flames *do* consume the object they cover! The object *can* still be carried or wielded, but will deal `SI * 2` points of Burning damage to whoever does, at the start of their every Turn! |
| 2     | Cone of Fire         | 3  | `SI * 2`   | `SI + 1`                  | Shoot a burst of fire in an AoE cone. <br> `≤ 1` Hit: `SI * 2` Burning; `+1` [Burning](./strive-core.md#burning) <br> `= 2` Hits: `SI * 4` Burning; `+2` [Burning](./strive-core.md#burning) <br> `≥ 3` Hits: `SI * 6` Burning; `+3` [Burning](./strive-core.md#burning) | The effect triggers in reverse, pointing the cone backwards, through your face. |
| 3     | Fire Ball            | 2  | `SI * 15`  | `SI`                      | Form a large ball of flame between your hands, ready to be flung at a target location, affecting an AoE radius of `SI` Squares. <br> `≤ 1` Hit: `SI` Burning; `+1` [Burning](./strive-core.md#burning) <br> `= 2` Hits: `SI * 2` Burning; `+1` [Burning](./strive-core.md#burning) <br> `≥ 3` Hits: `SI * 3` Burning; `+2` [Burning](./strive-core.md#burning) | The fire ball instead launches in a random direction, impacting with the first obstacle it comes across! |
| 3     | Flame Armor          | 1  |               | `SI`                         | **Reaction**: Upon you or an adjacent target being successfully attacked, engulf yourself or them in flames, that burst forth and absorb up to `SI * 3` points of damage. | You suffer `+1` [Burning](./strive-core.md#burning)! |
| 4     | Flame Jet            | 3  | `SI * 3`   | `SI + 1`                  | **Concentration**: A steady stream of flame shoots from your hands, dealing `SI * 2` points of Burning damage and inflicting `+1` [Burning](./strive-core.md#burning) to anything caught by it, in a straight AoE line. | The line of fire erupts backwards, through you! This lasts `1` Round and you **cannot** concentrate on any other spells in the meantime! |

**Rituals**

| Level | Name                 | Time Increment | Ob          | Ritualists | Effect(s)                      | Side-Effect(s)     | Backfire Effect(s) |
| ----- | -------------------- | -------------- | ----------- | ---------- | ------------------------------ | ------------------ | ------------------ |
| 5     | Rain of Fire         | 3 Hours        | `SI`        | 1+         | **Concentration**: Fire rains from the sky in a `SI * 10` Square radius, up to `SI * 15` Squares far away. Everything caught in the falling flames and sparks catches fire, suffering `SI * 3` Burning damage and `+1` [Burning](./strive-core.md#burning) Condition! | The blanket of firery precipitation has holes. | You are immolated, suffering `SI * 3` Burning damage and `+3` [Burning](./strive-core.md#burning) Condition! |

### Restoration (Arc/Awar)
The mending of the body and mind.

| Level | Name                 | AP | Distance   | Ob                           | Effect(s)                      | Backfire Effect(s) |
| ----- | -------------------- | -- | ---------- | ---------------------------- | ------------------------------ | ------------------ |
| 0     | Treating Touch       | 2  | `1`    | `Injury Ob - SI`             | An [Injury](./strive-core.md#injury) of a ST of your choosing, in hand's reach, is magically healed and removed. Only one such treatment can safely be made, per creature, every `6` hours. If a treatment is made before the waiting time is up, roll a `D6` - a `1` will cause the patient to suffer a mutation, while a `2` through `5` will cause them and you `+2` [Arcane Slag](#arcane-overheat--slag). A `6` is lucky and will cause no negative effects. <br> `≤ 1` Hit: Also restores `SI * 2` [HP](./strive-core.md#health-points-hp) <br> `= 2` Hits: Also restores `SI * 3` [HP](./strive-core.md#health-points-hp) <br> `≥ 3` Hits: Also restores `SI * 4` [HP](./strive-core.md#health-points-hp) | You suffer `SI * 5` points of [Bleeding](./strive-core.md#damage-types) damage. |
| 2     | Clear Mind           | 2  | `SI 3` | `2`                          | Removes the [Terrified](strive-core.md#terrified), [Jealous](strive-core.md#jealous), [Pacified](./strive-core.md#pacified), [Marked](./strive-core.md#marked) and [Stunned](./strive-core.md#stunned) Conditions from a ST in reach. | You become [Stunned](./strive-core.md#stunned)! |
| 2     | Life Leech           | 2  | `1`    | Opposed by `Toughness`       | Draw the life from a ST creature. Deals damage while healing the your own [HP](./strive-core.md#health-points-hp) for the same amount. May transfer `SI` points of [Bleeding](./strive-core.md#bleeding) or [Poisoned](./strive-core.md#poisoned) to the damaged creature, if you so choose. <br> `≤ 1` Hit: `SI * 2` Bleeding <br> `= 2` Hits: `SI * 3` Bleeding <br> `≥ 3` Hits: `SI * 4` Bleeding | The effect triggers in reverse. |
| 2     | Expel Illness        | 3  | `1`    | `Illness Ob - SI`            | Removes one [Illness](./strive-core.md#illness) of choice from a ST of choice, in hand's reach. | You contract a random [Illness](./strive-core.md#illness). | 
| 4     | Reduce Slag          | 3  | `1`    | `SI + 1`                     | Remove `SI` points of [Arcane Slag](#arcane-overheat--slag) from a ST! If successful, this spell does not cause [Arcane Slag](#arcane-overheat--slag). | Instead of removing any [Arcane Slag](#arcane-overheat--slag), you gain `+2` points of it! |

**Rituals**

| Level | Name                 | Time Increment | Ob          | Ritualists | Effect(s)                      | Side-Effect(s)     | Backfire Effect(s) |
| ----- | -------------------- | -------------- | ----------- | ---------- | ------------------------------ | ------------------ | ------------------ |
| 4     | Revert Mutation      | 10 Minutes     | `6 - SI`    | 1+         | Removes `SI` [Mutations](./strive-core.md#list-of-mutations) from a ST of choice, in hand's reach. | Half (RD) of the Mutations are not removed, but randomly replaced with other ones. | You suffer a random Mutation. |

### Sanguinomancy (Arc/Tough)
In the common tongue, blood magic, utilizes fresh mage blood to disturbing effect. 

| Level | Name                 | AP | Distance        | Ob                         | Effect(s)                      | Backfire Effect(s) |
| ----- | -------------------- | -- | --------------- | -------------------------- | ------------------------------ | ------------------ |
| 0     | Infusion             | 1  |                 | `SI`                       | **Concentration**: Cut a gash into your skin, arcanically charge your blood and smear it on something (like a weapon). The blood begins to boil, causing it to deal an additional `SI * 3` [Burning](./strive-core.md#damage-types) damage. You may avoid suffering [Arcane Overheat](#arcane-overheat--slag) if you choose to suffer `1D10` [Bleeding](./strive-core.md#damage-types) damage, instead. | You suffer `SI D4` points of [Bleeding](./strive-core.md#damage-types) damage. |
| 0     | Snap                 | 2  | `10`            | Opposed by `Toughness + 1` | Snap a twig or similar and channel the destructive power into a victim. They suffer a [Bludgeoning Injury](./strive-core.md#bludgeoning-injuries) and `SI * 3` points of [Bleeding](./strive-core.md#damage-types) damage. | You suffer the Injury, instead. |
| 1     | Blood Whip           | 2  | `SI * 5`        | `Opposed`                  | Have your blood lash out at a ST. You may avoid suffering [Arcane Overheat](#arcane-overheat--slag) if you choose to suffer `1D10` [Bleeding](./strive-core.md#damage-types) damage, instead. <br> `≤ 1` Hit: `3 + SI` [Slashing](./strive-core.md#damage-types) + `SI * 2` [Bleeding](./strive-core.md#damage-types) <br> `= 2` Hits: `5 + SI` [Slashing](./strive-core.md#damage-types) + `SI * 2` [Bleeding](./strive-core.md#damage-types) <br> `≥ 3` Hits: `8 + SI` [Slashing](./strive-core.md#damage-types) + `SI * 3` [Bleeding](./strive-core.md#damage-types) | You suffer `1D10` points of [Bleeding](./strive-core.md#damage-types) damage. |
| 2     | Blood Boil           | 2  | `SI * 2`        | Opposed by `Toughness + 1` | Bring a ST's blood to a boil. <br> `≤ 1` Hit: `SI * 2` Pure <br> `= 2` Hits: `SI * 3` Pure <br> `≥ 3` Hits: `SI * 4` Pure | You suffer `1D10 burning` damage, instead. |
| 2     | Bond of Suffering    | 1  | `SI * 5`        | `SI`                       | **Concentration**: Your blood forms a bond between two designated creatures, who then share all damage and healing. You may avoid suffering [Arcane Overheat](#arcane-overheat--slag) if you choose to suffer `1D10` [Bleeding](./strive-core.md#damage-types) damage, instead. | You suffer twice as much damage from all physical sources, until the start of your next Turn. |
| 2     | Life Leech           | 2  | `1`             | Opposed by `Toughness`     | Draw the life from a ST creature of choice. Deals `SI * 3` points of [Bleeding](./strive-core.md#damage-types) damage while healing your own [HP](./strive-core.md#health-points-hp) for the same amount. May transfer `SI` points of [Bleeding](./strive-core.md#bleeding) or [Poisoned](./strive-core.md#poisoned) from to the creature, if you so choose. | The effect triggers in reverse. |
| 3     | Blood Armor          | 1  |                 | `SI`                       | **Reaction**: Upon you or an adjacent target being successfully attacked, have your or your ally's blood form a hardened shell that absorbs up to `SI * 3` points of damage. | You suffer `+1` [Bleeding](./strive-core.md#bleeding)! |
| 4     | Slagletting          | 2  |                 | `SI + 1`                   | Remove `SI` points of [Arcane Slag](#arcane-overheat--slag) from yourself or a ST, but suffer `3` points of [Bleeding](./strive-core.md#damage-types) damage for each point of [Arcane Slag](#arcane-overheat--slag) that is removed! If successful, this spell does not cause [Arcane Slag](#arcane-overheat--slag). | Instead of removing any [Arcane Slag](#arcane-overheat--slag), you gain `+2` points of it and suffer `6` points of Bleeding damage! |

**Rituals**

| Level | Name                 | Time Increment | Ob                        | Ritualists | Effect(s)                      | Side-Effect(s)     | Backfire Effect(s) |
| ----- | -------------------- | -------------- | ------------------------- | ---------- | ------------------------------ | ------------------ | ------------------ |
| 3     | Crimson Tracks       | 10 Minutes     | `SI`                      | 1+         | If you have someone's blood, use it to track them up to `SI * 150` Squares far. If successful, you get a general sense of how far away and in what direction relative to your facing they are. You also glimpse a momentary fragment of their current emotional state. | The victim is overcome with an odd premonition and becomes aware *someone* attempted to track them. | Instead of tracking the target, it instead becomes briefly aware of the Ritualists' thoughts and emotions and may figure out *who* was trying to track them. |
| 5     | Puppeteer            | 1 Hour         | Opposed by `Self-Control` | 1+         | **Concentration**: Command the blood of a victim to obey you. You control their actions, like a puppeteer. Any action you make them take, costs *their* AP. They may try to resist at the beginning of their every Turn, or once every minute, with a [Self-Control](./strive-core.md#self-control-toughwit) Test at Ob equal to the number of Hits you achieved. | While in control of someone else, the head Ritualist cannot move or perceive their own body. | `5` pulsating tendrils of blood burst from your skin, which last `5` Rounds. If any of the tendrils is cut, the you suffer `3` Pure damage, each time. |

### Soul-Binding (Arc/Tough)
Also referred to as **necromancy**, this is the art and skill of calling souls from the Plane Of The Dead and binding them, to reanimate corpses or animate an otherwise unliving body. 

In order to bind a soul, a Soul-Seal is required. This seal has to take the form of a pentagram. The medium doesn't matter, although if the seal is destroyed, the soul binding is broken. So, if a mage wants to create a lasting soul-binding, an enduring medium for the seal is advisable. A mage can only ever issue commands to a soul that they themself have bound. It is not possible to command souls bound by other mages. 

| Level | Name                 | AP | Distance      | Ob                     | Effect(s)                      | Backfire Effect(s) |
| ----- | -------------------- | -- | ------------- | ---------------------- | ------------------------------ | ------------------ |
| 0     | Soul Blast           | 2  | `SI * 5`      | Opposed by `Tough + 1` | Blast the soul from a ST's body. The experience weakens them, rendering them [Marked](strive-core.md#marked). <br> `≤ 1` Hit: `SI * 2` Pure <br> `= 2` Hits: `SI * 3` Pure <br> `≥ 3` Hits: `SI * 4` Pure | You are affected, instead. |
| 1     | Command Bound Soul   | 1  | `SI * 3`      | Opposed by `Wit - SI`  | Issue a single command that a bound soul **must** follow. | Instead of the intended command, it will hear some other, random order. Consult your GM! |
| 1     | Break Binding        | 3  |               | `SI of the seal`       | Break a Soul-Binding and send the soul back to the Plane Of The Dead, leaving its former body inanimate and soulless. | Your soul is momentarily displaced from your body. You suffer `10` points of Pure damage! |
| 2     | Soul Tether          | 1  | `SI * 5`      | `2`                    | **Concentration**: An ethereal tether forms between two designated creatures, who then share all damage and healing. Both creatures are perfectly aware of each other's location and current emotional state and may even exchange thoughts. | You suffer twice as much damage from all physical sources, until the start of your next Turn. |

**Rituals**

| Level | Name                 | Time Increment | Ob          | Ritualists | Effect(s)                      | Side-Effect(s)     | Backfire Effect(s) |
| ----- | -------------------- | -------------- | ----------- | ---------- | ------------------------------ | ------------------ | ------------------ |
| 0     | Call and Bind a Soul | 10 Minutes     | `SI`        | 1+         | Create a Soul-Binding at the strength of the chosen `SI`. The larger, heavier and more complex a body is, the harder it is to create a binding. Anything larger than, heavier or more complex than a human will make the Soul-Binding harder. `2` for a small and simple, `3` for a moderate, `4` for a large and `5+` for a huge and complex binding. Consult your GM. Requires a Soul-Seal. Replacing an existing binding is possible, but the Test must exceed the original soul-seal's strength. | The ordeal is particularly difficult and causes `+3` [Strain](./strive-core.md#stamina--strain). | Your soul is momentarily displaced from your body. You suffer `1D10` points of Pure damage! |
| 5     | Call back a Soul     | 1 Hour         | `5`         | 1+         | Target a specific soul and recall them into their prior body. This isn't, strictly speaking, the same as binding a soul. It is easier to recall the soul that previously inhabited a body, the shorter the time of death has been. However, targeting a specific soul is an immensely difficult undertaking and shouldn't be taken lightly. | The ordeal is particularly difficult and causes `+3` [Strain](./strive-core.md#stamina--strain). | Your soul is evicted from your body and another soul takes its place. Your Character is effectively removed from the world. |
| 5     | Create Phylactery    | 1 Hour         | `4`         | 1          | Bind a portion of your Aetherium - soul and DNA - to a chunk of Abyssalite. For as long as the Phylactery remains intact, every time you die, it will bring you back to life near it, but every revival will cost you some of your sanity and you lose `-1` Wit. | The Phylactery becomes flawed. It will revive you as planned, but imperfectly. You suffer `+1` random Injury upon revival. | Your soul is temporarily drawn into the Phylactery and your body becomes a mindless Zombie for `5` Rounds! |

### Telekinesis (Arc/Agi)
The ability to affect things and even creatures from afar, using magic instead of muscles or tools. 

When using objects as projectiles, choose the [Damage Type](./strive-core.md#damage-types) as appropriate. For example, a crossbow bolt might cause Piercing damage, while a rock might cause Bludgeoning damage.

The mage can only ever perform *one* movement with a spell cast. So, for example, it is not possible to violently shake things or creatures around, without casting **telekinesis** multiple times, to do so. During combat, every movement takes one Turn. Out of combat, about five seconds. A single movement is a displacement from one point to another, in a straight and uninterrupted line. 

Only targets within and up to the given *distance* can be moved and only within and up to that *distance* from the mage. 

| Level | Name                   | AP | Distance      | Ob                           | Effect(s)                      | Backfire Effect(s) |
| ----- | ---------------------- | -- | ------------- | ---------------------------- | ------------------------------ | ------------------ |
| 0     | Force Push             | 2  | `SI * 5`      | `SI`                         | In a `SI * 2` Square AoE cone, push back all, by `SI` Squares. | You lose control and the cone blasts backwards, through you! |
| 0     | Telekinesis            | 2  | `SI * 5`      | `SI`                         | Move an inanimate ST object at great velocity (if desired). | You lose control and the object is flung in a random direction! |
| 1     | Force Wall             | 2  | `SI * 5`      | `SI`                         | Create a wall of purple force in a `SI * 2` Squares line that will push anyone who touch it back by `SI` Squares. | You lose control and the wall is formed in a random line, instead. |
| 1     | Hold Fluid             | 2  | `SI * 5`      | `SI`                         | **Concentration**: Cause an up to `SI * 3` large body of water to levitate. | You lose control and are thrown `SI` Squares in a random direction! |
| 2     | Forceful Strikes       | 1  | `SI * 5`      | `SI`                         | **Concentration**: Up to `SI` MST's weapons glow purple and are enhanced with unnatural force. Every strike with them deals an additional `SI * 2` Bludgeoning damage. | You lose control and are thrown `SI` Squares in a random direction! |
| 3     | Creature Telekinesis   | 3  | `SI * 5`      | `Opposed`                    | Force move a ST creature up to `SI * 3`. | You are thrown `SI * 2` Squares in a random direction! |
| 3     | Force Bubble           | 2  | `SI * 5`      | `Opposed`                    | **Concentration**: Form a purple force bubble around a ST that will move with them. It is up to `SI` Squares in radius large and will prevent anything from entering or leaving it. The bubble will push aside all other characters and prevents any and all abilities from passing it. Attacking through it is impossible, but so is helping an ally. | The bubble becomes stationary, instead, and stays for `3` Rounds. |

**Rituals**

| Level | Name                 | Time Increment | Ob          | Ritualists | Effect(s)                      | Side-Effect(s)     | Backfire Effect(s) |
| ----- | -------------------- | -------------- | ----------- | ---------- | ------------------------------ | ------------------ | ------------------ |
| 4     | Grand Levitation     | 1 Hour         | `SI`        | 1+         | **Concentration**: Everything in a `SI * 10` Square diameter begins to levitate, up to `SI * 5` Squares high above the ground. This may even include the ground, for example to create a levitating island. | Wayward force streams form, which push and pull objects in random directions, by `SI * 3` Squares. | The forces at work form an unstable torrent, `SI * 5` squares in diameter, that crushes everything it comes into contact with, for `SI * 4` Bludgeoning damage. |

### Telepathy (Arc/Wit)
The ability to communicate wordlessly, to alter emotions and even issue compelling commands against another's will. 

| Level | Name                   | AP | Distance       | Ob                             | Effect(s)                      | Backfire Effect(s) |
| ----- | ---------------------- | -- | -------------- | ------------------------------ | ------------------------------ | ------------------ |
| 0     | Wordless Communication | 2  | `SI * 4`       | `SI`                           | **Concentration**: Communicate wordlessly with `SI` MST. Language barriers do not apply to this form of communication. |  |
| 0     | Read Thoughts          | 2  | `SI * 4`       | Opposed by `Self-Control - SI` | Glimpse into the thoughts of ST for a short time. | The ST instead catches a glimpse into *your* thoughts. |
| 2     | Change a Mind          | 2  | `SI * 4`       | Opposed by `Self-Control - SI` | Alter a creature's current state of mind and emotion. | You are affected, instead. |
| 3     | Pressing Thought       | 2  | `SI * 10`      | `SI + 1`                       | **Concentration**: [Hasten](./strive-core.md#hasted) up to `SI` MST of choice. | You and your targets suffer `+1` [Strain](./strive-core.md#stamina--strain). |
| 4     | Quiet Command          | 2  | `SI * 10`      | Opposed by `Self-Control - SI` | Issue a command to another creature, which they feel **strongly** compelled to follow. | `+1` [Strain](./strive-core.md#stamina--strain) to self. |

**Rituals**

| Level | Name                 | Time Increment | Ob          | Ritualists | Effect(s)                      | Side-Effect(s)     | Backfire Effect(s) |
| ----- | -------------------- | -------------- | ----------- | ---------- | ------------------------------ | ------------------ | ------------------ |
| 5     | Confer Knowledge     | 1 Hour         | `6 - SI`    | 1 - 1      | Permanently confer `+1` Level of a Known Skill to a ST, but only up to your Level, minus two, in the Skill. Also, this costs **you** `-10` XP. Your Level in the Skill is unaffected. This can only be done once a day, to let the mind of the ST process its unnaturally gained knowledge. | You temporarily lose a Level in the Skill, for `1` day. | You permanently lose a Level in the Skill! |

## List of Illnesses
This list supplements the list of Injuries of the [Core rules](./strive-core.md#list-of-injuries). 

| Name              | Duration          | Effect      | Treatment |
| ----------------- | ----------------- | ----------- | --------- |
| Amber Curse       | `2D10` Days     | The victim finds it difficult to feel the flow of magic through their body. `-1D4` [Arcana](#arcana-arc); `-1D4` to any magic Skills and [Rune-Using](#rune-using-agiwit). | Conventional methods cannot treat this Illness. It can be treated with a potion of powdered [Abyssalite](#abyssalite). |

## List of Character Traits
The following is a list of all [Character Traits](#character-traits) of this Module.  See also the [Core Character Traits](./strive-core.md#list-of-character-traits).

### Anti-Mage
You are entirely incapable of Magic, to the point that the Arcanosphere slows around you. Your [Arcana](#arcana-arc) Attribute can never be above Level `0`. All Magic used against you loses `-1` [SI](#spell-intensity-si) **or** deals `-5` points of damage less - *you choose*.

### Armored Confidence
When wearing heavy armor, your confidence in it allows you to [Counter-Attack](./strive-core.md#counter-attack) whenever you are hit, at the cost of `-1` [Stamina](./strive-core.md#stamina--strain).

### Breath Weapon
Obvious jokes aside, your breath can deal some tangible damage. `1D8 + 2` of either Acid, Burning, Freezing or Poison damage (choose one when receiving the Trait). This costs `-1` AP and `-1` [Stamina](./strive-core.md#stamina--strain) and launches a ranged attack in an AoE cone with a distance of `3` Squares. Can only be used once per Turn. 

### Hot-Head
When in the [Consuming Arcane Overheat](#arcane-overheat--slag) threshold, suffer `-5` points of damage (minimum `0`) from it.

### Hyperattentive
Can [Concentrate](./strive-core.md#concentration) on `+1` spell.

### Radiator
Whenever your Arcane Slag is reduced, it is reduced by `+1` more.

### Tempered
Your [Arcane Overheat](#arcane-overheat--slag) thresholds are calculated as if your Arcana was `+1` Level higher.

## Archetype Characters
This section contains some pre-defined archetypal Characters. These are mostly ready to play and serve as instructional references on how to build your own Characters. 

Their name, species, gender, age and other details are left up to you to fill out, with the help of your GM, as such details must fit their world and cannot be predicted here. Also, the initial drivers are designed to get these Characters to come together and co-operate. There is no point in playing lone wolves. You are very much expected to replace the drivers and come up with your own after the first session of play. 

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

| BI     | Sprint | Stabil | HP  | Stamina    |
| ------ | ------ | ------ | --- | ---------- |
| 7      | 1      | 0      | 20  | 2          |

Titles of Renown:
* Loremaster of *X* (`3`) - at the cost of `2` points that would have gone to Skills. Replace *X* with something befitting your GM's world - make sure to consult them!

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

| BI     | Sprint | Stabil | HP  | Stamina    |
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
1. I will travel the world and seek out the most renowned medics and surgeons, to convince them to join my hospital. 
2. I will find a group of foolhardy adventurers to travel with, as I will need protection and coin. And to keep honing my art. 
3. A hospital is expensive - I will convince someone influential and wealthy to fund my hospital for me. 

Reactions:
1. Troublemaker: If someone is in need, I will always help. Afterwards I may still ask to be paid, though.
2. Troublemaker: If someone else tries to treat Injuries, I will always push them aside and take over. Can't have the laity play doctor!
3. Troublemaker: I **do not kill** people. I *may* hurt them, though.

| Agi (Core)   | Awar         | Str          | Tough        | Wit          | Arc          |
| ------------ | ------------ | ------------ | ------------ | ------------ | ------------ |
| 4            | 1            | 2            | 2            | 4            | 0            |

| BI     | Sprint | Stabil | HP  | Stamina    |
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

| BI     | Sprint | Stabil | HP  | Stamina    |
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
2. Assurance: Many negotiations in the past have taught me valuable appraisal skills. I can always tell if *something seems off* in an offered deal. 
3. Troublemaker/Assurance: You never know where the enemy lurks. I always have a weapon and my armor ready. 

| Agi          | Awar         | Str          | Tough        | Wit (Core)   | Arc          |
| ------------ | ------------ | ------------ | ------------ | ------------ | ------------ |
| 2            | 1            | 2            | 4            | 4            | 0            |

| BI     | Sprint | Stabil | HP  | Stamina    |
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
This and the following sections are reserved solely for the GM's eyes. Reading on as a player may spoil many surprises and the fun of discovery for you. 

# Creature Compendium
A by no means exhaustive list of medieval-fantasy themed creatures for the GM to draw from. 

In the Characteristics blocks below, when armor is concerned, it may be noted in the form `U/F/S/O`, which are simply the pre-calculated values the armor provides under consideration of the degrees of [Flanking](./strive-core.md#flanking). The order is always: Unthreatened, Flanked, Surrounded and Overwhelmed. However, armor may also be noted as a plain value, e. g. `5`, which implies the creature does not suffer [Flanking](./strive-core.md#flanking).

## Cursed
Beings that suffer some terrible curse, both reversible and irreversible. 

### Werewolf
Whether through the bite, or blood, a Werewolf's curse transforms its victim into a horribly twisted fusion of man and beast, driven by endless hunger. 

* Power: Legendary, CR: `20`
* Roles: Ambusher, Brawler, Shock-Trooper
  * An extremely dificult to hit, mobile brawler that benefits from moon lit battlefields. 
* Behavior: 
  * Constantly stalks the land in search of prey. 

| Agi   | Awar  | Str   | Tough | Wit   | Arc   |
| ----- | ----- | ----- | ----- | ----- | ----- |
| 6     | 4     | 6     | 3     | 3     | 3     |

| BI     | Sprint | Stabil | HP  | Stamina    | FS (Ranged `10`)| Def    | Armor             |
| ------ | ------ | ------ | --- | ---------- | --------------- | ------ | ----------------- |
| 13     | 4      | 0      | 30  | 6          | 7 Slashing      | 5D     |                   |

**Traits**:
* [Fast](./strive-core.md#fast--2-points-1-cr)
* [Fortified Mind](./strive-core.md#fortified-mind--4-points-1-cr)
* [Hyperactive + Multi-Initiative](./strive-core.md#hyperactive--7-points-4-cr)
* [Gritty](./strive-core.md#gritty--5-points-4-cr)
* [Moon Affinity](./strive-core.md#moon-affinity--7-points-4-cr);

**Assets**: None

**Skills**:
* Acrobatics (Agi/Str): Level `5`
* Bite (Agi/Str): 
  * Bite down hard at a ST with strong and sharp teeth. 
  * Level: `4`, AP: `2`, Ob: Opposed, Melee, ST, Innate
  * `≤ 1` Hit: `6` Piercing
  * `= 2` Hits: `8` Piercing
  * `≥ 3` Hits: `10` Piercing
* Rend (Agi/Str): 
  * Strike at a ST with sharp claws. 
  * Level: `5`, AP: `2`, Ob: Opposed, Melee, ST, Innate
  * `≤ 1` Hit: `7` Slashing
  * `= 2` Hits: `9` Slashing; `+1` Bleeding
  * `≥ 3` Hits: `11` Slashing; `+2` Bleeding
* Shoot Spine (Agi/Awar): 
  * Shoot a spine from your back at a ST, up to `10` Squares away. 
  * Level: `4`, AP: `2`, Ob: `Opposed`, Ranged, ST, Innate
  * `≤ 1` Hit: `4` Piercing
  * `= 2` Hits: `5` Piercing
  * `≥ 3` Hits: `6` Piercing

## Corruptions
Wherever powerful magic is cast, the Arcanosphere is disturbed, its winds accelerated unnaturally. If the torrents become too great, they begin warping reality unpredictably. Things caught in the storm become affected. If exposure is too long, they morph and transform into Corruption monsters - nightmarish things that don't follow the rules of this reality. While some of these abominations may be relatively feeble, others would challenge armies. 

### Hunched Dread
Warped bones are held together by sinew and parched remnants of skin. The heavily hunched creature moves with uncanny precision, although the tangle of malformed extremities forbid any elegance. The skull is laid bare, tentacle-esque boney protrusions dangle and deviously curl from it. Although it lacks eyes, its gaze is straight and filled with dark intent. 

* Power: Elite, CR: `10`
* Roles: Ambusher, Disruptor
  * A tricky and annoying foe, that will kidnap victims and drag them off to dark places, where it cages them, left to rot. 
* Behavior: 
  * Stalking the darkness, or waiting patiently for victims to draw near. 
  * Will attempt to drag off a single victim and then erect a Twisted Cage around them. 
  * If surrounded by foes, tries to Twisted Cage as many of them as possible, before attempting a daring escape. 
  * Prefers to stay on the move. Doesn't stand around idly when in combat. 

| Agi   | Awar  | Str   | Tough | Wit   | Arc   |
| ----- | ----- | ----- | ----- | ----- | ----- |
| 6     | 3     | 6     | 3     | 3     | 5     |

| BI     | Sprint | Stabil | HP  | Stamina    | FS              | Def    | Armor             |
| ------ | ------ | ------ | --- | ---------- | --------------- | ------ | ----------------- |
| 12     | 6      | 0      | 30  | 6          |                 | 3D     |                   |

**Traits**:
* [Fast](./strive-core.md#fast--2-points-1-cr)
* [Fortified Mind](./strive-core.md#fortified-mind--4-points-1-cr)
* [Climber + Sticky](./strive-core.md#climber--2-points-1-cr)

**Assets**: None

**Skills**:
* Kidnap (Agi/Str): 
  * Envelop a ST and drag them off. The victim counts as [Grappled](./strive-core.md#grappled). 
  * Level: `5`, AP: `2`, Ob: Opposed, Melee, ST, Innate
* Twisted Cage (Arc/Arc): 
  * Form a cage of twisted earth and bone around a ST, up to `10` Squares away, who is considered [Rooted](./strive-core.md#rooted) and due to the constricted space, suffers `+1` Ob to all Tests.
  * Level: `5`, AP: `2`, Ranged, ST, Innate

### Huskfallen
Muscle and bone are laid bare and mutated, as the monster's skin is akin to a tree's bark. It is heavily hunched over and low to the ground. Its double-jointed arms jut out above the shoulders and at the ends of its overgrown hands bony claws curve outward like daggers. 

* Power: Feeble, CR: `6`
* Roles: Tank
  * On its own, barely a challenge. Employ it with more of its kind as a mobile meat shield for higher value targets. 
  * Will also grapple enemies, keeping them in place and an easier target for its larger allies. 
* Behavior: 
  * Often accompanies greater Corruption monsters, like an escort. 

| Agi   | Awar  | Str   | Tough | Wit   | Arc   |
| ----- | ----- | ----- | ----- | ----- | ----- |
| 2     | 2     | 3     | 3     | 2     | 5     |

| BI     | Sprint | Stabil | HP  | Stamina    | FS (Melee)      | Def    | Armor             |
| ------ | ------ | ------ | --- | ---------- | --------------- | ------ | ----------------- |
| 6      | 3      | 0      | 30  | 6          | `4` Slashing    |        |                   |

**Traits**: None

**Assets**: None

**Skills**:
* Rend (Agi/Str): 
  * Tear a ST to shreds with your claws. 
  * Level: `3`, AP: `2`, Ob: Opposed, Melee, ST, Innate
  * `≤ 1` Hit: `3` Slashing
  * `= 2` Hits: `4` Slashing
  * `≥ 3` Hits: `5` Slashing
* Grapple (Agi/Str): 
  * Grapple a ST. Gain `+1` Compensation Point for Grapple Tests.
  * Level: `3`, AP: `2`, Ob: Opposed, Melee, ST, Innate

### Tentacled Tarbeast
A massive, bipedal abomination. Its thin limbs are too long for its proportions, feet and hands larger than they should be and always with at least a slight bend, like the creature simply cannot straighten itself. Nasty crooked claws tip the ends of its elongated fingers. The upper body is one amorphous shape, housing multiple eyes randomly breaking through the skin. Multiple tentacles curve from its hunched back, writhing like seaweed. Its skin is a matte purple and amorphous, like the ripples in the surface of a lake, always moving.

* Power: Legendary, CR: `20`
* Roles: Shock-Trooper, Tank
  * A considerable challenge and a **deadly** foe, that will Spew Taint to create more of its wicked kind. 
* Behavior: 
  * Roams the more heavily corrupted regions of the world, where the Arcanosphere's torrents are rampant. 

| Agi   | Awar  | Str   | Tough | Wit   | Arc   |
| ----- | ----- | ----- | ----- | ----- | ----- |
| 5     | 3     | 6     | 10    | 2     | 5     |

| BI     | Sprint | Stabil | HP  | Stamina    | FS (Melee)      | Def    | Armor             |
| ------ | ------ | ------ | --- | ---------- | --------------- | ------ | ----------------- |
| 10     | 7      | 3      | 100 | 20         | `10` Slashing   | 3D     |                   |

**Traits**:
* [The Flesh is Malleable](#the-flesh-is-malleable)
* [Fortified Mind](./strive-core.md#fortified-mind--4-points-1-cr)
* [Hyperactive + Multi-Initiative](./strive-core.md#hyperactive--7-points-4-cr)

**Assets**: None

**Skills**:
* Rend (Str/Tough): 
  * Tear a ST to shreds with your claws. Cannot be used against a target you're currently Grappling. 
  * Level: `5`, AP: `2`, Ob: Opposed, Melee, ST, Innate
  * `≤ 1` Hit: `8` Slashing
  * `= 2` Hits: `10` Slashing; `+1` Bleeding
  * `≥ 3` Hits: `13` Slashing; `+1` Bleeding
* Spew Taint (Arc/Arc): 
  * Spew the Taint at a victim, up to `5` Squares away, causing `+1` [Corruption](#corruption) in the victim.
  * Level: `4`, AP: `2`, Ob: Opposed, Ranged, ST, Innate
* Tentacles (Agi/Str): 
  * Crushing Squeeze:
    * Once per Turn, squeeze the life out of a currently Grappled ST victim, causing `8` Bludgeoning damage. 
    * Level: `4`, AP: ` 1`, ST, Innate
  * Grapple:
    * Grapple a ST with your tentacles, up to `3` Squares away. 
    * Level: `4`, AP: ` 1`, Opposed, ST, Innate

#### The Flesh is Malleable
Upon the start of your turn, regain `6` HP and remove one Injury!

**Legendary Actions**:
* Transform The Flesh:
  * Once per Round, remove all currently active Conditions and heal `2` HP for each. 
* Split:
  * Once a day, upon reaching half HP, split and duplicate yourself. Each half now has `50` current and maximum HP, but also half Toughness and `4` Strength. 

### Threaded Terror
Stilted legs hold aloft a large body comprised of tendrils pulsating with light. Its abstract form is vaguely humanoid, though it lacks any natural features. The air around it crackles with energy. 

* Power: Elite, CR: `10`
* Roles: Disruptor
  * A considerable challenge that turns foes against their former allies. May prove deadly to singular enemies who have no allies to bust them out of trouble. 
* Behavior: 
  * Roams the more heavily corrupted regions of the world, where the Arcanosphere's torrents are rampant. 

| Agi   | Awar  | Str   | Tough | Wit   | Arc   |
| ----- | ----- | ----- | ----- | ----- | ----- |
| 4     | 2     | 1     | 2     | 3     | 5     |

| BI     | Sprint | Stabil | HP  | Stamina    | FS              | Def    | Armor             |
| ------ | ------ | ------ | --- | ---------- | --------------- | ------ | ----------------- |
| 9      | 3      | 0      | 20  | 20         |                 | 2D     |                   |

**Traits**:
* [Fortified Mind](./strive-core.md#fortified-mind--4-points-1-cr)

**Assets**: None

**Skills**:
* Puppeteer (Agi/Arc): 
  * Jam your flesh tendrils in a victim's skin, taking control of them, up to `5` Squares away, with `+1` Compensation Point for the Test. If successful, the victim is under your direct control and cannot move on their own, although they may still think and speak of their own volition. The victim may attempt to break free from your control at the end of your Turn, with a successful Self-Control Test, at Ob `4`. An ally may attempt to sever the tendrils or pull loose their ally, with a Test at Ob `3`. 
  * For as long as a victim is Puppeteered, it will suffer all damage directed towards the Threaded Terror, who suffers no damage. 
  * Level: `5`, AP: `2`, Ob: Opposed, Ranged, ST, Innate
* Zap (Agi/Arc): 
  * Send a bolt of lightning from your tendrils to a ST victim, up to `5` Squares away.
  * Level: `5`, AP: `2`, Ob: Opposed, Ranged, ST, Innate
  * `≤ 1` Hit: `6` Electrical
  * `= 2` Hits: `8` Electrical
  * `≥ 3` Hits: `10` Electrical

### Time-Eater
A massive, monstrous mass of bare flesh and bone. Its skin is like fish's mail, made of screaming eyeless faces, forever contorted in horror. Reality warps oddly around it, like around a black hole, but with it remaining clearly visible at the center. 

* Power: Legendary, CR: `30`
* Roles: Disruptor, Multiplier, Tank
  * A legendary foe that warps reality around it, displacing foes and creating more of its kind. 
  * This thing could easily rival the greatest of Demons without breaking a sweat. It cannot sweat. 
* Behavior: 
  * Roams the most heavily corrupted regions of the world, where the Arcanosphere's torrents are cataclysmic. 
  * Uses "Corrupt Reality" when enemies come within `5` Squares of it. 
  * Uses "I Remember..." whenever possible, but no more than twice in a Turn. 

| Agi   | Awar  | Str   | Tough | Wit   | Arc   |
| ----- | ----- | ----- | ----- | ----- | ----- |
| 2     | 2     | 10    | 20    | 4     | 7     |

| BI     | Sprint | Stabil | HP  | Stamina    | FS (Melee)      | Def    | Armor             |
| ------ | ------ | ------ | --- | ---------- | --------------- | ------ | ----------------- |
| 7      | 0      | 0      | 200 | 40         |                 | 2D     |                   |

**Traits**:
* [Fortified Mind](./strive-core.md#fortified-mind--4-points-1-cr)
* [Shambler](./strive-core.md#shambler-2-points--2-cr)

**Assets**: None

**Skills**:
* I Remember... (Arc/Arc): 
  * Level: `6`, AP: `2`, ST, Innate
  * Roll `1D6`, on `1`: We Were More, `2`: You Were Not There, `3`: You Were Weaker, `4`: A Cage, `5`: You Were Slower, `6`: Being Alive
  * We Were More:
    * `1D4`, Spawn up to... 1: `5` [Huskfallen](#huskfallen), 2: `3` [Hunched Dread](#hunched-dread), 3: `2` [Threaded Terror](#threaded-terror), 4: `1` [Tentacled Tarbeast](#tentacled-tarbeast)
    * Only fills up the numbers of allies, but does not exceed them. For example, through this Ability, no more than `5` Huskfallen can exist at a time. 
  * You Were Not There:
    * Displace up to `3` foes randomly (see [Random Direction](./strive-core.md#random-direction)), up to `6` Squares far.
  * You Were Weaker:
    * Inflict a Bleeding Injury to `3` foes. 
  * A Cage:
    * Cages of bone form around `3` foes, [Rooting](./strive-core.md#rooted) them. Each cage has `10` HP and lasts `3` Rounds. 
  * You Were Slower:
    * An area, `10` Squares in diameter slows all within. Every Action taken within costs `+1` AP and movement is reduced by `2` Squares. 
  * Being Alive:
    * The sky darkens and it rains all Round. *Please, make it end*. 
* Corrupt Reality (Arc/Arc): 
  * A shockwave sends tremors through reality. All in a `20` Square diameter around are affected. Chunks of earth begin to float and warp. The battlefield changes its visage, bending around the Time-Eater. 
  * Level: `5`, AP: `4`, Ob: `2`, Ranged, AoE, Innate
  * `≤ 1` Hit: `6` Pure; `+1` [Corruption](#corruption); Knock-back `3` Squares
  * `= 2` Hits: `8` Pure; `+1` [Corruption](#corruption); Knock-back `4` Squares
  * `≥ 3` Hits: `10` Pure; `+1` [Corruption](#corruption); Knock-back `5` Squares

**Legendary Actions**:
* Bend Light:
  * Cause one ability that targets you to be re-directed to another Character, closest to you, picked on [random direction](./strive-core.md#random-direction). 

## Demons
Beings from a hostile world that exists in parallel to our own, Demons are as vile and cruel as their home. These are some of the worst monsters any adventurer may have to face and represent an end-game level threat. 

Thankfully, these horrid creatures cannot pass into our world easily. They require assistance to this end - [Demonologists](#demonology-arcwit) may summon them, or wherever violent storms of the Arcanosphere grow too fierce, enough magical potential may tear rifts into our existence, allowing all manner of unspeakable horror to pass through.

All Demons are of an Arcane nature and possess powers foreign to this world. 

### Demon Hostility
[Dominated](#demonology-arcwit) Demons do not have access to Hostility!

#### Consuming Rage
**`-5` Hostility**: The Demon begins to burn with unconsolable hatred. Its body is covered in unnatural flame that deals `3` Burning damage to all creatures adjacent to it. However, the Demon *also* suffers the damage every Turn. 

#### Molten Envy
**`-15` Hostility**: All who fail a Self-Control Ob `2` Test in a `5` Square radius around the Demon are struck with a fierce and terrible jealousy. They *alone* are meant to fight and prevail against this foe and will refuse any and all aid and also refuse to assist others!

### Major Demon Hostility
All major Demons have access to the following Hostility Actions. Theirs is a terrible power.

#### Hell On Earth
**`-20` Hostility**: The Demon stops and slams into the ground, flames dancing from its body, before the floor beneath it erupts with jets of flame. The environment, in a `20` Square AoE diameter, turns into a Demonic hell pit! The effect lasts `4` Rounds.

All non-Demonic creatures are set on fire and suffer `4` Burning damage every Turn! 

#### Darkness Is Coming!
**`-20` Hostility**: An unnatural darkness creeps from the Demon, enshrouding all in a `20` Square AoE diameter around it! Seeing in this blackness is impossible and all Tests that rely on sight are `+2` Ob harder to succeed! However, the Demon's eyes glow in the dark, like a sinister beacon. Though its form is hidden in the darkness, its location is always plain to see, as if it wanted its victims to know. The effect lasts `4` Rounds.

#### Drown In Grief!
**`-20` Hostility**: The environment deforms and grows limbs that grasp blindly, faces contorted in fear and pain and toothy mouths that clatter hungrily, in a `20` Square AoE diameter around the Demon. All terrain is considered Difficult Terrain and anyone who stands still, will be grabbed by the wayward limbs and thus [Rooted](./strive-core.md#rooted), until they free themselves at the cost of `2` AP. At the start of their Turn, when a creature is Rooted by the limbs, they will drag the creature down, making them [Prone](./strive-core.md#prone) and strangling them, for `5` Bludgeoning damage. 

### Lesser Demons

#### Lesser Demon of Hatred
This minor Demon is a horned mass of bulging muscle and covered in eternal flame. It is bipedal, with large claws and obsidian, scaly skin.

* Power: Elite, CR: `20`
* Summoning Ob: `4`, Requirements: [Murky Malevite Orb](#malevite) or greater
* Roles: Brawler, Shock-Trooper, Tank
  * Lesser Demons of Hatred often accompany or are summoned by a loose Greater Demon of Hatred.
  * These lesser demons have great staying-power and single-target damage. 
* Behavior: 
  * Like all Demons, it is bent on the destruction of everything around it. Its hate is pure and inconsolable. 

| Agi   | Awar  | Str   | Tough | Wit   | Arc   |
| ----- | ----- | ----- | ----- | ----- | ----- |
| 3     | 3     | 6     | 6     | 2     | 8     |

| BI     | Sprint | Stabil | HP  | Stamina    | FS (Melee)             | Def    | Armor             |
| ------ | ------ | ------ | --- | ---------- | ---------------------- | ------ | ----------------- |
| 8      | 5      | 3      | 60  | 12         | 5 Slashing + 3 Burning | 1      | Burning Immune <br> Double damage from Freezing <br> 8/4/2/0 Slashing <br> 6/3/2/0 Piercing <br> 4/2/1/0 Bludgeoning <br> 4/2/1/0 Acid |

**Traits**:
* [Fortified Mind](./strive-core.md#fortified-mind--4-points-1-cr)
* [Leaper](./strive-core.md#leaper--3-points-2-cr)

**Assets**: None

**Skills**:
* Breath Of Fire (Tough/Arc):
  * Breathe flame in a `3` Square AoE cone. 
  * Level: `4`, AP: `3`, Ob: `2`, AoE, Innate
  * `≤ 1` Hit: `4` Burning
  * `= 2` Hits: `6` Burning
  * `≥ 3` Hits: `9` Burning
* Charge (Str/Tough):
  * Charge at a ST, knocking them back and engulfing them in flame.
  * Level: `5`, AP: `3`, Ob: `Opposed`, Melee, ST, Innate
  * `≤ 1` Hit: `5` Bludgeoning + `5` Burning; Knocked back `2` Squares
  * `= 2` Hits: `6` Bludgeoning + `6` Burning; Knocked back `3` Squares
  * `≥ 3` Hits: `8` Bludgeoning + `8` Burning; Knocked back `5` Squares
* Claw Strike (Agi/Str):
  * Strike with burning claws at a ST.
  * Level: `5`, AP: `3`, Ob: `Opposed`, Melee, ST, Innate
  * `≤ 1` Hit: `8` Slashing + `6` Burning
  * `= 2` Hits: `10` Slashing + `8` Burning
  * `≥ 3` Hits: `13` Slashing + `10` Burning

#### Dread Guard
This minor Demon towers above and punishes foes with reckless abandon. One of its bony arms morphs into a shield of bone, the other into a wicked blade.

* Power: Regular, CR: `10`
* Summoning Ob: `3`, Requirements: `3` Bulk worth of [Abyssalite](#abyssalite)
* Roles: Shock-Trooper, Tank
  * Capable of defending itself with its bone shield, it retaliates against any and all foes who attempt to strike it, with astonishing force.
  * When hurt, its blood will harm its attacker.
  * Even when defeated, this Demon's Death Rattle lets them remain a threat, one final time. 
* Behavior: 
  * Like all Demons, it is bent on the destruction of everything around it. Its hate is pure and irredeemable. 

| Agi   | Awar  | Str   | Tough | Wit   | Arc   |
| ----- | ----- | ----- | ----- | ----- | ----- |
| 3     | 3     | 5     | 5     | 2     | 5     |

| BI     | Sprint | Stabil | HP  | Stamina    | FS (Melee)      | Def    | Armor             |
| ------ | ------ | ------ | --- | ---------- | --------------- | ------ | ----------------- |
| 8      | 4      | 3      | 50  | 10         | 5 Slashing      | 3      | 0                 |

**Traits**:
* [Fortified Mind](./strive-core.md#fortified-mind--4-points-1-cr)
* [Danger Blood (1D6 Burning)](./strive-core.md#danger-blood--1-point-1-cr)
* [Death Rattle (Reprisal)](./strive-core.md#death-rattle--2-points-2-cr)

**Assets**: None

**Skills**:
* Wicked Blade Strike (Agi/Str):
  * Strike at a ST with your blade-like arm.
  * Level: `4`, AP: `2`, Ob: `Opposed`, Melee, ST, Innate
  * `≤ 1` Hit: `3` Slashing
  * `= 2` Hits: `4` Slashing
  * `≥ 3` Hits: `5` Slashing
* Retaliate:
  * **Reaction**: When being attacked, immediately launch a free Counter-Attack with your Wicked Blade Strike. But in doing so, allow one *other* Character than the one you're retaliating against to *also* launch a free and immediate Counter-Attack against *you*! You cannot Retaliate against that other Character - the chain of Counter-Attacks ends with them. 
* Vomit Blood (Agi/Tough):
  * Cough up a blast of your own blood, its Demonic fire will burn all in a `3` Square AoE cone.
  * Level: `3`, AP: `3`, Ob: `1`, Ranged, AoE, Innate
  * `≤ 1` Hit: `2` Burning
  * `= 2` Hits: `3` Burning
  * `≥ 3` Hits: `4` Burning

#### Faceless Hunter
This minor Demon looks like a pale, muscular man, but its head is elongated and lacks any facial features, save a teeth-lined maw and reptilian nostrils. Each hand holds a rusty sickle and trophies taken from its victims adorn its body. When it moves, it does so like a beast, rather than a man. 

* Power: Regular, CR: `12`
* Summoning Ob: `3`, Requirements: `8` Bulk worth of [Abyssalite](#abyssalite)
* Roles: Ambusher, Sentry, Shock-Trooper, Disruptor
  * Though blind, it has excellent senses of smell and hearing. Avoiding it will require clever maneuvering. 
  * Its ability to hide makes it a dangerous foe to be surprised by. 
  * It is very agile and fast, can jump over foes and damage them, Leg Sweep them or Drop Kick them. 
* Behavior: 
  * Like all Demons, it is bent on the destruction of everything around it. Its hate is pure and irredeemable. 

| Agi   | Awar  | Str   | Tough | Wit   | Arc   |
| ----- | ----- | ----- | ----- | ----- | ----- |
| 6     | 6     | 4     | 4     | 3     | 5     |

| BI     | Sprint | Stabil | HP  | Stamina    | FS (Melee)      | Def    | Armor             |
| ------ | ------ | ------ | --- | ---------- | --------------- | ------ | ----------------- |
| 15     | 5      | 0      | 40  | 8          | 6 Slashing      | 3      | 0                 |

**Traits**:
* [Fortified Mind](./strive-core.md#fortified-mind--4-points-1-cr)
* [Fast (+2)](./strive-core.md#fast--2-points-1-cr)
* [Hyperactive + Multi-Initiative](./strive-core.md#hyperactive--7-points-4-cr)
* [Leaper + Dervish](./strive-core.md#leaper--3-points-2-cr)

**Assets**: It may have the odd trinket - still attached to the remains of its former host. 

**Skills**:
* Observation, Level `5`
* Stealth, Level `5`
* Drop Kick (Agi/Tough):
  * Jump into a ST, up to `3` Squares far, and knock them `Str` Squares away from you.
  * Level: `4`, AP: `3`, Ob: `Opposed`, Melee, AoE, Innate
* Leg Sweep (Agi/Str):
  * Sweep the legs of two adjacent creatures, knocking them [Prone](./strive-core.md#prone). 
  * Level: `4`, AP: `2`, Ob: `Opposed`, Melee, AoE, Innate
* Sickle Strike (Agi/Agi):
  * Strike at a ST with your sickles.
  * Level: `4`, AP: `2`, Ob: `Opposed`, Melee, ST, Innate
  * `≤ 1` Hit: `3` Slashing
  * `= 2` Hits: `4` Slashing; `+1` [Bleeding](./strive-core.md#bleeding)
  * `≥ 3` Hits: `5` Slashing; `+2` [Bleeding](./strive-core.md#bleeding)

#### Lesser Wendigo
This minor Demon appears like a half-rotted and calcified, large, bipedal Deer. Red eyes and vicious claws plainly demonstrate its rage-filled nature. 

* Power: Regular, CR: `10`
* Summoning Ob: `3`, Requirements: `6` Bulk worth of [Abyssalite](#abyssalite)
* Roles: Ambusher, Shock-Trooper
  * As it can jump through the shadows, this can be a very unpredictable and dangerous foe. In a moment, it can appear behind a victim and tear into them with its claws. 
* Behavior: 
  * Like all Demons, it is bent on the destruction of everything around it. Its hate is pure and inconsolable. 
  * This variant in particular stalks the shadows and prefers to strike from the deepest, darkest reaches of their environment. 

| Agi   | Awar  | Str   | Tough | Wit   | Arc   |
| ----- | ----- | ----- | ----- | ----- | ----- |
| 5     | 3     | 3     | 3     | 2     | 5     |

| BI     | Sprint | Stabil | HP  | Stamina    | FS (Melee)      | Def    | Armor             |
| ------ | ------ | ------ | --- | ---------- | --------------- | ------ | ----------------- |
| 10     | 4      | 0      | 30  | 6          | 5 Slashing      | 3      | 0                 |

**Traits**:
* [Fortified Mind](./strive-core.md#fortified-mind--4-points-1-cr)

**Assets**: None

**Skills**:
* Claw Strike (Agi/Str):
  * Strike at two adjacent MST with your claws.
  * Level: `4`, AP: `3`, Ob: `Opposed`, Melee, MST, Innate
  * `≤ 1` Hit: `4` Slashing
  * `= 2` Hits: `4` Slashing
  * `≥ 3` Hits: `5` Slashing
* Shadow-Jump:
  * Diffuse into a burst of darkness, and re-appear in anoter location, up to `10` Squares away.
  * AP: `1`, Innate
* Breath Of Death (Tough/Tough):
  * Breathe darkness in a `3` Square AoE cone. 
  * Level: `4`, AP: `3`, Ob: `2`, AoE, Innate
  * `≤ 1` Hit: `1` Pure
  * `= 2` Hits: `3` Pure; All victims whose Self-Control is `≤ 1` become Terrified of you! 
  * `≥ 3` Hits: `5` Pure; All victims whose Self-Control is `≤ 3` become Terrified of you! 

#### Possessed Zombie
This minor Demon has been forced into the body of a Zombie. It has deformed, as if multiple bodies were merged into one, with multiple heads growing out of each other and the torso, and multiple pairs of arms sticking out, grasping at nothing. 

* Power: Regular, CR: `8`
* Summoning Ob: `2`, Requirements: `3` Bulk worth of [Abyssalite](#abyssalite)
* Roles: Brawler, Multiplier
  * Stronger and more dangerous than a regular Zombie, with a few tricks to surprise foes with. 
* Behavior: 
  * Like all Demons, it is bent on the destruction of everything around it. Its hate is pure and inconsolable. 

| Agi   | Awar  | Str   | Tough | Wit   | Arc   |
| ----- | ----- | ----- | ----- | ----- | ----- |
| 2     | 3     | 6     | 5     | 2     | 5     |

| BI     | Sprint | Stabil | HP  | Stamina    | FS (Melee)      | Def    | Armor             |
| ------ | ------ | ------ | --- | ---------- | --------------- | ------ | ----------------- |
| 7      | 3      | 0      | 50  | 10         | 3 Bludgeoning   | 0      | 0                 |

**Traits**:
* [Fortified Mind](./strive-core.md#fortified-mind--4-points-1-cr)
* [Regenerator](./strive-core.md#regenerator--5-points-3-cr)
* [Death Rattle (Splitter)](./strive-core.md#death-rattle--2-points-2-cr)

**Assets**: None

**Skills**:
* Batter (Agi/Str):
  * Strike at two adjacent MST with your fists.
  * Level: `4`, AP: `3`, Ob: `Opposed`, Melee, MST, Innate
  * `≤ 1` Hit: `5` Bludgeoning
  * `= 2` Hits: `7` Bludgeoning
  * `≥ 3` Hits: `10` Bludgeoning
* Spew Acid (Agi/Awar): 
  * Spew acid in a `2` Square AoE cone.
  * Level: `3`, AP: `2`, Ob: `1`, AoE, Innate
  * `≤ 1` Hit: `4` Acid
  * `= 2` Hits: `6` Acid
  * `≥ 3` Hits: `9` Acid
* Moldy Breath (Awar/Tough): 
  * Cough a deathly mold in a `2` Square AoE cone.
  * Level: `3`, AP: `2`, Ob: `1`, AoE, Innate
  * `≤ 1` Hit: `4` Poison
  * `= 2` Hits: `6` Poison
  * `≥ 3` Hits: `9` Poison

**Legendary Actions**:
* Trample:
  Run up to `6` Squares far, knocking aside all other Characters by `1` Square, once per Round. 
* Rise Again:
  * Defy death once more, losing all Injuries and regaining all HP. Can only happen once. 
* Demon Freedom:
  * A [Spineling](#spineling) bursts forth, in a spectacular explosion of blood, acid and gore, dealing `6` Acid damage to all in a `5` Square diameter AoE around. The Possessed Zombie dies in the process. This can only happen once and only when below half HP. 

#### Spineling
This minor Demon is a canid-esque quadruped covered in countless bony spines, like a porcupine. It lacks fur, its skin is pallid and sunken, stretched taut across its bones. 

* Power: Regular, CR: `8`
* Summoning Ob: `2`, Requirements: `3` Bulk worth of [Abyssalite](#abyssalite)
* Roles: Artillery
  * A damage dealer that stays out of melee as best it can. Besides its ranged attack, it lacks any utility, but it is hard to hit and has great mobility as it can leap. 
* Behavior: 
  * Like all Demons, it is bent on the destruction of everything around it. Its hate is pure and inconsolable. 

| Agi   | Awar  | Str   | Tough | Wit   | Arc   |
| ----- | ----- | ----- | ----- | ----- | ----- |
| 6     | 4     | 2     | 3     | 2     | 5     |

| BI     | Sprint | Stabil | HP  | Stamina    | FS (Ranged `10`)| Def    | Armor             |
| ------ | ------ | ------ | --- | ---------- | --------------- | ------ | ----------------- |
| 12     | 4      | 0      | 30  | 6          | 4 Piercing      | 3      |                   |

**Traits**:
* [Fortified Mind](./strive-core.md#fortified-mind--4-points-1-cr)
* [Leaper](./strive-core.md#leaper--3-points-2-cr)

**Assets**: None

**Skills**:
* Shoot Spine (Agi/Awar): 
  * Shoot a spine from your back at a ST, up to `10` Squares away. 
  * AP: `2`, Ob: `Opposed`, Ranged, ST, Innate
  * `≤ 1` Hit: `4` Piercing
  * `= 2` Hits: `5` Piercing
  * `≥ 3` Hits: `6` Piercing

#### Taskmaster
This minor Demon appears to be some sort of stone-golem. Molten lava drips from the ridges and cracks in is limbs.

* Power: Regular, CR: `12`
* Summoning Ob: `3`, Requirements: `8` Bulk worth of [Abyssalite](#abyssalite)
* Roles: Commander, Supporter, Tank
  * Its commands are absolute and it *will* have dominion over all it can. 
  * Thanks to its stone-form it is naturally armored against all but Bludgeoning damage. It does not suffer Flanking. 
* Behavior: 
  * This peculiar variant seems more interested in dominating its foes, than destroying them. There is a strange, calculating cunning in its actions. 

| Agi   | Awar  | Str   | Tough | Wit   | Arc   |
| ----- | ----- | ----- | ----- | ----- | ----- |
| 2     | 3     | 3     | 4     | 5     | 5     |

| BI     | Sprint | Stabil | HP  | Stamina    | FS (Melee)      | Def    | Armor             |
| ------ | ------ | ------ | --- | ---------- | --------------- | ------ | ----------------- |
| 10     | 3      | 2      | 40  | 8          | 3 Bludgeoning   | 1      | 8 against all **except** Bludgeoning |

**Traits**: 
* [Fortified Mind](./strive-core.md#fortified-mind--4-points-1-cr)
* [Insurmountable](./strive-core.md#insurmountable--4-points-3-cr)

**Assets**: None

**Skills**:
* Obey! (Tough/Wit):
  * **Concentration**: Command any ST, up to `6` Squares away, to obey you! Their will is no longer their own. Commands are given telepathically, at the cost of `-1` AP. 
  * Level: `4`, AP: `3`, Ob: `Opposed by Self-Control`, Ranged, ST, Innate
* Serve Harder!: 
  * If dominating another creature's mind, bolster it, at the cost of its health.
  * AP: `3`, Ob: `1`, Ranged, ST, Innate
  * `≤ 1` Hit: Your servant must move towards a foe, up to `4` Squares far, which may provoke Opportunity Attacks, and also suffers `2` Pure damage.
  * `= 2` Hits: Your servant gets an immediate Turn, and must fulfill your command, but also suffers `5` Pure damage.
  * `≥ 3` Hits: Your servant gets an immediate Turn, with `+2` AP, and must fulfill your command, but also suffers `8` Pure damage.
* Whip Strike (Agi/Str):
  * Strike a ST, up to `3` Squares away, with your stone-whip. 
  * Level: `3`, AP: `2`, Ob: `Opposed`, Ranged, ST, Innate
  * `≤ 1` Hit: `2` Bludgeoning
  * `= 2` Hits: `4` Bludgeoning
  * `≥ 3` Hits: `6` Bludgeoning

### Greater Demons

#### Greater Demon Of Hatred
This major Demon is a horned hulking mass of bulging muscle and covered in eternal flame. It is bipedal, with large claws and obsidian, scaly skin.

* Power: Legendary, CR: `40`
  * Intended as a boss encounter, this creature has two phases. When its HP are depleted for the first time, it enters its second stage. In the second stage, it regains all HP, becomes enraged and starts burning up.
  * This legendary monster is an **end-game level threat** - unprepared PCs **will perish**. 
* Summoning Ob: `7`, Requirements: [Swirly Malevite Orb](#malevite) or greater
* Roles: Brawler, Disruptor, Tank
  * The Greater Demon Of Hatred is a legendary Demon. It does not yield and shows no quarter.
  * It is great at crowd control, and has several AoE damage abilities. 
* Behavior: 
  * Like all Demons, it is bent on the destruction of everything around it. Its hate is pure and inconsolable. 

| Agi   | Awar  | Str   | Tough | Wit   | Arc   |
| ----- | ----- | ----- | ----- | ----- | ----- |
| 3     | 3     | 8     | 10    | 2     | 8     |

**Assets**: None

##### First Stage
Flames dance across the Demon's obsidian skin and it roars with ferocity - yet also with restraint. 

| BI     | Sprint | Stabil | HP  | Stamina    | FS (Melee)                   | Def    | Armor             |
| ------ | ------ | ------ | --- | ---------- | ---------------------------- | ------ | ----------------- |
| 8      | 5      | 6      | 100 | 20         | 5 Slashing + 3 Burning (= 8) | 2D     | Burning Immune <br> -5 Freezing <br> 8 Slashing <br> 6 Piercing <br> 6 Bludgeoning <br> 6 Acid <br> 6 Bleeding |

**Traits**: [Fortified Mind](./strive-core.md#fortified-mind--4-points-1-cr); [Leaper](./strive-core.md#leaper--3-points-2-cr); [Danger Blood (Burning)](./strive-core.md#danger-blood--1-point-1-cr); [Hyperactive + Multi-Initiative](./strive-core.md#hyperactive--7-points-4-cr)

**Skills**:
* Breath Of Fire (Tough/Arc):
  * Breathe flame in a `5` Square AoE cone. 
  * Level: `8`, AP: `4`, Ob: `2`, AoE, Innate
  * `≤ 1` Hit: `8` Burning
  * `= 2` Hits: `9` Burning
  * `≥ 3` Hits: `10` Burning
* Claw Strike (Agi/Str):
  * Strike with fiery claws at everything in a `3` Square AoE cone.
  * Level: `8`, AP: `2`, Ob: `2`, Melee, AoE, Innate
  * `≤ 1` Hit: `10` Slashing + `4` Burning
  * `= 2` Hits: `13` Slashing + `5` Burning
  * `≥ 3` Hits: `18` Slashing + `6` Burning
* Fissure (Str/Arc):
  * Strike at the ground and cause molten earthen spikes to erupt in a straight AoE line, up to `8` Squares far, piercing foes and setting them on fire, before melting into harmless sludge. 
  * Level: `8`, AP: `4`, Ob: `2`, AoE, Innate
  * `≤ 1` Hit: `8` Piercing + `4` Burning
  * `= 2` Hits: `10` Piercing + `5` Burning
  * `≥ 3` Hits: `12` Piercing + `6` Burning
* Eruption (Tough/Arc):
  * Flames erupt from your body, pushing back all in a `10` Square diameter around you and leaving a flame field in a `10` Square diameter around, that last `3` Rounds. The flame field deals `6` Burning damage per Tick. 
  * Level: `6`, AP: `2`, Ob: `3`, AoE, Innate
  * `≤ 1` Hit: Knock-back `4` Squares; `4` Burning damage
  * `= 2` Hits: Knock-back `6` Squares; `6` Burning damage
  * `≥ 3` Hits: Knock-back `8` Squares; `9` Burning damage

**Legendary Actions**:
* Ignore Damage: 
  * Ignore an instance of damage, up to `2` times per Round. 
* Shrug It All Off:
  * If you have a combined total of at least `8` points of Health Conditions, remove all of them, once a day. 
* Action Surge
  * Gain `5` AP, once a day. 
* Building Hatred:
  * Whenever a PC successfully attacks you, regain `2` AP. 

##### Second Stage
The Demon's form vanishes in a sea of fire, which rages and roars with unbridled aggression, as if reaching for foes. At the start of every Round, it loses `5` HP.

| BI     | Sprint | Stabil | HP  | Stamina    | FS (Melee)                   | Def    | Armor             |
| ------ | ------ | ------ | --- | ---------- | ---------------------------- | ------ | ----------------- |
| 8      | 5      | 6      | 100 | 20         | 5 Slashing + 3 Burning (= 8) | 2D     | Burning Immune <br> 8 Slashing <br> 6 Piercing <br> 6 Bludgeoning <br> 6 Acid <br> 8 Bleeding |

**Traits**: 
* [Fortified Mind](./strive-core.md#fortified-mind--4-points-1-cr)
* [Leaper](./strive-core.md#leaper--3-points-2-cr)
* [Unstoppable Hatred](#unstoppable-hatred)

**Skills**:
* Breath Of Hate (Tough/Arc):
  * Breathe flame in a `8` Square AoE cone. 
  * Level: `8`, AP: `4`, Ob: `2`, AoE, Innate
  * `≤ 1` Hit: `6` Burning; Knock-back `2` Squares
  * `= 2` Hits: `8` Burning; Knock-back `3` Squares
  * `≥ 3` Hits: `10` Burning; Knock-back `4` Squares
* Claw Strike (Agi/Str):
  * Strike with red-hot claws at everything in a `3` Square AoE cone.
  * Level: `8`, AP: `2`, Ob: `2`, Melee, AoE, Innate
  * `≤ 1` Hit: `10` Slashing + `6` Burning; Knock-back `3` Squares
  * `= 2` Hits: `12` Slashing + `6` Burning; Knock-back `4` Squares
  * `≥ 3` Hits: `14` Slashing + `6` Burning; Knock-back `5` Squares
* Seek Revenge (Str/Arc):
  * **Reaction**: Upon suffering damage, leap to the ST foe who dealt it, and slam into them with both massive fists.
  * Level: `4`, AP: `1`, Ob: `Opposed`, Melee, ST, Innate
  * `≤ 1` Hit: `8` Bludgeoning + `6` Burning
  * `= 2` Hits: `10` Bludgeoning + `8` Burning
  * `≥ 3` Hits: `12` Bludgeoning + `10` Burning
* Flaming Whip (Tough/Arc):
  * Whip solid flame at a ST, up to `10` Squares away, and draw them closer.
  * Level: `6`, AP: `1`, Ob: `Opposed`, Ranged, ST, Innate
  * `≤ 1` Hit: Pull `6`; `4` Burning damage
  * `= 2` Hits: Pull `7`; `6` Burning damage
  * `≥ 3` Hits: Pull `8`; `9` Burning damage

**Legendary Actions**:
* Ignore Damage: 
  * Ignore an instance of damage, up to `2` times per Round. 
* Shrug It All Off:
  * If you have a combined total of at least `8` points of Health Conditions, remove all of them, once every other Round. 
* Stop Heroism
  * Prevent or end a Heroic Act's effects, once every other Round. 

###### Unstoppable Hatred
Nothing will stop the Demon's fire, and it *will* have ***revenge***. Every time it is attacked, it builds up `+1` **Rage**. 
* At `3` Rage, it may move freely, up to `4` Squares far, every time it is attacked, without provoking Opportunity Attacks. 
* At `5` Rage, it heals up to `30` HP and suffers `-1` of every negative Health Condition, every time one is suffered. 
* At `7` Rage, it may now launch a free Counter-Attack every time it is successfully attacked.
* At `9` Rage, it may now launch a free Counter-Attack every time it is attacked, regardless of the success of the attack.
* At `12` Rage, it may now move up to `8` Squares far, and launch a free Counter-Attack every time it is attacked, regardless of the success of the attack.

#### Greater Wendigo
This major Demon looks like a massive half-rotted and calcified, hunched bipedal Deer. Multiple pairs of red eyes and vicious claws twitch hungrily, as bony wings contrast the eerily majestic antlers.

* Power: Legendary, CR: `25`
* Summoning Ob: `5`, Requirements: [Swirly Malevite Orb](#malevite) or greater
* Roles: Ambusher, Shock-Trooper
  * The Greater Wendigo is a legendary Demon. It does not yield and shows no quarter.
  * As it can jump through the shadows, this can be a very unpredictable and dangerous foe. In a moment, it can appear behind a victim and tear into them with its claws. 
* Behavior: 
  * Like all Demons, it is bent on the destruction of everything around it. Its hate is pure and inconsolable. 

| Agi   | Awar  | Str   | Tough | Wit   | Arc   |
| ----- | ----- | ----- | ----- | ----- | ----- |
| 5     | 3     | 6     | 8     | 2     | 5     |

| BI     | Sprint | Stabil | HP  | Stamina    | FS (Melee)      | Def    | Armor             |
| ------ | ------ | ------ | --- | ---------- | --------------- | ------ | ----------------- |
| 10     | 6      | 3      | 80  | 16         | 5 Slashing      | 1      | 0                 |

**Traits**: 
* [Fortified Mind](./strive-core.md#fortified-mind--4-points-1-cr)
* [Glider](./strive-core.md#glider--1-points-1-cr)
* [Leaper](./strive-core.md#leaper--3-points-2-cr)
* [Danger Blood (1D6 Burning)](./strive-core.md#danger-blood--1-point-1-cr)
* [Forceful](./strive-core.md#forceful--2-points-1-cr)
* [Hyperactive + Multi-Initiative](./strive-core.md#hyperactive--7-points-4-cr)

**Assets**: None

**Skills**:
* Claw Strike (Agi/Str):
  * Strike at everything in a `3` Square AoE cone.
  * Level: `5`, AP: `3`, Ob: `2`, Melee, AoE, Innate
  * `≤ 1` Hit: `4` Slashing
  * `= 2` Hits: `5` Slashing
  * `≥ 3` Hits: `6` Slashing
* Breath Of Death (Tough/Tough):
  * Breathe darkness in a `5` Square AoE cone. 
  * Level: `5`, AP: `4`, Ob: `2`, AoE, Innate
  * `≤ 1` Hit: `3` Pure
  * `= 2` Hits: `4` Pure; All victims whose Self-Control is `≤ 2` become Terrified of you! 
  * `≥ 3` Hits: `6` Pure; All victims whose Self-Control is `≤ 3` become Terrified of you! 
* Draw Life (Arc/Arc):
  * With a terrible inverted howl, pull all in a `10` Square diameter AoE around you towards you by `5` Squares. You cannot suffer impact damage from this. 
  * Level: `5`, AP: `4`, Ob: `2`, AoE, Innate

**Legendary Actions**:
* Shadow-Jump: 
  * Diffuse into a burst of darkness, and re-appear in anoter location, up to `15` Squares away. Can be used to avoid damage, up to `2` times per Round.
* Create Thorns:
  * Once a Round, cover a `5` diameter AoE area in thorns that count as difficult terrain and cause `3` Piercing damage to all who move over it, once for each Square of movement. The Greater Wendigo is exempt from these penalties. The thorn fields last `3` Rounds. 
* Ignore Damage: 
  * Ignore an instance of damage, up to `2` times per Round. 

#### Greater Demon of Engorgement
This major Demon is a a quadrupedal mass of swollen flesh, with a massive and tooth-lined maw with an insatiable appetite for flesh. 

* Power: Legendary, CR: `30`
* Summoning Ob: `6`, Requirements: [Swirly Malevite Orb](#malevite) or greater
* Roles: Disruptor, Shock-Trooper, Tank
  * This is a legendary Demon that will inexorably devour anything it can get its grubby hands on. 
  * Its particular deviousness stems from the ability to scoff a single foe whole. 
  * Deadly Poison and Acid attacks.
* Behavior: 
  * Like all Demons, it is bent on the destruction of everything around it. Its hate is pure and inconsolable. 
  * Always in search of *more* food.
* Combat:
  * **Always** tries to Devour *someone*. Will stay close to foes. 
  * When surrounded, uses Release Noxious Fumes. Otherwise, will use Regurgitate and Chomp

| Agi   | Awar  | Str   | Tough | Wit   | Arc   |
| ----- | ----- | ----- | ----- | ----- | ----- |
| 3     | 3     | 8     | 10    | 3     | 6     |

| BI     | Sprint | Stabil | HP  | Stamina    | FS (Melee)      | Def    | Armor             |
| ------ | ------ | ------ | --- | ---------- | --------------- | ------ | ----------------- |
| 9      | 6      | 3      | 200 | 20         | 8 Piercing      | 2D     |                   |

**Traits**: 
* [Fortified Mind](./strive-core.md#fortified-mind--4-points-1-cr); 

**Assets**: None

**Skills**:
* Chomp:
  * Chomp down on up to `2` MST with your massive maw. 
  * Level: `5`, AP: `3`, Ob: `2`, AoE, Innate
  * `≤ 1` Hit: `5` Piercing
  * `= 2` Hits: `7` Piercing
  * `≥ 3` Hits: `9` Piercing
* Devour:
  * Devour a ST whole, for `2` Rounds. They suffer `6` Acid damage at the start of your Turn and are considered [Grappled](./strive-core.md#grappled), and untargetable. They cannot attack you from within, but can attempt to break free with an opposed Strength Test. 
  * AP: `2`, ST, Melee, Innate
* Release Noxious Fumes (Tough/Arc):
  * Some half-digested *food's* rotting remains within you are emanating a noxious fume. All in a `5` Square AoE radius around you are affected.
  * Level: `5`, AP: `3`, Ob: `2`, AoE, Innate
  * `≤ 1` Hit: `7` Poison; Knock-back `3` Squares
  * `= 2` Hits: `9` Poison; Knock-back `4` Squares
  * `≥ 3` Hits: `12` Poison; Knock-back `5` Squares
* Regurgitate (Awar/Tough):
  * Throw up some half-digested remains of some poor sap, up to `10` Squares far, where, in a `2` Square AoE radius, it causes damage. 
  * Level: `5`, AP: `2`, Ob: `2`, Ranged, AoE, Innate
  * `≤ 1` Hit: `6` Acid
  * `= 2` Hits: `8` Acid
  * `≥ 3` Hits: `10` Acid

**Legendary Actions**:
* Did I Eat That?:
  * Regurgitate `2` [Zombies](#zombie), who join the fight on your side. Can only have up to `4` Zombies on the field through this Ability. Can only be used every other Turn. 
* Do You Smell That?:
  * Interrupt a foe's Action, make them lose `1` AP and force them to run away from you, up to `4` Squares far. Can be used once per Round, at any time. 

**Hostility Actions**:
* [I don't Bleed](./strive-core.md#i-dont-bleed--5-points-6-cr)

#### Doom Bringer
This major Demon is a pale biped, without a head and many pairs of arms symmetrically sticking out of its body. When it unfolds the last arm, doom is upon us all. 

* Power: Legendary, CR: `30`
* Summoning Ob: `6`, Requirements: [Swirly Malevite Orb](#malevite) or greater
* Roles: Disruptor, Tank, Trapper
  * This is a legendary Demon that must be stopped before it can finish its Ritual. For if you don't, it will enact a terrible vengeance. This is essentially a timed encounter. If it is not stopped in time, it will cause great harm. 
  * It can Force-Move foes and litter the battlefield with hazards, which is a deadly combination. 
* Behavior: 
  * Like all Demons, it is bent on the destruction of everything around it. Its hate is pure and inconsolable. 
  * When not agitated, it always keeps its `12` pairs of arms folded. 
  * In Combat, prepares the battlefield with Prepare For Hell and when enemies get too close, uses Shake Ground to knock them away. Otherwise, always tries to use Count Down or Terrible Reprisal when it is available. 

| Agi   | Awar  | Str   | Tough | Wit   | Arc   |
| ----- | ----- | ----- | ----- | ----- | ----- |
| 2     | 2     | 6     | 10    | 2     | 6     |

| BI     | Sprint | Stabil | HP  | Stamina    | FS              | Def    | Armor             |
| ------ | ------ | ------ | --- | ---------- | --------------- | ------ | ----------------- |
| 6      | 6      | 3      | 100 | 20         |                 | 2D     | Half to all       |

**Traits**: 
* [Hyperactive + Multi-Initiative](./strive-core.md#hyperactive--7-points-4-cr)
* [Fortified Mind](./strive-core.md#fortified-mind--4-points-1-cr)
* [Shambler](./strive-core.md#shambler-2-points--2-cr)

**Assets**: None

**Skills**:
* Count Down:
  * Unfold one of your `12` pairs of arms. When all are unfolded, enact Terrible Reprisal.
  * AP: `3`, Innate
* Shake Ground (Arc/Arc):
  * Stomp the ground and make it tremble. All in a `10` Square radius around are knocked into a random direction. 
  * Level: `5`, AP: `4`, Ob: `2`, AoE, Innate
  * `≤ 1` Hit: Knock-back `3` Squares
  * `= 2` Hits: Knock-back `4` Squares
  * `≥ 3` Hits: Knock-back `5` Squares
* Prepare For Hell (Arc/Arc):
  * **Concentration**: Place up to `9` columns of flame, up to `20` Squares far away. Each is `1` Square wide, `6` Squares tall and will deal `8` Burning damage per Tick.
  * Level: `4`, AP: `3`, Innate
* Terrible Reprisal (Arc/Arc):
  * Another pair of unfolded hands claps together and remains so. The next time this ability is used, the next pair claps together. Each has a different and ever stronger effect. Once all hands have clapped, they fold again and the cycle repeats. 
  <br> 1st pair: The reverberation of the clap resonates within all in a `100` Square radius around. They suffer `+1` Bludgeoning Injury. 
  <br> 2nd pair: All in a straight AoE line, up to `20` Squares far, suffer `5` Bleeding damage. 
  <br> 3rd pair: All in a `100` Square radius around suffer `+1` Strain. 
  <br> 4th pair: Up to `3` MST become [Berserked](./strive-core.md#berserk), if they fail a Self-Control Ob `2` Test. 
  <br> 5th pair: All in a `10` Squares radius, suffer `8` Bleeding damage. 
  <br> 6th pair: All in a `10` Squares radius, suffer `-1` to every Attribute, for `3 Rounds.
  <br> 7th pair: Reprieve. All in a `30` Squares radius, regain `+10` HP and regain `3` Stamina.
  <br> 8th pair: All in a `100` Square radius around suffer `+2` Strain. 
  <br> 9th pair: All in a `20` Square radius around suffer `5` Pure damage.
  <br> 10th pair: Up to `3` MST become [Pacified](./strive-core.md#berserk), if they fail a Self-Control Ob `3` Test. 
  <br> 11th pair: All in a `20` Square radius around suffer `10` Pure damage.
  <br> 12th pair: All in a `100` Square radius around suffer `3D10 + 10` Pure damage.
  * Level: `4`, AP: `4`, Innate

**Legendary Actions**:
* Stop Time:
  * Once a Round, at any time, stop time and move freely, up to `10` Squares far while no one else may act. Can be used to avoid damage and other penalties. 
* Silent Clap:
  * A noiseless clap reverberates, shaking up the Arcanosphere, causing `1` Corruption in all magical creatures, in a `10` Square AoE radius around. Can be used once a Round. 

#### Hollow Gazer
This major Demon is but a husk of a creature. Its decrepit form can barely stand upright. Yet its piercing, red gaze is unwavering and merciless. 

* Power: Elite, CR: `15`
* Summoning Ob: `4`, Requirements: [Murky Malevite Orb](#malevite) or greater
* Roles: Artillery, Shock-Trooper
  * This Demon is particularly deadly. It lacks utility, but makes up for that with its evil gaze, which can quickly turn deadly. 
  * It is immovable, meaning Force-Moving it around won't work. Its foes will have to come up with smarter solutions.
* Behavior: 
  * Like all Demons, it is bent on the destruction of everything around it. Its hate is pure and inconsolable. 

| Agi   | Awar  | Str   | Tough | Wit   | Arc   |
| ----- | ----- | ----- | ----- | ----- | ----- |
| 1     | 5     | 1     | 6     | 3     | 8     |

| BI     | Sprint | Stabil | HP  | Stamina    | FS (Ranged `20`)| Def    | Armor             |
| ------ | ------ | ------ | --- | ---------- | --------------- | ------ | ----------------- |
| 9      | 3      | 0      | 60  | 12         | 6 Bleeding      |        | Half to all       |

**Traits**:
* [Fortified Mind](./strive-core.md#fortified-mind--4-points-1-cr)
* [Shambler](./strive-core.md#shambler-2-points--2-cr)
* [Immovable](./strive-core.md#immovable--2-points-1-cr);

**Assets**: None

**Skills**:
* Evil Gaze:
  * **Passive**: All victims it can see, in a `20` Square AoE line from it, begin to bleed incessantly from every orifice, suffering `6` Bleeding damage every Turn. Its maddening gaze is oppressive - its victims feel as though their head is being crushed and suffer `+1` [Strain](./strive-core.md#stamina--strain). This effect is constant and enduring.
  * Ranged, AoE, Innate

**Legendary Actions**:
* Pierce All:
  * Once every `3` Rounds, your gaze may pierce *any* obstacle. Breaking line of sight won't protect from the gaze anymore. 

#### Preacher
This major Demon appears as little more than a horned skull attached by chains to a torso of stone. Dark wings and brightly glowing arcane symbols flank the torso, almost giving it a divine appearance. It seems harmless, but this is part of its devious scheme. 

* Power: Elite, CR: `15`
* Summoning Ob: `5`, Requirements: [Murky Malevite Orb](#malevite) or greater
* Roles: Commander, Disruptor
  * One can only endure so much fear and doubt before they break. The Preacher knows this and can look into the heads of its victims. It will drive them mad, drive them to destroy themselves and each other. 
  * This Demon is very hard to reach, as it can freely float wherever it wishes and is difficult to Force-Move.
* Behavior: 
  * This peculiar variant floats calmly, often placing itself amidst and above settlements, whence its sinister words are carried far by the Arcane winds. And yet, its victims view it as some sort of savior, come to bring them salvation from sin and death. 

| Agi   | Awar  | Str   | Tough | Wit   | Arc   |
| ----- | ----- | ----- | ----- | ----- | ----- |
| 1     | 5     | 1     | 4     | 8     | 8     |

| BI     | Sprint | Stabil | HP  | Stamina    | FS (Ranged `20`)| Def    | Armor             |
| ------ | ------ | ------ | --- | ---------- | --------------- | ------ | ----------------- |
| 14     | 2      | 4      | 40  | 8          | 1 Pure          | 0      |                   |

**Traits**:
* [Fortified Mind](./strive-core.md#fortified-mind--4-points-1-cr)
* [Glider + Floater + Flyer](./strive-core.md#glider--1-points-1-cr)
* [Shambler](./strive-core.md#shambler-2-points--2-cr)

**Assets**: None

**Skills**:
* Sinister Sermon (Wit/Arc):
  * **Concentration**: All in a `20` Square radius around it, who can hear it and whose Self-Control is `≤ 3` begin to doubt their life is just and right. They begin to think of the darkness as a soft embrace, and to long for it. Every victim becomes hostile towards any other creature that succeeded the check. 
  * Level: `6`, AP: `4`, Ranged, AoE, Innate
* Prepare For Salvation (Wit/Arc):
  * A ST, up to `20` Squares away, becomes [Pacified](./strive-core.md#pacified) `+3`. 
  * Level: `6`, AP: `2`, Ob: `Opposed by Self-Control`, Ranged, AoE, Innate
* Come To Me:
  * Cause all who have fallen victim to your Sinister Sermon to become [Pacified](./strive-core.md#pacified) and run toward you, seeking your *loving* embrace. 
  * AP: `1`, Innate
* Embrace The Flock:
  * Draw the life from one of the victims to your Sinister Sermon or Come To Me, up to `20` Squares away. They suffer `10` Pure damage and you heal for the same amount. 
  * AP: `2`, Innate

## Swine-Beasts
Created in a vain and immoral conjuring of demons from another place, the Swine-Beasts themselves represent a cruel parody of man, molded from the flesh of pigs. All the worst properties of humanity are manifested in these unsavory creatures. 

A morphed and twisted union of human and swine flesh which stands on two legs, shorter than humans and in a perpetual hunch. They have boney claws instead of fingers and cloven swine-hooves instead of feet. Large tusks protrude aggressively from the jaw, as if reaching for victims. Red glowing, narrowed eyes glinting in the dark with malice. 

Beware the cesspits, the sewers, the bogs and marshes - any place where filth is abundant, for this is where the Swine thrive. They themselves are either impervious to the filth, or die too fast for it to matter, and will eat *anything*, with a particular appetite for flesh. They make it a particular point to bleed their victims, while skinning them alive and gloating at their pain. They are semi-demonic and live out the inherent cruelty that stems from that. 

They multiply quickly and often stay localized to their den. But they occasionally venture into more civilized areas to acquire food - which is often the inhabitants of those places - and plunder. They keep regular pigs as both livestock and as a means of reproducing, as when they have need of more of their foul kind, their shamans will perform the same wicked rituals to turn those harmless pigs into Swine-Beasts. 

### Swine Do Not Negotiate
Due to the demon bound inside them, they are inherently and irredeemably evil. Cruelty amuses them, injustice means nothing to them. They exist solely to mulitply, feed and destroy. Employ them for combat encounters. They do not negotiate and fight to the last. 

### Swine Tactics
The Swine's strength lies in their combat tactics. They work together, each precisely aware of their role, to stand united against a world that does not want them. 

Swine raiding parties usually comprise several [Stompers](#swine-stomper) and [Slashers](#swine-slasher) as the front-line, a few [Lungers](#swine-lunger) and several [Skewerers](#swine-skewerer) as support and back-line. If opposed by guardsmen or wannabe heroes, the Stompers and Slashers tie the enemy down and Lungers and Skewerers deal the real damage. Very rarely, raiding parties may be joined by [Champions](#swine-champion) and [Ogres](#swine-ogre). 

Swine war parties are often headed by a [Champion](#swine-champion) and rarely by a [Shaman](#swine-shaman). Many [Stompers](#swine-stomper) and [Slashers](#swine-slasher) and even one or two [Ogres](#swine-ogre) act as the front-line. Many [Belchers](#swine-belcher) and several [Skewerers](#swine-skewerer) act as the back-line. Some [Lungers](#swine-lunger) try to flank and disrupt enemy formations. 

### Swine Hostility
The following [Hostility Actions](./strive-core.md#hostility) are available to all Swine.

#### Demonic Blood
**`-20` Hostility**: Suddenly, a Swine stops dead in its tracks, clawing at its skull and squealing in distorted pain, as demon horns spring from its forehead and the veins beneath its skin begin to glow in bright crimson. It grows to twice its size and peers around hungrily. 
* It gains `+30` Temporary HP.
* It becomes [Berserked](strive-core.md#berserk).
* Its attacks deal an additional `+6` points of Bleeding damage. 

#### Filth & Darkness
**`-10` Hostility**: The foul Swine have prepared a trap! The battlefield is flooded with a nauseating miasma and covered in unnatural darkness! 
* All non-Swine with normal vision can only see up to `3` Squares far.
* All non-Swine suffer `-1D` to all Tests.

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

| BI     | Sprint | Stabil | HP  | Stamina    | FS (Ranged: 10) | Def    | Armor             |
| ------ | ------ | ------ | --- | ---------- | --------------- | ------ | ----------------- |
| 9      | 3      | 0      | 10  | 2          | 2 Acid          | 2      | 0                 |

**Traits**:
* [Disease-Ridden](strive-core.md#disease-ridden--1-point-1-cr)
* [Light-weight](strive-core.md#light-weight-2-points--1-cr)
* [Vulnerable](strive-core.md#vulnerable-2-points--2-cr) to Bleeding `+6`

**Assets**: Tattered Rags (Clothing)

**Skills**:
* Observation, Level: `3`
* Bite (Agi/Str):
  * Chomp down on a ST. 
  * Level: `2`, AP: `2`, Ob: `Opposed`, Melee, ST, Innate
  * `≤ 1` Hit: `2` Piercing
  * `= 2` Hits: `3` Piercing
  * `≥ 3` Hits: `4` Piercing
* Putrid Vomit (Agi/Awar):
  * Throw up a projectile of lumpy stomach acid and 'shoot' it at a target. 
  * Level: `4`, AP: `2`, Ob: `Opposed`, Ranged: `10`, ST, [Prefer Range](strive-core.md#weapon-traits), Innate
  * `≤ 1` Hit: `4` Acid
  * `= 2` Hits: `6` Acid
  * `≥ 3` Hits: `8` Acid

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

| BI     | Sprint | Stabil | HP  | Stamina    | FS (Melee)      | Def    | Armor             |
| ------ | ------ | ------ | --- | ---------- | --------------- | ------ | ----------------- |
| 8      | 4      | 2      | 50  | 5          | 3 Piercing      | 4      | 8/4/2/0 Slashing <br> 6/3/2/0 Piercing <br> 4/2/1/0 Bludgeoning |

**Traits**:
* [Vulnerable](strive-core.md#vulnerable-2-points--2-cr) to Bleeding `+6`
* [Hyperactive + Disruptive](strive-core.md#hyperactive--7-points-4-cr)

**Assets**: Polearm, Medium Shield, Swine Champion Armor

**Skills**:
* Shield, Level: `5`
* Unarmed Combat, Level: `3`
* Weapon \<Polearm\>, Level: `5`
* Bite (Agi/Str):
  * Chomp down on a ST. 
  * Level: `3`, AP: `2`, Ob: `Opposed`, Melee, ST, Innate
  * `≤ 1` Hit: `2` Piercing
  * `= 2` Hits: `3` Piercing
  * `≥ 3` Hits: `4` Piercing
* Gore:
  * Slam into a ST with your massive tusks. 
  * AP: `4`, Ob: `Opposed`, Melee, ST
  * `≤ 1` Hit: `Str + 2 (= 6)` Bludgeoning; Force-move `1`
  * `= 2` Hits: `Str + 4 (= 8)` Bludgeoning; Force-move `2`
  * `≥ 3` Hits: `Str + 6 (= 10)` Bludgeoning; Force-move `3`
* Interrupt:
  * **Reaction**: Upon an ally within `3` Squares of you being attacked, jump in and take over the Defense Test, with `+1` [Compensation Point](./strive-core.md#compensation-points). 
  * AP: `2`, Ob: `Opposed`, ST, Innate
* Swine Commanding (Tough/Wit):
  * A champion commands respect and obedience.
  * Level: `4`, Innate
  * You Are Mine!:
    * Instill fear and doubt into your a ST's heart, who becomes [Terrified](./strive-core.md#terrified) of you.
    * AP: `2`, Ob: `Opposed` by [Self-Control](./strive-core.md#self-control-toughtough), Ranged: `10`, Vocal
  * Kill That One!:
    * [Mark](./strive-core.md#marked) a ST of choice, up to `10` Squares away.
    * AP: `1`, Ob: `2`, Ranged, Vocal
  * You Die When I Let You!:
    * **Reaction**: Once in a battle, when an ally's HP are reduced to `0`, they are instead reduced to your `Hits * 3`. 
    * AP: `1`, Ranged, Vocal

**Hostility Actions**:
* [Collect Bounty](./strive-core.md#collect-bounty--4-points-3-cr)

### Swine Lunger
This variant is as almost as small as a Belcher, but with strong legs and arms, with atypically short tusks. Perhaps a youngling? It moves with uncanny precision, for a Swine. 

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

| BI     | Sprint | Stabil | HP  | Stamina    | FS (Melee)      | Def    | Armor             |
| ------ | ------ | ------ | --- | ---------- | --------------- | ------ | ----------------- |
| 10     | 4      | 0      | 20  | 2          | 4 Slashing      | 3      | 0                 |

**Traits**:
* [Vulnerable](strive-core.md#vulnerable-2-points--2-cr) to Bleeding `+6`

**Assets**: Tattered Rags (Clothing), Dagger x2

**Skills**:
* Stealth, Level: `4`
* Weapon \<Dagger\>, Level: `5`
* Lunge (Agi/Agi):
  * Lunge up to `7` Squares far, dealing damage to all foes in your path with your weapons. Does not provoke [Opportunity Attacks](strive-core.md#opportunity-attacks). 
  * Level: `4`, AP: `3`, Ob: `3`, Melee, AoE (line), Innate
  * `≤ 1` Hit: `2` Slashing
  * `= 2` Hits: `4` Slashing
  * `≥ 3` Hits: `6` Slashing
* Vault & Jab (Agi/Agi):
  * Jump over an adjacent enemy, landing behind them, and attack them. Does not provoke [Opportunity Attacks](strive-core.md#opportunity-attacks). 
  * Level: `5`, AP: `2`, Ob: `Opposed`, Melee, ST, Innate
  * `≤ 1` Hit: `Agi - 2 (= 4)` Slashing; Force-move `1`
  * `= 2` Hits: `Agi (= 6)` Slashing; Force-move `2`
  * `≥ 3` Hits: `Agi + 2 (= 8)` Slashing; Force-move `3`

### Swine Ogre
A hulking mass of Swine and muscle, towering above its lesser brethren. Despite its imposing nature, it frequently looks to the other Swine for guidance. Outside moments of violence, it appears lethargic. 

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
| 1     | 1     | 8     | 6     | 1     | 0     |

| BI     | Sprint | Stabil | HP  | Stamina    | FS (Melee)      | Def    | Armor             |
| ------ | ------ | ------ | --- | ---------- | --------------- | ------ | ----------------- |
| 3      | 4      | 4      | 60  | 7          | 4 Bludgeoning   | 1      | 0                 |

**Traits**:
* [Vulnerable](strive-core.md#vulnerable-2-points--2-cr) to Bleeding `+6`

**Assets**: Tattered Rags (Clothing), Crusher

**Skills**:
* Weapon \<Crusher\>, Level: `2`
* Slam (Str/Tough):
  * Slam into a ST.
  * Level: `4`, AP: `2`, Ob: `Opposed`, Melee, ST, `Strength` Bludgeoning damage, Innate
  * `≤ 1` Hit: `Strength - 2 (= 6)` Bludgeoning; Force-move `1`
  * `= 2` Hits: `Strength (= 8)` Bludgeoning; Force-move `2`
  * `≥ 3` Hits: `Strength + 2 (= 10)` Bludgeoning; Force-move `3`
* Tusk Thrust (Agi/Str):
  * Slam into a ST with your enormous tusks, imapling your victim upon them. 
  * Level: `3`, AP: `2`, Ob: `Opposed`, Melee, ST, Innate
  * `≤ 1` Hit: `2` Piercing; Force-move `1`
  * `= 2` Hits: `4` Piercing; Force-move `2`
  * `≥ 3` Hits: `6` Piercing; Force-move `3`

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

| BI     | Sprint | Stabil | HP  | Stamina    | FS (Ranged: 10) | Def    | Armor             |
| ------ | ------ | ------ | --- | ---------- | --------------- | ------ | ----------------- |
| 9      | 3      | 0      | 40  | 4          | 4 Acid          | 2      | 0                 |

**Traits**:
* [Vulnerable](strive-core.md#vulnerable-2-points--2-cr) to Bleeding `+6`

**Assets**: Fine Rags (Clothing)

**Skills**:
* Magic School \<Hexing\>, Level: `5`
* Medicine, Level: `3`
* Bite (Str/Tough):
  * Chomp down on a ST. 
  * Level `2`, AP: `2`, Ob: `Opposed`, ST, Melee, Innate
  * `≤ 1` Hit: `2` Piercing
  * `= 2` Hits: `3` Piercing
  * `≥ 3` Hits: `4` Piercing
* A Leader Of Swine (Wit/Wit):
  * A shaman commands respect and terror.
  * Level: `5`, Innate
  * Fire Up The Blood:
    * Strike up a haunting chant, in demonic language, stirring the blood of your fellow Swine. One of of them, up to `15` Squares away is enraged, and overwhelmed with their demoic blood beginning to boil, which starts leaking out of their eyes and nostrils. Until the end of combat, every tick, they suffer `5` points of bleeding damage (the Swine's vulnerability to bleeding damage does not get triggered by this), but also deal an additional `8` points of Bludgeoning damage on every successful attack. 
    * AP: `3`, Ob: `2`, ST (ally Swine), Ranged: `15`, Vocal
  * Drums Of Terror:
    * Beating on a drum with a... face... stretched across it, instill terror in your foes. Every non-Swine in a `15` Square AoE radius around must succeed a Self-Control Test, or else become [Terrified](strive-core.md#terrified) of the shaman. 
    * AP: `2`, Ob: `Opposed by Self-Control + 1`, MST, Ranged: `15`, Auditory
  * You Die When I Let You!:
    * **Reaction**: Once in a battle, when an ally's HP are reduced to `0`, they are instead reduced to your `Hits * 3`. 
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

| BI     | Sprint | Stabil | HP  | Stamina    | FS (Ranged: 10) | Def    | Armor             |
| ------ | ------ | ------ | --- | ---------- | --------------- | ------ | ----------------- |
| 10     | 4      | 0      | 30  | 4          | 4 Piercing      | 2      | 0                 |

**Traits**:
* [Vulnerable](strive-core.md#vulnerable-2-points--2-cr) to Bleeding `+6`
* [Poisoner](strive-core.md#poisoner--4-points-2-cr)

**Assets**: Tattered Rags (Clothing), Javelin x8, Trap: Bear x3

**Skills**:
* Observation, Level: `3`
* Stealth, Level: `5`
* Throw Javelin (Agi/Str):
  * Throw a javelin at a ST. 
  * Level: `4`, Ob: `Opposed`, Ranged: `10`, ST, Innate
  * `≤ 1` Hit: `4` Piercing
  * `= 2` Hits: `6` Piercing
  * `≥ 3` Hits: `8` Piercing

### Swine Slasher
This variant is lanky, lacking much of the bulk of its brethren. 

* Power: Regular, CR: `4`
* Roles: Brawler, Shock-Trooper
  * Employ as a front line fighter and cannon-fodder. Not meant to be particularly challenging, but rather as a wall of flesh in the way of high value targets. 
* Behavior: 
  * Noisy - squeals and grunts to itself frequently. 
  * Dislikes bright light and can see well in the dark.

| Agi   | Awar  | Str   | Tough | Wit   | Arc   |
| ----- | ----- | ----- | ----- | ----- | ----- |
| 2     | 2     | 4     | 3     | 1     | 0     |

| BI     | Sprint | Stabil | HP  | Stamina    | FS (Ranged: 10) | Def    | Armor             |
| ------ | ------ | ------ | --- | ---------- | --------------- | ------ | ----------------- |
| 5      | 3      | 1      | 30  | 4          | 3 Slashing      | 2      | 0                 |

**Traits**:
[Vulnerable](strive-core.md#vulnerable-2-points--2-cr) to Bleeding `+6`

**Assets**: Tattered Rags (Clothing), Axe, Light Shield

**Skills**:
* Shield, Level: `3`
* Weapon \<Axe\>, Level: `3`

### Swine Stomper
This variant is massive and strong. Most of its body is covered in dark, dirty clumped up fur. The tusks are menacing weapons of their own. 

* Power: Regular, CR: `5`
* Roles: Brawler, Disruptor
  * These hulking beasts represent the swine-folks front line fighters. They protect the squalid den and impede intruders who threaten the shaman. 
  * Employ as a front line fighter. May be taken down quickly, as it will not dodge, so consider using more than one in a fight. Intended to be a wall of flesh in the way toward high value targets. 
* Behavior: 
  * Very aggressively pushes enemies around. 
  * Bullies other Swine who aren't champions or shamans. 
  * Noisy - squeals and grunts to itself frequently. 
  * Dislikes bright light and can see well in the dark.

| Agi   | Awar  | Str   | Tough | Wit   | Arc   |
| ----- | ----- | ----- | ----- | ----- | ----- |
| 2     | 1     | 6     | 4     | 1     | 0     |

| BI     | Sprint | Stabil | HP  | Stamina    | FS (Melee)      | Def    | Armor             |
| ------ | ------ | ------ | --- | ---------- | --------------- | ------ | ----------------- |
| 4      | 3      | 3      | 40  | 4          | 3 Slashing      | 1      | 0                 |

Traits: [Vulnerable](strive-core.md#vulnerable-2-points--2-cr) to Bleeding `+6`

Assets:
* Clothing: Swine Armored Rags, Crusher

Swine Armored Rags: Slashing `6`, Piercing `4`, Bludgeoning `3`, Acid `6`

Skills:
* Unarmed Combat, Level: `4`
* Weapon \<Crusher\>, Level: `3`
* Bite (Agi/Str):
  * Chomp down on a ST. 
  * Level: `3`, AP: `2`, Ob: `Opposed`, Melee, ST, Innate
  * `≤ 1` Hit: `2` Piercing
  * `= 2` Hits: `3` Piercing
  * `≥ 3` Hits: `4` Piercing
* Gore:
  * Slam into a ST with your massive tusks. 
  * Level: `3`, AP: `2`, Ob: `Opposed`, Melee, ST
  * `≤ 1` Hit: `Str (= 6)` Bludgeoning; Force-move `1`
  * `= 2` Hits: `Str + 2 (= 8)` Bludgeoning; Force-move `2`
  * `≥ 3` Hits: `Str + 4 (= 10)` Bludgeoning; Force-move `3`

## Veil Entities
Veil Entities are unlike any other. They are strange and unfathomable things from a dimension, or other form of existence unlike any we know. These entities aren't necessarily evil, nor are they particularly interested in causing harm, if indeed they are capable of sapience at all. It is their very nature that is harmful to ours. Fortunately, The Veil reclaims its denizens diligently. 

### The Monolith
A rough-hewn, crystalline monolith of obsidian color. Crimson veins pulsate gently, just beneath the surface. It draws every gaze towards it, whispering unknowable secrets and beckoning with malignity. Everyone within a `30` Square AoE radius around it is affected and suffers `+1` [Bleeding](strive-core.md#bleeding) at the start of their Turn and **cannot** look away, for as long as they have line of sight to it. The Monolith lasts for `5` Rounds or `5` minutes, before The Veil reclaims it. When that happens, it explodes, dealing `8` [Bludgeoning](strive-core.md#damage-types) damage and inflicting `+2` [Bleeding](strive-core.md#bleeding) to all within its radius.

### Perfection
A giant sphere of pure white light. Its surface is infinitely smooth. Nothing can stick to it, nothing can touch it. Everything that touches it, is thrown back, by `8`. And yet, every living thing in a `30` Square AoE radius around it desires nothing more than to touch it, unless they succeed a Self-Control Test at Ob `4` at the start of their Turn. The Sphere lasts for `5` Rounds or `5` minutes, before it vanishes, leaving behind darkness and emptiness that fills all hearts with unconsolable sorrow. Every creature in range is [Pacified](strive-core.md#pacified) for `1` Round or minute.

### The Tar Mycelium
The entire scene is covered in a black, slimy web of tiny pulsating strands of a massive mycelium. This fungus grows quickly, rapidly enveloping everything it touches. The entire scene is considered Difficult Terrain. If a creature stands still for `2` Turns, the fungus envelops them and begins devouring them alive. They suffer `1D4` [Acid](strive-core.md#damage-types) damage at the end of their second Turn and after that, at the start of every Turn they haven't yet moved.

The mycelium dissipates into black smoke after `3` Rounds. 

### Cacophony of Flesh
An abominable mound of misshapen flesh, with countless ragged tentacles of various sizes protruding from it. As soon as it is able, it will violently thrash about, trying *desperately* to inflict vengeful violence upon all in its path. Lasts for `5` Rounds or `5` minutes, before it melts away gruesomely. 

* Power: Regular, CR: `20`
* Roles: Tank, Brawler
  * This aberration is not your average foe. It is not to be engaged, as trying to slay it would be far too perilous.
* Behavior: 
  * Hungrily seeks and lurches towards victims to devour. 

| Agi   | Awar  | Str   | Tough | Wit   | Arc   |
| ----- | ----- | ----- | ----- | ----- | ----- |
| 5     | 5     | 10    | 10    | 1     | 0     |

| BI     | Sprint | Stabil | HP  | Stamina    | FS (Melee)      | Def    | Armor             |
| ------ | ------ | ------ | --- | ---------- | --------------- | ------ | ----------------- |
| 4      | 1      | 5      | 200 | 5          | 5 Bludgeoning   | 1      | 0                 |

**Traits**:
* [Climber + Sticky](strive-core.md#climber--2-points-1-cr)

**Skills**: 
* Unarmed Combat: Level `5`, Innate
* Slam (Str/Tough):
  * Slam down with your entire body, enveloping all within reach in a tentacled mass. They are rendered [Prone](./strive-core.md#prone) and [Grappled](./strive-core.md#grappled).
  * Level: `4`, AP: `2`, Ob: `4`, Ranged: `2`, AoE (radius): `2` Squares
  * `≤ 1` Hit: `8` Bludgeoning
  * `= 2` Hits: `10` Bludgeoning
  * `≥ 3` Hits: `12` Bludgeoning
* Thrash (Agi/Str):
  * Everything in a `3` radius around you is thrown away from you as your tentacles flail about, wildly.
  * Level: `4`, AP: `3`, Ob: `4`, Ranged: `2`, AoE (radius): `2` Squares
  * `≤ 1` Hit: Force-move `2`
  * `= 2` Hits: Force-move `4`
  * `≥ 3` Hits: Force-move `6`
* Devour (Agi/Str):
  * Devour a ST creature in one swoop. As they enter your stomach, they are considered [Grappled](./strive-core.md#grappled) and cannot move on their own. They suffer `6` Acid damage at the start of your every Turn. Only one creature may be devoured, at a time. You can spit out a creature you devoured, at no AP cost.
  * Level: `3` AP: `2`, Ob: `Opposed`

### The Puppeteer
A giant stick-figure, shrouded in swirling darkness and blurred edges. All corpses, no matter how old, within `300` Squares around the Puppeteer begin to move again. They arise from their tombs, graves and battlefields, to enact terrible vengeance on the living. The Puppeteer lasts for several days. Should The Puppeteer be called again from The Veil in the time it is already present, then several more days will be added to the time it may escape The Veil. 

## Undead
Whether they occur naturally or unnaturally, both your typical undead and some more unusual specimen may haunt your world. While the Fantasy Module assumes them to be mindless monsters, you may of course decide for your world that they may in fact retain some if not all of their sapience. This Module assumes sapient Undead to be **Liches**, a greater form of [Revenant](#revenant), which you may build as you would any proper NPC. 

### Undead Hostility
The following [Hostility Actions](./strive-core.md#hostility) are available to most Undead.

#### Rise Again
**-10 Hostility**: Undead just don't stay down. One of them rises again, rejoined with whatever body parts it may have lost along the way by ghostly tendrils. 
* The Undead gains `+20` Temporary HP.

### Alp
The Alp is a predator, yet it preys not on flesh, but on raw fear itself. For this reason, it often encroaches on civilization, where it causes streaks of never ending nightmares for the people. They can take this evil spiel so far as to drive their victims insane. Suicides in villages haunted by Alps are not uncommon.

This hunched humanoid is pale and haggard. Its face is featureless, devoid of eyes and mouth. Long claws at the ends of its three fingers clarify its hostile intent. 

Alps are a fairly common occurence throughout the world. How they reproduce is a bit of a mystery, though it is assumed to be related victims taking their own lives. In a way, the Alp's condition might be carried like a self-perpetuating curse. Fact is that the graves of suicides often end up empty just a few days later. Although such graves are often regarded as sacrilegious and are ill-favored by the locals, which may simply have decided they have a better use for the space or valuables the victim was buried with. 

* Power: Elite, CR: `14`
* Roles: Ambusher
  * Employ as an investigation and moderate combat challenge. 
  * If you want to ramp up the challenge, have the encounter begin near a civilian victim which the Alp is about to or already has put to sleep, so it can immediately use "Induce Nightmare". 
  * Will try to Induce Sleep as often as it can and then Induce Nightmare. 
  * Will Rend singular nearby foes if given the chance. Tries to avoid being surrounded. 
  * Has a sense of self preservation and will try to flee Combat when things go awry. 
* Behavior: 
  * Stays close to civilization. May sometimes even hide inside towns and cities. 
  * Only active at night. Tends to hibernate during the day, in a well hidden location. 

| Agi   | Awar  | Str   | Tough | Wit   | Arc   |
| ----- | ----- | ----- | ----- | ----- | ----- |
| 4     | 2     | 2     | 3     | 5     | 5     |

| BI     | Sprint | Stabil | HP  | Stamina    | FS (Melee)      | Def    | Armor             |
| ------ | ------ | ------ | --- | ---------- | --------------- | ------ | ----------------- |
| 11     | 4      | 0      | 30  | 6          | 3 Slashing      | 3      | 0                 |

**Traits**:
* [Camouflage](./strive-core.md#camouflage--3-points-3-cr)

**Assets**: Usually none, although it may still wear whatever jewelry it had in life.

**Skills**: 
* Stealth: Level `3`
* Induce Nightmare (Wit/Arc):
  * Induces nightmares on all nearby (`20` Square AoE radius around the Alp) sleeping Characters. This strengthens the Alp, removing `1` active Injury for every induced nightmare. The Alp gains `+3` to Strength and `+1` to Toughness. While nightmare lasts, every Turn the Alp regains `5` HP for every nightmare and every victim suffers `5` Pure damage. Nightmare lasts for `5` Rounds or `30` minutes. Any creature with a nightmare can be woken up (in any way you like), at Ob `3`. The Alp immediately loses boons for every Character woken up early. This ability does not stack with itself. After the time is up, the affected creatures automatically wake up. 
  * Does not stack: Every sleeping Character can only be affected once. 
  * Level: `7`, AP: `2`
* Induce Sleep (Wit/Arc):
  * Forces the victim to fall asleep, on the spot. They become [Unconscious](./strive-core.md#unconscious), but can be woken through physical harm or a very strong shaking, at Ob `3` for Tests to wake them up. 
  * Level: `7`, AP: `2`, Ob: `Opposed by Self-Control`, ST, Ranged: `20`, Psionic
* Rend (Agi/Str): 
  * Tear a victim to shreds. 
  * Level: `3`, AP: `2`, Ob: `Opposed`, ST, Melee
  * `≤ 1` Hit: `Str + 2 (= 4)` Slashing
  * `= 2` Hits: `Str + 4 (= 6)` Slashing
  * `≥ 3` Hits: `Str + 6 (= 8)` Slashing
### Bloated Shambler
Bloated shamblers are grotesque, hulking masses of bloated undead flesh. They're a type of flesh golem, comprised of multiple bodies sewn together and filled with noxious, rotten air. With a vacant gaze through dulled eyes they waddle towards their goal, struggling to stay on their swollen feet, yet unfaltering in their sinister purpose. 

* Power: Regular, CR: `4`
* Roles: Disruptor, Tank
  * Employ as a priority target, that will punish foes who neglect it. It tries to get as close to as many enemies as possible and then attempts to grapple and choke the life out of whoever is most accessible. 
  * If left alive for too long, it will explode in a gory and nauseating display, that will Force-Move foes and deal damage to them.
  * Will attempt to grapple and then Choke a foe. 
* Behavior: 
  * When [bound](#soul-binding-arctough), will only follow its master's commands. Otherwise, wanders aimlessly or stands still, staring into space. But may become hostile if agitated. 

| Agi   | Awar  | Str   | Tough | Wit   | Arc   |
| ----- | ----- | ----- | ----- | ----- | ----- |
| 1     | 1     | 5     | 5     | 1     | 0     |

| BI     | Sprint | Stabil | HP  | Stamina    | FS (Melee)      | Def    | Armor             |
| ------ | ------ | ------ | --- | ---------- | --------------- | ------ | ----------------- |
| 3      | 3      | 3      | 50  | 10         | 3 Bludgeoning   | 0      | 0                 |

**Traits**:
* [Death Rattle](./strive-core.md#death-rattle--2-points-2-cr) (Explode: `2D4` Bludgeoning and Force-Moving `5` Squares, in an AoE radius of `2` Squares)
* [Shambler](./strive-core.md#shambler-2-points--2-cr)
* [Fortified Mind](./strive-core.md#fortified-mind--4-points-1-cr)

**Assets**: None

**Skills**: 
* Unarmed Combat: Level `3`
* Choke (Str/Tough): 
  * If grappling a ST, choke the life out of them. 
  * Level `3`, AP: `1`, Melee, ST, Innate
  * `≤ 1` Hit: `4` Bludgeoning
  * `= 2` Hits: `5` Bludgeoning
  * `≥ 3` Hits: `6` Bludgeoning

### Bone Spider
Bone spiders are a particularly nasty type of undead, often employed by necromancers as guardians or scouts. 

As their name implies, bone spiders are an amalgamation of various different bones that come together to form the shape of a spider.

Three skulls sit on its blobby body's front and two large fangs protrude from the larger central skull's jaw.

Eight very long and thin bony legs carry the creature's weight. Their ends are sharpened, with little "hooks" of bone protruding from the side, which allows the bone spider to stick to any surface.

* Power: Regular, CR: `10`
* Roles: Ambusher, Shock-Trooper
  * Employ 
* Behavior: 
  * When [bound](#soul-binding-arctough), will only follow its master's commands. Otherwise, wanders aimlessly or stands still, staring into space. But may become hostile if agitated. 

| Agi   | Awar  | Str   | Tough | Wit   | Arc   |
| ----- | ----- | ----- | ----- | ----- | ----- |
| 5     | 1     | 5     | 5     | 1     | 0     |

| BI     | Sprint | Stabil | HP  | Stamina    | FS (Melee)      | Def    | Armor             |
| ------ | ------ | ------ | --- | ---------- | --------------- | ------ | ----------------- |
| 3      | 3      | 3      | 50  | 10         | 6 Slashing      | 3D     | 8/4/2/0 Slashing <br> 6/3/2/0 Piercing <br> 4/2/1/0 Bludgeoning <br> Poison immune <br> 4 Bleeding |

**Traits**:
* [Death Rattle](./strive-core.md#death-rattle--2-points-2-cr) (Explode: `2D4` Bludgeoning and Force-Moving `5` Squares, in an AoE radius of `2` Squares)
* [Shambler](./strive-core.md#shambler-2-points--2-cr)
* [Fortified Mind](./strive-core.md#fortified-mind--4-points-1-cr)

**Assets**: None

**Skills**: 
* Rend (Agi/str): 
  * Strike at a ST with your claws, rending their flesh. 
  * Level `3`, AP: `1`, Melee, ST, Innate
  * `≤ 1` Hit: `5` Slashing
  * `= 2` Hits: `7` Slashing
  * `≥ 3` Hits: `10` Slashing

### Ghoul
A lesser Undead that stalks graveyards and fresh battlefields, in search of carrion. 

They're generally seen as nuisances that defile places of supposed eternal rest. When alone, they're not particularly threatening, but can prove quite dangerous in larger numbers. Ghouls are also fiercely territorial, driven by pure instinct to attack any intruders. The only exception to this rule is observable near feasting grounds, where food is very abundant. Otherwise, they're nomadic creatures, moving on whenever a feeding ground has been exhausted. Sometimes they move in packs, but most commonly, they migrate alone. 

They're squat creatures, with spotted pale skin. Their pathetic stature belies the threat they represent. Their long, gorilla-like arms are lined with bony spikes, which can cause nasty wounds. Their deformed hands end in long claws of bone, while their large split jaw can easily crush bone. 

* Power: Regular, CR: `8`
* Roles: Brawler
  * While not particularly threatening on their own, they become deadly en masse, as they can heal themselves. 
  * Will use Rend whenever at `10+` HP, otherwise attempts to Bite, in order to heal. 
* Behavior: 
  * When [bound](#soul-binding-arctough), will only follow its master's commands. Otherwise, stalks battlefields and graveyards, or any other place of death. 
  * Their bite and their excrements can pass on their condition, which only manifests a long time after death. As such, there is always a steady influx of Ghouls, as it is impossible to tell where they've been and near impossible to detect the latent curse. 
  * Too stupid to flee Combat when things go awry. 

| Agi   | Awar  | Str   | Tough | Wit   | Arc   |
| ----- | ----- | ----- | ----- | ----- | ----- |
| 5     | 2     | 5     | 2     | 2     | 0     |

| BI     | Sprint | Stabil | HP  | Stamina    | FS (Melee)      | Def    | Armor             |
| ------ | ------ | ------ | --- | ---------- | --------------- | ------ | ----------------- |
| 9      | 3      | 0      | 20  | 4          | 5 Slashing      | 2      |                   |

**Traits**:
* [Fast](./strive-core.md#fast--2-points-1-cr)
* [Disease-Ridden](./strive-core.md#disease-ridden--1-point-1-cr)

**Assets**: None

**Skills**: 
* Bite (Str/Tough): 
  * Bite an adjacent ST with your huge split jaw and feast! 
  * Level `3`, AP: `2`, Ob: `Opposed`, Melee, ST, Innate
  * `≤ 1` Hit: `2` Bludgeoning; Regain `+2` HP
  * `= 2` Hits: `3` Bludgeoning; Regain `+4` HP
  * `≥ 3` Hits: `4` Bludgeoning; Regain `+6` HP
* Rend (Agi/Str): 
  * Strike at an adjacent ST with your claws. 
  * Level `4`, AP: `2`, Ob: `Opposed`, Melee, ST, Innate
  * `≤ 1` Hit: `4` Slashing
  * `= 2` Hits: `5` Slashing
  * `≥ 3` Hits: `6` Slashing + `3` Piercing

### Revenant
A greater Undead with a limited capacity for independent thought. It retains much of its skill, even after death. 

* Power: Regular, CR: `6`
* Roles: Brawler
  * A greater threat than a [Zombie](#zombie), but still one of the more manageable Undead foes. Intended for use in greater numbers. 
  * Will attack and defend with its weapon. 
* Behavior: 
  * When [bound](#soul-binding-arctough), will only follow its master's commands. Otherwise, wanders aimlessly or stands still, staring into space. But may become hostile if agitated. 
  * May also occur naturally, when the Arcanosphere's winds are agitated near graveyards and fresh battlefields. 

| Agi   | Awar  | Str   | Tough | Wit   | Arc   |
| ----- | ----- | ----- | ----- | ----- | ----- |
| 3     | 3     | 4     | 3     | 3     | 0     |

| BI     | Sprint | Stabil | HP  | Stamina    | FS (Melee)      | Def    | Armor             |
| ------ | ------ | ------ | --- | ---------- | --------------- | ------ | ----------------- |
| 9      | 3      | 0      | 30  | 6          | 5 Slashing      | 3D     |                   |

**Traits**:
* [Fortified Mind](./strive-core.md#fortified-mind--4-points-1-cr)

**Assets**: Potentially some rusted armor

**Skills**: 
* One weapon Skill of choice, at Level `4`: [Axe](#weapon-axe-strstr), [Long Blade](#weapon-long-blade-agistr), [Polearm](#weapon-polearm-strtough), [Crossbow](#weapon-crossbow-awarawar)

### Spine Thresher
A bone golem with long, rope-y arms made of spinal columns, lined with knife-like bones and tipped with sharp spikes. And they have a tail with a mace-head at the end. 

* Power: Regular, CR: `8`
* Roles: Artillery
  * A deadly foe that stays out of melee. 
  * Uses Tail Slam to knock nearby enemies back. Otherwise, uses Spinal Whip. 
* Behavior: 
  * When [bound](#soul-binding-arctough), will only follow its master's commands. Otherwise, wanders aimlessly or stands still, staring into space. But may become hostile if agitated. 

| Agi   | Awar  | Str   | Tough | Wit   | Arc   |
| ----- | ----- | ----- | ----- | ----- | ----- |
| 6     | 2     | 3     | 4     | 1     | 0     |

| BI     | Sprint | Stabil | HP  | Stamina    | FS (Melee)      | Def    | Armor             |
| ------ | ------ | ------ | --- | ---------- | --------------- | ------ | ----------------- |
| 7      | 4      | 0      | 40  | 4          | 6 Bludgeoning   | 3D     | 8/4/2/0 Slashing <br> 6/3/2/0 Piercing <br> 4/2/1/0 Bludgeoning <br> Poison immune <br> 4 Bleeding |

**Traits**:
* [Fortified Mind](./strive-core.md#fortified-mind--4-points-1-cr)

**Assets**: None

**Skills**: 
* Spinal Whip (Agi/Str): 
  * Lash out at a ST with your spinal rope-arms, up to `5` Squares away.
  * Level `4`, AP: `2`, Ob: `Opposed`, Ranged, ST, Innate
  * `≤ 1` Hit: `5` Bludgeoning + `5` Slashing
  * `= 2` Hits: `6` Bludgeoning + `6` Slashing
  * `≥ 3` Hits: `8` Bludgeoning + `8` Slashing
* Knockback (Agi/Str): 
  * Lash out at all targets in a `5` Square AoE cone with your spinal rope-arms, knocking opponents away.
  * Level `4`, AP: `2`, Ob: `1`, Ranged, AoE, Innate
  * `≤ 1` Hit: `4` Bludgeoning; Knocked back `2` Square
  * `= 2` Hits: `6` Bludgeoning; Knocked back `3` Squares
  * `≥ 3` Hits: `8` Bludgeoning; Knocked back `4` Squares

### Terrorghast
A huge flesh golem with proportions like a gorilla and a strong carapace of metal, wielding a giant sword. 

* Power: Elite, CR: `15`
* Roles: Disruptor, Shock-Trooper, Tank
  * A deadly foe that is difficult to bring down. Its main weakness is its slow reaction speed. 
  * Uses Charge when surrounded, or when foes are neatly alined. But may also Charge at random. This thing isn't very tactically minded. 
  * Uses Slam on nearby singular foes, or at random. 
* Behavior: 
  * When [bound](#soul-binding-arctough), will only follow its master's commands. Otherwise, wanders aimlessly or stands still, staring into space. But may become hostile if agitated. 

| Agi   | Awar  | Str   | Tough | Wit   | Arc   |
| ----- | ----- | ----- | ----- | ----- | ----- |
| 3     | 1     | 6     | 6     | 1     | 0     |

| BI     | Sprint | Stabil | HP  | Stamina    | FS (Melee)      | Def    | Armor             |
| ------ | ------ | ------ | --- | ---------- | --------------- | ------ | ----------------- |
| 5      | 4      | 2      | 60  | 12         | 6 Bludgeoning   | 0      | 8/4/2/0 Slashing <br> 6/3/2/0 Piercing <br> 4/2/1/0 Bludgeoning <br> Poison immune <br> 4 Bleeding |

**Traits**:
* [Sluggish](./strive-core.md#sluggish-4-points--2-cr)
* [Fortified Mind](./strive-core.md#fortified-mind--4-points-1-cr)

**Assets**: None

**Skills**: 
* Charge (Tough/Tough): 
  * Charge forward in a AoE straight line, up to `10` Squares far, knocking aside anything in your path, `4` Squares far. You must charge at least `4` Squares in a straight line for this and cannot stop prematurely. But you *may* crash into an obstacle, which stops you. 
  * Level `3`, AP: `3`, Melee, AoE, Innate
* Slash (Agi/Str): 
  * Strike at a ST with your sword. 
  * Level `4`, AP: `2`, Ob: `Opposed`, Melee, ST, Innate
  * `≤ 1` Hit: `8` Slashing
  * `= 2` Hits: `10` Slashing; Target is knocked back `1` Square
  * `≥ 3` Hits: `13` Slashing; Target is knocked back `2` Squares
* Slam (Agi/Str): 
  * Slam into a ST with your massive arms.
  * Level `4`, AP: `2`, Ob: `Opposed`, Melee, ST, Innate
  * `≤ 1` Hit: `6` Bludgeoning; Target is knocked back `3` Squares
  * `= 2` Hits: `7` Bludgeoning; Target is knocked back `4` Squares
  * `≥ 3` Hits: `8` Bludgeoning; Target is knocked back `5` Squares

### Zombie
A lesser form of undeath, Zombies are mindless walking corpses in varying stages of decomposition, held together only by magic forces. 

* Power: Feeble, CR: `2`
* Roles: Tank
  * Zombies aren't dangerous on their own, but en masse, can serve as a mobile meat shield. 
  * Will try to grapple and then Choke a foe. 
  * May also occasionally punch a foe. 
* Behavior: 
  * When [bound](#soul-binding-arctough), will only follow its master's commands. Otherwise, wanders aimlessly or stands still, staring into space. But may become hostile if agitated. 
  * May also occur naturally, when the Arcanosphere's winds are agitated near graveyards and fresh battlefields. 

| Agi   | Awar  | Str   | Tough | Wit   | Arc   |
| ----- | ----- | ----- | ----- | ----- | ----- |
| 1     | 1     | 3     | 3     | 1     | 0     |

| BI     | Sprint | Stabil | HP  | Stamina    | FS (Melee)      | Def    | Armor             |
| ------ | ------ | ------ | --- | ---------- | --------------- | ------ | ----------------- |
| 3      | 2      | 0      | 30  | 6          | 3 Bludgeoning   |        | Poison immune     |

**Traits**:
* [Shambler](./strive-core.md#shambler-2-points--2-cr)
* [Sluggish](./strive-core.md#sluggish-4-points--2-cr)
* [Fortified Mind](./strive-core.md#fortified-mind--4-points-1-cr)

**Assets**: None

**Skills**: 
* Unarmed Combat: Level `3`
* Choke (Str/Tough): 
  * If grappling a ST, choke the life out of them. 
  * Level `3`, AP: `1`, Melee, ST, Innate
  * `≤ 1` Hit: `2` Bludgeoning
  * `= 2` Hits: `3` Bludgeoning
  * `≥ 3` Hits: `4` Bludgeoning

**Legendary Actions**: 
Employ these only for *really* special Zombies. 
* Uncanny Dodge:
  * Up to `3` times per Round, try avoiding an attack with `3D` and `1` Compensation Point.
* Trample:
  Run up to `6` Squares far, knocking aside all other Characters by `2` Squares, once per Round. 

## Voidlings
When a soul is thrust into the void between realities, it is stretched infinitely thin. Unable to fill the void, it snaps and implodes, bouncing back into reality, but broken. It cannot function as it once did and furthermore, keeps open a tear to the void. It apparates as a monster of swirling shadow, not quite corporeal, yet not fully ethereal. 

Desperate to fill the void within them, they seek out any source of heat and light to try and absorb. The souls of living things are of particular interest, as a Voidling desires to be made whole again. The only way it knows how, is by trying to merge its soul with another. As souls generally occupy a host and will not budge, the host must first be eliminated. As such, Voidlings act with utmost hostility towards living things and will stop at nothing to kill. 

A Voidling does not speak and is neither sapient, nor sentient. It cannot reason and does not negotiate. 

### Void's Breath
This variant of Voidling is vaguely humanoid, its amorphous face stretched out like a beak and its arms ending in spikes of hardened darkness. 

* Power: Regular, CR: `8`
* Roles: Ambusher, Multiplier
  * A simple, yet tricky foe, which is difficult to harm with mundane means and which will try to spawn more of its own kind, by inflicting damage to its victims. A challenge for the careless. Employ as a challenge that can increase its own intensity if left alive too long. 
* Behavior: 
  * Lurks the darkest shadows it can find, but hops between them frequently to find victims quickly. 

| Agi   | Awar  | Str   | Tough | Wit   | Arc   |
| ----- | ----- | ----- | ----- | ----- | ----- |
| 4     | 4     | 2     | 2     | 1     | 5     |

| BI     | Sprint | Stabil | HP  | Stamina    | FS (Melee)      | Def    | Armor             |
| ------ | ------ | ------ | --- | ---------- | --------------- | ------ | ----------------- |
| 9      | 3      | 0      | 20  | 4          | 2 Piercing + 3 Freezing | 1      | Half (RU) against all but Burning <br> Takes double damage from Burning |

Traits: 
* **Ethereal Nature**: Its shadowy form isn't quite corporeal and barely suffers physical damage, but burns well. It is very slowly disintegrating on its own, and unless it finds sustenance, will fade on its own, in a few days. 

Skills:
* **Breath Of The Void** (Arc/Arc):
  * Draw the energy out of a `5` Square AoE cone in front of you. Every living creature also suffers `+1` stack of the **Voidchilled** Condition. Once it reaches `5` stacks on the victim, it resets zo `0` and spawns another Void's Breath. It decreases by `-1` automatically, at the end of the victim's Turn. 
  * Level: `5`, AP: `5`, AoE, Ranged
  * `≤ 1` Hit: `4` Freezing; Foe Tough `≤ 1`: Heal self `+3` HP
  * `= 2` Hits: `6` Freezing; Foe Tough `≤ 3`: Heal self `+3` HP
  * `≥ 3` Hits: `8` Freezing; Foe Tough `≤ 5`: Heal self `+5` HP
* **Cold Spike** (Agi/Arc):
  * Strike at a ST with a spike of hardened shadow. 
  * Level: `4`, AP: `2`, Ob: `Opposed`, Melee, ST, Innate
  * `≤ 1` Hit: `2` Piercing + `2` Freezing
  * `= 2` Hits: `3` Piercing + `3` Freezing
  * `≥ 3` Hits: `4` Piercing + `4` Freezing
* **Shadow Step** (Arc/Arc):
  * Disappear into the shadows and re-appear in another shadowy location, up to `20` Squares away. 
  * AP: `1`

### Void's Hunger
This variant of Voidling loosely resembles an eel, with thin arms with which it drags its incorporeal form across the floor. The bloated upper body glows in spots. 

* Power: Regular, CR: `10`
* Roles: Artillery
  * A dangerous foe that may blast multiple foes with its AoE damage, but dies easy enough. 
  * Always prefers using Devour Light on light sources, but will also use it if none can be found, as a last-ditch defense. 
  * Will always try to use Light Blast as often as it may. 
* Behavior: 
  * Always drawn to light and flame, seeking to devour them. And always migrating towards new light sources, and may disintegrate and fade, if it cannot find any. 

| Agi   | Awar  | Str   | Tough | Wit   | Arc   |
| ----- | ----- | ----- | ----- | ----- | ----- |
| 2     | 4     | 2     | 3     | 1     | 5     |

| BI     | Sprint | Stabil | HP  | Stamina    | FS (Ranged `10`) | Def    | Armor             |
| ------ | ------ | ------ | --- | ---------- | ---------------- | ------ | ----------------- |
| 7      | 2      | 0      | 30  | 6          | 4 Freezing       | 1      | Half (RU) against all but Burning <br> Takes double damage from Burning |

Traits: 
* **Ethereal Nature**: Its shadowy form isn't quite corporeal and barely suffers physical damage, but burns well. It is very slowly disintegrating on its own, and unless it finds sustenance, will fade on its own, in a few days. 

Skills:
* **Devour Light** (Arc/Arc):
  * Devours all light and flame in a `5` Square AoE cone. 
  * Level: `5`, AP: `3`, Ob: `1`, AoE, Ranged
  * `≤ 1` Hit: `3` Freezing; Heal self `+2` HP, for each light or flame
  * `= 2` Hits: `4` Freezing; Heal self `+3` HP, for each light or flame
  * `≥ 3` Hits: `5` Freezing; Heal self `+4` HP, for each light or flame
* **Light Blast** (Agi/Arc):
  * Regurgitate devoured light, blasting all in a `5` Square AoE cone. Can only be used if Devour Light was used prior. 
  * Level: `4`, AP: `3`, Ob: `1`, Ranged, AoE, Innate
  * `≤ 1` Hit: `5` Burning
  * `= 2` Hits: `7` Burning
  * `≥ 3` Hits: `9` Burning

### Void's Lament
This variant of Voidling is a floating ball of swirling shadow. Eyes regularly materialize and then disintegrate on its body. 

* Power: Elite, CR: `12`
* Roles: Artillery
  * A particularly tricky foe, that floats just out of melee reach, keeping its distance and using a variety of Gazes to deadly effect. 
  * Will use every Gaze it has, one after another, except Lamenting Gaze, which it uses only after all other Gazes. 
* Behavior: 
  * 

| Agi   | Awar  | Str   | Tough | Wit   | Arc   |
| ----- | ----- | ----- | ----- | ----- | ----- |
| 2     | 4     | 2     | 3     | 1     | 5     |

| BI     | Sprint | Stabil | HP  | Stamina    | FS (Ranged `15`) | Def    | Armor             |
| ------ | ------ | ------ | --- | ---------- | ---------------- | ------ | ----------------- |
| 7      | 2      | 0      | 30  | 6          | 4 Freezing       | 0      | Half (RU) against all but Burning <br> Takes double damage from Burning |

Traits: [Glider + Floater (`10` Squares above the ground)](./strive-core.md#glider--1-points-1-cr)
* **Ethereal Nature**: Its shadowy form isn't quite corporeal and barely suffers physical damage, but burns well. It is very slowly disintegrating on its own, and unless it finds sustenance, will fade on its own, in a few days. 

Skills:
* **Chilling Gaze** (Arc/Arc):
  * The Void calls, its gaze merciless. A ST is chilled to the bone. 
  * Level `5`, AP: `2`, Ob: `Opposed by Toughness`, Ranged, ST, Innate
  * `≤ 1` Hit: `4` Freezing
  * `= 2` Hits: `6` Freezing
  * `≥ 3` Hits: `8` Freezing
* **Doubting Gaze** (Arc/Arc):
  * Instill doubt into a ST, who begins to question their right to existence. If successful, the target is [Pacified](./strive-core.md#pacified) for `1` Round. 
  * Level: `5`, AP: `2`, Ob: `Opposed by Self-Control`, Ranged, ST, Innate
* **Sickening Gaze** (Arc/Arc):
  * A victim starts feeling incredibly sick, to the point they must throw up. 
  * Level: `5`, AP: `2`, Ob: `Opposed by Toughness`, Ranged, ST, Innate
  * `≤ 1` Hit: `2` Poison; `+1` Strain
  * `= 2` Hits: `3` Poison; `+1` Strain
  * `≥ 3` Hits: `4` Poison; `+2` Strain
* **Lamenting Gaze** (Arc/Arc):
  * All targets in a `10` Square AoE cone are stricken with inconsolable emptiness, their soul is briefly drawn from their body, before it snaps back into place. Can only be used after all othr Gazes have been used at least once before. 
  * Level: `5`, AP: `3`, Ob: `1`, Ranged, AoE, Innate
  * `≤ 1` Hit: `4` Pure; Self `+10` HP
  * `= 2` Hits: `6` Pure; Self `+15` HP
  * `≥ 3` Hits: `8` Pure; Self `+20` HP
