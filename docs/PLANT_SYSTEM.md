# Plant System Design

## Overview

The plant system is the core of Steal a Plant. Players collect plants of various rarities, each with different spawn rates, prices, and earnings.

## Rarity Tiers

The game features **10 distinct rarity tiers**, from most common to most rare:

### 1. Common
- **Color Scheme**: White/Gray
- **Spawn Rate**: TBD
- **Base Price**: TBD
- **Earnings/Second**: TBD
- **Description**: Starter plants, easy to obtain

### 2. Uncommon
- **Color Scheme**: Green
- **Spawn Rate**: TBD
- **Base Price**: TBD
- **Earnings/Second**: TBD
- **Description**: Slightly better than common plants

### 3. Rare
- **Color Scheme**: Blue
- **Spawn Rate**: TBD
- **Base Price**: TBD
- **Earnings/Second**: TBD
- **Description**: Valuable plants that spawn less frequently

### 4. Epic
- **Color Scheme**: Purple
- **Spawn Rate**: TBD
- **Base Price**: TBD
- **Earnings/Second**: TBD
- **Description**: High-value plants, harder to obtain

### 5. Legendary
- **Color Scheme**: Orange/Gold
- **Spawn Rate**: TBD
- **Base Price**: TBD
- **Earnings/Second**: TBD
- **Description**: Very rare and powerful plants

### 6. Mythic
- **Color Scheme**: Red/Pink
- **Spawn Rate**: TBD
- **Base Price**: TBD
- **Earnings/Second**: TBD
- **Description**: Extremely rare plants

### 7. Plant God
- **Color Scheme**: TBD
- **Spawn Rate**: TBD
- **Base Price**: TBD
- **Earnings/Second**: TBD
- **Description**: Godly tier plants, incredible rarity

### 8. Secret
- **Color Scheme**: TBD
- **Spawn Rate**: TBD
- **Base Price**: TBD
- **Earnings/Second**: TBD
- **Description**: Hidden plants with special unlock conditions

### 9. Divine
- **Color Scheme**: TBD
- **Spawn Rate**: TBD
- **Base Price**: TBD
- **Earnings/Second**: TBD
- **Description**: Divine-tier plants, near-impossible to obtain

### 10. OG (Original)
- **Special Plant**: **"Pastel de Nata"** 🥮
- **Color Scheme**: Golden/Cream (like the pastry)
- **Spawn Rate**: Ultra Rare
- **Base Price**: TBD (Very High)
- **Earnings/Second**: TBD (Highest)
- **Description**: The rarest plant in the game, a tribute to Portuguese culture
- **Cultural Significance**: Named after Portugal's famous custard tart pastry

## Plant Spawning

### Spawn Mechanism
1. Plants spawn randomly from the **two trees** at the spawn point
2. They fall from the trees onto the grass conveyor belt
3. Plants travel along the belt until purchased or reaching the truck

### Spawn Rate System
- Each rarity has its own spawn probability
- Higher rarities spawn less frequently
- Spawn rates balance gameplay progression
- (Exact rates to be determined during balancing phase)

## Plant Economics

### Pricing Structure
- **Base Price**: Cost to purchase plant from conveyor
- **Mutation Effect**: Mutations DO NOT change price (only earnings!)
- **Rarity Scaling**: Each tier is significantly more expensive than the previous

### Earnings System
- **Money per Second**: Each plant generates passive income
- **Rarity Impact**: Higher rarities earn more per second
- **Mutation Bonus**: Mutations increase earnings
- **Compound Growth**: More plants = more total income

### Economic Balance (In Development)
The team is currently working on:
- Individual plant prices for each rarity
- Earnings per second for each rarity
- Mutation earnings multipliers (price stays same!)
- Progression curve to keep gameplay engaging

## Plant Properties

Each plant has the following properties:

| Property | Description |
|----------|-------------|
| **Name** | Unique identifier for the plant |
| **Rarity** | One of the 10 tiers |
| **Base Price** | Cost to purchase |
| **Earnings/Sec** | Money generated per second |
| **Mutation** | None, Silver, Gold, Diamond, or Rainbow |
| **Visual Design** | Hand-drawn artwork by the team |

## Plant Index

### Player Collection
- Shows all plants the player has collected
- Displays quantity of each plant owned
- Shows total earnings from each plant type
- Filterable by rarity and mutation
- Tracks collection completion percentage

### Collection Goals
- Collect all rarities
- Obtain all mutations for each plant
- Complete the full plant catalog
- Special achievements for rare collections

## Special Plants

### Pastel de Nata (OG Tier)
The crown jewel of the collection:
- **Rarity**: OG (unique tier)
- **Theme**: Portuguese custard tart
- **Status Symbol**: Ultimate achievement
- **Cultural Touch**: Connects game to Portuguese heritage
- **Gameplay Impact**: Highest earnings, extremely rare

## Future Plant Features

Potential additions being considered:
- **Seasonal Plants**: Special plants for holidays/events
- **Evolution System**: Combine plants to create new species
- **Shiny Variants**: Extra rare color variations
- **Plant Abilities**: Special effects beyond money generation
- **Breeding System**: Combine two plants to create offspring

---

**Note**: Visual designs for plants are being created on paper by the development team and will be digitized for the game.

**Status**: Rarities defined, pricing and spawn rates in development
**Last Updated**: October 2025
