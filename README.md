FIFA Football Players Data Analysis 🎮⚽
A comprehensive data analysis pipeline for FIFA football players dataset, featuring exploratory data analysis (EDA), data cleaning, and advanced feature engineering techniques.
📊 Project Overview
This project performs in-depth analysis of FIFA football players data, transforming raw player statistics into meaningful insights and engineered features ready for machine learning applications.
🎯 Key Features

Comprehensive EDA: Univariate, bivariate analysis
Data Quality Assessment: Missing value analysis, duplicate detection, and outlier identification
Advanced Feature Engineering: 20+ new features including composite scores, economic metrics, and categorical encodings
Professional Visualizations: Distribution plots, correlation heatmaps, and comparative analyses
Multiple Output Formats: Cleaned, engineered, and scaled datasets for different use cases

📁 Dataset Columns
The dataset includes the following player attributes:

Demographics: name, age, nationality, positions
Physical: height_cm, weight_kgs
Performance: overall_rating, potential
Economic: value_euro, wage_euro
Skills: pace, shooting, passing, dribbling, defending, physical, and 50+ detailed attributes

🔧 Installation
bash# Clone the repository
git clone https://github.com/yourusername/fifa-players-analysis.git
cd fifa-players-analysis

# Install required packages
pip install pandas numpy matplotlib seaborn
🚀 Usage
python# Run the complete analysis pipeline
python fifa_analysis.py

# Or use the Jupyter notebook
jupyter notebook fifa_analysis.ipynb
```

## 📈 Analysis Pipeline

### 1. **Exploratory Data Analysis**
- Initial data inspection and structure analysis
- Missing value patterns and data quality metrics
- Statistical summaries and distribution analysis
- Correlation analysis between features

### 2. **Data Cleaning**
- Handling missing values (median/mode imputation)
- Duplicate removal
- Outlier treatment using IQR method
- Text standardization

### 3. **Feature Engineering**

**Physical Features**
- BMI calculation
- Height-weight ratios

**Age-Based Features**
- Age groups (Young, Prime, Peak, Experienced, Veteran)
- Career stage classification

**Performance Features**
- Growth potential (potential - current rating)
- Rating categories (Bronze, Silver, Gold, Elite, World Class)

**Economic Features**
- Value-to-wage ratio (investment efficiency)
- Value per remaining career year

**Composite Skill Scores**
- Attacking score (avg of 9 offensive attributes)
- Defensive score (avg of 4 defensive attributes)
- Physical score (avg of 7 physical attributes)
- Mental score (avg of 5 technical/mental attributes)

**Position Features**
- Primary position extraction
- Position category (Goalkeeper/Defender/Midfielder/Forward)

**Encoded Features**
- One-hot encoding for categorical variables
- Binary encoding for preferred foot
- Label encoding for body types
- Feature scaling (Min-Max normalization)

## 📊 Output Files

The pipeline generates three processed datasets:

1. **`fifa_players_cleaned.csv`**: Basic cleaning applied, ready for visualization
2. **`fifa_players_engineered.csv`**: All new features included, ready for ML models
3. **`fifa_players_scaled.csv`**: Normalized features for distance-based algorithms

## 🔍 Key Insights

The analysis reveals:
- Age vs performance relationships
- Physical attribute correlations
- Market value determinants
- Position-specific skill patterns
- Nationality and talent distribution
- Young prospect identification
- Value-for-money player analysis

## 📸 Visualizations

The notebook includes:
- Distribution plots for age, height, weight, BMI, ratings
- Top nationalities and positions bar charts
- Skill attribute distributions
- Correlation heatmaps
- Scatter plots for key relationships
- Box plots for outlier detection

## 🛠️ Technologies Used

- **Python 3.x**
- **Pandas**: Data manipulation and analysis
- **NumPy**: Numerical computations
- **Matplotlib**: Static visualizations
- **Seaborn**: Statistical visualizations

## 📝 Project Structure
```
fifa-players-analysis/
│
├── fifa_analysis.ipynb              # Main analysis script
├── fifa_players.csv              # Raw dataset (add your file)
├── fifa_players_cleaned.csv      # Output: Cleaned data
├── fifa_players_engineered.csv   # Output: Feature engineered data
├── fifa_players_scaled.csv       # Output: Scaled data
├── README.md                     # Project documentation  
🎓 Learning Outcomes
This project demonstrates:

End-to-end data analysis workflow
Statistical analysis and interpretation
Feature engineering best practices
Data visualization techniques
Handling real-world messy data
Preparing data for machine learning


FIFA dataset from Kaggle
