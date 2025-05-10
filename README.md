# 🏠 House Price Info Scraping

This project is a web scraper built in Python that collects property listings data from a website, focusing on **house prices**, **locations**, and **property features** like bedrooms, bathrooms, and size in square meters.

## 📌 Features

- Scrapes listings between specified pages
- Extracts:
  - Property title
  - Price
  - Location
  - Number of bedrooms and bathrooms
  - Size (in square meters)
- Saves the scraped data in a structured **Pandas DataFrame**

## 🔧 Technologies Used

- `Python 3`
- `requests`
- `BeautifulSoup`
- `pandas`

## 📂 Project Structure
ETLS/
├── main.py # Main script for scraping
├── requirements.txt # Python dependencies
└── README.md # Project documentation


## 🚀 How to Run

**Clone the Repository**

```bash
git clone https://github.com/noahchirchir/House_Price_Info_Scrapping.git
cd House_Price_Info_Scrapping

pip install -r requirements.txt

scrap_pages(start_page=1, end_page=5)

python main.py





