# Bank Marketing Campaign Analysis

This project analyzes the effectiveness of direct marketing campaigns by a Portuguese bank. It uses machine learning models to predict whether a customer will subscribe to a term deposit, aiming to improve marketing strategies. The project combines **Python**, **MySQL**, and **Power BI** for data analysis, visualization, and model building, with development managed using **Visual Studio Code (VS Code)**.

## Tools and Versions

- **Programming Language**: Python 3.11.0
- **Database**: MySQL Workbench 8.0.38
- **Data Visualization**: Power BI Desktop version 2.136.1202.0
  - Project file: `Visualization_Bank_Project.pbix`
- **Development Environment**: VS Code 1.95.2
  - **Extensions**:
    - MySQL 7.6.5 extension for database management.
    - Markdown All in One v3.6.2 for improved Markdown functionality.
    
## Project Files

- **SQL File**: `Create_database.sql` – Defines the database schema and structure for the project.
- **Power BI File**: `Visualization_Bank_Project.pbix` – Contains dashboards and reports for data visualization.
- **Notebook File**: `Marjanrafiee_Bankmarketing_Capstone.ipynb` – The main Python script for data analysis and model development.
- **Excel Files**: Three files extracted from the main dataset to be imported into Power BI for visualization.

## Project Workflow

### 1. **Establishing Connection in MySQL**
   - Creating a MySQL connection interface.
   - Setting up database connectivity parameters.

### 2. **Database and Table Creation**
   - Creating the database structure.
   - Designing the table schema.
   - Importing Excel data into MySQL using Python code.
   - Writing the SQL file `Create_database.sql` for database creation.

### 3. **Data Loading**
   - Establishing a Python-MySQL connection.
   - Loading data into the Python environment.
   - Performing initial data verification through the notebook file.

### 4. **Data Cleaning**
   - Handling missing values.
   - Removing duplicates.
   - Correcting data types.
   - Standardizing formats.

### 5. **Data Analysis**
   - Conducting Exploratory Data Analysis (EDA).
   - Performing statistical and distribution analyses.
   - Studying feature correlations.

### 6. **Feature Engineering**
   - Creating new features.
   - Transforming existing features.
   - Encoding categorical variables.
   - Scaling features.

### 7. **Model Development and Optimization**
   - Building baseline models.
   - Hyperparameter tuning.
   - Evaluating and comparing model performance.

### 8. **Ensemble Modeling**
   - Selecting the best-performing models.
   - Implementing ensemble techniques (Voting, Stacking).
   - Optimizing ensemble parameters.
   - Comparing ensemble performance.

### 9. **Final Model Selection**
   - Identifying the best-performing model.
   - Analyzing feature importance.
   - Validating the model.
   - Evaluating performance metrics.

### 10. **Business Insights and Recommendations**
   - Extracting actionable business insights.
   - Developing recommendations based on model results.
   - Preparing performance reports.
   - Suggesting future improvements.

### 11. **Data Extraction for Power BI**
   - Exporting processed data for import into Power BI.
   - Creating interactive dashboards to visualize business insights.


## Usage

1. **Database Setup**
   - Run `Create_database.sql` in MySQL Workbench (8.0.38) to set up the database.

2. **Run the Jupyter Notebook**
   - Open the notebook file:
     `jupyter notebook Marjanrafiee_Bankmarketing_Capstone.ipynb`
   - Follow the notebook steps to:
     - Load data from MySQL.
     - Preprocess, analyze, and model the data.

3. **Visualize Data in Power BI**
   - Import the Excel files and processed data into Power BI using the `Visualization_Bank_Project.pbix` file.

