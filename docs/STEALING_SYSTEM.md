# Plant Stealing System Design

## Overview

The **Plant Stealing System** is the core competitive mechanic of Steal a Plant, directly inspired by Steal a Brainrot. Players can enter other players' bases and steal their plants, creating risk, reward, and strategic gameplay.

## How Stealing Works

### Basic Stealing Mechanics

**Same as Steal a Brainrot**:
1. **Approach another player's base**
2. **If base is open/unlocked** - you can enter
3. **Walk into the base** to start stealing
4. **Click/interact with plants** in flower pots to steal them
5. **Stolen plants** transfer to your inventory/base
6. **Other player loses** the stolen plant
7. **Risk of being stolen from** while your base is open

### Stealing Requirements

To steal from a base:
- ✅ Base must be **unlocked/open**
- ✅ Must contain **plants to steal**
- ✅ You must be **within the base area**
- ❌ **Cannot steal** from closed/locked bases
- ❌ **Cannot steal** from empty pots

## Base Lock/Unlock System

### How Locking Works

**Lock Your Base**:
- Click a button/interact with lock object
- Base becomes **closed/protected**
- **Nobody can enter** to steal
- **Visual indicator** shows base is locked (door closed, fence up, etc.)
- **You also cannot collect** plants from your conveyor while locked

**Unlock Your Base**:
- Click button/interact again to unlock
- Base becomes **open/vulnerable**
- **You can collect** plants from conveyor
- **Others can steal** from you
- **Visual indicator** shows base is open (door open, fence down, etc.)

### Strategic Decisions

**When to Lock**:
- Going AFK (away from keyboard)
- Have valuable plants you want to protect
- Just collected rare/mutated plants
- Leaving to steal from others
- Taking a break

**When to Unlock**:
- Actively playing and watching your base
- Need to collect plants from conveyor
- Building up your collection
- Confident you can defend/scare off thieves

## Stealing Limitations & Balance

### Anti-Grief Measures

To prevent stealing from being too frustrating:

**Suggested Limitations** (TBD - adjust during testing):

1. **Steal Cooldown**
   - Can only steal one plant every X seconds
   - Prevents instant robbery of entire base
   - Example: 2-5 second cooldown between steals

2. **Steal Speed**
   - Takes time to steal each plant
   - Progress bar or animation
   - Gives base owner chance to notice and lock base
   - Example: 3 seconds to steal one plant

3. **Protected Slots** (Optional)
   - First X slots cannot be stolen
   - Or certain special plants are "locked" to base
   - Ensures you never lose EVERYTHING

4. **Notification System**
   - Alert when someone enters your base
   - Sound effect or visual warning
   - Chance to lock base before major theft

5. **Stealing Penalty** (Optional)
   - Lose some money if caught stealing?
   - "Karma" system - steal too much, face consequences?
   - Or pure risk-free stealing (like Steal a Brainrot)

### Steal Value Calculation

What's worth stealing?

**High Value Targets**:
- Rare plants (Epic, Legendary, Mythic, Divine, OG)
- Mutated plants (especially Gold, Diamond, Rainbow)
- Plants that earn lots of money per second
- Full bases (lots to steal)

**Low Value Targets**:
- Common/Uncommon plants
- Non-mutated plants
- Bases with few plants
- Bases you've already stolen from recently

**Risk Assessment**:
- Is base owner active? (might lock base mid-steal)
- Is it worth the time? (could be farming your own conveyor)
- Will they steal back from you?

## Stealing Strategy & Gameplay

### Offensive Strategies

**Aggressive Stealing**:
- Constantly roam map looking for open bases
- Steal from everyone possible
- Fast progression through theft
- Risk: Make enemies, targets on your back

**Selective Stealing**:
- Only steal high-value plants
- Target offline/AFK players
- Minimize risk, maximize reward
- More strategic approach

**Opportunistic Stealing**:
- Steal when you happen to see open base
- Balance between farming and stealing
- Don't focus only on theft

### Defensive Strategies

**Always Locked**:
- Keep base locked except when actively collecting
- Safest approach
- Slower progression (less collection time)

**Monitored Unlocked**:
- Keep base open while watching carefully
- Lock immediately if someone approaches
- Maximizes collection while minimizing theft risk
- Requires active attention

**Bait Base**:
- Leave base open with only common plants
- Hide valuable plants or keep locked elsewhere
- Waste thieves' time
- Psychological warfare

**Revenge Stealing**:
- Remember who stole from you
- Steal back when opportunity arises
- Settling scores
- Eye for an eye

## PvP Dynamics

### Player Interactions

**Emergent Gameplay**:
- **Rivalries** - Players who keep stealing from each other
- **Alliances** - "Don't steal from me, I won't steal from you"
- **Territories** - Claiming certain bases as "yours"
- **Hunting** - Targeting specific players with good plants

**Social Dynamics**:
- Chat trash talk
- Reputation (known thief vs honest farmer)
- Server politics
- Community drama (entertaining for content!)

### Competitive Elements

