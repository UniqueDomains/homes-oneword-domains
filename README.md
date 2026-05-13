# Available .HOMES One-Word Domains (11,483)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-11%2C483%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .homes one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **11,483 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 11,483 domains · **Median ask:** $125.27 · **High-demand under $2,500:** 0

**Last updated:** 2026-05-13  
**Canonical page:** `https://unique.domains/domains/tld/homes`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/homes?utm_source=github&utm_medium=referral&utm_campaign=repo_homes_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./homes.csv">CSV</a> / <a href="./homes.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_homes_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_homes_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .HOMES search](https://unique.domains/domains/tld/homes?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_homes_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .HOMES search](https://unique.domains/domains/tld/homes?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_homes_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_homes_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .HOMES one-word domain catalog.

### Files

- `homes.csv` — public CSV extract (1,000 rows)
- `homes.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/homes-oneword-domains/main/homes.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain              | status    | ask_price | renewal_price | attractiveness | demand | length | registrar       |
| ------------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | --------------- |
| barup.homes         | available | $1.99     | —             | 82             | 2      | 6      | name.com        |
| geton.homes         | available | $1.99     | —             | 82             | 10     | 6      | name.com        |
| getup.homes         | available | $1.99     | —             | 82             | 14     | 6      | name.com        |
| pierogi.homes       | available | $1.99     | —             | 82             | 7      | 7      | name.com        |
| dogsick.homes       | available | $1.99     | —             | 90             | 1      | 7      | name.com        |
| getlife.homes       | available | $1.99     | —             | 80             | 5      | 8      | name.com        |
| leaveon.homes       | available | $1.99     | —             | 80             | 1      | 8      | name.com        |
| presents.homes      | available | $1.99     | —             | 80             | 9      | 8      | name.com        |
| Snickers.homes      | available | $19.98    | —             | 80             | 10     | 8      | namecheap       |
| FabFour.homes       | available | $1.99     | —             | 82             | 3      | 8      | name.com        |
| surebet.homes       | available | $1.99     | —             | 82             | 8      | 8      | name.com        |
| winners.homes       | available | $1.99     | —             | 60             | 81     | 7      | name.com        |
| woo.homes           | resell    | —         | —             | 67             | 83     | 3      | Spaceship, Inc. |
| CocaCola.homes      | premium   | $2,800    | $2,800        | 92             | 82     | 9      | namecheap       |
| makers.homes        | available | $1.99     | —             | 62             | 67     | 6      | name.com        |
| chatbot.homes       | resell    | —         | —             | 82             | 40     | 7      | Spaceship, Inc. |
| nets.homes          | premium   | $2,500    | —             | 54             | 81     | 4      | name.com        |
| keepthechange.homes | available | $1.99     | —             | 46             | 59     | 15     | name.com        |
| partners.homes      | resell    | —         | —             | 61             | 32     | 8      | Dynadot LLC     |
| online.homes        | premium   | $2,500    | —             | 70             | 62     | 7      | name.com        |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 11,483 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/homes?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_homes_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/homes?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_homes_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_homes_oneword_domains&utm_content=related_pricing)

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

This selection is entirely focused on one-word .homes domains. The set spans literal words, action words, and more flexible brandables such as getup.homes, useit.homes, dogsit.homes, and forces.homes. For founders, the main question is whether the word feels memorable and credible with the .homes ending. For investors, the key test is whether the ask leaves room for resale relative to renewal burden and buyer demand. With a median ask of 125.27, many names sit in impulse-buy territory, but quality still varies sharply. Prioritize clean spelling, broad housing relevance, and words that read naturally before the extension.

- Check whether the word reads naturally with .homes
- Favor clean spelling and clear pronunciation
- Compare ask price against likely renewal burden
- Watch for trademark and narrow-use wording

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .HOMES One-Word Domains*. Version 2026-05-13. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .HOMES page](https://unique.domains/domains/tld/homes?utm_source=github&utm_medium=referral&utm_campaign=repo_homes_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_homes_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_homes_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_homes_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
