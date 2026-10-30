# NSW Road Safety Dashboard

An interactive dashboard for NSW crash hotspots, time patterns, school-zone exposure and intervention planning.

**Technologies:** Python · Streamlit · pandas · Plotly · PyDeck

## What is included

- Five views covering overview, hotspots, temporal risk, external conditions and decisions.
- Filters for location, crash outcome, school zones and speed limits.
- Maps, visual summaries and explicitly hypothetical intervention scenarios.

## Setup

```bash
python3.11 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

## Run

```bash
streamlit run app.py
```

The included CSVs support the local dashboard. Original source attribution: https://data.nsw.gov.au/data/dataset/2-nsw-crash-data. Scenario sliders illustrate assumptions and do not establish causal effects.

## Source and credits

This portfolio snapshot preserves work from the following repositories. Existing author credits, citations and license files are retained; team and upstream code are not presented as solely authored work.

- https://github.com/Qimatxbase/DVN
- https://github.com/lLuckil/36104_DVN_AT3_G22

[Portfolio index](https://github.com/Qimatxbase/engineering_portfolio)
