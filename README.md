# 🍷 Red Wine Quality Analyzer

A machine learning project that analyzes physicochemical properties of red wine to predict quality ratings using classification models like **Random Forest** and **Decision Tree**. This project demonstrates practical skills in **data science, feature engineering, model evaluation, and hyperparameter tuning** — all delivered through a clean, interactive HTML report.

🔗 **Live Demo**: [View Project](https://yasminjd.github.io/Red-Wine-Quality-Analyzer/)

---

## 💡 Project Highlights
- **Goal**: Predict wine quality (scale of 3–8) using supervised ML classification techniques.
- **Outcome**: Achieved ~70% accuracy using Random Forest with hyperparameter tuning and class weight balancing.
- **Bonus**: Detailed EDA and model interpretability using feature importance visualizations and heatmaps.

---

## ⚙️ Tech Stack & Tools

| Category            | Tools / Libraries Used                                  |
|---------------------|----------------------------------------------------------|
| Data Processing     | `pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn` |
| Machine Learning    | `RandomForestClassifier`, `DecisionTreeClassifier`, `GridSearchCV` |
| Visualization       | `matplotlib`, `seaborn` (heatmaps, bar plots, line plots) |
| Evaluation Metrics  | Accuracy, Precision, Recall, F1-Score, Confusion Matrix  |
| Deployment          | Exported Jupyter notebook as static HTML for GitHub Pages |

---

## 📊 Models & Evaluation

### 🔁 Models Trained
- **Random Forest Classifier**
- **Decision Tree Classifier**

### ✅ Evaluation Strategy
- **Train/Test Split** (80/20)
- **Cross Validation** (`GridSearchCV`)
- **Class Imbalance Handling** (via `class_weight=balanced`)
- **Performance Metrics**:
  - Accuracy: 70% (Random Forest)
  - Precision, Recall, and F1-Scores across all classes
  - Visualizations of feature importance and correlation heatmaps

---

## 🔬 Key Insights
- **Random Forest** outperformed Decision Tree in both accuracy and balanced predictions.
- Both models struggled with minority classes (e.g., wines rated 3, 4, and 8).
- Feature importance revealed that **alcohol**, **sulphates**, and **pH** were most predictive.
- Addressing **class imbalance** remains a challenge for further improvements.

---

## 📁 Project Structure
Red-Wine-Quality-Analyzer/
├── index.html           # Full interactive notebook exported as HTML
├── README.md            # This file
