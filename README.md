# 🪙 CryptoApp – Django Web App for Cryptocurrency News & Blockchain Data

**CryptoApp** is a **Django-based web application** that aggregates the latest **cryptocurrency and blockchain data and news** from external sources.  
It uses the `requests` library to fetch live data and stores selected information in a **Django database** for easy management via the built-in admin panel.


---

## ✨ Features

- 🔗 Fetches and displays **live crypto & blockchain news and data**  
- 💾 Stores data in a **relational SQLite3 database**  
- 🧠 Built with **Django ORM** and clean, modular structure  
- 🧭 Includes **Django Admin panel** for data management  

---

## 🧩 Tech Stack

| Layer | Technology |
|-------|-------------|
| **Backend** | Python 3, Django |
| **Frontend** | HTML5, CSS3, Bootstrap |
| **Database** | SQLite3 |
| **API Calls** | Python `requests` |
| **Version Control** | Git + GitHub |

---

## 🛠️ Installation Guide

### 1️⃣ Clone the repository
```bash
git clone https://github.com/SPAL23IT/CryptoStarter-web-app-Python-Django-.git
cd CryptoStarter-web-app-Python-Django-

2️⃣ Create and activate a virtual environment

**Windows**

python -m venv venv
venv\Scripts\activate

**Mac / Linux**

python3 -m venv venv
source venv/bin/activate

3️⃣ Install dependencies

pip install django requests

4️⃣ Run migrations

python manage.py migrate

5️⃣ Start the server

python manage.py runserver

6️⃣ Open in browser

👉 http://127.0.0.1:8000/cryptoapp/

⚙️ Project Structure
CryptoApp/
├── cryptosite/              # Django project settings & URLs
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
├── cryptoapp/               # Main app (views, models, templates)
├── db.sqlite3               # Local database
├── manage.py                # Django management tool
├── requirements.txt          # Dependencies
├── .gitignore
└── README.md

🧑‍💻 Usage

Access Django Admin:
http://127.0.0.1:8000/admin/

Create a superuser:

python manage.py createsuperuser

Manage or view stored crypto-related news and data.

🚀 Future Plans

Add live crypto price charts (CoinGecko / Binance API)

Add user login / registration

Integrate search & filtering for news

Improve UI with Tailwind CSS or React frontend

👨‍💻 Author

SPAL23IT
💼 GitHub: @SPAL23IT

📧 Contact: spal2233@gmail.com

📜 License

This project is licensed under the MIT License.
Feel free to use, modify, and share it for educational or portfolio purposes.

⭐ If you find this project useful, please consider giving it a star on GitHub! ⭐
