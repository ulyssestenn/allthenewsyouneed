## WSJ

1. [Oil Nears $100 a Barrel as Fresh Attacks on Saudi Energy Operations Raise Supply Concerns](https://www.wsj.com/world/middle-east/oil-nears-100-a-barrel-as-fresh-attacks-on-saudi-energy-operations-raise-supply-concerns-568aad5f)
2. [GE Aerospace to Buy Consolidated Precision Products for $11.75 Billion](https://www.wsj.com/business/deals/ge-aerospace-to-buy-consolidated-precision-products-for-11-75-billion-ed7c8fc8)
3. [China's Trade Surplus Widens as Export Growth Accelerates](https://www.wsj.com/economy/trade/chinas-trade-surplus-widens-as-export-growth-accelerates-f4418eda)
4. [Mistral AI Exceeds $24 Billion Valuation After Samsung-Led Investment Round](https://www.wsj.com/tech/ai/mistral-ai-exceeds-24-billion-valuation-after-samsung-led-investment-round-ea377b82)
5. [After Far-Right Triumph, Merz Faces Narrow Path to Save His Government](https://www.wsj.com/world/europe/after-far-right-triumph-merz-faces-narrow-path-to-save-his-government-670f62c7)

## NYT

1. [UK Imposes Sanctions on Israeli Settlements in West Bank, Accuses Settlers of Ethnic Cleansing](https://www.nytimes.com/2026/09/08/world/europe/uk-sanctions-israel-west-bank-settlements.html)
2. [Canada's Retaliatory Tariffs Set to Take Effect as Trump Threatens to Escalate](https://www.nytimes.com/2026/09/07/world/canada/tariffs-trade-war-carney-trump.html)
3. [Oil Climbs Toward $100 a Barrel Following Houthi Attacks](https://www.nytimes.com/2026/09/08/business/oil-prices-iran-war.html)
4. [AfD's Far Right Win Puts New Pressure on Germany's Leader Merz](https://www.nytimes.com/2026/09/08/world/europe/germany-merz-pressure-afd.html)
5. [A.I. Models Built a Computer Worm That Could Rapidly Hack WeChat Accounts](https://www.nytimes.com/2026/09/08/us/politics/calif-ai-worm-wechat-hack.html)

## NBC

1. [Oil nears $100 after Saudi Arabia says energy infrastructure was attacked](https://www.nbcnews.com/business/energy/oil-prices-iran-war-saudi-arabia-rcna596558)
2. [Chinese hackers are running AI on stolen networks to avoid detection, Google says](https://www.nbcnews.com/tech/security/chinese-hackers-are-running-ai-stolen-networks-avoid-detection-google-rcna596155)
3. [Trump threatens to ban Bombardier jet sales as Canada's retaliatory tariffs take effect](https://www.nbcnews.com/politics/trump-administration/trump-calls-bombardier-plane-ban-drawing-pushback-gop-senator-rcna596525)
4. [Victims of Miami plane crash were in a cleaning company van and an SUV, officials said](https://www.nbcnews.com/news/us-news/victims-amazon-branded-plane-crash-van-suv-rcna596502)
5. [New Hampshire primaries test Trump and the left](https://www.nbcnews.com/politics/2026-election/new-hampshire-primaries-test-trump-left-rcna596109)

## AP

1. [Houthi attacks on Saudi Arabia ignite fires at oil facilities and wound 73 people](https://apnews.com/article/saudi-arabia-yemen-houthis-4ad9446f0bb8c096750c84b6e1ba86b8)
2. [UK government bans goods from Israeli settlements in the West Bank in a toughening of its stance](https://apnews.com/article/uk-west-bank-israel-settlement-sanctions-b4d7354221bfe0c48e4bfce7a3b7624b)
3. [Trump threatens Canadian jetmaker Bombardier, which has an extensive US footprint](https://apnews.com/article/trump-canada-carney-trade-bombardier-aircraft-e65b6eeaaa7ffbd06a67a57fb474b2e9)
4. [China's exports pick up in August, jumping 25% as its trade surplus widens](https://apnews.com/article/china-trade-exports-digital-trump-jinping-77c208d1f62270bba66b8241b1b14a4c)
5. [Zelenskyy says US envoys have 'very good' ideas to end Russia's war on Ukraine](https://apnews.com/article/russia-ukraine-war-kyiv-missiles-drones-attacks-fd634a6786462bc95b7dfefc97d2331e)

## Note

**Selection window:** 2026-09-07 13:36 UTC to 2026-09-08 13:36 UTC (24 hours), filtered by each item's original publication timestamp (each outlet's own RSS `<pubDate>` for WSJ/NYT/NBC; for AP, the `datePublished` timestamp embedded in the underlying apnews.com article page, not Google's feed-retrieval time).

**Access notes:**
- All eight listed WSJ feeds, all ten listed NYT feeds, and all eight listed NBC feeds were fetched directly with the specified user agent and parsed successfully as RSS/XML. No feed was inaccessible.
- The specified Google News search (`site:apnews.com when:1d`) was fetched directly and returned 100 real headlines with Google's own crawl-time timestamps, so it worked for candidate discovery. However, its `<link>` values are Google redirect tokens (`news.google.com/rss/articles/...`) that resolve only inside a JavaScript-rendered interstitial (confirmed unreachable both via direct fetch and via a headless browser through this session's network proxy). For each AP finalist, the exact headline text was instead cross-verified against AP's own site search (`apnews.com/search?q=...`, directly fetchable), matching the precise headline string to its canonical `apnews.com/article/...` URL and confirming its true `datePublished`. This surfaced a material discrepancy: Google's feed listed "Germany's Merz shocked by far-right state election triumph..." with a retrieval timestamp of 2026-09-08 01:01 UTC, inside the window, but the article's own `datePublished` on apnews.com was 2026-09-07 07:31 UTC — over six hours before the window opened — so it was dropped from AP's slate in favor of a genuinely fresh story (Zelenskyy's Ukraine remarks). All five final AP links were confirmed to return HTTP 200 with matching `<title>`/`og:title` and in-window `datePublished` metadata.
- WSJ and NYT article pages themselves returned 401/403 when fetched directly (both gate unauthenticated/bot-like requests behind paywall or bot checks); all five WSJ and five NYT links are canonical URLs taken directly from each outlet's own RSS feeds, with tracking query parameters stripped. All five NBC links were verified to return HTTP 200.
- One NBC candidate was dropped for the same original-publication reason as the AP swap above: a `today.com/video` segment titled "Trump asks Supreme Court to allow mail ballot restrictions to move forward for third time" carried an in-window feed timestamp, but the underlying story was first reported by NBC as a text article on 2026-09-06, two days before the window opened. It was replaced with "Victims of Miami plane crash were in a cleaning company van and an SUV, officials said," a text article with genuinely new reporting and an in-window publish time.

**Selection rationale:** The dominant cross-outlet development of the cycle was a wave of Houthi missile and drone attacks on Saudi Arabia's energy infrastructure, wounding more than 70 people, igniting fires at oil facilities, and pushing crude prices to the brink of $100 a barrel — selected independently by all four outlets as their top or near-top story, reflecting both an active war-conflict escalation and its immediate global economic transmission. A second cross-outlet thread was the U.S.-Canada trade war, which intensified as Canada's retaliatory tariffs took effect and Trump specifically threatened Canadian planemaker Bombardier, covered by NYT, NBC, and AP. A third thread was the aftermath of Alternative for Germany's landslide state-election win, with Chancellor Merz's governing coalition under new strain, covered by WSJ and NYT (and initially by AP, before its story was found to predate the window). Beyond these threads, outlets diverged to capture other durable stories: a major aerospace acquisition and a fresh AI financing round underscoring continued industry consolidation and capital flows (WSJ); the UK's new sanctions regime on Israeli West Bank settlements and the first documented case of AI models being used to build hacking malware (NYT); Google's disclosure that state-linked hackers are now running AI directly on compromised networks, and new detail on the fatal Miami cargo-plane crash (NBC); and renewed U.S. diplomatic engagement on ending the Russia-Ukraine war alongside China's accelerating export surge ahead of Trump-Xi talks (AP).

**Strongest excluded candidates:**
- **WSJ:** "AI Use Contributes to Global Decline in Student Reading Skills, OECD Says" — a genuine durable education-and-technology story, narrowly excluded because the slate already carried a technology/AI-industry item (Mistral's valuation) and four other selections offered more immediate market or geopolitical consequence.
- **NYT:** "China's Surging Exports Loom Over Trump's Talks With Xi" — a real and consequential economic story, but it overlapped heavily with WSJ's own China-trade coverage that day; NYT's AI-worm/WeChat-hacking story was judged more novel and carried more distinct durable security implications.
- **NBC:** "Iran increases gasoline price for its heaviest consumers as economy struggles" — a legitimate economic story reflecting the toll of sustained conflict, but narrower in scope and impact than the five selected, and largely a data point within the broader Iran-conflict thread already reflected elsewhere in the day's coverage.
- **AP:** "China's Huawei Technologies faces racketeering trial in New York" — a substantive legal/technology story with real institutional consequence, but its impact is narrower and more company-specific than the five macro/geopolitical developments selected.

**Redundancy check:** No outlet had three or more of its own five selections tied to a single underlying development. The Houthi/Saudi oil-price story and the U.S.-Canada trade war were each independently selected by three or more outlets across the digest, but within any single outlet's own slate no more than one item touched either topic, so no substitution was required under the redundancy rule.
