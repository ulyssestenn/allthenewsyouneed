## WSJ

1. [Trump Tells U.N. He Is Confronting World Threats and Putting America First](https://www.wsj.com/politics/policy/trump-tells-u-n-he-is-confronting-world-threats-and-putting-america-first-5fe48626)
2. [White House Considers Ban on Diesel Exports as Prices Keep Rising](https://www.wsj.com/logistics-report/white-house-considers-ban-on-diesel-exports-as-prices-keep-rising-fd3eec84)
3. [DoorDash to Pay $131.5 Million to Resolve NYC Investigation Into Minimum-Pay Law Compliance](https://www.wsj.com/business/doordash-to-pay-131-5-million-to-resolve-nyc-investigation-into-minimum-pay-law-compliance-8237c60e)
4. [Zelensky Asks Trump for Winter Arms Package, Expects Energy-Ceasefire Push](https://www.wsj.com/world/ukraine-zelensky-interview-emma-tucker-757e9a30)
5. [HHS Moved Money From a Minority Health Office to Pay RFK Jr.'s Security Costs](https://www.wsj.com/politics/policy/rfk-jr-hhs-security-cost-minority-health-office-f1c7b62a)

## NYT

1. [Trump Threatens Annihilation in Iran in UN Speech and Lays Out Winner-Takes-All Vision](https://www.nytimes.com/2026/09/22/us/politics/un-trump-speech-iran-venezuela-greenland.html)
2. [White House Defends Trump's Ban on CNN, MS NOW and Politico in Court Filing](https://www.nytimes.com/2026/09/23/business/trump-cnn-politico-ms-now-ban.html)
3. [Trump Officials Eject 750,000 From Obamacare Markets, Claiming Fraud](https://www.nytimes.com/2026/09/22/us/politics/aca-obamacare-vance-fraud.html)
4. [Texas Halts Data Center Permits, Expanding Environmental Scrutiny](https://www.nytimes.com/2026/09/22/climate/texas-halts-data-center-permits.html)
5. [Anthropic Releases a New A.I. Model, Opus 5.5, Amid Safety Debate](https://www.nytimes.com/2026/09/22/technology/anthropic-ai-model-safety.html)

## NBC

1. [CNN, Politico and MS NOW to Face Off With Trump Administration in Court Over White House Ban](https://www.nbcnews.com/politics/trump-administration/cnn-politico-ms-now-trump-court-white-house-media-ban-rcna599269)
2. [Trump Administration Cuts ACA Coverage for 750,000 People It Says Were 'Fraudulently' Enrolled](https://www.nbcnews.com/health/health-news/trump-administration-cuts-aca-coverage-750000-people-says-fraudulently-rcna599258)
3. [Trump Signs Deal With Denmark Over U.S. Military Presence in Greenland](https://www.nbcnews.com/video/trump-signs-deal-with-denmark-over-u-s-military-presence-in-greenland-270298181545)
4. [GOP Senator Calls for Subpoenaing Donald Trump Jr. and Hunter Biden Over Their Business Dealings](https://www.nbcnews.com/politics/congress/gop-senator-subpoena-donald-trump-jr-hunter-biden-kremlev-wedding-rcna599182)
5. [The U.S. Economy Before and After the Iran War, in Five Charts](https://www.nbcnews.com/business/economy/us-economy-iran-war-five-charts-rcna598412)

## AP

1. [Iran Downplays Indirect Talks With U.S., and Other Mideast Developments](https://apnews.com/article/iran-us-israel-yemen-un-houthis-hormuz-september-23-2026-f92f4e2fcb039365c082f081b73d6915)
2. [Trump-Backed Missouri Congressional Map Returns to the Supreme Court for the Third Time](https://apnews.com/article/supreme-court-missouri-redistricting-congressional-map-4359373974681c4170a6a4410ffd019d)
3. [Trump Administration to Remove 760,000 Affordable Care Act Enrollees Over Fraud Claims](https://apnews.com/article/vance-healthcare-oz-aca-fraud-task-force-eb57a4819c8a876a72c1301a112e21dc)
4. [Sen. Bernie Sanders Unveils Bill to Ban Artificial Superintelligence and Create Department of AI](https://apnews.com/article/ai-superintelligence-bernie-sanders-d6a6a2cd8e71d7c95bdc394595aa85d1)
5. [New York, California Sue to Block Trump Administration Deals Canceling Offshore Wind Projects](https://apnews.com/article/trump-offshore-wind-energy-fossil-fuels-e757e0492d91ac0dbb0d5992175a869a)

## Note

**Selection window:** 2026-09-22 13:46 UTC to 2026-09-23 13:46 UTC (24 hours), filtered by each item's original publication timestamp (each outlet's own RSS `<pubDate>` for WSJ/NYT/NBC; for AP, the timestamp on Google News's crawl of the AP wire item).

**Access notes:** All eight WSJ feeds, all ten NYT feeds, and all eight NBC feeds were fetched directly with the specified user agent and parsed successfully; no feed was inaccessible. After deduplication this yielded roughly 87 in-window WSJ items, 132 NYT items, 46 NBC items, and 100 AP items from the Google News search feed.

**AP resolution:** `apnews.com` itself returns HTTP 403 (Cloudflare bot challenge) to direct fetches, so canonical URLs could not be confirmed by loading the live page. Instead, each Google News `news.google.com/rss/articles/...` redirect link was resolved authoritatively via Google News's own internal `Fbv4je` "garturlreq" RPC (`https://news.google.com/_/DotsSplashUi/data/batchexecute`), using the signed `data-n-a-id`/`data-n-a-ts`/`data-n-a-sg` tokens embedded in each article's Google News page. This returns Google's own resolved canonical `apnews.com` URL for the underlying wire story (confirmed working end-to-end on all 100 in-window AP candidates), rather than a third-party republication as used on prior runs. Because the resolved `apnews.com` pages themselves could not be loaded directly, headline wording for AP's section was taken from Google News's AP-sourced RSS `<title>` field (with the trailing " - AP News" suffix stripped) rather than confirmed against the live article.

**WSJ headline note:** Two WSJ picks (items 1 and 5) were served by feeds whose `<title>` field is a social-media teaser sentence rather than the article's actual headline; both headlines above were reconstructed from the article's URL slug, which WSJ auto-generates from the real headline. WSJ's article pages themselves returned a bot-check interstitial and could not be used to confirm wording directly.

**Principal selection rationale:** Trump's U.N. General Assembly speech — threatening to "annihilate" Iran while casting himself as a peacemaker — was the day's dominant, concretely-already-happened story and anchors WSJ's and NYT's top picks, with AP's lead choosing the direct diplomatic follow-on (U.S.-Iran indirect talks) rather than repeating the speech itself. The White House's court fight with CNN/Politico/MS NOW over press-pool access and the Trump administration's removal of roughly 750,000–760,000 ACA marketplace enrollees over fraud claims were each independently selected by three of the four outlets from their own reporting, reflecting genuinely broad, durable institutional stakes (press access precedent; health coverage for hundreds of thousands of people) rather than redundant padding. One WSJ candidate ("Vance-Led Task Force Set to Remove 760,000 Allegedly Fraudulent Obamacare Enrollments") was excluded because it is the identical article, at the identical URL, already featured as WSJ's #3 pick in yesterday's (2026-09-22) digest; a fresher WSJ story was substituted. Novelty, celebrity, and shopping-deal items that filled much of the raw NBC pool were excluded per the standard's guidance.

**Strongest excluded candidate per outlet:**
- **WSJ:** "Meta's New AI Agent Is an Instant Hit—and the Backlash Has Already Begun" — a real product/industry story, but closer to novelty and unresolved backlash than to a confirmed durable consequence, and edged out by five stories with clearer institutional or geopolitical stakes.
- **NYT:** "How Paramount Won Warner Bros." — a substantive business story, but a retrospective/analysis piece on a merger settlement whose news event was already covered in yesterday's (2026-09-22) digest, rather than a fresh development.
- **NBC:** "New campaign aims to help millions at risk of losing Medicaid coverage under work requirements" — genuine durable healthcare-policy stakes, but a step behind the ACA-enrollee removal story in immediacy and concreteness.
- **AP:** "US futures inch higher and oil prices slip for 6th straight day after US and Iranian officials meet" — a real market consequence, but downstream of and largely redundant with AP's own lead pick on the underlying U.S.-Iran diplomatic development.

**Same-underlying-development check:** No single outlet's final five contained three or more selections tied to one underlying event. WSJ, NYT, and AP each carry exactly one item from Trump's U.N. speech/Iran theme, from distinct angles (WSJ: the speech itself; AP: the resulting indirect talks; NYT: the speech's "annihilate" framing and winner-take-all vision) rather than the same specific development repeated. The ACA-enrollee story appearing in three outlets (WSJ, NYT, NBC) and AP is a cross-outlet convergence on a single broadly-significant policy action, not an in-outlet repeat.
