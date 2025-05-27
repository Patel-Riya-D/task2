# task2

# 🚢 Task-2 : Exploratory Data Analysis (EDA)

Welcome aboard! This repository contains a complete Exploratory Data Analysis of the famous **Titanic dataset** — where data meets disaster, and insights emerge from the depths.

---

## 🎯 Objective

Use data visualization and statistics to explore survival patterns on the Titanic.  
Understand how features like **age**, **gender**, **passenger class**, and **embark location** influenced survival.

---

## 🛠️ Tools & Libraries

| Tool          | Purpose                          |
|---------------|----------------------------------|
| `pandas`      | Data loading & manipulation      |
| `seaborn`     | Statistical visualizations        |
| `matplotlib`  | Plotting basic graphs            |
| `plotly`      | Interactive visualizations       |
| `numpy`       | Numerical operations             |

---

## 🧪 EDA Checklist ✔

| Step | Task Description                              | Status |
|------|-----------------------------------------------|--------|
| 1    | Load data and inspect structure               | ✅     |
| 2    | Handle missing values                         | ✅     |
| 3    | Summary statistics                            | ✅     |
| 4    | Histograms of numerical columns               | ✅     |
| 5    | Boxplots to detect outliers                   | ✅     |
| 6    | Correlation matrix & heatmap                  | ✅     |
| 7    | Pairplots to visualize feature relationships  | ✅     |
| 8    | Countplots for categorical distributions      | ✅     |
| 9    | Age group creation and analysis               | ✅     |
| 10   | Barplots: survival by class & gender          | ✅     |
| 11   | Interactive plots (optional)                  | ✅     |
| 12   | Final conclusion + insights                   | ✅     |

---

## 📊 Key Insights

🔹 Women and children had **higher survival rates**  
🔹 Passengers from **1st class** were more likely to survive  
🔹 Most passengers embarked from **Southampton**  
🔹 **Fare** had a strong positive skew and outliers  
🔹 **Age** had missing values, handled using **median**  
🔹 **Embarked** was imputed using **mode** (`S` - Southampton)

---

## 📷 Visualization 

## 🎨 1. Histograms (Numeric Features)

![titanic_histogram_combined](https://github.com/user-attachments/assets/fa7b8dd2-d30f-4ce6-b0cd-3f1916c8e2fb)

- Distributions of `Age`, `Fare`, `SibSp`, `Parch`.
- `Fare` is highly right-skewed; `Age` clusters around 20–40.

## 📦 2. Boxplots (Outlier Detection)
| Feature   | Insights                                 |
|-----------|-------------------------------------------|
| **Age**   | Outliers: children & seniors              |
| **Fare**  | Very high fare outliers (> $500)          |
| **SibSp** | Most had 0–1 siblings/spouses             |
| **Parch** | Most had no parents/children aboard       |

## 📑 3. Countplots (Categorical Distributions)
| Feature     | Insight                                |
|-------------|------------------------------------------|
| **Pclass**   | Most were 3rd class passengers           |
| **Sex**      | More males than females onboard          |
| **Embarked** | Majority boarded from Southampton (`S`) |
| **Survived** | ~38% survived, 62% did not               |

## 🔗 4. Correlation Heatmap
- `Fare` and `Pclass` are negatively correlated.
- Low correlation across other features.

## 🧮 5. Pairplot (Feature Interactions)

![image](https://github.com/user-attachments/assets/325a9be6-af9b-4499-978a-34478ef6662c)

- Shows survival clustering by `Fare`, `Pclass`, and `Age`.
- Higher survival in higher fare and lower class numbers.

## 👶 6. Age Group vs Survival
- Children had the **highest survival rate**.
- Adults and seniors less likely to survive.

## 👨‍👩‍👧 7. Survival by Class & Gender
- **Women in 1st/2nd class** survived most.
- **Men in 3rd class** had lowest survival rate.

## 📈 8. Fare Distribution vs Survival (Interactive)
- Survivors generally paid **higher fares**.
- Indicates socioeconomic impact on survival.

---


  





