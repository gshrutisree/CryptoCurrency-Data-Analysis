**Crypto Historical Data Retrieval**

📖 **Description**

This project is designed to retrieve, store, and analyze historical cryptocurrency data using a free and reliable API. It supports the collection of daily price data for popular cryptocurrency pairs and includes analysis tools to identify trends. Additionally, the project utilizes machine learning for predictive analysis based on historical data.


🧰 **Technologies Used**
Programming Language: Python
Libraries:
Requests (For making API calls)
Pandas (For data manipulation and analysis)
Matplotlib & Seaborn (For data visualization)
Scikit-learn (For machine learning modeling)


📂 **Project Structure**

├── **data**/                             # Folder for storing historical data
│   ├── **cryptocurrency_data.xlsx**      # Excel file containing crypto data
│   └── **data.csv**                      # CSV file with processed crypto data
├── **notebooks/**                        # Jupyter notebooks for analysis and visualization
│   └── **data_analysis.ipynb****         # Notebook for exploring and visualizing data
├── **src/**                              # Source code for the project
│   ├── **crypto_info.py**                # Script for fetching historical crypto data
│   ├── **ml_model.py**                   # Script for machine learning analysis
│   └── **visualize_data.py**             # Script for visualizing the historical data
├── **README.md**                         # Project README file
└── **requirements.txt**                  # Required libraries for the project


📊 **Features**

- Fetch historical cryptocurrency data using a free API.
- Support for popular crypto pairs like BTC/USD, ETH/USD, etc.
- Save the data in JSON, CSV, and Excel formats for easy access.
- Data visualization to analyze trends over time.
- Machine learning analysis for predicting future trends.

🚀**Getting Started**

-- Prerequisites
    Ensure you have Python installed. You can install the required libraries using the command below:
    **pip install -r requirements.txt**
    
-- How to Run the Project

 ->  Clone the repository: git clone https://github.com/gshrutisree/CryptoCurrency-Data-Analysis.git
 -> Navigate to the project directory: cd CryptoCurrency-Data-Analysis
 -> Fetch Historical Data: python src/crypto_info.py
 -> Visualize Data: python src/visualize_data.py
 -> Run Machine Learning Model: python src/ml_model.py


📊**Data Visualization**

This project includes several visualizations for understanding cryptocurrency trends:

- Price Trends Over Time: Line plots to visualize daily price movements.
- Volume Analysis: Charts to see trading volume over the specified period.
- Correlation Analysis: Heatmaps to study the relationship between different crypto pairs.

🤖 **Machine Learning**

The ml_model.py script includes:
- Data Preprocessing: Preparing historical data for machine learning models.
- Model Training: Utilizing algorithms like linear regression or decision trees to predict future prices.
- Evaluation: Assessing the model's accuracy based on test data.

📦 **Dataset**

The dataset includes historical data for various cryptocurrency pairs, including:
- Date
- Opening Price
- Closing Price
- Highest Price
- Lowest Price
- Trading Volume

Data is fetched and saved in multiple formats:
- Excel File: data/cryptocurrency_data.xlsx
- CSV File: data/data1.csv


🌟 **Acknowledgments**

Thanks to the free API provider for providing access to historical crypto data.
Inspiration from various open-source projects focused on crypto trend analysis.




