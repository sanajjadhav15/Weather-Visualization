# 🌦️ Weather Data Visualization with Python

This project visualizes weather data such as daily **high and low temperatures** and **precipitation** for different locations using Python and Matplotlib. It's inspired by exercises from *Python Crash Course* by Eric Matthes and extended with a dataset for Mumbai.

---

## 📊 Visualizations

Each Jupyter Notebook generates a line chart showing:
- **Death Valley, USA (2018)**: Daily high and low temperatures.
- **Sitka, Alaska (2018)**: Daily high and low temperatures.
- **Mumbai, India**: Daily precipitation levels (rainfall).

Charts include:
- Temperature/precipitation over time
- Color-coded highs, lows, and precipitation
- Shaded area between highs and lows
- Proper date formatting and labeling

---

## 🧰 Technologies Used

- **Python 3.8+**
- **Jupyter Notebook**
- **matplotlib**
- **csv**
- **datetime**

---

## ▶️ How to Run

1. Clone this repo:
   ```bash
   git clone https://github.com/sanajjadhav15/Weather-Visualization.git

2. Open in Jupyter

3. Run the .ipynb notebooks to view the visualizations.

## 📌 Notes

- The project consists of individual Jupyter notebooks for each location's data.
- All datasets are stored in the `data/` folder and read using Python’s built-in `csv` module.
- The **Mumbai precipitation notebook** handles potential missing or inconsistent values gracefully using `try/except`.
- Date strings from the CSV files are parsed using Python’s `datetime` module to allow proper plotting on the x-axis.
- The visualizations use `matplotlib` with the `seaborn-v0_8` style for cleaner plots.
- Each chart uses:
  - A red line for high temperatures
  - A blue line for low temperatures
  - A shaded region between highs and lows (or below precipitation line) to emphasize the range
- X-axis labels are rotated for better readability using `fig.autofmt_xdate()`.
- The notebooks are designed to be beginner-friendly and easy to extend for more datasets or comparisons.

## 📚 Credits

- 📘 *Python Crash Course* by [Eric Matthes](https://nostarch.com/pythoncrashcourse2e) — for project inspiration and base datasets (Sitka and Death Valley weather data).
- 🌐 [NOAA National Centers for Environmental Information (NCEI)](https://www.ncei.noaa.gov/) — for official weather datasets.
- 🌧️ Mumbai rainfall data — self-collected/sample data for practice purposes.
- 📊 Visualizations — created using [Matplotlib](https://matplotlib.org/) and Python standard libraries (`csv`, `datetime`).
