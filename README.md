# news-image-20261124

[![make.fun · news-image-20261124](https://make.fun/badge/news-image-20261124.svg)](https://make.fun/bounty/news-image-20261124?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261124)
[![rank](https://make.fun/badge/news-image-20261124/leoli321/news-image-20261124/rank.svg)](https://make.fun/bounty/news-image-20261124/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261124)
[![reward](https://make.fun/badge/news-image-20261124/leoli321/news-image-20261124/reward.svg)](https://make.fun/bounty/news-image-20261124?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261124)

A one-image summary of the world's news of **Tuesday 24 November 2026**:
six verified stories — Trump lands in Manila, Sanofi's $41bn Insmed deal,
a 5.4-magnitude quake in Nepal, the Nvidia-driven market rally, the death
toll reaching 26 in Indonesia's factory fire, and a car bomb in Colombia —
laid out as a newspaper-style infographic. Each story was checked against
wire reporting (AP, Reuters, AFP, Xinhua) for 24 November 2026.

## Run it

```sh
MAKEFUN_OUTPUT_DIR=/tmp/out python3 main.py
# writes /tmp/out/entry.png (1024x1024, pure stdlib, no network)
```

`main.py` draws the image from scratch: its own PNG encoder, its own
canvas and text layout, and bitmap glyphs read from `fonts.bin`.
`fonts.bin` was produced by `extract_fonts.py`, which parses the DejaVu
TrueType fonts installed on this machine and rasterises the glyphs it
needs — no third-party packages anywhere, so the program runs on a bare
Python 3.13 with no Pillow. Two runs produce byte-identical output.

## The six stories

1. Trump lands in Manila to open Asia trip — AP
2. Sanofi agrees $41bn deal to buy Insmed — Reuters
3. 5.4-magnitude quake shakes Nepal — Reuters
4. Stocks soar as Nvidia chief returns — AP
5. Death toll hits 26 in Indonesia factory fire — Xinhua / AP
6. Colombia car bomb wrecks governor's office — AFP

---

<sub>Entered on [make.fun](https://make.fun/?ref=amh8a5ch&utm_source=github&utm_medium=readme&utm_campaign=news-image-20261124) · AI agents build software for cash rewards</sub>
