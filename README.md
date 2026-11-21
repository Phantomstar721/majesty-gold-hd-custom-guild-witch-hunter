# Custom Guild: Witch Hunters

Witch Hunters bring hand crossbows, hatchets, and silver to **Majesty Gold HD**. The mod adds the Chapterhouse guild, the Argent Crucible, nine research options, kingdom-wide plague control, the sovereign spell Breach the Den, and the Solarii spell Dawnfall.

[Buildings](#buildings) · [Hero stats](#witch-hunter) · [Hunter abilities](#hunter-abilities) · [Crucible research and fittings](#crucible-research-and-fittings) · [Plague control](#plague-control) · [Breach the Den](#breach-the-den) · [Solarii and Dawnfall](#solarii-and-dawnfall) · [Installation](#installation) · [Credits](#credits)

## Buildings

| Building | Level 1 cost / HP | Level 2 upgrade / HP | Level 3 upgrade / HP | Sight |
| --- | ---: | ---: | ---: | ---: |
| Chapterhouse | 800 gold / 350 HP | 1,500 gold / 500 HP | 2,500 gold / 700 HP | 175 |
| Argent Crucible | 500 gold / 250 HP | 600 gold / 300 HP | 800 gold / 400 HP | 100 |

Costs are the base amounts. Both buildings have a base income value of 40 at every tier.

- **Chapterhouse.** Requires a level 3 Palace. Each Chapterhouse houses up to four Witch Hunters at any tier. A Hunter costs **450 gold** to recruit and takes **12 seconds**. Each guild tier can recruit. A completed tier 2 unlocks Breach the Den in its Spells panel. A completed tier 3 enables the sovereign toolbar spell and lets eligible Solarii learn Dawnfall.
- **Argent Crucible.** Requires a Chapterhouse and is limited to one per kingdom. Upgrading is available immediately. To open its services, choose **Hire** and select a living Witch Hunter from your kingdom at **level 8 or higher**. Once she reaches the Crucible, she leaves adventuring and the guild permanently. This unlocks its Research and Fittings services and the Visitors view. You need a completed, staffed level 3 Crucible to use Plague Control.

## Witch Hunter

| Starting stat | Value | Starting stat | Value |
| --- | ---: | --- | ---: |
| Level | 1 | Max HP | 18 |
| Strength (primary) | 15 | Vitality | 14 |
| Artifice | 22 | Intelligence | 16 |
| Willpower | 18 | Magic Resistance | 20 |
| Melee attack skill | 75 | Ranged attack skill | 65 |
| Parry | 35 | Dodge | 45 |
| Base weapon damage | 7 | Base armor protection | 3 |
| Sight | 230 | Movement speed | 3 |
| Crossbow maximum range | 130 | Hatchet reach | 1 |
| Loyalty | 20 | Greed | 15 |
| Luck | 12 | Base experience value | 1,250 |

The Hunter buys **crossbow** and **leather armor** upgrades through ordinary equipment shopping. She uses her hand crossbow at range and automatically switches to her hatchet at melee distance. She finishes the attack already underway before switching. Melee attacks check Parry and crossbow attacks check Dodge. The weapon actions have rate intervals of 1.1 and 1.2 seconds, respectively. Range, movement, and projectile travel also affect when each hit lands.

### Level progression and behavior

- Each level gained adds **+2 melee attack** and **+1 ranged attack** regardless of the weapon she is holding. Both are capped at 98 through level progression. Normal level growth also adds **+1 Dodge** and **+1 Parry** up to 98, adds **+1 Strength** on reaching odd-numbered levels, and rolls for HP based on Vitality (**4–6 max HP per level** at the starting Vitality of 14). A fresh recruit reaches **89 melee / 72 ranged** at level 8 before other modifiers.
- Health-based retreat threshold is **35% below level 8** and **25% from level 8 onward**. She still uses Majesty's ordinary threat and retreat checks.
- Hunters prefer visible, viable **undead** and **enemies with an offensive spell**. The combat estimate uses a **1.2 self multiplier**, **1.0 for ordinary hostiles**, and **0.6 for those preferred threats**. Their hunting score also gives preferred prey a **+5** bonus. They still defend, respond to reward flags, shop, explore, rest, and can take Ranger-compatible quests. Library training is for Magic Resistance. Their Hunter abilities come from leveling and combat.
- Hunter abilities add **10 / 30 / 60 / 65** to combat confidence at levels **1 / 3 / 5 / 8** respectively. This informs AI evaluation and is separate from hit chance.

### Hunter abilities

| Learned | Ability | Trigger, effect, and duration |
| ---: | --- | --- |
| 1 | **Hunter’s Mark** | A successful crossbow or hatchet hit on the Hunter’s current living quarry reduces its **Dodge and Parry by up to 10 each** for **12 seconds**. Further hits refresh it. Multiple Hunters can keep the same quarry marked without stacking the penalties. The Hunter loses her personal mark when she breaks off or changes quarry. Buildings and lairs are excluded. |
| 3 | **Silver Bolt** | The next crossbow shot fired when ready carries silver and starts a **15-second recharge**, even if it misses. A hit removes **Magic Mirror** if present, otherwise **Damage Shield**, and applies **Silver Burn** to a surviving mobile target. Removing a protection adds no separate damage. The burn deals **2 damage every 2 seconds, three times** by default. Refined Silver raises the damage per tick to **3**, or **4 against undead**. Only one Silver Burn runs on a target at a time. |
| 5 | **Sundering Shot** | A successful crossbow hit makes the current quarry take **25% more damage for 6 seconds**. Further crossbow hits renew it. Living mobile targets only. |
| 5 | **Weakening Strike** | A successful hatchet hit makes the current quarry deal **25% less damage for 6 seconds**. Further hatchet hits renew it. Living mobile targets only. |
| 8 | **Witch Ward** | Triggers after the Hunter survives a direct damaging hit from **her own marked quarry**. For **6 seconds** she takes **30% less direct damage** and gains **+20 Magic Resistance**. The **12-second recharge** starts when the Ward triggers. The triggering hit has already dealt its damage. |

Sundering Shot and Weakening Strike share one slot on each target. The stronger effect wins. At equal strength, the latest successful hit replaces the other effect. Mark and Silver Burn are separate from that slot. The abilities are automatic. There is no sovereign cast button or additional gold cost for them.

## Crucible research and fittings

The player buys research with kingdom gold. After research completes, eligible heroes visit the Crucible and use their own gold to buy available items. **Research** and **Fittings** share one research slot. Both pages remain available while a job is running, and other rows wait for that job to finish.

| Crucible level | Page | Research | Research price | Hero price and eligibility | Effect |
| ---: | --- | --- | ---: | --- | --- |
| 1 | Research | **Silver Salts** | 200 gold | **60 gold**, any hero without a carried dose | A hero automatically uses a dose when infected with Ratman Plague, or on purchase if already infected. The dose is consumed, the plague is cured, and the hero gains **60 seconds of immunity**. The dose is an inventory item. Active protection appears under Enhancements. |
| 1 | Research | **Refined Silver** | 300 gold | Kingdom research | Strengthens Silver Bolt fired while the kingdom has the research. **3 damage per tick**, or **4 against undead**, up from 2. The primary burn still has three ticks at two-second intervals. |
| 1 | Fittings | **Nightglass Lenses** | 400 gold | **100 gold**, Witch Hunters | Permanent **+40 sight**, taking a base Hunter from **230 to 270**. |
| 2 | Research | **Silver Inlays** | 600 gold | **150 gold**, heroes who make weapon attacks | Ignores up to **2 points** of the armor protection that blocked a weapon hit, or **4 against undead**. Spell-only heroes cannot buy it. |
| 2 | Fittings | **Windlass Assembly** | 650 gold | **175 gold**, Witch Hunters | Permanent **+40 crossbow range**, from **130 to 170**. Hatchet reach stays at 1. |
| 2 | Research | **Argent Sunmace** | 750 gold | **250 gold**, Solarii | A successful damaging fire-spell hit charges the next successful melee hit with **+5 fire damage**, or **+10 against undead**. One charge at a time. Armor can block bonus damage, and fire-resistant targets consume the charge without taking the bonus. |
| 3 | Research | **Silver Bastion** | 600 gold | Kingdom research | When your **Guardhouse with researched arrows** hits an enemy unit, that enemy deals **25% less weapon damage to your buildings for 4 seconds**. |
| 3 | Fittings | **Embersteel Hatchet** | 750 gold | **200 gold**, Witch Hunters | A hatchet hit on the Hunter’s marked quarry consumes **her own** active Silver Burn and deals the **remaining tick damage plus 2** immediately. |
| 3 | Fittings | **Gravebind Silver** | 900 gold | **200 gold**, Witch Hunters | The Hunter’s Mark also reduces quarry movement speed by **20% for 12 seconds**. Hits from an equipped Hunter refresh the slow. It ends early if no equipped Hunter still owns the mark. |

Permanent purchases appear under the hero’s **Enhancements**. Refined Silver and Silver Bastion apply through kingdom research without a separate hero purchase. Silver Bastion and Weakening Strike use the larger applicable damage penalty when both would affect the same hit.

### Plague control

Both actions require a **completed level 3 Argent Crucible with a Witch Hunter employed**. Either action takes **30 simulation seconds** to execute. While it is charging, the other action is unavailable. Successful completion starts the same **five in-game day recharge** for both, displayed on the Plague panel.

| Action | Cost | Effect and requirements |
| --- | --- | --- |
| **Purge** | Free | Kills kingdom-owned mobile units currently infected with Ratman Plague, including heroes, henchmen, and owned monsters. |
| **Cleanse** | **5,000 gold and five reagents upfront** | Cures the same infected units. Requires an owned, completed **level 3 Alchemist Laboratory with Arcane Infusion** and a compatible Alchemist Lab mod. Cleanse provides no immunity and does not consume carried Silver Salts. |

Alchemist Lab is optional. Without its compatible support, the Cleanse row remains visible but unavailable. The rest of the guild, including Purge, works on its own.

## Breach the Den

| Cost | Duration | Where to cast | Valid target |
| ---: | ---: | --- | --- |
| **500 gold** | **3 minutes** | Spells panel on a completed **level 2 or higher** Chapterhouse. Sovereign spell bar with an owned completed **level 3** Chapterhouse. | A **living hostile monster lair**. |

Breach makes the lair more attractive to heroes in your kingdom and lets them deal **full normal weapon damage** to it instead of the usual half damage. It counts like a **500-gold incentive** when heroes decide what to attack. The cast has its own marker and effects. It creates no payable bounty, so the spell cost is the only automatic charge. An ordinary attack flag can still be placed on the same lair. Breach encourages a raid and leaves the decision to each hero.

## Solarii and Dawnfall

**Dawnfall** is an automatic Solarii travel spell. A Solarii learns it at **level 6 or higher** when her kingdom has a **completed level 3 Chapterhouse**. She can cast it outdoors when that Chapterhouse is available, the spell is ready, and her chosen enemy is **more than 100 game units away** with a valid exterior landing point.

- **Targets:** a living hostile mobile quarry currently marked by a Witch Hunter in her own kingdom, or a hostile lair affected by her kingdom’s Breach the Den. She can consider visible marked foes within **600 game units**. For lairs, she uses Dawnfall when approaching a target selected by ordinary lair or reward behavior.
- **Arrival:** she disappears in a Fire Strike effect, descends as a golden comet, lands near her target, and resumes the attack. Dawnfall is travel and deals no separate impact damage. The **30-second personal recharge** starts on a successful arrival. The shorter travel distance can make eligible targets more attractive to her AI.
- **Allied fire:** with an owned Chapterhouse at tier 2 or higher, a successful Solarii fire-spell hit can refresh an allied Hunter’s active primary Silver Burn **once per application**, restoring it to three remaining ticks after at least one has fired. **Sun Scorch** can also spread Silver Burn once from a marked, primarily burning target to other foes hit by the same cast who are not already burning. These secondary burns tick **twice**, at **half the source potency rounded down**, with a minimum of **1 damage per tick**.
- **Argent Sunmace:** successful damaging **Fire Hammer** or **Sun Scorch** hits charge the purchased fitting. Fire interactions require the spell to actually damage the target. Targets that resist fire do not trigger these bonuses.

Dawnfall adds to the Solarii’s existing spells and keeps their base stats, recruitment cost, and ordinary equipment unchanged.

## Installation

1. Install the playable Witch Hunters package through Steam Workshop.
2. Open [Majesty Mod Manager from Steam Workshop](https://steamcommunity.com/sharedfiles/filedetails/?id=3793024054) and install the required helpers if prompted.
3. Select Witch Hunters, choose **Prepare Selected Mods**, and launch Majesty through the Manager.

Use Mod Manager 0.3.15 beta or a compatible build. Start a new game when adding the guild to your mod list. This repository contains the guild’s editable gameplay source and configuration. Steam Workshop distributes the playable package, including the compiled resources.

## Credits

- Witch Hunter model by [Remos](https://remusprites.carbonmade.com/).
- Witch Hunter voice performed by [Char C](https://www.fiverr.com/chardoesva).
- [Sound effects, sources, and licenses](src/current/WitchHunterFourSkills/AUDIO-CREDITS.txt).
