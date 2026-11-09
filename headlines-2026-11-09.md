## WSJ

1. [Nvidia CEO Discloses Affair, Board Launches Probe Over Chinese Spy Fears](https://www.wsj.com/articles/nvidia-ceo-discloses-affair-board-launches-probe-over-chinese-spy-fears-c5d08af5)
2. [Oil Slides More Than 3% as Trump Downplays Prospect of New Iran Strikes](https://www.wsj.com/finance/commodities-futures/oil-prices-fall-staying-below-100-as-trump-plays-down-new-iran-strikes-27dc3911)
3. [NHTSA Opens Probe Into 1.2 Million Ford Vehicles Over Burn Risk from Airbag](https://www.wsj.com/business/autos/nhtsa-opens-probe-into-1-2-million-ford-vehicles-over-burn-risk-from-airbag-5610cb6c)
4. [UniCredit Signals It Is Ready to Bring Forward Merger With Commerzbank](https://www.wsj.com/business/earnings/unicredit-raises-profit-guidance-as-control-of-commerzbank-nears-ce8ccdc8)
5. [Japan Spent Record $50 Billion in Single Day to Bolster Yen](https://www.wsj.com/economy/central-banking/japan-spent-record-50-billion-in-single-day-to-bolster-yen-2bdeebd9)

## NYT

1. [Nvidia Opens Investigation Into Jensen Huang's Relationship With Chinese Spy](https://www.nytimes.com/2026/11/08/technology/nvidia-investigation-jensen-huang-china.html)
2. [Ukraine Peace Talks Resume This Week in Abu Dhabi](https://www.nytimes.com/2026/11/09/world/europe/ukraine-russia-peace-talks.html)
3. [Congress Returns to a Reordered Washington With a Hazy Agenda](https://www.nytimes.com/2026/11/09/us/politics/congress-republicans-agenda-lame-duck-session.html)
4. [Bipartisan Support for Israel Erodes as Both Sides Push for New Limits](https://www.nytimes.com/2026/11/09/us/politics/us-israel-midterm-elections.html)
5. [When the Boss on the Phone Isn't Real: How More Than $129 Million Was Stolen Using A.I.](https://www.nytimes.com/2026/11/08/business/ai-ceo-impersonation-theft.html)

## NBC

1. [Nvidia opens investigation after CEO's affair with alleged Chinese spy](https://www.nbcnews.com/tech/tech-news/nvidia-ceo-jensen-huang-investigation-rcna608148)
2. [Hakeem Jeffries says he's a 'hard yes' on impeaching Pete Hegseth](https://www.nbcnews.com/politics/congress/house-minority-leader-hakeem-jeffries-hard-yes-impeaching-hegseth-rcna608137)
3. [Trump says deportations were 'too tough' and hurt him in midterms](https://www.nbcnews.com/politics/trump-administration/trump-says-deportations-tough-hurt-midterms-rcna608208)
4. [U.S. Could Lose Measles Elimination Status as Cases Surge](https://www.today.com/video/u-s-could-lose-measles-elimination-status-as-cases-surge-273092165886)
5. [Tensions rise in Philadelphia over boycott of Jewish-owned restaurants](https://www.nbcnews.com/news/us-news/billboards-urge-boycott-boycott-jewish-owned-businesses-rcna608119)

## AP

1. [Nvidia investigates whether CEO Jensen Huang was targeted by Chinese spy with whom he had an affair](https://apnews.com/article/nvidia-jensen-huang-investigation-chinese-spy-68839e7ca6ba2b121529f7e475e501d6)
2. [A day before US-brokered talks, Russia and Ukraine batter each other with long-range strikes](https://apnews.com/article/russia-ukraine-war-talks-trump-514ff90fc04fae340898967e6655151c)
3. [Trump and his Justice Department stand defiant as Democrats ready an investigative blitz](https://apnews.com/article/congress-trump-democrats-investigations-impeachment-hegseth-blanche-a0a0593fab46dc8a24e89b03737d7a85)
4. [UN climate summit kicks off in Turkey after a disastrous year of extreme weather](https://apnews.com/article/turkey-cop31-summit-climate-change-edd587ab19f3b57848b50f9dc724ba82)
5. [Collision between 2 trains in Egypt kills 7 and injures at least 125](https://apnews.com/article/egypt-train-crash-giza-collision-cairo-injuries-4ad591268ce015d85ae302e22185b235)

## Note

**Selection window:** 2026-11-08 13:40 UTC to 2026-11-09 13:40 UTC (original publication time, not update or feed-retrieval time).

**Access limitations:**
- `wsj.com` returns HTTP 401 to direct fetches, consistent with prior days, so WSJ headlines are reproduced verbatim from their RSS `<title>` fields, with only the tracking query string (`?mod=...`) stripped from each canonical URL.
- `nytimes.com` article pages returned HTTP 403 to a direct bot fetch today (a change from recent prior days, when direct fetches succeeded), so NYT headlines and URLs were likewise taken as published in the RSS `<title>`/`<link>` fields rather than verified by loading the article page; the RSS feeds themselves fetched cleanly.
- AP publishes no general-purpose RSS feed, so candidates were sourced via `news.google.com/rss/search?q=site:apnews.com+when:1d`, per the task's own instructions. `apnews.com` itself returns HTTP 403 to direct fetches. Canonical AP URLs were recovered by fetching each Google News redirect page (with the task's own identifying user agent, no browser impersonation) for its embedded `data-n-a-sg`/`data-n-a-ts`/`data-n-a-id` attributes — the signature, timestamp, and signed article id Google News' own front end uses to resolve the link — and replaying Google News' public `batchexecute` RPC call with that payload, the same request a legitimate RSS reader makes when a reader opens the link. AP's own article pages were never fetched directly for content. All five resolved URLs returned HTTP 403 (bot-blocked, not 404) on a direct spot-check, consistent with this outlet's pattern on prior days, and each slug corresponds topically to its headline.
- All NBC feeds were fetched and spot-checked directly without issue; all five NBC links returned HTTP 200.
- One NBC selection (measles elimination status) resolves to a `today.com/video` URL rather than a text article, because that was the only in-window NBC-syndicated item on the subject; NBC's own text article on the same story published two days before the window and was not reused.

**Principal selection rationale:** The dominant story across every outlet today is Nvidia CEO Jensen Huang's disclosed affair with a woman U.S. officials have identified as a suspected Chinese intelligence asset, and the board investigation it has triggered — a story with corporate-governance, national-security, and markets consequences (Nvidia's stock was set to drop) for the world's most valuable chipmaker. Because all four outlets independently led with this story, each outlet's remaining four slots were chosen to surface genuinely distinct developments rather than further angles on Huang: the first days of a reordered, post-midterm Washington (Congress's hazy agenda, Jeffries' impeachment stance on Hegseth, Trump's own admission that his deportation policy "hurt" Republicans, and the Justice Department's defiance as Democrats ready investigations); acute geopolitical and economic developments (a last push of long-range strikes between Russia and Ukraine on the eve of U.S.-brokered talks, Japan's record-setting single-day currency intervention, a major Italian-German bank merger, and oil's slide on de-escalated Iran-strike fears); and distinct public-interest stories in safety, health, and society (a 1.2-million-vehicle Ford airbag recall probe, measles' threatened loss of U.S. elimination status, a deadly Egyptian train collision, a $129 million AI-voice-impersonation fraud, and rising boycott tensions in Philadelphia). This digest deliberately passed over ground already substantially covered in yesterday's (2026-11-08) edition — the Houthi/Aramco strike on Riyadh, Eisenkot's bid to form Israel's next government, and the Krakow, Poland mass shooting — in favor of today's new developments.

**Strongest excluded candidates:**
- **WSJ:** "Four Things to Watch as Power Changes Hands in Congress" — a real governance story, excluded as a forward-looking preview of scheduled events rather than a completed development; separately, WSJ's feed also carried "Netanyahu's Challenger Tapped to Try to Form Israeli Government" under the identical URL already used in yesterday's digest, confirming it as a rehash rather than new reporting.
- **NYT:** "Tesla Announces It Will Discontinue the Cybertruck, a Culture War on Wheels" — a genuinely significant auto-industry and cultural story, narrowly excluded to keep NYT's five from concentrating too heavily on business/technology themes already carried by the Huang and AI-fraud selections.
- **NBC:** "Russell Brand awaits sentencing as he faces 'significant' prison time for rape and sexual assaults" — a real courts-and-accountability story, excluded because its significance here depends substantially on celebrity personality, which this digest's standard deprioritizes.
- **AP:** "Israel's president gives Eisenkot the first chance to form the next government" — excluded because this is the identical development AP itself already featured in yesterday's (2026-11-08) digest, not a new one.

**Redundancy check:** No outlet's final five includes three or more items concerning the same underlying development. The Nvidia/Jensen Huang story was independently selected by all four outlets — cross-outlet convergence reflecting shared editorial judgment that it is the day's lead story, not within-outlet redundancy. The post-midterm Washington power shift was independently explored from four distinct angles by NYT, NBC (twice, on different sub-stories), and AP, each a genuinely separate development (legislative agenda, impeachment positioning, the president's own policy admission, and DOJ conduct) rather than repeated coverage of one fact.
