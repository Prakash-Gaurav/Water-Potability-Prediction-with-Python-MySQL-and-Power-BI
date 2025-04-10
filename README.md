# Water-Potability-Prediction-with-Python-MySQL-and-Power-BI
This project aims to determine whether water is safe for human consumption based on various chemical properties. It uses Python for machine learning, MySQL for database management, and Power BI for interactive visualization.
![Image](https://github.com/user-attachments/assets/87effbbb-4d6b-4ee5-adc9-e3e5d2e40345)

**💦 Data Source:** https://www.kaggle.com/datasets/adityakadiwal/water-potability/data

`Access to safe drinking-water is essential to health, a basic human right and a component of effective policy for health protection. This is important as a health and development issue at a national, regional and local level. In some regions, it has been shown that investments in water supply and sanitation can yield a net economic benefit, since the reductions in adverse health effects and health care costs outweigh the costs of undertaking the interventions.`

**🛠️ Tech Stack**
 
- 🐍 Python (Pandas, Scikit-learn, XGBoost, SMOTE)
- 🗄️ MySQL (Data Storage & Queries)
- 📊 Power BI (Interactive Dashboard)

![Image](https://github.com/user-attachments/assets/96e18cad-89a3-4a4a-b44a-03bbdaa0254f)
**🔍 Dataset Description**

1. **ph:** pH of 1. water (0 to 14).
2. **Hardness:** Capacity of water to precipitate soap in mg/L.
3. **Solids:** Total dissolved solids in ppm.
4. **Chloramines:** Amount of Chloramines in ppm.
5. **Sulfate:** Amount of Sulfates dissolved in mg/L.
6. **Conductivity:** Electrical conductivity of water in μS/cm.
7. **Organic_carbon:** Amount of organic carbon in ppm.
8. **Trihalomethanes:** Amount of Trihalomethanes in μg/L.
9. **Turbidity:** Measure of light emiting property of water in NTU.
10. **Potability:** Indicates if water is safe for human consumption. Potable -1 and Not potable -0

<img align="right" alt="SCatter Plot" width="400" src="https://github.com/user-attachments/assets/e156b638-f414-43ef-865b-8fce96d7404a">


## **🔄 Project Workflow / Steps**
1. **EDA & Data Cleaning and Preprocessing**  
   - Handled missing values and outliers  
   - Applied normalization and encoding

2. **Feature Engineering**  
   - Created new features like pH_Safety, TDS_Range, Mineralization_Index, etc.

3. **Database Integration (MySQL)**  
   - Stored cleaned dataset in a structured SQL table

<img align="right" alt="XGBoost Confusion Matrix" width="400" src="https://github.com/user-attachments/assets/7632a9ef-eb75-400a-9afa-ddc3986bb938">

4. **Model Building & Evaluation**  
   - Tried multiple models: Logistic Regression, SVM, Random Forest, XGBoost, etc.  
   - Handled class imbalance using SMOTE  
   - Evaluated using Accuracy, Confusion Matrix, Classification Report
     
`Note:` XGBoost achieved the highest accuracy at 78.46%, followed closely by GradientBoostingClassifier (77.52%) and RandomForestClassifier (76.41%)

5. **Dashboard Visualization (Power BI)**  
   - Created dynamic visuals to explore potability metrics  
   - Interactive filters based on safety flags, mineralization levels, and more

 -------------------------------------------------------------------------------------------------------------------------------------------------------------------

**`📈 Key Insights / KPIs`**
- Most safe water samples fall within pH 6.5–8.5
- High organic contamination correlates with non-potable samples
- Mineralization Index and Conductivity play key roles in water safety

 
![Image](https://github.com/user-attachments/assets/70d90fb4-b4a8-4704-acdf-f161b7bfe70a)

_______________
## 📬 Contact
Created by [Prakash Gaurav]  
📧 prakashgaurav98@gmail.com 

🔗 LinkedIn: [https://www.linkedin.com/in/prakash-gaurav-519164268/]


## 🙋‍♂️ Support
💙 If you like this project, give it a ⭐ and share it with friends!
