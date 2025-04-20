# 🛍️ Myntra Product Review Scraper

This is a Streamlit web application that allows users to scrape product reviews from Myntra and store them in a MongoDB Atlas database. The app fetches reviews using a scraping pipeline and provides an intuitive UI for input and display.

---

## 📌 Features

- 🔍 Search and input product names
- 🕷️ Scrape reviews from Myntra
- 💾 Store data in MongoDB Atlas
- 📊 View and analyze review data

---

## 🚀 Installation
### 1. Clone the repository

git clone https://github.com/your-username/myntra-review-scraper.git
cd myntra-review-scraper

### 2. Create a Virtual Environment

conda create -n myntra_scrapper python=3.10
conda activate myntra_scrapper

### 3. Install dependencies

pip install -r requirements.txt

## ⚙️ Configuration
###🔐 MongoDB Atlas Setup
Update the connection string in mongo_operation.py: 
from pymongo import MongoClient
import certifi

self.client = MongoClient(
    "your-mongodb+srv-url",
    tlsCAFile=certifi.where()
)

Or load the MongoDB URL from .env using python-dotenv.

##▶️ Running the App
streamlit run app.py
(in terminal)

This will launch the web app in your browser.




```bash




