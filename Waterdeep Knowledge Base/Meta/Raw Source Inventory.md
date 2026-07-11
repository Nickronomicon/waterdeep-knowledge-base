---
type: meta
status: current
updated: 2026-07-11
source_commit: 6fad85b plus current raw working tree
tags:
  - waterdeep
  - inventory
---

# Raw Source Inventory

Inventory of `../raw/` after commit `6fad85b`, updated for the current raw working tree. Raw sources were read and classified only; no files under `../raw/` were edited.

## Summary

`../raw/` currently contains 211 files:

| Extension | Count | Notes |
|---|---:|---|
| `.md` | 52 | Adventure markdown, roster/stats, DM notes, handouts, technical notes, character notes |
| `.pdf` | 6 | Remix PDF plus five level-3 character sheets |
| `.txt` | 11 | Text transcripts for Waterdeep sessions 2-12 |
| `.json` | 11 | JSON transcripts for Waterdeep sessions 2-12 |
| `.png` | 101 | Original adventure images and maps |
| `.jpg` | 30 | Original adventure images and maps |

## Top-Level Campaign Notes

| Path | Purpose | Ingest Use |
|---|---|---|
| `../raw/roster.md` | Player-to-character roster. Confirms Aladeen/Ankur, Broethuul/Tom, Davy/Hannah, Elior Thalosmere/Dane, Jonathan Usman Sonny Theodore Icarus Charles Eagleshield/Jake, and Nick as DM. | Use before transcript ingest and PC page creation. |
| `../raw/stats.md` | Current campaign status. Party name TBD, tavern still Trollskull Manor, party level 3, in-world date 5 Ches 1492 DR, next session 12 on 2026-07-09, aspirational weekly Thursday cadence. | Ingested into [[Dashboard/Current Campaign State]], [[Meta/Campaign Operations]], and [[Meta/DM Prep Source Map]]. |

## Technical and Process Notes

| Path | Purpose | Ingest Use |
|---|---|---|
| `../raw/notes/technical-notes.md` | How the remote campaign runs, Foundry/D&D Beyond source notes, transcript caveats, homebrew, Discord channel structure, document sharing, and DM note-taking caveats. | Ingested into [[Meta/Campaign Operations]] and used by [[Meta/DM Prep Source Map]]. Important warning: transcript diarization is unreliable. |
| `../raw/notes/discord-synopsis-channel.md` | Existing synopsis channel notes for sessions 1 and 2. Session 1 is especially important because there is no transcript. | Ingested into [[Sessions/Session 01 - 2026-02-15]], [[Sessions/Session 02 - 2026-02-22]], [[Dashboard/Player-Facing Synopsis]], and [[Meta/DM Prep Source Map]]. |

## Character Sources

### Character Sheets

| Path | Format | Purpose | Ingest Use |
|---|---|---|---|
| `../raw/notes/character-sheets/Aladeen-level-3.pdf` | PDF, 4 pages | Level-3 character sheet. | Ingested into [[People/PCs/Aladeen]]. |
| `../raw/notes/character-sheets/Broethuul-level-3.pdf` | PDF, 5 pages | Level-3 character sheet. | Ingested into [[People/PCs/Broethuul]]. |
| `../raw/notes/character-sheets/Broethuul-expanded.md` | Markdown, 49 lines | Expanded Broethuul background, personality traits, ideals, bonds, flaws, organizations, enemies, and backstory. | Ingested into [[People/PCs/Broethuul]]. |
| `../raw/notes/character-sheets/Davy-level-3.pdf` | PDF, 5 pages | Level-3 character sheet. | Ingested into [[People/PCs/Davy]]. |
| `../raw/notes/character-sheets/Elior-level-3.pdf` | PDF, 5 pages | Level-3 character sheet. | Ingested into [[People/PCs/Elior Thalosmere]]. |
| `../raw/notes/character-sheets/Jonathan-level-3.pdf` | PDF, 5 pages | Level-3 character sheet. | Ingested into [[People/PCs/Jonathan Usman Sonny Theodore Icarus Charles Eagleshield]]. |

### Character Arcs

| Path | Purpose | Ingest Use |
|---|---|---|
| `../raw/notes/character-arcs/davy-dm-notes.md` | DM-facing Davy material centered on Anastasia Crommor, including hooks and rumor vectors. | Ingested into [[People/PCs/Davy]], [[Threads/Davy Is Anastasia Crommor]], [[Threads/Crommor Incident]], [[Threads/Cassalanter Warning in the Bugle]], and related thread pages. |

