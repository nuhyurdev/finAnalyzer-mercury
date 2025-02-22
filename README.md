# FinAnalyzer

![GitHub License](https://img.shields.io/github/license/nuhyurdev/finAnalyzer-mercury?style=flat-square)
![Python Version](https://img.shields.io/badge/python-3.7%20%7C%203.8%20%7C%203.9%20%7C%203.10-blue?style=flat-square)
![Framework](https://img.shields.io/badge/framework-MLJAR--Mercury-orange?style=flat-square)
![Contributions Welcome](https://img.shields.io/badge/contributions-welcome-brightgreen?style=flat-square)

FinAnalyzer is a powerful web application built using the [MLJAR-Mercury](https://github.com/mljar/mercury) framework. It leverages financial data from Yahoo Finance to display key technical indicators such as Moving Averages (MAs), Moving Average Convergence Divergence (MACD), and Relative Strength Index (RSI) on interactive and dynamic charts. Whether you're a financial analyst, trader, or enthusiast, FinAnalyzer provides the tools to make data-driven decisions.

---

## ✨ Features

- **Financial Data Integration**: Seamlessly fetches real-time financial data from Yahoo Finance.
- **Technical Indicators**: Calculates and visualizes essential indicators like MAs, MACD, and RSI for in-depth financial analysis.
- **Interactive Charts**: Presents data through intuitive and interactive visualizations powered by Plotly or similar libraries.
- **User-Friendly Interface**: Easy-to-use web interface for quick analysis and insights.
- **Customizable**: Modify and extend the application to suit your specific financial analysis needs.

---

## 🛠️ Installation

To set up FinAnalyzer locally, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/nuhyurdev/finAnalyzer-mercury.git
   cd finAnalyzer-mercury
   ```

2. **Install Dependencies**:
   Ensure you have Python 3.7 or higher installed. Install the required packages using:
   ```bash
   pip install -r requirements.txt
   ```

3. **Set Up Environment Variables**:
   Create a `.env` file in the project directory and add any necessary environment variables. You can then set these variables using:
   ```bash
   source setup.sh
   ```

4. **Run the Application**:
   Start the application with:
   ```bash
   mercury run finAnalyser.ipynb
   ```
   This will launch the web app, and you can access it via your web browser at the provided local address.

---

## 🚀 Usage

Once the application is running:

1. **Access the Web Interface**: Open your web browser and navigate to the local address provided in the terminal (e.g., `http://127.0.0.1:8000`).
2. **Input Ticker Symbol**: Enter the ticker symbol of the stock or financial instrument you wish to analyze (e.g., `AAPL` for Apple Inc.).
3. **View Charts**: The application will display interactive charts with the selected technical indicators, allowing you to explore trends and patterns.

---

## 🤝 Contributing

We welcome contributions from the community! To contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a Pull Request.

Please ensure your code follows the project's style guidelines and includes appropriate tests.

---

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## 🙏 Acknowledgements

- **[MLJAR-Mercury](https://github.com/mljar/mercury)**: The framework powering this application, enabling seamless deployment of Jupyter Notebooks as web apps.
- **[Yahoo Finance](https://finance.yahoo.com/)**: The source of financial data used in this project.
- **[Plotly](https://plotly.com/)**: For creating interactive and dynamic visualizations.

---

## 📊 Example Screenshot

![FinAnalyzer Screenshot](https://via.placeholder.com/800x400.png?text=FinAnalyzer+Interactive+Charts)  
*Example of interactive charts displaying technical indicators.*

---

## 📬 Contact

For questions, suggestions, or feedback, feel free to reach out:  
- **GitHub Issues**: [Open an Issue](https://github.com/nuhyurdev/finAnalyzer-mercury/issues)  
- **Email**: [Your Email Address]  

---

*Note: This project is actively maintained and open to contributions. Let's make financial analysis more accessible and insightful together!*
