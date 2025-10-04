#  Mall Customer Segmentation using Machine Learning
**By:- [Sanjay Nagda]**  

##  Table of Contents
- Introduction
- Dataset Description
- Objective 
- Methodology 
- Results and Insights 
- Tools and Technologies Used 
- Conclusion 
- Future Work 
- How to Run the Project 
- Author 

---

##  Introduction

In today’s retail industry, **customer understanding** plays a vital role in improving marketing and business strategies.  
This project, **Mall Customer Segmentation**, applies **unsupervised learning algorithms** to group customers based on their **income**, **age**, and **spending score**, helping businesses design targeted marketing campaigns.

The project demonstrates how **data analysis and clustering** can reveal meaningful patterns in customer behavior, improving both **sales** and **customer satisfaction**.

---

##  Dataset Description

- **Dataset Name:** `Mall_Customers.csv`  
- **Total Records:** 200  
- **Attributes:**
  - `CustomerID`: Unique identifier for each customer  
  - `Gender`: Male or Female  
  - `Age`: Age of the customer  
  - `Annual Income (k$)`: Annual income in thousands  
  - `Spending Score (1–100)`: Spending behavior score assigned by the mall  

---

##  Objective

The goal of this project is to:
- Perform exploratory data analysis (EDA) on customer demographics and spending behavior.  
- Segment customers into distinct groups using **clustering algorithms**.  
- Help businesses identify valuable customer segments for **personalized marketing**.

---

## Methodology

### 1️ Data Preprocessing
- Imported dataset using **Pandas**.  
- Checked for missing values and ensured data quality.  
- Selected relevant features for clustering.  

### 2️ Exploratory Data Analysis (EDA)
Visualized relationships between key features such as:
- **Age vs Annual Income**
- **Gender vs Spending Score**
- **Annual Income vs Spending Score**

> Libraries used: `Matplotlib`, `Seaborn`

### 3️ Feature Scaling
- Standardized features using **StandardScaler** to ensure balanced clustering.

### 4️ Clustering Techniques
Three clustering models were applied:

####  K-Means Clustering
- Determined the optimal number of clusters using the **Elbow Method** (5 clusters).  
- Segmented customers into five behavioral groups.

####  DBSCAN
- Detected high-density clusters and outliers.  
- Less effective due to uneven data density.

####  Hierarchical Clustering
- Used **Agglomerative Clustering** and **Dendrograms** for cluster validation.  

---
##  Results and Insights

###  Key Findings from K-Means:
| **Cluster** | **Customer Type** | **Description** |
|--------------|-------------------|------------------|
| 1 | High Income, High Spending | Premium customers; loyal and brand-focused |
| 2 | High Income, Low Spending | Potential high-value targets for marketing |
| 3 | Average Income, Average Spending | Balanced regular customers |
| 4 | Low Income, High Spending | Enthusiastic, possibly younger customers |
| 5 | Low Income, Low Spending | Budget-conscious shoppers |

###  Business Insights:
- **High-income low-spending** customers can be encouraged through **exclusive offers**.  
- **Low-income high-spending** groups represent **brand loyalty** and should be retained.  
- The segmentation provides a foundation for **targeted and efficient marketing strategies**.

---

## Tools and Technologies Used

| Category | Tools / Libraries |
|-----------|------------------|
| **Programming Language** | Python |
| **Libraries** | Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn |
| **Algorithms** | K-Means, DBSCAN, Hierarchical Clustering |
| **Platform** | Jupyter Notebook |

---

##  Conclusion

The **Mall Customer Segmentation Project** effectively utilized **unsupervised machine learning** to group customers into meaningful clusters.  
Among all algorithms, **K-Means** proved to be the most efficient and interpretable, revealing **five clear customer segments**.

This segmentation allows the mall management team to:
- **Personalize offers and campaigns** for different customer types.  
- **Increase revenue** through targeted promotions.  
- **Build data-driven marketing strategies** that improve customer engagement.

---

##  Future Work

To enhance this project further:
- Add additional variables like **purchase history**, **visit frequency**, and **product categories**.  
- Apply **PCA (Principal Component Analysis)** for dimensionality reduction.  
- Build an interactive **dashboard** using Streamlit or Power BI.  
- Perform **RFM Analysis (Recency, Frequency, Monetary)** for deeper segmentation.

---

##  How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Mall-Customer-Segmentation.git
   ```
2. Navigate into the project directory:
   ```bash
   cd Mall-Customer-Segmentation
   ```
3. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the notebook:
   ```bash
   jupyter notebook Mall_Customer_Segmentation.ipynb
   ```

---

##  Author

** Sanjay Nagda**  
Data Science & Machine Learning Enthusiast  

 *sanjaynagda049@gmail.com*  
   
*If you like this project, give it a star on GitHub!*  
