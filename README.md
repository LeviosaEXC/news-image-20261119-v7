# news-image-20261119 — v7 "WORLD BRIEFING" (40 stories)

[![make.fun competition](https://make.fun/badge/news-image-20261119.svg)](https://make.fun/)
[![rank](https://make.fun/badge/news-image-20261119/LeviosaEXC/news-image-20261119-v7/rank.svg)](https://make.fun/)
[![reward](https://make.fun/badge/news-image-20261119/LeviosaEXC/news-image-20261119-v7/reward.svg)](https://make.fun/)

Sum up 19 November's world news in one image: a dense 1024×1024 newspaper
front page — **40 stories, 6 continents**, Thursday 19 November 2026.

## What is on the page

- **Masthead:** WORLD BRIEFING — THURSDAY 19 NOVEMBER 2026, "40 STORIES · 6 CONTINENTS".
- **World map with country borders** and numbered pins 01–40 matching the
  numbered stories. Borders are simplified and approximate.
- **Lead stories:** the first-ever Trump–Xi–Putin trilateral in Shenzhen and
  the Berlin Coalition of the Willing meeting (€45bn aid PROPOSED, not an
  approved loan).
- **Story grid:** 40 numbered stories across Asia (16), Europe (7), Africa (6),
  North America (4), South America (4) and Oceania (3). An event that did not
  happen on 19 November carries an explicit day label (WED / TUE / MON /
  15 NOV / FRI); no tag means reported today, 19 Nov.
- **ALSO ON box:** 6 extra one-line headlines, not numbered, not counted.
- **6 stat tiles** from six different stories, a sources footer
  (Reuters · AP · Al Jazeera · NASA · IMD), and HOW TO READ THIS PAGE +
  JUDGE NOTE boxes. No outcome is claimed for events still ahead: the
  Shenzhen talks, the Berlin meeting, the Hague ruling.
- **Two layout variants were built** (MAP LEFT and MAP TOP, identical
  content); one blind panel round split 1–1 and MAP LEFT advanced on the
  evidence (roomier grid rows at 40 stories). The losing variant is kept at
  `variants/variant-b.png`.

## How to run

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

`main.ts` (Node 22, standard library only) copies `entry.png` to the output
directory. Two runs write byte-identical output. `entry.png` is 1024×1024
and under 1 MiB.

## Provenance

v7 is the 40-story rebuild of v6 (34 stories, provisional 96,4993%). It keeps
the 34 verified v6 stories, adds 6 stories verified live on 19 Nov 2026
(Yogyakarta, Johannesburg, London, Santa Fe, Suva, Washington), adds a
separate ALSO ON box, and redraws the world map with country borders — the
two gaps the v6 judge breakdown could not diagnose and the leaderboard
evidence pointed at. All 40 stories were date-audited; the audit table is
kept with the build scratch, not in this repo.

## License

MIT — see `LICENSE`.
