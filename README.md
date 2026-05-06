# Available .WATCH One-Word Domains (11,596)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-11%2C596%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .watch one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **11,596 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 11,596 domains · **Median ask:** $13.46 · **High-demand under $2,500:** 0

**Last updated:** 2026-05-06  
**Canonical page:** `https://unique.domains/domains/tld/watch`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/watch?utm_source=github&utm_medium=referral&utm_campaign=repo_watch_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./watch.csv">CSV</a> / <a href="./watch.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_watch_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_watch_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .WATCH search](https://unique.domains/domains/tld/watch?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_watch_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .WATCH search](https://unique.domains/domains/tld/watch?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_watch_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_watch_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .WATCH one-word domain catalog.

### Files

- `watch.csv` — public CSV extract (1,000 rows)
- `watch.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/watch-oneword-domains/main/watch.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain         | status    | ask_price | renewal_price | attractiveness | demand | length | registrar         |
| -------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ----------------- |
| whynot.watch   | available | $4.99     | —             | 74             | 39     | 7      | name.com          |
| online.watch   | resell    | —         | —             | 70             | 62     | 7      | Dynadot Inc       |
| events.watch   | premium   | $500      | —             | 68             | 37     | 6      | name.com          |
| letsgo.watch   | available | $4.99     | —             | 57             | 31     | 7      | name.com          |
| time.watch     | resell    | —         | —             | 92             | 46     | 4      | Porkbun LLC       |
| William.watch  | premium   | $138.60   | $138.60       | 74             | 31     | 7      | namecheap         |
| maps.watch     | available | $4.99     | —             | 56             | 31     | 4      | name.com          |
| ever.watch     | resell    | —         | —             | 86             | 41     | 4      | Porkbun LLC       |
| SanDiego.watch | premium   | $78.54    | $78.54        | 74             | 29     | 9      | namesilo          |
| spaces.watch   | available | $4.99     | —             | 54             | 30     | 6      | name.com          |
| coins.watch    | resell    | —         | —             | 56             | 41     | 5      | Dynadot Inc       |
| heroes.watch   | premium   | $82.50    | —             | 68             | 29     | 6      | name.com          |
| blocks.watch   | available | $4.99     | —             | 53             | 29     | 6      | name.com          |
| perfect.watch  | resell    | —         | —             | 92             | 39     | 7      | Porkbun LLC       |
| photos.watch   | premium   | $500      | —             | 54             | 28     | 6      | name.com          |
| Jim.watch      | available | $56.98    | —             | 78             | 28     | 3      | namecheap         |
| stories.watch  | resell    | —         | —             | 58             | 36     | 7      | Dynadot Inc       |
| systems.watch  | premium   | $250      | —             | 46             | 27     | 7      | name.com          |
| sites.watch    | available | $4.99     | —             | 53             | 26     | 5      | name.com          |
| anything.watch | resell    | —         | —             | 68             | 31     | 8      | Sav.com, LLC - 36 |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 11,596 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/watch?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_watch_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/watch?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_watch_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_watch_oneword_domains&utm_content=related_pricing)

## 🧱 Field summary

- `domain` — Fully qualified domain name.
- `status` — Current acquisition state for the domain in the public extract.
- `purchase_price` — Visible purchase price when available.
- `renewal_price` — Visible renewal price when available.
- `attractiveness` — Composite naming score used as a decision-support signal.
- `demand` — Relative buyer-pressure score when available.
- `length` — Character count without the TLD.
- `registrar` — Registrar name when known.
- `created_at` — Creation timestamp when known.
- `expires_at` — Expiry timestamp when known.

See [DATA_DICTIONARY.md](./DATA_DICTIONARY.md) for full definitions and types.

## ⚠️ Methodology and caveats

This selection is entirely made up of one-word .watch domains. The set leans niche by extension, so the main question is whether the keyword and the .watch ending reinforce each other. Names such as compact.watch, appeal.watch, desk.watch, and premium.watch read clearly and can feel direct, but relevance varies by use case. For founders, the best options are usually the words that are easy to say, easy to remember, and naturally suited to a watch-focused brand or content angle. For investors, the cleaner opportunities are typically keywords with obvious commercial meaning, sensible ask levels, and a renewal profile that does not erode the entry price advantage.

- Prefer words that read naturally before .watch
- Use median ask 13.46 as a rough price anchor
- Check whether the keyword fits a watch-specific use
- Avoid words with weak meaning or legal ambiguity

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .WATCH One-Word Domains*. Version 2026-05-06. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .WATCH page](https://unique.domains/domains/tld/watch?utm_source=github&utm_medium=referral&utm_campaign=repo_watch_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_watch_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_watch_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_watch_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
