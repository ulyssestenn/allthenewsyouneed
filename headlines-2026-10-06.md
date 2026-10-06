## WSJ

1. [Former German Spy Chief Arrested on Suspicion of Espionage](https://www.wsj.com/world/europe/former-german-spy-chief-arrested-on-suspicion-of-espionage-9e261c69)
2. [Oil Industry's Bid to Kill Climate Change Lawsuits Faces SCOTUS Skepticism](https://www.wsj.com/politics/policy/oil-industrys-bid-to-kill-climate-change-lawsuits-faces-scotus-skepticism-a9be9855)
3. [Paramount Names Leadership Team for Combined Entity Post $81 Billion Warner Deal](https://www.wsj.com/business/media/paramount-names-leadership-team-for-combined-entity-post-81-billion-warner-deal-c37b9b0d)
4. [Yemen's Houthi Rebels Strike Two Airports in Saudi Arabia](https://www.wsj.com/world/middle-east/yemens-houthi-rebels-strike-two-airports-in-saudi-arabia-072f4dd3)
5. [Hackers Use Chinese AI Tool to Hit South Korean Banks, Exposing New Risk](https://www.wsj.com/world/asia/hackers-use-chinese-ai-tool-to-hit-south-korean-banks-exposing-new-risk-5d4d3885)

## NYT

1. [Paramount Closes Its Deal for Warner Bros. Discovery](https://www.nytimes.com/2026/10/06/business/media/paramount-warner-bros-discovery-skydance.html)
2. [German Officials Arrest Former Spy Chief on Espionage Charges](https://www.nytimes.com/2026/10/06/world/europe/germany-spy-chief-hanning-arrested-espionage.html)
3. [Supreme Court Tangles Over a Major Climate Change Case](https://www.nytimes.com/2026/10/05/us/politics/supreme-court-climate-change-oil.html)
4. [Germany's Far Right Claims Its First Statehouse Speaker Since 1945](https://www.nytimes.com/2026/10/06/world/europe/germany-afd-saxony-anhalt.html)
5. [Protests Spread Across France, Growing From School Demonstrations](https://www.nytimes.com/2026/10/06/world/europe/france-student-strikes-protests.html)

## NBC

1. [Flydubai pilot planned 9/11-style attack, source tells NBC News](https://www.nbcnews.com/world/middle-east/flydubai-pilot-planned-crash-israel-airport-tel-aviv-oman-investigatio-rcna601806)
2. [California officials condemn Trump for saying Iran could 'take out' Los Angeles or San Diego](https://www.nbcnews.com/politics/donald-trump/california-newsom-condemn-trump-iran-los-angeles-san-diego-rcna601821)
3. [FBI whistleblower says White House pushed unconstitutional probe of protesters](https://www.nbcnews.com/politics/justice-department/fbi-whistleblower-says-white-house-pushed-unconstitutional-probe-prote-rcna601599)
4. [Cornell faculty senate introduces no-confidence resolution over handling of alleged 2024 sexual assault](https://www.nbcnews.com/news/us-news/cornell-faculty-senate-introduces-no-confidence-resolution-handling-al-rcna601824)
5. [Pennsylvania's measles outbreak is the country's largest in three decades](https://www.nbcnews.com/health/health-news/pennsylvanias-measles-outbreak-countrys-largest-three-decades-rcna601648)

## AP

1. [Ex-spy chief is arrested in Germany on suspicion of trading state secrets and treason](https://apnews.com/article/germany-arrest-espionage-allegation-former-intelligence-chief-47bb15543a3e2404e3f756dbb517d14c)
2. [Supreme Court weighs local governments' climate change lawsuits against oil and gas companies](https://apnews.com/article/supreme-court-climate-change-wildfires-natural-disasters-6f8bb7d17b03c128017c961f872cff3e)
3. [FBI arrests California woman accused of spying on Taiwan leader's family for China](https://apnews.com/article/fbi-arrest-china-taiwan-spying-42e55337e768722b67874b9dc29f127c)
4. [Quebec separatists vowing independence vote win an election but fall short of majority](https://apnews.com/article/canada-quebec-election-a4e8ecaa4026c46d0346e9487c5e333d)
5. [ICC unseals arrest warrants for 4 Taliban leaders wanted on gender persecution charges](https://apnews.com/article/icc-taliban-afghanistan-women-girls-d865b7b9695311a5c18c8f95769b9132)

## Note

**Selection window:** 2026-10-05 13:37 UTC to 2026-10-06 13:37 UTC (the 24 hours preceding compilation), filtered on each feed's original `pubDate`/`published` timestamp, not an update or retrieval time.

**Access limitations and verification methods:**
- `apnews.com` returns an HTTP 403 bot challenge to direct fetches in this environment, and AP publishes no general-purpose RSS feed, so candidates were sourced via Google News search (`site:apnews.com when:1d`) as instructed. Decoding the Google News redirect IDs via Google's internal `batchexecute` endpoint (the method noted as failing in this repository's prior digests) was not attempted again; instead, a headless Chromium browser (pre-installed in this environment, routed through the session's egress proxy) loaded each Google News redirect page and followed its client-side JavaScript redirect to capture the resulting canonical `apnews.com/article/...` URL. All five AP links above were resolved this way and the original Google News-reported headline and timestamp were retained.
- `wsj.com` blocks direct fetches with a DataDome bot challenge in this environment, so WSJ headlines/timestamps were taken as published in Dow Jones' own RSS feeds; tracking query parameters (`?mod=...`) were stripped from feed links to produce canonical article URLs.
- `nytimes.com` and `nbcnews.com`/`today.com` fetches succeeded directly via their own RSS feeds, which is treated as sufficient verification since links and timestamps originate directly from the outlets' own feed metadata.

**Principal selection rationale:** Prioritized developments with durable, 30-days-from-now consequence over the day's volume of midterm-campaign ad spending, Prime Day shopping content, and NFL/MLB playoff recaps: the arrest of Germany's former foreign-intelligence chief on espionage and treason charges; the Supreme Court's new term taking up a major climate-liability case against oil and gas companies; Paramount's completed $81 billion acquisition of Warner Bros. Discovery reshaping the media industry; a new escalation in the Saudi-Houthi conflict with strikes on two Saudi airports; evidence that a Chinese AI tool was used to breach South Korean banks; Germany's AfD winning its first state-legislature speakership since 1945; spreading student-led protests destabilizing France's government; a planned Flydubai 9/11-style hijacking plot; presidential rhetoric about striking U.S. cities that drew formal state pushback; an FBI whistleblower's claim of an unconstitutional White House-directed investigation of protesters; Cornell's faculty no-confidence vote over its handling of a campus assault case; the largest U.S. measles outbreak in three decades; an FBI counterintelligence arrest tied to alleged Chinese surveillance of Taiwan's president's family; Quebec's separatist party winning power on a sovereignty platform; and the ICC's first gender-persecution arrest warrants against Taliban leaders. Deprioritized: Jim Bakker's death, Cornell "tipster" and ketamine-detail coverage beyond the institutional no-confidence vote itself, Prime Day deal round-ups, celebrity items (Kash Patel's engagement, Karoline Leavitt's new job), NFL/MLB game recaps, and routine opinion columns.

**Strongest excluded candidate per outlet:**
- **WSJ:** "C.H. Robinson to Buy RXO for About $5.8 Billion" — a genuine freight-industry consolidation, but narrower in consequence than the $81 billion Paramount-Warner Bros. Discovery deal that filled WSJ's media/business slot.
- **NYT:** "India Cut 130 Million From Voter Roll, Fueling Protests Against Modi" — a major democratic-integrity story for the world's largest democracy, but narrowly excluded in favor of Germany's AfD speakership milestone and France's spreading protests, which carry more immediate institutional consequence this cycle.
- **NBC:** "Massachusetts man pleads guilty to selling radioactive material from Russia" — a real nuclear-security case, but a narrower single-defendant story than the whistleblower, Flydubai, Cornell, and measles-outbreak stories that filled NBC's list.
- **AP:** "Alito says Supreme Court can't stem emergency appeals and voices concern over Trump's rhetoric" — a sitting justice's rare on-the-record remarks about the president, lost its slot narrowly to the ICC's Taliban arrest warrants, which represent a concrete new institutional action rather than commentary.

**Redundancy check:** No outlet's own five selections contain three or more items about the same underlying development. Two stories recur across outlets: the arrest of Germany's former intelligence chief (WSJ, NYT, AP) and the Supreme Court's climate-liability case (WSJ, NYT, AP). In both cases this reflects natural convergence — each outlet independently judged these among the day's most significant stories — rather than one outlet repeating itself.
