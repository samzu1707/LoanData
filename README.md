## 🧭 Project Workflow

### 1️⃣ Data Loading
- Load the dataset using `pandas` with the `LoanDataLoader` class.

### 2️⃣ Data Cleaning
- Handle missing values using the `LoanDataCleaner` class:
  - Fill numerical missing values with **median**.
  - Fill categorical missing values with **mode**.

### 3️⃣ Data Visualization
- Use the `LoanDataVisualizer` class to explore the dataset:
  - **Age Distribution Plot** (histogram + KDE)
  - **Income vs Default** (boxplot)
  - **Correlation Heatmap** (numeric features)

### 4️⃣ Model Training
- Use the `LoanModelTrainer` class:
  - Train a **Logistic Regression** model
  - Evaluate accuracy and classification report

---

## 🧱 Class-Based Structure

| Class Name           | Purpose                                                                 |
|----------------------|-------------------------------------------------------------------------|
| `LoanDataLoader`     | Load data from a CSV file using `pandas`                                |
| `LoanDataCleaner`    | Clean data (handle missing values using median/mode)                    |
| `LoanDataVisualizer` | Visualize data using `matplotlib`, `seaborn`, and `numpy` (for stats)   |
| `LoanModelTrainer`   | Train and evaluate a logistic regression model using `scikit-learn`     |

---

## 🛠️ Tools & Libraries Used

| Library        | Purpose                            |
|----------------|-------------------------------------|
| `pandas`       | Data loading and manipulation       |
| `numpy`        | Numerical operations (e.g. mean)    |
| `matplotlib`   | Plotting visualizations             |
| `seaborn`      | Statistical data visualization      |
| `sklearn`      | Model training and evaluation       |

---

## 📁 File Structure

```
📂 loan-data-project/
│
├── LoanData.csv                 # Raw dataset
├── LoanData_OOP_Complete.ipynb  # Main notebook with full OOP structure
├── README.md                    # GitHub documentation (this file)
```

---

## ▶️ Getting Started

### 🔧 Installation

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

### 🚀 Run Instructions

1. Upload the `LoanData.csv` file
2. Open `LoanData_OOP_Complete.ipynb`
3. Run all cells in order

---

## 📊 Sample Output

```
✅ Data Loaded Successfully
🧹 Missing values filled
📊 Plots displayed (Age, Income vs Default, Heatmap)
🤖 Model Accuracy: 0.84
📋 Classification Report:
              precision    recall  f1-score   support
           0       0.85      0.89      0.87       190
           1       0.75      0.67      0.71        60
```

---

## 💡 Future Enhancements

- Add more ML models (Random Forest, SVM)
- Export cleaned data and predictions
- Build prediction interface using **Streamlit** or **Flask**
- Perform feature selection and parameter tuning

---

## 👤 Contributor

- **Samra Zulfiqar**  
  📧 Email: [samrazulfiqar0@gmail.com](mailto:samrazulfiqar0@gmail.com)  
  💻 GitHub: [samzu1707](https://github.com/samzu1707)

---

> 📈 *Modular code. Better maintenance. Clear insights.* 🚀
