This is the comprehensive official instruction manual for **Legion Survivor: Tactical Grid**, compiled directly from the project source code.

---

# Legion Survivor: Tactical Grid – Official Manual

## 1. Game Overview
**Legion Survivor** is a tactical grid-based Roguelike action survival game. You command a legion of units that you can arrange in a formation. Your goal is to survive waves of enemies by moving your legion strategically while your units automatically engage targets within their range.

### Core Gameplay Loop
*   **Real-time Combat**: Control legion movement via Joystick or WASD. Units auto-attack.
*   **Tactical Management**: Access the "Tactics" menu to hire, swap, promote, or sacrifice units.
*   **Roguelike Progression**: Level up your "Legion Level" to acquire **Doctrines** (powerful passive skills).

---

## 2. Core Mechanics

### 2.1 Resources & Progression
*   **Gold**: Earned by killing enemies. Used for hiring (50G), promotion (100G), revival (30G), and formation expansion.
*   **Legion Level**: Increased by global XP. Each level-up allows you to choose one of three random Doctrines.
*   **Unit Level**: Individual units gain XP by fighting. Leveling up grants a random stat boost (**Atk +1**, **HP +10**, or **Def +1**) and heals a portion of current HP.

### 2.2 The Stage System
The game progresses through distinct difficulty phases:
1.  **Stage 1 (Monsters)**: 0–15 mins. Face slimes, stingers, and titans. Unit promotion is capped at Tier 2.
2.  **Stage 2 (Humans)**: 15–30 mins. Face organized Human Infantry, Archers, and Knights.
3.  **Stage 3 (The Horde)**: 30–45 mins. A lethal mix of both Monsters and Humans.
4.  **Endless Mode**: Unlocks after 45 mins. Difficulty scales linearly and infinitely.

---

## 3. Legion Unit Classes

Units are divided into three Tiers (T1, T2, T3) across five base archetypes.

### 3.1 Base Classes (Tier 1)
*   **Infantry**: Balanced frontline unit. (150 HP, 12 Atk, 120 Range)
*   **Archer**: Reliable ranged DPS. (80 HP, 10 Atk, 450 Range)
*   **Heavy Guard**: High defense tank. (250 HP, 8 Atk, 15 Def, 80 Range)
*   **Apprentice (Mage)**: Small AOE magic damage. (70 HP, 18 Atk, 350 Range)
*   **Acolyte (Priest)**: Heals wounded allies. (100 HP, 10 Heal, 300 Range)

### 3.2 Advanced Classes (Tier 2 – Requires Unit Level 5)
*   **Infantry Branch**: 
    *   *Swordsman*: High attack speed and evasion.
    *   *Spearman*: Increased melee range (180), perfect for the second row.
*   **Archer Branch**: 
    *   *Crossbowman*: High single-target burst.
    *   *Hunter*: Rapid fire rate for crowd suppression.
*   **Heavy Branch**: 
    *   *Guardian*: Definitive tank. (500 HP, 35 Def)
    *   *Knight*: Aggressive heavy armor with higher mobility.
*   **Mage Branch**: 
    *   *Wizard*: Fire magic with large explosion radius.
    *   *Sorcerer*: Dark magic with faster casting and longer range.
*   **Priest Branch**: 
    *   *Cleric*: Multi-target healing.
    *   *Monk*: Hybrid frontline healer.

### 3.3 Ultimate Classes (Tier 3 – Requires Unit Level 10)
*   **Melee Specialists**: *Holy Knight* (Aura), *Berserker* (Low HP/High Speed), *Phalanx* (Line pierce), *Gladiator* (Crit expert).
*   **Ranged Specialists**: *Sniper* (Infinite range), *Marksman* (Arrow storm), *Ranger* (Pierce), *Assassin* (Auto-execute non-bosses).
*   **Defensive Titans**: *Iron Wall* (1500 HP, 90 Def), *Paladin* (Def aura), *Juggernaut* (Knockback), *Templar* (Def-to-Damage conversion).
*   **Magic Masters**: *Archmage* (Chain spells), *Lich* (Life-steal), *Elementalist* (Slow on hit), *Battlemage* (Tanky AOE).
*   **Divine Supports**: *High Priest* (Heals whole legion), *Prophet* (Evasion buff), *Saint* (High Def healer), *Bishop* (Heal + Punishment damage).

---

## 4. Enemy Index

