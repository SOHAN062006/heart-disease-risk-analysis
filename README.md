# 🏥 Heart Disease Risk Analysis

## 📌 Problem Statement
This project analyzes heart disease risk factors using a comprehensive dataset from Kaggle. The analysis identifies key patterns, correlations, and demographic risk factors to help understand heart disease prevalence across different patient populations.

## 📁 Dataset
- **Source**: Kaggle Heart Disease Dataset
- **File**: `dataset/heart.csv`
- **Size**: Multiple patient records with health indicators
- **Key Features**: Age, Gender, Cholesterol, Blood Pressure, Chest Pain Type, and Target (Heart Disease presence)

## 🛠️ Tools & Libraries
- **Python 3.x**
- **Pandas** - Data manipulation and analysis
- **NumPy** - Numerical computations
- **Matplotlib** - Static visualization
- **Seaborn** - Statistical visualization
- **Jupyter** - Interactive notebook environment

## 📊 Key Analyses Performed
1. **Exploratory Data Analysis (EDA)** - Understanding data structure and distributions
2. **Age vs Disease Risk** - Correlation between age and heart disease prevalence
3. **Gender-based Risk Analysis** - Comparative risk between male and female patients
4. **Cholesterol Distribution** - Understanding cholesterol levels across populations
5. **Correlation Heatmap** - Identifying relationships between variables
6. **Chest Pain Type Analysis** - Impact of chest pain symptoms on disease diagnosis
7. **Target Distribution** - Overall disease prevalence in dataset

## 💡 Key Insights
- [Your insights will go here after running the analysis]
- Risk factors vary significantly by age and gender
- Cholesterol levels show strong correlation with disease presence
- Chest pain type is a strong predictor of heart disease

## 📸 Visualizations
All charts are saved in the `visuals/` folder:
- `age_vs_disease.png` - Age distribution across disease cases
- `gender_risk.png` - Risk comparison by gender
- `cholesterol_dist.png` - Cholesterol distribution analysis
- `correlation_heatmap.png` - Feature correlation matrix
- `chest_pain_analysis.png` - Chest pain type analysis
- `target_distribution.png` - Overall disease prevalence

## 📄 Report
- **File**: `report/insights_summary.pdf`
- A concise 1-page summary of key findings and recommendations

## 🚀 How to Run

### 1. Install Dependencies
```bash
pip install -r requirements.txt
```

### 2. Launch Jupyter Notebook
```bash
jupyter notebook
```

### 3. Open and Run the Analysis
- Navigate to `notebooks/heart_disease_analysis.ipynb`
- Run all cells to generate visualizations and insights

### 4. View Results
- Check `visuals/` folder for generated charts
- Review `report/insights_summary.pdf` for key findings

## 📝 Project Structure
```
heart-disease-risk-analysis/
│
├── 📁 dataset/
│   └── heart.csv                      # Raw dataset
│
├── 📁 notebooks/
│   └── heart_disease_analysis.ipynb   # Main analysis notebook
│
├── 📁 visuals/
│   ├── age_vs_disease.png
│   ├── gender_risk.png
│   ├── cholesterol_dist.png
│   ├── correlation_heatmap.png
│   ├── chest_pain_analysis.png
│   └── target_distribution.png
│
├── 📁 report/
│   └── insights_summary.pdf
│
├── requirements.txt
└── README.md
```

## 👨‍💻 Author
[Your Name]

## 📜 License
MIT License

## 🤝 Contributing
Feel free to fork, modify, and improve this project!
