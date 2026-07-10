# Waterdeep Knowledge Base Agent Guide

This vault is a living, LLM-maintained campaign wiki for an ongoing Dungeons & Dragons campaign set in Waterdeep. The DM is running *Waterdeep: Dragon Heist* using Justin Alexander's *Dragon Heist Remix* as the primary scenario structure, with actual table events recorded in session transcripts.

The job of the agent is to maintain the wiki as a compiled campaign memory: summarize sessions, track current state, update people/places/factions/objects, preserve unresolved threads, and help prepare weekly sessions. The agent writes the wiki. The user curates direction, sources, and judgment calls.

## Non-Negotiables

- Never edit anything under `../raw/`.
- Never move, rename, delete, reformat, clean, normalize, or add metadata to files under `../raw/`.
- Never use `../raw/` as scratch space or output space.
- Generated and maintained notes belong in this Obsidian vault, `../Waterdeep Knowledge Base/`.
- Treat transcripts as imperfect but important evidence. Note uncertainty rather than silently resolving ambiguous speech, names, or chronology.
- Avoid copying long passages from published adventure sources or the Remix into the vault. Summarize, cite the raw path, and preserve only short excerpts when genuinely useful.
- Assume this vault is DM-facing and spoiler-permissive unless the user explicitly asks for a player-safe note or handout.

## Source Priority

When sources conflict, use this priority order:

1. Direct user instructions in the current conversation.
2. Established table truth from session transcripts and prior maintained vault notes.
3. The DM's stated campaign direction and prep notes.
4. `../raw/Dragon-Heist-Remix.pdf`, as the main adventure framework.
5. `../raw/waterdeep_dragon_heist/`, as the original adventure reference and setting backfill.

If a conflict matters, record it in the relevant page under `Uncertainties`, `Retcons`, or `DM Decision Needed`.

> N.B. DM's session prep will often contradict the transcripts, as the prep notes are purely aspirational. Players may deviate entirely from the planned session, or prepped material from one session may spill over into another. Some items may or may not have been revealed to the characters, and as the story progresses, anything captured in prep that was not presented to the players is treated as fungible and may change or be dropped entirely.

## Canonical Files

Read these first at the start of any substantial work:

- `AGENTS.md` - operating rules and workflows.
- `INDEX.md` - content map, source inventory, and processing status.
- `CHANGELOG.md` - append-only history of wiki work.

Update `INDEX.md` whenever pages are created, moved, renamed, substantially revised, or newly categorized. Append to `CHANGELOG.md` after every ingest, lint pass, restructuring pass, or major planning pass.

## Vault Shape

Use these folders as the wiki grows:

- `Dashboard/` - current campaign state, next-session prep, open loops, faction clocks.
- `Sessions/` - session summaries, transcripts-derived notes, session-by-session decisions.
- `People/PCs/` - player characters.
- `People/NPCs/` - non-player characters, including canon NPCs and table-created NPCs.
- `Factions/` - Waterdeep factions, villain factions, response teams, and local power groups.
- `Places/` - locations, wards, businesses, lairs, faction outposts, and route notes.
- `Objects/` - artifacts, clues, handouts, magic items, legal/business documents, and notable mundane objects.
- `Timeline/` - campaign chronology, in-world dates, faction timelines, and event chains.
- `Prep/` - weekly prep pages, scene menus, encounter notes, clue lists, and recap drafts.
- `Reference/` - synthesized reference pages from the Remix and original adventure.
- `Meta/` - wiki maintenance notes, templates, lint reports, and naming conventions.

Do not create a folder just because it is listed here. Create it when there is a real page to put inside it.

## Page Conventions

Use Obsidian wikilinks for vault pages:

- `[[Renaer Neverember]]`
- `[[Trollskull Manor]]`
- `[[Xanathar Guild]]`

Use normal markdown links or code-formatted paths for raw source references, because raw files live outside the vault:

- `../raw/text_transcripts/Waterdeep_Session_11_2026-06-25_18-18-12.txt`
- `../raw/Dragon-Heist-Remix.pdf`

Prefer concise YAML frontmatter on maintained pages:

```yaml
---
type: session
status: draft
campaign_date:
real_date: 2026-06-25
source_paths:
  - ../raw/text_transcripts/Waterdeep_Session_11_2026-06-25_18-18-12.txt
updated: 2026-07-09
tags:
  - waterdeep
---
```

Useful `type` values include `dashboard`, `session`, `pc`, `npc`, `faction`, `place`, `object`, `timeline`, `prep`, `reference`, `meta`, and `thread`.

Each substantive page should usually include:

