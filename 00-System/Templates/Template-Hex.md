---
type: hex
coordinates: 
region: 
danger_level: 
dominant_faction: 
explored: false
---
# Hex {{coordinates}}: {{Location Name}}

## Environment & Terrain
(A vivid description of the biome, weather, and general atmosphere. AI should pull from `Wilderness-Dressing.md`.)

## Landmarks & Discoveries
- **Landmark 1:** (Visibility: Icon/Landmark/Hidden/Secret) - (Description)

## The Living World (AI Instruction: MUST COMPLETE)
*(AI Instruction: Read `00-System/Active-Clocks.md` or `00-System/Campaign-Secrets.md`. Weave a clue, complication, or background element of an active clock or secret into this hex.)*
- **Clock/Secret Tie-in:** (Describe the clue or element here)

## Encounters (Danger Level: {{danger_level}})
*(AI Instruction: Roll on `Encounters-By-Biome.md` to populate this section.)*
- **Creatures/Obstacle:** - **Treasure/Loot:** ```

**4. The Mission Template (`Template-Mission.md`)**
*Structured perfectly for your post-session rewards system (FP, BP, and Renown).*

```markdown
---
type: mission
status: open
sponsoring_faction: 
target_hex: 
recommended_tier: 
fp_multiplier: 1
bp_reward: 0
gold_reward: 0
---
# Mission: {{Title}}

## The Call to Action
(The narrative hook as it appears to the players, e.g., a notice board posting or a direct plea from an NPC.)

## Objectives
1. **Primary:** (The main goal required for the BP/FP payout)
2. **Denial/Secondary:** (An optional goal to thwart a rival faction or secure extra resources)

## GM Notes & The "B-Plot" Clue
*(AI Instruction: How does this mission secretly connect to the sponsoring faction's Active Clocks? Provide the GM with the hidden truth behind the mission.)*
- **The Real Motive:** - **Clues to find:** ## Reward Distribution Structure
- **Faction Points (FP):** 1 FP x {{fp_multiplier}} (Awarded to participating characters' aligned factions)
- **Bastion Points (BP):** {{bp_reward}} (Awarded to the {{sponsoring_faction}} Bastion)
- **Individual Rewards:** {{gold_reward}} gp, (List any specific loot/items)