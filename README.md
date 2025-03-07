# Polynomial Regression for Salary Prediction  

This project demonstrates the implementation of **Polynomial Regression** to predict salaries based on position levels in a company. It compares the performance of **Linear Regression** and **Polynomial Regression** models on a dataset representing the relationship between position levels and corresponding salaries.  

##  Project Overview  

The goal of this project is to predict an employee's salary based on their **position level** in a company. The dataset includes position levels ranging from **1 to 10** and their corresponding salaries. We apply both **Linear Regression** and **Polynomial Regression** techniques to model the data and visualize the results, comparing their effectiveness.  

##  Dataset  

The dataset used in this project is **Position_Salaries.csv**, which contains the following columns:  

- **Level**: The position level in the company (integer values from 1 to 10).  
- **Salary**: The salary corresponding to each position level.  

The dataset can be obtained from a simulated source or a publicly available dataset on salary data.  

##  Technologies Used  

- **Python**  
- **NumPy**  
- **Pandas**  
- **Matplotlib**  
- **Scikit-learn**  

##  Steps Involved  

### 1. Importing Libraries  
We import necessary libraries such as `numpy`, `pandas`, `matplotlib`, and `sklearn` for data manipulation, visualization, and machine learning tasks.  

### 2. Loading the Dataset  
The dataset **Position_Salaries.csv** is loaded into a pandas DataFrame. We extract the **Position Level** and **Salary** values for training the model.  

### 3. Training Linear Regression  
A **Linear Regression** model is trained using the dataset to predict salaries based on position levels.  

### 4. Training Polynomial Regression  
We use `PolynomialFeatures` from **scikit-learn** to transform the input data into polynomial features and train a second **Linear Regression** model on these transformed features.  

### 5. Visualization  
- The results of **Linear Regression** are visualized by plotting the actual salary data and the regression line.  
- The results of **Polynomial Regression** are visualized by plotting the actual salary data and the smooth polynomial curve.  
- A **high-resolution curve** is also plotted to provide a clearer view of how well the **polynomial regression** fits the data.  

### 6. Prediction  
Predictions are made for a new **position level (e.g., 6.5)** using both **Linear Regression** and **Polynomial Regression**, showcasing the difference in predictions between the two models.  

##  Results & Insights  

- **Linear Regression** provides a straight-line fit, which may not capture the **non-linear** relationship between position level and salary.  
- **Polynomial Regression** provides a **more accurate** fit, as it captures the **curved trend** in the data.  
- The predictions using **Polynomial Regression** are generally more reliable for non-linear salary structures.  

##  Installation & Usage  

1. Clone the repository:  
   ```sh
   git clone https://github.com/your-username/your-repo-name.git