## DM Planning Notes

These are aspirational prep sources. Per `AGENTS.md`, they may contradict transcripts because players may bypass, alter, or delay prepared material.

| Session | Paths | Ingest Use |
|---|---|---|
| Session 1 | `../raw/notes/dm-planning/session-1/opening-scene.md` | Ingested into [[Sessions/Session 01 - 2026-02-15]] and [[Meta/DM Prep Source Map]]. |
| Session 3 | `../raw/notes/dm-planning/session-3/prep-notes.md` | Ingested into [[Sessions/Session 03 - 2026-03-01]] and [[Meta/DM Prep Source Map]] as prep context to distinguish planned from actual. |
| Session 4 | `../raw/notes/dm-planning/session-4/prep_sheet.md`; `../raw/notes/dm-planning/session-4/session_4_notes.md`; `../raw/notes/dm-planning/session-4/traversing_blackstaff_tower.md`; `../raw/notes/dm-planning/session-4/vajra_recruitment.md` | Ingested into [[Sessions/Session 04 - 2026-03-22]] and [[Meta/DM Prep Source Map]]. Cross-check against actual transcript. |
| Session 5 | `../raw/notes/dm-planning/session-5/outline.md`; `../raw/notes/dm-planning/session-5/prep_sheet.md` | Ingested into [[Sessions/Session 05 - 2026-04-01]] and [[Meta/DM Prep Source Map]]. Actual play reached Blackstaff, Gray Hands, the Dock Ward grell, and crate clues; Rassal's Chandlery and opera slid forward. |
| Session 6 | `../raw/notes/dm-planning/session-6/lightsinger_theater.md`; `../raw/notes/dm-planning/session-6/run_sheet.md` | Ingested into [[Sessions/Session 06 - 2026-04-09]] and [[Meta/DM Prep Source Map]]. Actual play covered Trollskull follow-up, neighbors, Vajra report/payment, gazer research, and formalwear; theater/Mirt prep slid forward. |
| Session 7 | `../raw/notes/dm-planning/session-7/outline.md` | Ingested into [[Sessions/Session 07 - 2026-04-16]] and [[Meta/DM Prep Source Map]]. Actual play assigned the Maxeene mission but did not reach Thomril & Sons Cartage or the prepped Zhent response team. |
| Session 8 | `../raw/notes/dm-planning/session-8/outline.md` | Ingested into [[Sessions/Session 08 - 2026-04-30]] and [[Meta/DM Prep Source Map]]. |
| Session 10 | `../raw/notes/dm-planning/session-10/outline.md` | Ingested into [[Sessions/Session 10 - 2026-06-11]], [[Dashboard/Current Campaign State]], and [[Meta/DM Prep Source Map]]. |
| Session 11 | `../raw/notes/dm-planning/session-11/outline.md` | Ingested into [[Sessions/Session 11 - 2026-06-25]] and [[Meta/DM Prep Source Map]]. Current-state finalization intentionally deferred until after the post-ingestion commit. |
| Session 12 | `../raw/notes/dm-planning/session-12/outline.md`; `../raw/notes/dm-planning/session-12/force-grey.md` | Ingested into [[Sessions/Session 12 - 2026-07-09]] and [[Meta/DM Prep Source Map]]. Actual play used the loan/renovation and Force Grey harbor material, while the smuggler's-passage combat stayed unused. |

Missing planning folders for sessions 2 and 9 are expected from current raw contents.

## Handouts

These are record copies of player-facing or player-targeted handouts. The vault is DM-facing, but future handout pages should track YAML metadata for reveal status, recipient, and session when known.

