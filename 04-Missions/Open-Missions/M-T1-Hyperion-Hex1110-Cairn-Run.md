---
type: mission
canon_status: draft
status: open
sponsoring_faction: Hyperion Syndicate
patron: Lady Vexis
target_hex: "1110"
recommended_tier: 1
linked_clock: "Monopolize the \"Blight-Crystal\" Trade (Step 1/6)"
fp_multiplier: 1
bp_reward: 2
gold_reward: 50
---
> [!editor] Editor pass — upstream blocker
> `00-System/Templates/Template-Mission.md` is currently **empty (0 bytes)**, so YAML/section conformance was reviewed against the brief's checklist and the Showrunner's evident schema only, not against a canonical template. **Proposed fix (for the Showrunner / template owner):** populate `Template-Mission.md` with the canonical mission structure, then re-tag this file with `canon_status: canon` once it conforms. No content change to this mission is required.

# Mission: The Cairn Above the Tide

## The Call to Action
Delivered in person, by a clerk in plum-and-gold livery, to whichever party has been seen taking Syndicate work. The clerk does not say the name *Lady Vexis*; she does not need to. She produces a folded square of vellum, sealed with crimson wax stamped with a sun-and-coin motif, and waits while it is read:

> *"A modest delivery of mine has come ashore in a place it should not have. Two crates, straw-packed, beneath a stone cairn in the sea-grass above the high tide on Gullcry Strand — east coast, **the Cairn Above the Tide**. The men who placed it there were paid to be discreet. They have proven, instead, to be visible. Recover the crates. Bring them whole and unbroken to my factor at the Gilded Seat by sundown. The men who placed them are no longer my concern; if they remain on the strand when you arrive, they are yours to dispose of as your conscience permits. I find conscience an expensive thing on a beach.*
>
> *Whatever you do, darling: do not break a crate. The contents are temperamental, and the sea is wide."*
>
> — *L.V., Gilded Seat*

The clerk will further confirm, only if asked: the strand can be reached on the Havenport east road; the cairn lies above the high-tide line, partially hidden in sea-grass; the **Teeth** reef offshore is not the party's concern. She declines to discuss the contents.

## Objectives
1. **Primary — Recover the Cache:** Travel to [[../../03-Hex-Map/Region-01-Safe-Zone/Hex-1110|Hex 1110: Gullcry Strand]], locate **the Cairn Above the Tide** in the sea-grass, and recover **both crates of raw Blight-crystals** intact. Deliver them to Lady Vexis's factor at the **Gilded Seat** before sundown of the day they are recovered. *(Hazard reminder: any violent impact on a crate triggers a DC 12 Dex save vs. 1d4 necrotic damage to everyone within 5 ft. Carry, do not roll.)*
2. **Denial / Secondary — Silence the Loose Thread:** The **three Syndicate smugglers** working the cairn are jumpy and visible from the road. Lady Vexis would prefer they not return to Havenport to talk. Either **bring her the smugglers' waxed cipher ledger** (and ensure none of the smugglers escape down the strand) **or** deliver convincing proof that none of the three will be filing complaints with the City Watch. *(This denies the Cronus Dominion's revenue agents the lead they would otherwise have to tax — and tax-trail — the Blight-crystal route.)*

## Reward Distribution Structure
- **Faction Points (FP):** **1 FP × 1** to Hyperion Syndicate for Primary completion. **+1 FP** if Denial is also achieved (max **2 FP**). *(Awarded to participating characters' aligned factions; full FP paid only on intact delivery to the Gilded Seat.)*
- **Bastion Points (BP):** **2 BP** to **Havenport (Gilded Seat / Hyperion Syndicate)** on Primary. **+1 BP** if Denial is also achieved (max **3 BP**). *(BP source: a successful, untraced first cache-run is the foundation of Vexis's Tier 1 supply infrastructure.)*
- **Individual Rewards:** **50 gp** per character on Primary completion (Vexis pays in clipped Havenport silver and Syndicate scrip). **+25 gp per character** if Denial is achieved (max **75 gp**). *Bonus loot:* the smugglers carry **8 gp in mixed coin** between them, free for the taking, and Lady Vexis will turn a blind eye.
- **Penalty Clause:** If a crate is **broken in transit**, **FP is forfeit (0)**, BP is reduced to **1**, and base gold is reduced to **25 gp per character**. Vexis will pay for results, not theatrics.
- **Loot In-Hex (kept by party):** Anything from the **Keeled Dory** wreck — including the **four stamped iron nails** with the rayed-sun maker's mark, the **copper ring with the dockmaster's stamp** (Edbert Thurlow's), and any salvageable flotsam from the tide pools (1d4 pieces) — Vexis has no claim on. She does not even know it is there.

### Math / Parity Breakdown
| Component | Primary Only | Primary + Denial | Crate Broken |
|---|---|---|---|
| FP (Hyperion Syndicate) | 1 | 2 | 0 |
| BP (Gilded Seat, Havenport) | 2 | 3 | 1 |
| Gold (per character) | 50 gp | 75 gp | 25 gp |

## GM Notes & The "B-Plot" Clue
*(Read silently. Do not reveal to players.)*

- **The Real Motive:** This is not a recovery, it is a **stress test**. Lady Vexis's Blight-Crystal clock is at Step 1/6, and the cairn drop is the very first link in a planned coastal cache-chain that will eventually move refined product from a deeper Blight-source ruin to Le Baron's alchemical workshop and out through Havenport's harbor without ever crossing a Dominion checkpoint. Vexis is using the party to learn three things at once: *(a)* whether the cairn drop method survives contact with non-Syndicate eyes, *(b)* whether the party can deliver a hazardous cargo without breaking it, and *(c)* whether they are willing to clean up loose threads when paid to. Each answer prices her next tier of work for them.
- **The B-Plot Truth (Faction-cross tie):** The four iron nails in the **Keeled Dory** were *Dominion* stamp — same rayed-sun mark as the **Dominion Blazes** in [[../../03-Hex-Map/Region-01-Safe-Zone/Hex-1011|Hex 1011]]. Someone inside the Cronus Dominion is selling Iron-Line ironmongery to the Hyperion Syndicate. Vexis knows. **Valerius does not.** When the inside leak is finally exposed in a later tier, the party will already have held the proof in their hands — and may even have delivered some of it to Vexis without realizing what they were carrying. Edbert Thurlow, the missing fisherman, is almost certainly dead because he saw the wrong cargo on the wrong beach.
- **The Concrete Clue (one, hand it to the party):** When the cairn is opened, **wedged between the two crates as packing material is a torn page from Edbert Thurlow's dockmaster's-ledger logbook**, salt-stained, with three lines of his own handwriting still legible: a date (nine days ago), a tide-time, and the entry "*east strand — saw two iron-stamp nails in C-Y's hull, not theirs, asked nothing.*" The smugglers used it as packing because it was waste paper to them. Anyone in Havenport who knew Edbert (or anyone who has visited the wrecked dory and seen the stamped nails) will recognize the hand and the connection.
- **If the smugglers escape:** Mark this on the Hyperion clock. Vexis's people now know an adventuring party is working her coast — she will offer the next mission slightly cheaper, but with watchers attached.
- **If the party reads the cipher ledger:** It is a Syndicate substitution cipher (DC 15 Investigation over a long rest, or one favor owed to Brother Caelum Ash at the Common Record). It lists **three more drop coordinates** along the east coast — seeds for future Tier 1 missions, all reachable from Havenport.
