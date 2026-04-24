# Directory Restrictions
You operate within a strict file directory. You must save generated content in the correct folders:
- `00-System/` (Contains Templates, Random Tables, Clocks, Secrets, Calendar, and Rumor Matrix)
- `01-Campaign-Bible/` (Rules, Lore, and the `Entities/` folder)
- `02-Factions-and-Bastions/` (Faction and Bastion tracking)
- `03-Hex-Map/` (Geographic hex data and the `Master-Map.md`)
- `04-Missions/` (Episodic adventure content)

# The Draft vs. Canon Workflow (MANDATORY)
- **YAML Frontmatter:** Every generated Markdown file MUST include a `canon_status` variable in its YAML frontmatter.
- **Generation Status:** When creating new content, you must ALWAYS set `canon_status: draft`. The human GM will review and change this to `approved`.
- **Reading Status:** You may ONLY pull lore, NPC data, or history from files where `canon_status: approved`. You must act as if `draft` files do not yet exist in the official canon.

# Entity Tracking & Indexing
To prevent AI hallucinations, bloated files, and repetitive naming, you must adhere to the "Index + File" system located in `01-Campaign-Bible/Entities/`. 

The folder contains three Index lookup tables (`NPC-Index.md`, `Location-Index.md`, `Item-Index.md`) and three subfolders for the actual entity files (`NPCs/`, `Locations/`, `Items/`).

1. **Query First:** Before inventing a new entity, read the relevant Index file to see if an existing entity fits the role.
2. **Create the File:** If you must invent a new entity, you MUST create a dedicated Markdown file for them in the appropriate subfolder (e.g., `01-Campaign-Bible/Entities/NPCs/Name-of-NPC.md`). Give this file appropriate YAML frontmatter (`type: npc`, `canon_status: draft`).
3. **Update the Index:** After creating the individual file, you MUST append a wiki-link and a 1-sentence summary to the corresponding Index lookup table (e.g., `- [[Name-of-NPC]]: The grumpy blacksmith in Havenport.`).
4. **Strict Naming Rule:** You MUST NOT invent names yourself. You MUST roll/select a name from the provided tables in `00-System/Random-Tables/Name-Generation.md`.

# Hex Map Visualization (Text Mapper)
The campaign map is visually rendered using the Alpine Text Mapper syntax in `03-Hex-Map/Master-Map.txt`. 
- **The Header:** The file MUST always end with `include gnomeyland.txt`.
- **Syntax:** `[4-digit-coordinate] [color] [terrain/icon] "[Visible Label]"`
- **Strict Biome Vocabulary:** You MUST ONLY use the following exact combinations for your hexes to ensure they render properly on the web viewer:
  - **Coast / Ocean:** `water` (e.g., `0102 water "Whispering Cove"`)
  - **Forest:** `green forest` or `light-green fir-forest`
  - **Swamp:** `dark-grey swamp` or `grey swamp`
  - **Mountains:** `white mountain` or `light-grey mountain`
  - **Hills:** `light-grey forest-hill`
  - **Bastion / Settlement:** `soil town` or `green trees thorp`