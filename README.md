# Zomato Restaurant Data Analysis 📊

## 📌 Project Overview
This project analyzes Zomato restaurant data to understand customer preferences, dining trends, and the competitive landscape of restaurants in Bengaluru. The analysis focuses on rating distributions, online order impacts, and cost preferences.

## 📂 Dataset
The dataset contains information on various restaurants, including:
* **Votes & Ratings**
* **Approx. Cost for Two**
* **Online Ordering Availability**
* **Restaurant Type** (Buffet, Dining, Cafe, etc.)

## 🛠️ Tech Stack
* **Language:** Python
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn

## 🔑 Key Insights
Based on the Exploratory Data Analysis (EDA), the following trends were identified:

1.  **Dining is Dominant:** Dining-out remains the most preferred restaurant type compared to cafes or delivery-only spots.
2.  **Top Contenders:** There is high competition between *Onesta*, *Empire Restaurant*, and *Meghana Foods* for the highest number of votes.
3.  **Pricing Sweet Spot:** Couples prefer restaurants where the approximate cost for two is around **₹300**.
4.  **Online vs. Offline:**
    * The majority of restaurants listed do *not* offer online ordering.
    * **Crucial Insight:** Restaurants that accept online orders generally have higher ratings than those that are offline-only.
5.  **Rating Distribution:** Most restaurant ratings fall between **3.5 and 4.0**.

## 📊 Visualizations
*Included in the notebook are visualizations for:*
* Impact of online ordering on ratings (Boxplot)
* Top 10 restaurants by votes (Bar Chart)
* Heatmap of Restaurant Type vs. Online Ordering availability

## 🚀 How to Run
1. Clone the repository.
2. Install the required libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn
