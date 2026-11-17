# The Bitcoinionaire Vetted Index (open edition, v1.3)

A dated, source-checked register of whether named luxury brands accept Bitcoin and other cryptocurrency, **read on each company's own website**, not taken from press coverage.

- **Publisher:** [Bitcoinionaire](https://bitcoinionaire.com), a luxury publication for buyers who hold Bitcoin
- **Live register:** https://bitcoinionaire.com/vetted-index/ (re-checked continuously; 132 entries as of 17 November 2026)
- **This file:** `vetted-index-v1-3.csv`, version 1.3, cut 22 August 2026: **101 entries** (25 verified, 72 unverified, 4 indirect)
- **Method:** [The Acceptance Standard](https://bitcoinionaire.com/acceptance-standard/), with a four-value status vocabulary and six decay rules
- **Corrections:** every correction is public at https://bitcoinionaire.com/correction-log/
- **Licence:** CC BY 4.0 (see `LICENSE`). Later editions (v1.4 onward) and the monthly change feed are licensed separately: https://bitcoinionaire.com/license/
- **Also on Hugging Face:** https://huggingface.co/datasets/bitcoinionaire/vetted-index

## Why it exists
Most published lists of "luxury brands that accept Bitcoin" carry no dates, no sources and no method. They are assembled from press coverage, and a claim that was true in 2022 sits unchallenged years later. Each row here records the source that was read, the date it was read, and a plain statement when acceptance could not be confirmed.

## Columns
| column | meaning |
|---|---|
| `id` | stable entry number |
| `name` | brand, dealer or service |
| `category` | e.g. Private Aviation, Watches & Timepieces, Real Estate |
| `status` | `verified` (stated on the company's own site at the date shown), `unverified` (could not be confirmed at source; the finding says why), `indirect` (a settlement route through a dealer, processor or OTC desk rather than direct acceptance) |
| `currencies` | coins named by the source, where stated |
| `last_checked` | ISO date of the check |
| `source_url` | the page that was read |
| `finding` | what the source said, or why it could not be confirmed |

## How to cite
> Bitcoinionaire. *The Bitcoinionaire Vetted Index*, version 1.3, 22 August 2026. 101 entries, of which 25 verified against a first-party source. Available at https://bitcoinionaire.com/vetted-index/

Figures move as entries are re-checked. Cite this version when the figures must stay fixed, and the live page when you want the current record.