**Who's the Best Thief?**
- Leaderboard for most plants stolen
- Achievement for stealing rare plants
- "Master Thief" title

**Who's the Best Defender?**
- Leaderboard for least plants lost
- "Impenetrable Base" achievement
- Bragging rights

## Integration with Other Systems

### Stealing and Rebirths

**Rebirth Advantages in PvP**:
- Faster plant earning = quicker recovery from theft
- Better plants = more tempting target BUT faster replacement
- High rebirth players less affected by stealing

**Stealing Strategy by Rebirth**:
- Low rebirth: Be careful, each plant matters
- High rebirth: Less concerned, fast recovery
- Creates natural balance

### Stealing and Mutations

**Mutation Theft**:
- Rainbow plants extremely valuable to steal
- Risk vs reward: steal Rainbow or let it go?
- Emotional impact (losing rare mutation hurts!)

**Mutation Protection**:
- Players extra protective of mutated plants
- Lock base immediately after getting Rainbow
- Target selection: steal mutations from others

### Stealing and Events

**Event Stealing Bonuses**:
- During Saturday events, admins could:
  - Make all bases unlockable (chaos mode!)
  - Remove steal cooldowns (fast stealing!)
  - Spawn notification when rare plant stolen
  - Stealing competitions (most stolen wins prize)

## Visual & Audio Feedback

### Stealing Indicators

**For the Thief**:
- Cursor changes when hovering over stealable plant
- Progress bar when stealing
- Satisfying sound effect when theft completes
- Visual effect (plant disappears from pot)
- Notification "Stole [Plant Name]!"

**For the Victim**:
- Alert sound when someone enters base
- Notification "[Player] is in your base!"
- Visual indicator on screen (warning icon)
- Notification when plant is stolen "Lost [Plant Name]!"
- Sad/alarm sound effect

**For Observers**:
- Server announcement for rare plant thefts?
- "Player X stole Rainbow Divine from Player Y!"
- Creates drama and excitement

### Base Lock Visuals

**Locked Base**:
- Door/gate closed
- Red glow or force field
- Padlock icon above base
- Cannot enter or click inside

**Unlocked Base**:
- Door/gate open
- Green glow or no barrier
- Open lock icon
- Can freely enter and interact

## Technical Considerations

### Server & Anti-Cheat

**Prevent Exploits**:
- Server-side validation of all stealing
- Cannot steal from locked bases (server check)
- Cannot steal too fast (cooldown enforced server-side)
- Cannot teleport plants without proper stealing
- Log all thefts for admin review

**Performance**:
- Efficient collision detection for base boundaries
- Optimized notifications (don't spam)
- Rate limiting on theft attempts

### Data Persistence

**Saving Theft Data**:
- Update both players' data immediately
- Handle disconnects gracefully (mid-theft)
- Prevent duplication exploits
- Backup/rollback for bugs

## Balancing Philosophy

### Making Stealing FUN, Not Frustrating

**Good Stealing System**:
- ✅ Exciting risk/reward decisions
- ✅ Comebacks possible after being robbed
- ✅ Strategic depth (when to lock, when to steal)
- ✅ Creates memorable moments
- ✅ Encourages active gameplay

**Bad Stealing System**:
- ❌ Lose everything instantly, no recovery
- ❌ No counterplay or protection options
- ❌ Discourages playing the game
- ❌ Pure griefing with no purpose
- ❌ Pay-to-win protection

**Our Goal**:
- Follow Steal a Brainrot's proven formula
- Add unique plant-themed flair
- Ensure new players aren't completely discouraged
- Keep high-level players engaged
- Balance protection and vulnerability

## Testing Checklist

Before launch, verify:

- [ ] Can successfully steal from open bases
- [ ] Cannot steal from locked bases
- [ ] Lock/unlock button works reliably
- [ ] Cooldowns prevent spam stealing
- [ ] Notifications alert base owner
- [ ] Stolen plants transfer correctly
- [ ] No duplication bugs
- [ ] Visual/audio feedback works
- [ ] Feels fair and fun (playtest!)
- [ ] Similar feel to Steal a Brainrot

## Future Enhancements

Potential additions to stealing system:

**Advanced Protection**:
- Alarms that auto-lock base when thief detected
- Guard NPCs/pets that scare off thieves
- Insurance system (get compensation for stolen plants)

**Advanced Stealing**:
- Stealth mode (silent stealing, no notifications)
- Hacking mini-game to unlock bases
- Disguises or invisibility (temporary items)

**Stealing Events**:
- "Purge" hour where all bases forced unlocked
- Double steal speed event
- "Steal-proof" challenge (keep base open for 10 min)

**Stealing Achievements**:
- "Master Thief" - Steal 1000 plants
- "Robin Hood" - Steal from rich, give to poor
- "Never Stolen" - Play 10 hours without losing a plant
- "Revenge" - Steal back from someone who stole from you

---

**Status**: System designed based on Steal a Brainrot mechanics
**Balance Priority**: Fun and engaging, not frustrating
**Technical Priority**: Prevent exploits and cheating
**Last Updated**: October 2025
**Platform**: Roblox Studio
