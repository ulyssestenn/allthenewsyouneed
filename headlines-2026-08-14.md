## WSJ

1. [Luigi Mangione Pleads Guilty to Federal Charges in Killing of Insurance Executive](https://www.wsj.com/us-news/law/luigi-mangione-pleads-guilty-to-federal-charges-in-killing-of-insurance-executive-7a7f4272)
2. [Retail Sales Fell Last Month](https://www.wsj.com/economy/consumers/retail-sales-fell-last-month-78fdf39a)
3. [NATO Jet Downs Drone as Concerns Grow Over Russia Threat](https://www.wsj.com/world/europe/nato-jet-downs-drone-as-concerns-grow-over-russia-threat-9b4b76c7)
4. [Trump Announces Drone Tariffs to Protect National Security, Bolster U.S. Supply Chains](https://www.wsj.com/economy/trade/trump-announces-drone-tariffs-to-protect-national-security-bolster-u-s-supply-chains-87bab5b8)
5. [Trump Orders Navy to Restore Older Tech on Aircraft Carriers, Costing Billions](https://www.wsj.com/us-news/trump-orders-navy-to-restore-old-technology-in-aircraft-carriers-costing-billions-0055ec1b)

## NYT

1. [Israeli Settlers Resume West Bank Siege After Eviction](https://www.nytimes.com/2026/08/13/world/middleeast/west-bank-siege-israeli-settlers.html)
2. [Zambia Halts Presidential Election Vote Count Over Violence and Fraud Allegations](https://www.nytimes.com/2026/08/14/world/africa/zambia-election-vote-count-suspended-president.html)
3. [France's Top Court Strikes Down Ban on Social Media for Children](https://www.nytimes.com/2026/08/14/world/europe/france-court-strikes-down-ban-social-media-children.html)
4. [July Retail Sales Notch Biggest Drop in Over a Year](https://www.nytimes.com/2026/08/14/business/retail-sales-july.html)
5. [Amazon and Alphabet's Profits Reveal Circular Nature of A.I. Boom](https://www.nytimes.com/2026/08/14/business/ai-tech-profits.html)

## NBC

1. [Luigi Mangione pleads guilty to federal charges in the killing of UnitedHealthcare's CEO](https://www.nbcnews.com/news/us-news/luigi-mangione-guilty-plea-federal-court-case-ceo-shooting-rcna592421)
2. [Trump asks Supreme Court to allow White House ballroom construction to continue](https://www.nbcnews.com/politics/supreme-court/trump-appeals-supreme-court-white-house-ballroom-rcna266912)
3. [Kennedy Center board votes to add president's name again — and throw in a 'Trump Plaza'](https://www.nbcnews.com/politics/trump-administration/kennedy-center-board-votes-partially-close-arts-center-renovations-add-rcna592355)
4. [Appeals court dodges major ruling on Trump's contentious use of obscure deportation law](https://www.nbcnews.com/politics/immigration/appeals-court-trump-alien-enemies-act-tren-de-aragua-venezuela-rcna592435)
5. [In an apparent shift, Vance says lowering oil prices is 'goal No. 1' of Iran war](https://www.nbcnews.com/world/iran/low-oil-prices-trump-goal-iran-war-vance-blockade-economic-pressure-rcna592504)

## AP

1. [Luigi Mangione pleads guilty in killing of UnitedHealthcare CEO](https://apnews.com/article/luigi-mangione-plea-unitedhealthcare-ceo-3b8a5bb41589c9f5f4775dba2beea66f)
2. [Surveillance operation in Minnesota targeted progressive groups, unions, court documents show](https://apnews.com/article/minnesota-immigration-enforcement-progressive-groups-investigated-5e6e554e79980553c3a02ca199593a7d)
3. [Retail sales slide unexpectedly in July](https://apnews.com/article/retail-inflation-consumer-sentiment-economy-3e2bc5807d7396b8e6c5f599941cb2a9)
4. [Trump asks Supreme Court to let White House ballroom work continue](https://apnews.com/article/trump-white-house-ballroom-supreme-court-84db62e26459e2206659d36cc5a749aa)
5. [Trump wants older tech used on aircraft carriers, likely costing billions](https://apnews.com/article/trump-aircraft-carriers-steam-catapults-ffa9f3ce102ecd5d6126db03e901a56f)

## Note

**Selection window:** 2026-08-13 17:07 UTC to 2026-08-14 17:07 UTC (24 hours), filtered by original publication timestamp in each feed, not update or retrieval time.

**Access notes:**
- All listed WSJ, NYT, and NBC feeds were fetched directly and parsed successfully.
- AP does not publish a general RSS feed. Candidates were sourced via Google News search (`site:apnews.com when:1d`), but Google's News redirect links use an opaque token that requires client-side JS to resolve and defeats direct HTTP fetch. Canonical apnews.com URLs were instead independently resolved by querying AP's own site search (apnews.com/search) with keywords from each candidate headline, then verifying the resulting article's `<title>` and `datePublished`/`dateModified` fields matched the candidate headline and fell within the selection window before inclusion.
- WSJ and NYT article pages return 401/403 to non-browser HTTP requests (bot/paywall protection) even though their RSS feeds are open; WSJ/NYT links above are used from each outlet's own RSS `<link>` field with tracking query parameters stripped, so they are canonical regardless of that block. Two WSJ headlines (the drone-tariff story and the Navy carrier-tech story) were reconstructed into clean headline form from the RSS `<title>`, which for those two items was a full descriptive sentence rather than a standalone headline; the reconstruction was checked against the article's URL slug for accuracy.

**Selection rationale:** Prioritized developments with durable, 30-day-relevant consequences: a federal guilty plea closing out a case with continuing implications for the healthcare-industry-outrage debate (Mangione, selected independently by all four outlets); a national-security tariff action and a NATO-Russia drone incident with ongoing conflict implications; a sharp, trend-confirming drop in July retail sales that is reshaping the economic-slowdown narrative across markets; a reversal of Navy aircraft-carrier launch technology carrying a multibillion-dollar cost; a Minnesota surveillance disclosure raising government-overreach questions; a French constitutional-court ruling on a tech/child-safety law with precedent value beyond France; a contested Zambian presidential election with disputed legitimacy; and the AI-boom "circularity" story examining whether Big Tech's earnings are propped up by intra-industry investment. Deprioritized: shopping/product-recommendation posts, celebrity and reality-TV items, film/TV/book reviews, routine game recaps, and the Mangione case's ancillary video/rundown coverage once the core plea story was captured.

**Strongest excluded candidates:**
- **WSJ:** "Charter Gets Final State Approval for $21.9 Billion Cox Deal" — a major telecom-cable consolidation, but this was the last procedural approval of a deal already announced and priced in, rather than a fresh development.
- **NYT:** "Homeland Security Paid $464 Million for Airplanes. Then It Parked Them." — a solid accountability story, but narrower in scope than the institutional and policy stories selected.
- **NBC:** "Judge shows signs of frustration with DOJ attorneys over handling of Epstein files" — a real development in an ongoing saga, but incremental rather than resolving anything new.
- **AP:** "Italian police recover stolen Renoir, Cézanne and Matisse artworks worth millions" — a genuinely notable cultural-crime story, but judged to have less durable, forward-looking consequence than the institutional and policy items chosen.

**Redundancy check:** No outlet had three or more selections tied to the same underlying development. The Mangione guilty plea, the July retail-sales report, and the White House ballroom Supreme Court appeal each appear in more than one outlet's list, but each outlet selected each story only once, independently, so no consolidation was needed.
