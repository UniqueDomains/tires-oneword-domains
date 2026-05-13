# Available .TIRES One-Word Domains (12,795)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-12%2C795%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .tires one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **12,795 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 12,795 domains · **Median ask:** $25.47 · **High-demand under $2,500:** 0

**Last updated:** 2026-05-13  
**Canonical page:** `https://unique.domains/domains/tld/tires`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/tires?utm_source=github&utm_medium=referral&utm_campaign=repo_tires_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./tires.csv">CSV</a> / <a href="./tires.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_tires_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_tires_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .TIRES search](https://unique.domains/domains/tld/tires?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_tires_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .TIRES search](https://unique.domains/domains/tld/tires?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_tires_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_tires_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .TIRES one-word domain catalog.

### Files

- `tires.csv` — public CSV extract (1,000 rows)
- `tires.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/tires-oneword-domains/main/tires.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain             | status    | ask_price | renewal_price | attractiveness | demand | length | registrar   |
| ------------------ | --------- | --------- | ------------- | -------------- | ------ | ------ | ----------- |
| agents.tires       | available | $14.99    | —             | 56             | 50     | 6      | name.com    |
| abc.tires          | resell    | —         | —             | 78             | 50     | 3      | Porkbun LLC |
| matcha.tires       | available | $14.99    | —             | 86             | 39     | 6      | name.com    |
| prompts.tires      | available | $5.99     | $78.99        | 54             | 39     | 7      | namesilo    |
| tokens.tires       | available | $5.99     | $78.99        | 51             | 36     | 6      | namesilo    |
| spectra.tires      | available | $14.99    | —             | 62             | 34     | 7      | name.com    |
| etc.tires          | available | $14.99    | —             | 58             | 34     | 3      | name.com    |
| payments.tires     | available | $14.99    | —             | 58             | 33     | 8      | name.com    |
| teams.tires        | available | $14.99    | —             | 62             | 32     | 5      | name.com    |
| William.tires      | available | $110.98   | —             | 74             | 31     | 7      | namecheap   |
| maps.tires         | available | $14.99    | —             | 56             | 31     | 4      | name.com    |
| slots.tires        | available | $5.99     | $78.99        | 49             | 31     | 5      | namesilo    |
| inspiration.tires  | available | $14.99    | —             | 88             | 30     | 11     | name.com    |
| spaces.tires       | available | $14.99    | —             | 54             | 30     | 6      | name.com    |
| Jim.tires          | available | $110.98   | —             | 78             | 28     | 3      | namecheap   |
| commonground.tires | available | $14.99    | —             | 74             | 28     | 13     | name.com    |
| gems.tires         | available | $5.99     | $78.99        | 70             | 28     | 4      | namesilo    |
| brands.tires       | available | $14.99    | —             | 62             | 28     | 6      | name.com    |
| forms.tires        | available | $14.99    | —             | 54             | 28     | 5      | name.com    |
| KFC.tires          | available | $110.98   | —             | 74             | 27     | 3      | namecheap   |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 12,795 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/tires?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_tires_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/tires?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_tires_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_tires_oneword_domains&utm_content=related_pricing)

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

These domains are all one-word names on the .tires extension. The set includes direct category words such as automobile.tires, broader geographic or market terms like country.tires, and more abstract brandables such as alight.tires or zone.tires. For founders, the main question is whether a name is clear, memorable, and specific enough for a tire business without feeling overly narrow. For investors, the key is whether the word has obvious commercial relevance to tires, auto service, retail, fleet, or aftermarket use. With a median ask near $25, price is less of a filter here than relevance, resale realism, and whether the term creates immediate buyer recognition.

- Direct tire-market terms usually read clearer than abstract words.
- Median ask is about $25, so fit matters more than entry price.
- Check if the word suits retail, service, fleet, or wholesale use.
- Avoid terms with unclear tire relevance or possible trademark overlap.

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .TIRES One-Word Domains*. Version 2026-05-13. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .TIRES page](https://unique.domains/domains/tld/tires?utm_source=github&utm_medium=referral&utm_campaign=repo_tires_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_tires_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_tires_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_tires_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
