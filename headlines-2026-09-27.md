# Headlines — September 27, 2026

## WSJ

1. [The Supreme Court on Friday allowed the federal government to deploy its own immigration database to check voters' citizenship](https://www.wsj.com/politics/policy/how-the-trump-administrations-election-plan-is-falling-into-place-aa991667)
2. [OpenAI Agents Used Aggressive Techniques to Access U.N. Website](https://www.wsj.com/tech/ai/openai-agents-used-aggressive-techniques-to-access-u-n-website-522c70ff)
3. [North Korea Is Testing Swarm Attacks Mixing Drones and Missiles](https://www.wsj.com/world/north-korea-is-testing-swarm-attacks-mixing-drones-and-missiles-6f8a0a38)
4. [New Boeing 737 MAX Software Glitch Could Disrupt Navigation Feature](https://www.wsj.com/business/airlines/new-boeing-737-max-software-glitch-could-disrupt-navigation-feature-d537b8d8)
5. [A World War II-Era Feud Is Threatening a Pivotal Alliance for Ukraine](https://www.wsj.com/world/europe/a-world-war-ii-era-feud-is-threatening-a-pivotal-alliance-for-ukraine-e648a66e)

## NYT

1. [Iran Seeks U.S. Clarification After Trump Rejects Cease-Fire Proposal](https://www.nytimes.com/2026/09/27/world/middleeast/iran-trump-ceasefire-strait-of-hormuz.html)
2. [As A.I. Accelerates, Governments Are Increasingly Being Left Behind](https://www.nytimes.com/2026/09/27/technology/ai-government-regulation.html)
3. [Trump Administration Plans to Gut Clean Car Rules](https://www.nytimes.com/2026/09/26/climate/trump-fuel-economy-car-rules.html)
4. [At Summit, Xi Sought to Tilt Trump's Stance on America's Place in Asia](https://www.nytimes.com/2026/09/26/world/asia/summit-xi-trump-taiwan-japan.html)
5. [TikTok to Pay Alabama $100 Million to Settle Social Media Addiction Claims](https://www.nytimes.com/2026/09/25/technology/tiktok-alabama-child-safety-settlement.html)

## NBC

1. [Bill Gates says getting countries to agree on AI regulations will be harder than Cold War-era nuclear negotiations](https://www.nbcnews.com/news/us-news/bill-gates-global-artificial-intelligence-regulations-nuclear-rcna599646)
2. [Bomb squad searching vans near U.S. air base in Britain after five men arrested](https://www.nbcnews.com/world/united-kingdom/men-arrested-suspicion-explosives-offences-us-air-base-britain-rcna600052)
3. [Special report: One person dead as dangerous nor'easter slams East Coast](https://www.nbcnews.com/video/one-person-dead-as-dangerous-nor-easter-slams-east-coast-270606405817)
4. [White House blocks CNN from covering Trump's Tennessee trip](https://www.nbcnews.com/politics/white-house/white-house-blocks-cnn-covering-trumps-tennessee-trip-rcna599944)
5. [Anger grows across Spain after elderly woman evicted from her home of 70 years](https://www.nbcnews.com/world/spain/anger-grows-spain-elderly-woman-evicted-home-70-years-rcna599808)

## AP

1. [China and US agree to establish AI safety channel and continue trade and military talks](https://www.whec.com/ap-top-news/china-and-us-agree-to-establish-ai-safety-channel-and-continue-trade-and-military-talks/)
2. [Anthropic and OpenAI sound the alarm on AI safety — and seek to shape how it's controlled](https://www.wral.com/news/ap/9a057-anthropic-and-openai-sound-the-alarm-on-ai-safety-and-seek-to-shape-how-its-controlled/)
3. [UK police evacuate homes near air base used by US and detain men on suspected explosives offensives](https://abcnews.com/International/wireStory/uk-police-evacuate-homes-air-base-us-detain-136793296)
4. [House Democrats plan vast oversight of Trump administration. Impeachment is an option](https://www.whec.com/ap-top-news/house-democrats-plan-vast-oversight-of-trump-administration-impeachment-is-an-option/)
5. [Trump rejects Iran's proposal to reopen the Strait of Hormuz and other Mideast news](https://www.whec.com/ap-top-news/ap-top-news-international/trump-rejects-irans-proposal-to-reopen-the-strait-of-hormuz-and-other-mideast-news/)

## Note

**Selection window:** 2026-09-26 13:36 UTC to 2026-09-27 13:36 UTC (24 hours prior to collection), filtered on each item's original `pubDate`, not retrieval or update time.

**Feed/domain access limitations:**
- All specified WSJ (8 feeds), NYT (10 feeds), and NBC (8 feeds) RSS feeds were fetched directly and successfully.
- AP does not publish a general RSS feed. Per the sourcing instructions, candidates were drawn from a Google News search (`site:apnews.com when:1d`), which returned 100 results, of which 89 were substantive (non-topic-page) items after deduplication.
- **apnews.com itself could not be fetched directly** — the domain returns a Cloudflare "Just a moment…" bot-verification challenge (HTTP 403) to direct requests, and Anthropic's own web-search tooling is also blocked from indexing apnews.com by name. Additionally, Google News' article-redirect links now resolve client-side via an obfuscated `batchexecute` call rather than a plain HTTP redirect, so the raw `news.google.com` links could not be mechanically decoded to bare `apnews.com` URLs.
- To meet the "no unresolved/guessed URLs" requirement, each selected AP story was cross-verified against its Google News RSS entry (for original headline and publish time) and then linked to a same-text wire-service syndication partner that mirrors the AP story verbatim under an AP byline (WHEC.com, WRAL.com, and ABC News' `wireStory` mirror) — all confirmed reachable (HTTP 200) with titles matching the original AP headline exactly.

**Selection rationale:** Prioritized developments with durable, 30-day-plus consequences — active war/ceasefire diplomacy (Iran/Strait of Hormuz), AI governance and regulation (U.S.-China AI safety channel, industry self-regulation push, government/AI accountability), institutional and legal consequence (SCOTUS election ruling, House oversight/impeachment planning, TikTok's $100M settlement), safety/infrastructure (Boeing 737 MAX glitch, UK explosives incident, nor'easter damage), and policy rollback (clean car rules). Deprioritized crime-of-the-day, celebrity/lifestyle, routine sports, and partisan-theater coverage even where such items were prominent in the raw feeds.

**Strongest excluded candidates:**
- **WSJ:** "A Storied Indian Business Empire Is Being Torn Apart by Infighting" — a genuine ownership/succession story, but narrower in durable consequence than the SCOTUS ruling, the Boeing safety issue, and North Korea's weapons testing.
- **NYT:** "27 killed in mass shootings in South Africa overnight" — high casualty count and real news weight, but a fast-developing casualty story without the multi-week institutional consequence of the diplomacy, regulation, and policy stories selected.
- **NBC:** "How an American teacher's $5,000 donation helped turn a Chinese desert into a lush forest" — a notable human-interest/environmental story, but personal/local in scale next to the security incident, storm damage, press-access dispute, and housing-crisis protest chosen.
- **AP:** "Death toll in Indonesia's capsized Java Sea ferry rises to 64 as 71 people remain missing" — a major disaster by casualty count, but a discrete, geographically contained tragedy without the broader ongoing institutional consequences of the AI-governance, oversight, and Iran-diplomacy stories chosen.

**Same-underlying-development check:** No outlet's five selections included three or more items about the same underlying development. (Two WSJ, two NYT, and two AP items touch related-but-distinct AI-governance and Iran/Hormuz threads respectively, each representing a genuinely separate development — e.g., the U.S.-China AI safety channel vs. industry self-regulation lobbying; SCOTUS's own ruling text is standalone.)
