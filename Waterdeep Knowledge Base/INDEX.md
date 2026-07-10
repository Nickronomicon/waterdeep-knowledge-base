# Waterdeep Knowledge Base Index

This is the content map for the Obsidian vault. It should be updated whenever the wiki gains, loses, renames, or substantially revises pages.

## Current Status

- Vault initialized: 2026-07-09.
- Transcript ingest has started; sessions 1 through 3 are ingested/reconstructed.
- DM prep notes have been scaffolded into session pages and [[Meta/DM Prep Source Map]].
- Session 1 is not available in the recorded transcript sources.
- Waterdeep session transcripts are available for sessions 2 through 11; sessions 2 and 3 are ingested.
- The adventure should be tracked through the *Dragon Heist Remix* first, with the original `waterdeep_dragon_heist` markdown as supporting reference.
- Raw sources live outside the vault in `../raw/` and are read-only.

## Start Here

- [[AGENTS]] - operating rules, source hierarchy, page conventions, and workflows.
- [[INDEX]] - this file.
- [[CHANGELOG]] - append-only history of knowledge-base maintenance.
- [[Meta/Raw Source Inventory]] - classified inventory of files under `../raw/`.
- [[Meta/Campaign Operations]] - transcript ingest guardrails, campaign logistics, and source authority notes.
- [[Meta/DM Prep Source Map]] - session-by-session map of DM prep sources, likely handouts, and transcript ingest focus.
- [[Dashboard/Player-Facing Synopsis]] - spoiler-safe campaign recap prose suitable for posting between sessions.

## Planned Dashboards

These pages should be created or finalized during the first campaign ingest or first prep pass:

- [[Dashboard/Current Campaign State]] - pre-transcript current-state scaffold from stats and latest DM prep.
- [[Dashboard/Next Session]] - current weekly prep landing page or pointer to the active prep note.
- [[Dashboard/Open Threads]] - unresolved hooks, promises, mysteries, obligations, and dangling consequences.
- [[Dashboard/Player-Facing Synopsis]] - Discord-postable player recap, updated after each session ingest.
- [[Dashboard/Faction Clocks]] - live faction agendas and escalation timers.
- [[Timeline/Campaign Timeline]] - chronological campaign record.

## Source Inventory

### Primary Adventure Sources

- `../raw/Dragon-Heist-Remix.pdf` - Justin Alexander's Remix PDF; 337 pages; primary structural source for the campaign.
- `../raw/waterdeep_dragon_heist/` - original adventure markdown, images, maps, NPCs, magic items, and handouts.

### Original Adventure Markdown

- `../raw/waterdeep_dragon_heist/00.Introduction.md`
- `../raw/waterdeep_dragon_heist/01.A-Friend-In-Need.md`
- `../raw/waterdeep_dragon_heist/03.Fireball.md`
- `../raw/waterdeep_dragon_heist/04.Dragon-Season.md`
- `../raw/waterdeep_dragon_heist/05.Spring-Madness.md`
- `../raw/waterdeep_dragon_heist/06.Hell-of-a-Summer.md`
- `../raw/waterdeep_dragon_heist/07.Maestros-Fall.md`
- `../raw/waterdeep_dragon_heist/08.Winter-Wizardry.md`
- `../raw/waterdeep_dragon_heist/09.Volos-Waterdeep-Enchiridion.md`
- `../raw/waterdeep_dragon_heist/Contents.md`
- `../raw/waterdeep_dragon_heist/Handouts.md`
- `../raw/waterdeep_dragon_heist/Magic-Items.md`
- `../raw/waterdeep_dragon_heist/Monsters-and-NPCs.md`
- `../raw/waterdeep_dragon_heist/images/` - maps, portraits, handout art, and location images.

### Transcript Sources

Use text transcripts for normal reading. Use JSON transcripts when timestamps or segment boundaries matter.

