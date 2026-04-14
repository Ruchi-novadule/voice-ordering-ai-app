# 🎤 AI Voice Ordering System for Restaurants

An intelligent voice-based food ordering system that allows users to place orders using natural language speech. The system converts speech to text in real-time, matches user intent with menu items using NLP techniques, and generates an order summary with pricing.

---

## 🚀 Features

- 🎤 Real-time Speech-to-Text (like Siri)
- 🧠 Smart Item Matching (NLP-based)
- 🔤 Typo Handling & Keyword Mapping
- 🔢 Quantity Detection (e.g., "two burgers")
- 🧾 Order Summary Generation
- 💰 Automatic Price Calculation
- ⚡ Fast Response using optimized logic
- 🌐 Simple Web Interface

---

## 🛠️ Tech Stack

- **Frontend:** HTML, JavaScript (Web Speech API)
- **Backend:** FastAPI (Python)
- **AI/NLP:** Rule-based + Regex + Matching Logic
- **Database:** JSON (Menu storage)
- **Server:** Uvicorn

---

## 📁 Project Structure


voice-ordering-app/
│
├── app/
│ ├── api/
│ │ └── routes.py
│ ├── services/
│ │ ├── matching_service.py
│ │ ├── order_service.py
│ │ └── embedding_service.py
│ └── main.py
│
├── data/
│ └── menu.json
│
├── frontend/
│ └── index.html
│
├── scripts/
│ └── build_index.py
│
├── requirements.txt
└── README.md


---

## ⚙️ Installation & Setup

### 1️⃣ Clone Repository

```bash
git clone https://github.com/Ruchi-novadule/voice-ordering-ai-app.git 
cd voice-ordering-ai-app
2️⃣ Install Dependencies
pip install -r requirements.txt
3️⃣ Run Backend Server
uvicorn app.main:app --reload
4️⃣ Run Frontend
Open frontend/index.html
OR use Live Server in VS Code
🎯 Usage
Click Start Speaking
Speak your order:

Example:

I want one burger and two coke
📊 Output Example
Matched Items:
Veggie Burger, Diet Coke

Order Summary:
Veggie Burger x1 = ₹100
Diet Coke x2 = ₹100

Total items: 3
Total price: ₹200
🧠 How It Works
🎤 Speech is captured using Web Speech API
📝 Converted to text in real-time
🔍 Text processed using NLP logic
🍔 Items matched from menu
🔢 Quantities extracted using regex
🧾 Order summary generated
💰 Total price calculated
🔥 Future Enhancements
🔊 Voice response (Text-to-Speech)
📱 Mobile responsive UI
🧠 ML-based recommendation system
💳 Payment integration
🛒 Cart management system
🌍 Multi-language support
📸 Screenshots

Add screenshots here (UI + Output)

![UI Screenshot](images/ui.png)
![Output Screenshot](images/output.png)
💼 Use Case

This project demonstrates real-world applications of:

AI in food ordering systems
Voice-based interfaces
NLP-based intent recognition
Automation in restaurants
👩‍💻 Author

Ruchi Tiwari

⭐ Show Your Support

If you like this project, please ⭐ the repository and share it!
