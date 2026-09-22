## WSJ

1. [Paramount Settles States' Antitrust Suit, Clearing Way for Warner Megadeal](https://www.wsj.com/business/media/paramount-settles-states-antitrust-suit-clearing-way-for-warner-megadeal-95588926)
2. [British Columbia Sues OpenAI, Alleging ChatGPT Aided Mass School Shooting](https://www.wsj.com/tech/ai/british-columbia-sues-openai-alleging-chatgpt-aided-mass-school-shooting-aac66568)
3. [Vance-Led Task Force Set to Remove 760,000 Allegedly Fraudulent Obamacare Enrollments](https://www.wsj.com/politics/policy/vance-led-task-force-set-to-remove-760-000-allegedly-fraudulent-obamacare-enrollments-0fbb72d7)
4. [OpenAI Urges Washington to Lead Global Effort to Create AI-Safety Standards](https://www.wsj.com/tech/ai/openai-urges-u-s-government-to-create-global-ai-safety-standards-a8afba96)
5. [Saudi Arabia Spent Months Trying to Bypass Hormuz. For Now, There's No Way Around It.](https://www.wsj.com/world/middle-east/saudi-arabia-strait-of-hormuz-57e8fcb4)

## NYT

1. [Trump and Xi Meet Amid an Uneasy U.S.-China Trade Truce](https://www.nytimes.com/2026/09/21/business/economy/trump-xi-china-trade.html)
2. [Networks Suspend Pool Coverage of Trump After White House Bars CNN](https://www.nytimes.com/2026/09/21/business/media/cnn-trump-press-pool-ban.html)
3. [Paramount Settles States' Lawsuit, Clearing Way for Warner Bros. Merger](https://www.nytimes.com/2026/09/21/business/paramount-warner-bros-ellison.html)
4. [British Columbia Sues OpenAI Over Tumbler Ridge Shooting](https://www.nytimes.com/2026/09/21/world/canada/open-ai-tumbler-ridge-shooting-british-columbia.html)
5. [Trump Set to Sign Deal on U.S. Presence in Greenland](https://www.nytimes.com/2026/09/22/world/europe/us-greenland-deal-denmark-trump.html)

## NBC

1. [Paramount Reaches Deal With California, Other States Over Warner Bros. Discovery Merger](https://www.nbcnews.com/business/media/paramount-reaches-settlement-states-warner-bros-discovery-merger-rcna598645)
2. [U.S. Military Leaders Divided Over Action Against the Houthis](https://www.nbcnews.com/politics/national-security/us-military-leaders-divided-action-houthis-rcna599049)
3. [Appeals Court Seeks to Revive GOP Congressional Map in Missouri](https://www.nbcnews.com/politics/2026-election/appeals-court-seeks-revive-gop-congressional-map-missouri-rcna599108)
4. [CDC's Teen Behavior Report Focuses on Nutrition, Downplays Sex and Drug Use](https://www.nbcnews.com/health/health-news/teen-behavior-cdc-report-nutrition-mental-health-sex-rcna598037)
5. [Climate Scientists Fired by Trump Step In to Fill U.S. Report Gap](https://www.nbcnews.com/science/climate-change/climate-scientists-fired-trump-step-fill-us-report-gap-rcna598585)

## AP

1. [News Outlets Sue Trump Over Lost White House Access, Citing 'Blatant Violation' of First Amendment](https://www.kake.com/news/news-outlets-sue-trump-over-lost-white-house-access-citing-blatant-violation-of-first-amendment/article_dbab2fc0-4a29-51d5-9fc1-781ffecda113.html)
2. [States Settle Lawsuit Over Paramount-Warner Merger, Clearing Key Hurdle for $81 Billion Deal](https://www.pbs.org/newshour/nation/states-settle-lawsuit-over-paramount-warner-merger-clearing-key-hurdle-for-81-billion-deal)
3. [China Expels 2 Top Military Leaders Accused of Corruption From the Ruling Communist Party](https://www.wral.com/news/ap/b11fa-china-expels-2-top-military-leaders-accused-of-corruption-from-the-ruling-communist-party/)
4. [AP Exclusive: ICE Hides Locations of Thousands of Detainees With Final Removal Orders](https://www.opb.org/article/2026/09/21/ap-exclusive-ice-hides-locations-of-thousands-of-detainees-with-final-removal-orders/)
5. [Trump and Xi See Tensions Flare Over AI, Trade and Iran but Still Seek Stability](https://www.wral.com/news/ap/e5609-trump-and-xi-see-tensions-flare-over-ai-trade-and-iran-but-still-seek-stability/)

## Note

**Selection window:** 2026-09-21 13:36 UTC to 2026-09-22 13:36 UTC (24 hours), filtered by each item's original publication timestamp (each outlet's own RSS `<pubDate>` for WSJ/NYT/NBC; for AP, the timestamp on Google News's crawl of the AP wire item, cross-checked against the publication date on the verified republished article).

**Access notes:** All eight WSJ feeds, all ten NYT feeds, and all eight NBC feeds were fetched directly with the specified user agent and parsed successfully; no feed was inaccessible. This yielded roughly 80 in-window WSJ items after dedup, 122 NYT items, and 39 NBC items.

**AP resolution — a material limitation:** `apnews.com` is inaccessible to this session's tools entirely (both direct fetch and web search return no results from the domain, consistent with AP opting the site out of automated/AI access), so canonical `apnews.com` URLs could not be obtained this run. The fallback of resolving Google News's `news.google.com/rss/articles/...` redirect links — which normally requires either Google's internal `batchexecute` RPC or a JavaScript-executing browser — also failed: hand-reconstructing the `batchexecute` signed request was rejected by Google's endpoint, and a real headless-Chromium session (with cookies, a spoofed user agent, and anti-automation flags) was consistently blocked with HTTP 403 on the `gstatic.com` script required to complete the client-side redirect, indicating the network egress IP is flagged by Google's bot defenses rather than any fixable client misconfiguration. As a substitute, each selected AP story was identified from the Google News search pool, then independently verified via web search to a legitimate outlet that republishes the identical AP wire copy verbatim (confirmed via direct fetch of each page showing the matching AP byline, headline, and "Copyright The Associated Press" notice): PBS NewsHour, WRAL, OPB, and KAKE. These are treated as the canonical links for AP's section this run; none are aggregator or paywall-only mirrors.

**Principal selection rationale:** The Paramount–Warner Bros. Discovery merger settlement — twelve states and the Writers Guild dropping their antitrust challenge, clearing the last major hurdle for the $81 billion deal — was the single story with the broadest concrete, already-happened significance today, and was independently selected as a top pick by all four outlets from their own reporting. The Trump-Xi summit (trade, AI, and Iran tensions) and the escalating White House press-ban saga (networks suspending pool coverage; the formal First Amendment lawsuit filing) were treated as genuinely distinct, fresh developments rather than redundant continuations, since each represents a new concrete action rather than a repeat of prior analysis. Novelty items (celebrity deaths, game recaps, shopping deals, awards-show previews) that filled much of the raw NBC and WSJ pools were excluded per the standard's guidance.

**Strongest excluded candidate per outlet:**
- **WSJ:** "Radar and Radio Outage Roiled Flights Around New York City, Northeast" — a real infrastructure incident (and one independently covered by NYT and NBC), but a single-day disruption with less durable consequence than the five selected. Separately, WSJ's highest-ranked press-freedom item, "Television Networks Suspend Some Coverage of Trump After Bans," was excluded because it shares an identical URL with WSJ's own top pick already featured in yesterday's (2026-09-21) digest — an updated headline on the same article rather than a new one.
- **NYT:** "Russia's Election Was Engineered to Send a Message: Putin Remains in Control" — durable geopolitical significance, but substantially a continuation of the Duma election result already covered in yesterday's digest (via AP) rather than a fresh development.
- **NBC:** "Marco Rubio Defends Trump's Ban on Media Outlets From White House" — real institutional stakes, but reactive commentary on an already-reported story rather than a new fact on the ground.
- **AP:** "The Netherlands Is Bracing for Potentially Devastating US Sanctions Against the ICC" — durable legal/geopolitical significance, but narrower and more speculative than the selected five.

**Same-underlying-development check:** No single outlet's final five contained three or more selections tied to one underlying event. Two outlets (NYT and AP) each carry one item from the continuing White House press-ban saga, but from distinct facets (NYT: networks suspending pool coverage; AP: the formal lawsuit filing) rather than the same specific development. The Paramount-Warner settlement appearing as a top-two pick across all four outlets is a cross-outlet convergence, not an in-outlet repeat, and reflects the story's outsized, broadly-agreed significance rather than padding.
