\# 📊 Customer Churn Analysis – Python \& SQL based EDA Project



\## 👩‍💻 Author  

Anjali Yadav – Aspiring Data Analyst



---



\## 📌 Project Overview



This project focuses on analysing customer churn patterns to understand how

operational and business factors such as delivery delays, freight cost and

product performance influence customer retention.



The objective is to support better business decisions using data analysis

and visual insights.



---



\## 🎯 Objectives



\- Understand the distribution of churned and retained customers

\- Analyse the impact of freight cost on customer churn

\- Study how delivery delays affect customer behaviour

\- Identify top product categories based on revenue

\- Compare on-time and late deliveries



---



\## 📄 Dataset Description



The dataset contains customer-level and order-related information that is

used to analyse customer churn and delivery performance.



It includes information related to:

\- customer orders

\- freight cost

\- delivery delays

\- product categories

\- revenue



The main focus is to understand patterns that influence customer churn.



---



\## 🔍 Churn Definition \& Data Preparation



There was no direct churn table available in the dataset.  

So, I created a single master table by combining the required customer, order

and transaction information.



A customer is considered churned if there is no activity for the last 6 months.  

Using this rule, I identified churned customers and then analysed the main

reasons behind customer churn.



---



\## ❓ Business Questions Answered



\- Are churned customers significantly different from retained customers?

\- Does higher freight cost contribute to customer churn?

\- Do delivery delays increase the likelihood of churn?

\- Which product categories contribute the most to revenue?

\- Is delivery performance related to customer behaviour?



---



\## 🔍 Key Analysis Performed



\- Data cleaning and preprocessing

\- Exploratory Data Analysis (EDA)

\- Grouping and aggregation

\- Feature-wise churn comparison

\- Visual analysis using charts



---



\## 📊 Visual Outputs



All visualisations generated from the notebook are saved in the \*\*outputs\*\*

folder.



The project includes charts for:



\- Churned vs retained customers distribution

\- Freight cost sensitivity and churn

\- Impact of delivery delays on churn

\- Top product categories by revenue

\- On-time vs late delivery comparison



---



\## 🧠 Key Insights



\- Customer churn shows noticeable variation based on delivery performance.

\- Freight cost sensitivity appears higher among churned customers.

\- Delivery delays show a visible impact on churn behaviour.

\- A small group of product categories contributes a major portion of revenue.

\- On-time deliveries are associated with better customer retention.



---



\## ⚙️ Challenges Faced



\- Handling file path issues while loading and saving data and charts.

\- Managing missing or inconsistent values during data cleaning.

\- Deciding the most meaningful visualizations to represent churn behaviour.

\- Organising the project structure for better readability.



---



\## ⚠️ Limitations



\- The analysis is limited to the available features in the dataset

\- No customer demographic information is included

\- No predictive or machine learning model is built



This project focuses mainly on exploratory and descriptive analysis.



---



\## 🚀 Future Improvements



\- Build a churn prediction model

\- Perform feature importance analysis

\- Add customer segmentation

\- Create an interactive dashboard using Power BI or Tableau



---



\## 🛠 Tools \& Technologies



\- Python  

\- Pandas  

\- Matplotlib  

\- Seaborn  

\- Jupyter Notebook  



---



\## 📂 Project Structure

```

customer-churn-analysis

│

├── data

├── notebook

├── outputs

├── README.md

└── requirements.txt

```



---



\## ▶️ How to Run This Project



1\. Clone the repository



git clone https://github.com/ydanjali09/customer-churn-analysis-sql-python.git



2\. Go to the project folder



cd customer-churn-analysis



3\. Install required libraries



pip install -r requirements.txt



4\. Open the notebook



jupyter notebook



5\. Open the file



notebook/CUSTOMER\_CHURN.ipynb



6\. Run all cells to see the analysis and charts.



---



\## ⭐ Project Highlights for Recruiters



\- Clean and organised project structure

\- Proper use of relative file paths for data and outputs

\- Separate folders for data, notebooks and visual outputs

\- Clear documentation and easy-to-follow project workflow

\- Real-world business and operational focused analysis

