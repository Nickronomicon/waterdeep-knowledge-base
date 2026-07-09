---
type: meta
status: current
updated: 2026-07-09
source_commit: 5fdbc
tags:
  - waterdeep
  - inventory
---

# Raw Source Inventory

Inventory of `../raw/` after commit `5fdbc1b` (`Begins addressing items in TODO.md.`). Raw sources were read and classified only; no files under `../raw/` were edited.

## Summary

`../raw/` currently contains 205 files:

| Extension | Count | Notes |
|---|---:|---|
| `.md` | 48 | Adventure markdown, roster/stats, DM notes, handouts, technical notes, character notes |
| `.pdf` | 6 | Remix PDF plus five level-3 character sheets |
| `.txt` | 10 | Text transcripts for Waterdeep sessions 2-11 |
| `.json` | 10 | JSON transcripts for Waterdeep sessions 2-11 |
| `.png` | 101 | Original adventure images and maps |
| `.jpg` | 30 | Original adventure images and maps |

## Top-Level Campaign Notes

| Path | Purpose | Ingest Use |
|---|---|---|
| `../raw/roster.md` | Player-to-character roster. Confirms Aladeen/Ankur, Broethuul/Tom, Davy/Hannah, Elior Thalosmere/Dane, Jonathan Usman Sonny Theodore Icarus Charles Eagleshield/Jake, and Nick as DM. | Use before transcript ingest and PC page creation. |
| `../raw/stats.md` | Current campaign status. Party name TBD, tavern still Trollskull Manor, party level 3, in-world date 5 Ches 1492 DR, next session 12 on 2026-07-09, aspirational weekly Thursday cadence. | Seed `Dashboard/Current Campaign State` and session prep. |

## Technical and Process Notes

| Path | Purpose | Ingest Use |
|---|---|---|
| `../raw/notes/technical-notes.md` | How the remote campaign runs, Foundry/D&D Beyond source notes, transcript caveats, homebrew, Discord channel structure, document sharing, and DM note-taking caveats. | Update AGENTS assumptions and/or create `Meta/Campaign Operations` later. Important warning: transcript diarization is unreliable. |
| `../raw/notes/discord-synopsis-channel.md` | Existing synopsis channel notes for sessions 1 and 2. Session 1 is especially important because there is no transcript. | Primary source for reconstructing `Sessions/Session 01`; supporting source for session 2 ingest. |

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
| Session 1 | `../raw/notes/dm-planning/session-1/opening-scene.md` | Reconstruct missing session 1 alongside the Discord synopsis and session 2 recap. |
| Session 3 | `../raw/notes/dm-planning/session-3/prep-notes.md` | Prep context for session 3; very large source. Use after transcript pass to distinguish planned from actual. |
| Session 4 | `../raw/notes/dm-planning/session-4/prep_sheet.md`; `../raw/notes/dm-planning/session-4/session_4_notes.md`; `../raw/notes/dm-planning/session-4/traversing_blackstaff_tower.md`; `../raw/notes/dm-planning/session-4/vajra_recruitment.md` | Major prep bundle for Blackstaff/Vajra material, session-4 events, and possible faction recruitment. Cross-check against actual transcript. |
| Session 5 | `../raw/notes/dm-planning/session-5/outline.md`; `../raw/notes/dm-planning/session-5/prep_sheet.md` | Session 5 prep and outline. Use during session 5 ingest after transcript. |
| Session 6 | `../raw/notes/dm-planning/session-6/lightsinger_theater.md`; `../raw/notes/dm-planning/session-6/run_sheet.md` | Lightsinger Theater, Mirt/Harper material, opera/intermission scenes, spy/chase/ambush material. Cross-check actual reveal status. |
| Session 7 | `../raw/notes/dm-planning/session-7/outline.md` | Thomril & Sons Cartage, Maxeene, and a Zhent response-team setup. |
| Session 8 | `../raw/notes/dm-planning/session-8/outline.md` | Remallia Haventree introduction and Underbough hiring/sabotage setup. |
| Session 10 | `../raw/notes/dm-planning/session-10/outline.md` | Short outline source for session 10. |
| Session 11 | `../raw/notes/dm-planning/session-11/outline.md` | Dinner party menu, rat interruption, Underbough hiring decision, and next-day Cassalanter loan signing setup. |

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
| `../raw/notes/handouts/s4-businesses-of-trollskull-alley.md` | Businesses of Trollskull Alley. | Places pages for Trollskull Alley businesses. |
| `../raw/notes/handouts/s6-cargo-chit.md` | Dockside transfer receipt. | Object/clue page; connect to session 6 if actually revealed. |
| `../raw/notes/handouts/s6-note-fragment.md` | Note fragment. | Object/clue page; connect to session 6 if actually revealed. |
| `../raw/notes/handouts/s7-scrap-of-note.md` | Scrap of note. | Object/clue page; connect to session 7 if actually revealed. |
| `../raw/notes/handouts/s9-Maxeene-info.md` | Maxeene information. | NPC/page update for Maxeene and clue tracking. |
| `../raw/notes/handouts/s9-thalosmere-archive-report.md` | Thalosmere archive report on Lady Remallia Haventree. | Remallia, Harpers, and Elior/Thalosmere pages. |
| `../raw/notes/handouts/the-amberleaf-dispatch.md` | Amberleaf Dispatch. | Object/handout page; track encoded or partial state. |
| `../raw/notes/handouts/the-amberleaf-dispatch-revealed.md` | Revealed Amberleaf Dispatch. | Object/handout page; track decoded/revealed state and recipients. |