| Path | Apparent Subject | Ingest Use |
|---|---|---|
| `../raw/notes/handouts/s0-aladeen-backstory.md` | Aladeen session-0 backstory, including Crommor-related material. | Ingested into [[People/PCs/Aladeen]], [[Threads/Aladeen and the Crommor Collapse]], and [[Threads/Crommor Incident]]. |
| `../raw/notes/handouts/s0-davy-backstory.md` | Davy session-0 backstory. | Ingested into [[People/PCs/Davy]], [[Threads/Davy Is Anastasia Crommor]], and [[Threads/Crommor Incident]]. |
| `../raw/notes/handouts/s0-elior-backstory.md` | Elior session-0 backstory. | Ingested into [[People/PCs/Elior Thalosmere]] and [[Threads/House Thalosmere Divine Correction]]. |
| `../raw/notes/handouts/s0-jonathan-backstory.md` | Jonathan/JUSTICE session-0 backstory. | Ingested into [[People/PCs/Jonathan Usman Sonny Theodore Icarus Charles Eagleshield]] and [[Threads/Jonathan and House Crommor]]. |
| `../raw/notes/handouts/s0-private-archive-house-thalosmere.md` | Private archive material for House Thalosmere. | Ingested into [[People/PCs/Elior Thalosmere]], [[Threads/House Thalosmere Divine Correction]], [[Threads/Crommor Incident]], and [[Threads/Cassalanter Warning in the Bugle]]. |
| `../raw/notes/handouts/s0-the-crommor-incident.md` | The Crommor Incident. | Ingested into the affected PC pages and [[Threads/Crommor Incident]]. |
| `../raw/notes/handouts/s0-what-broethuul-remembers.md` | Broethuul memory handout about the Crommor Incident. | Ingested into [[People/PCs/Broethuul]], [[Threads/Broethuul and the Autumn Court]], and [[Threads/Crommor Incident]]. |
| `../raw/notes/handouts/s4-businesses-of-trollskull-alley.md` | Businesses of Trollskull Alley. | Ingested into [[Places/Trollskull Alley]], [[Places/Corellon's Crown]], [[Places/Frewn's Brews]], and [[Sessions/Session 04 - 2026-03-22]]. |
| `../raw/notes/handouts/s6-cargo-chit.md` | Dockside transfer receipt. | Revealed during session 5 despite filename; ingested into [[Objects/Dockside Transfer Receipt]], [[Objects/Ironbound Grell Crate]], and [[Sessions/Session 05 - 2026-04-01]]. |
| `../raw/notes/handouts/s6-note-fragment.md` | Note fragment. | Revealed during session 5 despite filename; ingested into [[Objects/Loose It Then Leave Note Fragment]] and [[Sessions/Session 05 - 2026-04-01]]. |
| `../raw/notes/handouts/s7-scrap-of-note.md` | Scrap of note. | Revealed in session 7; ingested into [[Objects/Scrap of Note]]. |
| `../raw/notes/handouts/s9-Maxeene-info.md` | Maxeene information. | Revealed in session 9; ingested into [[Objects/Maxeene Information Handout]], [[People/NPCs/Maxeene]], [[People/NPCs/Remallia Haventree]], and clue tracking. |
| `../raw/notes/handouts/s9-thalosmere-archive-report.md` | Thalosmere archive report on Lady Remallia Haventree. | Revealed privately to Elior in session 9; ingested into [[Objects/Thalosmere Archive Report on Remallia Haventree]], [[People/PCs/Elior Thalosmere]], [[People/NPCs/Remallia Haventree]], and [[Threads/House Thalosmere Divine Correction]]. |
| `../raw/notes/handouts/s12-the-amberleaf-dispatch.md` | Amberleaf Dispatch, revealed privately to Broethuul in session 12. | Ingested into [[Objects/The Amberleaf Dispatch]], [[People/PCs/Broethuul]], and [[Threads/Broethuul and the Autumn Court]]. |
| `../raw/notes/handouts/the-amberleaf-dispatch-revealed.md` | Revealed Amberleaf Dispatch variant. | Tracked as related to [[Objects/The Amberleaf Dispatch]]; session 12 transcript did not establish every variant line as table-revealed. |
| `../raw/notes/handouts/the-crommor-warning.md` | Unrevealed Davy handout containing the recovered warning hidden inside the Crommor bugle for Laeral Silverhand. | Ingested into [[Objects/The Crommor Warning]], [[People/PCs/Davy]], [[Threads/Cassalanter Warning in the Bugle]], and [[Threads/Crommor Incident]]. |

## Session Transcripts

Recorded Waterdeep transcripts exist for sessions 2-12:

