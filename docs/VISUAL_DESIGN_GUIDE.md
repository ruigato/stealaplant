# Visual Design Guide

## Overview

This guide helps the team maintain consistent visual style throughout Steal a Plant. Use these guidelines when creating artwork, building in Roblox Studio, and designing UI.

## Art Style

### Overall Theme
- **Garden/Nature**: Everything feels natural and plant-themed
- **Colorful**: Bright, appealing colors
- **Friendly**: Welcoming to kids and teens
- **Hand-drawn Charm**: Your original art gives the game personality
- **Portuguese Touch**: Subtle nods to Portuguese culture

### Inspiration Sources
- Roblox adopt me (successful collecting game)
- Steal a Brainrot (inspiration game)
- Garden games
- Idle/clicker games
- Portuguese gardens and nature

## Color Palette

### Rarity Colors (Standard)
These colors help players instantly recognize plant value:

| Rarity | Primary Color | Secondary Color | Effect |
|--------|--------------|-----------------|--------|
| Common | White/Gray | Light Gray | Simple, plain |
| Uncommon | Green | Light Green | Natural |
| Rare | Blue | Light Blue | Cool, valuable |
| Epic | Purple | Pink/Magenta | Mystical |
| Legendary | Orange | Gold | Prestigious |
| Mythic | Red | Deep Pink | Powerful |
| Plant God | TBD | TBD | Godly |
| Secret | TBD | TBD | Mysterious |
| Divine | White/Gold | Light Blue | Celestial |
| OG | Golden/Cream | Brown | Pastel colors |

### Mutation Colors

| Mutation | Primary Effect | Accent |
|----------|---------------|--------|
| Silver | Metallic Silver | White shine |
| Gold | Metallic Gold | Yellow glow |
| Diamond | Crystal Clear | Rainbow refraction |
| Rainbow | Shifting Colors | All colors cycling |

