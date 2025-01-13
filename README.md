# Public-Transportation-schedule-using-regression
An Ml model based on the regression for predicting no.of buses in between the terminals
-------------------------------------------------------------------------------------
This project is a Streamlit application that predicts the number of buses required for a public transport system based on input data. The app uses gradient descent for linear regression and allows users to interactively upload datasets, train the model, and make predictions.

## Features
- Upload CSV files containing public transport data.
- Preprocess the dataset to handle missing values and encode categorical variables.
- Train a linear regression model using gradient descent.
- Evaluate the model's performance and display the mean squared error (MSE).
- Make predictions for the number of buses required based on user input.

## Dataset Requirements
The input CSV file should have the following columns:
- `No. of buses of that type` (numeric)
- `No. of bus terminals` (numeric)
- `No. of bus stands` (numeric)
- `No. of bus stops` (numeric)
- `Type Of Bus (Ac / Non Ac)` (categorical)

## How to Run the Application
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/public-transport-schedule-optimization.git
   cd public-transport-schedule-optimization
## install required packages:
``` bash
    pip install -r requirements.txt
```
## to run the code required:
``` bash
    streamlit run app.py
```
##Usage
1.Upload a dataset in CSV format using the "Upload your CSV file" widget.
2.View the model training results, including coefficients and mean squared error.
3.Input values for the number of bus terminals, stands, and stops to make predictions.
Example Dataset
Here’s a sample of the expected dataset structure:

No. of buses of that type	No. of bus terminals	No. of bus stands	No. of bus stops	Type Of Bus (Ac / Non Ac)
50	10	25	100	AC
40	8	20	80	Non AC
##Technologies Used

-Python
-Streamlit
-NumPy
-Pandas

##Contributing
  Contributions are welcome! Please open an issue or submit a pull request for any improvements or feature requests.

##License
This project is licensed under the MIT License. See the LICENSE file for details.

##Acknowledgments
Dataset source: https://data.opencity.in/dataset/public-transport-data/resource/public-transport-accessibility-).



