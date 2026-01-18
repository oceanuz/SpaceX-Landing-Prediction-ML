SpaceX Falcon 9 Landing Prediction
🚀 Project Overview
This project aims to predict whether the Falcon 9 first stage will land successfully. SpaceX can reuse the first stage, which reduces the cost of a launch from $165M to $62M. Predicting the landing success is critical for determining the cost of a launch.

📊 Key Features
Data Collection: Leveraged SpaceX API and Web Scraping (Wikipedia) to build a comprehensive dataset.

Data Wrangling: Cleaned data, handled missing values, and performed feature engineering (one-hot encoding).

EDA & SQL: Explored launch trends, success rates, and site analysis using Pandas and SQL.

Interactive Maps: Visualized launch sites and proximity analysis using Folium.

Dashboard: Built an interactive dashboard using Plotly Dash to analyze success rates.

Machine Learning: Developed classification models (Logistic Regression, SVM, KNN, Decision Tree) to predict landing outcomes.

🛠️ Tech Stack
Languages: Python

Libraries: Pandas, NumPy, Scikit-learn, Folium, Plotly, Dash, Matplotlib, Seaborn

Tools: Jupyter Notebook, SQL (SQLite)

📈 Methodology & Results
Data Gathering: Pulled data from SpaceX API and scraped Wikipedia launch records.

Analysis: Found that success rates have increased significantly over the years and vary by launch site.

Modeling: Tested multiple algorithms. The Decision Tree and SVM models provided the highest accuracy during cross-validation.

📁 Repository Structure
Notebooks/: Contains all step-by-step Jupyter notebooks from data collection to ML.

Data/: CSV datasets used for analysis.

Images/: Visualizations and plots generated during EDA.
