## WSJ

1. [Iran Gambles on Escalation With Surprise Attack on U.S. Forces](https://www.wsj.com/world/middle-east/iran-gambles-on-escalation-with-surprise-attack-on-u-s-forces-72cfd422)
2. [Oil Surges as Fresh Middle East Strikes Threaten Fragile Diplomacy](https://www.wsj.com/economy/oil-surges-as-fresh-middle-east-strikes-threaten-fragile-diplomacy-7fd2d4e8)
3. [Anthony Fauci Repeatedly Invokes Fifth Amendment at Covid-19 Hearing](https://www.wsj.com/politics/policy/anthony-fauci-invokes-fifth-amendment-in-covid-19-hearing-5eeb2f3d)
4. [Trump Administration to End Medicare Drug Plan Subsidy](https://www.wsj.com/health/healthcare/trump-administration-to-end-medicare-drug-plan-subsidy-76d255d1)
5. [Russia Charges Telegram Founder Durov With Aiding Terrorism](https://www.wsj.com/world/russia-charges-telegram-founder-durov-with-aiding-terrorism-06285c1f)

## NYT

1. [Iran War Live Updates: U.S. and Saudi Airstrikes Drag More Countries Into Fighting](https://www.nytimes.com/live/2026/07/28/world/iran-us-strikes-iraq-trump)
2. [Global Oil Prices Jump as Attacks Resume in the Middle East](https://www.nytimes.com/2026/07/29/business/oil-prices-iran-war-us-attacks.html)
3. [Fauci Invokes the Fifth Amendment, Refusing to Answer Senate Committee Questions](https://www.nytimes.com/2026/07/29/us/politics/fauci-testifies-rand-paul.html)
4. [Big Tech Turmoil Clouds the A.I. Earnings Picture](https://www.nytimes.com/2026/07/29/business/dealbook/big-tech-ai-earnings.html)
5. [Trump Will End Subsidies for Medicare Drug Premiums](https://www.nytimes.com/2026/07/28/business/medicare-drug-subsidies-part-d.html)

## NBC

1. [Iran launches attacks on U.S. targets, shattering dayslong lull in fighting](https://www.nbcnews.com/world/middle-east/us-thwarts-iranian-missile-attack-launches-strikes-saudi-arabia-rcna589773)
2. [Dr. Fauci invokes his Fifth Amendment right not to testify at Senate hearing](https://www.nbcnews.com/now/video/dr-fauci-invokes-his-fifth-amendment-right-not-to-testify-at-senate-hearing-267446853703)
3. [At least 13 killed in Japan earthquake as rescuers search for survivors in a 'race against time'](https://www.nbcnews.com/world/asia/least-13-killed-japan-earthquake-others-trapped-rubble-rcna589771)
4. [Nasdaq-100 slides into correction as global chip and memory stocks sell off](https://www.nbcnews.com/business/markets/nasdaq-100-correction-tech-stocks-rcna589630)
5. [Have cyclospora outbreaks peaked yet? CDC reports over 18,000 possible cases nationwide](https://www.nbcnews.com/health/health-news/cyclospora-outbreak-michigan-new-cases-down-parasite-lettuce-cdc-rcna589699)

## AP

1. [US thwarts an Iranian missile attack and launches strikes with Saudi Arabia against militias in Iraq](https://apnews.com/article/iran-war-us-trump-saudi-houthis-iraq-8d2ae29300a8dc5495a4ce56c5312bf1)
2. [Fauci invokes Fifth Amendment and declines to testify in Republican-led COVID-19 Senate hearing](https://apnews.com/article/fauci-covid19-pandemic-senate-rand-paul-a774a79e46824ebec9e8e270b9cb9825)
3. [Rescuers search for survivors after a 7.1 quake kills 18 in southwestern Japan](https://apnews.com/article/japan-earthquake-kumamoto-kagoshima-mall-factory-6b0fe69d44fa5c82ac4765a8ad82ebf6)
4. [US bans foreign-made humanoid robots, targeting China over national security](https://apnews.com/article/china-us-humanoid-robots-ban-tech-c9f5e3c94d91d00eff3b61b141fab366)
5. [Russia accuses Telegram CEO Pavel Durov of aiding terrorism in its latest digital crackdown](https://apnews.com/article/russia-telegram-pavel-durov-ukraine-a6efe4692f3415c2046f0893d114174b)

## Note

Selection window: 2026-07-28T13:36 UTC through 2026-07-29T13:36 UTC (09:36 ET to 09:36 ET). All eight WSJ Dow Jones RSS feeds, all ten NYT section RSS feeds, and all eight NBC section RSS feeds listed in the source instructions returned HTTP 200 and were used to build each outlet's candidate pool; items were filtered on `pubDate`/`published`, not on feed-retrieval time. One WSJ Medicare-subsidy link carried a `?mod=pls_whats_news_us_business_f` tracking parameter in its own RSS feed, which was stripped for a clean canonical URL.

AP does not publish a public RSS feed. Its candidate pool (100 items) was built from Google News's `site:apnews.com when:1d` search feed. Google News wraps AP links in obfuscated `news.google.com/rss/articles/...` redirects that this environment could not decode directly (the redirect-resolution endpoint was not reachable, and `apnews.com` is not crawlable by the web-search tool available in this session). Instead, each candidate headline was cross-verified by fetching `apnews.com` directly with a browser user agent (homepage, hub pages, and AP's own site search) and matching titles against each article's JSON-LD `headline`/`datePublished` metadata, which was treated as the authoritative original-publication timestamp. This surfaced a material discrepancy: Google News's feed listed "Johnson & Johnson proposes $5.5 billion talc settlement" with a `pubDate` of 2026-07-28T16:54 (inside today's window), but the article's own `datePublished` metadata was 2026-07-28T12:12:40 UTC — about 84 minutes before the window opened (and it was in fact already used in yesterday's, 2026-07-28, digest). It was excluded on that basis and replaced with the Telegram/Durov story, which verified within-window (06:40 UTC). AP's continuously-updated "stock market wrap" story is republished under dozens of near-duplicate URLs per day as prices move, so no single snapshot of it could be pinned to a clean canonical article within the window; it was left out rather than guessed at.

The dominant story of the cycle was Iran's missile attack on U.S. forces and the resulting U.S.–Saudi strikes on Iraq-based militias, a sharp escalation after a days-long lull, which all four outlets led with; each outlet's second Iran-adjacent pick (oil-price/market reaction at WSJ and NYT) captures a distinct economic consequence rather than restating the military event. A second major thread was Dr. Anthony Fauci invoking his Fifth Amendment right rather than answer Senate Republicans' questions on Covid-19-pandemic decisions, selected independently by all four outlets. A third was the deadly 7.1-magnitude earthquake in Kumamoto, Japan (death toll risen to 13–18, with a mall collapse and ongoing rescue operations), selected by NBC and AP. A fourth was renewed strain in the U.S.–China tech relationship: Washington's new ban on foreign-made (China-linked) humanoid robots over national-security concerns (AP) and a global sell-off in AI/chip stocks clouding Big Tech earnings (NYT, NBC). Rounding out selections were the Trump administration's move to end a Medicare Part D drug-plan premium subsidy affecting seniors' 2027 costs (WSJ, NYT), Russia's criminal charges against Telegram founder Pavel Durov for allegedly aiding terrorism (WSJ, AP), and the CDC's report of more than 18,000 likely cyclospora cases tied to contaminated produce (NBC).

Strongest excluded candidates: for WSJ, "BMW Aims to Cut 8,000 Jobs as China Woes Mount" — a genuine labor/industry story, narrowly passed over for stories with broader international-conflict and policy consequence. For NYT, "After Large Earthquake, Japan 'Races Against Time' to Reach People Trapped" — a major disaster story, judged to have a shorter half-life of durable consequence than the policy and markets stories selected (it is represented instead at NBC and AP). For NBC, "Trump Asks Supreme Court to Overturn $83.3 Million Award in E. Jean Carroll Defamation Case" — a real legal-precedent story, narrowly excluded for space. For AP, "Johnson & Johnson Proposes $5.5 Billion Talc Settlement to End Marathon Legal Fight" — excluded specifically because its verified original publish time fell just outside the 24-hour window, not for lack of significance (see above).

No outlet's five selections contained three or more items concerning the same underlying development. Each outlet capped its Iran-war-related coverage at two items (the attack itself and its distinct oil-market/diplomatic fallout), and the Japan earthquake, Fauci hearing, and Telegram/Durov charges each appear at no more than two outlets, reflecting independent judgment across the candidate pool rather than any single outlet's internal redundancy.
