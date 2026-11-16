AI Business Insight Generator 🚀

Project Overview

AI Business Insight Generator is an AI-powered Streamlit application that analyzes business datasets and generates meaningful business insights using Google Gemini AI.

Users can upload CSV files, explore business performance through interactive dashboards, and ask questions about their business data.

Features

CSV Upload: Upload business datasets.

Dataset Preview: View uploaded data.

KPI Dashboard: Track Sales, Profit, Orders, Customers, and Average Discount.

Business Analysis: Analyze category, region, and customer segment performance.

Interactive Charts: Visualize business performance.

AI Business Insights: Generate insights using Google Gemini API.

Business Health Score: Evaluate overall business performance.

Download Report: Download AI-generated business reports.

Technologies Used

Python

Streamlit

Pandas

Plotly

Google Gemini API

Python-dotenv

Project Structure

app.py – Main Streamlit application

requirements.txt – Project dependencies

.gitignore – Files excluded from GitHub

Dataset Requirements

The uploaded CSV dataset should contain these columns:

Sales

Profit

Order ID

Customer ID

Discount

Category

Region

Segment

Installation and Setup

Clone the repository:

git clone https://github.com/mohit590027-cpu/AI-Business-Insight-Generator.git

Open the project folder:

cd AI-Business-Insight-Generator

Create a virtual environment:

py -m venv .venv

Activate the environment:

.venv\Scripts\activate

Install dependencies:

pip install -r requirements.txt

Create a .env file and add your Gemini API key:

GEMINI_API_KEY=your_api_key

Run the application:

streamlit run app.py

GitHub Repository

AI Business Insight Generator

Author

Mohit Sharma

Aspiring Data Analyst | Python | SQL | Excel | Power BI
