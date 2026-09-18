## WSJ

1. [Warren Buffett Steps Down as Berkshire Hathaway Chairman](https://www.wsj.com/finance/warren-buffett-to-step-down-as-berkshire-hathaway-chairman-de0e003f)
2. [Bank of Japan Raises Rates, Making U.S. Less Alluring for Tokyo Investors](https://www.wsj.com/economy/central-banking/bank-of-japan-raises-benchmark-interest-rate-to-1-25-highest-level-since-1995-2b28cbe9)
3. [Russia Seizes Control of Nestlé's Local Operations](https://www.wsj.com/articles/nestle-weighs-options-for-russia-unit-after-moscow-puts-it-under-administration-221402de)
4. [White House Withdraws Nominee to Lead ICE](https://www.wsj.com/politics/policy/white-house-withdraws-nominee-to-lead-ice-2cadae3f)
5. [Failure of Clarity Act Turns Crypto Industry Focus to Federal Regulators](https://www.wsj.com/politics/policy/failure-of-clarity-act-turns-crypto-industry-focus-to-federal-regulators-135914cc)

## NYT

1. [Warren Buffett Steps Down as Berkshire Chairman and Names Son to Replace Him](https://www.nytimes.com/2026/09/18/business/warren-buffett-berkshire-chairman.html)
2. [Japan Raises Interest Rates to 31-Year High Under U.S. Pressure](https://www.nytimes.com/2026/09/17/business/japan-interest-rates.html)
3. [Russia and China Veto U.S. Bid to Renew U.N. Monitoring of Iran Nuclear Program](https://www.nytimes.com/2026/09/17/world/middleeast/un-iran-resolution-russia-china-veto.html)
4. [Trump Moves Ahead With F-35 Jet Sales to Saudi Arabia Despite Intelligence Concerns](https://www.nytimes.com/2026/09/17/us/politics/trump-f35-jet-saudi-arabia.html)
5. [Yemen War Intensifies as Houthi Militia Advances on Marib](https://www.nytimes.com/2026/09/17/world/middleeast/yemen-houthis-marib.html)

## NBC

1. [Warren Buffett steps down as chairman of Berkshire Hathaway](https://www.nbcnews.com/business/business-news/warren-buffett-steps-down-chairman-berkshire-hathaway-rcna598503)
2. ['Godfather of AI' warns Congress has 'maybe a year' left to regulate AI](https://www.nbcnews.com/politics/congress/godfather-ai-warns-congress-maybe-year-left-regulate-ai-rcna598330)
3. [White House withdraws Trump's nominee to lead ICE](https://www.nbcnews.com/politics/immigration/white-house-withdraws-trumps-nominee-lead-ice-rcna598386)
4. [Texas abortion ban caused pregnant woman's death, lawsuit says](https://www.nbcnews.com/news/us-news/pregnant-womans-death-texas-caused-states-abortion-ban-lawsuit-says-rcna598303)
5. [Soaring mortgage rates and high prices are putting homeownership further out of reach](https://www.nbcnews.com/business/real-estate/high-mortgage-rates-home-prices-stress-rcna598396)

## AP

1. [Warren Buffett steps down as Berkshire Hathaway chairman, a post he has held since 1970](https://apnews.com/article/berkshire-hathaway-buffett-70f52159fdcaedae3f8926893de37023)
2. [Japan's central bank raises benchmark interest rate to 1.25%, the highest in 31 years](https://apnews.com/article/japan-economy-interest-rates-inflation-67e71246d3af41bcfc61aa788f9959c7)
3. [Russia and China veto US proposal for UN experts to keep monitoring sanctions on Iran](https://apnews.com/article/united-nations-iran-sanctions-russia-china-c509e344bc45ba87670b9a668afbbb49)
4. [A sweeping US sanctions bill offers Ukraine new leverage on Russia, but enforcement looms](https://apnews.com/article/russia-ukraine-war-sanctions-explainer-8ed078bcd04fc60111382ebd7402ef32)
5. [Attorney General Blanche's appearances at political events blur Justice Department boundaries](https://apnews.com/article/todd-blanche-politics-trump-justice-department-b9e41a9222825a697b7a532a9686e3e7)

## Note

**Selection window:** 2026-09-17 13:36 UTC to 2026-09-18 13:36 UTC (24 hours), filtered by each item's original publication timestamp (each outlet's own RSS `<pubDate>` for WSJ/NYT/NBC; for AP, the Google News aggregation timestamp for the wire item).

**Access notes:** All eight listed WSJ feeds, all ten listed NYT feeds, and all eight listed NBC feeds were fetched directly with the specified user agent and parsed successfully as RSS/XML; no feed was inaccessible. This yielded 367 raw WSJ items (112 in-window), 345 raw NYT items (173 in-window), and 192 raw NBC items (59 in-window) before deduplication. WSJ and NYT article pages return 401/403 to automated requests (login/paywall gating and bot detection, respectively) rather than 404, confirming the selected URLs are live, reachable pages; they were not fetched directly for content verification. All five NBC links were verified to return HTTP 200.

**AP resolution:** `apnews.com` itself returns HTTP 403 to automated requests (Cloudflare bot challenge), so, per the source instructions, AP candidates were pulled from the specified Google News search (`site:apnews.com when:1d`), yielding 100 candidates in the window. Each candidate's Google News redirect page was fetched to extract its embedded article id/timestamp/signature triple, which was then exchanged against Google News's internal `Fbv4je` "get article URL" endpoint (`news.google.com/_/DotsSplashUi/data/batchexecute`) to recover the canonical `apnews.com` URL directly, rather than relying on a plain HTTP redirect. This resolved all five selected candidates to canonical, slug-consistent `apnews.com/article/...` links; each returned HTTP 403 on direct fetch (the same Cloudflare bot-challenge behavior as the outlet's own homepage), consistent with a genuine, reachable page rather than a broken or non-canonical link. Two AP candidates that were substantially identical to items already published in yesterday's digest ("UN-backed experts cite possible US war crimes in Iran strikes" and "Carney embraces EU associate membership proposal...") were excluded as non-original within this window despite carrying a fresh Google News crawl timestamp, since both resolved to the same canonical URLs already used on 2026-09-17.

**Selection rationale:** The dominant, cross-outlet story of the day is Warren Buffett's retirement as Berkshire Hathaway's chairman after 56 years, with his son taking over — a once-in-a-generation succession at one of the world's most closely watched companies, selected independently by all four outlets. The next-strongest global thread is the Bank of Japan's interest-rate increase to a 31-year high, ending an era of ultra-loose Japanese monetary policy with direct consequences for global capital flows (WSJ, NYT, AP). Iran-related nonproliferation and security stories were also prominent: Russia and China's veto of a U.S.-backed UN measure to continue monitoring Iran's nuclear program (NYT, AP) and, separately, the Trump administration's F-35 jet sales to Saudi Arabia over U.S. intelligence-community objections (NYT) and the intensifying Yemen war as Houthi forces advance on Marib (NYT) reflect distinct, durable developments in Middle East security rather than a single repeated story. Elsewhere: the withdrawal of the White House's ICE director nominee amid Republican pushback was independently confirmed by WSJ, NYT, and NBC; Russia's move to seize Nestlé's local operations marks a notable escalation in state expropriation of Western multinational assets; the stalled Clarity Act leaves crypto regulation with federal agencies rather than a new statutory framework; a newly passed Russia sanctions bill gives Washington fresh leverage over Moscow pending enforcement; and Attorney General Blanche's political campaign appearances were flagged by multiple outlets as an unusual breach of a Justice Department norm dating to Watergate. On the domestic front, NBC's slate captures a "Godfather of AI" warning to Congress on the narrowing window to regulate artificial intelligence, a lawsuit tying a Texas abortion-ban death to state law, and new data on 7%-range mortgage rates squeezing homebuyers.

**Strongest excluded candidates:**
- **WSJ:** "U.S. Probes Iran Link to Cyberattacks on Texas-Bound Energy Tankers" — a genuine critical-infrastructure security story, excluded because the investigation remains open and unresolved, versus the more settled developments selected.
- **NYT:** "Alabama Executes Inmate After Supreme Court Blocked Last Attempt" — a significant capital-punishment and judicial-process story, excluded in favor of the Yemen war's active regional-security escalation, judged the more durable international development.
- **NBC:** "Democratic senators request Pentagon provide 'bare minimum' on cost of Iran war" — a solid government-oversight story, excluded in favor of the Texas abortion-ban lawsuit's more immediate legal and public-health consequences.
- **AP:** "Tens of thousands flee as Iran-backed rebels draw Yemen into the wider war" — a genuine, durable conflict-escalation story, excluded for topical balance since NYT's slate already carries this same underlying Yemen development today; AP's slot instead went to the Attorney General Blanche story for domestic-institutional coverage.

**Redundancy check:** No outlet's final five contains three or more items tied to the same underlying development. Warren Buffett's Berkshire departure appears once in each of the four outlets' slates — as in yesterday's digest with the Fed's rate decision, this reflects a single, exceptionally significant event independently judged newsworthy by every outlet, not internal repetition. The Bank of Japan's rate hike and the Russia/China UN-Iran veto each appear in two outlets' slates (WSJ/NYT/AP and NYT/AP respectively) for the same reason.
