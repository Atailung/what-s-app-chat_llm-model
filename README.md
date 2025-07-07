

A Python-based tool to analyze and visualize WhatsApp group or personal chat exports. Extract insights like top senders, active times, message frequency, and conversational patterns — all from your chat data.

---

## 🚀 Features

- ✅ Clean and filter raw WhatsApp exports
- ✅ Extract sender names, timestamps, and message content
- ✅ Analyze total messages, active hours, word counts, and more
- ✅ Export results to structured formats (CSV, JSON, Pandas DataFrame)
- ✅ Visualize chat behavior over time (optionally extendable with Matplotlib/Seaborn)
- ✅ Built-in support for both `AM/PM` and `24-hour` timestamp formats

---

## 🛠️ Tech Stack

- **Python 3.x**
- **Pandas**
- **Regular Expressions (Regex)**
- **Matplotlib / Seaborn** *(optional visualization support)*

---

## 📂 File Structure

```

whatsapp-chat-analyzer/
├── analyzer.py
├── utils/
│   └── parser.py
├── data/
│   └── chat.txt
├── output/
│   └── analysis.csv
└── README.md

````

---

## 📥 How to Use

1. **Export your WhatsApp chat**
   - Open the chat in WhatsApp
   - Click on `More` → `Export Chat` → **Without Media**
   - Save it as a `.txt` file and place it in the `data/` folder

2. **Run the analyzer**

```bash
python analyzer.py --input data/chat.txt --output output/analysis.csv
````

3. **(Optional)** Visualize patterns using the plotting module (coming soon!)

---

## 🔍 Sample Analysis

* Total Messages Sent
* Most Active Participants
* Top Words & Emojis
* Daily/Hourly Activity Heatmap
* Sentiment Distribution *(NLP extension)*

---

## ✨ Future Enhancements

* Dashboard UI using Streamlit or Flask
* NLP-based sentiment tagging
* Chat word cloud
* Export to Excel/PDF reports
* Telegram/Signal support

---

## 👨‍💻 Author

**Arun Joshi**
📍 Kathmandu, Nepal
📧 [tai.lung2062@gmail.com](mailto:tai.lung2062@gmail.com)
🔗 [LinkedIn](https://www.linkedin.com/in/arun-joshi-45b36a293)

---

## 🪪 License

This project is open-source under the [MIT License](LICENSE).

