# Economy & Balancing Guide

## Overview

This document helps balance the game economy - prices, earnings, and progression. The goal is to keep the game fun and engaging without being too easy or too hard.

## Balancing Goals

### Player Experience
- **Early Game (0-30 min)**: Quick progress, frequent purchases, immediate rewards
- **Mid Game (30 min - 2 hours)**: Strategic choices, saving for better plants
- **Late Game (2+ hours)**: Long-term goals, rare collection completion
- **End Game**: Mutation hunting, perfect collection, flex achievements

### Economic Principles
1. **Exponential Growth**: Each rarity should cost ~3-5x more than previous
2. **Fair Returns**: Higher investment = better earnings (but not too fast)
3. **Compound Growth**: More plants = faster growth = more plants
4. **Rare Value**: Rarest items should feel special and worth the wait

## Suggested Plant Pricing

### Example Pricing Curve

| Rarity | Base Price | Earnings/Sec | Time to Earn Back |
|--------|-----------|--------------|-------------------|
| Common | 10 | 0.5 | 20 seconds |
| Uncommon | 50 | 3 | 17 seconds |
| Rare | 250 | 18 | 14 seconds |
| Epic | 1,500 | 125 | 12 seconds |
| Legendary | 10,000 | 1,000 | 10 seconds |
| Mythic | 75,000 | 8,500 | 9 seconds |
| Plant God | 600,000 | 75,000 | 8 seconds |
| Secret | 5,000,000 | 700,000 | 7 seconds |
| Divine | 50,000,000 | 7,500,000 | 7 seconds |
| OG (Pastel de Nata) | 500,000,000 | 85,000,000 | 6 seconds |

*Note: These are EXAMPLE numbers - adjust based on gameplay testing!*

### Pricing Philosophy
- **Pay-back time decreases** with rarity (better ROI for rare plants)
- **Encourages upgrading** to rarer plants
- **Creates prestige** for expensive plants
- **Requires strategy** about when to upgrade vs. buy more

## Mutation Multipliers

### Important: Mutations Only Affect Earnings!

**Mutations DO NOT change purchase price** - only earnings per second increase!

### Suggested Earnings Multipliers

| Mutation | Purchase Price | Earnings Multiplier |
|----------|---------------|---------------------|
| None | Base Price | 1x |
| Silver | Base Price (same!) | 2x |
| Gold | Base Price (same!) | 5x |
| Diamond | Base Price (same!) | 12x |
| Rainbow | Base Price (same!) | 30x |

### Mutation Value Examples
Example: Rare plant (250 base price, 18/sec base earnings)

| Mutation | Price | Earnings/Sec | Value Proposition |
|----------|-------|--------------|-------------------|
| None | 250 | 18 | Standard |
| Silver | **250** | 36 | Same price, 2x earnings! |
| Gold | **250** | 90 | Same price as unmutated! |
| Diamond | **250** | 216 | Incredible value! |
| Rainbow | **250** | 540 | Amazing deal! |

**Key Insight**:
- Mutated plants are ALWAYS worth buying (same price, better earnings!)
- Rainbow Common (10 cost, 15/sec) could earn MORE than unmutated Epic (1500 cost, 125/sec)!
- Makes mutations extremely valuable and exciting to find

## Spawn Rates

### Balancing Spawn Probability

#### Plant Rarity Spawns
Suggested spawn rates (must total 100%):

| Rarity | Spawn Rate | Approx. Time Between Spawns* |
|--------|-----------|------------------------------|
| Common | 40% | Every 2-3 plants |
| Uncommon | 25% | Every 4 plants |
| Rare | 15% | Every 6-7 plants |
| Epic | 10% | Every 10 plants |
| Legendary | 5% | Every 20 plants |
| Mythic | 3% | Every 33 plants |
| Plant God | 1.5% | Every 66 plants |
| Secret | 0.3% | Every 333 plants |
| Divine | 0.15% | Every 666 plants |
| OG | 0.05% | Every 2000 plants |

*Assuming other rarities also spawn

#### Mutation Spawn Rates
Independent chance for each plant:

| Mutation | Spawn Rate | Approx. Time Between* |
|----------|-----------|----------------------|
| Silver | 5% | Every 20 plants |
| Gold | 1% | Every 100 plants |
| Diamond | 0.2% | Every 500 plants |
| Rainbow | 0.05% | Every 2000 plants |

