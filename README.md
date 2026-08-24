# Available .HOMES One-Word Domains (17,775)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-17%2C775%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .homes one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **17,775 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 17,775 domains · **Median ask:** $105.21 · **High-demand under $2,500:** 16

**Last updated:** 2026-08-24
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

- `homes.csv`, public CSV extract (1,000 rows)
- `homes.json`, public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/homes-oneword-domains/main/homes.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain         | status    | ask_price | renewal_price | attractiveness | demand | length | registrar                                    |
| -------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | -------------------------------------------- |
| but.homes      | available | $1.99     | —             | high           | low    | 3      | name.com                                     |
| broad.homes    | resell    | $1.99     | $20.99        | high           | low    | 5      | Spaceship, Inc.                              |
| all.homes      | premium   | $812.50   | $812.50       | high           | medium | 3      | name.com                                     |
| cxv.homes      | available | $1.80     | $19.98        | low            | low    | 3      | namecheap                                    |
| silly.homes    | resell    | $1.99     | $20.99        | high           | low    | 5      | Spaceship, Inc.                              |
| Ava.homes      | premium   | $812.50   | —             | high           | medium | 3      | name.com                                     |
| dig.homes      | available | $1.99     | $15.75        | high           | low    | 3      | namesilo                                     |
| inviting.homes | resell    | $1.99     | —             | high           | low    | 8      | Go Daddy, LLC                                |
| bed.homes      | premium   | $812.50   | —             | high           | low    | 3      | name.com                                     |
| err.homes      | available | $1.99     | $15.75        | high           | low    | 3      | namesilo                                     |
| ant.homes      | resell    | —         | —             | high           | medium | 3      | Xiamen ChinaSource Internet Service Co., Ltd |
| cut.homes      | premium   | $812.50   | $20.99        | high           | low    | 3      | name.com                                     |
| hic.homes      | available | $1.99     | —             | high           | low    | 3      | name.com                                     |
| atp.homes      | resell    | —         | —             | medium         | low    | 3      | Dynadot LLC                                  |
| inc.homes      | premium   | $812.50   | —             | medium         | low    | 3      | name.com                                     |
| low.homes      | available | $1.99     | —             | high           | low    | 3      | name.com                                     |
| cap.homes      | resell    | —         | —             | high           | low    | 3      | Global Domains International, Inc.           |
| law.homes      | premium   | $845      | $15.73        | high           | medium | 3      | namecheap                                    |
| NYT.homes      | available | $1.99     | —             | high           | low    | 3      | name.com                                     |
| egg.homes      | resell    | —         | —             | high           | low    | 3      | Spaceship, Inc.                              |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 17,775 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 16 high-demand names under $2,500          |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/homes?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_homes_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/homes?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_homes_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_homes_oneword_domains&utm_content=related_pricing)

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

See [DATA_DICTIONARY.md](./DATA_DICTIONARY.md) for full definitions and types.

## ⚠️ Methodology and caveats

This list covers one-word .homes domain names — a mix of compound phrases, everyday words, and brand-style terms suited to real estate, lifestyle, and community-driven projects. With a median asking price near $186, the set spans budget-friendly picks to higher-value names carrying stronger brand recognition. Some entries include well-known terms or trademarked-adjacent phrases, which merit extra scrutiny before acquisition. Reviewing pricing, renewal cost, and brandability side by side helps identify which names offer the best fit for a real estate brand or a long-term investment hold.

- 11,487 one-word .homes domains in this set
- Median asking price near $186 across the list
- Mix of compounds, phrases, and brand-style terms
- Some names carry trademark-adjacent risk — review closely

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .HOMES One-Word Domains*. Version 2026-08-24. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .HOMES page](https://unique.domains/domains/tld/homes?utm_source=github&utm_medium=referral&utm_campaign=repo_homes_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_homes_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_homes_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_homes_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
