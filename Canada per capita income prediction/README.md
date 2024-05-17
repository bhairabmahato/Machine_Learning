# Linear Regression Analysis on Canada's Per Capita Income

This project performs a linear regression analysis on the per capita income data of Canada. The data is read from a CSV file and visualized using a scatter plot. A linear regression model is then trained to predict the per capita income for future years.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Code Explanation](#code-explanation)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Installation

To run this project, you need to have Python installed along with the following packages:
- pandas
- numpy
- matplotlib
- scikit-learn

You can install the required packages using pip:

```bash
pip install pandas numpy matplotlib scikit-learn
```

## Usage

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/your-repo-name.git
    ```

2. Navigate to the project directory:

    ```bash
    cd your-repo-name
    ```

3. Ensure the CSV file `canada_per_capita_income.csv` is in the project directory.

4. Run the script:

    ```bash
    python your_script_name.py
    ```

### Steps:

1. **Data Import**: The CSV file `canada_per_capita_income.csv` is read into a DataFrame.
2. **Data Visualization**: A scatter plot is created to visualize the relationship between the year and per capita income.
3. **Feature Selection**: The year is selected as the feature (X), and the per capita income is the target variable (y).
4. **Model Training**: A linear regression model is created and trained using the data.
5. **Prediction**: The model predicts the per capita income for the year 2025.
6. **Model Evaluation**: The model's performance score is calculated.

## Results

The linear regression model provides a prediction for Canada's per capita income in 2025 and a score indicating the fit of the model to the data. In this case, the model score is -0.8909, which suggests that the model may not fit the data well. This negative score indicates that a simple mean-based prediction would be more accurate than the linear model provided.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your changes. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
