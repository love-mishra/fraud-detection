# Fraud Detection Project

## Overview
This project aims to detect fraudulent credit card transactions using machine learning techniques. The dataset contains transaction details along with a binary variable indicating whether each transaction is fraudulent or not.

## Features
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Mutual Information and Correlation Analysis
- Model Training and Evaluation using XGBoost
- Hyperparameter Tuning
- Predictions on the Test Dataset

## Technologies Used
- **Programming Languages**: Python
- **Libraries**:
  - Data Manipulation and Analysis: Pandas, NumPy
  - Data Visualization: Matplotlib, Seaborn
  - Machine Learning: Scikit-learn, XGBoost
- **Tools**:
  - Jupyter Notebook

## Platform Used
- **Local Environment**: macOS (or your specific OS if different)
- **Data Storage and Access**: Local File System

## Installation

1. **Clone the repository:**
   ```sh
   git clone https://github.com/love-mishra/fraud-detection.git
   cd fraud-detection
   ```

2. **Create and activate a virtual environment:**
   ```sh
   python3 -m venv venv
   source venv/bin/activate   # On Windows, use `venv\Scripts\activate`
   ```

3. **Install the required dependencies:**
   ```sh
   pip install -r requirements.txt
   ```

## Directory Structure

```plaintext
fraud-detection/
├── data/
│   ├── train.csv               # Training dataset
│   ├── test.csv                # Testing dataset
├── notebooks/
│   ├── fraud-detection.ipynb                  # Utility functions
├── requirements.txt            # Required Python packages
├── README.md                   # Project documentation
└── predictions.csv             # Output predictions
```

## Usage

1. **Run Jupyter Notebooks:**
   Launch Jupyter Notebook and open the notebooks in the `notebooks` directory to explore data, perform feature engineering, train models, and make predictions.

2. **Execute Python Scripts:**
   Alternatively, you can run the Python scripts in the `src` directory for each step of the project.

## Contributing
Contributions are welcome! Please feel free to submit a pull request or open an issue to discuss improvements, features, or bugs.

## License
This project is licensed under the MIT License.

## Contact
For any questions or inquiries, please contact [love-mishra](https://github.com/love-mishra).

 