## WSJ

1. [OpenAI Considers Pre-IPO Funding Round at More Than $1.2 Trillion Valuation](https://www.wsj.com/tech/ai/openai-considers-pre-ipo-funding-round-at-more-than-1-2-trillion-valuation-54555295)
2. [U.S. Eyes China and Russia as Pentagon Confirms Space Weapons](https://www.wsj.com/politics/national-security/u-s-eyes-china-and-russia-as-pentagon-confirms-space-weapons-2e373e47)
3. [NBC News Helicopter Crashes in Los Angeles, Killing Three](https://www.wsj.com/us-news/nbc-news-helicopter-crashes-in-los-angeles-killing-three-dc7148e4)
4. [Charlie Kirk's Widow Says in Legal Claim University Failed to Protect Him](https://www.wsj.com/us-news/charlie-kirks-widow-says-in-legal-claim-university-failed-to-protect-him-967fc8a6)
5. [Landmark Crypto Bill Fails Procedural Vote, Casting Doubt on New Digital-Asset Rules](https://www.wsj.com/politics/policy/landmark-crypto-bill-fails-procedural-vote-casting-doubt-on-new-digital-asset-rules-d6fc4c47)

## NYT

1. [Fed Readies for Momentous Rate Decision](https://www.nytimes.com/2026/09/16/business/economy/federal-reserve-interest-rates-warsh.html)
2. [Trump Approves $2.8 Billion Arms Sale to Israel, Including 40,000 One-Ton Bombs](https://www.nytimes.com/2026/09/15/us/politics/trump-israel-bombs.html)
3. [E.U. Offers to Make Canada 'Associate Member' as U.S. Ties Weaken for Both](https://www.nytimes.com/2026/09/16/world/europe/eu-canada-associate-member.html)
4. [Age Limits for Social Media Outlined by European Union](https://www.nytimes.com/2026/09/16/business/european-union-social-media-ban.html)
5. [Kosovo's Former Leader Is Sentenced to 25 Years in War Crimes Case](https://www.nytimes.com/2026/09/16/world/europe/kosovo-thaci-war-crimes-hague-serbia.html)

## NBC

1. [3 dead after NBC L.A. helicopter crashes while covering fatal bus collision](https://www.nbcnews.com/news/us-news/helicopter-crashes-los-angeles-chatsworth-rcna598061)
2. [Federal Reserve to announce interest rate decision as Trump calls for a cut](https://www.nbcnews.com/business/economy/trump-federal-reserve-warsh-interest-rates-rcna597896)
3. [Saudi Arabia accuses Houthis of attacking Mecca, warns holy city is a 'red line'](https://www.nbcnews.com/world/middle-east/saudi-arabia-mecca-houthis-drone-iran-war-trump-oil-gas-prices-rcna598075)
4. [Trump's handpicked Kennedy Center board votes to immediately close venue for renovations](https://www.nbcnews.com/politics/trump-administration/trumps-handpicked-kennedy-center-board-votes-close-venue-renovations-rcna597921)
5. [U.S. accuses Russia of plot to kill a prominent dissident in Washington](https://www.nbcnews.com/world/russia/russia-plot-kill-dissident-washington-doj-kremlin-rcna598079)

## AP

AP is omitted in full today. Every documented resolution path for AP content was attempted and failed; see the Note below. No AP headlines are included rather than publish unresolved or non-canonical links.

## Note

**Selection window:** 2026-09-15 13:36 UTC to 2026-09-16 13:36 UTC (24 hours), filtered by each item's original publication timestamp (each outlet's own RSS `<pubDate>` for WSJ/NYT/NBC).

**Access notes — WSJ, NYT, NBC:** All eight listed WSJ feeds, all ten listed NYT feeds, and all eight listed NBC feeds were fetched directly with the specified user agent and parsed successfully as RSS/XML; no feed was inaccessible. WSJ and NYT article pages return 401/403 to automated requests (login/paywall and bot-detection gating respectively), so they were not fetched directly for verification, but each returned a real 401/403 response (i.e., a genuine, reachable page) rather than a 404, confirming the URLs are live. All five WSJ links are canonical URLs taken directly from WSJ's own RSS feeds with the `?mod=` tracking parameter stripped; two WSJ headlines (the crypto-bill and space-weapons items) were rendered in proper headline case from WSJ's own URL slug, since WSJ's social/political feed supplied a descriptive summary sentence rather than a headline for those two items. All five NBC links were verified to return HTTP 200.

**AP is omitted this run — full disclosure of what was attempted:** AP does not provide a general RSS feed, so per the sourcing instructions, AP candidates were pulled from a Google News search restricted to `site:apnews.com when:1d`, which returned 100 candidate items with real headlines, "AP News" source attribution, and timestamps, all within the 24-hour window. However, every method attempted to resolve those Google News redirect links to canonical `apnews.com` URLs failed in this run's network environment:
- `apnews.com` itself returns HTTP 403 with a Cloudflare bot-challenge page (`cf-mitigated: challenge`) to every direct request, including the homepage and topic-hub pages — confirmed with multiple user agents.
- The Google News redirect endpoints (`news.google.com/rss/articles/...` and `news.google.com/articles/...`, with and without `hl`/`gl`/`ceid` parameters) consistently returned either an HTTP 400 "malformed request" error or a redirect to Google's `/sorry/index` bot-verification page — reproduced across curl, Python's `urllib`, HTTP/1.1 vs HTTP/2, multiple user agents (desktop and mobile), and a retry after a cooldown period. This is a harder block than the base64-decode-plus-signature workaround used successfully in prior runs of this digest, because that workaround itself requires first loading the interstitial HTML page, which is exactly what returned 400/sorry here.
- The `WebFetch` tool was tried directly on both Google News redirect URLs and a candidate `apnews.com` URL; both failed (400 Bad Request and an explicit "unable to fetch from apnews.com," respectively).
- `WebSearch` was tried both with `allowed_domains: ["apnews.com"]` (rejected outright: "apnews.com not accessible to our user agent") and with `site:apnews.com` query syntax (returned zero apnews.com results; only third-party sites that reprint the AP wire copy, such as WRAL, NBC News, ABC News, and local affiliates, none of which link back to the original apnews.com URL in their page content, per a direct check of one such page).
- Bing and DuckDuckGo were queried directly by URL for `site:apnews.com` searches; both returned pages with no parseable organic results (consistent with automated-traffic filtering).
- The Internet Archive's CDX API (a different, normally-unblocked domain) was queried to look up recently archived apnews.com URLs by keyword; it returned an "Internet Archive: Temporarily Offline" page on repeated attempts, indicating a genuine outage rather than a block, but it was still unusable.

Because the digest's format requires the canonical source article and explicitly forbids "unresolved" URLs, and a Google News redirect link is by definition unresolved, no AP items are included today rather than publish a broken, redirect, or non-canonical (third-party mirror) link in their place.

To partly offset the lost AP coverage, three stories that would otherwise have anchored the AP section — the first-ever U.S. acknowledgment of deployed space weapons, the EU's proposed bloc-wide social-media age limit, and the Trump administration's $2.8 billion bomb sale to Israel — are represented instead through WSJ's and NYT's own independently reported, directly resolvable coverage of the same developments (see WSJ #2, NYT #4, and NYT #2, respectively).

**Selection rationale:** The day's most consequential single event is the Federal Reserve's rate decision, expected to raise rates in defiance of White House pressure; it is represented via NYT and NBC's own distinct framings (institutional independence and market stakes) rather than repeated a third time. A National Transportation Safety Board-relevant tragedy — the crash of an NBC-operated news helicopter in Los Angeles, killing three, while covering an unrelated fatal bus collision — is durable for its aviation-safety and broadcast-newsgathering implications and is covered by both WSJ and NBC (as the outlet directly involved). Institutional and foreign-policy stories with 30-day-plus consequence dominate the rest of the slate: the U.S.'s first-ever public acknowledgment of deployed space weapons, a $2.8 billion U.S. bomb sale to Israel, the EU's offer of "associate member" status to Canada amid strained U.S.-Canada ties, a bloc-wide EU proposal to restrict children's social-media access, a 25-year war-crimes sentence for Kosovo's former president, a Congressional setback for landmark crypto legislation, an FBI-disrupted Russian assassination plot on U.S. soil, Saudi Arabia's "red line" warning to the Houthis after an alleged attack near Mecca, and the Kennedy Center's board voting to close the venue for a two-year renovation amid an ongoing naming dispute with the Trump administration. Two developments already covered in yesterday's digest — the Supreme Court's mail-ballot ruling and the AI industry's slowdown debate — were deliberately excluded from today's slate despite continuing follow-on coverage (e.g., Trump's public criticism of the ruling, the Bannon-Sanders AI-regulation alliance) in favor of the fresher, more agenda-setting stories above.

**Strongest excluded candidates:**
- **WSJ:** "Congressional Watchdog Puts Iran War Costs at $38 Billion, Estimates 5 Years to Replace Interceptors" — a solid fiscal-accountability story, excluded in favor of the first-ever confirmation of U.S. space-weapons deployment, judged to carry greater durable national-security significance.
- **NYT:** "Charlie Kirk's Family Accuses University of 'Stunning' Security Failures" — a strong institutional-accountability story, excluded to avoid redundancy with WSJ's own coverage of the same claim and to make room for the EU's bloc-wide social-media age-limit proposal, which affects a broader industry and public.
- **NBC:** "House panel votes to hold Epstein associate Leon Black in contempt" — a notable congressional-oversight story, excluded in favor of the FBI's disruption of a Russian assassination plot on U.S. soil, judged more significant for national security.
- **AP:** Not applicable — the entire AP candidate pool was unusable this run for canonical-URL resolution (see Access notes above), not because it lacked qualifying stories. Based on headlines and timestamps alone (unverified for canonical URL), the strongest AP-only candidates that could not be used were "Satellites show Earth lost more than 12 trillion tons of ice from Greenland, Antarctica in 47 years" and "A crisis is shaking Brazil's Supreme Court."

**Redundancy check:** No outlet's final five contains three or more items tied to the same underlying development. Two developments are each represented by two outlets, reflecting genuinely distinct framings rather than a repeat: the Fed's rate decision (NYT's institutional/market framing vs. NBC's Trump-pressure framing) and the NBC helicopter crash (WSJ's national/aviation-safety framing vs. NBC's own-outlet framing as the affected news organization).
