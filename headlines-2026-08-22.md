## WSJ

1. [U.S. Imposes 50% Tariffs on Some Canadian Goods After Last-Ditch Talks Fail](https://www.wsj.com/economy/trade/u-s-to-impose-50-tariffs-on-some-canadian-goods-after-failed-talks-d1510425)
2. [Trump Can Keep Building Ballroom While Supreme Court Weighs Appeal](https://www.wsj.com/politics/policy/trump-can-keep-building-ballroom-while-supreme-court-weighs-appeal-a749e6b1)
3. [Iran's Top Politicians Urge an End to the War](https://www.wsj.com/world/middle-east/irans-top-politicians-urge-an-end-to-the-war-d0936e12)
4. [Mexican Governor Indicted by U.S. Returns to Office](https://www.wsj.com/world/americas/mexican-governor-indicted-by-u-s-vows-return-to-office-fe6ecff7)
5. [Boeing Engineers, Technical Workers Reject Four-Year Contract Offer](https://www.wsj.com/business/boeing-engineers-technical-workers-reject-four-year-contract-offer-1a683686)

## NYT

1. [Canada-U.S. Trade War Escalates as Talks Collapse](https://www.nytimes.com/2026/08/21/world/canada/trump-tariffs-trade-no-deal-carney-canada.html)
2. [Anthropic Could Aim to Raise $100 Billion in Blockbuster I.P.O.](https://www.nytimes.com/2026/08/21/technology/anthropic-ipo-100-billion.html)
3. [Judge Strikes Down Trump's 75-Country Visa Ban](https://www.nytimes.com/2026/08/21/us/politics/judge-trump-75-country-visa-ban.html)
4. [Postal Service Publishes Finalized Plan to Restrict Mail Ballots](https://www.nytimes.com/2026/08/21/us/politics/postal-service-rule-restrict-mail-ballots.html)
5. [Pentagon Fires Editor and Publisher of Independent Military Publication](https://www.nytimes.com/2026/08/21/us/politics/pentagon-fires-stars-stripes-editor.html)

## NBC

1. [Canadian prime minister suspends trade talks with U.S., setting new 50% tariffs in motion](https://www.nbcnews.com/business/economy/trump-canada-tariffs-carney-rcna593510)
2. [Supreme Court temporarily allows Trump ballroom construction to continue](https://www.nbcnews.com/politics/supreme-court/supreme-court-trump-white-house-ballroom-rcna592899)
3. [Alfalfa sprouts recalled for E. coli and salmonella after dozens of illnesses in 15 states](https://www.nbcnews.com/health/health-news/sprouts-e-coli-salmonella-illnesses-minnesota-wisconsin-rcna593710)
4. [11 arrested by federal agents aboard two cruise ships in Boston](https://www.nbcnews.com/news/us-news/11-arrested-federal-agents-board-cruise-ships-boston-rcna593791)
5. [Trump says loyalist Ed Martin to leave the DOJ to focus on election-related legal battles](https://www.nbcnews.com/politics/justice-department/trump-loyalist-ed-martin-leaving-justice-department-pardon-attorney-rcna593793)

## AP

1. [US imposes 50% tariffs on Canadian products. Canada plans to retaliate](https://apnews.com/article/canada-us-trade-tariffs-trump-857ef76b20a766e370d70176135b678e)
2. [TikTok agrees to $400M settlement with US Department of Justice](https://apnews.com/article/tiktok-doj-settlement-children-privacy-coppa-7d92b65fa23968b8ce13ea3b5c52e7a4)
3. [Amid dire drought on the Colorado River, federal officials announce water cuts to three states](https://apnews.com/article/colorado-river-drought-water-cuts-dfb3a5deec3ecaeab0632dca7a10612e)
4. [Pentagon fires Stars and Stripes' top editor, publisher and a reporter](https://apnews.com/article/stars-stripes-pentagon-censorship-media-d42affb0c17fef31c6089645c8dbbe70)
5. [Congo receives first 16,000 doses of possible Ebola vaccine](https://apnews.com/article/congo-ebola-vaccine-1ce25c0697bfae7656eae3e5fe6aa6ae)

## Note

**Selection window:** 2026-08-21 13:36 UTC to 2026-08-22 13:36 UTC (24 hours), filtered by original publication timestamp (each outlet's RSS `<pubDate>`, or AP's own `datePublished` page metadata), not update or retrieval time.

**Access notes:**
- All eight listed WSJ feeds, all ten listed NYT feeds, and all eight listed NBC feeds were fetched directly and parsed successfully (979 raw items across the three outlets before windowing/dedup; 380 fell inside the 24-hour window).
- AP does not publish a general RSS feed. The Google News search (`site:apnews.com when:1d`) was fetched for candidate discovery; its `<pubDate>` values are Google's own crawl timestamps, which are usable for AP (unlike some prior days' section-front timestamps) because they track closely with when Google indexed each freshly published story. However, its article links are opaque `news.google.com/rss/articles/...` redirect tokens, not direct `apnews.com` URLs, and following the redirect (even with cookies) only returns Google's client-rendered shell with no embedded source URL. Each shortlisted AP candidate was instead resolved by querying AP's own site search (`apnews.com/search?q=...`) for matching keywords, then confirming the correct result by fetching each candidate `apnews.com/article/...` page directly and checking its `<title>` and `datePublished` metadata against the Google News headline and timestamp.
- WSJ and NYT article pages return 401/403 to non-browser HTTP requests even though their RSS feeds are open, so WSJ/NYT links above are used verbatim from each outlet's own RSS `<link>` field (WSJ links had tracking query parameters stripped to their canonical form), consistent with each feed's own headline text.
- One NBC pick, "11 arrested by federal agents aboard two cruise ships in Boston," and NBC's Ed Martin and Colorado-adjacent picks are text articles; NBC's tariffs story was only available in the feed as a same-day rewrite of an earlier video segment, so the fuller text article covering the same news (`nbcnews.com/business/economy/trump-canada-tariffs-carney-rcna593510`) was used instead of the shorter video item.
- The Alaska plane-crash story (8 killed near a remote military radar site) remained in heavy rotation across all four outlets today but was excluded from every outlet's list here: WSJ's and NBC's in-window items today resolve to the identical articles/story already selected in yesterday's digest (2026-08-21), so continued coverage of the same underlying event was not treated as a new development.

**Selection rationale:** The U.S.-Canada trade war's escalation into active 50% tariffs (after last-ditch talks collapsed at midnight) is the day's dominant, cleanly cross-outlet story and leads WSJ, NYT, NBC, and AP alike — each outlet's own reporting, not a repeated link. Beyond that, distinct institutional threads defined the day: two press-freedom/military-oversight stories (the Pentagon's dismissal of Stars and Stripes' editor, publisher, and a reporter after they objected to interference, selected independently by NYT and AP) and a Supreme Court order letting White House ballroom construction continue while weighing Trump's appeal (WSJ and NBC) both bear on the boundaries of executive power. Regulatory and legal precedent also advanced: a federal judge struck down Trump's 75-country visa ban, TikTok agreed to a $400 million settlement with the Justice Department over children's-privacy violations, and the Postal Service finalized a rule restricting mail ballots ahead of the midterms. Anthropic's reported plans for a $100 billion IPO was selected as a tech/business story with industry-wide significance for AI-sector valuations. Elsewhere, durable non-U.S. developments included Iran's top politicians publicly urging an end to the conflict with the U.S. (a potential inflection point after months of standoff), a Mexican governor indicted by U.S. prosecutors over cartel ties returning to office, and Congo's Ebola response receiving its first vaccine shipment amid the largest outbreak on record. Consumer/public-health and labor stories rounded out the set: a 15-state E. coli/salmonella outbreak linked to alfalfa sprouts, Boeing engineers and technical workers rejecting a four-year contract offer, federal water cuts to three Colorado River states amid a 26-year drought, and a wave of federal immigration-enforcement arrests aboard cruise ships in Boston. Deprioritized: Prince Harry and Meghan's move back to the UK (heavily covered everywhere but a private/royal-life story), the ongoing Lindsay Clancy and Alex Jones trial-update coverage, South Carolina primary campaign-trail stories, sports and awards coverage, and lifestyle/shopping filler.

**Strongest excluded candidates:**
- **WSJ:** "GM Faces Safety Probe Over Engine-Failure Concerns in Nearly One Million Vehicles" — a real consumer-safety story at significant scale, but excluded because it is a probe rather than a confirmed finding or recall, ranking below the tariffs, ballroom, Iran, cartel-indictment, and Boeing-labor stories that filled WSJ's five slots.
- **NYT:** "TikTok Settles With U.S. Over Child Privacy Concerns for $400 Million" — a large, genuine regulatory settlement (and AP's own pick), but excluded from NYT's list because the trade war, Anthropic's IPO, the visa-ban ruling, the mail-ballot rule, and the Pentagon press-freedom firing carry comparably broad or longer-running institutional consequences.
- **NBC:** "Karoline Leavitt to work for Trump-affiliated super PAC after leaving White House" — a notable personnel move, but excluded as a staffing change with less durable consequence than the enforcement, health, trade, and legal-battle stories selected.
- **AP:** "Tesla recalls nearly 3M vehicles in China over door handle safety risks" — huge in scale, but excluded as a single-market safety recall next to the tariffs, TikTok settlement, Colorado River water cuts, Pentagon firing, and record Ebola outbreak response that filled AP's five slots.

**Redundancy check:** No single outlet had three or more selections tied to the same underlying development. The Canada-U.S. tariff escalation was independently selected by all four outlets (each counting it once, via its own reporting) reflecting genuine across-the-board significance rather than padding. The Pentagon's Stars and Stripes dismissals (NYT and AP) and the Supreme Court's White House ballroom order (WSJ and NBC) are the only other cross-outlet overlaps, again each outlet selecting the story only once.
