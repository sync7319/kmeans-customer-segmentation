# Customer Segmentation and Churn Prediction

This project is similar to a customer segmentation initiative i originally completed at **Astound Broadband** using public data. The goal was to segment customers into meaningful groups, predict churn risk, and derive actionable insights for marketing and retention strategies.

## Project Overview
- **Objective:** Replicate a real-world customer analytics project to demonstrate segmentation, predictive modeling, and optimization techniques.
- **Approach:**
  - Customer segmentation using **K-Means clustering** with **elbow optimization**.
  - Dimensionality reduction with **Principal Component Analysis (PCA)** for visualization and feature simplification.
  - Predictive modeling using **Logistic Regression** and **XGBoost** for churn classification.
  - Evaluation with metrics such as accuracy, precision, recall, and ROC-AUC.
- **Outcome:** Actionable insights into customer groups and churn drivers that can inform marketing campaigns, retention strategies, and resource allocation.

## Tech Stack
- **Languages:** Python  
- **Libraries:** pandas, numpy, scikit-learn, matplotlib, seaborn, xgboost  
- **Techniques:** Clustering, PCA, Logistic Regression, Gradient Boosting, Elbow Optimization, Model Evaluation  

---

## Visualizations

### 1. 3D Customer Segmentation (Most Important)
<table>
<tr>
<td style="width:70%;">
<img src="https://github.com/user-attachments/assets/4e9ddc23-7144-4356-8048-d7271c15406d" style="width:100%;"/>
</td>
<td style="width:30%; vertical-align:top;">
A 3D visualization of customer segments across <b>Annual Income, Spending Score, and Age</b>.<br><br>
Each cluster highlights unique customer behaviors,<br>
enabling deeper insights into purchasing power and spending habits.<br><br>
This chart provides the most comprehensive segmentation view.
</td>
</tr>
</table>

### 2. Distribution of Annual Income
<table>
<tr>
<td style="width:70%; vertical-align:top;">
<img src="https://github.com/user-attachments/assets/b3d55eab-5716-4261-ac1b-e89295463d44" style="width:100%;"/>
</td>
<td style="width:30%; vertical-align:top;">
Customer income distribution showing how purchasing power varies<br>
across the dataset.<br><br>
This distribution is foundational for understanding<br>
potential segmentation boundaries.
</td>
</tr>
</table>

### 3. Violin Plot – Spending by Age
<table>
<tr>
<td style="width:70%;">
<img src="https://github.com/user-attachments/assets/0c66b006-ba3e-4078-a8a2-71ba244e716c" style="width:100%;"/>
</td>
<td style="width:30%; vertical-align:top;">
Spending score variation across age groups,<br>
illustrating how younger and older customers differ<br>
in engagement and purchasing patterns.
</td>
</tr>
</table>

### 4. Customers in Age Group Bins
<table>
<tr>
<td style="width:70%; vertical-align:top;">
<img src="https://github.com/user-attachments/assets/344d22a0-f4de-4197-94ed-a808e2dbaf8" style="width:100%;"/>
</td>
<td style="width:30%; vertical-align:top;">
Customer counts across defined age bins.<br><br>
This helps reveal which age groups dominate the customer base<br>
and supports targeted marketing strategies.
</td>
</tr>
</table>

### 5. Spending Score vs Annual Income
<table>
<tr>
<td style="width:70%;">
<img src="https://github.com/user-attachments/assets/053b16e5-c7a3-4c04-94af-579799b36478" style="width:100%;"/>
</td>
<td style="width:30%; vertical-align:top;">
A scatterplot comparing <b>Annual Income</b> against <b>Spending Score</b>.<br><br>
Natural clustering patterns are visible,<br>
justifying the use of K-Means segmentation.
</td>
</tr>
</table>

### 6. Elbow Method – Cluster Optimization
<table>
<tr>
<td style="width:70%; vertical-align:top;">
<img src="https://github.com/user-attachments/assets/0a4a8edc-b8ae-4a6f-8335-572a0a7ffcf8" style="width:100%;"/>
</td>
<td style="width:30%; vertical-align:top;">
The elbow method determines the optimal number of clusters<br>
for K-Means.<br><br>
This ensures a balance between model complexity and interpretability.
</td>
</tr>
</table>

### 7. Customer Segments (Age vs Spending Score)
<table>
<tr>
<td style="width:70%;">
<img src="https://github.com/user-attachments/assets/9940bcf0-6362-4319-aa36-ebe416645721" style="width:100%;"/>
</td>
<td style="width:30%; vertical-align:top;">
Four customer clusters identified by <b>Age</b> and <b>Spending Score</b>,<br>
with centroids marked.<br><br>
This segmentation highlights young high spenders,<br>
older conservative spenders, and more.
</td>
</tr>
</table>

### 8. Customer Segments (Income vs Spending Score)
<table>
<tr>
<td style="width:70%; vertical-align:top;">
<img src="https://github.com/user-attachments/assets/8ebe0009-a55c-49ce-94bb-258dc0c25694" style="width:100%;"/>
</td>
<td style="width:30%; vertical-align:top;">
Five customer clusters segmented by <b>Annual Income</b> and <b>Spending Score</b>.<br><br>
This view helps businesses align product pricing and<br>
marketing strategies with distinct customer groups.
</td>
</tr>
</table>


---

## Files
- `customer_segmentation.ipynb` – Main notebook with data preparation, clustering, modeling, and evaluation.
- `requirements.txt` – List of required dependencies.
- `images/` – Folder containing saved plots and charts.

## Key Learnings
- How clustering techniques and elbow optimization can identify distinct customer segments.  
- Importance of dimensionality reduction for simplifying customer data without losing key patterns.  
- Practical application of supervised models for churn prediction.  
- End-to-end workflow from raw data preprocessing to business-focused insights.  
