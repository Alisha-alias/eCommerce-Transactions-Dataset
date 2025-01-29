# eCommerce Transactions Analysis

This repository contains data science solutions for an eCommerce transactions dataset. The project includes Exploratory Data Analysis (EDA), Lookalike Modeling, and Customer Segmentation using clustering techniques.

## Dataset
The dataset consists of three CSV files:
- **Customers.csv**: Contains customer details such as CustomerID, Name, Region, and Signup Date.
- **Products.csv**: Contains product details such as ProductID, Name, Category, and Price.
- **Transactions.csv**: Contains transaction records including TransactionID, CustomerID, ProductID, TransactionDate, Quantity, TotalValue, and Price.

## Project Structure

### 1. Exploratory Data Analysis (EDA)
- **EDA Notebook:** `Alisha_Alias_EDA.ipynb`
- **Report:** `Alisha_Alias_EDA.pdf`
- **Description:**
  - Performs exploratory data analysis on the dataset.
  - Identifies key patterns and trends in customer behavior.
  - Extracts and presents five key business insights based on the data.

### 2. Lookalike Model
- **Code Notebook:** `Alisha_Alias_Lookalike.ipynb`
- **Lookalike Recommendations CSV:** `Alisha_Alias_Lookalike.csv`
- **Description:**
  - Builds a Lookalike Model that recommends three similar customers based on profile and transaction history.
  - Uses cosine similarity to compute customer similarity.
  - Outputs the top three lookalikes and their similarity scores for the first 20 customers.

### 3. Customer Segmentation / Clustering
- **Clustering Notebook:** `Alisha_Alias_Clustering.ipynb`
- **Report:** `Alisha_Alias_Clustering.pdf`
- **Description:**
  - Applies clustering techniques to segment customers based on profile and transaction data.
  - Evaluates clusters using the Davies-Bouldin Index.
  - Visualizes customer segments and provides insights into different customer groups.

## Getting Started
### Prerequisites
- Python 3.x
- Jupyter Notebook
- Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn

### How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/Alisha-alias/eCommerce-Transactions-Dataset.git
   cd eCommerce-Transactions-Dataset
   ```
2. Open and run Jupyter Notebooks in the specified order.

## Results and Insights
- The EDA report provides key business insights to improve decision-making.
- The Lookalike Model helps identify similar customers, enabling personalized marketing strategies.
- The Customer Segmentation analysis groups customers into distinct segments for targeted business strategies.

---

For any questions or collaboration, feel free to reach out!

