
# 🛒 Amazon Web Scraper

A simple Python-based Amazon product scraper that extracts the product title and price from any Amazon India product URL.

> ⚠️ **Disclaimer:** This project is for educational purposes only. Web scraping may violate Amazon’s Terms of Service. Use responsibly and avoid overloading their servers.

---

## 📸 Example Output

Product: iQOO Neo 10 (Titanium Chrome, 8GB RAM, 256GB Storage) | Snapdragon 8s Gen 4 Processor & SuperComputing Chip Q1 | 7000 mAh Battery 
Price: ₹ 33,999

---

## 🚀 Features

- Extract product title and price from Amazon product page
- Uses `requests` and `BeautifulSoup`
- Easy to run and modify
- Can be extended to send email alerts or run on a schedule

---

## 🛠️ Installation

1. **Clone this repository**
   ```bash
   git clone https://github.com/YOUR_USERNAME/amazon-web-scraper.git
   cd amazon-web-scraper

2.	Install dependencies

	pip install -r requirements.txt



⸻

🧪 Usage
	1.	Open scraper.py
	2.	Replace the sample URL with your desired Amazon product URL
	3.	Run the script:

python scraper.py



⸻

🧾 Requirements
	•	Python 3.6+
	•	requests
	•	beautifulsoup4

You can install them with:

pip install -r requirements.txt


⸻

🧠 How It Works

The script sends an HTTP GET request to the Amazon product page with a browser-like User-Agent to avoid being blocked. It then parses the HTML and extracts:
	•	Title using the productTitle ID
	•	Price using the a-price-whole class

⸻

📌 Note
	•	Amazon uses dynamic content and anti-scraping measures. If the script stops working, try changing headers, adding delays, or using tools like Selenium or ScraperAPI.
	•	Avoid frequent requests to prevent being IP banned.

⸻

🤝 Contributing

Pull requests are welcome! If you find bugs or want to add features, feel free to open an issue or PR.

⸻

📄 License

This project is open source and available under the MIT License.

