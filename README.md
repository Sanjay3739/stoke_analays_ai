# stoke_analays_ai

This project is a web application that allows users to input a stock ticker symbol, select various stock indicators, and receive a visual representation of the stock's performance over time. The application leverages OpenAI's GPT-4o to provide detailed financial analysis based on the stock chart and additional financial metrics.

## Features

- Input a stock ticker symbol to retrieve historical data.
- Select stock indicators such as Close Price, Open Price, High Price, Low Price, and Volume.
- Generate a stock trend chart.
- Utilize GPT-4o for in-depth financial analysis of the stock and company.
- Display the analysis in a user-friendly format.

## Technologies Used

- **Flask:** A lightweight WSGI web application framework in Python.
- **yfinance:** A Python library to fetch financial data.
- **Matplotlib:** A plotting library to create stock charts.
- **OpenAI's GPT-4o:** An advanced AI model for generating financial analysis.
- **HTML/CSS:** For structuring and styling the web application.

## Project Structure

- `app.py`: The main Flask application file that handles routing, data fetching, chart generation, and financial analysis.
- `templates/index.html`: The HTML template for the web application's user interface.
- `static/style.css`: The CSS file for styling the web application.

## Setup and Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Sanjay3739/stoke_analays_ai.git
   cd stoke_analays_ai
   ```

2. **Create and activate a virtual environment:**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scriptsctivate`
   ```

3. **Install the required dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Set up OpenAI API key:**
   Create a `.env` file and have it look like the following:
   ```
   OPENAI_API_KEY='KEY_HERE'
   ```

6. **Run the Flask application:**
   ```bash
   flask run
   ```

7. **Open the application in your web browser:**
   Navigate to `http://127.0.0.1:5000` to access the web application.
