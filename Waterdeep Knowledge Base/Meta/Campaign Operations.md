---
type: meta
status: active
updated: 2026-07-09
source_paths:
  - ../raw/roster.md
  - ../raw/stats.md
  - ../raw/notes/technical-notes.md
tags:
  - waterdeep
  - operations
  - transcript-ingest
---

# Campaign Operations

This page captures the operating assumptions needed before session transcript ingest. It is DM-facing and should be checked whenever transcript-derived facts seem ambiguous.

## Current Logistics

- Campaign runs remotely over Discord, usually Thursday evenings around 5 or 6 PM Pacific.
- Sessions are intended to run about four hours, with occasional skipped weeks or overruns.
- Foundry is the live tabletop and the canonical sheet source between level exports.
- D&D Beyond sheets are useful links, but exported sheets in `../raw/notes/character-sheets/` may lag behind Foundry changes.
- OBS recordings are converted to audio and transcribed with Whisper plus pyannote diarization.

## Transcript Ingest Guardrails

- Speaker labels are unreliable across sessions and within a session.
- Attribute actions by context, not by `SPEAKER_XX` labels alone.
- Treat off-topic table talk as normal noise unless it records a real ruling, retcon, schedule, or table agreement.
- DM prep notes are aspirational. They are useful for intent, unused material, and hidden structure, but transcript evidence decides what actually happened at the table.
- When prep and transcript conflict, keep the transcript as table truth and preserve prep-only material as unused, delayed, or uncertain.
- If a reveal status is unclear, mark it in the relevant page rather than assuming the whole party knows it.

## Source Authority For Session Ingest

1. Direct user direction.
2. Session transcripts and session summaries.
3. DM prep and campaign notes under `../raw/notes/`.
4. `../raw/Dragon-Heist-Remix.pdf` for campaign structure.
5. `../raw/waterdeep_dragon_heist/` for original adventure support.

## Current Party Context

- Party level: 3.
- Party name: TBD.
- Tavern name: Trollskull Manor for now.
- Current in-world date from `../raw/stats.md`: 5 Ches, 1492 DR.
- Next listed session: Session 12 on 2026-07-09.

## Homebrew And Character Sources

- Broethuul uses a homebrew Blood Hunter specialization, Order of the Faeslayer, based on the Critical Role Blood Hunter.
- Foundry deltas have not yet been ingested into PC pages.
- Level-3 exported sheets should be treated as a stable baseline, not necessarily the live sheet state.

## Discord And Document Channels

- Each PC has a public character channel and a private character channel shared with the GM.
- The campaign has shared campaign, handouts, synopsis, and voice channels.
- Google Docs may contain longer private handouts; links usually appear in handouts or private character channels.

## Follow-Up For Transcript Pass

- During each session ingest, record any explicit table ruling or retcon in the session page and relevant entity pages.
- Reconcile Foundry-only character changes when the user exports or provides updated sheet data.
- Use [[Meta/DM Prep Source Map]] to pair each transcript with same-session prep sources.
