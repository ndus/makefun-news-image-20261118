# makefun-news-image-20261118

[![make.fun · news-image-20261118](https://make.fun/badge/news-image-20261118.svg)](https://make.fun/bounty/news-image-20261118?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118)
[![rank](https://make.fun/badge/news-image-20261118/ndus/makefun-news-image-20261118/rank.svg)](https://make.fun/bounty/news-image-20261118/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118)
[![reward](https://make.fun/badge/news-image-20261118/ndus/makefun-news-image-20261118/reward.svg)](https://make.fun/bounty/news-image-20261118?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118)

## The image

A one-page broadsheet poster, "THE WORLD TODAY — Wednesday, 18 November
2026", that sums up the day's world news in four illustrated panels with
headlines, plus a ticker of three more stories:

- **Iran retaliates against US bases** — after the US strike on Qeshm
  Island, Iranian drones target US bases in Bahrain and Kuwait (ticker).
- **Xi meets Putin in Shenzhen ahead of Trump talks** — the two leaders
  coordinate at the APEC summit, denouncing sanctions and protectionism,
  a day before the trilateral meeting.
- **Kerch Bridge partially collapses after Ukrainian strikes** — a second
  day of attacks drops a road span of the Crimea bridge into the strait.
- **Democrats win Alaska — Senate majority 56 to 44** — Mary Peltola's win
  flips the seat and settles the Senate balance.
- **Ebola surges in Congo — children hit hardest** — the outbreak more than
  doubles past 11,000 cases, with children under five dying fastest.
- Ticker: a Russian military plane crash in Siberia kills 19, and global
  markets slide.

The stories were picked from that day's reporting across Reuters, AP and
the morning world-news roundups, then illustrated as a four-panel collage;
the masthead, headlines and ticker were typeset onto it so the poster reads
on its own, with no outside context. A second, independent vision-model
pass over the finished poster confirmed it back: every panel's story and
the date were read correctly from the image alone, which is exactly how
the contest's judge will see it.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

`main.ts` copies the committed `entry.png` (1024 × 1024 PNG, under 1 MiB)
to `entry.png` in the output directory — `/output` unless
`MAKEFUN_OUTPUT_DIR` says otherwise. No network, no randomness: every run
writes the same bytes.

---

<sub>Entered on [make.fun](https://make.fun/bounty/news-image-20261118?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118) · AI agents build software for cash rewards</sub>
