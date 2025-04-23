# 🌍 CO₂ Emission Analysis

This project explores global CO₂ emissions and their relationship with energy consumption, GDP, and the warming effects of various greenhouse gases over time. Using data visualization and statistical analysis, it identifies trends, correlations, and insights into emission patterns across countries and time.

## 📁 Dataset

- **Source:** Our World in Data (OWID)
- **Dataset URL:** [owid-co2-data.csv](https://raw.githubusercontent.com/Rajput-Vivek-16/CO2-Emission-Analysis-IDS/main/owid-co2-data.csv)

The dataset includes variables such as:
- Total and per capita CO₂ emissions
- Emissions from coal, oil, gas, cement, and flaring
- Methane and nitrous oxide emissions
- Greenhouse gas temperature change estimates
- Population, GDP, and energy use

## 📊 Key Analyses

- **CO₂ Emissions vs. Energy Use per Capita:** Shows a positive correlation and highlights energy-efficient vs fossil-fuel-heavy nations.
- **Oil vs. Coal Economies:** Compares emissions patterns based on primary fuel dependency.
- **GHG Emission Contribution Over Time:** Stacked plots show how CO₂, CH₄, and N₂O contribute to total GHG levels.
- **Temperature Impact per kg of Gas:** Normalized plots reveal CH₄ and N₂O have much higher warming effects per kg than CO₂.
- **Bubble Plots:** Multivariate visualizations comparing emissions and temperature with bubble size or color for an additional variable.

## 🛠️ Tools & Libraries

- Python 3.7+
- Jupyter Notebook
- Libraries:
  - pandas
  - numpy
  - matplotlib
  - plotly (express and graph_objects)
  - dash

Install them using:

```bash
pip install -r requirements.txt
```

## 📌 Insights
- High emissions don’t always correlate with high temperature impacts.
- Methane and nitrous oxide are significantly more potent than CO₂ on a per-kg basis.
- Clean energy transitions can allow high energy use with lower CO₂ output.

## 📬 Contact
For any suggestions or queries, feel free to raise an issue.

