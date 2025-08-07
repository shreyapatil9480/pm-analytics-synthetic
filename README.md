# Project Management Analytics

This repository contains a synthetic dataset simulating project management metrics and a Jupyter notebook that walks through exploratory data analysis (EDA) and builds a basic predictive model.

## Dataset

The data resides in `synthetic_project_data.csv`. It includes the following columns:

| Column | Description |
|-------|-------------|
| `project_id` | Unique identifier for each project |
| `planned_start` | Planned start date (YYYY-MM-DD) |
| `planned_end` | Planned end date (YYYY-MM-DD) |
| `actual_end` | Actual completion date (YYYY-MM-DD) |
| `planned_duration_days` | Planned duration of the project in days |
| `delay_days` | Difference between planned and actual completion dates (positive = delay, negative = ahead of schedule) |
| `budget` | Planned project budget in USD |
| `actual_cost` | Actual cost incurred in USD |
| `team_size` | Number of people on the project team |
| `complexity` | Project complexity score from 1 (lowest) to 5 (highest) |
| `risk_score` | Continuous risk score between 0 and 1 |
| `success` | Binary indicator where 1 means the project finished within 14 days of the plan and within 10% of budget |

## Getting Started

1. Clone or download this repository.
2. Create a virtual environment (optional) and install dependencies:
   ```bash
   python -m venv venv
   source venv/bin/activate  # on Windows use `venv\Scripts\activate`
   pip install -r requirements.txt
   ```

3. Launch the notebook:
   ```bash
   jupyter notebook analysis.ipynb
   ```

4. Run through the cells to reproduce the exploratory analysis and model results.

## Project Structure

```
.
├── synthetic_project_data.csv
├── analysis.ipynb
├── requirements.txt
└── README.md
```

## Contributing

Feel free to fork this repository, experiment with more advanced models, or extend the dataset with additional features. Pull requests are welcome!

## License

This project is released under the MIT License.
