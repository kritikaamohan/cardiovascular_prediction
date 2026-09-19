# 📈 Cardiovascular Disease (CVD) Prophet Forecasting & Risk Analysis

An advanced time-series forecasting and risk-assessment pipeline built using Meta’s **Prophet** model to project cardiovascular disease (CVD) trends, evaluate county-level impacts, and identify high-risk demographic segments through 2030.

---

## 🚀 About the Project
Cardiovascular diseases remain a critical public health challenge. This project leverages time-series analysis and forecasting techniques to model historical CVD incidence data, project future trajectories up to 2030, and isolate high-risk zones and age groups. By breaking down projections into distinct cohorts (such as ages 35–64 and 65+), the project aims to assist healthcare planners and policymakers in targeted resource allocation.

---

## ✨ Key Features
- **Prophet Time-Series Modeling:** Employs additive regression models to capture temporal trends, seasonality, and long-term trajectory shifts.
- **Demographic Segmentation:** Generates separate predictive forecasts for different age brackets (e.g., 35–64 and 65+ cohorts).
- **County-Level Risk Ranking:** Automatically processes model outputs to surface the top 10 high-risk counties for proactive intervention.
- **Validation & Performance Metrics:** Includes systematic tracking of validation errors to ensure forecasting accuracy.

---

## 🛠️ Tech Stack & Libraries
- **Language:** Python
- **Forecasting Engine:** Prophet (Meta / Facebook)
- **Data Manipulation & Analysis:** Pandas, NumPy
- **Visualization:** Matplotlib, Seaborn

---

## 📂 Repository Structure
```text
cardiovascular_prediction/
│
├── data/
│   └── CVD.csv                                 # Main historical CVD dataset
│
├── notebooks/
│   └── CVD_Prophet_Forecasting_2030.ipynb      # Core exploratory data analysis and forecasting notebook
│
├── outputs/                                    # Generated model forecasts and validation metrics
│   ├── county_forecast_2030_35_64.csv          # Forecasts for the 35–64 age group
│   ├── county_forecast_2030_65_plus.csv        # Forecasts for the 65+ age group
│   ├── top10_high_risk_counties_35_64.csv      # Top 10 high-risk counties (35–64)
│   ├── top10_high_risk_counties_65_plus.csv    # Top 10 high-risk counties (65+)
│   └── validation_metrics.csv                  # Model evaluation performance metrics
│
├── requirements.txt                            # Project dependencies
└── README.md                                   # Project documentation

```

---

## ⚙️ Installation & Setup

Follow these steps to set up and run the project locally:

1. **Clone the repository:**
```bash
git clone [https://github.com/kritikaamohan/cardiovascular_prediction.git](https://github.com/kritikaamohan/cardiovascular_prediction.git)
cd cardiovascular_prediction

```


2. **Create and activate a virtual environment:**
```bash
python -m venv venv
# On Windows:
venv\Scripts\activate
# On macOS/Linux:
source venv/bin/activate

```


3. **Install dependencies:**
```bash
pip install -r requirements.txt

```



---

## 📊 Usage

1. Ensure your historical data file (`CVD.csv`) is placed inside the `data/` directory.
2. Open Jupyter Lab or Notebook to run the forecasting workflow:
```bash
jupyter notebook notebooks/CVD_Prophet_Forecasting_2030.ipynb

```


3. Review the generated forecast CSVs and risk rankings updated dynamically inside the `outputs/` folder.

---

## 🔮 Future Enhancements

* [ ] Integrate external socio-economic and environmental regressors into the Prophet model to improve forecast precision.
* [ ] Build an interactive web dashboard (using Streamlit or Plotly Dash) to visualize county-level risk maps dynamically.
* [ ] Automate the end-to-end pipeline execution using modular Python scripts.

---

## 🤝 Contributing

Contributions, bug reports, and feature requests are welcome! Feel free to open an issue or submit a pull request on the [issues page](https://www.google.com/search?q=https://github.com/kritikaamohan/cardiovascular_prediction/issues&utm_source=gemini).

---

## 📝 License

This project is open-source and available under the [MIT License](https://www.google.com/search?q=LICENSE&utm_source=gemini).

```

```
