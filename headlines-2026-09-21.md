## WSJ

1. [CNN, MS NOW and Politico Are Suing the Trump Administration After Their Journalists Were Denied Entry to the White House](https://www.wsj.com/politics/policy/cnn-ms-now-politico-to-sue-white-house-over-reporter-ban-f1dceded)
2. [Trump Ramps Up Bid to Dismantle International Criminal Court](https://www.wsj.com/politics/policy/trump-administration-prepares-to-sanction-the-international-criminal-court-85f5f44c)
3. [Tanker Shortage Sends Oil-Shipping Rates Soaring](https://www.wsj.com/logistics-report/tanker-shortage-sends-oil-shipping-rates-soaring-d526cdb7)
4. [Trump's Greenland Deal Eases Way for U.S. Business on Arctic Island](https://www.wsj.com/world/trumps-greenland-deal-eases-way-for-u-s-business-on-arctic-island-1cbef960)
5. [Apartment Landlords Have a $2 Trillion Debt Problem That Is Only Getting Worse](https://www.wsj.com/real-estate/apartment-landlords-have-a-2-trillion-debt-problem-that-is-only-getting-worse-6a096162)

## NYT

1. [CNN, MS NOW and Politico to Sue Trump Administration Over White House Access](https://www.nytimes.com/2026/09/21/business/media/trump-white-house-ban-lawsuit-cnn-politico-msnow.html)
2. [Bessent and China Hail Progress on A.I. Talks. Now Comes the Hard Part.](https://www.nytimes.com/2026/09/21/business/dealbook/bessent-china-ai-talks.html)
3. [White House Moves to Take Control of N.I.H. Grants](https://www.nytimes.com/2026/09/20/science/nih-omb-grants-bhattacharya-vought.html)
4. [Ex-Commander of China's Military Accused of Corruption and Expelled From Party](https://www.nytimes.com/2026/09/21/world/asia/china-generals-expelled-corruption.html)
5. [Houthis Push to Expand Territory as Tensions With Saudi Arabia Rise](https://www.nytimes.com/2026/09/20/world/middleeast/saudi-arabia-yemen-houthis-fighting.html)

## NBC

1. [CNN, Politico and MS NOW Plan to Sue Trump Administration Over Ban on White House Coverage](https://www.nbcnews.com/politics/trump-administration/cnn-politico-ms-now-plan-sue-trump-administration-ban-white-house-cove-rcna598912)
2. [Tehran Warns of 'New Weapons' as Trump Weighs Meeting With Iranian President](https://www.nbcnews.com/world/middle-east/trump-wiping-out-iran-warns-new-weapons-rcna598954)
3. [U.S. Proposes AI Alert System With China Ahead of Trump-Xi Summit](https://www.nbcnews.com/world/asia/us-proposes-exchanging-ai-safety-alerts-china-bessent-says-rcna598923)
4. [ICE Agent Shoots Food Delivery Driver in His Car](https://www.today.com/video/protests-erupt-in-texas-after-ice-agent-shoots-delivery-driver-270208581665)
5. [California Tightens Disclosure Rules for Influencers Who Post Political Ads](https://www.nbcnews.com/news/us-news/california-tightens-disclosure-rules-influencers-political-ads-rcna598828)

## AP

1. [CNN, MS NOW, Politico Say They've Notified Trump They're Suing Over Denied White House Access](https://apnews.com/article/trump-ban-ms-now-media-cnn-politico-72f9acf68244ca70e9078d9d3661c722)
2. [The Main Kremlin Party Keeps Control of Russian Parliament After a Carefully Orchestrated Vote](https://apnews.com/article/russia-elections-kremlin-putin-5342c2757623f2e46e94b4c548e94213)
3. [Russia Targets Zaporizhzhia After Ukraine Launches 1,000-Drone Weekend Barrage](https://apnews.com/article/russia-ukraine-war-united-nations-drones-445b619fc9b2d002df1edaac8b320d09)
4. [Google Hit With $463 Million Fine for EU Location Data Rule Breach](https://apnews.com/article/google-eu-privacy-ireland-3447a228ad95b17c53e990dd0b4afd43)
5. [US Proposes AI Incident Alert System in Talks With China, Bessent Says](https://apnews.com/article/bessent-ai-xi-trump-china-trade-2c7f54f07e755f506d9db9b91df282bd)

## Note

**Selection window:** 2026-09-20 13:36 UTC to 2026-09-21 13:36 UTC (24 hours), filtered by each item's original publication timestamp (each outlet's own RSS `<pubDate>` for WSJ/NYT/NBC; for AP, the Google News crawl timestamp on the resolved canonical article).

**Access notes:** All eight WSJ feeds, all ten NYT feeds, and all eight NBC feeds were fetched directly with the specified user agent and parsed successfully; no feed was inaccessible. This yielded 62 in-window WSJ items after dedup, 74 NYT items, and 25 NBC items (NBC's in-window pool skewed heavily toward celebrity-death and sports-recap items, but still supplied five durable, non-redundant candidates).

**AP resolution:** `apnews.com` returns HTTP 403 to both direct `curl` and WebFetch on every path (a bot-protection wall, not specific to any article), confirming the source instructions' assumption that AP requires the Google News workaround. The specified Google News search (`site:apnews.com when:1d`) returned 100 candidates; a large share were AP topic/hub pages ("Artificial intelligence - AP News," "Crime - AP News"), author archives, or routine sports recaps and were excluded. Each remaining Google News redirect was resolved to its canonical `apnews.com/article/...` URL via Google News's internal article-redirect endpoint (`news.google.com/_/DotsSplashUi/data/batchexecute`, method `Fbv4je` — the same call the Google News web app makes when a reader clicks a headline), rather than a plain HTTP redirect, which Google News does not serve to non-browser clients.

**Repeat-story check:** Before finalizing, all candidates were cross-checked by URL against the three most recent digests (2026-09-18 through 2026-09-20) to avoid re-publishing an already-featured article rather than a genuinely new development. Four candidates were caught and replaced as exact repeats of 2026-09-20's picks (identical canonical URLs, same articles still surfacing in today's feed crawl): WSJ's "Trump Announces an 'AI Force'" (replaced with the Apartment Landlords debt story), NYT's "Hundreds of Drones Target Moscow on Final Day of Russian Elections" (replaced with the Houthis/Saudi Arabia escalation story), and AP's "Federal Reserve rate hike..." and "Ukraine fires over 1,000 drones at Russia, including hundreds launched at Moscow" (replaced with the Kremlin-party election story and the Zaporizhzhia-targeting story, respectively — a distinct facet of the same weekend drone barrage, newly reported today).

**Principal selection rationale:** The White House press-access lawsuit (CNN/MS NOW/Politico formally suing over the reporter ban) was the single story with the widest, most durable cross-outlet significance today — a First Amendment/press-freedom precedent — and leads three of the four outlets. U.S.-China AI-safety-alert talks ahead of the Trump-Xi summit were treated as a genuinely major, freshly-reported development (covered independently by NYT, NBC, and AP, each with its own distinct article) rather than as redundant padding. Continuing durable threads — the Russia-Ukraine drone war, Yemen/Saudi tensions, Germany's political fallout, and NIH grant oversight — were favored over one-off novelty items (celebrity deaths, game recaps, shopping deals) that filled much of the NBC and WSJ raw pools.

**Strongest excluded candidate per outlet:**
- **WSJ:** "Novo Nordisk Aims to Launch Several New Blockbuster Drugs in the Next Few Years" — a solid durable pharma-industry story, but narrower in consequence than the five selected.
- **NYT:** "Merz Vows to Stay After Another State Election 'Disaster'" — genuinely significant German political fallout, but AP's Kremlin-vote and NYT's own China-military-purge story carried more novel information for the day.
- **NBC:** "Texas Poll: James Talarico Holds a Narrow Advantage for Senate While Greg Abbott Leads for Governor" — deprioritized under the standard's guidance to avoid leading with daily horse-race polling.
- **AP:** "Trump's 'Grand Conspiracy' Probe Presses On With Subpoenas After the Lead Prosecutor's Exit" — a durable legal story that narrowly lost out to the day's stronger international and regulatory developments.

**Same-underlying-development check:** No outlet's final five contained three or more selections tied to one underlying event. The Russia-Ukraine drone barrage appears once in the AP list (Zaporizhzhia angle) and once in the NYT-adjacent pool (not selected, to avoid redundancy with AP's coverage); the White House press-ban lawsuit appears once per outlet, each drawing on that outlet's own distinct reporting rather than a shared wire feed.
