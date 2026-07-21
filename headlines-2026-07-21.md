## WSJ

1. [DOJ Sought Phone Records Tied to Relatives of New York Times Reporters](https://www.wsj.com/politics/policy/doj-sought-phone-records-tied-to-relatives-of-new-york-times-reporters-53aa9321)
2. [Trump Imposes Additional 50% Tariffs on Certain Canadian Goods](https://www.wsj.com/economy/trade/trump-imposes-additional-50-tariffs-on-certain-canadian-goods-5ab06a45)
3. [Judge Temporarily Blocks Paramount-Warner Deal](https://www.wsj.com/business/media/judge-temporarily-blocks-paramount-warner-deal-a9c6af43)
4. [Israel Believes Iran Moved Nuclear Centrifuges Into Pickaxe Mountain](https://www.wsj.com/world/middle-east/israel-believes-iran-moved-nuclear-centrifuges-into-pickaxe-mountain-d29d21c0)
5. [BlackRock Leads $12 Billion Financing for New Meta Data Centers in Texas](https://www.wsj.com/business/deals/blackrock-leads-12-billion-financing-for-new-meta-data-centers-in-texas-e1c3d42c)

## NYT

1. [Daniel Ortega, President of Nicaragua, Says He Plans to Abolish Elections](https://www.nytimes.com/2026/07/20/world/americas/nicaragua-ortega-abolish-elections.html)
2. [Trump Administration Sought Phone Records of Times Journalists and Their Relatives](https://www.nytimes.com/2026/07/20/business/media/new-york-times-subpoenas-phone-records.html)
3. [Judge Temporarily Pauses Paramount-Warner Bros. Deal](https://www.nytimes.com/2026/07/20/business/media/paramount-warner-bros-deal.html)
4. [Houthis in Yemen Declare Red Sea Blockade on Saudi Arabia](https://www.nytimes.com/2026/07/20/world/middleeast/yemen-houthis-saudi-arabia-red-sea-blockade.html)
5. [Trump to Impose 50% Tariff on Many Canadian Goods](https://www.nytimes.com/2026/07/20/business/economy/trump-tariffs-canada.html)

## NBC

1. [Judge Pauses Paramount-Warner Merger](https://www.nbcnews.com/business/media/judge-puts-temporary-pause-paramount-warner-bros-merger-rcna587804)
2. [Trump Imposes 50% Tariffs on Dairy, Alcohol, and Cars From Canada](https://www.nbcnews.com/video/trump-imposes-50-tariffs-on-dairy-alcohol-and-cars-from-canada-266971717891)
3. [Trump Says New Air Force One Will Be Sent Away for Upgrades Amid Security Concerns](https://www.nbcnews.com/politics/politics-news/trump-air-force-one-maxed-out-security-qatar-gift-iran-threat-rcna588323)
4. [FDA Says It's Still Investigating Taylor Farms in Cyclosporiasis Outbreak](https://www.nbcnews.com/health/health-news/fda-still-investigating-taylor-farms-cyclosporiasis-outbreak-rcna588385)
5. [Trump Administration Says Iran War Reaching 'Time of Ambiguity' as Military Strikes Escalate](https://www.nbcnews.com/meet-the-press/video/trump-administration-says-iran-war-reaching-time-of-ambiguity-as-military-strikes-escalate-266969669682)

## AP

1. [Yemen's Iranian-Backed Houthis Say They Will Block Saudi Shipping at Red Sea Gateway](https://apnews.com/article/yemen-saudi-arabia-maritime-embargo-fd7c4a3911f7eee18251483fc8af768c)
2. [Judge Says Paramount and Warner Must Halt Merger for at Least Two Weeks, Granting States' Request](https://apnews.com/article/warner-bros-paramount-injunction-361fa669019e0053cf6d4513e6e275e3)
3. [Officials Sought Phone Records of NYT Journalists and Their Relatives in an Effort to Unmask Sources](https://apnews.com/article/new-york-times-justice-department-trump-88f5ceca88dcdd19779e6f61abedf337)
4. [Nicaragua's President Ortega Moves to Extend His 20-Year Rule and Says No Elections Anytime Soon](https://apnews.com/article/nicaragua-elections-ortega-rosario-murillo-sandinist-db7df72ee90928737a8f3fbad8b76dd3)
5. [French Lawmakers Race to Introduce an Under-15 Social Media Ban Before the New School Year](https://apnews.com/article/france-social-media-ban-b559fecdb7193235e8f75d7d69578830)

## Note

Selection window: 2026-07-20 05:26 UTC through 2026-07-21 05:26 UTC. WSJ was fetched via its public Dow Jones RSS feeds (World News, US Business, WSJD/Tech, US News, Politics, Economy, Arts & Culture, Health) with a browser-style User-Agent. NYT was fetched via its public section RSS feeds (HomePage, World, US, Politics, Business, Media & Advertising, Technology, Science, Health, Arts). NBC's general public feed skewed heavily toward shopping/lifestyle video content, so, as on prior days, section feeds (world, politics, business, health, science, us-news, pop-culture) were also pulled to surface enough hard news within the window; two of NBC's five links are consequently to NBC/MSNBC video pages rather than text articles, since no text-article equivalent existed in NBC's own feeds at fetch time for those specific updates. WSJ and NYT article pages return bot-protection HTTP status codes (401/403) to automated requests without a browser session, so most of those links could not be live-verified by fetching the article page directly; they are the exact, unmodified `<link>` values published in each outlet's own official RSS feed, consistent with prior days' methodology.

AP does not publish a public RSS feed, so candidate stories were located via Google News's site-restricted search (`site:apnews.com when:1d`). As on prior days, the `news.google.com` redirect links in that feed do not resolve via a simple HTTP redirect (Google now serves an opaque, non-decodable article token rather than an embedded URL), so each candidate headline was instead cross-referenced against apnews.com's own homepage and topic-hub/search pages to find the matching canonical `apnews.com/article/...` URL, which was then fetched directly and confirmed live via its `og:title` and `datePublished` metadata to verify both exact headline text and that it fell inside the 24-hour window. One candidate — an analysis piece on the Strait of Hormuz standoff surfaced only via Google News — could not be matched to a canonical AP URL before publication time (AP's own daily "Iran-US war" rolling article for July 21 had not yet been published as of the fetch) and was dropped in favor of a fully verified alternative.

Selection prioritized developments with institutional and legal consequence over the ongoing but largely incremental U.S.-Iran war reporting: a federal judge's order temporarily halting the $81 billion Paramount-Warner Bros. Discovery merger (recurring independently across all four outlets), the Trump administration's subpoenas for phone records of New York Times journalists and their relatives in a source-unmasking effort (also cross-outlet), and Nicaragua's Daniel Ortega formally moving to cancel elections and extend two decades of one-party rule. The Iran war was represented through its most durable current threads rather than day-to-day casualty updates: Israel's assessment that Iran relocated nuclear centrifuges (proliferation risk) and the Houthis' new Red Sea blockade against Saudi Arabia (regional spillover and shipping risk). Trump's additional 50% tariffs on Canadian goods and BlackRock's $12 billion Meta data-center financing rounded out the durable economic and technology-infrastructure angles. Excluded across all outlets were the World Cup victory parade and related celebration/fashion coverage, the Tate brothers' extradition fight, the Lindsay Clancy murder trial, the Ohio river drownings, the Guyana ferry sinking, and other novelty-, tragedy-of-the-day-, or celebrity-driven items whose significance does not extend much past the news cycle.

Strongest excluded candidates: **WSJ** — Lockheed Martin's plan for a bargain-rate Patriot missile to replenish stockpiles (strong defense-industrial-base story, but narrower in institutional stakes than the five selected). **NYT** — "Pentagon Withheld Dozens of U.S. Military Injuries in Iran War" (a real accountability story, but the war's durable angle was already covered via the Houthi blockade, and this outlet's five leaned toward broader institutional/governance breadth). **NBC** — Sen. Darline Graham's announcement that she'll run for a full Senate term (notable, but more campaign-horse-race than institutional consequence next to the Air Force One security story). **AP** — Trump's Canada tariffs (a real story, but already well-represented elsewhere in this digest, and AP's five leaned toward stories not duplicated across outlets).

Three outlets (WSJ, NYT, AP) each selected a story about the Paramount-Warner merger block and a story about the DOJ/NYT phone-records subpoena; within each outlet these represent only one selection apiece (no outlet has three or more selections tied to a single underlying development), so no redundancy adjustment was needed.
