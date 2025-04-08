# 🛍️ Amazon Scraper Analyzer

A Flask + Tailwind-powered web app to scrape Amazon products, track prices (including discounts), and analyze competitor offerings.

---

## 🚀 Features

- 🔍 Search for any Amazon product using a keyword
- 📊 Analyze average prices, product count, and top discounted products
- 🧠 Competitor pricing analysis with data-driven insights
- 🌐 Responsive UI using Tailwind CSS
- 🧼 Clean, modular Python codebase with scraping + analysis separated

---

## 📷 Demo

> Add screenshots or a Loom video/GIF of the UI here once deployed

---

## 🧰 Tech Stack

- **Backend**: Flask, Python
- **Frontend**: Jinja2 Templates, Tailwind CSS
- **Scraping**: BeautifulSoup, Requests, Fake UserAgent
- **Analysis**: Pandas
- **Optional DB**: SQLite or MongoDB for persistence (coming soon)

---

## 📦 Project Structure

```
amazon-scraper-analyzer/
│
├── app/
│   ├── __init__.py
│   ├── routes.py
│   ├── scraper/
│   ├── analyzer/
│   ├── templates/
│   └── static/
│
├── instance/
├── .env
├── config.py
├── tailwind.config.js
├── postcss.config.js
├── run.py
└── requirements.txt
```

---

## 🛠️ Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/amazon-scraper-analyzer.git
   cd amazon-scraper-analyzer
   ```

2. **Create a virtual environment**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run Tailwind (optional frontend changes)**
   ```bash
   npm install
   npx tailwindcss -i ./app/static/css/tailwind.css -o ./app/static/css/output.css --watch
   ```

5. **Set environment variables**
   ```bash
   cp .env.example .env
   ```

6. **Run the app**
   ```bash
   python run.py
   ```

---

## 🔒 Environment Variables

Create a `.env` file like this:

```
FLASK_ENV=development
SECRET_KEY=your_secret_key_here
```

---

## 📈 Example Use Case

1. Visit the homepage
2. Type "wireless mouse" or any product
3. View a visual breakdown of average prices and best discounts

---

## 📌 Future Plans

- 🗂️ Add MongoDB to save and compare past trends
- 🕵️ Background scraping with Celery
- 📱 Responsive mobile-first layout
- 🔐 User authentication for saved searches

---

## 📄 License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for more details.

---

## 🤝 Contributing

Feel free to fork this repo, make changes, and open a PR. Contributions are welcome!

---

## 🌐 Author

Built by [@epythonlab](https://github.com/epythonlab2)
