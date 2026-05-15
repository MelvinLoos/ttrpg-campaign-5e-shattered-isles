---
type: session_report
session_number: 
in_game_date: 
real_date: 
party_present: 
xp_awarded: 
---
# Session {{session_number}}: {{Session Title}}

## Recap
*(Briefly summarize where we left off and the opening scene. 1–3 sentences, player-facing.)*

## Session Summary
*(Bullet points or short paragraphs. Stay factual; interpretation goes in GM Notes.)*
- 

## Key NPCs Met
*(For any first-time appearance, create a new NPC file under `01-NPCs/` and link it here.)*
- [[NPC Name]] — (faction / role / current disposition toward party)

## Locations Visited
*(For each hex visited for the first time, open the hex file and flip `explored: true`. Note any newly discovered landmarks or status changes.)*
- [[Hex-XXXX]] — (what changed; mark `explored: true` in the hex file if first visit)

## Mission Updates

### Completed
*(Move the mission file from `04-Missions/Open-Missions/` to `04-Missions/Completed-Missions/` and set `status: completed` in its frontmatter.)*
- [[Mission File]] — (one-line outcome)

### Failed / Abandoned
*(Move the mission file from `04-Missions/Open-Missions/` to `04-Missions/Failed-Missions/` and set `status: failed` in its frontmatter.)*
- [[Mission File]] — (one-line outcome)

### Newly Accepted
*(Any open missions the party formally accepted this session. Confirm the file exists in `04-Missions/Open-Missions/` with `status: open`.)*
- [[Mission File]] — (who offered it, deadline if any)

## Faction Points (FP) Changes
*(Apply these to the faction files' `current_standing` field after the session.)*

| Faction | ΔFP | Reason | New Standing |
|---|---|---|---|
| *[[Faction Name]]* | *+1* | *Completed escort to outer hex* | *Allied* |

## Bastion Points (BP) Changes
*(Update the bastion file's `current_bp` immediately after the session.)*

| Bastion | ΔBP | Reason | New BP Total |
|---|---|---|---|
| *[[Bastion Name]]* | *+2* | *Mission improved infrastructure* | *12* |

## Clock Ticks
*(Direction = + (toward completion) / − (rolled back). Reference exact clock names from `00-System/Active-Clocks.md`. Update that file immediately after the session.)*

| Clock | Direction | Segments | Trigger |
|---|---|---|---|
| *Iron Line* | *+* | *2* | *Party failed to disrupt supply caravan* |

## Loot, Treasure & Gold
*(List items recovered, gold split, and who is carrying what. Log on PC sheets / party inventory before next session.)*
- 

## New Rumors Earned / Overheard
*(Format matches `00-System/Rumor-Matrix.md` so entries can be lifted verbatim. Tag each rumor's truth value and source.)*
- (TRUE / PARTIALLY TRUE / FALSE) — Rumor text here. *(speaker, where heard)*

## World-State Changes
*(Anything in this list should propagate to the relevant hex / faction / NPC file before next session. NPC deaths, settlements burned, secrets revealed, B-Plot clues uncovered, shifted allegiances, etc.)*
- 

## GM Notes & B-Plot Tracking
*(GM-only. Do not share with players.)*
- **B-Plot Clues Surfaced:**
  - 
- **Player Theories Worth Encouraging:**
  - 
- **Adjustments for Next Session:**
  - (pacing / difficulty / spotlight balance)

## Cliffhanger / Next Session Hook
*(1–2 sentences capturing where play paused and any ticking-clock pressure heading into next session.)*

## Update Checklist
- [ ] Active-Clocks.md updated
- [ ] FP totals updated in 02-Factions-and-Bastions/
- [ ] BP totals updated in 02-Factions-and-Bastions/
- [ ] Mission files moved to Completed-Missions/ or Failed-Missions/ with status updated
- [ ] Hex files updated (explored flag, new landmarks, status changes)
- [ ] New rumors added to Rumor-Matrix.md
- [ ] New NPC files created where needed
- [ ] Campaign-Calendar.md advanced to current in_game_date
- [ ] Loot logged on PC sheets
