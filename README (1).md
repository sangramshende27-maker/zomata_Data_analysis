# 🍽️ Zomato Restaurant Data Analysis

A data analysis project exploring restaurant trends, ratings, pricing, and ordering patterns using a Zomato dataset with **148 restaurant entries**.

---

## 📁 Dataset Overview

**File:** `Zomato_data.csv`  
**Records:** ~148 rows  
**Columns:**

| Column | Description |
|---|---|
| `name` | Name of the restaurant |
| `online_order` | Whether online ordering is available (`Yes` / `No`) |
| `book_table` | Whether table booking is available (`Yes` / `No`) |
| `rate` | Customer rating (e.g., `4.1/5`) |
| `votes` | Total number of votes received |
| `approx_cost(for two people)` | Approximate cost in INR for two people |
| `listed_in(type)` | Category of the restaurant (e.g., `Buffet`, `Cafes`, `Dining`) |

---

## 📊 Project Goals

- Analyze the distribution of restaurant ratings and votes
- Compare online ordering vs. dine-in restaurant performance
- Study pricing trends across different restaurant types
- Identify top-rated and most-voted restaurants
- Visualize relationships between cost, rating, and votes
- Explore category-wise (Buffet, Cafes, Dining) breakdowns

---

## 🗂️ Project Structure

```
zomato-data-analysis/
│
├── Zomato_data.csv           # Raw dataset
├── zomato_analysis.ipynb     # Main Jupyter Notebook
├── requirements.txt          # Python dependencies
└── README.md                 # Project documentation
```

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/your-username/zomato-data-analysis.git
cd zomato-data-analysis
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Launch the Notebook

```bash
jupyter notebook zomato_analysis.ipynb
```

---

## 🛠️ Tech Stack

- **Python 3.8+**
- **Pandas** – data loading, cleaning, and manipulation
- **NumPy** – numerical operations
- **Matplotlib / Seaborn** – static data visualizations
- **Plotly** – interactive charts
- **Jupyter Notebook** – interactive analysis environment

---

## 📌 Key Insights (Examples)

- **Dining** is the most common restaurant type, followed by **Cafes** and **Buffet**.
- Restaurants with **online ordering** tend to receive significantly more votes.
- Most restaurants fall in the **₹300–₹800** price range for two people.
- Higher-rated restaurants generally have a greater number of votes, indicating reliability of scores.
- Table booking availability is more common among higher-priced restaurants.

---

## 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you'd like to change.

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).