| Session | Real Date | Text Source | JSON Source | Status |
|---|---:|---|---|---|
| Session 1 | 2026-02-15 | Not available | Not available | Reconstructed |
| Session 2 | 2026-02-22 | `../raw/text_transcripts/Waterdeep_Session_2_2026-02-22_17-27-38.txt` | `../raw/json_transcripts/Waterdeep_Session_2_2026-02-22_17-27-38.json` | Ingested; JSON source empty |
| Session 3 | 2026-03-01 | `../raw/text_transcripts/Waterdeep_Session_3_2026-03-01_17-31-11.txt` | `../raw/json_transcripts/Waterdeep_Session_3_2026-03-01_17-31-11.json` | Ingested |
| Session 4 | 2026-03-22 | `../raw/text_transcripts/Waterdeep_Session_4_2026-03-22_18-18-25.txt` | `../raw/json_transcripts/Waterdeep_Session_4_2026-03-22_18-18-25.json` | Prep scaffolded; transcript not ingested |
| Session 5 | 2026-04-01 | `../raw/text_transcripts/Waterdeep_Session_5_2026-04-01_18-17-33.txt` | `../raw/json_transcripts/Waterdeep_Session_5_2026-04-01_18-17-33.json` | Prep scaffolded; transcript not ingested |
| Session 6 | 2026-04-09 | `../raw/text_transcripts/Waterdeep_Session_6_2026-04-09_18-17-17.txt` | `../raw/json_transcripts/Waterdeep_Session_6_2026-04-09_18-17-17.json` | Prep scaffolded; transcript not ingested |
| Session 7 | 2026-04-16 | `../raw/text_transcripts/Waterdeep_Session_7_2026-04-16_18-09-58.txt` | `../raw/json_transcripts/Waterdeep_Session_7_2026-04-16_18-09-58.json` | Prep scaffolded; transcript not ingested |
| Session 8 | 2026-04-30 | `../raw/text_transcripts/Waterdeep_Session_8_2026-04-30_18-09-18.txt` | `../raw/json_transcripts/Waterdeep_Session_8_2026-04-30_18-09-18.json` | Prep scaffolded; transcript not ingested |
| Session 9 | 2026-05-07 | `../raw/text_transcripts/Waterdeep_Session_9_2026-05-07_18-24-35.txt` | `../raw/json_transcripts/Waterdeep_Session_9_2026-05-07_18-24-35.json` | Prep scaffolded; transcript not ingested |
| Session 10 | 2026-06-11 | `../raw/text_transcripts/Waterdeep_Session_10_2026-06-11_18-06-12.txt` | `../raw/json_transcripts/Waterdeep_Session_10_2026-06-11_18-06-12.json` | Prep scaffolded; transcript not ingested |
| Session 11 | 2026-06-25 | `../raw/text_transcripts/Waterdeep_Session_11_2026-06-25_18-18-12.txt` | `../raw/json_transcripts/Waterdeep_Session_11_2026-06-25_18-18-12.json` | Prep scaffolded; transcript not ingested |

### Non-Campaign or Unclassified Sources

- `../raw/roster.md` - player-to-character roster.
- `../raw/stats.md` - current party/campaign status.
- `../raw/notes/technical-notes.md` - remote play, Foundry/D&D Beyond, transcript caveats, Discord setup, and DM note-taking caveats; ingested into [[Meta/Campaign Operations]].
- `../raw/notes/discord-synopsis-channel.md` - existing synopsis notes for sessions 1 and 2; ingested into [[Sessions/Session 01 - 2026-02-15]], [[Sessions/Session 02 - 2026-02-22]], [[Dashboard/Player-Facing Synopsis]], and [[Meta/DM Prep Source Map]].
- `../raw/notes/character-sheets/` - level-3 character sheets and Broethuul expanded character notes.
- `../raw/notes/character-arcs/` - DM-facing character arc notes; currently Davy.
- `../raw/notes/dm-planning/` - aspirational DM prep notes for sessions 1, 3, 4, 5, 6, 7, 8, 10, and 11; scaffolded into session pages and [[Meta/DM Prep Source Map]].
- `../raw/notes/handouts/` - record copies of session-0 backstory handouts, in-game clue handouts, and other player-facing documents.
- See [[Meta/Raw Source Inventory]] for the detailed classified source map.

## Campaign Pages

Initial PC pages have been generated from level-3 character-sheet sources and updated with session-0 background and character arc notes.

As pages are created, maintain these sections:

### Sessions

- Session pages live in `Sessions/`.
- Current scaffold pages:
  - [[Sessions/Session 01 - 2026-02-15]]
  - [[Sessions/Session 02 - 2026-02-22]]
  - [[Sessions/Session 03 - 2026-03-01]]
  - [[Sessions/Session 04 - 2026-03-22]]
  - [[Sessions/Session 05 - 2026-04-01]]
  - [[Sessions/Session 06 - 2026-04-09]]
  - [[Sessions/Session 07 - 2026-04-16]]
  - [[Sessions/Session 08 - 2026-04-30]]
  - [[Sessions/Session 09 - 2026-05-07]]
  - [[Sessions/Session 10 - 2026-06-11]]
  - [[Sessions/Session 11 - 2026-06-25]]

### Player Characters

Pages under `People/PCs/`:

- [[People/PCs/Aladeen]]
- [[People/PCs/Broethuul]]
- [[People/PCs/Davy]]
- [[People/PCs/Elior Thalosmere]]
- [[People/PCs/Jonathan Usman Sonny Theodore Icarus Charles Eagleshield]]

