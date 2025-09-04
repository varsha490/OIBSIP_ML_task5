# 📊 OIBSIP ML Internship – Task 5  
## Sales Prediction using Machine Learning  

### 🔹 Objective  
Build a machine learning model that can predict **product sales** based on advertising expenditure on **TV, Radio, and Newspaper**.  
This helps businesses optimize their ad budgets and forecast sales effectively.  

---

### 🔹 Dataset  
- **TV** – Advertising spend on TV (in thousands of dollars)  
- **Radio** – Advertising spend on Radio  
- **Newspaper** – Advertising spend on Newspaper  
- **Sales** – Product sales (in thousands of units)  

📂 Dataset Source: [Advertising Sales Dataset](https://www.kaggle.com/datasets/ishaanv/Advertising-dataset)  

---

### 🔹 Steps Performed  
1. **Data Exploration & Visualization**  
   - Checked dataset structure & statistics  
   - Correlation analysis between ad spend & sales  
   - Scatter plots for feature relationships  

2. **Data Preprocessing**  
   - Selected features → `TV`, `Radio`, `Newspaper`  
   - Defined target variable → `Sales`  
   - Train-test split (80%-20%)  

3. **Model Building**  
   - Linear Regression Model  
   - Trained using training dataset  

4. **Evaluation**  
   - R² Score, Mean Squared Error (MSE)  
   - Compared **Actual vs Predicted Sales**  
   - Visualized prediction results  

5. **Prediction**  
   - User input (TV, Radio, Newspaper ad spend)  
   - Model outputs predicted **Sales**  

---

### 🔹 Visualizations  
- 📊 Correlation Heatmap  
- 📊 Actual vs Predicted Sales Scatter Plot  

---

### 🔹 Insights & Conclusions  
- **TV & Radio** advertising strongly influence sales  
- **Newspaper** advertising has minimal impact  
- Linear Regression achieved **high accuracy (R² ≈ 0.90–0.92)**  
- Businesses can prioritize **TV & Radio ads** for better ROI  

---

### 🔹 Tools & Libraries  
- **Python**  
- **Pandas, NumPy** for data handling  
- **Matplotlib, Seaborn** for visualization  
- **Scikit-learn** for model building  
- **Jupyter Notebook** for analysis  

---

### 🔹 Results / Outcome  
✅ Built a sales prediction model using Linear Regression  
✅ Evaluated model performance (R², MSE)  
✅ Visualized ad spend impact on sales  
✅ Interactive user input for real-time predictions  

---

### 🔹 Project Links  
📓 Notebook: [Sales_Prediction.ipynb](./Sales_Prediction.ipynb)  
📂 Dataset: [advertising.csv](./advertising.csv)  
📘 Repository: [OIBSIP_ML_task5](https://github.com/varsha490/OIBSIP_ML_task5)  

---

### 🔹 Author  
👩‍💻 **Varsha** – OIBSIP ML Intern  
