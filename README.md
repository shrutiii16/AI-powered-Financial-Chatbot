# AI-powered-Financial-Chatbot
An intelligent chatbot designed to answer financial queries by analyzing structured data. This project demonstrates how basic AI principles can be applied to financial datasets for quick, accurate, and interactive responses.

# Overview
This chatbot reads from a CSV file containing financial data and uses keyword-based logic to interpret user input. Based on the question, it extracts relevant insights such as stock prices, company revenue, sector performance, and more.

# Features
Reads and processes CSV-based financial data
Responds to user questions based on keywords and filters
Displays financial details for companies, years, sectors, etc.
Easy to extend with more complex AI or NLP logic

# Technology Used
Python 🐍
Pandas 📊
Jupyter Notebook 📓

# Project Structure
AI-Financial-Chatbot/
├── bcg_internship (1).ipynb    # Main chatbot logic
└── financial_data.csv          # Source financial dataset

# How to run
1.Clone this repository:
git clone https://github.com/your-username/AI-Financial-Chatbot.git
cd AI-Financial-Chatbot
2.Open the Jupyter Notebook:
jupyter notebook
3.Run bcg_internship (1).ipynb cell by cell.
4.Enter your financial query in the input cell to receive chatbot responses.

# Sample Queries
What is the revenue of Infosys in 2022?
Tell me the net profit of TCS.
Which sector has the highest market cap?
Show me data for 2023.

# Sample Output
The chatbot will respond with filtered rows or summarized insights from the financial data like this:
Company: Infosys
Year: 2022
Revenue: ₹1,23,000 Cr
Net Profit: ₹24,500 Cr

# Limitations
The logic is based on string matching, not deep NLP or ML (can be added later).
Responses are based only on the structure and quality of the dataset provided.
