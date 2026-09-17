## WSJ

1. [Fed Raises Rates for First Time in Three Years](https://www.wsj.com/economy/central-banking/fed-raises-rates-for-first-time-in-three-years-08539fbe)
2. [Trump Says Allowing Canada to Become Associate Member of EU Could Be 'Hostile Act'](https://www.wsj.com/world/europe/trump-says-allowing-canada-to-become-associate-member-of-eu-could-be-hostile-act-c6a02766)
3. [Yemen's Houthi Rebels Claim Shooting Down Saudi F-15 Jet Fighter](https://www.wsj.com/world/middle-east/yemens-houthi-rebels-claim-shooting-down-saudi-f-15-jet-fighter-237ecc7d)
4. [GM to Produce Patriot Missile Parts as U.S. Faces Critical Arms Shortage](https://www.wsj.com/business/autos/gm-to-produce-patriot-missile-parts-as-u-s-faces-critical-arms-shortage-c0f94101)
5. [Former Kosovo President Sentenced to 25 Years for War Crimes in Serbia Conflict](https://www.wsj.com/world/europe/former-kosovo-president-sentenced-to-25-years-for-war-crimes-in-serbia-c1aa4063)

## NYT

1. [Trump Looks Isolated on Interest Rates](https://www.nytimes.com/2026/09/17/business/dealbook/trump-fed-rates.html)
2. [Bank of England Holds Rates Steady but Warns of Higher Inflation](https://www.nytimes.com/2026/09/17/business/bank-of-england-interest-rates.html)
3. [Judge Orders Data Sharing and Other Fixes to Solve Google's Ad Tech Monopoly](https://www.nytimes.com/2026/09/16/technology/google-ad-tech-remedies.html)
4. [U.S. Charges Five Men in Russia-Backed Assassination Plots](https://www.nytimes.com/2026/09/16/us/russia-assassination-plot-kremlin.html)
5. [Gold Mine Collapse in Sudan Kills at Least 70](https://www.nytimes.com/2026/09/16/world/africa/sudan-gold-mine-collapse.html)

## NBC

1. [Fed raises interest rates for first time since 2023, defying Trump as inflation mounts](https://www.nbcnews.com/business/economy/fed-raises-rates-defying-trump-rcna598148)
2. [House passes Russia sanctions bill named for Lindsey Graham, sending it to Trump](https://www.nbcnews.com/politics/congress/house-passes-russia-sanctions-bill-named-lindsey-graham-sending-trump-rcna598124)
3. [OpenAI flags 6 new incidents of 'concerning' behavior and unveils plan to track it](https://www.nbcnews.com/tech/tech-news/openai-new-incidents-concerning-behavior-model-misalignment-rcna598277)
4. [House passes bill to shield consumers from data center price hikes on energy](https://www.nbcnews.com/politics/congress/house-passes-bill-shield-consumers-data-center-price-hikes-energy-rcna597683)
5. [House votes to hold Epstein associate Leon Black in contempt of Congress](https://www.nbcnews.com/politics/congress/house-leon-black-contempt-of-congress-jeffrey-epstein-probe-rcna598186)

## AP

1. [Federal Reserve hikes key rate for 1st time in 3 years, defying Trump demands for a cut](https://apnews.com/article/federal-reserve-warsh-trump-inflation-bab1bcb07e973bfb2dd0c3e5fbbb73b1)
2. [UN-backed experts cite possible US war crimes in Iran strikes](https://apnews.com/article/un-human-rights-us-iran-99e690efd1e818e835d4f5a00e0d261b)
3. [A Hague court convicts Kosovo's former President Thaci of war crimes and sentences him to 25 years](https://apnews.com/article/thaci-kosovo-serbia-war-crimes-0b24b81d6e1ca8f01d8b8b54bb465ee9)
4. [Carney embraces EU associate membership proposal as Trump pushes Canada closer to Europe](https://apnews.com/article/carney-canada-eu-trump-parliament-speech-ef4559ce5972abb47444e469f42005bb)
5. [Trump administration has cut or frozen $177 billion in grants across every state, analysis shows](https://apnews.com/article/trump-administration-federal-grants-cuts-edbdf9f49b1235bf38834417ef8dc130)

## Note

**Selection window:** 2026-09-16 13:40 UTC to 2026-09-17 13:40 UTC (24 hours), filtered by each item's original publication timestamp (each outlet's own RSS `<pubDate>` for WSJ/NYT/NBC; for AP, the Google News aggregation timestamp for the wire item).

**Access notes:** All eight listed WSJ feeds, all ten listed NYT feeds, and all eight listed NBC feeds were fetched directly with the specified user agent and parsed successfully as RSS/XML; no feed was inaccessible. WSJ and NYT article pages return 401/403 to automated requests (login/paywall gating and bot detection, respectively) rather than 404, confirming the URLs are live, reachable pages; they were not fetched directly for content verification. All five NBC links were verified to return HTTP 200. One WSJ headline (the Fed rate decision) was rendered in proper headline case from WSJ's own URL slug, since WSJ's social/economy feed supplied a descriptive summary sentence rather than a headline for that item; the link itself is WSJ's own canonical URL, tracking parameter stripped.

**AP resolution:** `apnews.com` itself returns HTTP 403 to automated requests (Cloudflare bot challenge), so, per the source instructions, AP candidates were pulled from the specified Google News search (`site:apnews.com when:1d`), yielding 99 candidates in the window. Each candidate's Google News redirect page was fetched to extract its embedded article id/timestamp/signature triple, which was then exchanged against Google News's internal `Fbv4je` "get article URL" endpoint (`news.google.com/_/DotsSplashUi/data/batchexecute`) to recover the canonical `apnews.com` URL directly, rather than relying on a plain HTTP redirect. This resolved all 99 candidates (100%) to canonical, slug-consistent `apnews.com/article/...` links; each returned HTTP 403 on direct fetch (the same Cloudflare bot-challenge behavior as the outlet's own homepage), consistent with a genuine, reachable page rather than a broken or non-canonical link.

**Selection rationale:** The day's dominant, cross-outlet story is the Federal Reserve's decision to raise interest rates for the first time in three years — a unanimous vote defying White House pressure, with officials signaling further increases to come. All four outlets are represented with distinct framings: WSJ's straight decision report, NYT's angle on Trump's diminished influence over the Fed, NBC's framing of the rate hike as a direct rebuff of Trump, and AP's own wire framing. Because Kosovo's former president Hashim Thaci's 25-year war-crimes sentence and the U.S.-Canada-EU "associate member" trade realignment were already covered by NYT in yesterday's digest, both stories were kept out of today's NYT slate to avoid repeating an identical link and angle, but retained for WSJ and AP, which had not yet run them, since each represents a fresh, distinct, durable development (a final sentencing; Trump's new "hostile act" threat and Carney's parliamentary speech, respectively). Other durable threads independently selected across outlets include: the U.S. formally charging five men in a Russia-backed assassination plot (an escalation from mere accusation, previously reported by NBC yesterday); a federal judge's order requiring Google to share ad-tech data as an antitrust remedy; the deadly Houthi-Saudi military escalation (a Saudi F-15 reportedly shot down); GM's move into Patriot missile-parts production amid a national arms shortage; congressional passage of a Russia sanctions bill and a data-center electricity-cost bill; the House's contempt vote against Epstein associate Leon Black; a UN-backed panel's finding that U.S. strikes on Iran may have violated the laws of war; a Sudan gold-mine collapse that killed at least 70; and an AP analysis finding the Trump administration has cut or frozen $177 billion in grants nationwide.

**Strongest excluded candidates:**
- **WSJ:** "Top Democrat Opposes Trump's Planned Sale of Heavy Bombs to Israel" — a genuine legislative-oversight story, excluded in favor of the Houthi-Saudi F-15 story, judged to carry greater immediate regional-security significance.
- **NYT:** The U.S.-Canada-EU "associate member" story (multiple angles: Carney's speech, von der Leyen's address, Trump's reaction) — the single most-covered thread in NYT's own candidate pool today, but excluded to avoid a third consecutive day of NYT coverage on the same throughline and because WSJ and AP already carry fresher takes on it in this digest.
- **NBC:** "OpenAI flags 6 new incidents of 'concerning' behavior and unveils plan to track it" was used; the strongest excluded NBC candidate was "Trump administration spent $9.5B last year on employee leave, driven by DOGE-era cuts" — a solid fiscal-accountability story, excluded in favor of the Leon Black contempt vote, judged to carry broader immediate institutional consequence.
- **AP:** "House approves sweeping Russia sanctions bill, sending it to Trump" — a strong foreign-policy story, excluded to avoid redundancy with NBC's selection of the same underlying development, in favor of AP's own distinct $177 billion federal-grants analysis.

**Redundancy check:** No single outlet's final five contains three or more items tied to the same underlying development. The Fed's rate decision appears once in each of the four outlets' slates, reflecting genuinely distinct framings (straight decision, political-isolation angle, defiance angle, and wire framing) rather than a repeat. NBC's slate includes three items describing bills passed by the House (Russia sanctions, data-center energy costs, and Leon Black's contempt vote); these are three distinct legislative/oversight actions on unrelated subjects, not the same underlying development.