| Session | Text Path | JSON Path | Ingest Status |
|---|---|---|---|
| 2 | `../raw/text_transcripts/Waterdeep_Session_2_2026-02-22_17-27-38.txt` | `../raw/json_transcripts/Waterdeep_Session_2_2026-02-22_17-27-38.json` | Ingested into [[Sessions/Session 02 - 2026-02-22]]; JSON source is empty |
| 3 | `../raw/text_transcripts/Waterdeep_Session_3_2026-03-01_17-31-11.txt` | `../raw/json_transcripts/Waterdeep_Session_3_2026-03-01_17-31-11.json` | Ingested into [[Sessions/Session 03 - 2026-03-01]] |
| 4 | `../raw/text_transcripts/Waterdeep_Session_4_2026-03-22_18-18-25.txt` | `../raw/json_transcripts/Waterdeep_Session_4_2026-03-22_18-18-25.json` | Ingested into [[Sessions/Session 04 - 2026-03-22]] |
| 5 | `../raw/text_transcripts/Waterdeep_Session_5_2026-04-01_18-17-33.txt` | `../raw/json_transcripts/Waterdeep_Session_5_2026-04-01_18-17-33.json` | Ingested into [[Sessions/Session 05 - 2026-04-01]] |
| 6 | `../raw/text_transcripts/Waterdeep_Session_6_2026-04-09_18-17-17.txt` | `../raw/json_transcripts/Waterdeep_Session_6_2026-04-09_18-17-17.json` | Ingested into [[Sessions/Session 06 - 2026-04-09]] |
| 7 | `../raw/text_transcripts/Waterdeep_Session_7_2026-04-16_18-09-58.txt` | `../raw/json_transcripts/Waterdeep_Session_7_2026-04-16_18-09-58.json` | Ingested into [[Sessions/Session 07 - 2026-04-16]] |
| 8 | `../raw/text_transcripts/Waterdeep_Session_8_2026-04-30_18-09-18.txt` | `../raw/json_transcripts/Waterdeep_Session_8_2026-04-30_18-09-18.json` | Ingested into [[Sessions/Session 08 - 2026-04-30]] |
| 9 | `../raw/text_transcripts/Waterdeep_Session_9_2026-05-07_18-24-35.txt` | `../raw/json_transcripts/Waterdeep_Session_9_2026-05-07_18-24-35.json` | Ingested into [[Sessions/Session 09 - 2026-05-07]] |
| 10 | `../raw/text_transcripts/Waterdeep_Session_10_2026-06-11_18-06-12.txt` | `../raw/json_transcripts/Waterdeep_Session_10_2026-06-11_18-06-12.json` | Ingested into [[Sessions/Session 10 - 2026-06-11]] |
| 11 | `../raw/text_transcripts/Waterdeep_Session_11_2026-06-25_18-18-12.txt` | `../raw/json_transcripts/Waterdeep_Session_11_2026-06-25_18-18-12.json` | Ingested into [[Sessions/Session 11 - 2026-06-25]] |
| 12 | `../raw/text_transcripts/Waterdeep_Session_12_2026-07-09_18-20-21.txt` | `../raw/json_transcripts/Waterdeep_Session_12_2026-07-09_18-20-21.json` | Ingested into [[Sessions/Session 12 - 2026-07-09]] |

Important caveat from `../raw/notes/technical-notes.md`: transcript speaker labels are unreliable and should not be treated as stable evidence of who spoke.

## Adventure Sources

| Path | Purpose | Ingest Use |
|---|---|---|
| `../raw/Dragon-Heist-Remix.pdf` | Justin Alexander's *Dragon Heist Remix*, 337 pages. | Primary structural adventure reference. Ingest as runnable structures, not long prose. |
| `../raw/waterdeep_dragon_heist/` | Original adventure markdown plus 131 image/map files. | Supporting canon, NPC/place/stat reference, maps, handout art, and Trollskull Alley reference. |

Original adventure markdown files:

- `../raw/waterdeep_dragon_heist/00.Introduction.md`
- `../raw/waterdeep_dragon_heist/01.A-Friend-In-Need.md`
- `../raw/waterdeep_dragon_heist/02.Trollskull-Alley.md`
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

## Recommended Ingest Order

1. Create the first weekly prep page when the session 13 date is known.
2. Expand active adventure-reference pages into prep cards as Fireball, Gralhund Villa, faction outposts, or Eye heists approach.
3. Continue ingesting active handouts/clue objects as they arise during session ingest.
4. Add quick references for Waterdeep wards, law, faction missions, and frequently used NPC/stat lookups as active prep requires them.
5. Periodically lint the vault for stale facts, missing links, orphan pages, and unresolved threads.
