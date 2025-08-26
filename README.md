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
| ![3D Clusters](https://github.com/user-attachments/assets/4e9ddc23-7144-4356-8048-d7271c15406d) |  
|:--|  
| A 3D visualization of customer segments across **Annual Income, Spending Score, and Age**. Each cluster highlights unique customer behaviors, enabling deeper insights into purchasing power and spending habits. This chart provides the most comprehensive segmentation view. |

---

### 2. Distribution of Annual Income
| ![Displot](https://github.com/user-attachments/assets/b3d55eab-5716-4261-ac1b-e89295463d44) | Customer income distribution showing how purchasing power varies across the dataset. This distribution is foundational for understanding potential segmentation boundaries. |

---

### 3. Violin Plot – Spending by Age
| ![Violin Plot](https://github.com/user-attachments/assets/0c66b006-ba3e-4078-a8a2-71ba244e716c) | Spending score variation across age groups, illustrating how younger and older customers differ in engagement and purchasing patterns. |

---

### 4. Customers in Age Group Bins
| ![Age Bins](https://github.com/user-attachments/assets/344d22a0-f4de-4197-94ed-a808e2dbaf8c) | Customer counts across defined age bins. This helps reveal which age groups dominate the customer base and supports targeted marketing. |

---

### 5. Spending Score vs Annual Income
| ![Scatterplot](https://github.com/user-attachments/assets/053b16e5-c7a3-4c04-94af-579799b36478) | A scatterplot comparing **Annual Income** against **Spending Score**. Natural clustering patterns are visible, justifying the use of K-Means segmentation. |

---

### 6. Elbow Method – Cluster Optimization
| ![Elbow Method](https://github.com/user-attachments/assets/0a4a8edc-b8ae-4a6f-8335-572a0a7ffcf8) | The elbow method determines the optimal number of clusters for K-Means. This ensures a balance between model complexity and interpretability. |

---

### 7. Customer Segments (Age vs Spending Score)
| ![Cluster 4](https://github.com/user-attachments/assets/9940bcf0-6362-4319-aa36-ebe416645721) | Four customer clusters identified by **Age** and **Spending Score**, with centroids marked. This segmentation highlights young high spenders, older conservative spenders, and more. |

---

### 8. Customer Segments (Income vs Spending Score)
| ![Cluster 5](https://github.com/user-attachments/assets/8ebe0009-a55c-49ce-94bb-258dc0c25694) | Five customer clusters segmented by **Annual Income** and **Spending Score**. This view helps businesses align product pricing and marketing strategies with distinct customer groups. |

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
