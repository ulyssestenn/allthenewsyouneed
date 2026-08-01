## WSJ

1. [Trump Orders Fresh Attack Against Iran as War Enters Sixth Month](https://www.wsj.com/world/middle-east/trump-sours-on-diplomacy-vows-to-hit-iran-hard-2c7af868)
2. [Settlers Torch Mosques and Villagers Guard Homes: West Bank Violence Is Surging](https://www.wsj.com/world/middle-east/settlers-torch-mosques-and-villagers-guard-homes-west-bank-violence-is-surging-29a33a51)
3. [Warsh Floats Fewer Fed Meetings](https://www.wsj.com/economy/central-banking/warsh-floats-fewer-fed-meetings-debf5a23)
4. [OpenAI Surpasses One Billion Users After Cutting Prices](https://www.wsj.com/tech/ai/openai-surpasses-one-billion-users-after-cutting-prices-8a9943e4)
5. [U.S., Allies Put Frictions Aside, Showing China Combined Naval Might](https://www.wsj.com/world/asia/u-s-allies-put-frictions-aside-showing-china-combined-naval-might-3f92b8f9)

## NYT

1. [Russian Missiles Kill 9 in Kyiv After Trump Backs Off Air-Defense Pledge](https://www.nytimes.com/2026/08/01/world/europe/ukraine-russia-attack-missiles-patriot.html)
2. [Evidence Indicates U.S. Dropped Bomb on Residential Area in Iran, Killing 3 Civilians](https://www.nytimes.com/2026/07/31/world/middleeast/us-iran-bomb-mk84-qeshm-island.html)
3. [Kuwait Says It Downed Iranian Drones as Mideast Braces for Possible Escalation](https://www.nytimes.com/2026/08/01/world/middleeast/iran-kuwait-drone-strikes-trump-escalation.html)
4. [Warsh Considers Reducing Frequency of Fed Policy Meetings](https://www.nytimes.com/2026/07/31/business/federal-reserve-warsh-meetings.html)
5. [Ebola Outbreak Is Now the Second-Largest Ever, and in Record Time](https://www.nytimes.com/2026/07/30/world/africa/ebola-deaths-record.html)

## NBC

1. [Hackers targeted municipal water systems in 7 states this week, FBI says](https://www.nbcnews.com/tech/security/hackers-targeted-municipal-water-systems-7-states-week-fbi-says-rcna590210)
2. [Judge denies request by Elon Musk's xAI to pause Minnesota nudification ban](https://www.nbcnews.com/tech/elon-musk/judge-denies-request-elon-musks-xai-block-mn-nudification-ban-rcna589993)
3. [Trump appeals ruling that found his $10B IRS suit aimed to 'manipulate' legal proceedings](https://www.nbcnews.com/politics/donald-trump/appeals-ruling-found-10-billion-irs-suit-aimed-manipulate-legal-rcna590307)
4. [Trump defends 'anti-weaponization' fund, further complicating Blanche nomination](https://www.nbcnews.com/politics/donald-trump/trump-defends-anti-weaponization-fund-complicating-blanche-nomination-rcna590254)
5. [FIFA president nixes idea to sell stakes in World Cup to private equity investors](https://www.nbcnews.com/sports/soccer/fifa-private-equity-plan-gianni-infantino-world-cup-rcna590317)

## AP

1. [Spain installs 500-meter barrier at Ceuta after 67 die in border surge](https://apnews.com/article/migration-spain-ceuta-morocco-d76c6dc9d2da828907a1c04e1d482bbe)
2. [Russian missile attack on Ukrainian capital kills at least 9](https://apnews.com/article/russia-ukraine-war-zelenskyy-missile-attack-ballistics-eb62397d10bca2d6db4269a3bcfc9dc6)
3. [Infantino is not proceeding with divisive plan to sell World Cup profits to private equity](https://apnews.com/article/world-cup-infantino-fifa-investors-8aba1b529f220c27d02d326e8fd9e377)
4. [Trump administration plans major overhaul of civil rights-era banking rules](https://apnews.com/article/community-reinvestment-act-banks-ncrc-occ-fdic-5ddb1b4dfcd08eaa0243b0b80cceb0ff)
5. [Trump stands to profit by selling fast access to his social media posts](https://apnews.com/article/trump-truth-social-media-insider-trading-posts-feeds-traders-25c2c5be926f2650d0610c84100cffb8)

## Note

Selection window: 2026-07-31T13:36 UTC through 2026-08-01T13:36 UTC (09:36 ET to 09:36 ET). All eight WSJ Dow Jones RSS feeds, all ten NYT section RSS feeds, and all eight NBC section RSS feeds listed in the source instructions returned HTTP 200 and were used to build each outlet's candidate pool; items were filtered on `pubDate`, not on feed-retrieval time. wsj.com and nytimes.com both returned HTTP 401/403 to direct fetch attempts from this environment, so WSJ and NYT selections rely on their own RSS `title`/`pubDate` fields as the verification source. The WSJ Fed item's own feed `title` was a raw conversational sentence rather than a formatted headline; the cleaner published headline ("Warsh Floats Fewer Fed Meetings") was cross-verified via an MSN wire-syndication mirror of the same WSJ story.

AP does not publish a public RSS feed. Its 100-item candidate pool was built from Google News's `site:apnews.com when:1d` search feed, whose links are obfuscated `news.google.com/rss/articles/...` redirects that do not resolve via HTTP (Google serves them client-side). Each AP candidate was instead cross-verified by matching the Google News item's headline text against AP's own site search (`apnews.com/search`) and topic hub pages, then confirming the resulting `apnews.com/article/...` URL's live headline and JSON-LD `datePublished` metadata directly. This process caught two stale items that Google News' feed had assigned fresh-looking pubDates to: New York's Kalshi lawsuit (`datePublished` 2026-07-31T12:29:52Z, before the window, and identical to the article already used in yesterday's, 2026-07-31, digest) and a "major oil companies book massive profits" story (`datePublished` 2026-07-31T04:01:06Z, also before the window) — both were dropped from the AP pool despite appearing "IN" on Google News' own pubDate field. A similar check on WSJ's own feed caught its Kalshi and Ceuta "regains control" items reusing URLs already published in yesterday's digest; both were excluded from today's WSJ pool for the same reason. All five confirmed-final AP URLs carry `datePublished` timestamps between 2026-07-31T17:54:55Z and 2026-08-01T11:06:22Z.

Principal selection rationale: with the exception of the Ceuta migrant-crisis aftermath (still resolving but now with a confirmed 67 dead and a permanent barrier under construction) and the FIFA/Infantino private-equity collapse, most of today's strongest candidates clustered around two active wars — Russia's escalating missile campaign against Kyiv after the U.S. stepped back from a Patriot-missile commitment, and the U.S.-Iran conflict entering its sixth month with confirmed U.S. civilian casualties and a Kuwait drone-downing raising regional-escalation risk — plus Fed Chairman Kevin Warsh's move to cut the frequency of FOMC meetings, an unusual institutional shift at the central bank picked up independently by both WSJ and NYT.

Strongest excluded candidates: for WSJ, "Three Fed policymakers said stubborn inflation drove their dissenting votes for higher interest rates" — a real and related monetary-policy story, but folded out as redundant with the selected Warsh meeting-frequency story about the same underlying Fed leadership dynamic. For NYT, "Trump Administration Plans to Upend Head Start by Deregulating It" — a genuine institutional policy change, but narrower in immediate consequence than the war, monetary-policy, and public-health stories selected. For NBC, "F-35 fighter jet crashes in San Diego, sparking fire at Miramar air base" — a notable safety incident, but without a confirmed cause or fatality that would give it lasting institutional weight, versus the confirmed critical-infrastructure, legal, and governance stories chosen. For AP, "Trump wanted interest rate cuts to be 'Rocket Fuel' for the economy. He is losing that fight so far" — a solid Fed-independence story, but narrower than the confirmed banking-regulation overhaul and the Truth Social conflict-of-interest story selected.

No outlet's five selections contained three or more items concerning the same underlying development. Notable cross-outlet overlaps, each reflecting independent selection of the same story by two different newsrooms: Russia's missile strike on Kyiv (NYT and AP), the Fed's reduced meeting cadence under Warsh (WSJ and NYT), and FIFA's abandonment of its World Cup private-equity plan (NBC and AP).
