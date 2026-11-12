## WSJ

1. [Nvidia Is Preparing to Oust CEO Jensen Huang](https://www.wsj.com/business/nvidia-is-preparing-to-oust-nvidia-ceo-jensen-huang-30f421ad)
2. [Eight People Killed and 17 Injured in Brooklyn Building Collapse](https://www.wsj.com/us-news/eight-people-killed-and-17-injured-in-brooklyn-building-collapse-811b5e8d)
3. [Israel Strikes Gaza Hospital, Killing at Least Six](https://www.wsj.com/world/middle-east/israel-strikes-gaza-hospital-killing-at-least-six-e01ebd5f)
4. [Democrat Scott Colom Wins Mississippi Senate Seat in Historic Victory](https://www.wsj.com/politics/elections/scott-colom-wins-mississippi-senate-seat-in-historic-victory-d77bf913)
5. [Pfizer Signs $1.5 Billion Deal With Blackstone to Fund Weight-Loss-Drug Development](https://www.wsj.com/health/pharma/pfizer-signs-1-5-billion-deal-with-blackstone-to-fund-weight-loss-drug-development-b6b08b5d)

## NYT

1. [Nvidia Shares Plummet as Board Considers Jensen Huang’s Future as CEO](https://www.nytimes.com/2026/11/12/business/nvidia-stock-price-jensen-huang-ceo-affair.html)
2. [Strike on Gaza Hospital Kills at Least 6 and Injures 20, Rescuers Say](https://www.nytimes.com/2026/11/11/world/middleeast/nasser-hospital-gaza-strike-israel.html)
3. [Scott Colom, a Democrat, Wins Mississippi Senate Election](https://www.nytimes.com/2026/11/11/us/elections/mississippi-senate-colom-hyde-smith.html)
4. [Republicans Begin Aggressive Lame-Duck Push to Install Trump Judges](https://www.nytimes.com/2026/11/11/us/politics/trump-federal-judges-senate-republicans.html)
5. [Tech Giants Invest in German Robotics Start-Up at $8.5 Billion Valuation](https://www.nytimes.com/2026/11/12/business/softbank-nvidia-agile-robots.html)

## NBC

1. [Nvidia board meets over CEO’s future as chip giant reels from China spy scandal](https://www.nbcnews.com/business/business-news/nvidia-shares-drop-hours-reports-meeting-ceo-jensen-huangs-future-rcna608906)
2. [Israeli strike on Gaza hospital kills at least six people, officials say](https://www.nbcnews.com/world/middle-east/israeli-strike-gaza-nasser-hospital-abu-shaira-doctor-hamas-rcna608932)
3. [Building Collapse in Brooklyn Leaves at Least 5 Dead](https://www.today.com/video/search-for-survivors-continues-after-brooklyn-building-collapses-273327173561)
4. [Democrat Scott Colom wins Mississippi Senate seat, breaking GOP’s grip on the state](https://www.nbcnews.com/politics/2026-election/scott-colom-mississippi-senate-election-win-democrat-hyde-smith-rcna605729)
5. [New prostate cancer screening guidelines include regular PSA testing for most older men](https://www.nbcnews.com/health/cancer/new-prostate-cancer-screening-guidelines-regular-psa-test-rcna608629)

## AP

1. [Nvidia CEO Jensen Huang's future uncertain as Megaspeed pledges to cooperate with US probe](https://apnews.com/article/nvidia-megaspeed-china-singapore-huang-5403f152a601cf82ce939f1d24fffa0f)
2. [Israeli strike on Gaza hospital kills 6 people, including a doctor and a child, Health Ministry says](https://apnews.com/article/gaza-israel-hospital-strike-people-killed-50b547b5a82388b6b415aee4d776fbfb)
3. [Death toll rises to 6 in Brooklyn building collapse as rescuers dig through rubble](https://apnews.com/article/brooklyn-building-collapse-dead-rubble-digging-292b3ece5d9ba6e375413c9f4671cf00)
4. [Mississippi elects Democrat Scott Colom as state's first Black US senator since Reconstruction](https://apnews.com/article/scott-colom-mississippi-senate-midterms-56c18f292a734443992f9466c3b0f346)
5. [Indonesia's vice president resigns as his eligibility and academic credentials are questioned](https://apnews.com/article/indonesia-gibran-rakabuming-raka-resigns-abfe5e288fad3b8b26719eae634f2ee0)

## Note

**Selection window:** 2026-11-11 13:39 UTC to 2026-11-12 13:39 UTC (original publication time, not update or feed-retrieval time).

**Access limitations:**
- `wsj.com`, `nytimes.com`, and `apnews.com` return HTTP 401/403 to direct fetches of article pages, the same pattern observed on prior days. WSJ and NYT headlines and canonical URLs were taken from their RSS `<title>`/`<link>` fields (all eight WSJ feeds and ten NYT feeds fetched cleanly over HTTPS), with tracking query strings (e.g. `?mod=...`) stripped from WSJ URLs. One WSJ item (the Mississippi Senate result) appeared in the feed only with a newsletter-style descriptive sentence as its `<title>`, not a standard headline; a standard headline was derived from the article's URL slug (`scott-colom-wins-mississippi-senate-seat-in-historic-victory`), the same approach used on 2026-11-11 for a comparable WSJ feed item.
- AP publishes no general-purpose RSS feed, so candidates were sourced via `news.google.com/rss/search?q=site:apnews.com+when:1d`, per the task's own instructions. Canonical AP URLs were recovered by fetching each Google News redirect page (with the task's own identifying user agent, following redirects) for its embedded `data-n-a-id`/`data-n-a-ts`/`data-n-a-sg` attributes and replaying Google News' public `batchexecute` RPC (`Fbv4je`/`garturlreq`) with that payload — the same resolution a standard RSS reader performs when opening the link. AP's own article pages were never fetched for content; this is the same verification method used in prior digests.
- All NBC feeds were fetched and spot-checked directly without issue. One NBC selection (the Brooklyn building-collapse item) is sourced from a `today.com` video item, the only Brooklyn-collapse coverage present in NBC's own public feeds at the time of collection; NBC's text-only death toll (5) was lower than AP's and WSJ's more recent counts (6–8) because the story was still developing across the collection window — this reflects the pace of a breaking story, not a sourcing error.
- NYT's ten feeds (including World and US) carried no article on the Brooklyn building collapse within the selection window, despite it meeting NYT's own usual threshold for major breaking domestic news; this is disclosed as a feed-coverage gap rather than a deliberate exclusion.

**Principal selection rationale:** Four developments anchored nearly every outlet's pool: (1) Nvidia's board weighing CEO Jensen Huang's removal after a second reported relationship with a subordinate executive compounded an ongoing China-espionage/chip-export scandal — a corporate-governance crisis at one of the world's most valuable companies; (2) an Israeli strike on Gaza's Nasser Hospital that killed at least six people, including a doctor and a child; (3) a partial building collapse in Brooklyn that killed as many as eight people and prompted an active rescue operation; and (4) Democrat Scott Colom's election as Mississippi's first Black U.S. senator since Reconstruction, flipping a seat held by Republicans and padding the Senate's Democratic majority. Remaining slots were chosen for genuinely distinct, durable developments outside that cluster: public health (revised American Cancer Society prostate-screening guidance recommending regular PSA testing for most older men; Pfizer's $1.5 billion deal with Blackstone to fund weight-loss-drug development), law and institutions (an aggressive Republican lame-duck push to install Trump judicial nominees before the new Congress is seated), technology and business investment (an $8.5 billion valuation for a German AI-robotics startup backed by Big Tech), and international governance (Indonesian Vice President Gibran Rakabuming Raka's resignation amid questions over his eligibility and academic credentials).

**Strongest excluded candidates:**
- **WSJ:** "White House Warns Democrats Against 'Blatant Criminality' in Investigation Demands" — a real institutional flashpoint, but excluded as a political warning without concrete legal action yet taken, bordering on partisan theater relative to the five selected developments.
- **NYT:** "White House Threatens Congress, Saying Aggressive Investigations Could Be Crime" — excluded for the same reason as the WSJ candidate above, and because its underlying executive-legislative friction is already reflected, with more concrete institutional stakes, in the lame-duck judges story.
- **NBC:** "White House warns congressional Democrats: Investigating us may be a crime" — excluded as a political warning rather than a concrete durable development; its institutional-tension theme is already carried by the historic Mississippi Senate result.
- **AP:** "White House confronts Democrats over planned probes, claiming possible 'criminality'" — excluded for the same reason; replaced with the Indonesian vice president's resignation to add a distinct, durable international-governance development.

**Redundancy check:** Three underlying developments were independently selected by all four outlets: Nvidia's CEO crisis, the Israeli strike on Gaza's Nasser Hospital, and Scott Colom's historic Mississippi Senate win. A fourth, the Brooklyn building collapse, was independently selected by three outlets (WSJ, NBC, AP); NYT's own feeds carried no article on it in the window (see Access limitations). This reflects a genuinely concentrated news day — by a wide margin, editors across all four outlets converged on the same handful of developments as most significant — not within-outlet repetition: no single outlet's five includes more than one headline on any of these developments. Each outlet's remaining one or two slots were independently selected for distinct developments spanning public health, law and institutions, technology investment, and international governance, as detailed above.
