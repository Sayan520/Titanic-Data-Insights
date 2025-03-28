# Titanic-Data-Insights 🚢

This project performs exploratory data analysis (EDA) on the Titanic dataset to understand factors that influenced passenger survival.

## Project Overview

The analysis involves the following steps:
1. **Import Libraries** - Load essential Python libraries for data manipulation and visualization.
2. **Load the Dataset** - Import the Titanic dataset using Pandas.
3. **Perform Data Overview** - Explore basic statistics and gain insights into the data.
4. **Handle Missing Data** - Clean and preprocess the data by handling missing values.
5. **Analyze Passenger Data** - Investigate survival rates by gender and class.
6. **Calculate Fare Statistics** - Calculate average, minimum, and maximum fares paid by passengers.
7. **Find Correlations** - Analyze correlations between various features.
8. **Classify Data by Passenger Class** - Explore survival trends across different passenger classes.
9. **Save Cleaned Data** - Export the cleaned dataset to a CSV file.

## Additional Enhancements

- **Data Cleaning Explanation**: A detailed explanation of the data cleaning steps.
- **Visualizations**: Additional box plots to visualize fare and age distributions by survival status.
- **Model Evaluation**: Implementation of cross-validation to ensure more reliable model performance.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Jupyter Notebook

### The data set
| Variable Name |  Variable Description |
|---------------|-----------------------|
|PassengerID| Passenger ID|
|   Survived  |  Survival (0 = No; 1 = Yes)|
|Pclass|Passenger Class (1 = 1st; 2 = 2nd; 3 = 3rd)|
|Name|Name|
|Sex|Sex|
|Age|Age|
|SibSp| Number of Siblings/Spouses Aboard|
|Parch|Number of Parents/Children Aboard|
|Ticket|Ticket Number|
|Fare|Passenger Fare|
|Cabin|Cabin|
|Embarked|Port of Embarkation (C = Cherbourg; Q = Queenstown; S = Southampton)|


You can view a description of this dataset on the [Kaggle website](https://www.kaggle.com/c/titanic)- the original source.

## Results

The project reveals insightful findings about survival rates based on gender, passenger class, and fare. Notably:
- Females had a higher survival rate compared to males.
- First-class passengers had a significantly higher survival rate than lower classes.
- Higher fares were associated with better survival chances.

## How to Run the Project

1. Clone the repository:
    ```bash
    git clone https://github.com/Sayan520/Titanic-Data-Insights.git
    cd Titanic-Data-Insights
    ```
2. Install the required packages:
    ```bash
    pip install -r requirements.txt 
    ```
3. Run the Jupyter Notebook:
    ```bash
    jupyter lab
    ```

## Contributing

Contributions are welcome! Please follow these steps:
- Fork the repository.
- Create a new branch.
- Make your changes.
- Submit a pull request.

## License

This project is licensed under the MIT License.

