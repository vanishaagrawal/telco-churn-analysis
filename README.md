# Smart Churn Analytics: Predicting and Preventing Telecom Customer Loss

## 📌 Overview

**Smart Churn Analytics** is a data-driven project aimed at identifying and preventing customer churn in the telecom industry. Leveraging machine learning algorithms and business intelligence tools like **Power BI**, this project analyzes customer data to predict churn and provides actionable insights through interactive dashboards and a custom web interface. The solution helps telecom providers understand not just who is likely to churn, but why, enabling proactive retention strategies.

---

## 💡 Objectives

- Predict customer churn using machine learning models.
- Analyze customer behavior and service usage patterns.
- Create a business-friendly interactive dashboard using Power BI.
- Build a custom web app to visualize ML insights for broader accessibility.
- Provide actionable insights for decision-makers to reduce churn.

---

## 🛠️ Technologies Used

- **Python** (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)
- **Machine Learning Models**: Logistic Regression, Random Forest
- **Power BI**: For building interactive dashboards and business storytelling
- **HTML/CSS**: For the custom frontend visualization
- **Jupyter Notebooks**: For exploratory data analysis and modeling

---

## 📊 Dataset

- **Source**: Kaggle - [Telco Customer Churn Dataset](https://www.kaggle.com/blastchar/telco-customer-churn)
- **Records**: 7,043 customers
- **Features**: 21 columns including demographic info, services used, billing, and churn status

---

## 🧪 Machine Learning Pipeline

### 1. **Data Preprocessing**
- Removed null values from 'Total Charges'
- Dropped irrelevant columns like `CustomerID` and `Count`
- Encoded categorical variables using Label Encoding
- Standardized numerical features

### 2. **Exploratory Data Analysis (EDA)**
- Churn distribution analysis using pie and count plots
- Correlation analysis to identify important variables
- Visual patterns in churn by:
  - Tenure
  - Monthly charges
  - Contract types
  - Internet service and add-ons

### 3. **Model Building**
- **Logistic Regression**: Baseline model for interpretability
- **Random Forest Classifier**: For better performance and feature importance

### 4. **Model Evaluation**
- Confusion matrix and classification reports
- Key metrics: Accuracy, Precision, Recall, F1-score
- Feature importance rankings

---

## 📈 Power BI Dashboard Features

- Interactive slicers for gender, contract, and payment method
- Churn analysis via bar charts, pie charts, and trendlines
- KPI cards for Total Customers, Churn Rate, Avg. Tenure
- Filter-based dynamic updates across all visuals

---

## 🌐 Custom Web App

- **Live Link**: [https://telco-churn-analysis.netlify.app/](https://telco-churn-analysis.netlify.app/)
- Displays EDA plots, model metrics, and churn insights
- User-friendly interface for stakeholders without Power BI access
- Real-time filtering and drill-down capabilities

---

## 🚀 Results

- **Random Forest Accuracy**: ~84%
- **Top Influential Features**:
  - Contract Type
  - Tenure
  - Monthly Charges
  - Internet Service Type
- **Business Impact**: Helps reduce churn by identifying at-risk segments (e.g., month-to-month fiber users) and suggesting targeted interventions

---

## 🌟 Key Innovations

- Dual delivery system: Power BI for business, Web App for general users
- Integration of ML insights into BI dashboards
- Defined segments by combining tenure and contract type
- Geographic and service-level churn distribution analysis
- Visual storytelling approach for non-technical stakeholders

---

## 📚 References

1. [Power BI and Machine Learning Integration – Enterprise DNA](https://enterprisedna.co/blog/integrating-ml-models-in-power-bi)
2. [Microsoft Learn – AI Features in Power BI](https://learn.microsoft.com/en-us/power-bi/visuals/ai-visuals)
3. [Quanthub – Power BI AutoML Models](https://quanthub.com/creating-machine-learning-models-in-power-bi)

---

## 📬 Contact

For any queries or collaboration opportunities, feel free to connect:

**Name**: Hasitha Reddy  
**Institute**: Symbiosis Institute of Technology, Pune  
**Email**: *hasithareddye@gmail.com*

---

