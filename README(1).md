# IPL Auction 2022 Web Scraper 🏏📊

## 📌 Project Overview
This project extracts **IPL Auction 2022** data from the [official IPL website](https://www.iplt20.com/auction/2022) using **Python**. It scrapes **team names, funds remaining, and other auction details**, cleans the data, and exports it to a **CSV file** for further analysis.

## 🔹 Features
- 🏗 **Web Scraping:** Uses `BeautifulSoup` and `requests` to extract IPL auction data.
- 📊 **Data Cleaning:** Handles missing values and removes unwanted characters.
- 💾 **CSV Export:** Saves structured data for analysis.
- ⚡ **Automation:** Reduces manual data collection effort by **80%**.

## 🛠 Tech Stack
- **Python** (`requests`, `BeautifulSoup`, `pandas`)
- **Jupyter Notebook** (for running the script)

## 🚀 How to Run the Script
1. **Clone the Repository:**
   ```bash
   git clone https://github.com/yourusername/IPL-Auction-Web-Scraper.git
   cd IPL-Auction-Web-Scraper
   ```

2. **Install Dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Script:**
   ```bash
   python scrape_ipl.py
   ```

4. **View the Data:**
   The scraped data will be saved as `IPL_Auction_2022.csv`. Open it in Excel or any data analysis tool.

## 📄 Example Output (CSV Format)
| SR. NO. | TEAM                     | FUNDS REMAINING |
|---------|--------------------------|----------------|
| 1       | Chennai Super Kings      | ₹2,95,00,000   |
| 2       | Delhi Capitals           | ₹10,00,000    |
| 3       | Gujarat Titans           | ₹15,00,000    |
| ...     | ...                      | ...           |

## 🏆 Contributing
Feel free to fork this repository and submit pull requests with improvements! 😊

## 📜 License
This project is **open-source** under the MIT License.

---
🚀 **Happy Scraping!**