## Session Transcripts

Recorded Waterdeep transcripts exist for sessions 2-11:

| Session | Text Path | JSON Path | Ingest Status |
|---|---|---|---|
| 2 | `../raw/text_transcripts/Waterdeep_Session_2_2026-02-22_17-27-38.txt` | `../raw/json_transcripts/Waterdeep_Session_2_2026-02-22_17-27-38.json` | Not ingested |
| 3 | `../raw/text_transcripts/Waterdeep_Session_3_2026-03-01_17-31-11.txt` | `../raw/json_transcripts/Waterdeep_Session_3_2026-03-01_17-31-11.json` | Not ingested |
| 4 | `../raw/text_transcripts/Waterdeep_Session_4_2026-03-22_18-18-25.txt` | `../raw/json_transcripts/Waterdeep_Session_4_2026-03-22_18-18-25.json` | Not ingested |
| 5 | `../raw/text_transcripts/Waterdeep_Session_5_2026-04-01_18-17-33.txt` | `../raw/json_transcripts/Waterdeep_Session_5_2026-04-01_18-17-33.json` | Not ingested |
| 6 | `../raw/text_transcripts/Waterdeep_Session_6_2026-04-09_18-17-17.txt` | `../raw/json_transcripts/Waterdeep_Session_6_2026-04-09_18-17-17.json` | Not ingested |
| 7 | `../raw/text_transcripts/Waterdeep_Session_7_2026-04-16_18-09-58.txt` | `../raw/json_transcripts/Waterdeep_Session_7_2026-04-16_18-09-58.json` | Not ingested |
| 8 | `../raw/text_transcripts/Waterdeep_Session_8_2026-04-30_18-09-18.txt` | `../raw/json_transcripts/Waterdeep_Session_8_2026-04-30_18-09-18.json` | Not ingested |
| 9 | `../raw/text_transcripts/Waterdeep_Session_9_2026-05-07_18-24-35.txt` | `../raw/json_transcripts/Waterdeep_Session_9_2026-05-07_18-24-35.json` | Not ingested |
| 10 | `../raw/text_transcripts/Waterdeep_Session_10_2026-06-11_18-06-12.txt` | `../raw/json_transcripts/Waterdeep_Session_10_2026-06-11_18-06-12.json` | Not ingested |
| 11 | `../raw/text_transcripts/Waterdeep_Session_11_2026-06-25_18-18-12.txt` | `../raw/json_transcripts/Waterdeep_Session_11_2026-06-25_18-18-12.json` | Not ingested |

Important caveat from `../raw/notes/technical-notes.md`: transcript speaker labels are unreliable and should not be treated as stable evidence of who spoke.

## Adventure Sources

| Path | Purpose | Ingest Use |
|---|---|---|
| `../raw/Dragon-Heist-Remix.pdf` | Justin Alexander's *Dragon Heist Remix*, 337 pages. | Primary structural adventure reference. Ingest as runnable structures, not long prose. |
| `../raw/waterdeep_dragon_heist/` | Original adventure markdown plus 131 image/map files. | Supporting canon, NPC/place/stat reference, maps, and handout art. |

Original adventure markdown files:

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

## Recommended Ingest Order

1. `../raw/roster.md`, `../raw/stats.md`, and `../raw/notes/technical-notes.md`.
2. `../raw/notes/discord-synopsis-channel.md` and `../raw/notes/dm-planning/session-1/opening-scene.md` to reconstruct session 1.
3. Session transcripts 2-11, each paired with same-session prep notes when available.
4. Active handouts/clue objects as they arise during session ingest.
5. Remix structures and original adventure reference pages once current campaign state is established.
