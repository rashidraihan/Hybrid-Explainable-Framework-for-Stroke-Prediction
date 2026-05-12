# Hybrid Explainable Framework for Stroke Prediction

Hybrid Explainable Framework for Stroke Prediction is an advanced AI-powered system for early stroke prediction that combines machine learning, deep learning, and explainable AI techniques. This comprehensive framework enhances predictive accuracy while ensuring clinical interpretability for healthcare applications.

## 📊 Data Analysis & Exploratory Data Analysis

### Class Distribution Analysis
<img width="1771" height="1168" alt="target_distribution" src="https://github.com/user-attachments/assets/719dbb29-bc6d-4ad3-a38e-e3b1f077f1a9" />

The dataset exhibits significant class imbalance with only 4.9% stroke-positive cases, necessitating advanced resampling techniques for robust model training.

### Univariate Distributions by Stroke Status
<img width="2348" height="1454" alt="age_distribution_by_stroke" src="https://github.com/user-attachments/assets/2fa31d19-675d-4d00-be78-3ee97a30fc03" />


**Age Analysis**: Stroke-positive individuals show distinct age distribution patterns, with higher risk observed in older demographic groups.

<img width="2350" height="1454" alt="bmi_distribution_by_stroke" src="https://github.com/user-attachments/assets/1a2c3e8a-6577-4d06-baed-3c840c95dd7f" />

**BMI Analysis**: Body Mass Index distributions reveal subtle differences between stroke and non-stroke cases, informing feature engineering strategies.

<img width="2350" height="1454" alt="avg_glucose_level_distribution_by_stroke" src="https://github.com/user-attachments/assets/3742e2c1-5c77-430f-84ed-62c641723708" />

**Glucose Level Analysis**: Average glucose levels demonstrate significant variations between stroke-positive and negative cases, highlighting its importance as a clinical predictor.

## 📈 Model Performance Evaluation

### Comprehensive Model Comparison
<img width="4500" height="2400" alt="metrics_grid" src="https://github.com/user-attachments/assets/fa4970ba-d011-427c-826e-d3a007560ce3" />

Multi-faceted evaluation across 12 machine learning algorithms demonstrating performance trade-offs across accuracy, F1-score, precision, recall, ROC-AUC, and PR-AUC metrics.

### ROC Curve Analysis
<img width="3600" height="2700" alt="image" src="https://github.com/user-attachments/assets/8f468c69-cb61-4066-9b01-2eb97672469b" />

Receiver Operating Characteristic curves showing strong discriminative power across all evaluated models, with consistent performance across different classification thresholds and excellent area under curve values.

## 🔬 Explainable AI (XAI)

### Integrated Feature Importance Analysis
<img width="3103" height="2369" alt="shap_lime_tabnet_fn_approx_final_labeled_quantile" src="https://github.com/user-attachments/assets/4650ab9e-49f4-4052-b0f0-20ce7971130c" />

Combined SHAP and LIME analysis revealing key clinical features contributing to stroke prediction, with age and glucose levels emerging as dominant risk factors in model decision-making.

## 🏗️ Technical Architecture

### End-to-End Prediction Pipeline
Our framework implements a comprehensive workflow:

1. **Data Preprocessing**: Handling class imbalance, missing values, and feature normalization
2. **Feature Engineering**: Clinical feature transformation and selection
3. **Hybrid Modeling**: Machine learning and deep learning ensemble approaches
4. **Model Interpretation**: Explainable AI techniques for clinical transparency
5. **Performance Validation**: Comprehensive evaluation across multiple metrics

## 🔧 Key Features

- **🤖 Hybrid AI Approach**: Combines traditional machine learning and modern deep learning models
- **🔍 Explainable Predictions**: Transparent feature importance for clinical trust
- **🔄 Robust Preprocessing**: Advanced handling of class imbalance and data quality
- **📊 Comprehensive Evaluation**: Multi-metric assessment across diverse algorithms
- **🏥 Clinical Relevance**: Domain-informed feature selection and interpretation
- **⚡ Scalable Architecture**: Modular design for healthcare integration

## 🛠️ Technical Stack

- **Programming**: Python 3.8+
- **Machine Learning**: Scikit-learn, XGBoost, LightGBM
- **Deep Learning**: PyTorch-based architectures
- **Explainable AI**: SHAP, LIME for model interpretability
- **Visualization**: Matplotlib, Seaborn, Plotly
- **Data Processing**: Pandas, NumPy for efficient data manipulation
- **Model Optimization**: Advanced hyperparameter tuning techniques

## 📁 Repository Structure

```
Hybrid-Stroke-Prediction/
├── src/
│   ├── data_preprocessing/       # Data cleaning and preparation pipelines
│   ├── feature_engineering/      # Feature selection and transformation
│   ├── models & evaluation/      # Model implementations & performance assessment
├── config/                       # Model and experiment configurations
├── tests/                        # Comprehensive test suites
├── requirements.txt              # Project dependencies
└── README.md                     # Project documentation
```

## 🎯 Research Contributions

### 1. Clinical AI Integration
Bridges the gap between high-performance AI models and clinical practicality through interpretable and actionable predictions.

### 2. Advanced Modeling Strategy
Implementation of both traditional machine learning algorithms and modern deep learning architectures for comprehensive predictive performance.

### 3. Explainable Healthcare AI
Transparent model reasoning enabling clinical validation and trust in AI-assisted decision making.

### 4. Robust Evaluation Framework
Multi-dimensional assessment across accuracy, sensitivity, specificity, and clinical relevance metrics.

## 📊 Performance Highlights

- **Strong Predictive Performance**: Comprehensive model evaluation demonstrating reliable stroke prediction capabilities across multiple algorithms
- **Clinical Interpretability**: Transparent feature importance analysis aligning with medical domain knowledge
- **Robust Generalization**: Consistent performance across different validation strategies and data splits
- **Scalable Architecture**: Modular design suitable for integration with healthcare systems

## 🔬 Methodology Overview

Our systematic approach encompasses:

1. **Comprehensive Data Analysis**: In-depth exploratory data analysis to understand feature distributions and relationships
2. **Advanced Feature Engineering**: Domain-informed transformations and selection techniques
3. **Diverse Model Development**: Implementation of multiple machine learning and deep learning approaches
4. **Rigorous Evaluation**: Multi-faceted assessment including performance metrics and model interpretability
5. **Clinical Validation**: Framework designed for healthcare professional review and practical application

*© 2026 Raihan Rashid. All rights reserved.*
