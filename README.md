# SCT_ML_1
![House Price Prediction](https://github.com/BottomsNode/SCT_ML_1/blob/main/Task%201%20%20ML.png)

# House Price Prediction with Linear Regression

This project implements a linear regression model to predict house prices based on square footage, number of bedrooms, and number of bathrooms.

## Dataset

The dataset used for this project contains information about various features of houses and their corresponding sale prices. It includes features like:
- GrLivArea: Above grade (ground) living area square feet
- BedroomAbvGr: Number of bedrooms above grade (does NOT include basement bedrooms)
- FullBath: Number of full bathrooms above grade
- SalePrice: Sale price of the house in dollars

## Files

- `train.csv`: Training dataset containing features and target variables.
- `test.csv`: Testing dataset used for making predictions.
- `sample_submission.csv`: Sample submission file with the format required for submission.

## Dependencies

- Python 3.x
- Libraries: pandas, numpy, scikit-learn, matplotlib, seaborn

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/your/repository.git
   cd repository
   
2. Install dependencies:
   pip install -r requirements.txt

3. Run the script:
   python house_price_prediction.py

4. The script will train the linear regression model, make predictions on the test set, and display various visualizations to evaluate the model's performance.
