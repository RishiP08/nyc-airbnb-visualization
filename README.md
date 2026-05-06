# NYC Airbnb Data Analysis & Visualization

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Pandas](https://img.shields.io/badge/Pandas-1.3+-green.svg)
![Plotly](https://img.shields.io/badge/Plotly-5.0+-orange.svg)
![License](https://img.shields.io/badge/License-MIT-yellow.svg)
![Platform](https://img.shields.io/badge/Platform-Google%20Colab-red.svg)

> Exploratory Data Analysis and interactive visualization of 48,000+ Airbnb listings across New York City using Python.

---

## Project Overview

This project performs an end-to-end **Exploratory Data Analysis (EDA)** on the NYC Airbnb Open Data (2019) to uncover pricing trends, neighborhood patterns, room type distributions, and host behavior across all five NYC boroughs — Manhattan, Brooklyn, Queens, the Bronx, and Staten Island.

The highlight of this project is an **interactive geospatial map** built with Plotly, allowing users to visually explore 5,000+ listings across New York City colored by price.

---

## Objectives

- Understand the distribution of Airbnb listings across NYC boroughs
- Analyze pricing trends and factors that affect price
- Identify the most expensive and busiest neighborhoods
- Visualize geographic patterns of listings using an interactive map
- Explore correlations between key numerical features

---

##  Visualizations Included

| # | Visualization | Library |
|---|---|---|
| 1 | Listings distribution by Borough (Bar + Pie) | Matplotlib, Seaborn |
| 2 | Price distribution (Histogram + Box Plot) | Matplotlib, Seaborn |
| 3 | Room type count and average price | Seaborn |
| 4 | Top 10 most expensive neighbourhoods | Matplotlib |
| 5 | Correlation heatmap of numerical features | Seaborn |
| 6 | Interactive scatter — Price vs Reviews | Plotly |
| 7 | Interactive geospatial map of listings | Plotly |
| 8 | Availability heatmap by Borough & Room Type | Seaborn |

---

##  Project Structure

```
nyc-airbnb-visualization/
│
├── NYC_Airbnb_Visualization.ipynb   # Main Colab notebook
├── README.md                        # Project documentation
├── requirements.txt                 # Python dependencies
├── LICENSE                          # MIT License
└── assets/
    └── preview.png                  # Preview image of visualizations
```

---

##  Dataset

- **Source:** [NYC Airbnb Open Data — Kaggle](https://www.kaggle.com/datasets/dgomonov/new-york-city-airbnb-open-data)
- **Size:** 48,895 listings
- **Features:** 16 columns including price, location, room type, reviews, availability

| Column | Description |
|---|---|
| `neighbourhood_group` | NYC Borough |
| `neighbourhood` | Specific neighbourhood |
| `latitude / longitude` | Geographic coordinates |
| `room_type` | Entire home, Private room, Shared room |
| `price` | Price per night ($) |
| `number_of_reviews` | Total reviews |
| `availability_365` | Days available per year |

---

## Tech Stack

| Library | Version | Purpose |
|---|---|---|
| `pandas` | 1.3+ | Data loading, cleaning, manipulation |
| `numpy` | 1.21+ | Numerical operations |
| `matplotlib` | 3.4+ | Static charts and plots |
| `seaborn` | 0.11+ | Statistical visualizations |
| `plotly` | 5.0+ | Interactive charts and maps |

---

## Getting Started

### Option 1 — Run on Google Colab (Recommended)

1. Click the link below to open in Colab:

   https://colab.research.google.com/

2. Run all cells — the dataset loads automatically, no download needed.

### Option 2 — Run Locally

```bash
# Clone the repository
git clone https://github.com/YOUR_USERNAME/nyc-airbnb-visualization.git
cd nyc-airbnb-visualization

# Install dependencies
pip install -r requirements.txt

# Launch Jupyter
jupyter notebook NYC_Airbnb_Visualization.ipynb
```

---

## Key Findings

1. **Manhattan dominates** — highest number of listings and significantly higher median price compared to other boroughs
2. **Entire home/apt** listings cost 2–3x more than private rooms on average
3. **Brooklyn** is the second most popular borough for listings
4. **Staten Island and the Bronx** have the highest year-round availability — indicating lower demand
5. **Price and number of reviews** show a weak negative correlation — cheaper listings attract more bookings
6. **Certain neighbourhoods** outside Manhattan (e.g. Fort Wadsworth) still command premium prices

---

##  Preview

> Interactive map and chart previews from the notebook:

- Geographic scatter map of 5,000+ listings colored by price
- Correlation heatmap across all numeric features
- Box plots comparing price distributions across boroughs

---

## Author

**Your Name**
- GitHub: [RishiP08](https://github.com/RishiP08)
- LinkedIn: [Rishi Patel](https://www.linkedin.com/in/patelrishi0801)

---

## License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.

---

## Acknowledgements

- Dataset by [Kaggle — NYC Airbnb Open Data](https://www.kaggle.com/datasets/dgomonov/new-york-city-airbnb-open-data)
- Inspired by open-source EDA projects on Kaggle
