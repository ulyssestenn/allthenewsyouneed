## WSJ

1. [Trump Pauses Iran Strikes as Officials Weigh Dwindling Air Defense Stocks](https://www.wsj.com/world/middle-east/trump-pauses-iran-strikes-as-officials-weigh-dwindling-air-defense-stocks-c7d7ebb0)
2. [Nvidia in Talks With OpenAI to Guarantee $250 Billion Financing for Data Center](https://www.wsj.com/tech/ai/nvidia-in-talks-with-openai-to-guarantee-250-billion-financing-for-data-center-3dd6eae3)
3. [United Approached Delta Last Year About Merging Airlines](https://www.wsj.com/business/airlines/united-approached-delta-last-year-about-merging-airlines-af83fc64)
4. [Suspect in Deadly Berlin Pride Attack Killed by Police](https://www.wsj.com/world/europe/van-rams-into-crowd-at-berlin-pride-parade-killing-one-2d54f62e)
5. [Porsche to Cut a Further 5,000 Jobs](https://www.wsj.com/business/autos/porsche-to-cut-a-further-5-000-jobs-5cef413f)

## NYT

1. [How the Iran-Backed Houthis Cornered Saudi Arabia Into a New Conflict](https://www.nytimes.com/2026/07/27/world/middleeast/houthis-saudi-arabia-iran-war.html)
2. [Merz Criticizes Terrorism Laws After Deadly Berlin Pride Attack](https://www.nytimes.com/2026/07/27/world/europe/berlin-pride-attack-suspect-isis.html)
3. [The Fed's New Chairman Faces His Biggest Test Yet](https://www.nytimes.com/2026/07/27/business/the-feds-new-chairman-faces-his-biggest-test-yet.html)
4. [How Meta Got Everything It Wanted in a Secret Louisiana Data Center Deal](https://www.nytimes.com/2026/07/27/technology/meta-data-center-louisiana.html)
5. [China's CXMT Stock Soars 470% in Start of Trading, Amid A.I. Race](https://www.nytimes.com/2026/07/27/business/cxmt-stock-price-ai.html)

## NBC

1. [Oil prices slide as U.S. and Iran pause strikes to give 'space' for diplomacy](https://www.nbcnews.com/world/iran/oil-prices-slide-us-iran-pause-strikes-trump-diplomacy-hormuz-red-sea-rcna589383)
2. [Shootout at Seattle food festival kills 3; police arrest suspect and search for another](https://www.nbcnews.com/news/us-news/multiple-people-injured-seattle-center-shooting-police-say-rcna589371)
3. [New Details Emerge on Suspect in Deadly Berlin Pride Attack](https://www.today.com/video/suspect-in-berlin-pride-attack-shot-and-killed-by-police-267306053828)
4. [Mike Waltz dismisses concerns over depleted U.S. weapons stockpile amid Iran war](https://www.nbcnews.com/politics/trump-administration/mike-waltz-dismisses-concerns-depleted-us-weapons-stockpile-iran-war-rcna589281)
5. [Video helps free man from death row](https://www.nbcnews.com/nightly-news/video/video-helps-free-man-from-death-row-267287621910)

## AP

1. [US and Iran pause attacks for a second straight day](https://apnews.com/article/iran-war-united-states-ceasefire-ad9fa27d5b1b5fd51e30d923ee738238)
2. [A fatal attack on Berlin's Pride festival leaves locals wondering how their city will recover](https://apnews.com/article/germany-lgbtq-attack-reactions-6ff1f3bfbbccb24bd55444a40c453e3e)
3. [Chinese chipmaker CXMT shares soar in blockbuster Shanghai IPO](https://apnews.com/article/cxmt-china-memory-chips-debut-shares-9cd8b79866cf4bd5ef7c1cb81215e796)
4. [Pentagon's Iran war death toll no longer lists 4 troops killed in July](https://apnews.com/article/iran-war-casualty-count-pentagon-us-troops-4c578fc74746052627b1c87845fdc0d5)
5. [US appeals court upholds halt to Trump's executive order to create voter list](https://apnews.com/article/trump-mail-voting-appeal-executive-order-8bfb1f787f84fc60f9b6b284794b18b5)

## Note

Selection window: 2026-07-26T13:38 UTC through 2026-07-27T13:38 UTC. All eight WSJ Dow Jones RSS feeds, all ten NYT section RSS feeds, and all eight NBC section RSS feeds listed in the source instructions returned HTTP 200 and were used to build each outlet's candidate pool; items were filtered on `pubDate`, not on feed-retrieval time. A parsing bug (namespaced `atom:link` elements silently overwriting the plain `<link>` value on NYT items) was caught and fixed before selection, so no NYT candidate was dropped for a false-empty URL. WSJ and NYT article pages return bot-protection placeholders (HTTP 401 / 403) to automated requests without a browser session, so their links could not be live-verified by fetching the article page directly; they are the exact `<link>` values published in each outlet's own RSS feed, with WSJ's tracking query parameters (e.g., `?mod=rss_Technology`, `?mod=pls_whats_news_us_business_f`) stripped for a clean canonical URL.

AP does not publish a public RSS feed. Its candidate pool was built from Google News's `site:apnews.com when:1d` search feed (HTTP 200, 100 items), which supplied headlines and timestamps but, as on prior days, whose `news.google.com/rss/articles/...` links resolve only through a client-side JavaScript redirect (confirmed via a headless-browser attempt, which failed on `net::ERR_CONNECTION_RESET` through the environment's network policy) rather than a fetchable canonical apnews.com URL; a large share of the Google News items were also untitled or topic-hub placeholders (e.g., "Ohio - AP News," "Artificial intelligence - AP News") rather than articles. Final AP URLs were instead located by fetching apnews.com's business, financial-markets, and China hub pages directly (all HTTP 200) and matching headlines, and every selected AP candidate was confirmed by fetching the live apnews.com article page and reading its `datePublished` structured-data field directly, rather than trusting the Google News feed timestamp.

The dominant story of the cycle remained the fragile pause in US-Iran hostilities, reported by all four outlets from different angles: WSJ and NBC both surfaced concern over depleted US air-defense/munitions stockpiles, NYT and AP covered the diplomatic mechanics of the pause and its knock-on effect on oil markets, and AP separately reported that the Pentagon's official casualty count for the war no longer lists four troops killed in recent fighting — a distinct accountability story. A second major thread was the aftermath of the van-ramming attack at Berlin's Pride festival (the suspect killed by police, and Chancellor Merz calling for tighter counterterrorism monitoring), covered by all four outlets. A third thread was a notable AI/chipmaking and data-center financing wave — Nvidia's reported talks to guarantee $250 billion in OpenAI data-center financing, Meta's Louisiana data-center deal, and Chinese memory-chip maker CXMT's 470% Shanghai trading debut — reflecting a durable inflection in AI infrastructure investment and the US-China chip race. Rounding out selections were a deadly shooting at a Seattle food festival, a reported United-Delta merger approach, Porsche's further 5,000 job cuts, a federal appeals court's ruling against a Trump voter-list executive order, the Federal Reserve chairman's looming test, and a death-row exoneration aided by video evidence.

Strongest excluded candidates: for WSJ, "Big Companies Are Starting to Hire Again, Defying Predictions of AI Wipeout" — a genuine macro-labor-market trend piece, but judged narrower than the geopolitical, financing, and industry-consolidation stories selected, and would have crowded the list with AI/labor themes already covered by the Nvidia item. For NYT, "The A.I. Debate That's Driving a Wedge Through Big Tech" — a strong industry-narrative piece, displaced to keep category breadth (technology was already represented by the Meta and CXMT items) rather than concentrating three of five slots in tech/AI. For NBC, "First Kenyan-born NFL player deported, ICE says" — a genuine immigration-policy story, but judged more single-case and personality-driven than the death-row exoneration story, which carries broader criminal-justice-system consequences. For AP, "US nuclear regulators want to nix a requirement that keeps exposures to radiation low" — a significant regulatory-safety story (and yesterday's AP selection), but its `datePublished` (2026-07-26T13:00:25Z) fell roughly 38 minutes before this window opened, so it was excluded on timing grounds independent of its merits.

No outlet's list contained three or more items concerning the same underlying development. Two related-but-distinct Iran-war items appear within NBC (oil-market reaction and the weapons-stockpile debate) and within AP (the diplomatic pause and the Pentagon casualty-count change) — in each case only two items, each representing a clearly distinct consequence (markets/military-readiness, or diplomacy/institutional-accountability), so no redundancy threshold was reached within any single outlet.
