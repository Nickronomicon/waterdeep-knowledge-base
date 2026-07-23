# TODO

Setup checklist for turning this repo into a working Waterdeep campaign wiki.

## Add Source Material

- [x] Add current character sheets for every player character.
  - Suggested location: `raw/notes/character-sheets/`
  - Include exported PDFs, markdown, text, screenshots, or whatever format is easiest to preserve.
- [ ] Add PC background notes and character arc notes.
  - Suggested location: `raw/notes/character-arcs/`
  - Include secrets, player goals, faction ties, bonds, unresolved hooks, and planned personal beats.
- [ ] Add existing DM session notes.
  - Suggested location: `raw/notes/session-notes/`
  - Include notes for session 1, since there is no transcript.
  - Include prep notes, post-session notes, private rulings, and any ad hoc recap documents.
- [x] Add any campaign planning notes that explain your version of the Remix.
  - Suggested location: `raw/notes/dm-planning/`
  - Include villain choices, faction changes, altered timelines, changed NPC motives, custom hooks, and table-specific canon.
- [x] Add any handouts, images, maps, tavern/business notes, or legal/financial documents created during play.
  - Suggested location: `raw/notes/handouts/`

Agents may read these files after you add them, but should never edit anything under `raw/`.

## Clarify Campaign Facts

- [x] Confirm the player character roster and exact spellings.
- [x] Map player names to character names, if useful for transcript interpretation.
- [x] Identify the speaker labels in the transcripts where possible. -- *UPDATE: Not really possible, transcript speaker labels are wildly innacurate*
- [x] Confirm current party level, current in-world date, and current real-world session cadence.
- [x] Confirm the party name, if any. -- *UPDATE: None yet*
- [x] Confirm the tavern name, if the group has chosen one. -- *UPDATE: Still Trollskull Manor for now*
- [ ] Record any known retcons or table rulings that should override transcript wording.
- [x] Decide whether the vault is entirely DM-facing or whether it will also contain player-safe handouts.  -- *UPDATE: This vault will contain player-facing handouts for record keeping, and will mark in yaml frontmatter if/when/to whom it was revealed, but this vault will be for DM consumption only*

## Initial Wiki Build

- [x] Ask Codex to inventory newly added `raw/notes/` files without editing them.
- [x] Ingest character sheets into `Waterdeep Knowledge Base/People/PCs/`.
- [x] Ingest background and character arc notes into PC pages and open-thread pages.
- [x] Ingest existing DM session notes before transcript ingest, so table canon and private prep are available.
- [x] Reconstruct `Sessions/Session 01` from notes, memory, and the session 2 recap.
- [x] Ingest recorded session 12. -- *UPDATE: Sessions 1-12 are ingested/reconstructed from currently available raw transcripts.*
- [x] Update people, factions, places, objects, and timeline pages as each session is processed. -- *UPDATE: Complete through session 12; current-state synthesis is now built for weekly use.*
- [x] Build `Dashboard/Current Campaign State`.
- [x] Expand `Dashboard/Open Threads` from session summaries.
- [x] Build `Timeline/Campaign Timeline`.
- [x] Build `Dashboard/Faction Clocks` from actual play plus the Remix.

## Remix and Adventure Reference

- [x] Ingest the Remix at a structural level. -- *UPDATE: Initial structural pass created overview, timelines, revelations, outposts, response teams, Eye heists, Golorr artifacts, and Stone pages.*
  - Villain goals.
  - Faction outposts.
  - Response teams.
  - Clue and revelation lists.
  - Eyes of the Stone.
  - Golorr artifacts.
  - Faction timelines.
  - Simple running checklist.
- [x] Cross-link Remix structures to the current campaign state.
- [x] Ingest original adventure reference only where it supports active play. -- *UPDATE: Added original adventure overview and lair/chapter backfill references for Remix-called structures.*
- [ ] Create quick-reference pages for frequently used Waterdeep law, wards, factions, NPCs, and locations.

## Begin Weekly Use

- [x] Create the first `Prep/Session Prep - YYYY-MM-DD.md` for the next scheduled session.
- [x] Use the prep page to produce:
  - recap bullets;
  - likely scenes;
  - active NPC agendas;
  - secrets and clues to reveal;
  - consequences waiting in the background;
  - maps, handouts, and stat blocks to review.
- [ ] After each future session, add the transcript and/or notes, then run a session ingest.
- [ ] Periodically ask Codex to lint the vault for stale facts, missing links, orphan pages, and unresolved threads.

## Repository Hygiene

- [ ] Confirm `.gitignore` excludes generated junk but keeps the vault, raw sources, and setup docs tracked as intended.
- [ ] Make an initial commit once the setup docs and source inventory look right.
- [ ] Commit after each meaningful ingest batch.
