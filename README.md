# Md Shahiduzzaman

**Business Analytics and Data Analytics** · Queens, New York, USA

I build reproducible analyses of U.S. public data. Each project starts from a
decision someone would actually make, states what the evidence can and cannot
support, and publishes every figure from a recorded run.

My background is in public administration, and I am completing a Master of
Science in Business Analytics at Trine University. That combination is the
thing I find most useful: public administration is largely about how
organisations decide, and analytics is about what they decide with.

---

## Completed projects

| Project | Question it answers | Result |
| --- | --- | --- |
| [U.S. Retail Sales Forecasting](https://github.com/shahiduzzamansony/us-retail-sales-forecasting) | Which U.S. retail categories show predictable monthly patterns, and how accurately can a simple model… | **1.41%** — held-out WAPE, most predictable category |
| [U.S. Consumer Complaint Intelligence](https://github.com/shahiduzzamansony/us-consumer-complaint-intelligence) | What reported product and issue patterns should a customer experience team investigate, and can complaint… | **0.951** — held-out macro-F1, narrative routing |
| [NYC Taxi Demand and Revenue Analysis](https://github.com/shahiduzzamansony/nyc-taxi-demand-and-revenue) | Which pickup-zone and time combinations have consistent recorded activity and fare patterns, and how well… | **3.22** — held-out MAE, pickups per zone-hour |
| [U.S. Workforce Location Strategy](https://github.com/shahiduzzamansony/us-workforce-location-strategy) | Which selected U.S. counties offer different combinations of industry employment scale, concentration,… | **48,360** — workers in the most specialised county studied |


Every figure in the Result column is read from that project's own `reports/metrics.json`, produced by executing its pipeline. 4 of 10 planned projects are complete; the rest are not listed until they have produced measured results.

---

## How these are built

Every repository follows the same discipline:

- **Real data, acquired by code.** Each project downloads from the official
  source, records the URL, retrieval time, SHA-256 and row counts, and
  reconciles what it received against the provider's own count where one
  exists.
- **A data contract that stops the build.** A missing month, a duplicated
  grain, a suppressed value that survived as a zero — these raise rather than
  producing a confident wrong number.
- **Named denominators.** Every rate states the population it is a share of,
  in the output rather than in a footnote.
- **Honest evaluation.** Chronological splits, a baseline that is genuinely
  hard to beat, and a loss reported as a loss.
- **Limitations that are specific.** Each project says what its data cannot
  answer, not just what it can.

Results carry a run identifier tying them to a manifest with the configuration,
source checksums, package versions and code commit. Metrics that could not be
measured are absent rather than estimated.

---

## Tools shown in the linked work

`DuckDB` · `Parquet` · `Plotly` · `Python` · `SQL` · `Streamlit` · `matplotlib` · `openpyxl` · `pandas` · `scikit-learn` · `statsmodels`

Listed only where a linked repository actually uses the tool.

---

## Elsewhere

- **Portfolio:** https://shahiduzzamansony.github.io/
- **Email:** shahiduzzamansony2703@gmail.com
- **LinkedIn:** https://www.linkedin.com/in/md-shahiduzzaman-a80231241/
- **Google Scholar:** https://scholar.google.com/citations?user=etBV2wQAAAAJ&hl=en

---

*These are independent case studies. No organisation commissioned, reviewed or
endorsed them, and the stakeholders they describe are scoping devices rather
than people who were consulted. Earlier web-development work from 2022 remains
in the repository list; the analytics projects above are the current work.*