### Environment Colors
- **Grass Conveyor**: Vibrant green (#2ecc71 or similar)
- **Wooden Base**: Warm brown (#8b4513 or similar)
- **Flower Details**: Various bright colors (red, yellow, pink, purple)
- **Trees**: Natural green with brown trunks
- **Sky**: Pleasant blue with white clouds

## Plant Design Guidelines

### Your Hand-Drawn Plants
- Keep drawings **clear and simple** (easy to see on screen)
- Use **bold outlines** (will show up better when digitized)
- Add **distinctive features** (each plant should be unique)
- Consider **how it looks small** (will be tiny on conveyor)
- Think about **color** (even if drawn in pencil now)

### Digitizing Your Drawings
When ready to put drawings in the game:

1. **Scan or Photograph**
   - Good lighting
   - Clear image
   - Straight angle
   - High resolution

2. **Digital Cleanup** (optional)
   - Trace in digital art software (like Paint.NET, Krita, or Photoshop)
   - Or use as-is for authentic hand-drawn look
   - Add colors
   - Remove background

3. **Size for Roblox**
   - Save as PNG with transparent background
   - Recommended: 512x512 pixels or 1024x1024
   - Keep file size reasonable

### Plant Personality
Give each plant character:
- **Common**: Simple, cute, basic
- **Uncommon**: A bit more detailed, friendly
- **Rare**: Beautiful, elegant
- **Epic**: Impressive, "wow" factor
- **Legendary**: Majestic, powerful looking
- **Mythic**: Otherworldly, magical
- **Plant God**: Godly, imposing
- **Secret**: Mysterious, intriguing
- **Divine**: Heavenly, ethereal
- **OG (Pastel de Nata)**: Delicious, iconic, prestigious

## World Design

### Map Layout & Base System

**6 Bases Configuration**:
```
Visual Description:
- 6 distinct base locations spread across the map
- Each base is identical in structure but positioned differently
- Enough space between bases to feel separate but not too far to walk
- Perhaps arranged in a circle or hexagon pattern?
- Central area or pathways connecting all bases
```

**Building Tips**:
- Symmetrical layout for fairness (no "best" base position)
- Clear visual markers for each base (numbered signs?)
- Mini-map showing all 6 base locations
- Walking distance: ~5-10 seconds between adjacent bases
- Consider terrain variety (some on hills, some flat, etc.)

**Base Claiming Visual**:
- **Unclaimed base**: Neutral appearance, gray or white
- **Claimed base**: Player's name displayed above
- **Your base**: Special highlight or glow
- **Other players' bases**: Different color coding
- Clear indication of which base belongs to who

### Individual Base Components

Each of the 6 bases includes all these elements:

### Spawn Area (Trees) - Per Base
```
Visual Description:
- Two large trees with thick trunks
- Leafy canopy where plants spawn
- Natural, welcoming area
- Perhaps some flowers around the base
- Grass ground
```

**Building Tips**:
- Use Roblox tree models or build custom
- Make trees tall enough to see plants fall
- Add particle effects for spawning plants
- Ensure good lighting in this area

### Grass Conveyor Belt - Per Base
```
Visual Description:
- Moving grass surface (not metal)
- Green, natural looking
- Wide enough for multiple plants
- Clear direction of movement
- Plants should be easily visible on it
- Each base has its own independent conveyor
```

**Building Tips**:
- Use Roblox TweenService or CFrame for movement
- Green baseplate with grass texture
- Add subtle animation (grass blowing?)
- Ensure plants don't fall through
- Each conveyor operates independently

### Wooden Base with Flower Pots - Per Base
```
Visual Description:
- Wooden platform/structure
- Flower decorations (vines, petals, etc.)
- Individual flower pots for each plant slot
- Expandable design (can add more pots)
- Warm, inviting look
```

**Building Tips**:
- Use brown wooden materials in Roblox
- Create flower pot models (cylinder + decorations)
- Grid layout for pots (organized look)
- Leave room for expansion
- Add small flower decorations around edges

### Base Lock/Unlock System

**CRITICAL VISUAL FEATURE** - Players must clearly see if a base is locked or unlocked:

**Locked Base Visual** 🔒:
```
Visual Description:
- Door/gate CLOSED in front of base
- Red glow or force field around base perimeter
- Padlock icon floating above base
- "LOCKED" text or sign
- Dark or muted colors
- Cannot see inside clearly (privacy)
```

**Building Tips**:
- Invisible wall/collision when locked (prevents entry)
- Tween animation when locking (door closing, shield appearing)
- Red particle effects or red transparent parts
- Sound effect when locking (click, thud)

**Unlocked Base Visual** 🔓:
```
Visual Description:
- Door/gate OPEN
- Green glow or no barrier
- Open padlock icon or no lock
- "OPEN" text or welcoming sign
- Bright, inviting colors
- Can clearly see plants inside (tempting!)
```

**Building Tips**:
- No collision when unlocked (free entry)
- Tween animation when unlocking (door opening, shield disappearing)
- Green particle effects or welcoming glow
- Sound effect when unlocking (unlock sound, chime)

**Lock/Unlock Button**:
```
Visual Description:
- Big, obvious button/lever at base entrance
- Toggle between locked/unlocked
- Color changes based on state (red=locked, green=unlocked)
- Icon shows current state
```

**Building Tips**:
- ProximityPrompt in Roblox for easy interaction
- Clear label: "Press E to Lock/Unlock"
- Feedback animation when pressed (button push down)
- Cooldown to prevent spam (1-2 seconds)

### Truck - Per Base
```
Visual Description:
- Plant transport truck
- Portuguese style (if possible)
- Bed/container for collecting plants
- Could have flower/plant decorations
- Friendly, cartoon look
```

**Building Tips**:
- Can use simple blocky truck design
- Green to match nature theme?
- Add wheels, cab, cargo area
- Particle effect when it leaves (dust cloud?)
- New truck should appear smoothly

## User Interface (UI) Design

### Main HUD (On-Screen Display)
```
Elements to Include:
- Player money (large, clear number)
- Earnings per second
- Plant count or collection progress
- Open Index button
- Settings button
```

**Design Tips**:
- **Top of screen**: Money and earnings
- **Bottom/Side**: Button to open Index
- **Clean fonts**: Easy to read
- **Nature theme**: Green backgrounds, leaf decorations
- **Not too intrusive**: Don't block the game view

### Plant Index (Collection Screen)
```
Elements to Include:
- Grid of all plants
- Name, rarity, mutation status
- Quantity owned
- Individual earnings
- Total collection stats
- Filter/sort options
- Close button
```

**Design Tips**:
- **Card-based layout**: Each plant has a card
- **Rarity color border**: Instant recognition
- **Mutation indicator**: Icon or glow effect
- **Scrollable**: For many plants
- **Search/filter**: By rarity, mutation, owned/not owned
- **Satisfying to browse**: Make collection feel rewarding

### Purchase UI
```
When hovering/clicking plant on conveyor:
- Plant name
- Rarity
- Price
- Earnings per second
- Purchase button
- Quick preview
```

**Design Tips**:
- **Quick to read**: Decisions must be fast
- **Color-coded**: Rarity color
- **Clear price**: Big, obvious
- **Buy button**: Easy to click
- **Show if can't afford**: Red or grayed out

### Rebirth UI
```
Elements to Include:
- Current rebirth count (displayed prominently)
- Cost to rebirth
- Bonuses you'll gain
- What you'll lose warning
- Confirm/Cancel buttons
```

**Design Tips**:
- **Big warning**: "You will lose all plants and money!"
- **Show benefits clearly**: +10% earnings, etc.
- **Confirmation dialog**: Prevent accidental rebirths
- **Rebirth badge**: Show current rebirth on screen always
- **Exciting animation**: When rebirth happens

### Stealing Notifications
```
Alert Types:
- "Player X entered your base!"
- "Player X stole [Plant Name]!"
- "Your base is being robbed!"
- "Base locked successfully"
```

**Design Tips**:
- **Urgent alerts**: Red color, alarm icon
- **Sound effects**: Attention-grabbing but not annoying
- **Quick action button**: "Lock Base Now!" in notification
- **Don't spam**: Combine multiple steals into one update
- **Visible but not intrusive**: Corner of screen

### Base Claiming UI
```
When joining server:
- Show all 6 bases on map
- Highlight available (unclaimed) bases
- Show claimed bases with owner names
- "Claim This Base" button
```

**Design Tips**:
- **Clear availability**: Green = free, Red = taken
- **Player names visible**: Know who's in each base
- **Easy selection**: Click base to claim
- **Confirmation**: "Are you sure?" before claiming
- **Show distance**: Which bases are close together

### Mini-Map
```
Elements:
- All 6 base locations
- Your base highlighted (bright color)
- Other players' bases (different color)
- Your current position
- Steal alerts (flashing icon if being robbed)
```

**Design Tips**:
- **Always visible**: Top corner of screen
- **Toggle on/off**: Button to hide if desired
- **Click to navigate**: See where bases are
- **Lock status icons**: Padlock icons on locked bases
- **Player dots**: Show where other players are currently

## Special Effects

### Particle Effects
Add excitement and polish:

| Effect | When Used | Description |
|--------|-----------|-------------|
| **Spawn Sparkle** | Plant spawns | Small sparkles when plant appears |
| **Purchase Flash** | Buy a plant | Brief flash/glow effect |
| **Money Earn** | Passive income | Coins floating up occasionally |
| **Mutation Glow** | Mutated plants | Continuous subtle glow |
| **Rainbow Trail** | Rainbow mutation | Color-shifting particle trail |
| **Truck Departure** | Truck leaves | Dust cloud or exhaust |
| **Steal Flash** | Plant stolen | Red flash/poof when plant taken |
| **Base Lock** | Locking base | Force field appearing animation |
| **Base Unlock** | Unlocking base | Force field disappearing |
| **Rebirth Explosion** | Rebirth | Huge impressive effect, reset visual |
| **Alert Pulse** | Being robbed | Red pulsing glow around base |

**Implementation Tips**:
- Don't overdo it (too many = lag)
- Optimize for mobile devices
- Allow settings to reduce effects
- Test with many plants on screen

### Animations
Bring the world to life:

| Animation | Element | Description |
|-----------|---------|-------------|
| **Idle Sway** | Plants | Gentle back-and-forth motion |
| **Fall** | Spawned plants | Drop from trees to conveyor |
| **Conveyor Move** | Belt | Smooth movement |
| **Money Pop** | UI | Number increase animation |
| **Button Bounce** | UI | Hover and click feedback |
| **Truck Drive** | Truck | Wheels turning, movement |
| **Door Close/Open** | Base lock | Smooth door animation for locking |
| **Plant Vanish** | Stealing | Plant disappears when stolen |
| **Rebirth Flash** | Rebirth UI | Screen flash and zoom effect |
| **Alert Shake** | Notifications | Shake animation when robbed |

## Portuguese Cultural Elements

### Pastel de Nata Plant (OG)
The special plant deserves special design:

**Visual Concept**:
- **Shape**: Round like the pastry, maybe with "petals" like flaky layers
- **Colors**: Golden yellow, cream white, caramelized brown on top
- **Details**: Perhaps cinnamon speckles?
- **Glow**: Special golden/cream aura
- **Size**: Slightly larger than other plants
- **Effect**: Delicious-looking!

**Cultural Accuracy**:
- Research what Pastel de Nata looks like
- Capture the essence (golden, creamy, prestigious)
- Make Portuguese players proud!
- Could add subtle Portuguese flag colors somewhere

### Optional Portuguese Touches
Other ways to add Portuguese flavor:

- **Azulejo Patterns**: Portuguese tile patterns on base decorations
- **Cork Elements**: Portugal's cork industry (cork oak tree?)
- **Colors**: Green and red (Portuguese flag) in decorations
- **Music**: Portuguese guitar (fado) in background music?
- **Plant Names**: Some plants with Portuguese names?
- **Event Decorations**: Portuguese festival themes

## Accessibility Considerations

### Colorblind Friendly
- Don't rely on color alone for rarity
- Use **icons** or **shapes** too
- **Text labels** always included
- Test with colorblind simulators

### Readability
- **Large fonts** for important info
- **High contrast** between text and background
- **Clear icons**: Not too detailed/confusing
- **Consistent layout**: Same info always in same place

### Mobile Friendly
- **Buttons big enough** to tap with finger
- **UI not too small** on phone screens
- **Test on mobile** before launch
- **Optimize performance** for phones

## Consistency Checklist

Before adding any visual element, check:
- [ ] Does it fit the nature/garden theme?
- [ ] Is it colorful and friendly?
- [ ] Does it work on mobile screens?
- [ ] Is it clear and easy to understand?
- [ ] Does it match other elements in style?
- [ ] Would it appeal to your target audience?
- [ ] Does it represent Portuguese creativity?

## Inspiration & References

### Games to Study (for ideas only - don't copy!)
- **Adopt Me**: UI design, collection system
- **Pet Simulator X**: Rarity effects, hatching
- **Tower Defense Simulator**: Clean UI
- **Idle games**: Progression feel

### Visual References
- **Real plants**: Look at actual flowers and plants
- **Portuguese gardens**: For authentic feel
- **Pastel de Nata photos**: For the OG plant
- **Color theory**: For pleasing color combinations

### Roblox Resources
- **Toolbox**: Pre-made models (be selective!)
- **Creator Marketplace**: Textures and decals
- **Developer Hub**: Tutorials for effects
- **YouTube**: Roblox building tutorials

---

## Your Unique Style

**Most Important**: Don't try to copy other games exactly. Your hand-drawn plants and Portuguese origin make this game special!

### What Makes Steal a Plant Unique:
✅ Your original plant drawings
✅ Portuguese cultural elements (Pastel de Nata!)
✅ Made by Portuguese students
✅ Wooden bases with flower pots (not generic)
✅ Grass conveyor (different from metal)
✅ Community events with YouTube integration

**Embrace these unique elements!** They're what will make players remember your game.

---

**Status**: Guidelines established, ready for creative implementation
**Remember**: Consistency is good, but creativity is better!
**Last Updated**: October 2025
**Make it beautiful!** 🎨🌱
