# 📸 Instagram Post Downloader using Web Scraping (BeautifulSoup)

This Python project allows you to download images from **public Instagram posts** by scraping HTML data using **BeautifulSoup**. It's a simple CLI-based tool for educational purposes that demonstrates how metadata can be extracted from a webpage.

> ⚠️ **Disclaimer:** Instagram's content is protected by copyright and governed by its terms of service. This project is for **educational use only** and works only for **public** posts.

---

## 📌 Features

- ✅ Download image from **any public Instagram post**
- 🔍 Extract image URL using BeautifulSoup
- 💾 Save image to your local system
- 📂 Simple CLI-based interaction

---

## 🧰 Tech Stack

- Python 3.x
- [BeautifulSoup4](https://pypi.org/project/beautifulsoup4/)
- [Requests](https://pypi.org/project/requests/)

---

## 🚀 How it Works

1. You input the **public Instagram post URL**.
2. The script fetches and parses the page HTML using `requests` and `BeautifulSoup`.
3. It extracts the image URL from the `<meta property="og:image">` tag.
4. The image is downloaded and saved locally.

---

## 🧑‍💻 Installation & Setup
pip install -r requirements.txt
python instagram_downloader.py


## 📞 Contact

For any queries or suggestions, feel free to reach out:

- 📧 **Email**: talkwithharpreet@gmail.com
- 📱 **Phone**: +91-7048691931

