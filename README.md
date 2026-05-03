# Customer-Segmentation-using-K-Means-Clustering

📌 Project Overview

This project focuses on segmenting customers of a retail store based on their purchasing behavior using K-Means Clustering, an unsupervised machine learning algorithm.

The goal is to identify distinct customer groups to help businesses make better marketing and strategic decisions.

🎯 Problem Statement

Businesses often have large amounts of customer data but lack insights into customer behavior.

This project aims to:

- Group customers into different segments
- Understand spending patterns
- Help businesses target the right customers

📊 Dataset Information

The dataset contains the following features:

- CustomerID
- Gender
- Age
- Annual Income (k$)
- Spending Score (1–100)

🧠 Approach

1. Data Preprocessing

- Removed unnecessary columns (CustomerID)
- Selected relevant features:
  - Annual Income
  - Spending Score

2. Finding Optimal Clusters

Used the Elbow Method to determine the optimal number of clusters (K).

- Calculated WCSS (Within-Cluster Sum of Squares)
- Identified K = 5 as the optimal number

3. Model Building

- Applied K-Means Clustering
- Assigned each customer to a cluster

---

4. Visualization

- Plotted clusters using scatter plot
- X-axis: Annual Income
- Y-axis: Spending Score
- Color-coded clusters for clear understanding

---

📈 Results (Customer Segments)

The model identified 5 distinct customer groups:

- 🔴 Budget Customers
  Low income and low spending

- 🔵 Impulse Buyers
  Low income but high spending

- 🟢 Average Customers
  Medium income and medium spending

- 🟣 Potential Customers
  High income but low spending

- 🟠 Premium Customers
  High income and high spending

💼 Business Insights

- 🎯 Premium customers should be targeted with loyalty programs
- 🎯 Potential customers can be converted using offers and discounts
- 🎯 Impulse buyers respond well to marketing campaigns
- 🎯 Budget customers are price-sensitive
- 🎯 Average customers maintain steady revenue

🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

🚀 How to Run the Project

1. Clone the repository
2. Install required libraries:
   pip install pandas numpy matplotlib seaborn scikit-learn
3. Run the Python file or Jupyter Notebook

📁 Output

- Clustered dataset with customer segments
- Visualization of customer groups

📌 Future Improvements

- Add more features like Age and Gender analysis
- Build interactive dashboard using Power BI
- Deploy as a web app using Streamlit

🙌 Conclusion

This project demonstrates how unsupervised learning can uncover hidden patterns in customer data and provide actionable business insights.

🔗 Author
Afrith Basha
