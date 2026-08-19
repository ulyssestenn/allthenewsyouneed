## WSJ

1. [Disney Sues FCC Over License Review, Says Government Trying to Quash Free Speech](https://www.wsj.com/business/media/disneys-abc-sues-fcc-over-challenge-to-its-broadcast-licenses-64e8f794)
2. [Iran's Attacks on Ships in Hormuz Mount, Testing U.S. Military Restraint](https://www.wsj.com/world/middle-east/irans-attacks-on-ships-in-hormuz-pile-up-testing-u-s-military-restraint-6ff9f5dd)
3. [Wall Street Sees No End in Sight to the Global Bond Selloff](https://www.wsj.com/finance/investing/wall-street-sees-no-end-in-sight-to-the-global-bond-selloff-a1b5d1e3)
4. [Pivotal Child Safety Trial That Could Change Instagram Starts in California](https://www.wsj.com/tech/massive-child-safety-trial-against-meta-starts-in-federal-court-130e3739)
5. [Trump Pauses 50% Tariff on Some Canadian Products](https://www.wsj.com/economy/trade/trump-pauses-50-tariff-on-some-canadian-products-2b3fd404)

## NYT

1. [Two Ships Transiting Strait of Hormuz Are Attacked as Oil Prices Rise](https://www.nytimes.com/2026/08/18/business/strait-of-hormuz-ship-attack.html)
2. [ABC Sues Trump Administration Over F.C.C. Threat to Its TV Licenses](https://www.nytimes.com/2026/08/18/business/media/abc-fcc-lawsuit-broadcast-licenses.html)
3. [Meta to Stand Trial Over Claims It Addicted Children to Social Media](https://www.nytimes.com/2026/08/18/technology/meta-social-media-addiction-trial.html)
4. [Bond Sell-Off Sends Borrowing Costs to Highest Level Since 2007](https://www.nytimes.com/2026/08/18/business/oil-prices-bonds.html)
5. [Trump Pauses 50 Percent Tariffs on Canada and Claims Deal Is Near](https://www.nytimes.com/2026/08/18/world/canada/tariffs-trade-trump-carney.html)

## NBC

1. [Trump pauses 50% tariffs on Canada for 3 days, citing a new deal](https://www.nbcnews.com/business/economy/trump-pauses-canada-tariffs-rcna593176)
2. [U.S. military drills with South Korea are cut short after surprise order](https://www.nbcnews.com/world/asia/us-south-korea-joint-military-drills-scaled-back-trump-order-rcna593264)
3. [China's backflipping robots leap to blockbuster stock market debut in latest sign of AI boom](https://www.nbcnews.com/world/asia/unitree-china-robot-maker-stock-market-ai-humanoids-tech-trump-rcna593278)
4. [Merck and Moderna say cancer vaccine shows promise in preventing recurrence of melanoma](https://www.nbcnews.com/health/health-news/merck-moderna-say-melanoma-vaccine-promise-prevent-recurrence-cancer-rcna593316)
5. [Gov. Josh Shapiro takes a hard line against 'predatory' data center developers in Pennsylvania](https://www.nbcnews.com/politics/2028-election/gov-josh-shapiro-executive-order-data-centers-pennsylvania-rcna593177)

## AP

1. [United Arab Emirates suspends trade with Iran after coming under renewed missile fire](https://apnews.com/article/iran-united-arab-emirates-trade-august-19-2026-47c95fe382c49289ab0419310b6d8057)
2. [Jury selection begins in Meta youth harms trial in California federal court](https://apnews.com/article/meta-oakland-trial-states-children-harms-d35bc173d109c156ce911aa6a1e2f05b)
3. [South Korean and US militaries shorten drills by about half after Trump ordered a reduction](https://apnews.com/article/korea-us-military-drills-313e01e4ee305b4c9b1b8bf12643fb17)
4. [Zelenskyy fires a top aide amid a graft probe as Ukraine's ex-defense minister demands elections](https://apnews.com/article/russia-ukraine-war-fedorov-zelenskyy-8c808244dcf51217027ebc97dba01761)
5. [Israeli military launches criminal probes into killings of Hind Rajab and Palestinian paramedics](https://apnews.com/article/israel-military-hind-rajab-gaza-parademics-investigations-c0a733a3ac78660b474e5bdb47154f8b)

## Note

**Selection window:** 2026-08-18 13:37 UTC to 2026-08-19 13:37 UTC (24 hours), filtered by original publication timestamp (each outlet's RSS `<pubDate>`, or the AP article page's `data-posted-date-timestamp`/`og:title` metadata for AP), not update or retrieval time.

**Access notes:**
- All eight listed WSJ feeds, all ten listed NYT feeds, and all eight listed NBC feeds were fetched directly and parsed successfully (1,025 raw items across all three outlets before windowing/dedup).
- A parsing bug in the first pass (RSS `<link>` colliding with the namespaced `<atom:link>` element, which has no text) initially zeroed out nearly all NYT links; this was caught and fixed before selection, and all NYT links below are direct, verified article URLs.
- AP does not publish a general RSS feed. The Google News search (`site:apnews.com when:1d`) was fetched for candidate discovery, but as before, its `<pubDate>` reflects Google's crawl/discovery time rather than AP's original publication time, and its article links are opaque redirect tokens. Every AP candidate was instead verified directly against apnews.com's own search results, reading each article's true `data-posted-date-timestamp` and canonical `apnews.com/article/...` URL from the page markup. This surfaced several Google News items whose *listed* time looked in-window but whose *actual* original AP publication time was not: "ABC sues FCC over challenge to its broadcast licenses" was originally posted at 13:33:37 UTC on Aug. 18 — about 4 minutes before this window opened — so it was dropped despite being the single most attention-grabbing AP candidate of the day; "Judge blocks the Trump administration from moving FBI headquarters to DC office building" was originally posted at 23:40:37 UTC on Aug. 17, well outside the window, despite Google News surfacing it with a same-day-looking timestamp; and AP's Canada-tariff coverage lives under a single continuously-updated article first posted at 04:01:06 UTC on Aug. 18 (before the window), so no qualifying original AP publication existed for today's tariff-pause news even though WSJ, NYT, and NBC each had fresh, in-window articles on it.
- WSJ and NYT article pages return 401/403 to non-browser HTTP requests even though their RSS feeds are open, so WSJ/NYT links above are used verbatim from each outlet's own RSS `<link>` field, consistent with each feed's own headline text. AP links were verified with direct 200-status fetches.

**Selection rationale:** The day's dominant throughline was the Iran standoff widening into concrete economic and military fallout: two ships were attacked transiting the Strait of Hormuz, oil prices and global bond yields moved as investors priced in the stalemate, and the UAE suspended trade with Iran after being targeted by missile fire — a fresh diplomatic and economic rupture distinct from the ship attack itself. ABC/Disney's lawsuit against the FCC over broadcast-license threats was a first-amendment and media-regulation story covered heavily across outlets, and a landmark trial over Meta's alleged harm to children opened in California, with major implications for social-media regulation. Trump's last-minute pause of 50% tariffs on Canada averted a trade rupture between the two countries. Elsewhere: the U.S. and South Korea scaled back joint military drills as Trump courts Kim Jong Un, Zelenskyy fired a top aide amid a corruption probe as his ex-defense minister broke with him to demand elections, Israel opened criminal probes into the killing of a 6-year-old girl and Gaza aid workers, Merck and Moderna reported a melanoma vaccine breakthrough, and China's Unitree had a blockbuster robotics IPO despite U.S. sanctions. Deprioritized: the wall-to-wall Florida primary results (governor, Senate, and House races all decided the same night, generating a dozen-plus redundant candidate-profile stories per outlet), Hayden Panettiere's death and its tabloid-style follow-on coverage, Penn State fraternity drug-ring arrests, sports scores, and shopping/lifestyle filler.

**Strongest excluded candidates:**
- **WSJ:** "Chinese Humanoid Robot Leader Soars in Market Debut Despite U.S. Ban" (Unitree's IPO) — a genuine markets/tech milestone, but excluded from WSJ's list because it is a single-company debut rather than a broader structural shift, and the day's stronger tech/law story (the Meta child-safety trial) already covered the technology beat.
- **NYT:** "U.A.E. Halts Trade Ties With Iran and Says It Was Targeted With Missiles" — a real new geopolitical rupture, but excluded from NYT's own list because the Hormuz ship-attack story already carried the day's Iran-conflict thread for NYT, and four other picks (media law, tech law, markets, trade) offered stronger topical range.
- **NBC:** Two candidates were effectively tied for strongest excluded. "Disney and ABC sue FCC, accusing Trump administration of 'retaliatory campaign'" was published at 12:34:57 UTC on Aug. 18 — about 62 minutes before this window opened — and would likely have topped NBC's list had it fallen inside the window. Within the window, "Republican Byron Donalds and Democrat David Jolly set to square off for Florida's governorship" was the strongest of roughly a dozen Florida-primary stories NBC ran; it was excluded because the data-center policy story (Shapiro's Pennsylvania order) reflects a broader multistate infrastructure trend rather than a single state's horse race.
- **AP:** "A new look and fresh merch are winning customers back at Target as sales rebound" — a solid business story with a real turnaround narrative, but excluded because it is more routine quarterly-earnings news than the five geopolitical, legal, and industry-changing stories that made AP's final list.

**Redundancy check:** No outlet had three or more selections tied to the same underlying development. Two Iran-related picks appear on both WSJ's and NYT's lists (the Hormuz ship attacks and the bond/market reaction), but each represents a genuinely distinct consequence — the military event itself versus its downstream financial effect — rather than one story split across slots. All three outlets that covered the Canada tariff pause (WSJ, NYT, NBC) used it as one of five distinct picks alongside four unrelated stories, not a repeated theme within any single outlet's list.
