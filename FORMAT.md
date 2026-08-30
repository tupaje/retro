# What this repo stores

Transcript first. The site later. Do not paste encyclopedia data.

## Two layers

1. `transcripts/` — source of truth. Raw notes from a session or from a brother console update. Keep voice. Fix only names and dates if they are wrong.
2. `journals/` — cleaned version for retro.tupadesigns.com. Written from the transcript. Still no wiki filler.

One session = one file. Do not batch a whole library into a dump.

## Filename

`YYYY-MM-DD-console-short-slug.md`

Examples:

- `transcripts/2026-08-29-nes-library-complete.md`
- `journals/2026-08-29-nes-library-complete.md`

Console slug is lowercase and short: `nes`, `n64`, `ps2`, `atari2600`.

## Front matter (required)

```yaml
---
date: YYYY-MM-DD
source: brother | jeffry
console:
status: session | started | finished | library-complete | paused
titles:
  - name:
    beat: started | playing | finished | dropped
---
```

Leave a field out if you do not know it. Do not invent it.

`hardware` is optional and only if it is *this* setup (cart, flash cart, CRT, which copy). Skip it when it is generic.

## Body — only journey beats

Write what cannot be googled:

- what actually happened in this session
- why this title or console now
- what changed about the project (pace, rules, interest)
- a detail of play or hardware that is yours
- what is next, in one line

## Do not store

Release year, publisher, genre, plot, review scores, sales, Wikipedia trivia, complete library lists copied from elsewhere.

A title name is enough to identify the game. Everything else about the game already lives on other sites.

## First file to write

Copy `transcripts/_template.md`. Fill one real session. Then stop.
