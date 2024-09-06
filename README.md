# Linear Regression on Head and Brain Size Data

This project demonstrates a simple linear regression model applied to a dataset containing head size and brain weight. The goal is to predict brain weight based on head size using a linear regression model.

## Dataset

The dataset used in this project is **headbrain.csv**, which contains the following features:
- **Head Size (cm³)**: The size of the head in cubic centimeters.
- **Brain Weight (grams)**: The weight of the brain in grams.

## Requirements

To run the code, you need the following Python libraries:
- `pandas`
- `numpy`
- `matplotlib`
- `scikit-learn`

You can install them using pip:

```bash
pip install pandas numpy matplotlib scikit-learn
```

## Code Overview

1. **Data Loading and Visualization**:
   - The dataset is loaded using pandas, and the `Head Size` and `Brain Weight` are plotted using `matplotlib` to visualize the relationship between the variables.

2. **Linear Regression**:
   - The linear regression model is built using `scikit-learn`'s `LinearRegression` class.
   - The model is trained on the dataset and used to make predictions.
   - A line of best fit is plotted along with the data points to show the regression results.

3. **Evaluation**:
   - The performance of the model is evaluated using **Mean Squared Error (MSE)** and **Coefficient of Determination (R² score)**.

## Usage

1. Clone the repository or download the source code.
   
   ```bash
   git clone <repository-link>
   ```

2. Ensure the **headbrain.csv** dataset is in the same directory as the script.

3. Run the script:

   ```bash
   python linear_regression.py
   ```

4. View the scatter plot with the line of best fit and check the model's performance metrics (MSE and R²).

## Output

The script will display:
- A scatter plot of Head Size vs. Brain Weight with the linear regression line.
- The Mean Squared Error (MSE) and the Coefficient of Determination (R² score) of the model.

## Improvements

- Handle missing or outlier data.
- Split the dataset into training and testing sets for better evaluation.
- Implement other regression models for comparison.

## License

This project is open-source and available for use under the [MIT License](LICENSE).

---