### Open Threads

- [[Dashboard/Open Threads]]
- [[Threads/Crommor Incident]]
- [[Threads/Davy Is Anastasia Crommor]]
- [[Threads/Cassalanter Warning in the Bugle]]
- [[Threads/Aladeen and the Crommor Collapse]]
- [[Threads/Jonathan and House Crommor]]
- [[Threads/House Thalosmere Divine Correction]]
- [[Threads/Broethuul and the Autumn Court]]
- [[Threads/Floon Rescue]]
- [[Threads/Zhentarim-Xanathar Street War]]
- [[Threads/Neverember Cache and Renaer's Locket]]

### NPCs

Create pages under `People/NPCs/`. Early expected pages include:

- [[People/NPCs/Volo]]
- [[People/NPCs/Floon Blagmaar]]
- [[People/NPCs/Renaer Neverember]]
- [[People/NPCs/Durnan]]
- [[People/NPCs/Yagra Stonefist]]
- [[People/NPCs/Krentz]]
- [[People/NPCs/Xoblob]]
- [[People/NPCs/Bonnie]]
- [[People/NPCs/Threestrings]]
- [[People/NPCs/Hustus Staget]]
- [[People/NPCs/Nihiloor]]
- [[People/NPCs/Grum'shar]]
- [[People/NPCs/Lif]]
- [[People/NPCs/Fala Lefaliir]]
- [[People/NPCs/Victoro Cassalanter]]
- [[People/NPCs/Ammalia Cassalanter]]
- [[People/NPCs/Dorger]]

Verify spelling and table-specific details against transcripts before treating any page as stable.

### Factions

Create pages under `Factions/`. Expected major pages:

- [[Factions/Xanathar Guild]]
- [[Factions/Zhentarim]]
- [[Factions/City Watch]]
- [[Factions/Cassalanters]]
- [[Factions/Bregan D'aerthe]]
- [[Factions/Lords' Alliance]]
- [[Factions/Gray Hands]]
- [[Factions/Order of the Gauntlet]]
- [[Factions/Harpers]]
- [[Factions/Emerald Enclave]]

### Places

Create pages under `Places/`. Expected early pages:

- [[Places/Waterdeep]]
- [[Places/Yawning Portal]]
- [[Places/Dock Ward]]
- [[Places/Skewered Dragon]]
- [[Places/Old Xoblob Shop]]
- [[Places/Candle Lane]]
- [[Places/Candle Lane Zhentarim Warehouse]]
- [[Places/Xanathar Sewer Hideout]]
- [[Places/Trollskull Manor]]
- [[Places/Trollskull Alley]]
- [[Places/Cassalanter Villa]]

### Objects, Clues, and Obligations

Create pages under `Objects/` for durable campaign objects and paperwork:

- [[Objects/Stone of Golorr]]
- [[Objects/Dragonstaff of Ahghairon]]
- [[Objects/Trollskull Manor Deed]]
- [[Objects/Cassalanter Loan]]
- [[Objects/Seance Candle]]
- [[Objects/The Crommor Warning]]
- [[Objects/Floon's Unicorn Necklace]]
- [[Objects/Renaer's Locket]]
- [[Objects/Magical Paper from Candle Lane Warehouse]]
- [[Objects/Grum'shar's Spellbook]]

### Timeline

- [[Timeline/Campaign Timeline]]

### Reference

Create synthesized adventure reference pages under `Reference/` as needed:

- [[Reference/Dragon Heist Remix Overview]]
- [[Reference/Remix Revelation Lists]]
- [[Reference/Remix Faction Timelines]]
- [[Reference/Original Adventure Overview]]
- [[Reference/Waterdeep Code Legal]]

## Immediate Backlog

1. Complete the setup checklist in `../TODO.md`.
2. Ingest sessions 4 through 11 in chronological order, pairing transcripts with [[Meta/DM Prep Source Map]].
3. Continue expanding people, factions, places, objects, and timeline pages as each session is processed.
4. Finalize [[Dashboard/Current Campaign State]] after session 11 is processed.
5. Build a first [[Dashboard/Faction Clocks]] page using transcripts plus Remix structure.
6. Create a weekly prep workflow page once the next real session date is known.
7. Ingest the Remix at the structural level: villains, clues, faction outposts, faction response teams, Eyes of the Stone, Golorr artifacts, and simple checklist.

## Maintenance Notes

- Keep this index content-oriented, not chronological.
- Keep source processing status accurate.
- Prefer links to missing but planned pages over silent omission; Obsidian makes these useful.
- Do not let the index become a session recap. Session content belongs in `Sessions/` and dashboards.
