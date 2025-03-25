# Child-mortality-clustering
Clustering Analysis of Countries Based on Child Mortality and Health Spending
Overview
This project applies unsupervised learning (clustering) techniques to classify countries based on child mortality rates and healthcare spending. The goal is to uncover patterns in global health investment and mortality rates, helping policymakers and organizations allocate resources more effectively.

Problem Statement
High child mortality rates remain a major concern, particularly in low-income regions with inadequate healthcare infrastructure. This study investigates how healthcare spending relates to child mortality and identifies country clusters with similar economic and healthcare characteristics.

Dataset
Source: Kaggle & World Bank

Number of Countries: 167

Key Features:

Child Mortality Rate (deaths per 1,000 live births)

Healthcare Spending (% of GDP)

Life Expectancy

Government Health Expenditure

GDP per Capita

Methodology
✔ Data Preprocessing: Handled missing values, removed outliers, and normalized data.
✔ Clustering Algorithms: Applied K-Means and DBSCAN to classify countries based on child mortality and healthcare spending.
✔ Evaluation Metrics: Used Elbow Method to find optimal K for K-Means and Silhouette Score to assess clustering quality.
✔ Visualization: Created cluster plots to interpret the relationships between health spending and mortality.

Key Findings
✔ Three major clusters identified, differentiating countries by income levels and healthcare investment.
✔ Countries with higher healthcare spending generally have lower child mortality rates.
✔ Low-income countries exhibit higher mortality despite increasing government health expenditure, indicating inefficiencies in healthcare systems.

Real-World Applications
✔ Governments & NGOs can use insights to allocate healthcare resources efficiently.
✔ Researchers can extend the study by integrating more socioeconomic factors.

Technologies Used
✔ Python (Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn)
✔ Clustering Techniques: K-Means, DBSCAN
✔ Evaluation Metrics: Silhouette Score, Elbow Method

How to Run the Project
Clone the repository:

bash
Copy
Edit
git clone https://github.com/yourusername/child-mortality-clustering.git
cd child-mortality-clustering
Install dependencies:

bash
Copy
Edit
pip install pandas numpy matplotlib seaborn scikit-learn
Run the Jupyter Notebook or Python script:

bash
Copy
Edit
jupyter notebook clustering_analysis.ipynb
Project Structure
bash
Copy
Edit
📂 child-mortality-clustering  
│── 📄 README.md           # Project documentation  
│── 📄 clustering_analysis.ipynb  # Jupyter Notebook with full analysis  
│── 📄 data.csv            # Cleaned dataset  
│── 📂 images/             # Visualizations and graphs  
│── 📄 requirements.txt    # Dependencies
