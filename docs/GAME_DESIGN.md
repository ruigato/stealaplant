# Steal a Plant - Game Design Document

## Overview

**Steal a Plant** is a competitive Roblox collecting game inspired by Steal a Brainrot. Players claim bases, collect plants, steal from other players, and progress through rebirths. The game features a mutation system, various rarities, and weekly community events.

## Core Gameplay Loop

1. **Claim a base** - Choose one of 6 available bases in the map
2. **Plants spawn** from two trees in front of your base and fall onto a grass conveyor belt
3. **Collect plants** from the conveyor belt to add to your base
4. **Plants generate money** over time based on rarity and mutations
5. **Steal plants** from other players' bases (like Steal a Brainrot)
6. **Protect your base** by closing it when away
7. **Use money** to buy more plants, upgrades, and rebirths
8. **Rebirth** to gain permanent bonuses and prestige

## Game World

### Map Layout
- **6 Bases Total** - Limited number of bases in each server
- **First-come-first-serve** - Players claim available bases
- **Spread across map** - Bases positioned around the map area
- **Garden environment** - Natural, plant-themed world

### Individual Base System
Each base includes:

**Spawn Area (Per Base)**
- **Two large trees** in front of each base
- Plants fall from the trees onto that base's conveyor belt
- Each base has its own independent plant spawn

**Conveyor Belt System (Per Base)**
- **Material**: Grass (instead of traditional metal/rubber)
- Plants travel along the grass conveyor to the end
- Each base has its own conveyor belt
- Only spawns plants for that specific base

**Base Structure**
- **Material**: Wooden base with flower details/decorations
- **Storage Slots**: Flower pots (vasos) where plants are placed
- **Expandable**: Players can buy more plant slots
- **Each pot can hold one plant**
- **Lock/Unlock System**: Players can close their base to prevent stealing

**Truck System (Per Base)**
- **Location**: End of each base's conveyor belt
- **Function**: Collects unclaimed plants
- **Capacity**: 1,000 plants
- **Behavior**: When full, truck leaves and a new empty truck arrives immediately

### Base Claiming
- When joining a server, players select an available base
- If all 6 bases are taken, player must wait or join another server
- Claimed base persists while player is in server
- Base becomes available when player leaves

## Core Mechanics

### Plant Stealing System
Inspired by Steal a Brainrot's mechanics:

**How Stealing Works**
- **Walk into another player's base** to start stealing
- **Same mechanics as Steal a Brainrot** - familiar gameplay
- **Steal plants** from their pots one by one
- **Stolen plants** go to your base/inventory
- **Risk vs Reward** - better plants = more valuable to steal

**Base Protection**
- **Close/Lock Base** - Prevents other players from entering
- **Open Base** - Required to collect your own plants from conveyor
- **Strategic Decision** - Lock when away, unlock when farming
- **Visual Indicator** - Shows if base is open or closed

**Stealing Limitations** (TBD - adjust for balance)
- Cooldown between steals?
- Can't steal from closed bases
- Some plants too valuable to steal easily?
- Anti-grief measures (can't lose everything instantly)

### Rebirth System
Progression system inspired by Steal a Brainrot:

**How Rebirths Work**
- **Cost**: Significant amount of money/progress
- **Effect**: Reset your base and plants
- **Benefit**: Gain permanent bonuses/multipliers
- **Prestige**: Higher rebirth = status symbol

**Rebirth Benefits** (TBD - specific values)
- Increased earnings multiplier
- Better plant spawn rates
- Rare mutation chances increase
- Exclusive plant access at higher rebirths
- Visual prestige (special base decorations, effects)

**Rebirth Tiers** (Suggestions)
1. First Rebirth - Small bonuses, introduction to system
2. Early Rebirths (2-10) - Steady progression
3. Mid Rebirths (11-50) - Committed players
4. High Rebirths (51+) - Elite players
5. Special Milestones (100, 500, 1000) - Unique rewards

## Player Progression

### Index System
- Player's personal collection of all plants they own
- Shows:
  - Plant name and rarity
  - Mutation status (if any)
  - Money earned per second
  - Total owned of each type
  - Collection completion percentage

### Economy
- Plants generate money per second
- Money is used to:
  - Collect more plants from your conveyor
  - Expand your base (more pot slots)
  - Purchase rebirths
  - Buy upgrades (TBD)
- Mutation status affects plant value and earnings
- Rebirth multipliers boost all earnings
- (Specific pricing and earnings rates in development)

## Visual Style

### Art Direction
- Hand-drawn plant designs created by the development team
- Colorful, friendly aesthetic
- Portuguese influences
- Garden/nature theme throughout

### Base Aesthetics
- **Different from Steal a Brainrot**: Custom wooden design
- Flower decorations and details
- Flower pots as plant containers
- Natural, organic look

## Inspiration

Based on **Steal a Brainrot** with plant theme:
- **Same core mechanics**: Base claiming, stealing, rebirths
- **Same stealing system**: Walk into bases to steal plants
- **Same rebirth concept**: Reset for permanent bonuses
- **Different theme**: Plants instead of brainrots
- **Different visual style**: Garden/nature aesthetic with Portuguese touches
- **Custom base designs**: Wooden bases with flower pots
- **Unique content**: Hand-drawn plants, mutations, OG tier

## Target Audience

- **Primary**: Kids and teens (10-15 years old)
- **Region**: Portugal (but playable worldwide)
- **Language**: English (for international reach)
- **Interest**: Collecting games, idle games, Roblox community

## Unique Selling Points

1. **Familiar Mechanics, New Theme**: Steal a Brainrot gameplay with plants
2. **Portuguese Origin**: Made by Portuguese students, for the world
3. **Hand-Drawn Plants**: Original artwork from the development team
4. **Mutation System**: 4-tier mutation system (Silver, Gold, Diamond, Rainbow)
5. **Weekly Events**: YouTube-integrated community events every Saturday
6. **OG Rarity**: "Pastel de Nata" as ultimate plant (Portuguese cultural tribute)
7. **Custom Aesthetics**: Wooden bases with flower pots instead of generic design
8. **Competitive Stealing**: Player vs player plant theft mechanics
9. **Rebirth Progression**: Prestige system for long-term engagement

## Future Considerations

- **Trading system** between players (safe trade UI)
- **Special seasonal plants** (Christmas, Halloween, etc.)
- **Base customization** (different wood types, flower decorations)
- **Leaderboards** (richest, most rebirths, best collection)
- **Achievement system** (collect all rarities, reach rebirth milestones)
- **Plant fusion/combination** mechanics (breed new plants?)
- **PvP stealing events** (special stealing tournaments)
- **Clan/Team system** (share bases with friends?)
- **VIP/Game passes** (auto-collector, mutation boosts, extra base slots)

## Key Differences from Steal a Brainrot

While heavily inspired, Steal a Plant includes:

| Feature | Steal a Brainrot | Steal a Plant |
|---------|------------------|---------------|
| **Theme** | Brainrots | Plants (nature/garden) |
| **Visual Style** | TBD | Hand-drawn art, Portuguese flair |
| **Base Design** | Generic | Wooden with flower pots |
| **Conveyor** | Standard | Grass-themed |
| **Rarest Tier** | TBD | OG tier (Pastel de Nata) |
| **Mutations** | TBD | 4-tier system with visual effects |
| **Community** | TBD | YouTube integration, weekly events |
| **Cultural Identity** | TBD | Portuguese origin and references |

---

**Document Version**: 2.0
**Last Updated**: October 2025
**Status**: Design Phase (Updated with stealing/rebirth mechanics)
**Platform**: Roblox Studio
