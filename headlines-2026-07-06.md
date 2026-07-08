# Headlines — 2026-07-06

Five headlines each from WSJ, NYT, NBC, and AP, published in the last 24 hours and ranked by durable significance rather than virality.

## WSJ

1. [Chinese Nuclear Submarine Test-Launches Long-Range Missile](https://www.wsj.com/world/chinese-nuclear-submarine-test-launches-long-range-missile)
2. [Trump to Meet With Zelensky as Russia-Ukraine Battlefield Remains ‘Frozen’](https://www.wsj.com/politics/trump-to-meet-with-zelensky-as-russia-ukraine-battlefield-remains-frozen-6f28ee97)
3. [Microsoft Is Cutting More Than 3,000 Jobs in Xbox Division](https://www.wsj.com/tech/microsoft-is-cutting-more-than-3000-jobs-in-xbox-division)
4. [TeraWulf Signs $19 Billion Lease With Anthropic for AI-Infrastructure Campus](https://www.wsj.com/business/terawulf-signs-19-billion-lease-with-anthropic-for-ai-infrastructure-campus)
5. [Solstice Advanced Materials to Buy Element Solutions for More Than $12 Billion](https://www.wsj.com/business/deals/solstice-advanced-materials-to-buy-element-solutions-for-more-than-12-billion-833e5d3f)

## NYT

1. [China Tests Long-Range Ballistic Missile in the Pacific, Angering Neighbors](https://www.nytimes.com/2026/07/06/world/asia/china-ballistic-missile-test-pacific.html)
2. [Iran Updates: Hundreds of Thousands Attend Ayatollah’s Funeral Procession](https://www.nytimes.com/live/2026/07/06/world/iran-khamenei-funeral)
3. [Former Syrian Officials Found Guilty in Torture of Pro-Democracy Protesters](https://www.nytimes.com/2026/07/06/world/europe/syria-officials-torture-trial-austria.html)
4. [Research Universities Are Admitting Fewer Ph.D.s, a Bad Sign for Science](https://www.nytimes.com/2026/07/06/us/research-universities-phd-admissions.html)
5. [At Trump’s Direction, Federal Agencies Are Abandoning Discrimination Cases](https://www.nytimes.com/2026/07/05/us/politics/trump-dei-order-eeoc-discrimination.html)

## NBC

1. [Russian strikes on Ukraine’s capital kills at least 15 ahead of NATO summit](https://www.nbcnews.com/news/world/russian-strikes-ukraine-kyiv-kills-15-ahead-nato-summit-rcna353142)
2. [China conducts rare long-range missile test, rattling U.S. allies](https://www.nbcnews.com/news/world/china-conducts-rare-long-range-missile-test-rattling-us-allies-rcna353085)
3. [Iran begins funeral procession through Tehran for Supreme Leader Ayatollah Ali Khamenei](https://www.nbcnews.com/news/world/iran-funeral-procession-tehran-supreme-leader-ayatollah-ali-khamenei-rcna353136)
4. [25 dead in ongoing heat wave as storms bring flood, wind threats to East Coast](https://www.nbcnews.com/weather/heat/25-dead-ongoing-heat-wave-storms-bring-flood-wind-threats-east-coast-rcna353020)
5. [Fierce winds hit U.S. Pacific territories as Super Typhoon Bavi makes landfall near Guam](https://www.nbcnews.com/weather/hurricanes/super-typhoon-bavi-guam-us-pacific-territories-rcna353044)

## AP

1. [Russia’s missile and drone attacks on Ukraine kill at least 22](https://apnews.com/article/russia-ukraine-war-july-6-2026-0280e3d86022720fd5fa0236122ad90e)
2. [Hamas dissolves its government in Gaza to transfer power to a UN-backed committee](https://apnews.com/article/israel-gaza-palestinians-hamas-war-government-146f9a609580d4c8c42ab35fbe60d5b3)
3. [China test-launches a ballistic missile in the South Pacific and raises regional concerns](https://apnews.com/article/china-missile-test-south-pacific)
4. [Philippine Senate opens the impeachment trial of Vice President Sara Duterte](https://apnews.com/article/philippine-vice-president-sara-duterte-impeachment-trial-6052d854b78881b742e48732b9305509)
5. [NATO chief demands allies present credible plans to reach defense spending targets](https://apnews.com/article/nato-summit-spending-rutte-afeb65422318e1dd91c5a433f9d35980)

## Note

Access limitations and method notes for this session:

- **WSJ** — The WSJ RSS index page was reachable with the browser user-agent, but direct local `curl` requests to the RSS feeds returned empty responses or proxy 403s. Headlines were selected from WSJ archive/search results and Google News' last-24-hours site feed; sports/World Cup process stories, opinion, books, and lifestyle items were excluded.
- **NYT** — Direct local `curl` to the NYT RSS feed returned empty responses or proxy 403s in this environment. The selection was cross-checked through Google News' last-24-hours site feed and secondary surfaced NYT references. Opinion, sports/The Athletic items, celebrity/lifestyle items, and crime-of-the-day coverage were excluded.
- **NBC** — Direct local `curl` to NBC's public feed returned empty responses or proxy 403s in this environment. The selection used Google News' last-24-hours site feed for `nbcnews.com`, excluding World Cup process stories, celebrity/royal coverage, AI-entertainment novelty, and transit/holiday curiosities.
- **AP** — AP was seeded via the requested Google News site-search feed. Google News RSS links did not resolve server-side to canonical article URLs in this environment, so AP article URLs were cross-checked against searchable AP result pages where available. World Cup process stories, daily crime items, sports, and novelty/celebrity items were excluded.

Selection standard: stories were chosen for likely significance 30 days out — war, strategic weapons tests, Middle East governance, NATO defense capacity, major institutional/legal developments, public health/weather risk, scientific capacity, and material corporate/technology developments — rather than outrage, novelty, celebrity, partisan theater, daily polling, social-media controversy, or transient viral attention. All selected items appeared in last-24-hours feeds or search surfaces checked on 2026-07-06 UTC.
