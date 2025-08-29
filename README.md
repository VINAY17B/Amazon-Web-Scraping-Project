# 🛒 Amazon Laptop Data Web Scraping (Python + Power BI)

## 📖 Project Overview
This project scrapes laptop product details from **Amazon India** using Python (Requests + BeautifulSoup).  
The collected data is cleaned using **Pandas** and then visualized in **Power BI** to analyze laptop prices, ratings, and product trends.

## 📂 Dataset
- **Source:** Amazon India (live scraping)
- **Data Collected:**  
  - Laptop Title  
  - Price  
  - Ratings  

## 🛠 Tools & Skills
- **Python Libraries**: `requests`, `BeautifulSoup`, `pandas`  
- **Power BI** for dashboard visualization  
- **Data Cleaning**: handling missing values, converting text to numeric formats  

## 🔑 Steps Performed
1. **Web Scraping**  
   - Sent HTTP requests with custom headers to mimic a real browser.  
   - Parsed HTML content using **BeautifulSoup**.  
   - Extracted product title, price, and rating.  

2. **Data Cleaning (Python + Pandas)**  
   - Removed missing or invalid entries.  
   - Converted prices and ratings into numerical format for analysis.  

3. **Data Export & Visualization**  
   - Exported cleaned dataset into **Excel**.  
   - Imported into **Power BI** for visualization.  

## 📊 Key Insights
- Pricing of laptops varies widely across brands.  
- Average customer ratings remain around **4.0** regardless of price point.  
- Higher-rated laptops do not always correspond to higher prices.  

## 🖼️ Results
Here’s a snapshot of the Power BI dashboard:  

<img width="1226" height="703" alt="Screenshot 2025-08-29 180122" src="https://github.com/user-attachments/assets/2c86da97-1573-4c68-8b1c-edb06c65d89b" />



   ```bash
   pip install requests beautifulsoup4 pandas
