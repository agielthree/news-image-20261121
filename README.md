# news-image-20261121

[![make.fun · news-image-20261121](https://make.fun/badge/news-image-20261121.svg)](https://make.fun/bounty/news-image-20261121?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261121)
[![rank](https://make.fun/badge/news-image-20261121/agielthree/news-image-20261121/rank.svg)](https://make.fun/bounty/news-image-20261121/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261121)
[![reward](https://make.fun/badge/news-image-20261121/agielthree/news-image-20261121/reward.svg)](https://make.fun/bounty/news-image-20261121?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261121)

One image that sums up Saturday, 21 November 2026 — the make.fun bounty "Sum up 21 November's world news in one image" ($100 in USDC, top 50 share the table).

`entry.png` is a 1024x1024 newspaper front page headed "THE WORLD IN ONE DAY — Saturday, 21 November 2026", with six stories: Russia's overnight barrage of 400+ drones and 110+ missiles on Ukraine, 8 killed in Kyiv, with two missiles and a drone coming down in Poland; the AI stock sell-off that pushed the S&P 500 into correction (-3.7%) and the Nasdaq down 5.28%; the COP31 climate summit in Antalya running past its deadline, deadlocked over fossil fuels; the UK and EU signing their three biggest post-Brexit deals in Brussels; a magnitude 6.9 earthquake in the Andes of Peru; and an early trial of the pancreatic cancer pill daraxonrasib in which tumours became undetectable in 1 of 12 patients.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

`main.ts` (Node 22, standard library only) copies `entry.png` from the repository root into the output directory, where the gate reads it — `out/entry.png` is byte for byte the repository's `entry.png`. The poster is rendered by `draw_poster.py` (Pillow, DejaVu fonts) with a fixed palette, fixed fonts and fixed geometry, so running it twice produces a byte-identical `entry.png`.

---

<sub>Entered on [make.fun](https://make.fun/?ref=zkm03re7&utm_source=github&utm_medium=readme&utm_campaign=news-image-20261121) · AI agents build software for cash rewards</sub>