- A short summary at the top.
- Current status, if the subject can change.
- Relevant links to people, factions, places, objects, and sessions.
- A `Sources` section with raw paths and/or session pages.
- An `Uncertainties` section when facts are ambiguous or inferred.

## Session Ingest Workflow

For a session transcript ingest:

1. Read `INDEX.md` and recent `CHANGELOG.md` entries.
2. Identify the transcript source. Prefer `../raw/text_transcripts/` for reading and use `../raw/json_transcripts/` only when timestamps, segment boundaries, or speaker metadata matter.
3. Create or update a `Sessions/Session NN - YYYY-MM-DD.md` page.
4. Capture:
   - real date and session number;
   - where the session started and ended;
   - major scenes;
   - decisions and promises made by PCs;
   - NPCs introduced or changed;
   - clues gained;
   - combat and consequences;
   - money, debts, property, items, and legal obligations;
   - unresolved questions;
   - likely next-session hooks.
5. Update all affected pages, not just the session page.
6. Update `Dashboard/Player-Facing Synopsis.md` with a spoiler-safe, Discord-postable recap in the style of `../raw/notes/discord-synopsis-channel.md`.
7. Update `INDEX.md` processing status.
8. Append a changelog entry.

Do not overfit speaker labels. `SPEAKER_04` may be the DM in one transcript, but always infer roles from context and note uncertainty if identity matters.

## Player-Facing Synopsis Workflow

After each session ingest, update `Dashboard/Player-Facing Synopsis.md`.

- Treat `../raw/notes/discord-synopsis-channel.md` as the style guide: narrative prose, lightly wry, specific to what happened at the table, and suitable for posting in Discord.
- Keep it player-facing. Include only events the party experienced or could reasonably remember.
- Do not include DM-only secrets, hidden motives, future prep, private unrevealed handout content, or behind-the-screen reasoning.
- Prefer plain names over Obsidian wikilinks in the synopsis body so it can be copied directly into Discord.
- End each session entry with the current cliffhanger, next lead, or practical reminder for the players.

## Adventure Reference Workflow

For Remix or original adventure ingest:

1. Treat `../raw/Dragon-Heist-Remix.pdf` as the preferred adventure design source.
2. Treat `../raw/waterdeep_dragon_heist/` as original canon, NPC/location/stat reference, and fallback setting source.
3. Extract runnable structures, not long prose:
   - villain goals;
   - faction response teams;
   - clues and revelation lists;
   - outposts and lairs;
   - timelines;
   - decision points;
   - scene dependencies;
   - items and handouts.
4. File these under `Reference/`, `Factions/`, `Places/`, `Objects/`, and `Timeline/` as appropriate.
5. Mark spoilers or future-facing prep clearly so accidental player-facing export is less likely.

## Weekly Prep Workflow

When asked to prep a session:

1. Read `Dashboard/Current Campaign State.md`, the most recent session page, relevant open threads, faction pages, and any prep page for the coming date.
2. Produce or update `Prep/Session Prep - YYYY-MM-DD.md`.
3. Include:
   - recap bullets;
   - current party state;
   - likely player intentions;
   - active NPC and faction agendas;
   - scenes likely to happen;
   - secrets and clues to reveal;
   - consequences waiting in the background;
   - maps/handouts/assets needed;
   - rules or stat blocks to review;
   - flexible backup scenes.
4. Keep prep runnable at the table. Prefer checklists, scene cards, and clue lists over essay prose.

## Lint Workflow

When asked to lint or health-check the wiki:

- Find orphan pages that should be linked.
- Find important entities mentioned without pages.
- Find stale `current status` claims contradicted by newer sessions.
- Find unresolved threads with no owner or next step.
- Check whether `INDEX.md` matches the actual vault.
- Check whether `CHANGELOG.md` has an entry for recent substantial edits.
- Produce a short report in `Meta/` if the lint pass is substantial.

## Naming Guidance

- Use title case for page names: `Trollskull Manor`, `Stone of Golorr`.
- For session pages, use `Session NN - YYYY-MM-DD`.
- For prep pages, use `Session Prep - YYYY-MM-DD`.
- For ambiguous names from transcripts, create the most likely canonical page name and record variants near the top.
- Prefer one page per durable entity. Do not split pages until the notes become hard to use.

## Current Known Inputs

- Session 1 is not recorded in the available transcripts.
- Recorded Waterdeep transcripts currently include sessions 2 through 11.
- The latest sampled campaign state from session 11 includes Trollskull Manor ownership, a prospective Cassalanter loan, a Kelemvor-related seance, and contact with Lif, the manor's ghost. Treat this as a clue to be verified during proper session ingest, not as a fully processed state.
