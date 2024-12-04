

# 📊 **RFM Analysis for Customer Segmentation and Marketing Insights**

## 🚀 **Overview**
This repository demonstrates the implementation of **RFM Analysis** (*Recency, Frequency, Monetary Value*), a powerful technique for customer segmentation and marketing strategies. Using real-world data, we classify customers into meaningful segments, enabling businesses to understand customer behavior and target them effectively.

---

## 🧩 **Project Highlights**

- **Dataset**: Brazilian E-Commerce Public Dataset by Olist (from [Kaggle](https://www.kaggle.com)).
  - Includes 100,000+ orders with customer, product, and review data.
- **Tech Stack**: Python, Pandas, Matplotlib, Plotly, Squarify, Scikit-Learn, Seaborn.
- **Key Deliverables**:
  - 📈 **RFM Scores and Segments** for customer classification.
  - 📊 **Interactive Dashboards** for customer insights.
  - 🎯 **Marketing Actions** tailored to customer segments.

---

## 📂 **Repository Structure**

```plaintext
📁 rfm_analysis
├── rfm_analysis.ipynb     # Jupyter Notebook with the full implementation
├── rfm.csv                # Final processed dataset with RFM scores and segments
├── README.md              # Project documentation
└── requirements.txt       # Python dependencies
```

---

## 📜 **Key Concepts**

### **What is RFM Analysis?**
RFM Analysis evaluates customers based on:
- **Recency (R)**: How recently a purchase was made.
- **Frequency (F)**: How often purchases are made.
- **Monetary Value (M)**: How much a customer spends.

### **Why Use RFM?**
- Identify VIP and loyal customers.
- Detect at-risk or lost customers.
- Optimize marketing strategies with tailored actions.

### **Process Overview**
1. **Feature Engineering**: Transform raw data into usable features (e.g., converting timestamps to datetime).
2. **RFM Metrics Calculation**: Compute Recency, Frequency, and Monetary Value for each customer.
3. **Segmentation**: Use statistical methods (quartiles and custom thresholds) to assign RFM scores.
4. **Interactive Dashboard**: Visualize customer segments dynamically for actionable insights.

---

## 📊 **Interactive Dashboard**

### Static Dashboard Example:
![Static Treemap](https://via.placeholder.com/600x400?text=Treemap+Placeholder)

### Interactive Dashboard (Preview):
Click [here](https://link-to-your-dashboard) to explore the interactive dashboard.

---

## ⚡ **How to Run the Project**

### 1️⃣ Clone the Repository:
```bash
git clone https://github.com/yourusername/rfm_analysis.git
cd rfm_analysis
```

### 2️⃣ Install Dependencies:
```bash
pip install -r requirements.txt
```

### 3️⃣ Run the Jupyter Notebook:
```bash
jupyter notebook rfm_analysis.ipynb
```

---

## 🔍 **Results & Insights**

### **Customer Segments Identified**:
- **VIP Customers**: High RFM scores; focus on loyalty programs.
- **Loyal Customers**: Frequent and high spenders; prioritize upselling.
- **At-Risk Customers**: Long time since last purchase; require re-engagement campaigns.
- **Lost Customers**: Minimal activity; focus efforts elsewhere.

### **Marketing Recommendations**:
- Tailored incentives based on RFM scores.
- Focus on cross-selling, upselling, and retention strategies.

---

## 🤖 **Key Features**

- **Automated RFM Score Calculation**: Generate scores dynamically based on data.
- **Customer Segmentation**: Create meaningful groups with actionable insights.
- **Interactive Visualizations**: Use treemaps to explore segment details.
- **Marketing Strategies**: Suggest actionable steps for each segment.

---

## 📚 **Learnings & Takeaways**
This project demonstrates the importance of combining **data science** with **business insights**. From raw data to actionable recommendations, it highlights the potential of **Python** in solving real-world challenges.

---

## 🛠 **Tools & Libraries**

- **Data Analysis**: Pandas, Numpy
- **Visualization**: Matplotlib, Plotly, Squarify
- **Machine Learning**: Scikit-Learn
- **Dashboarding**: Plotly Dash (for interactive visualizations)

---

## 📥 **Data Source**

- Dataset: [Olist E-Commerce Public Dataset](https://www.kaggle.com/olistbr/brazilian-ecommerce)

---

## 📧 **Contact**

If you have questions or suggestions, feel free to reach out:
- Author: Leonardo Anello
- Email: [your-email@example.com](mailto:your-email@example.com)
- LinkedIn: [your-linkedin-profile](https://linkedin.com/in/your-profile)

---

## 🌟 **Contributions**
Contributions are welcome! Feel free to fork the repository, open an issue, or submit a pull request.
