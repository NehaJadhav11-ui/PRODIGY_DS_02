# Titanic EDA - Prodigy Infotech Internship Task 2

This repository contains Exploratory Data Analysis (EDA) on the Titanic dataset as part of Task 2 of the Prodigy Infotech Internship. The objective is to explore, clean, and visualize the Titanic passenger data to find patterns related to survival.



📊 Dataset

The dataset used is from Kaggle's [Titanic - Machine Learning from Disaster](https://www.kaggle.com/competitions/titanic/data) competition.

The specific file used in this task is:
- `tested.csv` (Note: This is likely the `test.csv` file from the original dataset)

 Key Features:
- `Pclass`: Passenger class
- `Sex`, `Age`: Demographic information
- `SibSp`, `Parch`: Family aboard
- `Fare`, `Embarked`: Economic & boarding info
- `Survived`: Survival outcome (0 = No, 1 = Yes)


 📌 Task Highlights

- Data Cleaning:
  - Filled missing `Age` and `Fare` with median values.
  - Dropped irrelevant columns: `Cabin`, `Ticket`, `Name`.

- EDA:
  - Survival analysis by gender, class, age, fare, and embarkation port.
  - Visualizations using `seaborn` and `matplotlib`.
  - Correlation heatmap of numeric features.



💻 Technologies Used

- Python
- Pandas, NumPy
- Seaborn, Matplotlib
- Jupyter Notebook (Google Colab)



 🚀 How to Run

1. Clone the repository:
```bash
git clone https://github.com/yourusername/titanic-eda-task.git
cd titanic-eda-task
