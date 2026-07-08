# All the News You Need

[Go to Today's Headlines.](headlines-2026-07-06.md)

The premise: news consumption is not civic virtue, a way to stay well-informed, or a sound path to better understanding the world. The news is inherently prone to focusing on outlier events, sensational content, and outrage.

The news is in the business of selling eyeballs to advertisers, selling talking points to decision-makers, and selling the illusion of being informed to you. 

It's entertainment posing as information. You don't need to follow it.

This is a tiny daily news digest for people who know that they don't need the news but are afraid of missing something truly important.

This is all the news you need.

## What It Does

Each day, a prompt generates a Markdown file named:

```md
headlines-YYYY-MM-DD.md
```

The file contains five headlines each from:

1. **WSJ** — for material significance: markets, law, institutions, business, geopolitics, regulation, energy, etc.
2. **NYT** — for agenda-setting influence among cultural, political, and professional elites.
3. **NBC** — for mainstream “normie” national news.
4. **AP** — for the wire-service baseline.

## Selection Standard

Headlines are selected based on significance, not virality; based on whether or not the story is likely to be significant in 30 days, not how many people are sharing it on social media. 

Preference is given to developments with durable consequences, including:

- War and international conflict
- Law, courts, and constitutional questions
- Elections and governance
- Regulation and public policy
- Markets, trade, labor, and business
- Technology and scientific developments
- Public health, medical developments
- Infrastructure, energy, and logistics
- Major institutional changes

The digest intentionally avoids or deprioritizes:

- Celebrity news
- Crime-of-the-day stories
- Outrage bait
- Daily polling noise
- Social media controversies
- Partisan theater
- Viral curiosities
- Lifestyle filler

## Format

Each daily file uses this structure:

```md
## WSJ

1. [Headline](https://example.com/article)
2. [Headline](https://example.com/article)
3. [Headline](https://example.com/article)
4. [Headline](https://example.com/article)
5. [Headline](https://example.com/article)

## NYT

1. [Headline](https://example.com/article)
2. [Headline](https://example.com/article)
3. [Headline](https://example.com/article)
4. [Headline](https://example.com/article)
5. [Headline](https://example.com/article)

## NBC

1. [Headline](https://example.com/article)
2. [Headline](https://example.com/article)
3. [Headline](https://example.com/article)
4. [Headline](https://example.com/article)
5. [Headline](https://example.com/article)

## AP

1. [Headline](https://example.com/article)
2. [Headline](https://example.com/article)
3. [Headline](https://example.com/article)
4. [Headline](https://example.com/article)
5. [Headline](https://example.com/article)

## Note

Access limitations, if any, are disclosed here.
```

## What This Is Not

This is not an attempt to showcase balance. This is not a substitute for being informed, which requires reading and contemplating actual books and other longform content, not the news. 

This is (more than) all the news you need.

## Implementations

This repository is the original: both the concept and a live daily digest, generated each day by a Claude routine that applies the selection standard and pushes a new `headlines-YYYY-MM-DD.md`.

Others have built their own implementations of the concept:

- **[ann](https://github.com/wbrown-dev/ann)** by [William C. Brown](https://github.com/wbrown-dev) — a Python implementation that fetches the feeds, uses Claude to apply the selection standard, and serves the digest through a Streamlit dashboard.

Built something? Open an issue to let me know and I'll add it here.

## License

The premise, selection standard, and digest format are licensed [CC BY 4.0](LICENSE) © Bethany Hunt (@ulyssestenn). Reuse freely with credit. 
