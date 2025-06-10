# 📰 Scraperly

A sleek, terminal-style Python news aggregator with GUI that scrapes headlines from major international news websites, groups them by importance, and lets you export the results to an Excel file.

## 🧠 Features

* 🔍 Scrapes latest headlines from:

  * Al Jazeera
  * BBC
  * CNN
  * Reuters
  * New York Times
  * The Guardian
  * Fox News

* ⚠️ Categorizes headlines into High, Medium, or Low importance

* 📄 Export news headlines into a styled Excel spreadsheet

* 🧭 GUI built using `tkinter` with importance-based grouping and direct news site access

* 🐍 Clean Python OOP architecture with BeautifulSoup, threading, and openpyxl support

## 💻 Demo UI Screenshot (Example Only)

```
+---------------------------------------------------------------+
| Scraperly News 🔥                                           |
| Grouped by Importance Level                                  |
+-----------------+---------------------------------------------+
| Source          | Headline                                    |
|-----------------+---------------------------------------------|
| BBC             | Breaking: New Political Crisis in Europe... |
+-----------------+---------------------------------------------+
|  [Scrape] [Export to Excel]                                   |
+---------------------------------------------------------------+
```

## 📦 Requirements

```bash
pip install requests beautifulsoup4 pandas openpyxl
```

## 🚀 How to Run

```bash
python scraperly_5.py
```

Make sure your environment supports `tkinter`.

## 📁 File Structure

```
.
├── scraperly_5.py            # Main Python application file
├── news_headlines_styled.xlsx  # Output Excel file (after export)
├── README.md
```

## 📌 To-Do

* [ ] Add support for more news sites
* [ ] Add dark mode toggle for GUI
* [ ] Deploy a web version

## 🐙 GitHub Setup

You can clone this repository and start using it:

```bash
git clone https://github.com/yourusername/earthquaker.git
cd earthquaker
python scraperly_5.py
```

## 📃 License

MIT License

---

**Made with Python + News + 🔥**

