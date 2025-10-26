# Rebirth System Design

## Overview

The **Rebirth System** is a prestige mechanic inspired by Steal a Brainrot that allows players to reset their progress in exchange for permanent bonuses and multipliers. This creates long-term progression and gives dedicated players goals to work toward.

## How Rebirths Work

### The Rebirth Process

1. **Reach Required Level** - Accumulate enough money/progress
2. **Access Rebirth Menu** - Special UI button or NPC
3. **Confirm Rebirth** - Warning about reset (can't undo!)
4. **Reset Happens** - Lose current progress
5. **Gain Bonuses** - Permanent multipliers applied
6. **Start Fresh** - Begin again with advantages

### What Gets Reset

When you rebirth, you **LOSE**:
- ❌ All your money (back to starting amount)
- ❌ All plants in your base (empty pots)
- ❌ Base expansions (back to starting slots)
- ❌ Temporary upgrades (if any)

### What You Keep

After rebirth, you **KEEP**:
- ✅ Rebirth count (your prestige level)
- ✅ Permanent multipliers from all previous rebirths
- ✅ Your plant index/collection record (for bragging rights)
- ✅ Achievement progress
- ✅ Exclusive unlocks from rebirth milestones

### Why Rebirth?

**Permanent Bonuses** make future progress faster:
- Earn money **MUCH faster** with multipliers
- Better chance for **rare plants** and **mutations**
- Unlock **exclusive plants** only available at high rebirths
- **Prestige and status** - show you're a dedicated player
- **Leaderboard rankings** - compete for highest rebirth count
- Eventually earn more in 10 minutes than you did in hours before

## Rebirth Benefits

### Core Multipliers

Each rebirth grants permanent bonuses:

| Bonus Type | Example Value | Effect |
|------------|---------------|--------|
| **Money Multiplier** | +10% per rebirth | Plants earn more money/second |
| **Spawn Rate Boost** | +5% per rebirth | Rarer plants spawn more often |
| **Mutation Chance** | +2% per rebirth | Higher chance for mutations |
| **Starting Money** | +1000 per rebirth | Start with more money after reset |

*Note: These are EXAMPLE values - adjust during balancing!*

### Example Progression

**Rebirth 0 (No rebirths yet)**
- Common plant earns: 0.5/sec
- Epic spawn rate: 10%
- Silver mutation: 5% chance
- Starting money: 100

**Rebirth 5**
- Money multiplier: 1.5x (50% more)
- Common plant earns: 0.75/sec
- Epic spawn rate: 12.5%
- Silver mutation: 7% chance
- Starting money: 5,100

**Rebirth 20**
- Money multiplier: 3x (200% more!)
- Common plant earns: 1.5/sec
- Epic spawn rate: 20%
- Silver mutation: 12% chance
- Starting money: 20,100

**Rebirth 100** (Dedicated player!)
- Money multiplier: 11x (1000% more!)
- Common plant earns: 5.5/sec
- Epic spawn rate: 60%
- Silver mutation: 27% chance
- Starting money: 100,100

## Rebirth Cost

### Cost Structure

The cost to rebirth should **increase** with each rebirth to maintain challenge:

**Suggested Formula** (adjust as needed):
```
Rebirth Cost = BaseAmount × (Multiplier ^ CurrentRebirths)

Example:
Base Amount = 10,000
Multiplier = 1.5

Rebirth 1 cost: 10,000
Rebirth 2 cost: 15,000
Rebirth 3 cost: 22,500
Rebirth 4 cost: 33,750
Rebirth 5 cost: 50,625
...
Rebirth 10 cost: 576,650
Rebirth 20 cost: 33,306,690
```

### Alternative: Fixed Tier Costs

Or use fixed costs per tier:

| Rebirth Range | Cost |
|---------------|------|
| Rebirth 1-10 | 10,000 each |
| Rebirth 11-25 | 100,000 each |
| Rebirth 26-50 | 1,000,000 each |
| Rebirth 51-100 | 10,000,000 each |
| Rebirth 100+ | 100,000,000 each |

Choose the system that feels best during testing!

## Rebirth Tiers & Milestones

### Tier System

**Beginner Rebirths (1-10)**
- Learning the rebirth mechanic
- Small but noticeable bonuses
- Relatively quick to achieve
- First milestone rewards at Rebirth 1, 5, 10

**Intermediate Rebirths (11-50)**
- Committed players
- Significant multipliers stack up
- Special plants unlock
- Milestones at 25, 50

**Advanced Rebirths (51-100)**
- Dedicated players
- Elite status in community
- Very high multipliers
- Exclusive cosmetics/effects
- Milestones at 75, 100

**Master Rebirths (101-500)**
- Hardcore players
- Insane multipliers
- Ultimate prestige
- Milestones at 250, 500

**Legendary Rebirths (500+)**
- The ultimate grind
- Top of leaderboards
- Maximum bragging rights
- Special title/badge at 1000

### Milestone Rewards

Special rewards at key rebirth counts:

| Milestone | Reward |
|-----------|--------|
| **Rebirth 1** | Achievement badge, first-time bonus |
| **Rebirth 5** | Special plant unlock or base decoration |
| **Rebirth 10** | Exclusive base color/theme option |
| **Rebirth 25** | Rare plant guaranteed in next 100 spawns |
| **Rebirth 50** | Golden base effect, special title |
| **Rebirth 75** | Exclusive emote or particle effect |
| **Rebirth 100** | Diamond base effect, "Century Club" badge |
| **Rebirth 250** | Rainbow base effect, special chat color |
| **Rebirth 500** | Legendary title, exclusive plant variant |
| **Rebirth 1000** | Ultimate achievement, hall of fame |

## Visual Prestige

### Rebirth Indicators

Players should be able to **show off** their rebirth count:

**Visual Effects on Base**
- Bronze glow (Rebirths 1-10)
- Silver glow (Rebirths 11-25)
- Gold glow (Rebirths 26-50)
- Diamond sparkle (Rebirths 51-100)
- Rainbow aura (Rebirths 101-250)
- Cosmic effect (Rebirths 251+)

**Player Name Tag**
- Display rebirth count next to username
- Special color coding by tier
- Badges or icons for milestones

**Base Customization**
- Unlock new base materials at rebirth milestones
- Special flower decorations for high rebirths
- Exclusive pot designs
- Particle effects around base

## Strategic Considerations

### When to Rebirth?

Players must decide optimal timing:

**Rebirth Early Strategy**
- Reset frequently for fast multiplier stacking
- Reach high rebirth counts quickly
- Accept slower short-term progress for long-term gains

**Rebirth Late Strategy**
- Push for complete collection before resetting
- Enjoy current power level longer
- Maximize each run before reset

**Balanced Strategy**
- Rebirth when progress slows significantly
- Set goals (e.g., collect all Epics, then rebirth)
- Maintain steady progression

### Rebirth and Stealing

Interesting dynamics with the stealing mechanic:

**High Rebirth Advantages**
- Earn plants back quickly after being stolen from
- Can afford better base locks/protection
- Fast progression makes stealing less impactful

**Low Rebirth Vulnerabilities**
- Slower to recover from being robbed
- Tempting to steal from (they have good plants!)
- May need to focus on protection

**Stealing Strategy**
- Steal from lower rebirth players (slower recovery)
- Or target high rebirths (better plants)
- Risk vs reward decisions

## Rebirth Leaderboards

### Competitive Rankings

**Rebirth Count Leaderboard**
- Who has the most rebirths?
- Resets monthly/seasonally or all-time
- Rewards for top 10/100 players

**Speed Run Leaderboard**
- Fastest time to reach Rebirth milestones
- "Rebirth 10 Speedrun" category
- "Rebirth 100 Speedrun" category

**Wealth Leaderboard (Per Rebirth)**
- Richest player at Rebirth 0
- Richest player at Rebirth 1
- Etc. (separate categories)

## Balance Considerations

### Avoiding Power Creep

**Be careful not to make early game too easy**:
- New players should still have challenge
- High rebirth players shouldn't get everything instantly
- Diminishing returns at very high rebirths?

**Suggested Balance**:
- First 10 rebirths: Strong impact
- Rebirths 11-50: Moderate impact
- Rebirths 51-100: Smaller impact but still meaningful
- Rebirths 100+: Mostly for prestige, minor bonuses

### Testing Checklist

Before finalizing rebirth values, test:

- [ ] Does Rebirth 1 feel rewarding?
- [ ] Is the grind to rebirth reasonable?
- [ ] Do multipliers make progress noticeably faster?
- [ ] Can high rebirth players still enjoy the game?
- [ ] Is there a reason to keep rebirthing past 100?
- [ ] Are milestones exciting?
- [ ] Does it feel fair compared to Steal a Brainrot?

## Integration with Other Systems

### Rebirths and Mutations

**Mutation Boost**
- Higher rebirths = better mutation rates
- Makes Rainbow plants more achievable
- Creates goal: "Get Rainbow OG at Rebirth 100"

### Rebirths and Events

**Event Benefits**
- High rebirth players get bonus rewards in events?
- Or events help lower rebirth players catch up?
- Special events for Rebirth 50+ players only?

### Rebirths and Collections

**Collection Persistence**
- Index remembers what you've collected across rebirths
- "Collected 100 Divine plants total" (across all rebirths)
- Achievement: "Collect all plants at Rebirth 10+"

## Future Enhancements

Potential additions to rebirth system:

**Rebirth Tokens**
- Earn special currency per rebirth
- Spend on exclusive items
- Can't be obtained any other way

**Rebirth Paths**
- Choose bonus type (money vs spawn rate vs mutations)
- Specialize your rebirth build
- Different strategies for different players

**Seasonal Rebirths**
- Special seasonal rebirth events
- Limited-time multipliers
- Exclusive seasonal rewards

**Rebirth Prestige Tiers**
- Beyond normal rebirths
- Ultra-hard mode
- For the most dedicated players

---

**Status**: System designed, values need testing and balancing
**Inspiration**: Steal a Brainrot rebirth system
**Balance Priority**: Should feel rewarding but not make game too easy
**Last Updated**: October 2025
