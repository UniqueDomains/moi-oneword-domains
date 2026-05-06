# Available .MOI One-Word Domains (10,510)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-10%2C510%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .moi one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **10,510 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 10,510 domains · **Median ask:** $64.22 · **High-demand under $2,500:** 0

**Last updated:** 2026-05-06  
**Canonical page:** `https://unique.domains/domains/tld/moi`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/moi?utm_source=github&utm_medium=referral&utm_campaign=repo_moi_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./moi.csv">CSV</a> / <a href="./moi.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_moi_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_moi_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .MOI search](https://unique.domains/domains/tld/moi?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_moi_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .MOI search](https://unique.domains/domains/tld/moi?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_moi_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_moi_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .MOI one-word domain catalog.

### Files

- `moi.csv` — public CSV extract (1,000 rows)
- `moi.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/moi-oneword-domains/main/moi.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain           | status    | ask_price | renewal_price | attractiveness | demand | length | registrar |
| ---------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | --------- |
| Audi.moi         | premium   | —         | —             | 86             | 69     | 4      | —         |
| Uber.moi         | premium   | —         | —             | 88             | 82     | 4      | —         |
| Cindy.moi        | premium   | —         | —             | 80             | 15     | 5      | —         |
| finals.moi       | available | $25.99    | $25.99        | 80             | 7      | 6      | namesilo  |
| barup.moi        | available | $39.99    | —             | 82             | 2      | 6      | name.com  |
| getup.moi        | available | $39.99    | —             | 82             | 14     | 6      | name.com  |
| kirkland.moi     | available | $39.99    | —             | 74             | 82     | 8      | name.com  |
| our.moi          | premium   | $250      | —             | 64             | 48     | 3      | name.com  |
| jetpack.moi      | available | $39.99    | —             | 82             | 75     | 8      | name.com  |
| its.moi          | premium   | $937.50   | —             | 78             | 43     | 3      | name.com  |
| farmers.moi      | available | $39.99    | —             | 54             | 59     | 7      | name.com  |
| realestate.moi   | premium   | $250      | —             | 77             | 42     | 11     | name.com  |
| team.moi         | available | $39.99    | —             | 76             | 49     | 4      | name.com  |
| foto.moi         | premium   | $250      | —             | 76             | 28     | 4      | name.com  |
| intelligence.moi | available | $39.99    | —             | 84             | 38     | 12     | name.com  |
| SriLanka.moi     | premium   | —         | —             | 68             | 94     | 9      | —         |
| notes.moi        | available | $39.99    | —             | 73             | 37     | 5      | name.com  |
| Philippines.moi  | premium   | —         | —             | 68             | 94     | 11     | —         |
| chatbot.moi      | available | $39.99    | —             | 82             | 36     | 7      | name.com  |
| Netherlands.moi  | premium   | —         | —             | 76             | 93     | 11     | —         |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 10,510 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/moi?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_moi_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/moi?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_moi_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_moi_oneword_domains&utm_content=related_pricing)

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

This selection is entirely focused on .moi domains. The names shown suggest a mix of short generic words, personal names, acronyms, and geo terms, with examples such as tips.moi, Liam.moi, Cindy.moi, and NYC.moi. The median ask is 64.22, which sets a low reference point for initial review. When comparing these domains, focus on whether the word is easy to recognize, easy to say, and commercially usable within a non-mainstream extension. Be stricter with names that match famous brands or protected marks, such as Audi.moi, Sony.moi, or Uber.moi, because legal risk can outweigh price.

- Focus on short, recognizable words and clear personal names
- Use 64.22 as the median ask reference point
- City terms and acronyms can be memorable but narrower
- Avoid obvious trademark conflicts despite low entry prices

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .MOI One-Word Domains*. Version 2026-05-06. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .MOI page](https://unique.domains/domains/tld/moi?utm_source=github&utm_medium=referral&utm_campaign=repo_moi_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_moi_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_moi_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_moi_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
