# Available .DEV One-Word Domains (65,271)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-65%2C271%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .dev one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **65,271 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 65,271 domains · **Median ask:** $83.76 · **High-demand under $2,500:** 0

**Last updated:** 2026-07-07
**Canonical page:** `https://unique.domains/domains/tld/dev`
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/dev?utm_source=github&utm_medium=referral&utm_campaign=repo_dev_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./dev.csv">CSV</a> / <a href="./dev.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_dev_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_dev_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .DEV search](https://unique.domains/domains/tld/dev?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_dev_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .DEV search](https://unique.domains/domains/tld/dev?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_dev_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_dev_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .DEV one-word domain catalog.

### Files

- `dev.csv`, public CSV extract (1,000 rows)
- `dev.json`, public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/dev-oneword-domains/main/dev.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain        | status    | ask_price | renewal_price | attractiveness | demand | length | registrar                                                 |
| ------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | --------------------------------------------------------- |
| inon.dev      | available | $14.99    | —             | medium         | low    | 5      | name.com                                                  |
| nippy.dev     | resell    | —         | —             | medium         | high   | 5      | Sav.com, LLC                                              |
| lie.dev       | premium   | $198.75   | —             | medium         | low    | 3      | name.com                                                  |
| seemed.dev    | available | $14.99    | —             | low            | low    | 6      | name.com                                                  |
| unify.dev     | resell    | —         | —             | high           | low    | 5      | Global Domains International, Inc. DBA DomainCostClub.com |
| Jews.dev      | premium   | $57.82    | $57.82        | medium         | low    | 4      | namesilo                                                  |
| assuch.dev    | available | $14.99    | —             | medium         | low    | 7      | name.com                                                  |
| chimney.dev   | resell    | —         | —             | high           | low    | 7      | Global Domains International, Inc. DBA DomainCostClub.com |
| week.dev      | premium   | $198.75   | —             | high           | low    | 4      | name.com                                                  |
| beborn.dev    | available | $14.99    | $14.99        | medium         | low    | 7      | namesilo                                                  |
| quartet.dev   | resell    | —         | —             | medium         | low    | 7      | Sav.com, LLC                                              |
| beans.dev     | premium   | $198.75   | $198.75       | high           | high   | 5      | name.com                                                  |
| boarded.dev   | available | $14.99    | $14.99        | medium         | low    | 7      | namesilo                                                  |
| sandbar.dev   | resell    | —         | —             | medium         | high   | 7      | Uniregistrar Corp                                         |
| enemy.dev     | premium   | $106.80   | $106.80       | high           | low    | 5      | namesilo                                                  |
| descend.dev   | available | $14.99    | $14.99        | high           | low    | 7      | namesilo                                                  |
| positives.dev | resell    | —         | —             | low            | low    | 9      | Namecheap Inc.                                            |
| parks.dev     | premium   | $198.75   | —             | medium         | low    | 5      | name.com                                                  |
| howfar.dev    | available | $14.99    | —             | medium         | low    | 7      | name.com                                                  |
| whitehat.dev  | resell    | —         | —             | high           | high   | 9      | Porkbun LLC                                               |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 65,271 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/dev?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_dev_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/dev?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_dev_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_dev_oneword_domains&utm_content=related_pricing)

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

This set of one-word .dev domain names spans everyday English words—christmas.dev, sorry.dev, come.dev, bingo.dev, nothing.dev, easy.dev, pure.dev, special.dev, fancy.dev, and present.dev among them. With a median asking price near $84 across 65,271 domains, these names are largely accessible without heavy negotiation. Their single-word structure and .dev extension make them well suited to developer tools, SaaS products, and technical brands seeking a short, ownable identity.

- Single-word .dev names: easy to spell, say, and remember
- Median asking price near $84 across 65,271 domains
- Developer-focused extension signals technical, builder-friendly brands
- Everyday words like easy, pure, and bingo reduce trademark risk

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .DEV One-Word Domains*. Version 2026-07-07. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .DEV page](https://unique.domains/domains/tld/dev?utm_source=github&utm_medium=referral&utm_campaign=repo_dev_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_dev_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_dev_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_dev_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
