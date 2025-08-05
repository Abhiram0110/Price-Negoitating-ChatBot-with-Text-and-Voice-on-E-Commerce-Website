# Price-Negoitating-ChatBot-with-Text-and-Voice-on-E-Commerce-Website


This project is an interactive **chatbot-enabled e-commerce platform** where users can negotiate product prices using **text and voice commands**. The chatbot offers dynamic pricing through specific keywords and performs **sentiment analysis** on user reviews after purchase.

---

## 🛍️ Key Features

- User registration and login
- Product browsing with actual and negotiable prices
- Chatbot-based price negotiation via:
  - 💬 Text input
  - 🎤 Voice commands
- Real-time discount logic:
  - `"first price"` → 10% off
  - `"final price"` → Extra 10% off
- Purchase system with order tracking
- Post-purchase review submission
- Sentiment analysis on reviews (Positive / Negative)
- Admin can view user reviews and sentiments

---

## ⚙️ Technologies Used

- **Python 3.7+**
- **Flask** (Backend web framework)
- **MySQL** with PyMySQL
- **SpeechRecognition** (Voice input)
- **VADER Sentiment Analysis** (NLP)
- **HTML / CSS / JavaScript** (Frontend)

---

## 🗃️ Project Structure

```

project/
├── templates/
│   ├── index.html
│   ├── Signup.html
│   ├── Login.html
│   ├── UserScreen.html
│   ├── BrowseProducts.html
│   ├── Chatbot.html
│   ├── VoiceBot.html
│   ├── PostReview\.html
│   ├── ViewOrders.html
│   └── ViewReview\.html
├── static/
│   └── default.css
├── Main.py
├── DB.txt
├── run.bat
├── requirements.txt
├── SCREENS.docx
├── admin.py
├── models.py
├── views.py
├── urls.py
├── apps.py
└── test.py

````

---

## 📦 Installation

1. **Clone the Repository**
```bash
git clone https://github.com/your-username/your-repo.git
cd your-repo
````

2. **Install Python Dependencies**

```bash
pip install -r requirements.txt
```

3. **Set Up MySQL Database**

* Open MySQL and run the commands from `DB.txt` to create required tables.

4. **Run the App**

```bash
python Main.py
```

Then open: `http://127.0.0.1:5000/index` in your browser.

Or double-click `run.bat` (Windows only).

---

## 💬 Chatbot Commands

| Command       | Description                     |
| ------------- | ------------------------------- |
| `first price` | Applies 10% discount            |
| `final price` | Applies additional 10% discount |
| Other inputs  | Invalid or unrecognized command |

---

## 🧠 Sentiment Analysis

* Users can submit reviews after purchase.
* The system uses **VADER Sentiment Analyzer** to classify each review as:

  * ✅ Positive
  * ❌ Negative

---

## ✅ Requirements

```
pandas==0.25.3
numpy==1.19.2
vaderSentiment==3.3.1
scikit-learn==0.22.2.post1
SpeechRecognition==3.8.1
PyMySQL==0.9.3
Flask==1.1.2
Flask-Cors==3.0.10
```

Install via:

```bash
pip install -r requirements.txt
```


## 👨‍💻 Author

**Abhiram0110**
GitHub: [https://github.com/Abhiram0110](https://github.com/Abhiram0110)

---

## 📌 Disclaimer

This project is for academic and demonstration purposes only. It does not process real payments and is not connected to a live e-commerce backend.

