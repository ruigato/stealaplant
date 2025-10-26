# Frequently Asked Questions (FAQ)

## Game Design Questions

### Q: How many plants should we create for each rarity?
**A**: Start with 3-5 plants per rarity tier. You can always add more later! Having variety is nice, but it's better to launch with fewer high-quality plants than many rushed ones.

### Q: Should all plants be completely unique or can some be variations?
**A**: Mix of both! For common plants, variations are fine (different colored flowers). For rare/legendary plants, make them more unique and special.

### Q: What if we want to change the rarities later?
**A**: That's okay! During testing, you might find some plants are too common or too rare. Adjusting is part of game development. Just update your documentation.

### Q: Can we add new rarities beyond these 10?
**A**: Sure, but be careful about power creep. Maybe add new rarities as special events or seasonal additions rather than making the system too complex at launch.

---

## Economy Questions

### Q: How do we know if prices are balanced?
**A**: Testing! Have friends play and watch:
- Are they stuck too long at one rarity?
- Do they feel excited about upgrades?
- Is progression too fast or too slow?
- Adjust based on feedback!

### Q: What if the economy breaks (too much money)?
**A**: You can patch this! Options:
- Adjust earnings rates in an update
- Add money sinks (expensive cosmetics, base upgrades)
- Reset economy (last resort, players won't like this)

### Q: Should we add a prestige/rebirth system?
**A**: Good idea for later! Not necessary at launch. Add it once players reach "end game" to give them a reason to keep playing.

---

## Technical Questions

### Q: We don't know how to code in Lua. Where do we start?
**A**: Great resources:
1. **Roblox Developer Hub**: https://create.roblox.com/docs
2. **YouTube tutorials**: Search "Roblox Lua tutorial for beginners"
3. **AlvinBlox**: Popular Roblox tutorial YouTuber
4. **Practice**: Make small test projects first

### Q: How do we make the conveyor belt move?
**A**: Two main methods:
1. **TweenService**: Smoothly move plants along
2. **CFrame manipulation**: Update position in a loop
Search "Roblox conveyor belt tutorial" for specific guides!

### Q: How many players can be in one server?
**A**: You decide! Recommended:
- **Start**: 10-20 players per server
- **Test**: How does it perform?
- **Adjust**: Increase if performance is good
More players = more lag but more social

### Q: Can we make it work on mobile?
**A**: Yes! Roblox works on mobile by default, but:
- Test UI on phone screens (small!)
- Make buttons bigger for touch
- Optimize performance (reduce particles on mobile)
- Add mobile controls if needed

### Q: What about data saving?
**A**: Very important! Players need to keep their plants and money when they leave. Learn about:
- **DataStoreService** (Roblox's save system)
- **Auto-save** (save every few minutes)
- **On leave save** (save when player exits)
- **Error handling** (what if save fails?)

---

## YouTube/Events Questions

### Q: What if nobody enters the giveaway?
**A**: At first, entries will be low. Strategies:
- **Share with friends/family** (they can enter and share)
- **Post in Portuguese Roblox communities**
- **Be patient** (growth takes time)
- **Make great content** (people will come!)

### Q: What if we can't do events every Saturday?
**A**: That's okay! Options:
- **Skip a week** (announce in advance)
- **Schedule differently** (monthly instead?)
- **Have a team rotation** (different admins host)
- **Consistency is ideal but life happens!**

### Q: What should we do if the event winner is inappropriate/rude?
**A**: Have rules ready:
- **Remove them from the server** (you're the admin)
- **Pick a new winner** (have backup)
- **Block from future events** if necessary
- **Stay professional** (don't engage with drama)
- **Record events** (proof if needed)

### Q: Do we need parent permission for YouTube?
**A**: **YES!** Since you're under 13 or a minor:
- Get parent/guardian permission
- They should manage the account
- Follow YouTube's terms of service
- Stay safe online

### Q: What if our videos don't get views?
**A**: Normal at first! Tips:
- **Good titles** (clear, interesting)
- **Thumbnails** (bright, eye-catching)
- **Consistent uploads** (regular schedule)
- **Promote** (share links appropriately)
- **Patience** (channels take time to grow)

---

## Pastel de Nata (OG Plant) Questions

### Q: Why "Pastel de Nata" as the rarest plant?
**A**: Perfect choice because:
- Iconic Portuguese symbol
- Instantly recognizable
- Shows national pride
- Unique to your game
- Fun cultural reference

### Q: Can we have multiple OG plants?
**A**: Up to you! Options:
- **Just Pastel de Nata** (makes it ultra special)
- **Add more OG tier** (other Portuguese foods/symbols?)
  - Francesinha
  - Bacalhau
  - Galo de Barcelos
  - Cork (Cortiça)

### Q: Should the Pastel de Nata plant actually look like the pastry?
**A**: Recommended approach:
- **Inspired by** but still plant-like
- Use the colors (golden, cream, caramel)
- Capture the "essence"
- Make it beautiful, not literal
- Players should recognize the reference

---

## Gameplay Questions

### Q: Should we add trading between players?
**A**: Great feature but maybe not at launch:
- **Phase 1**: Get core game working
- **Phase 2**: Add trading in an update
- **Consider**: Scamming prevention, trade UI, value balance

### Q: What about plant fusion or breeding?
**A**: Awesome idea for future updates!
- Combine two plants → new plant?
- Breeding for better mutations?
- Special recipes?
Add after core game is stable.

### Q: Should rare plants appear in a special way?
**A**: Yes! Make them exciting:
- **Special sound effect** when legendary+ spawns
- **Server announcement** for mythic and above
- **Different particle effect** when they fall
- **Rainbow appear** for OG plant

### Q: Can players lose plants?
**A**: **Not recommended** for this type of game:
- Players like collecting
- Losing progress feels bad
- Could make players quit
- If you want stakes, add optional "risky" features

---

## Community Questions

### Q: What if people copy our game?
**A**: Unfortunately common on Roblox:
- Focus on **being the original**
- **Build your community** (loyal players)
- **Keep updating** (stay ahead of copycats)
- **Your personality/events** can't be copied
- **Report blatant copies** to Roblox if appropriate

### Q: Should we have a Discord server?
**A**: Helpful but not required:
- **Pros**: Better community interaction, announcements, feedback
- **Cons**: More to moderate, requires time
- **Recommendation**: Wait until you have 100+ active players
- **Parent permission needed** (Discord is 13+)

### Q: How do we handle negative feedback?
**A**: Part of game development:
- **Listen**: Some criticism is helpful
- **Separate**: Constructive vs. just mean
- **Don't take personally**: Not everyone will like everything
- **Learn**: Improve based on valid points
- **Ignore trolls**: Some people just like being negative

### Q: What if players find bugs/exploits?
**A**: Will happen! Response plan:
1. **Thank reporter** (encourage reporting)
2. **Fix ASAP** (especially if game-breaking)
3. **Test fix** (don't break other things)
4. **Update game** (push patch)
5. **Announce** (show you're responsive)

---

## Money/Monetization Questions

### Q: Should we add game passes or microtransactions?
**A**: Your choice! Considerations:
- **Free to play**: Build player base first
- **Fair only**: Don't make it pay-to-win
- **Time savers**: Auto-collect, mutation boost, etc.
- **Cosmetics**: Custom base decorations?
- **Support**: Help fund updates and servers

### Q: How much money can we make?
**A**: Honest answer - **probably not much at first**:
- Most Roblox games don't make money
- Success requires luck + quality + marketing
- Focus on **learning and fun** first
- If it succeeds, great bonus!
- Don't expect to get rich

### Q: Do we need to pay for anything?
**A**: Minimal costs:
- **Roblox Studio**: FREE
- **Publishing game**: FREE
- **Private servers** (for events): ~100 Robux/month
- **Premium payout**: Free players give less, but it's fine
- **Optional**: Commission artists, buy assets

---

## Safety Questions

### Q: Is it safe to interact with players online?
**A**: With precautions:
- **Never share**: Real name, address, school, phone
- **Parent supervision**: Especially for events
- **Privacy settings**: Limit who can contact you
- **Report**: Inappropriate behavior immediately
- **Record**: Events and interactions (for safety)

### Q: What information should we share publicly?
**A**: Safe to share:
- First names only (Joaquim is fine)
- "Portugal" as location (don't say city/town)
- Ages (general, like "12 years old" is okay)
- Interests (gaming, Roblox, etc.)

**NEVER share**:
- Last names
- Specific location
- School name
- Phone numbers
- Social media accounts (personal)
- Meeting locations

### Q: What if someone asks to meet in person?
**A**: **NEVER!** And:
- **Tell a parent/guardian** immediately
- **Block the person**
- **Report to Roblox**
- **Screenshot evidence**
- This is a serious red flag

---

## Getting Started Questions

### Q: Where do we start?
**A**: Suggested order:
1. **Finish plant drawings** (all rarities)
2. **Finalize prices/earnings** (balance on paper first)
3. **Learn basic Roblox Studio** (tutorials)
4. **Build prototype** (simplest version)
5. **Test with team** (find issues)
6. **Iterate** (improve and expand)
7. **Launch** (when ready, not rushed!)

### Q: How long will this take?
**A**: Honest timeline:
- **Learning Roblox**: 2-4 weeks
- **Building MVP**: 4-6 weeks
- **Full game**: 2-4 months
- **Polished launch**: 4-6 months

**Don't rush!** Quality takes time.

### Q: What if we get stuck?
**A**: Resources for help:
1. **Roblox DevForum**: https://devforum.roblox.com
2. **YouTube tutorials**: Specific problems
3. **Discord communities**: Roblox developer servers
4. **Ask each other**: Team collaboration
5. **Break it down**: Solve one small piece at a time

### Q: Can we hire someone to code it for us?
**A**: You could, but:
- **Expensive**: Good developers cost Robux/money
- **Learning opportunity lost**: You won't understand your own game
- **Recommendation**: Learn together as a team!
- **Compromise**: Maybe hire for specific hard parts later

---

## Success Questions

### Q: How do we know if our game is successful?
**A**: Success metrics:
- **Fun**: Are YOU having fun playing it?
- **Friends**: Do friends want to play?
- **Players**: Are people playing regularly?
- **Retention**: Do players come back?
- **Community**: Are people talking about it?

Money and fame aren't the only measures!

### Q: What if the game fails/flops?
**A**: That's okay! Because you still:
- **Learned**: Roblox development, coding, teamwork
- **Created**: Something from nothing
- **Tried**: Which is more than most people
- **Improved**: Skills you can use on next project
- **Had fun**: Hopefully!

Most successful developers failed many times first.

### Q: Should we make a sequel or new game?
**A**: Decision tree:
- **Game doing well**: Keep updating, don't abandon it
- **Game okay**: Maybe add huge update/revamp
- **Game flopped**: Learn from it, try new concept
- **Time**: A sequel is basically a new game, same effort

---

## Final Advice

### Q: Any last tips?
**A**: Yes!

1. **Have Fun**: This should be enjoyable!
2. **Be Patient**: Good things take time
3. **Stay Safe**: Online safety is important
4. **Learn Together**: Help each other
5. **Be Creative**: Your ideas make it special
6. **Don't Give Up**: Challenges are normal
7. **Be Proud**: You're creating something!
8. **Portuguese Pride**: Represent your country well!
9. **Iterate**: First version won't be perfect
10. **Enjoy the Journey**: The process is the reward

---

## Need More Help?

### Roblox Resources
- **Developer Hub**: https://create.roblox.com/docs
- **DevForum**: https://devforum.roblox.com
- **YouTube**: AlvinBlox, TheDevKing, Russcode

### Game Design Resources
- YouTube: Game design principles
- Study successful Roblox games
- Play lots of games (research!)

### Ask Your Parents/Teachers
- They can help!
- Especially with technical or safety questions
- They might have useful skills

---

**Remember**: Every expert was once a beginner. You're learning valuable skills that will help you for years to come!

**Good luck with Steal a Plant!** 🌱🎮

**Status**: FAQ compiled and ready
**Last Updated**: October 2025
**You've got this!** 🇵🇹
