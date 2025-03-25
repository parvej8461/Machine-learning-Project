```markdown
# Health Insurance Risk Classification: Boosting vs. Bagging Comparison

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-1.2.2-orange)
![XGBoost](https://img.shields.io/badge/XGBoost-1.7-green)
![LightGBM](https://img.shields.io/badge/LightGBM-3.3-yellowgreen)

A machine learning project comparing ensemble methods (bagging and boosting) to classify applicants as "healthy" or "unhealthy" for insurance premium optimization. Achieves **95% F1-score** using LightGBM/XGBoost.

## 📌 Key Features
- **10+ ML Models Tested**: Decision Trees, Random Forest, AdaBoost, XGBoost, LightGBM, CatBoost
- **Optimal Performance**: LightGBM achieves 0.95 F1-score on test data
- **Feature Analysis**: Identifies top health indicators (BMI, Blood Pressure, Cholesterol)
- **Production-Ready**: Includes hyperparameter tuning and OOB error analysis

## 📊 Results Summary
| Model                  | Train F1 | Test F1 |
|------------------------|----------|---------|
| Decision Tree (Simple) | 0.99     | 0.90    |
| Random Forest          | 0.94     | 0.93    |
| XGBoost                | 1.00     | 0.95    |
| **LightGBM**           | **0.98** | **0.95** |

![OOB Error Analysis](assets/oob_error_plot.png) *(Example visualization)*

## 🛠 Installation
```bash
git clone https://github.com/yourusername/health-insurance-classification.git
cd health-insurance-classification
pip install -r requirements.txt
```

## 🚀 Usage
1. Preprocess data:
```python
python preprocess.py
```

2. Train all models:
```python
python train.py
```

3. Evaluate performance:
```python
python evaluate.py
```

## 📂 Project Structure
```
├── data/
│   ├── Healthcare_Dataset_Preprocessednew.csv
├── notebooks/
│   ├── EDA.ipynb
│   ├── Model_Comparison.ipynb
├── src/
│   ├── preprocess.py
│   ├── train.py
│   ├── evaluate.py
├── assets/               # Visualizations
├── requirements.txt
└── README.md
```

## 🤝 Contributing
Pull requests welcome! For major changes, please open an issue first.

## 📜 License
MIT

```



