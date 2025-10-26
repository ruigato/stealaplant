# Mutation System Design

## Overview

Plants in Steal a Plant can undergo **mutations** that change their appearance, value, and earnings. Mutations are rare variants that make plants more valuable and desirable to collectors.

## Mutation Types

There are **4 mutation tiers**, from most common to rarest:

### 1. Silver 🥈
- **Visual**: Silver/metallic sheen overlay
- **Mutation Rate**: TBD (Most common mutation)
- **Price Multiplier**: TBD (e.g., 2x base price)
- **Earnings Multiplier**: TBD (e.g., 2x base earnings)
- **Rarity**: Uncommon mutation

### 2. Gold 🥇
- **Visual**: Golden/yellow metallic overlay
- **Mutation Rate**: TBD (Rare mutation)
- **Price Multiplier**: TBD (e.g., 5x base price)
- **Earnings Multiplier**: TBD (e.g., 5x base earnings)
- **Rarity**: Rare mutation

### 3. Diamond 💎
- **Visual**: Crystal/diamond sparkle effect
- **Mutation Rate**: TBD (Very rare mutation)
- **Price Multiplier**: TBD (e.g., 10x base price)
- **Earnings Multiplier**: TBD (e.g., 10x base earnings)
- **Rarity**: Very rare mutation

### 4. Rainbow 🌈
- **Visual**: Multicolor/rainbow shifting effect
- **Mutation Rate**: TBD (Ultra rare mutation)
- **Price Multiplier**: TBD (e.g., 25x base price)
- **Earnings Multiplier**: TBD (e.g., 25x base earnings)
- **Rarity**: Ultra rare mutation, the ultimate variant

## How Mutations Work

### Mutation Occurrence
1. When a plant spawns from the trees, there's a chance it's mutated
2. Mutation type is rolled independently (Silver → Gold → Diamond → Rainbow)
3. Higher tier mutations override lower tiers if multiple are rolled
4. Mutations are visible on the plant while on the conveyor belt

### Mutation Stacking
- **Only ONE mutation per plant**
- Mutations do NOT stack (can't have Silver + Gold)
- Rainbow is the "best" mutation, overriding all others

### Visual Effects
Each mutation adds a distinct visual overlay to the base plant design:
- **Silver**: Metallic silver tint, subtle shine
- **Gold**: Golden glow, sparkle particles
- **Diamond**: Crystal facets, bright reflections, sparkle effect
- **Rainbow**: Color-shifting hue, rainbow trail effect

## Economic Impact

### Price Scaling
Mutations significantly increase plant purchase price:

| Mutation | Price Impact | Example (100 coin plant) |
|----------|--------------|--------------------------|
| None | Base Price | 100 coins |
| Silver | 2-3x | 200-300 coins |
| Gold | 5-7x | 500-700 coins |
| Diamond | 10-15x | 1,000-1,500 coins |
| Rainbow | 25-50x | 2,500-5,000 coins |

*Note: Exact multipliers to be determined during balancing*

### Earnings Scaling
Mutations also boost money generation per second:

| Mutation | Earnings Impact | Example (10/sec plant) |
|----------|-----------------|------------------------|
| None | Base Earnings | 10/sec |
| Silver | 2-3x | 20-30/sec |
| Gold | 5-7x | 50-70/sec |
| Diamond | 10-15x | 100-150/sec |
| Rainbow | 25-50x | 250-500/sec |

*Note: Exact multipliers to be determined during balancing*

## Mutation Rates

### Probability Distribution
The spawn rate for each mutation should be balanced to maintain rarity:

```
Suggested Rate Structure (TBD):
- Silver: ~5-10% chance
- Gold: ~1-2% chance
- Diamond: ~0.1-0.5% chance
- Rainbow: ~0.01-0.05% chance
```

### Rarity Interaction
- Mutation rates should be **independent of plant rarity**
- A Common plant can be Rainbow (though very rare)
- A Divine plant can be unmutated
- This creates interesting collection goals (e.g., "Rainbow Common" vs "Unmutated Divine")

## Strategy & Gameplay

### Player Decisions
Mutations create interesting choices:
- **Mutated Common** vs **Unmutated Rare**: Which is better value?
- **Save up** for mutated rare plants or **buy many** unmutated plants?
- **Complete collection** or **focus on mutations**?

### Collection Goals
Mutations expand collection objectives:
- Collect all base plants
- Collect all plants in Silver
- Collect all plants in Gold
- Collect all plants in Diamond
- Collect all plants in Rainbow (ultimate goal!)

### Trading Value (Future)
If trading is implemented:
- Mutations increase trade value significantly
- Rainbow variants of rare plants = most valuable trades
- Creates player-driven economy

## Special Cases

### OG Plant Mutations
The **Pastel de Nata** (OG tier) can also mutate:
- **Rainbow Pastel de Nata** = Rarest possible item
- Ultimate collection achievement
- Extremely high value and earnings

### Event Mutations (Future Possibility)
Potential special mutation types for events:
- Event-specific color schemes
- Temporary mutations during events
- Special effects for admin event participants

## Visual Design Guidelines

### Mutation Overlays
- Must be clearly visible on conveyor belt
- Should not obscure base plant design
- Consistent effect style across all plants
- Animated for Gold, Diamond, and Rainbow

### UI Indicators
- Clear labels in player index
- Color-coded borders or backgrounds
- Mutation icon next to plant name
- Sorting/filtering options by mutation type

## Technical Considerations

### Performance
- Particle effects should be optimized
- Too many Rainbow plants on screen = potential lag
- Consider LOD (Level of Detail) for distant plants
- Mobile device compatibility

### Randomization
- Fair RNG (Random Number Generation)
- Server-side validation to prevent exploits
- Consistent mutation rates across all servers
- Anti-cheat measures for mutation manipulation

## Future Enhancements

Potential additions:
- **Mutation Boosters**: Items that increase mutation chances temporarily
- **Mutation Reroll**: System to reroll a plant's mutation
- **Custom Mutations**: Special mutations for VIPs or event winners
- **Mutation Fusion**: Combine mutations in special ways
- **Seasonal Mutations**: Holiday-themed variants

---

**Status**: System designed, rates to be determined during testing
**Balance Priority**: Ensure mutations are desirable but not mandatory
**Last Updated**: October 2025
