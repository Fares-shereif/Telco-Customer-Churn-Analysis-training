# Telco Customer Churn Analysis

Hey there! Welcome to my Telco Customer Churn Analysis project! I'm diving into the Telco Customer Churn dataset to figure out why customers might leave their telecom services. Using some cool techniques like K-means clustering to group customers and machine learning models (Logistic Regression and Random Forest) to predict churn, I’ve also thrown in some fun visualizations to tell the story behind the data.

## Dataset
- **Where to Find It**: Grab the dataset from [Kaggle’s Telco Customer Churn page](https://www.kaggle.com/datasets/blastchar/telco-customer-churn).
- **File Name**: `WA_Fn-UseC_-Telco-Customer-Churn.csv`
- **What’s in It**: This dataset is packed with info on 7,043 customers across 21 columns, covering demographics (like age and gender), services (like internet or phone), billing details, and whether they churned (left the service).

## How to Run the Notebook
Want to check out the analysis? Here’s how to get the Jupyter Notebook (`assignment.ipynb`) running on your computer:

1. **What You Need**:
   - Python 3.8 or newer (most recent versions work great).
   - Install the libraries we’ll use by running this in your terminal:
     ```bash
     pip install pandas numpy scikit-learn matplotlib seaborn
     ```
   - Make sure Jupyter Notebook is installed:
     ```bash
     pip install jupyter
     ```

2. **Get Set Up**:
   - Download the dataset from the Kaggle link above and place the `WA_Fn-UseC_-Telco-Customer-Churn.csv` file in the same folder as `assignment.ipynb`.

3. **Run It**:
   - Open your terminal (or command prompt) and navigate to the folder with your notebook and dataset.
   - Start Jupyter Notebook with:
     ```bash
     jupyter notebook
     ```
   - Your browser will open Jupyter. Click on `assignment.ipynb` to open it.
   - Run all the cells one by one (hit Shift+Enter) or use the “Run All” button in the menu.

4. **What You’ll See**:
   - A quick peek at the data (size, columns, first few rows, stats, and more).
   - A cleaned-up dataset with no missing values and all variables ready for analysis.
   - K-means clustering results, including an elbow plot to pick the best number of clusters and a breakdown of each customer group.
   - Performance scores for churn prediction models (Logistic Regression and Random Forest, plus an improved RF version).
   - Five visualizations, showing things like how long customers stay, churn rates by group, and what factors drive churn the most.

5. **Quick Tips**:
   - Make sure the dataset file is named exactly `WA_Fn-UseC_-Telco-Customer-Churn.csv` and is in the same folder as the notebook.
   - The notebook uses `%matplotlib inline`, so plots will show up right in the notebook—no extra setup needed.
   - I’ve used random seeds (`random_state=42`) to keep results consistent, so you’ll get the same output each time.

If you run into any trouble, double-check your library versions or ensure the dataset file is in the right spot. Have fun exploring the churn patterns!

---
