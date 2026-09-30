# Available .WATCH One-Word Domains (26,762)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-26%2C762%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .watch one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **26,762 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 26,762 domains · **Median ask:** $11.18 · **High-demand under $2,500:** 1

**Last updated:** 2026-09-30
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

- `watch.csv`, public CSV extract (1,000 rows)
- `watch.json`, public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/watch-oneword-domains/main/watch.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain        | status    | ask_price | renewal_price | attractiveness | demand | length | registrar                                                 |
| ------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | --------------------------------------------------------- |
| abm.watch     | available | $5.99     | $44.49        | high           | low    | 3      | namesilo                                                  |
| fresh.watch   | resell    | $4.99     | —             | high           | medium | 5      | Sav.com, LLC                                              |
| his.watch     | premium   | $118.80   | $118.80       | high           | low    | 3      | namesilo                                                  |
| adr.watch     | available | $3.48     | $56.98        | high           | low    | 3      | namecheap                                                 |
| lonely.watch  | resell    | $4.99     | —             | high           | low    | 6      | name.com                                                  |
| llp.watch     | premium   | $118.80   | $118.80       | high           | low    | 3      | namesilo                                                  |
| aes.watch     | available | $2.79     | $35.39        | high           | low    | 3      | spaceship                                                 |
| account.watch | resell    | $4.99     | —             | high           | low    | 7      | Spaceship, Inc.                                           |
| ngo.watch     | premium   | $512      | $512          | high           | low    | 3      | namesilo                                                  |
| ana.watch     | available | $5.50     | —             | high           | low    | 3      | unstoppable                                               |
| ask.watch     | resell    | —         | —             | high           | medium | 3      | NameSilo, LLC                                             |
| anne.watch    | premium   | $78.54    | $78.54        | high           | low    | 4      | namesilo                                                  |
| con.watch     | available | $5.50     | —             | high           | low    | 3      | unstoppable                                               |
| sell.watch    | resell    | —         | —             | high           | medium | 4      | Global Domains International, Inc. DBA DomainCostClub.com |
| jeff.watch    | premium   | $42.90    | $42.90        | high           | medium | 4      | namecheap                                                 |
| dre.watch     | available | $2.79     | $35.39        | high           | low    | 3      | spaceship                                                 |
| soft.watch    | resell    | —         | —             | high           | low    | 4      | Dynadot Inc                                               |
| cooks.watch   | premium   | $66.50    | —             | medium         | low    | 5      | unstoppable                                               |
| ein.watch     | available | $3.48     | $56.98        | high           | low    | 3      | namecheap                                                 |
| alpha.watch   | resell    | —         | —             | high           | medium | 5      | Spaceship, Inc.                                           |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 26,762 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 1 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/watch?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_watch_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/watch?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_watch_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_watch_oneword_domains&utm_content=related_pricing)

## 🧱 Field summary

- `domain`, Fully qualified domain name.
- `status`, Current acquisition state for the domain in the public extract.
- `purchase_price`, Visible purchase price when available.
- `renewal_price`, Visible renewal price when available.
- `attractiveness`, Public composite naming band used as a decision-support signal.
- `demand`, Public buyer-pressure band when available.
- `length`, Character count without the TLD.
- `registrar`, Registrar name when known.
- `created_at`, Creation timestamp when known.
- `expires_at`, Expiry timestamp when known.
- `status_verified_at`, When status was last established against the registry. Null means never checked.

See [DATA_DICTIONARY.md](./DATA_DICTIONARY.md) for full definitions and types.

## ⚠️ Methodology and caveats

This set covers 11,603 one-word domain names on the .watch extension, ranging from everyday words like coffeeberry.watch and getmoving.watch to distinctive names like DaffyDuck.watch and JollyRoger.watch. With a median asking price near $14.68, most names in this selection are priced for quick, low-risk acquisition. Single-word .watch domains suit media, time-related, and lifestyle branding, and the shorter the word, the easier it is to recall and register consistently across channels. Because pricing updates daily, this list reflects current market asks rather than stale listings.

- 11,603 one-word domain names built on the .watch extension
- Median asking price near $14.68 keeps entry costs low
- Short, single-word names are easy to brand and remember
- Updated daily so pricing reflects current market asks

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The snapshot date above is when this file was written, not when each row was checked. Read `status_verified_at` for that: a name whose status was last established months ago is exported with its real date rather than the snapshot's.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .WATCH One-Word Domains*. Version 2026-09-30. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .WATCH page](https://unique.domains/domains/tld/watch?utm_source=github&utm_medium=referral&utm_campaign=repo_watch_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_watch_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_watch_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_watch_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `kai@unique.domains`
