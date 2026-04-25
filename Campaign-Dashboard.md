# 📋 Havenport Bounty Board

*This is your automated mission control. Take a screenshot of the "Open Bounties" section and drop it into your group chat when asking your West Marches players where they want to go next.*

---

## 🟢 Open Bounties (Menu of Three)

```dataview
TABLE 
  giving_faction AS "Client Faction", 
  target_hex AS "Target Location"
FROM "04-Missions"
WHERE type = "mission" AND status = "open"
SORT file.ctime ASC
```

---

## 🔴 Completed / Archived Missions

```dataview
TABLE 
  giving_faction AS "Client Faction", 
  target_hex AS "Target Location"
FROM "04-Missions"
WHERE type = "mission" AND (status = "completed" OR status = "archived")
SORT file.mtime DESC
```

---

## ⏱️ Active Faction Clocks
*Quick reference for which factions are making moves behind the scenes.*

```dataview
TABLE 
  "[" + file.link + "]" AS "Faction"
FROM "00-System/Active-Clocks.md"
```
*(Note: Because your active clocks are currently stored in a single markdown file, you can easily open `Active-Clocks.md` directly from this link to tick the clocks forward after a session.)*