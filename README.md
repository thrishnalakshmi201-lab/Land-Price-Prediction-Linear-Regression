# Land Price Prediction using Linear Regression

## 📌 Project Overview

This project demonstrates land price prediction using Machine Learning. A Linear Regression model is trained to predict the price of a plot of land based on its size in square feet.

## 🎯 Project Objectives

- Understand the difference between regression and classification.
- Explore the relationship between land size and price.
- Visualize data using Matplotlib.
- Train a Linear Regression model.
- Understand the equation of a straight line: y = mx + b.
- Predict land prices for new land sizes.

## 📊 Dataset Information

The project uses a dataset containing 10 land records.

**Dataset file:** `data/landpriceprediction.csv`

**Features:**
- Land: Land size in square feet.
- Price: Price of the land.

**Input Variable:** Land size

**Target Variable:** Land price

**Note:** The original dataset file is required to run the notebook and is not included in this repository unless separately uploaded.

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

## 🤖 Machine Learning Algorithm

**Linear Regression**

Linear Regression is a supervised Machine Learning algorithm used to predict continuous numerical values. It finds the best-fitting straight line between the input and target variables.

The mathematical equation is:

**y = mx + b**

Where:
- y = Predicted price
- m = Slope
- x = Land size
- b = Intercept

## ⚙️ Project Workflow

1. Import the required Python libraries.
2. Load the land price dataset.
3. Explore the dataset using descriptive statistics.
4. Visualize the relationship between land size and price.
5. Select the input feature and target variable.
6. Train the Linear Regression model.
7. Predict the price for a land size of 1500 square feet.
8. Visualize the regression line.
9. Calculate the slope and intercept.
10. Verify the prediction using the equation y = mx + b.

## 📁 Project Structure

```text
Land-Price-Prediction-Linear-Regression/
│
├── data/
│   └── landpriceprediction.csv
│
├── 03_land_price_prediction.ipynb
│
├── README.md
│
└── requirements.txt
```

## 🚀 How to Run the Project

**Step 1: Clone the repository**

```bash
git clone https://github.com/thrishnalakshmi201-lab/Land-Price-Prediction-Linear-Regression.git
```

**Step 2: Navigate to the project folder**

```bash
cd Land-Price-Prediction-Linear-Regression
```

**Step 3: Install the required libraries**

```bash
pip install -r requirements.txt
```

**Step 4: Add the dataset**

Place the original `landpriceprediction.csv` file inside the `data` folder.

**Step 5: Run the Jupyter Notebook**

```bash
jupyter notebook
```

Open `03_land_price_prediction.ipynb` and run the cells.

## 📈 Model Prediction

The notebook uses the trained Linear Regression model to predict the land price for a plot measuring 1500 square feet.

It also visualizes the actual data points and the fitted regression line.

## 📚 Learning Outcomes

- Understanding regression problems.
- Working with datasets using Pandas.
- Visualizing relationships between variables.
- Implementing Linear Regression.
- Understanding slope and intercept.
- Making numerical predictions using Machine Learning.

## 👩‍💻 Author

**Thrishnalakshmi MV**

Machine Learning Project | Python | Scikit-learn

---

⭐ If you find this project useful, feel free to star this repository!
