# Titanic Survival Analysis  

**Author:** Samuel Cardona Ochoa.

---

## Project Overview  

This project explores the Titanic dataset to analyze which factors influenced passenger survival during the disaster. Using Python, Pandas, and visualization libraries, the goal is to clean, process, and analyze the dataset to extract meaningful insights and communicate findings effectively.  

---

## Objectives  

- Manipulate structured data using Pandas (filters, groupings, transformations).  
- Apply data preprocessing and cleaning techniques.  
- Generate visualizations to identify patterns and insights.  
- Derive conclusions based on statistical analysis.  

---

## Dataset  

The dataset used comes from Kaggle’s Titanic competition:  
🔗 [Titanic - Machine Learning from Disaster](https://www.kaggle.com/c/titanic/data)  

From the provided files, the main focus is on:  
- `train.csv`  

Additional background information on the Titanic can be found here:  
🔗 [National Geographic: The Titanic Story](https://historia.nationalgeographic.com.es/a/historia-titanic-tragedia-barco-insumergible_16344)  

---

## Project Structure  

### 1. Data Loading  
- Import and preview the Titanic dataset.  

### 2. Data Profiling  
- Description of variables (meaning and data type).  
- Identification of missing values in **Age**, **Sex**, and **Survived**.  

### 3. Preprocessing and Cleaning  
- Remove records with missing values and report the remaining dataset size.  
- Create a new column for **Family Size**.  
- Encode categorical variables (**Sex** and **Embarked**) into numerical representations, with a clear explanation of the mapping.  

### 4. Statistical Analysis  
- Calculate the **overall survival rate**.  
- Calculate survival rates by:  
  - Passenger Class  
  - Gender  
  - Age groups  
  - Family size groups  
  - Port of Embarkation  

### 5. Visualizations  
- Create plots with proper titles, labeled axes, and legends to illustrate survival by:  
  - Class  
  - Gender  
  - Age  
  - Port of Embarkation  

### 6. Findings  
- Identify the factors with the strongest impact on survival.  
- Describe any unexpected patterns or insights.  

---

## Technologies Used  

- Python  
- Pandas – Data manipulation  
- Matplotlib & Seaborn – Data visualization  

---

## Example Insights  

- Were women and children more likely to survive?  
- Did passenger class influence chances of survival?  
- Was family size related to survival probability?  

---

## How to Run  

1. Download the dataset from Kaggle and place `train.csv` in the project folder.  
2. Open the Jupyter notebook provided in the repository.  
3. Run all cells to reproduce the analysis.  

---

## License  

This project was created for portfolio and educational purposes.
