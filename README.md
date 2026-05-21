# State of Biohacking & Longevity

This repository contains the anonymized CSV dataset for Outliyr's State of Biohacking & Longevity report.

Report URL: https://outliyr.com/state-of-biohacking-and-longevity

## Dataset

- File: `state-of-biohacking-and-longevity.csv`
- Format: CSV
- Rows: 75 respondents
- Columns: `response_date` plus survey questions Q1 through Q26
- License: Creative Commons Attribution 4.0 International (CC-BY-4.0)

## Methodology

The dataset comes from an ongoing survey of the Outliyr community. Responses were merged across each respondent's session records to recover their available answer set, then deduplicated by IP address. The published CSV contains 75 respondents who answered at least three core questions.

Reported on an available-case basis: partial responses are included for the questions they answered; each question's n varies (41-77).

The survey is self-selecting and reflects people who chose to participate through Outliyr. It should be treated as directional community data, not a representative population sample.

## Anonymization

The CSV excludes direct submission metadata and higher-risk fields, including IP address, user agent, raw metadata, derived totals, and free-text bonus questions. Multi-select answers are joined with `; `.

## DOI & Mirrors

- DOI (always latest version): https://doi.org/10.5281/zenodo.20320083
- Hugging Face: https://huggingface.co/datasets/nick-urban/state-of-biohacking-and-longevity

## Citation

If you use this dataset, cite:

Urban, Nick / Outliyr. State of Biohacking & Longevity. https://outliyr.com/state-of-biohacking-and-longevity