### 4.1 Monsters
*   **Grunt**: Standard chaser.
*   **Stinger**: Zig-zag movement; lunges at 150 range then retreats.
*   **Spitfire**: Ranged slime attacks.
*   **Titan**: High HP mini-boss.
*   **Bomber**: Flashes white/red; explodes for massive AOE damage after 0.8s.
*   **Shield**: High defense; straight-line charger.
*   **Healer**: Maintains distance; heals other enemies.
*   **Dasher**: Charges up, then dashes at 6x speed.

### 4.2 Human Units (Stage 2+)
*   **Infantry**: Faster and stronger than Grunts.
*   **Archer**: High-velocity arrows with massive range.
*   **Knight**: Extremely tanky and mobile chasers.

---

## 5. Tactical Systems

### 5.1 Formation Expansion
Expand your grid to fit more units:
*   3x3 → 4x4 (500G)
*   4x4 → 5x5 (2000G)
*   5x5 → 6x6 (6000G)
*   6x6 → 7x7 (12000G)

### 5.2 Dismiss & Sacrifice
Drag a unit in the Tactics menu to:
*   **Dismiss**: Remove a unit and receive a 50% refund plus a level bonus.
*   **Sacrifice (T2+ only)**: Destroy the unit to immediately trigger a high-tier Doctrine selection.

---

## 6. Doctrines (Passives) List
You can carry a maximum of **10 Doctrines**. If full, you must replace an old one.

### 6.1 Common
*   **Sharpened Blades**: Melee Damage +25%.
*   **Iron Plating**: Def +8, HP +50.
*   **Quick Draw**: Attack Speed +20%.
*   **Eagle Eye**: Range +40%.
*   **Greed**: Gold Gain +30%.

### 6.2 Rare
*   **Vampire Teeth**: Heal 3 HP on hit.
*   **Piercing Shot**: Projectiles pierce 1 enemy.
*   **Thorns Aura**: Reflect 60% of damage taken.
*   **Berserker Blood**: Lower HP increases Speed.
*   **Heavy Impact**: Melee attacks knockback.

### 6.3 Legendary
*   **Split Shot**: Projectiles +2, Damage -30%.
*   **Executioner**: Executes enemies below 20% HP.
*   **Ricochet**: Projectiles bounce once between targets.
*   **Core Protection**: Center unit is invincible if allies are alive.
*   **Membership Card**: All upgrade/hiring costs -30%.

### 6.4 Special/Elemental
*   **Frostbite**: Attacks slow enemies by 30%.
*   **Ignite**: Attacks burn enemies for % of Atk.
*   **Soul Siphon**: Kill chance to summon a 10s Skeleton.
*   **Golden Bullets**: Damage scales with your total Gold.
*   **Orbitals**: 2 magic orbs rotate around the legion.
*   **Homing Missiles**: All projectiles seek targets.

---

## 7. Advanced Strategy & Math

### 7.1 Positioning
*   **Row 0 (Front)**: Place Shields/Iron Walls.
*   **Row 1 (Middle)**: Place Spearmen or Battlemages (Medium range).
*   **Row 2 (Back)**: Place Archers and Priests.

### 7.2 Damage Formula
`Final Damage = (Base Damage * Legion Level Bonus * Doctrine Multiplier) - Target Defense`
*(Minimum damage is always 1)*.

### 7.3 AI Manipulation
*   **Dasher Dodge**: When a Dasher turns red and stops, move vertically to its current path to avoid the 6x speed dash.
*   **Bomber Pull**: Draw Bombers toward the edge of your formation and move away quickly once they start flashing.

### 7.4 Controls
*   **Keyboard**: WASD or Arrows to move.
*   **Mobile**: Dynamic Joystick (anywhere on screen).
*   **Tactics**: Tap units to select, drag to swap or recycle.

---

## 8. Tips for Success
*   **T3 Sacrifice**: Sacrificing a Tier 3 unit guarantees at least one **Legendary** choice in the Doctrine selection.
*   **Investment**: If you have the **Investment** Doctrine, try to stay above 1000G to maximize interest gains every 60 seconds.
*   **Crit Mastery**: Gladiator and Assassin have built-in crit rates. Combine them with **Bounty Hunter** to generate massive gold during combat.

---

## 9. Technical Architecture & Performance
*Legion Survivor* is built with a custom **Entity-Component-System (ECS)** style architecture to handle hundreds of entities on mobile devices.

### 9.1 Spatial Hash Grid (SpatialSystem.ts)
To prevent the game from lagging during massive collisions:
*   The map is divided into a grid of **250x250 pixel cells**.
*   The game only checks for collisions between a projectile and enemies located in the same or adjacent 8 cells.
*   **Result**: CPU usage remains low even with 150+ enemies on screen.

### 9.2 Procedural Audio (SoundService.ts)
Instead of loading large MP3 files, the game uses the **Web Audio API** to generate sounds mathematically:
*   **Melee**: Square wave (150Hz) for a "thump" effect.
*   **Healing**: Exponentially rising frequency (440Hz to 880Hz).
*   **Death**: Frequency slide from 200Hz down to 50Hz.
*   **Throttling**: The system prevents the same sound from playing more than once every 40-60ms to avoid "audio popping" during intense battles.

---

## 10. The Evolution Tree (Detailed Paths)

Each starting unit has a branching path. You must reach **Level 5** for Tier 2 and **Level 10** for Tier 3.

### 10.1 The Melee Path (Frontline)
*   **Infantry** (T1)
    *   → **Swordsman** (T2: Evasion/Speed) → **Holy Knight** (T3: Tank/Aura) OR **Berserker** (T3: Glass Cannon)
    *   → **Spearman** (T2: Range) → **Phalanx** (T3: Line Pierce) OR **Gladiator** (T3: Crit Specialist)

### 10.2 The Tank Path (Shield)
*   **Heavy Guard** (T1)
    *   → **Guardian** (T2: Pure HP) → **Iron Wall** (T3: Ultimate Def) OR **Paladin** (T3: Support Aura)
    *   → **Knight** (T2: Mobility) → **Juggernaut** (T3: Knockback) OR **Templar** (T3: Holy Damage)

### 10.3 The Ranged Path (Arrows)
*   **Archer** (T1)
    *   → **Crossbowman** (T2: Single Target) → **Sniper** (T3: Boss Killer) OR **Marksman** (T3: High Speed)
    *   → **Hunter** (T2: Rapid Fire) → **Ranger** (T3: Piercing) OR **Assassin** (T3: Executioner)

---

## 11. Passive Skill (Doctrine) Mechanical Logic
Understanding how "Flags" work allows for high-level "Broken" builds.

| Flag Name | Mechanical Effect | Best Synergistic Unit |
| :--- | :--- | :--- |
| **`ricochet`** | Bounced projectiles deal 80% damage. | **Hunter / Marksman** |
| **`cleave`** | Melee hits apply damage in 150px radius. | **Berserker / Juggernaut** |
| **`piercing`** | Arrows don't disappear on first hit. | **Crossbowman / Sniper** |
| **`homing`** | Projectiles adjust velocity towards nearest enemy. | **Mage / Wizard** |
| **`coreProtection`** | Center unit is literally invincible. | **High Priest** (keep the healer alive) |
| **`vengeance`** | Guaranteed Critical Hit after taking damage. | **Monk / Saint** |

---

## 12. Save & Load System
The game uses a `SAVE_PREFIX` linked to **Local Storage**.
*   **What is saved?** Legion Level, Gold, Stage Timer, Formation Size, and every individual Unit Instance (Level, XP, Class, and Bonus Stats).
*   **Auto-Save**: The game state is serialized into a JSON string. Note that active projectiles and particles are **not** saved to keep save files clean; only the permanent army state is preserved.

---

## 13. Advanced Combat Formulas (Internal)

### 13.1 Healing Logic
Healing is calculated as:
`HealAmount = BaseDamage * (1 + (LegionLevel - 1) * 0.1)`
*   The **High Priest** heals 3 targets simultaneously, making it the most efficient late-game survival unit.

### 13.2 Promotion Bonus
When you promote a unit (e.g., Archer → Sniper):
*   The unit **resets to Level 1**.
*   However, it retains **50% of the Bonus Stats** (Bonus Atk/HP/Def) earned from its previous form's level-ups.
*   **Pro Tip**: Grinding levels on a Tier 1 unit before promoting yields a slightly stronger Tier 3 unit than rushing the promotion.

---

## 14. Troubleshooting & Settings
*   **Screen Blur**: The game uses `ctx.imageSmoothingEnabled = false` for a crisp "Pixel Art" look. If the game looks blurry, ensure your browser zoom is set to 100%.
*   **Input Latency**: The game is optimized with `desynchronized: true` for the Canvas context to minimize input lag on Chrome-based browsers.
*   **Language Toggle**: Can be switched at any time from the Main Menu or the System Menu within the Tactics screen.

---
**END OF MANUAL**
*May your formation stand strong against the encroaching legions.*