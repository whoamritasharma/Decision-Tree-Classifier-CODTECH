# Decision-Tree-Classifier-CODTECH

## 📋 Project Overview

This project implements a **Decision Tree Classifier** using scikit-learn to classify the famous Iris dataset. The project includes comprehensive data analysis, model visualization, and performance evaluation.

**Internship:** CODTECH  
**Task:** Task 1 - Build and Visualize a Decision Tree Model  
**Deliverable:** Notebook with model visualization and analysis

---

## 🎯 Objectives

- Build a Decision Tree model using scikit-learn
- Visualize the decision tree structure
- Analyze model performance with various metrics
- Understand feature importance in classification
- Compare different tree depths for optimal performance

---

## 📊 Dataset

**Dataset Used:** Iris Dataset (Built-in scikit-learn dataset)

- **Samples:** 150
- **Features:** 4 (sepal length, sepal width, petal length, petal width)
- **Classes:** 3 (Setosa, Versicolor, Virginica)
- **Type:** Multiclass classification

---

## 🛠️ Technologies Used

- **Python 3.8+**
- **Libraries:**
  - `scikit-learn` - Machine learning algorithms
  - `pandas` - Data manipulation
  - `numpy` - Numerical computations
  - `matplotlib` - Data visualization
  - `seaborn` - Statistical visualizations

---

## 📁 Project Structure

```
decision-tree-task1/
│
├── decision_tree_analysis.ipynb    # Main Jupyter notebook
├── README.md                        # Project documentation
└── requirements.txt                 # Python dependencies
```

---

## 🚀 Getting Started

### Prerequisites

Make sure you have Python 3.8 or higher installed on your system.

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/decision-tree-task1.git
   cd decision-tree-task1
   ```

2. **Create a virtual environment (optional but recommended):**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install required packages:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Launch Jupyter Notebook:**
   ```bash
   jupyter notebook decision_tree_analysis.ipynb
   ```

---

## 📈 Key Features

### 1. **Data Exploration**
- Statistical summary of features
- Class distribution analysis
- Correlation heatmap
- Pairplot visualization

### 2. **Model Building**
- Decision Tree Classifier implementation
- Train-test split (80-20)
- Model training and prediction

### 3. **Model Evaluation**
- Accuracy scores (training & testing)
- Cross-validation (5-fold)
- Classification report
- Confusion matrix

### 4. **Visualizations**
- Complete decision tree structure
- Feature importance ranking
- Model performance vs tree depth
- Confusion matrix heatmap

### 5. **Analysis**
- Feature importance analysis
- Overfitting detection
- Optimal depth determination
- Sample predictions with probabilities

---

## 📊 Results

| Metric | Score |
|--------|-------|
| **Training Accuracy** | ~97-100% |
| **Testing Accuracy** | ~95-100% |
| **Cross-Validation Score** | ~95% (±5%) |
| **Optimal Tree Depth** | 3-4 levels |

**Most Important Features:**
1. Petal length
2. Petal width
3. Sepal length
4. Sepal width

---

## 🔍 Model Insights

### Advantages of Decision Trees:
✅ Easy to understand and interpret  
✅ Requires minimal data preprocessing  
✅ Handles both numerical and categorical data  
✅ No assumptions about data distribution  
✅ Visual representation of decision-making process

### Limitations:
⚠️ Prone to overfitting with deep trees  
⚠️ Sensitive to small variations in data  
⚠️ Can create biased trees with imbalanced classes

---

## 📸 Sample Visualizations

The notebook includes:
- **Decision Tree Diagram** - Full tree structure with split conditions
- **Feature Importance Chart** - Bar chart showing feature contributions
- **Confusion Matrix** - Heatmap of predictions vs actual values
- **Performance Curves** - Accuracy vs tree depth analysis
- **Pairplots** - Feature relationships colored by species

---

## 💡 Usage

Run all cells in the notebook sequentially to:
1. Load and explore the Iris dataset
2. Train the Decision Tree model
3. Evaluate model performance
4. Visualize the decision tree and results
5. Analyze feature importance

---


## 🙏 Acknowledgments

- CODTECH for the internship opportunity
- Scikit-learn documentation
- UCI Machine Learning Repository for the Iris dataset

---

## 📞 Contact

For any questions or feedback, please reach out:
- **Email:** whoamritasharma@gmail.com

---

*This project fulfills the requirements for CODTECH Internship Task 1*
