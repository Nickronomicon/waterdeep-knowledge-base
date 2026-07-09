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
