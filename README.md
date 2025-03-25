# Audible Scraping & Analysis

## 📌 Overview  
This project scrapes audiobook data from the Audible website using Selenium and performs data analysis using Pandas, Matplotlib, and Seaborn.

## 🛠️ Technologies Used  
- **Selenium** (for web scraping)  
- **Pandas** (for data manipulation)  
- **Matplotlib & Seaborn** (for visualization)  

## 🚀 Features  
- Extracts book titles, authors, release dates, and lengths  
- Converts book length to minutes  
- Visualizes audiobook trends (release year, duration distribution, top authors)  

## 📂 Files  
- `scraping.ipynb` → Web scraping script  
- `analysis.ipynb` → Data analysis script  
- `audible_books.csv` → Raw scraped data  
- `cleaned_books.csv` → Cleaned dataset  

## 📜 How to Run  
1. Install dependencies:  
   ```bash
   pip install selenium pandas matplotlib seaborn webdriver-manager
