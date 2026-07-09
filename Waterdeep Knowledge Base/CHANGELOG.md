# Waterdeep Knowledge Base Changelog

This is the append-only maintenance log for the vault. Add a new entry after every ingest, restructuring pass, lint pass, weekly prep pass, or substantial answer that gets filed back into the knowledge base.

Use this format:

```markdown
## [YYYY-MM-DD] kind | Short title

- Summary of what changed.
- Pages created or updated.
- Sources read.
- Follow-up work.
```

Recommended `kind` values: `setup`, `ingest`, `prep`, `lint`, `query`, `refactor`, `decision`.

## [2026-07-09] ingest | Add PC player names

- Used `../raw/roster.md` to fill the `player` field on the five generated PC pages.
- Added `../raw/roster.md` to each PC page's source list.
- Current roster mapping: Aladeen/Ankur, Broethuul/Tom, Davy/Hannah, Elior Thalosmere/Dane, and Jonathan Usman Sonny Theodore Icarus Charles Eagleshield/Jake.

Follow-up:

- If the roster changes again, update the PC page frontmatter and this mapping.

## [2026-07-09] ingest | Character sheets

- Created PC pages under `People/PCs/` for Aladeen, Broethuul, Davy, Elior Thalosmere, and Jonathan Usman Sonny Theodore Icarus Charles Eagleshield.
- Ingested the five level-3 PDF character sheets from `../raw/notes/character-sheets/`.
- Ingested `../raw/notes/character-sheets/Broethuul-expanded.md` into Broethuul's PC page because it supplements text cut off by the exported PDF.
- Updated `INDEX.md` to list the generated PC pages and adjust the immediate backlog.
- Updated [[Meta/Raw Source Inventory]] to mark character-sheet sources as ingested.
- Marked the character-sheet ingest task complete in `../TODO.md`.

Follow-up:

- Ingest character arc notes, especially `../raw/notes/character-arcs/davy-dm-notes.md`.
- Ingest session-0/backstory handouts for richer PC arc pages and open threads.

## [2026-07-09] setup | Inventory raw source files

- Created [[Meta/Raw Source Inventory]] to classify the current `../raw/` tree after commit `5fdbc1b`.
- Confirmed `../raw/` currently contains 205 files: 48 markdown, 6 PDFs, 10 text transcripts, 10 JSON transcripts, 101 PNGs, and 30 JPGs.
- Added the new campaign-owned raw sources to `INDEX.md`: roster, stats, technical notes, Discord synopsis, character sheets, character arcs, DM planning notes, and handouts.
- Updated the confirmed PC roster in `INDEX.md`.
- Refined the immediate backlog around the recommended ingest order from the inventory.
- Marked the raw inventory task complete in `../TODO.md`.

Follow-up:

- Ingest roster, stats, and technical notes into current-state and operations pages.
- Create PC pages from character sheets and backstory/arc sources.

## [2026-07-09] setup | Add project setup checklist

- Added `../TODO.md` as the top-level setup checklist for collecting character sheets, character arc notes, DM notes, existing session notes, and handouts before full ingest.
- Updated `INDEX.md` to remove the stale unrelated playtest transcript reference after the source was deleted.
- Updated `INDEX.md` to point the immediate backlog at the new setup checklist and the `../raw/notes/` source collection step.

Follow-up:

- Add user-owned source files under `../raw/notes/`.
- Inventory the newly added sources before starting session ingest.

## [2026-07-09] setup | Initialize vault operating files

- Created the canonical vault guide, index, and changelog.
- Established the raw-source rule: files under `../raw/` may be read but never edited, moved, renamed, reformatted, or used as scratch space.
- Set the source hierarchy for campaign truth: user direction, table transcripts, DM prep, Dragon Heist Remix, then original adventure reference.
- Inventoried available Waterdeep transcripts for sessions 2 through 11 and marked session 1 as missing.
- Identified `../raw/Dragon-Heist-Remix.pdf` as the primary adventure structure source and `../raw/waterdeep_dragon_heist/` as supporting original adventure reference.
- Noted `Here_Lies_Playtest_1-2026-05-28_18-10-07.txt` as likely unrelated and not to be ingested unless requested.
- Added root-level pointer files so future agents starting from the workspace root can find the canonical vault docs and the read-only `raw/` rule.

Follow-up:

- Ingest session transcripts in chronological order.
- Reconstruct session 1 from the session 2 recap and user memory.
- Create the first current-state dashboard after latest-session ingest.
- Ingest the Remix as runnable structures rather than long copied prose.
