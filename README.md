[![Python CI](https://github.com/shreyapatil9480/pm-analytics-synthetic/actions/workflows/python-ci.yml/badge.svg)](https://github.com/shreyapatil9480/pm-analytics-synthetic/actions/workflows/python-ci.yml)
![Python](https://img.shields.io/badge/python-3.11-blue)
![pytest](https://img.shields.io/badge/tested%20with-pytest-0A9EDC)

# Pm Analytics Synthetic

What predicts satisfied enterprise clients?

**Stakeholder:** Account Director

## Key Insights

- Response times over 24 hours reduce satisfaction by 19 points NPS.
- More than 2 escalations per quarter predicts dissatisfaction.
- Clients with NPS above 40 rarely escalate support issues.

## Dataset

Primary file: `data/client_satisfaction.csv`  
Target variable: `satisfied`

## Getting Started

```bash
pip install -r requirements.txt
jupyter notebook notebooks/analysis.ipynb
```



## Testing

```bash
pip install -r requirements.txt
pytest tests/ --cov=src
```

## Next Steps

Automate SQL exports into a weekly stakeholder report.

---
*Analytics portfolio project — 2025-08*

<!-- build 5 -->

### Implemented

```bash
pip install -r requirements.txt
python scripts/weekly_report.py
```
