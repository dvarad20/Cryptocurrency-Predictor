**Cryptocurrency Price Predictor**
This project is a cryptocurrency price predictor dashboard built using Python, Streamlit, and various data analysis libraries. It gathers historical cryptocurrency data using yfinance and makes future predictions using the ARIMA model. The dashboard is interactive and provides visual insights into past and predicted price movements.

Features
Data Collection: Uses yfinance to collect historical cryptocurrency data.
Data Visualization: Provides interactive visualizations using Matplotlib and Seaborn.
Prediction Model: Uses the ARIMA model to predict future prices.
Web Dashboard: Built using Streamlit for interactive user experience.
Web Scraping: Fetches additional data using BeautifulSoup and requests.
Prerequisites
Make sure you have Python installed (preferably version 3.7 or above).

Required Libraries:
You can install the required libraries by running the following command:


File Structure
```
├── DSBDA.py               # Main Python script
├── README.md              # This README file
└── assets/                # (Optional) Images, logos, or additional assets for the dashboard
```
How to Run the Project
Clone the repository or download the project files.

```bash
git clone https://github.com/dvarad20/Cryptocurrency-Predictor.git
```

Navigate to the project directory.
```bash
cd Cryptocurrency Predictor\DSBDA
```

Install the required dependencies.
```bash
pip install yfinance matplotlib pandas seaborn pillow statsmodels streamlit requests beautifulsoup4
```

Run the Streamlit app.
```bash
streamlit run DSBDA.py
```
Streamlit will launch a local web server. Open your browser and go to the provided URL, typically http://localhost:8501.

Main Libraries Used
Streamlit: For building the interactive dashboard.
YFinance: To collect historical cryptocurrency data.
Matplotlib & Seaborn: For data visualization.
Pandas: For data restructuring and manipulation.
Statsmodels: For building the ARIMA model.
Requests & BeautifulSoup: For web scraping additional data.
Pillow: To handle and display images.

Screenshots

![image](https://github.com/user-attachments/assets/0fa089b0-05e1-40df-a8b1-c6a456046252)

![image](https://github.com/user-attachments/assets/0c5eb931-d7c9-4733-9d2c-bade8c13b866)

![image](https://github.com/user-attachments/assets/dbbce0e4-6d1a-42fd-9095-1e5468ba86f1)


Future Improvements
Add more sophisticated machine learning models.
Enable real-time cryptocurrency tracking.
Implement more robust error handling.
