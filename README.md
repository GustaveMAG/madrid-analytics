
<div align="center">

# 🇪🇸 📊 Madrid City Analytics

**A 360° Exploratory Data Analysis (EDA) of the Spanish Capital.**
<br>
*Mobility, Safety, Environment, Tourism, and Quality of Life.*

[![Python](https://img.shields.io/badge/Python-3.10%2B-blue?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Notebook-Jupyter-orange?style=for-the-badge&logo=jupyter&logoColor=white)](https://jupyter.org/)
[![Pandas](https://img.shields.io/badge/Data-Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org/)

[Overview](#-overview) • [Datasets](#-datasets) • [Key Insights](#-key-insights) • [Installation](#-installation)

</div>

---

## 📖 Overview

This project aims to decode the urban dynamics of **Madrid** by cross-referencing heterogeneous datasets. The goal is to understand how environmental factors (weather, pollution) interact with social life (tourism, cultural events) and public safety (accidents, crime).

The core of the project lies in the `EDA_Project_on_Madrid.ipynb` notebook, which cleans, merges, and visualizes this data to extract actionable insights.

## 📂 Datasets

To keep the repository clean, all raw data is compressed in the **`Datasets in Madrid analysis.zip`** file. Once extracted, it provides the following CSV files:

| Category | File | Description |
| :--- | :--- | :--- |
| **Safety** | `madrid_crime_dataset_2019_2022.csv` | Crime stats by district and type. |
| **Safety** | `2025_Accidentalidad.csv` | Detailed traffic accident data. |
| **Emergency** | `ActuacionesBomberos_2025.csv` | Fire department interventions. |
| **Environment** | `MadridPolution2001-2022...csv` | Air quality and pollutants by district. |
| **Weather** | `weather_madrid_2019-2022.csv` | Temperatures, precipitation, and conditions. |
| **Mobility** | `bases_bicimad.csv` | Location and usage of BiciMAD (bike sharing) stations. |
| **Tourism** | `tourist_arrivals_madrid.csv` | Inbound tourist flow statistics. |
| **Housing** | `airbnb_reservations_madrid.csv` | Short-term rental market data. |
| **Culture** | `300107-0-agenda-actividades...csv` | Agenda of cultural events and activities. |

## 🔍 Key Insights & Analysis

The notebook explores several correlations and trends:

1.  **Weather Impact:** Correlation between weather conditions (rain, fog) and the frequency of traffic accidents or fire department interventions.
2.  **Air Quality:** Analysis of pollution trends over the years and identification of "Hotspot" districts.
3.  **Tourism & Gentrification:** Correlating tourist arrivals with Airbnb reservations and crime rates in central areas.
4.  **Urban Mobility:** Study of the distribution of BiciMAD stations in relation to cultural activity zones.

## 🛠️ Installation & Usage

### 1. Clone the repository
```bash
git clone [https://github.com/GustaveMAG/madrid-analytics.git](https://github.com/GustaveMAG/madrid-analytics.git)
cd madrid-analytics
````

### 2\. Set up Virtual Environment (Recommended)

```bash
python -m venv venv
# Windows:
.\venv\Scripts\activate
# Mac/Linux:
source venv/bin/activate
```

### 3\. Install dependencies

Ensure you have the necessary libraries installed:

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### 4\. Unzip and Run

Unzip `Datasets in Madrid analysis.zip` into the project folder, then start Jupyter:

```bash
jupyter notebook "EDA_Project_on_Madrid.ipynb"
```

## 📊 Tech Stack

  * **Python**: Primary language.
  * **Pandas & NumPy**: Data manipulation and cleaning.
  * **Matplotlib & Seaborn**: Data visualization (Charts, Heatmaps).
  * **Jupyter Notebook**: Interactive development environment.

-----


