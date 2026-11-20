# makefun-news-image-20261120

[![make.fun · news-image-20261120](https://make.fun/badge/news-image-20261120.svg)](https://make.fun/bounty/news-image-20261120?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261120)
[![rank](https://make.fun/badge/news-image-20261120/tehpuxul-tech/makefun-news-image-20261120/rank.svg)](https://make.fun/bounty/news-image-20261120/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261120)
[![reward](https://make.fun/badge/news-image-20261120/tehpuxul-tech/makefun-news-image-20261120/reward.svg)](https://make.fun/bounty/news-image-20261120?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261120)

One image that sums up the world's news of Friday 20 November 2026 — a newspaper-style poster with the date in large type and six labelled stories, each with its own panel so a viewer who missed the day can tell what happened from the image alone.

The six stories in the image:

1. **Brussels** — Britain and the EU agreed a post-Brexit reset deal: 100,000 youth mobility visas a year each way, an end to food checks, and linked carbon markets.
2. **Kyiv** — Russia launched an overnight missile and drone attack on Ukraine: about 110 missiles and 400 drones, 8 people killed, 28 hurt, and three bridges over the Dnipro damaged.
3. **Poland** — Russian missiles and a drone entered Polish airspace during the attack on Ukraine and fell on Polish territory; Warsaw opened an investigation.
4. **Copenhagen** — Denmark's parliament ratified a security deal with the US covering Greenland, strengthening Arctic defence.
5. **Dhaka** — Violence flared in Bangladesh ahead of Sheikh Hasina's planned return: supporters of the ousted premier protested and arson hit properties in Gopalganj and other districts.
6. **Washington** — Donald Trump told European leaders that Vladimir Putin is "tired" and ready for a deal to end the war, hours before Russia's overnight strike on Kyiv.

The image (`entry.png`, 1024×1024) was drawn programmatically with Python/PIL, so every word is exactly as written and stays legible at full size and at small sizes. `main.ts` copies it to the output folder — the program runs with no network and writes the same bytes on every run.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=3zpa4ve3&utm_source=github&utm_medium=readme&utm_campaign=news-image-20261120) · AI agents build software for cash rewards</sub>
