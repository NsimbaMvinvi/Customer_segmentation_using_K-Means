# 🧠 E-commerce Customer Segmentation with K-Means

## 📌 Business Problem
In the e-commerce space, understanding customer behavior is key to maximizing revenue and improving the user experience.

Without proper segmentation, companies face:
- Generic, ineffective marketing campaigns
- Low personalization in the customer experience
- Difficulty identifying high-value customers

This directly impacts:
- Lower conversion rates
- Poor customer retention
- Missed growth opportunities

👉 **Solution:** apply clustering techniques to segment customers into homogeneous groups and enable data-driven strategic decisions.

---

## 🎯 Analysis Objectives

### Main objective
Identify customer segments using the **K-Means** algorithm to improve marketing and business decision-making.

### Specific objectives
- Analyze customer behavior based on key variables
- Clean and transform the data
- Explore patterns through exploratory data analysis (EDA)
- Determine the optimal number of clusters (Elbow Method)
- Apply the **K-Means** algorithm
- Interpret and characterize each segment
- Generate actionable business insights

---

## 📊 Data Used

The dataset contains behavioral information from an online store's customers (~55,000 records).

### Key variables:
- `ID` → customer identifier
- `n_clicks` → number of clicks
- `n_visits` → site visits
- `purchase_amount` → total spend
- `discount_amount` → discounts received
- `days_since_first_purchase` → customer tenure
- `profile_info` → level of user information

### Processing performed:
- Data cleaning and removal of inconsistencies
- Variable normalization (critical for K-Means)
- Exploratory analysis to understand distributions
- Identification of patterns and correlations

---

## ⚙️ Technologies & Libraries

### Technologies
- Python
- Jupyter Notebook

### Libraries
- **pandas** → data manipulation
- **numpy** → numerical computing
- **matplotlib** → visualization
- **seaborn** → exploratory analysis
- **scikit-learn** → K-Means, scaling, and metrics

---

## 📈 Key Results

### 🔹 Determining the optimal number of clusters
The **Elbow Method** was used to find the ideal number of segments.

📌 Result: **Optimal K ≈ 4–5 clusters**

---

### 🔹 Segments identified (interpretive example)

**Cluster 1 – Premium Customers**
- High spend
- High interaction
- High purchase frequency
👉 Strategy: VIP programs, loyalty

**Cluster 2 – Frequent Low-Ticket Customers**
- Many visits
- Low spend
👉 Strategy: increase average order value

**Cluster 3 – Occasional Customers**
- Low frequency
- Low engagement
👉 Strategy: reactivation campaigns

**Cluster 4 – Discount-Sensitive Customers**
- High discount usage
👉 Strategy: personalized promotions

---

## 💡 Business Insights

- Not all customers have the same value → segmentation makes it possible to prioritize resources
- A small group of customers generates a large share of revenue (Pareto principle)
- Discounts significantly influence certain segments
- Interaction frequency is a key predictor of customer value

---

## 🚀 Potential Impact

This model enables the company to:

- Increase conversion through personalized marketing
- Improve customer retention
- Optimize promotional campaigns
- Increase Customer Lifetime Value (CLV)

---

## 📊 Key Visualizations (recommended for GitHub)

👉 Add these images to your repo to make it more professional:

- **Elbow Method** chart
- Cluster scatter plot (2D with PCA)
- Variable distribution by cluster

---

## 🔮 Future Improvements

- Implement **PCA** for advanced visualization
- Try alternative algorithms:
  - DBSCAN
  - Hierarchical Clustering
- Integrate the model into a recommendation system
- Automate segmentation in real time

---
