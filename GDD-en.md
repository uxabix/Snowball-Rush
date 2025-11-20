# Snowball Rush — Game Design Document (GDD)
*Version 1.2 — English*

---

# 1. General Information

## 1.1. Game Title
**Snowball Rush**

## 1.2. Genre
- Endless Runner  
- Arcade / Action  
- Casual Skill-Based Runner  

## 1.3. Platforms
- Mobile (iOS, Android)

## 1.4. Game Goal
The player controls a rolling snowball that grows in size, collects coins, and avoids obstacles.  
The goal is to survive as long as possible, maintain an optimal size, and achieve the highest score.

---

# 2. Core Mechanics

## 2.1. Controls
- **Swipe left/right** or **free drag movement** — move across the wide track.  
- **“Shrink” button**:
  - instantly reduces the snowball size;
  - decreases the score multiplier.

## 2.2. Growth System
The snowball grows when rolling over:
- snow patches,
- snow pickups,
- cold zones,
- snow mini-areas (freezers, ice trucks, etc.).

### Growth Effects:
- score multiplier increases,
- ability to collect coins across multiple lanes,
- reduced maneuverability,
- some tight passages become inaccessible.

## 2.3. Shrinking System
The snowball shrinks when exposed to:
- heat zones (steam, sunlight, hot asphalt),
- soft or non-lethal obstacles,
- manual shrinking ability.

### Minimum Size
- warning when approaching minimum size (e.g. 0–10%),
- **reaching 0% size ends the run**.

## 2.4. Obstacles

### Lethal (instant death)
- walls, cars, rocks, trees,
- large falling objects,
- narrow tunnels if the snowball is too big.

### Non-lethal (reduce size)
- steam vents,
- soft snow piles,
- bushes,
- warm road sections,
- hot air bursts.

### Dynamic
- rolling snowballs,
- falling icicles,
- moving hazards (snowplow, skier, etc.).

---

# 3. Special Surfaces

## 3.1. Ice Zones
- increase speed,
- reduce control,
- increase score gain,
- higher coin spawn chance.

Behavior variations:
1. Complete sliding (no control).  
2. High inertia.  
3. Partially limited control.

---

# 4. Movement System

## Option A: 5 Lanes
- clear and familiar control scheme.

## Option B: Free Movement
- the player moves freely across a wide runway,
- more physics-based and dynamic.

---

# 5. Biomes & Level Themes

## 5.1. Cold Levels (default)
- lots of snow,
- stable growth,
- minimal melting,
- classic gameplay.

## 5.2. Spring Levels
- snow melts gradually,
- constant small shrink rate,
- puddles and sunlight appear frequently,
- player focuses on conserving size.

## 5.3. Warm Biomes (hot environments)
The main theme is survival under continuous melting.

### Effects:
- constant melting (example: –10%/sec),
- very little natural snow,
- dangerous warm surfaces.

### Hazardous Elements:
- hot asphalt,
- puddles (–10–20% size),
- hot steam bursts.

### Helpful Elements:
- building shadows (reduce/stop melting),
- cold ventilation ducts,
- cool tunnels,
- snow mini-locations.

---

# 6. Mini-Locations (Size Restore Areas)

## 6.1. Broken Freezer
- snow spills out,
- fast growth: +15–30%.

## 6.2. Store Freezer Aisle
- long cold corridor,
- strong growth + slight sliding effect.

## 6.3. Overturned Refrigerated Truck
- ice falls from the doors,
- efficient restoration zone.

## 6.4. Ice Cavern (under bridges)
- cold surface,
- zero melting + growth,
- difficult handling.

---

# 7. Economy & Collectibles

## 7.1. Coins
Types:
- regular coins,
- ice coins (temporary multiplier boost),
- rare gifts (premium currency for cosmetics).

## 7.2. Progression
- upgrades (slower melting, faster growth, wider coin pickup radius),
- snowball skins,
- new biomes,
- seasonal events.

---

# 8. HUD & UI

## 8.1. HUD Elements
- snowball size bar (possibly a ring UI),
- score multiplier,
- melting indicator (in warm biomes),
- “Shrink” button.

## 8.2. Warning Effects
- red vignette when low on size,
- screen shake,
- flashing size indicator.

---

# 9. Environment Interaction

## 9.1. Snowball Physics
- mild inertia,
- increased mass effects when large,
- sliding on ice.

## 9.2. Dynamic Camera
- zooms out as snowball grows,
- zooms in when small.

---

# 10. Audio & Music

## 10.1. Sound Effects
- crunchy snow (changes by size),
- melting sounds (drips, hissing),
- ice sliding,
- bump impacts.

## 10.2. Music
- cold levels: calm wintery electronic music,
- warm levels: tense survival mood,
- ice zones: crystalline ambient sounds.

---

# 11. Progression & Metagame

## 11.1. Player Goals
- maximum distance,
- high multipliers,
- completing challenges.

## 11.2. Missions / Challenges
Examples:
- “Survive 100m in a warm biome without melting.”
- “Collect 3 ice coins on ice.”
- “Survive 60 seconds without using manual shrink.”

---

# 12. Monetization

## 12.1. Non-aggressive Model
- cosmetic skins,
- premium pass (x2 coins),
- rewarded ads (snow boost, revive, etc.),
- unlockable biomes with in-game currency.

---

# 13. Lore & Atmosphere

## 13.1. Core Idea
The player is a living snowball traveling through various climates, trying to survive and maintain its mass.

## 13.2. Aesthetic Style
- colorful and cartoony,
- soft rounded shapes,
- strong cold/warm contrasts,
- easily readable silhouettes.

---

# 14. Future Expansions

- seasonal events (Christmas, Summer, Easter),
- competitive races,
- PvP “Snowball Duel” modes,
- big boss obstacles (avalanche, giant snowplow),
- track editor.

---

# 15. Key Game Identity
**“Players constantly balance between risk (growing → harder obstacles) and safety (shrinking → losing multiplier).”**

This core tension defines Snowball Rush’s unique gameplay.

---

# End of Document
