## WSJ

1. [North Koreans Use Stolen IDs, AI to Land U.S. Jobs—and Funnel Millions to Kim's Regime](https://www.wsj.com/business/north-koreans-use-stolen-ids-ai-to-land-u-s-jobsand-funnel-millions-to-kims-regime-1385adf7)
2. [War Is Squeezing Another Global Chokepoint: The Black Sea](https://www.wsj.com/world/europe/war-is-squeezing-another-global-chokepoint-the-black-sea-ce08b232)
3. [Taiwan Weaponizes Coast Guard to Prepare for Battle With China](https://www.wsj.com/world/asia/taiwan-weaponizes-coast-guard-to-prepare-for-battle-with-china-e7235080)
4. [Putin's Visit to Disputed Island Adds to Pressure on Japan](https://www.wsj.com/world/asia/russia-japan-putin-kuril-islands-c59e7f3b)
5. [DeepMind's Hassabis Pitched AI-Oversight Body Before Shake-Up](https://www.wsj.com/tech/ai/deepminds-hassabis-pitched-ai-oversight-body-before-shake-up-e25b3f71)

## NYT

1. [Trump Administration Lets Parts of the National Firearms Act Lapse](https://www.nytimes.com/2026/08/13/us/politics/national-firearms-act-gun-control-doj.html)
2. [Treasury Scales Back Scrutiny of U.S. Shell Companies](https://www.nytimes.com/2026/08/12/us/politics/treasury-scrutiny-shell-companies.html)
3. [Russian Blockade of Major Ukrainian Ports Threatens Global Grain Supplies](https://www.nytimes.com/2026/08/13/world/europe/russia-ukraine-ports-odesa-cargo-ship-attacks.html)
4. [America Wants to Make Its Own Humanoid Robots. That Won't Be Easy.](https://www.nytimes.com/2026/08/13/business/humanoid-robot-us-china.html)
5. [Trump Wants the M.M.R. Vaccine Split Into Three Separate Shots. Doctors Say It's a Bad Idea.](https://www.nytimes.com/2026/08/12/health/mmr-vaccine-combination-separate.html)

## NBC

1. [Surveillance company Flock moves to increase oversight after police misuse](https://www.nbcnews.com/tech/security/flock-safety-police-abuse-oversight-data-retention-rcna592217)
2. [White House press secretary Karoline Leavitt to step down](https://www.nbcnews.com/politics/white-house/press-secretary-karoline-leavitt-step-down-end-of-august-rcna592223)
3. [Los Angeles Lakers sold to Bob Iger, Josh Kushner for $12 billion](https://www.nbcnews.com/sports/nba/los-angeles-lakers-sold-bob-iger-josh-kushner-12-billion-rcna592121)
4. [Extremism expert charged in case on Southern Poverty Law Center informants](https://www.nbcnews.com/politics/justice-department/extremism-expert-charged-case-targeting-southern-poverty-law-centers-u-rcna592198)
5. [3 takeaways from David Crowley's comeback: From the Politics Desk](https://www.nbcnews.com/politics/politics-news/3-takeaways-david-crowleys-comeback-politics-desk-rcna592208)

## AP

1. [US military to complete Iraq withdrawal by September, ending 23-year presence](https://apnews.com/article/iraq-us-withdrawal-7d050ff17a0c52298207bd9e60851fcd)
2. [Lawsuit seeks to ban Trump Media from charging for early access to president's posts on US policy](https://apnews.com/article/trump-media-lawsuit-truth-social-access-wall-street-traders-7f057fd1dba31dd4e357c8bf635ee009)
3. [Pentagon review says US strikes killed 153 civilians in Yemen last year](https://apnews.com/article/yemen-civilians-killed-pentagon-houthis-c5e2190729a93aa54f6a4d5d1232fce3)
4. [Vaccine-makers unlikely to split MMR shots despite Trump's push](https://apnews.com/article/vaccines-trump-mmr-drugmakers-5a1d91e149feab99b18dd916412523ee)
5. [Brazil's Supreme Court backs state laws denying tax incentives for Amazon soy moratorium](https://apnews.com/article/brazil-amazon-rainforest-soy-moratorium-deforestation-4145415431832ff862b40e2ed1ab627e)

## Note

**Selection window:** 2026-08-12 13:38 UTC to 2026-08-13 13:38 UTC (24 hours), filtered by original publication timestamp in each feed, not update or retrieval time.

**Access notes:**
- All listed WSJ, NYT, NBC feeds were fetched directly and parsed successfully.
- AP does not publish a general RSS feed. Candidates were sourced via Google News search (`site:apnews.com when:1d`), but Google's News redirect links no longer resolve to canonical URLs via direct HTTP fetch (Google changed its redirect format to an opaque token that requires client-side JS to resolve, and this also defeated automated web-fetch tooling). Canonical apnews.com URLs were instead independently verified by cross-referencing each candidate headline against AP's own site search (apnews.com/search) and confirming matching titles and `datePublished` timestamps within the selection window before inclusion.
- One AP candidate (a WHO/Congo Ebola outbreak severity story, headlined "surpasses the deadliest one in history," published ~19:49 UTC Aug 12) could not be matched to a canonical apnews.com URL — it wasn't yet indexed in AP's own site search — so it was excluded per the no-unresolved-URL rule despite scoring well on significance.
- WSJ and NYT article pages return 401/403 to non-browser HTTP requests (bot/paywall protection) even though their RSS feeds are open; all WSJ/NYT links above are used verbatim from each outlet's own RSS `<link>` field (WSJ links had only tracking query parameters stripped), so they are canonical regardless of that block.

**Selection rationale:** Prioritized developments with durable, 30-day-relevant consequences — war/shipping chokepoints (Black Sea grain routes, Taiwan-China tension, Kuril Islands dispute), regulatory rollbacks (Treasury shell-company enforcement, National Firearms Act), a 23-year U.S. military withdrawal from Iraq, public-health policy fights (MMR vaccine splitting), and institutional accountability stories (Pentagon Yemen civilian-casualties review, Flock surveillance oversight, SPLC prosecution). Deprioritized: the European solar eclipse (heavy volume across NYT/NBC but a one-day spectacle without forward consequence), lottery jackpots, celebrity/entertainment items, and routine monthly economic releases (CPI/PPI/jobless claims) that were already priced into markets and didn't change the outlook.

**Strongest excluded candidates:**
- **WSJ:** White House Press Secretary Karoline Leavitt's resignation — real news, but a personnel change without policy consequence; covered instead by NBC.
- **NYT:** Homeland Security's $464 million purchase of jets that then sat idle — strong accountability story, but narrower and less structurally significant than the NFA lapse and shell-company items chosen.
- **NBC:** Apache helicopter crash near Fort Hood killing two soldiers — a real tragedy, but an isolated incident rather than a development with forward consequences (aviation-safety fallout was still developing at deadline).
- **AP:** Congo Ebola outbreak WHO severity warning — excluded solely because a canonical URL could not be verified in time (see access notes), not because of insignificance; also, US ambassador's condemnation of the West Bank settler siege was a strong alternate pick, but was judged slightly less consequential than the Pentagon Yemen civilian-casualties review.

**Redundancy check:** No outlet had three or more selections tied to the same underlying development. WSJ's Black Sea/grain item and NYT's Ukrainian ports item both stem from the same Russia-Ukraine maritime conflict but were selected independently for their respective outlets and are the only such item in each outlet's list, so no consolidation was needed.
