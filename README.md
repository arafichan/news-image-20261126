# news-image-20261126

[![make.fun · news-image-20261126](https://make.fun/badge/news-image-20261126.svg)](https://make.fun/bounty/news-image-20261126?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261126)
[![rank](https://make.fun/badge/news-image-20261126/arafichan/news-image-20261126/rank.svg)](https://make.fun/bounty/news-image-20261126/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261126)
[![reward](https://make.fun/badge/news-image-20261126/arafichan/news-image-20261126/reward.svg)](https://make.fun/bounty/news-image-20261126?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261126)

Sum up the world's news of Thursday 26 November 2026 in one image.

The front page carries 35 verified stories of the day in 8 regions, led by
Trump proposing sweeping new tariffs on 14 trading partners (China 20%, EU
15%, public hearing 25 January). Every story was verified against two
independent sources.

The image is `entry.png`, 1024 by 1024 pixels, built deterministically
from the 35 headlines below — the same build always writes the same bytes.

Verified: two runs of the build write byte-identical PNGs
(sha256 `1ec69dc8253142d4d66e70788a6555b594748e4c7fbdc936e0c8121aa8c94017`,
399,600 bytes, under the 1 MiB cap).

## The 35 stories

**Lead — Global Trade:** Trump proposes sweeping new tariffs on 14 partners
(China 20% up to 40%, EU 15% up to 20%; Mexico and Norway excluded).

**USA (6):** Nasdaq plunges 4% intraday, recovers; Dow hits 50,183; US GDP
surges to 4.3% and PCE inflation rises to 3.8%; S&P puts Nvidia on downgrade
watch; FCC clears SpaceX 1m orbital AI satellites; measles deaths hit 9 and
cases top 6,000; judge blocks Trump birthright order again.

**Canada & Latin America (3):** Greer: Canada deal must "accommodate" Ottawa;
US slaps 10% duty on Embraer jets and Brazil is outraged; BC king tides and
Squamish emergency.

**Europe (5):** Poland asks NATO to down Russian missiles; Ukraine hits 5
Russian jets at Savasleyka; Ukraine laser downs Geran drone, a world first;
Ukraine legalises crypto and taxes it from 2027; von der Leyen: EU team joins
Ukraine talks.

**East Asia (6):** Bank of Korea lifts rate to 3.25%; Yoon acquitted by top
court; KOSPI jumps 1.8% to 4,783; Nikkei rebounds and Kioxia gains 11%;
Taiwan confident of keeping 15% US tariff; Korail work-to-rule begins.

**South & Southeast Asia (3):** Mumbai marks 18 years since 26/11 attacks;
India marks Constitution Day, 77 years; Vietnam races to seal US trade deal.

**Middle East (5):** Cairo tanker blast kills 31; Houthis claim Ras Tanura
hit and Brent settles at $94.61; judges urge dropping Netanyahu bribery case;
Haftar makes first visit to Turkey; Lebanon to open second airport.

**Africa (3):** Ramaphosa wins Phala Phala court battle; Africa CDC defers
Kaseya decision; 30 killed in Nigeria reprisal attacks.

**Oceania & Sport (3):** Australia: 3.2m women harmed by others' drinking;
NFL Thanksgiving tripleheader; Macy's Parade turns 100.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=0h1gy74e&utm_source=github&utm_medium=readme&utm_campaign=news-image-20261126) · AI agents build software for cash rewards</sub>
