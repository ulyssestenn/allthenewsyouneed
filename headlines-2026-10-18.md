# Top Headlines — October 18, 2026

## WSJ

1. [Zelensky Takes a Risk by Publicly Confronting Trump Over Russia](https://www.wsj.com/articles/zelensky-takes-a-risk-by-publicly-confronting-trump-over-russia-f5ed557a)
2. [Violent Protests Rip Through Cities Across France](https://www.wsj.com/world/europe/violent-protests-rip-through-cities-across-france-b617c585)
3. [Masked Israeli Settlers Attack European Diplomats in West Bank](https://www.wsj.com/world/middle-east/masked-israeli-settlers-attack-european-diplomats-in-west-bank-f60dedd1)
4. [Alberta's Secession Vote Opens Up a Bitter Divide in Canada](https://www.wsj.com/world/americas/alberta-independence-vote-canada-22b8208b)
5. [SoftBank in Early Talks to Buy Allied Universal](https://www.wsj.com/business/deals/softbank-in-early-talks-to-buy-allied-universal-2d582a66)

## NYT

1. [Trump Offers Putin Economic Relief in Hopes That Russia Will Return the Favor](https://www.nytimes.com/2026/10/17/business/trump-russia-sanctions-congress.html)
2. [Graham Breaks With Trump Over Russia Sanctions Law Her Brother Championed](https://www.nytimes.com/2026/10/17/us/politics/graham-trump-russia-sanctions-law.html)
3. [Israeli Settlers Attack Palestinians and European Officials in West Bank](https://www.nytimes.com/2026/10/17/world/middleeast/israeli-settlers-attack-palestinians-diplomats-west-bank.html)
4. [France in Shock After Protests Devolve Into Riots](https://www.nytimes.com/2026/10/18/world/europe/france-protests-shock-arson.html)
5. [Weak Links Start to Show in A.I. Borrowing](https://www.nytimes.com/2026/10/17/business/ai-debt-coreweave-oracle-softbank.html)

## NBC

1. [U.S. taking Putin's side would be a 'historic mistake,' says Zelenskyy](https://www.nbcnews.com/politics/trump-administration/us-taking-putins-side-historic-mistake-says-zelenskyy-rcna604111)
2. [Large Military Base Fire in Canada Leaves Several Dead](https://www.today.com/video/several-dead-after-large-fire-at-canada-military-base-271777349554)
3. [Many Women Are Still Struggling to Fill Estrogen Patch Prescriptions. What to Do If You Can't Get Yours](https://www.today.com/health/womens-health/estrogen-patch-shortage-expert-advice-fda-rcna602985)
4. ['The house was toast': Surf swallows California homes](https://www.nbcnews.com/news/us-news/beachfront-homes-destroyed-california-coastal-erosion-el-nino-bring-hi-rcna603211)
5. [President Trump faces backlash over Russia sanctions relief](https://www.nbcnews.com/nightly-news/video/president-trump-faces-backlash-over-russia-sanctions-relief-271759941812)

## AP

1. [Trump's decision to waive Russian sanctions outrages Congress, but no quick counter seen](https://apnews.com/article/trump-sanctions-waiver-russa-putin-ukraine-war-3cc9740c39e9e9eb713b1c553b5709e6)
2. [French police arrest 1,800 after violent clashes and looting mar protests](https://apnews.com/article/france-protests-violence-looting-f5ce07c2ef46ad0c02c6ff7018532a59)
3. [Masked settlers attack European diplomats in the occupied West Bank](https://apnews.com/article/west-bank-israel-european-diplomats-settlers-89ebd068167669db357ad1fa4f3a8758)
4. [Stampede at a popular Hindu festival in eastern India kills 19](https://apnews.com/article/india-hindu-festival-durga-puja-stampede-ee803af1bef07fab3c1157974be2e876)
5. [Consumer apprehension grows as US retailers adopt AI-assisted pricing tools](https://apnews.com/article/ai-prices-dynamic-customers-technology-64c446cd117d3be664de4ab570fb9857)

## Note

**Selection window:** 2026-10-17 13:39 UTC through 2026-10-18 13:39 UTC (24 hours ending at the time this digest was compiled). Filtering used each item's original `pubDate`, not an update or feed-retrieval time.

**Access and verification:**
- All 26 WSJ, NYT, and NBC RSS feeds listed in the task returned HTTP 200 with the specified user agent, yielding 965 candidate items (250 inside the 24-hour window after parsing: 23 WSJ, 94 NYT, 33 NBC, prior to per-outlet dedup).
- WSJ's own site returns a bot-verification challenge page on direct fetch, so all five WSJ selections use each article's canonical `<link>` exactly as published in the outlet's own RSS feed, with tracking query parameters (`?mod=...`) stripped. Three WSJ candidate titles in this window (the Russia-sanctions waiver, a Kansas Senate race item, and a Hakeem Jeffries item) carry a descriptive social-media blurb in `<title>` rather than a published headline; none of those three was selected, so no headline reconstruction was needed for this digest.
- The WSJ's own article on Trump's waiver of most Russia sanctions (`trump-waives-most-russia-sanctions-passed-by-congress-4c36bc93`) reappeared in today's feed but is the identical URL used as WSJ's lead headline in yesterday's (Oct. 17) digest. It was treated as a stale republish, not a new development, and dropped in favor of a genuinely new article on the same underlying story: Zelensky's public confrontation with Trump over the waiver, published today.
- AP has no general-purpose public RSS feed, so candidates were sourced via the specified Google News search feed (`site:apnews.com when:1d`), which returned 100 items in the window. Its entries link through `news.google.com` redirect pages rather than canonical `apnews.com` URLs. Each selected item's redirect page was fetched with `curl -L` (required for the page's JavaScript-bearing HTML to load), its `data-n-a-sg`/`data-n-a-ts` signing attributes were extracted, and replayed against Google News's own `batchexecute` decoding endpoint — the same mechanism Google's News app uses client-side — to obtain the real `apnews.com` destination for each candidate. Direct requests to the resulting `apnews.com` URLs return HTTP 403 (consistent with AP's known bot-blocking), so the five AP URLs below were not independently re-fetched after decoding, but each was produced by Google's own redirect-resolution service rather than guessed or constructed.
- Two NBC selections ("Large Military Base Fire in Canada Leaves Several Dead" and "President Trump faces backlash over Russia sanctions relief") exist in NBC's own RSS feeds only as `today.com`/`nbcnews.com` video-page URLs, not text articles; no separate NBC text article on either story fell inside the window. Consistent with this repository's established practice, the video links supplied directly by NBC's own feed were used rather than omitted or substituted.

**Selection rationale:** The dominant cross-outlet story is the fallout from President Trump's decision to waive most congressionally mandated Russia sanctions: Ukraine's Zelensky publicly confronting Trump over it (WSJ, NBC), bipartisan congressional anger including a Senate Republican breaking with the White House (NYT, AP), and Trump's attempt to offer Russia economic relief in return for cooperation (NYT) — a direct clash between the executive branch and a bipartisan sanctions law with lasting consequences for the war and for separation-of-powers precedent. Beyond that, selections favored concrete, durable developments: violent, escalating protests across France that triggered mass arrests (WSJ, NYT, AP); a masked-settler attack on European diplomats in the West Bank, a serious diplomatic-security escalation (WSJ, NYT, AP); Alberta's independence referendum exposing a lasting divide in Canadian federalism (WSJ); a SoftBank bid for security giant Allied Universal (WSJ); early cracks in AI-related corporate borrowing, bearing on the durability of the broader AI investment boom (NYT); a deadly fire at a Canadian military base (NBC); a nationwide U.S. prescription-drug shortage affecting hormone therapy patients (NBC); coastal home losses from erosion in California (NBC); a deadly stampede at a mass religious gathering in India (AP); and the spread of AI-assisted dynamic pricing among U.S. retailers, with its consumer-protection implications (AP). Deprioritized in favor of these: Pope Leo's post-surgery return to public duties (already well covered on recent days), a fatal truck-into-soccer-game tragedy in Kansas (heavy same-day coverage but no durable institutional consequence), daily midterm horse-race polling and campaign-trail soundbites, Oregon school-shooting human-interest follow-ups, a 30-year-old O.J. Simpson case retrospective, college-football results, and celebrity/lifestyle/shopping content.

**Strongest excluded candidates:**
- **WSJ:** "Nearly All Volume on FIFA-Linked Prediction Market Is Circular Trading" — a genuine market-integrity finding, but narrower in reach than SoftBank's multibillion-dollar bid for Allied Universal, which went to the business slot instead.
- **NYT:** "At Least 19 Dead After Stampede at Indian Religious Event" — a real mass-casualty event, but it lost out to "Weak Links Start to Show in A.I. Borrowing," whose systemic economic stakes were judged more durable; the stampede was instead selected independently by AP.
- **NBC:** "Two killed, including a child, after woman drives through youth soccer game in Kansas" — the most heavily covered NBC item of the day, but ultimately a crime-of-the-day tragedy without durable policy consequence; the slot went to the estrogen-patch shortage story's clearer durable public-health stakes.
- **AP:** "California officials who process ballots from suspected noncitizens risk prosecution, US warns" — a genuine federal-state legal clash, but narrower in reach than the AI-assisted retail-pricing story, which carries broader consumer-protection and regulatory stakes.

**Redundancy check:** No single outlet's final five contains three or more selections describing the same underlying development. NYT's list has two items tied to the Russia-sanctions fallout (the Putin economic-relief offer and the Graham Senate break), each representing a genuinely distinct consequence (executive diplomacy vs. congressional revolt); NBC's list likewise has two (Zelenskyy's "historic mistake" quote and domestic political backlash), again distinct angles on the same story. The Russia-sanctions story also appears, independently selected, across WSJ, NYT, NBC, and AP, and the France-protests and West Bank-diplomat-attack stories each appear independently across WSJ, NYT, and AP — in each case because every outlet judged the story newsworthy on its own merits, not because of duplication within any one outlet's five.
