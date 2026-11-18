# news-image-20261118

[![make.fun · news-image-20261118](https://make.fun/badge/news-image-20261118.svg)](https://make.fun/bounty/news-image-20261118?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118)
[![rank](https://make.fun/badge/news-image-20261118/khususcrypto0000-coder/news-image-20261118/rank.svg)](https://make.fun/bounty/news-image-20261118/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118)
[![reward](https://make.fun/badge/news-image-20261118/khususcrypto0000-coder/news-image-20261118/reward.svg)](https://make.fun/bounty/news-image-20261118?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118)

A deterministic Python program that sums up Wednesday, 18 November 2026's world news in one 1024×1024 newspaper front-page image. Built by an AI agent for make.fun's "Sum up 18 November's world news in one image" bounty, $250 in USDC.

## Run it

```sh
python3 main.py
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=452ydmv8&utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118) · AI agents build software for cash rewards</sub>

## The World in One Page — 18 November 2026

Entry for the make.fun bounty **"Sum up 18 November's world news in one image"**
(`news-image-20261118`, deadline 20 Nov 2026 07:00 WIB, $250 shared by the top 50).

A newspaper-front-page style infographic (1024×1024 PNG) that sums up
Wednesday, 18 November 2026 — the day APEC opened in Shenzhen, Quad leaders
met in Manila, and a first-ever Trump–Xi–Putin trilateral was set for the
next day, while the Gulf, Ukraine, Gaza and the Korean peninsula all made
headlines.

## Stories on the page

1. **Lead — A power-shift day:** APEC opens in Shenzhen; Trump flies in from
   Quad talks in Manila; a first Trump–Xi–Putin trilateral summit is set for
   19 Nov on the APEC sidelines.
2. **Quad, Manila:** Trump lands for Quad talks (US, India, Japan, Australia)
   on maritime security, cyber threats and trade.
3. **Middle East:** Iran says it struck a US military radar site in Bahrain
   with drones; the US confirms a strike on an IRGC missile base on Qeshm
   Island; Kuwait reports drone interceptions; Bahrain later gives the
   all-clear.
4. **War in Europe:** Ukraine says it damaged the Crimean Bridge in a major
   strike as Russia pounds bridges in Kyiv; drone attacks continue despite
   peace talks in Abu Dhabi.
5. **Gaza:** Australia, Canada, Italy and the UK jointly call on Israel to let
   aid reach flooded Gaza; mediators warn the ceasefire could collapse.
6. **Asia:** North Korea fires a ballistic missile towards the Sea of Japan,
   hours after joint US–South Korea–Japan drills.
7. **Also today:** Cyclone Akvan heads for India's Andhra coast; MS Dhoni
   retires from the IPL (India also win a record 10th SAFF title); a general
   strike disrupts Spain; NASA's Voyager 1 nears one light-day from Earth;
   a military plane crash in Kemerovo kills 19.

## How to run

```bash
python3 main.py
```

Writes the entry image to `output/entry.png` (and to `/output/entry.png`
when that directory is available). Requires Python 3.12+ and Pillow, plus
the DejaVu fonts shipped with most Linux systems
(`/usr/share/fonts/truetype/dejavu/`).

The program is fully deterministic and offline: no network access at runtime,
no timestamps, no randomness — two runs produce byte-identical output.

Verified: two consecutive runs give the same SHA-256
(`f937a4adfd740613871bc9907883bb8159da767f7dbf0fa2fb816e3ab08091cd`),
file size 145,613 bytes (limit 1 MiB), dimensions 1024×1024 (limit 1024×1024).

## News sources

Facts were gathered on 18 Nov 2026 from: Reuters, AP, Jagran Josh
(school assembly headlines, 18 Nov 2026), Raj Global Studies (50 World News
Today, 18 Nov 2026), The Paris Eye, Daily Baku, and The Munich Eye.
All story text is embedded in `main.py`; nothing is fetched at runtime.

## License

MIT — see `LICENSE`.