*For any rarity plant

### Spawn Rate Philosophy
- Common plants keep action flowing
- Rare plants create excitement
- Mutations add surprise factor
- Ultra-rare spawns are special events

## Progression Curve

### Starting Resources
- **Starting Money**: 100 (enough for 10 Common plants)
- **Starting Base Slots**: 10 pots
- **First Goal**: Fill all slots with Common plants

### Early Goals (First 30 minutes)
1. Buy 10 Common plants (100 coins)
2. Wait for money to accumulate
3. Upgrade to Uncommon plants
4. Expand base slots
5. Save for first Rare plant

### Mid Game Goals (30 min - 2 hours)
1. Replace Common with Uncommon/Rare
2. Unlock more base slots (25, 50, 100?)
3. Save for first Epic or Legendary
4. Start hunting mutations
5. Build diverse collection

### Late Game Goals (2+ hours)
1. Fill base with Epic+ plants
2. Hunt for mutated rare plants
3. Complete collection of all rarities
4. Save for Mythic/Plant God/Secret
5. Chase perfect mutations

### End Game Goals (Ongoing)
1. Obtain Divine plants
2. Hunt for the OG plant
3. Get Rainbow mutations on all plants
4. Complete 100% collection
5. Max out base size
6. Ultimate goal: Rainbow Pastel de Nata

## Monetization (Optional)

If you decide to add game passes or purchasable items:

### Game Pass Ideas
- **Auto-Clicker**: Automatically purchase plants
- **Mutation Boost**: Increased mutation spawn rate
- **Lucky Touch**: Better rare plant spawn rate
- **Extra Slots**: More base capacity
- **VIP Status**: Special perks, exclusive area

### Pricing Philosophy
- **Never pay-to-win**: Free players can get everything
- **Time savers only**: Purchases speed up, not unlock
- **Fair pricing**: Reasonable Robux costs
- **Support development**: Help fund updates

## Balancing Testing

### What to Test
1. **Time to First Rare**: Should be achievable in first session
2. **Time to First Legendary**: Should require commitment but feel achievable
3. **Time to Divine/OG**: Should be long-term goal (days/weeks)
4. **Mutation Discovery Rate**: Should see at least Silver in first hour
5. **Player Retention**: Are players coming back?

### Adjustment Indicators

#### Too Easy
- Players reach end-game in hours
- No excitement for rare spawns
- Economy inflates too quickly
- Boredom sets in fast

#### Too Hard
- Players stuck on Common for too long
- Never see rare plants
- Frustration with slow progress
- Players quit before getting hooked

#### Just Right
- Constant sense of progression
- Excitement when rare plants spawn
- Strategic decisions matter
- Players return for more

## Formula Reference

### Quick Balance Formulas

**Price Multiplier Between Tiers**:
```
Next_Price = Current_Price × (4 to 5)
```

**Earnings Multiplier Between Tiers**:
```
Next_Earnings = Current_Earnings × (5 to 7)
```

**Payback Time**:
```
Payback_Time = Price ÷ Earnings_Per_Second
```

**Total Earnings with N Plants**:
```
Total_Per_Second = Sum(All_Plants × Their_Earnings)
```

**Time to Afford Plant**:
```
Time = (Target_Price - Current_Money) ÷ Current_Earnings_Per_Second
```

## Testing Checklist

Before launch, verify:
- [ ] Can afford first plant upgrade within 5 minutes
- [ ] See at least 1 Epic plant in 30 minutes
- [ ] See at least 1 mutation (any type) in 15 minutes
- [ ] Can expand base at reasonable pace
- [ ] Late-game goals still feel achievable
- [ ] Economy doesn't break with mutations
- [ ] No exploits or money glitches
- [ ] Progression feels rewarding

## Community Feedback

After launch, monitor:
- Player progression speed
- Common complaints (too slow/fast)
- Which rarities are seen as "worth it"
- Mutation excitement level
- Player retention metrics
- Economic inflation over time

Be ready to adjust based on real player data!

---

**Status**: Example values provided, requires testing
**Priority**: Balance for fun, not just math
**Remember**: You can always adjust after launch!
**Last Updated**: October 2025
