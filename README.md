# Retail Customer Segmentation with Clustering

## 📌 Project Overview
This project analyzes retail transaction data to segment customers using clustering techniques. The dataset contains two years of sales data, including customer purchases, product details, and transaction timestamps. The goal is to identify distinct customer groups based on purchasing behavior using K-Means and DBSCAN clustering.

## 📂 Dataset Details
The dataset used is **online_retail_II.xlsx**, which consists of two sheets:
- **Year 2009-2010**
- **Year 2010-2011**

### **Columns in the Dataset:**
- **Invoice Number**: Unique identifier for each transaction
- **Stock Code**: Unique product identifier
- **Description**: Product details
- **Quantity**: Number of items purchased
- **Invoice Date**: Timestamp of the transaction
- **Unit Price**: Price per unit
- **Customer ID**: Unique (anonymized) customer identifier
- **Country**: Country where the transaction took place

## 🚀 Key Features
- **Data Cleaning**: Handles missing values, removes anomalies, and ensures data integrity.
- **Exploratory Data Analysis (EDA)**: Analyzes sales trends, customer spending patterns, and best-selling products.
- **Customer Segmentation**: Uses **K-Means** and **DBSCAN** clustering to group customers based on Recency, Frequency, and Monetary (RFM) values.
- **Visualizations**: Includes scatter plots, box plots, and cluster distribution charts for better insights.
- **Predictive Modeling** *(Future Scope)*: Can extend to predicting customer churn and personalized recommendations.

## 🏗️ Installation & Setup
Ensure you have Python and Jupyter Notebook installed. Then, install the required libraries:

```sh
pip install pandas numpy matplotlib seaborn scikit-learn openpyxl
```

Clone the repository:
```sh
git clone https://github.com/your-username/retail-customer-segmentation.git
cd retail-customer-segmentation
```

## 📜 Usage Guide
1. **Load the Dataset**: The script reads the dataset and combines both sheets.
2. **Preprocess the Data**: Missing values and outliers are handled.
3. **Perform RFM Analysis**: Recency, Frequency, and Monetary values are calculated for each customer.
4. **Apply Clustering**:
   - **K-Means Clustering**: Segments customers into optimal groups.
   - **DBSCAN Clustering**: Identifies high-density customer clusters.
5. **Visualize the Results**: Insights are presented using graphs and boxplots.
6. **Save Cleaned Data**: The cleaned dataset is saved as `cleaned_online_retail.csv`.

Run the main script in Jupyter Notebook:
```sh
jupyter notebook
```
Then open and execute `customer_segmentation.ipynb`.

## 📊 Sample Visualizations
### **Cluster Distribution**
![Cluster Plot](cluster_plot.png)

### **Boxplot of Customer Segments**
![Boxplot](boxplot.png)

## 🤖 Future Enhancements
- Implement **predictive modeling** for customer purchase behavior.
- Deploy the model using a **Flask/Django web application**.
- Integrate with **Power BI or Tableau** for dynamic visualizations.

## 📜 License
This project is licensed under the MIT License.

## 🤝 Contributing
Feel free to fork this repository, submit issues, or open pull requests to improve this project!

---
**Author:** Your Name  
📧 Contact: your.email@example.com  
🔗 GitHub: [Your GitHub Profile](https://github.com/your-username)

