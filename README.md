# 🏁 RunSignUp Race Scraper

This project uses Selenium to scrape triathlon, duathlon, and related endurance race events from [RunSignUp](https://runsignup.com), collecting structured information including event title, location, date, and links.

## 📌 Purpose
The scraper was built to streamline the process of gathering race director contacts and event details for outreach and partnership initiatives.

## ⚙️ Features
- Pulls data for 6 race types (triathlon, duathlon, bike race, etc.)
- Iterates over multiple pages of results
- Extracts event title, date, location (city, state, country), and race link
- Outputs data to CSV

## 🧰 Tech Stack
- Python
- Selenium
- pandas
- webdriver-manager

## 📁 Project Structure
race_scraper/
├── race_scraper_runsignup.ipynb
├── requirements.txt
├── data/
│ └── race_listings_RunSignUp.csv
└── README.md


## 🚀 How to Run
1. Clone the repo
2. Install dependencies:  
   `pip install -r requirements.txt`
3. Run the notebook:  
   `jupyter notebook race_scraper_runsignup.ipynb`

## ✅ Sample Output
A sample of the resulting data is included in `/data/race_listings_RunSignUp.csv`.

## 🧠 Future Improvements
- Add email/contact scraping
- De-duplicate overlapping listings
- Schedule recurring scraping runs

## 📬 Contact
Created by [Your Name]. Feel free to reach out on [LinkedIn](https://linkedin.com/in/your-link) or by email.

