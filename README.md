# 🐾 PETTEOMOCHA 🐾

> **Your Digital Companion Awaits.** Experience the nostalgia of 90s virtual pets reimagined for the modern web. Raise, nurture, and watch your pet evolve into unique forms based on your care!

![Status](https://img.shields.io/badge/status-adorable-ff69b4.svg)
![Retro](https://img.shields.io/badge/aesthetic-90s_retro-9b59b6.svg)
![Evolution](https://img.shields.io/badge/evolution-6_forms-00ff00.svg)
![Games](https://img.shields.io/badge/mini--games-4-ffff00.svg)

---

## ✨ What Is This?

**PETTEOMOCHA** is a browser-based virtual pet simulator that combines the beloved mechanics of classic Tamagotchi-style games with modern web technology and a stunning retro aesthetic. Watch your pet grow from an egg through multiple life stages, each influenced by your care choices and interactions.

Built with pure HTML5, CSS3, and vanilla JavaScript—no frameworks, no dependencies, just pure nostalgic fun with CRT scanlines, pixel-perfect graphics, and that unmistakable 90s vibe.

---

## 🌟 Features

### 🥚 Life Cycle System
- **Egg Stage** - The beginning of your journey (Days 0-1)
- **Baby Stage** - Your pet hatches and needs constant care (Days 1-3)
- **Child Stage** - Personality begins to emerge (Days 3-7)
- **Teen Stage** - Evolution path is determined (Days 7-14)
- **Adult Stage** - Final evolution into unique forms (Day 14+)

### 📊 Complex Care System
**Primary Needs:**
- 🍖 **Hunger** - Feed your pet regularly or face the consequences
- ⚡ **Energy** - Rest is essential for growth
- 💖 **Happiness** - Play and interact to keep spirits high
- 🛁 **Hygiene** - Cleanliness prevents sickness
- 👥 **Social** - Your pet needs companionship
- 🔍 **Curiosity** - Explore and train to stimulate the mind

**Hidden Stats** (affect evolution):
- 🎓 Discipline
- 💝 Affection
- 🧠 Intelligence
- 🎨 Creativity
- 🦅 Independence

### 🎭 Personality System
Each pet has **3 random personality traits** that affect behavior:
- **LAZY** - Slower energy decay, less excited about play
- **ENERGETIC** - Faster energy decay, loves playing
- **PICKY EATER** - Gets less satisfaction from food
- **FOODIE** - Extra happiness from meals
- **NEAT FREAK** - Hygiene decays faster, happier when clean
- **SOCIAL BUTTERFLY** - Needs more social interaction
- **LONER** - Social needs decay slower
- **CURIOUS** - Curiosity stat grows faster
- **STUBBORN** - Less responsive to training
- **SENSITIVE** - More emotional reactions

### ✨ Evolution System

Your pet evolves into one of **6 unique forms** based on care history:

| Evolution Form | Requirements | Characteristics |
|---------------|--------------|-----------------|
| 🎓 **SCHOLAR** | High Discipline + Intelligence | Intellectual, wears glasses, loves learning |
| 🦋 **SOCIAL BUTTERFLY** | High Happiness + Social | Outgoing, colorful wings, loves company |
| 🗺️ **ADVENTURER** | High Independence + Curiosity | Explorer spirit, wears adventure hat |
| 🎨 **ARTIST** | High Affection + Creativity | Creative soul, wears beret, expressive |
| 🌑 **MYSTERIOUS** | Low Discipline + Low Affection | Dark appearance, enigmatic nature |
| ☯️ **HARMONIOUS** | Balanced stats | Well-rounded, peaceful disposition |

### 🎮 Mini-Games Collection

Boost your pet's stats through interactive games:

#### 🧠 MEMORY MATCH
- Match pairs of cards before time runs out
- **Duration:** 60 seconds
- **Pairs:** 8 to find
- **Boosts:** Intelligence +15, Happiness +10
- **Challenge:** Exercise your brain with your pet!

#### ⚡ REACTION TEST
- Click the moving target as fast as possible
- **Duration:** 30 seconds
- **Goal:** Maximum clicks
- **Boosts:** Energy +15, Happiness +5
- **Challenge:** Test your reflexes!

#### 🔍 MAZE RUNNER
- Navigate through a randomly generated maze
- **Duration:** 90 seconds
- **Controls:** Arrow keys to move
- **Boosts:** Curiosity +15, Happiness +10
- **Challenge:** Find your way to the exit!

#### 🎵 RHYTHM MASTER
- Press SPACE when notes cross the hit line
- **Duration:** 45 seconds
- **Combo System:** Build streaks for bonus points
- **Boosts:** Creativity +15, Happiness +10
- **Challenge:** Follow the beat!

### 🎨 Retro Aesthetic
- **Authentic 90s Design** - Outset borders, gradient backgrounds
- **CRT Effects** - Scanlines and screen glow
- **Pixel Art** - Hand-drawn pet animations
- **Neon Colors** - Cyan, magenta, yellow color scheme
- **Press Start 2P Font** - Classic gaming typography
- **Glitch Animations** - Nostalgic visual effects

### 💾 Save System
- **Auto-save** - Progress saved every minute
- **Manual Save** - Save button for peace of mind
- **LocalStorage** - No server needed, works offline
- **Persistent Data** - Your pet remembers you

---

## 🎯 Quick Start

### Just Want to Play?
1. Open `index.html` in any modern browser
2. Watch your egg appear
3. Start caring for your new digital companion
4. Check back regularly to keep your pet happy!

### First-Time Owners Guide
1. **Day 0-1:** Your egg will hatch within 24 hours (game hours)
2. **Days 1-3:** Baby stage - needs frequent feeding and attention
3. **Days 3-7:** Child stage - start building stats with mini-games
4. **Days 7-14:** Teen stage - your evolution path is decided here
5. **Day 14+:** Adult stage - see your pet's final form!

---

## 🎮 Controls & Actions

### Main Actions

| Button | Effect | When to Use |
|--------|--------|-------------|
| 🍖 **FEED** | +30 Hunger, +10 Happiness | When hungry or just for fun |
| 🎮 **PLAY** | +20 Happiness, -15 Energy | When pet needs entertainment |
| 🛁 **CLEAN** | +50 Hygiene, +10 Happiness | When dirty or sick |
| 😴 **SLEEP** | +50 Energy after 30s | When tired (triggers rest mode) |
| 💬 **TALK** | +15 Social, +0.5 Affection | For bonding and mood checks |
| 🎯 **TRAIN** | +10 Discipline, +5 Intelligence | To increase hidden stats |

### Menu Options

| Button | Function |
|--------|----------|
| 💾 **SAVE** | Manually save your progress |
| 📊 **STATS** | View detailed stats & evolution info |
| 🔄 **NEW PET** | Start over with a new egg |

---

## 🧮 Game Mechanics

### Stat Decay System

Stats naturally decrease over time:
```
Hunger:     -0.05/tick (faster decay = needs feeding often)
Energy:     -0.03/tick (slower decay = can play longer)
Happiness:  -0.02/tick (moderate decay = regular play needed)
Hygiene:    -0.015/tick (slow decay = cleaning every few hours)
Social:     -0.01/tick (slow decay = doesn't need constant attention)
Curiosity:  -0.005/tick (very slow = occasional training sufficient)
```

**Stage Multipliers:**
- Egg: 0.5× (very slow decay)
- Baby: 1.5× (high maintenance!)
- Child: 1.2× (still needy)
- Teen: 1.0× (balanced)
- Adult: 0.8× (more independent)

### Personality Trait Effects

Traits modify decay rates and interactions:
```javascript
LAZY:             -30% energy decay, -25% play effectiveness
ENERGETIC:        +30% energy decay, +50% play bonus
PICKY EATER:      +20% hunger decay, -33% feeding effectiveness
FOODIE:           +100% feeding happiness bonus
NEAT FREAK:       +50% hygiene decay, +100% cleaning satisfaction
SOCIAL BUTTERFLY: +40% social decay, +50% talk effectiveness
LONER:            -40% social decay, prefers solitude
CURIOUS:          +50% curiosity decay, loves training
STUBBORN:         +20% training difficulty, unique personality
SENSITIVE:        +50% emotional range, more expressive
```

### Sickness System

Your pet can get sick if:
- **Hunger < 20** → 5% chance per tick
- **Hygiene < 15** → 5% chance per tick

When sick:
- Pet's mood shows "sick" 🤒
- Stats decay faster
- Requires feeding + cleaning to recover
- 30-40% recovery chance per care action

### Mood States

Pet's mood changes based on stat thresholds:

| Mood | Trigger | Display |
|------|---------|---------|
| 😊 **HAPPY** | Default state (good stats) | Content and peaceful |
| 🤩 **EXCITED** | Happiness > 80, Energy > 60 | Full of energy! |
| 😄 **PLAYFUL** | Curiosity > 80 | Wants to play games |
| 😴 **TIRED** | Energy < 20 | Needs rest urgently |
| 😋 **HUNGRY** | Hunger < 20 | Needs food now! |
| 😢 **SAD** | Happiness < 30 | Needs cheering up |
| 😔 **LONELY** | Social < 30 | Needs attention |
| 🤢 **DIRTY** | Hygiene < 20 | Needs cleaning |
| 🤒 **SICK** | Health compromised | Requires care |
| 💤 **SLEEPING** | Sleep mode active | Resting peacefully |

### Time of Day System

The game tracks real-world time:
- ☀️ **DAY** (6 AM - 6 PM) - Bright background
- 🌅 **EVENING** (6 PM - 9 PM) - Warm tones
- 🌙 **NIGHT** (9 PM - 6 AM) - Dark background

---

## 🏗️ Technical Details

### Architecture

```
Single-File Application
├── HTML Structure
│   ├── Game Container
│   ├── Pet Display (Canvas)
│   ├── Stats Panel
│   ├── Actions Panel
│   ├── Mini-Games Panel
│   └── Chat Log
│
├── CSS Styling
│   ├── 90s Aesthetic (gradients, borders)
│   ├── CRT Effects (scanlines, glow)
│   ├── Animations (glitch, pulse, slide)
│   └── Responsive Design (mobile-friendly)
│
└── JavaScript Logic
    ├── Pet Class (stats, traits, evolution)
    ├── Game Class (UI, save/load, actions)
    ├── Canvas Renderer (pet drawing)
    ├── Mini-Game Engines
    └── State Management
```

### Canvas Rendering

Each life stage has unique hand-drawn appearance:
- **Egg:** Oval shape with cracks appearing
- **Baby:** Round body with antenna, simple eyes
- **Child:** Larger body with arms, expressive face
- **Teen:** Humanoid form, legs appear, more detail
- **Adult:** Full features, evolution-specific accessories

Evolution forms add special details:
- Scholar: Glasses
- Social Butterfly: Colorful wings
- Adventurer: Explorer hat
- Artist: Painter's beret
- Mysterious: Dark aura
- Harmonious: Balanced appearance

### Save Data Structure

```javascript
{
  name: "PETTEO",
  stage: "adult",
  age: 15,
  born: 1699999999999,
  
  // Primary stats
  hunger: 85,
  energy: 92,
  happiness: 78,
  hygiene: 88,
  social: 71,
  curiosity: 95,
  
  // Hidden stats
  discipline: 68,
  affection: 82,
  intelligence: 75,
  creativity: 88,
  independence: 59,
  
  // Status
  mood: "happy",
  isSleeping: false,
  isSick: false,
  
  // Evolution
  evolutionPath: "ACTIVE",
  evolutionForm: "SOCIAL BUTTERFLY",
  
  // Personality
  traits: ["ENERGETIC", "FOODIE", "CURIOUS"]
}
```

---

## 🎨 Customization

### Modify Pet Names
```javascript
// Line 1177: Change default name
constructor() {
    this.name = "YOUR_NAME_HERE"; // Default: "PETTEO"
    ...
}
```

### Adjust Decay Rates
```javascript
// Line 1333: Modify stat decay
decay() {
    let hungerDecay = 0.05;    // Increase = faster hunger
    let energyDecay = 0.03;    // Increase = tires quicker
    let happinessDecay = 0.02; // Increase = needs more play
    ...
}
```

### Change Evolution Requirements
```javascript
// Line 1243: Customize evolution paths
determineEvolutionPath() {
    const avgCare = (this.hunger + this.energy + 
                     this.happiness + this.hygiene) / 4;
    
    if (avgCare < 40) this.evolutionPath = "NEGLECT";
    else if (this.discipline > 70) this.evolutionPath = "INTELLECTUAL";
    // Modify these thresholds!
    ...
}
```

### Modify Visual Style
```css
/* Change color scheme */
body {
    background: #000; /* Main background */
    color: #00ff00;   /* Primary text color */
}

/* Change neon glow colors */
.game-container {
    box-shadow: 
        0 0 20px rgba(0, 255, 255, 0.5),  /* Cyan glow */
        0 0 40px rgba(255, 0, 255, 0.3);  /* Magenta glow */
}
```

---

## 🌟 Care Guide

### Optimal Care Schedule

**Every 2-3 Hours:**
- Check all stats
- Feed if Hunger < 70
- Clean if Hygiene < 60
- Play if Happiness < 70

**Daily:**
- At least one mini-game session
- Multiple talk interactions
- Training session for hidden stats
- Manual save before closing

**Weekly:**
- Review stats panel to check evolution progress
- Adjust care style for desired evolution
- Try different mini-games for variety

### Evolution Path Guide

Want a specific evolution? Follow these guidelines:

**🎓 SCHOLAR (Intellectual Path)**
- Train frequently (every few hours)
- Keep Discipline high (70+)
- Play Memory game often
- Moderate social interaction

**🦋 SOCIAL BUTTERFLY (Active Path)**
- Talk constantly (keep Social at 80+)
- Play often (Happiness at 80+)
- Feed generously
- High interaction frequency

**🗺️ ADVENTURER (Independent Path)**
- Let some stats get low occasionally
- High Curiosity (play Maze game)
- Balanced training
- Moderate attention

**🎨 ARTIST (Doting Path)**
- Maximum affection (talk + play constantly)
- High Creativity (Rhythm game)
- Never let stats drop low
- Constant positive interaction

**🌑 MYSTERIOUS (Neglect Path)**
- Low Discipline (<30)
- Low Affection (<30)
- Minimal interaction
- (Not recommended for first playthrough!)

**☯️ HARMONIOUS (Balanced Path)**
- Keep all stats above 50
- Balanced interaction types
- Moderate attention
- Default evolution if no clear path

### Common Issues

**Pet keeps getting sick:**
- Don't let Hunger drop below 20
- Keep Hygiene above 20
- Feed + Clean immediately when sick

**Stats decay too fast:**
- Check personality traits (ENERGETIC/NEAT FREAK increase decay)
- Baby stage has 1.5× decay multiplier
- Visit more frequently during Baby/Child stages

**Not evolving as expected:**
- Evolution determined during Teen stage (days 7-14)
- Final form set at day 14
- Focus care efforts days 7-14 for best results

**Pet won't talk/interact:**
- Try different times of day
- Check mood—some moods have unique responses
- Stage affects dialogue complexity

---

## 🎮 Mini-Game Strategies

### 🧠 Memory Match
**Strategy:**
1. Start from top-left, work systematically
2. Remember positions of unmatched cards
3. Create mental map of board
4. Speed matters—match quickly for time bonus

**Tips:**
- All 8 pairs must be found to win
- Time limit: 60 seconds
- Best stat boost: Intelligence +15

### ⚡ Reaction Test
**Strategy:**
1. Keep cursor near center
2. Click immediately when target appears
3. Don't anticipate—react to movement
4. Steady pace better than frantic clicking

**Tips:**
- Target repositions after each click
- 30 seconds to click as many as possible
- Score: 10 points per click
- Best stat boost: Energy +15

### 🔍 Maze Runner
**Strategy:**
1. Scan for clear paths before moving
2. Try to move toward exit (bottom-right)
3. Dead ends are common—backtrack freely
4. Keep mental map of explored areas

**Tips:**
- Use arrow keys to navigate
- Start: top-left, Exit: bottom-right
- 90 seconds time limit
- Fewer moves = better result
- Best stat boost: Curiosity +15

### 🎵 Rhythm Master
**Strategy:**
1. Watch notes approach from right
2. Press SPACE when note crosses yellow circle
3. Build combo multiplier by hitting consecutively
4. Timing is everything—practice makes perfect

**Tips:**
- Combo multiplier increases score
- Notes move at constant speed
- Perfect timing = best results
- 45 seconds duration
- Best stat boost: Creativity +15

---

## 📱 Responsive Design

### Desktop Experience
- Full-width sidebar layout
- Large interactive buttons
- Detailed stat displays
- Optimal canvas size (240×240px)

### Tablet Experience
- Stacked layout for better viewing
- Medium-sized buttons
- Readable text at 0.9× scale
- Canvas: 200×200px

### Mobile Experience
- Single column layout
- Touch-optimized buttons (min 44px)
- Compact stat displays
- Reduced animations for performance
- Canvas: 180×160px depending on screen

### Landscape Mode
- Two-column layout when possible
- Optimized button sizes
- Better use of horizontal space

---

## 🎓 Educational Value

### Life Lessons
- **Responsibility** - Consistent care yields rewards
- **Consequences** - Neglect has real effects
- **Patience** - Growth takes time
- **Balance** - Managing multiple needs simultaneously
- **Cause & Effect** - Actions directly influence outcomes

### Skill Development
- **Memory** - Memory Match game
- **Reaction Time** - Reaction Test game
- **Problem Solving** - Maze Runner game
- **Timing & Rhythm** - Rhythm Master game
- **Resource Management** - Stat balancing

### Emotional Connection
- Players form genuine attachment to their pets
- Encourages empathy and caregiving
- Teaches emotional awareness through mood system
- Rewards positive interaction patterns

---

## 🐛 Known Quirks

### Intended Behaviors
- Stats can go negative internally (displays as 0)
- Personality traits are permanent (part of pet's identity)
- Evolution can't be changed once adult stage reached
- Some stat combinations produce unexpected moods
- Traits may seem contradictory but add personality

### Browser Compatibility
- **Best on:** Chrome, Firefox, Edge (Chromium)
- **Works on:** Safari, Samsung Internet
- **LocalStorage required:** No incognito/private mode
- **JavaScript required:** Obviously!

---

## 🔮 Future Enhancement Ideas

Potential additions (not yet implemented):
- [ ] Multiple pet slots (raise 3+ pets simultaneously)
- [ ] Pet-to-pet interactions
- [ ] Breeding system with trait inheritance
- [ ] More mini-games (Simon Says, Whack-a-Mole, etc.)
- [ ] Achievements and badges
- [ ] Extended evolution tree (20+ forms)
- [ ] Seasonal events and special items
- [ ] Online leaderboards
- [ ] Pet customization (colors, accessories)
- [ ] Journal/diary feature
- [ ] Photo mode with filters
- [ ] Sound effects and music
- [ ] Multiple language support
- [ ] Export/import save files
- [ ] Pet aging (elderly stage)

---

## 💡 Pro Tips

1. **Save Often** - Browser crashes lose unsaved progress
2. **Check Stats Daily** - Prevention easier than recovery
3. **Play Mini-Games** - Best way to boost hidden stats
4. **Talk Frequently** - Builds affection, reveals personality
5. **Note Personality** - Tailor care to your pet's traits
6. **Evolution Focus** - Days 7-14 determine final form
7. **Balance is Key** - Don't neglect any single stat
8. **Time Management** - Set phone reminders for check-ins
9. **Experiment** - Different care styles = different outcomes
10. **Have Fun** - It's about the journey, not just the destination!

---

## 🎭 Pet Personality Examples

### Example 1: Lazy Foodie Loner
- Eats enthusiastically but sleeps a lot
- Doesn't need much social interaction
- Perfect for busy owners
- Likely evolution: Harmonious or Mysterious

### Example 2: Energetic Social Butterfly Curious
- Constantly wants to play and interact
- Needs frequent attention
- Great for active players
- Likely evolution: Social Butterfly or Adventurer

### Example 3: Neat Freak Picky Eater Stubborn
- Challenging but rewarding
- Requires specific care strategies
- Unique personality shines through
- Likely evolution: Scholar or Artist

---

## 🎪 Community Challenges

Try these self-imposed challenges:

### 🏆 Speedrun Challenge
- Reach adult stage in minimum real-world time
- No time manipulation!
- Document your strategy

### 🎯 Perfect Care Challenge
- Keep ALL stats above 80 at all times
- From egg to adult
- Screenshot proof!

### 🎨 Artist Challenge
- Get Artist evolution with specific traits
- Must have at least 2 "difficult" traits
- Share your evolved pet!

### 🌈 Collection Challenge
- Unlock all 6 evolution forms
- One new egg after each adult evolution
- Create evolution guide for others

---

## 🤝 Credits & Inspiration

### Inspired By:
- **Tamagotchi** (1996) - The original virtual pet
- **Digimon** - Evolution mechanics
- **Neopets** - Stat depth and mini-games
- **Webkinz** - Online care simulation
- **90s Internet Culture** - Aesthetic design

### Made With:
- Pure HTML5, CSS3, JavaScript
- No external libraries or frameworks
- Canvas API for graphics
- LocalStorage API for saves
- Press Start 2P font (Google Fonts)

---

## 📜 License

This project is open source and available for personal and educational use.

**Based on virtual pet mechanics** - Thank you to all the digital pets that shaped our childhoods! 🐾

---

## 🌈 Final Thoughts

> *"The best time to start caring for a digital pet was in 1996. The second best time is now."* - Ancient Tamagotchi Proverb

PETTEOMOCHA is more than just a game—it's a companion, a responsibility, and a journey. Each pet is unique, shaped by your care choices and their own personality. There's no "perfect" way to play; every player's experience will be different.

Whether you're here for nostalgia, to learn about care simulation mechanics, or just to have fun watching a cute pixel creature grow, remember: your pet is counting on you!

**Now go raise the best digital companion the internet has ever seen!** 🚀🐾

---

*Crafted with nostalgia and pixelated love* 💖✨

*P.S. - Don't forget to save before closing your browser!* 💾
