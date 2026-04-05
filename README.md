# 🚀 Domain-Restricted Q&A Assistant

A Streamlit-based AI assistant that answers user questions strictly within a selected domain using a custom knowledge base.

---

## 📌 Project Overview

This application allows users to:

- Select a **specific domain** (e.g., Fitness, Travel, Biology, Personal Finance)
- Upload a **custom knowledge base (CSV file)**
- Ask questions related to that domain
- Get AI-generated responses **strictly limited to the provided knowledge**

---

## 🧠 Key Features

✅ Domain-specific AI responses  
✅ Custom knowledge base via CSV upload  
✅ Controlled prompt engineering  
✅ Adjustable response style:
- Tone (Friendly, Professional, Casual)
- Length (Brief, Moderate, Detailed)
- Audience (Beginner, Intermediate, Advanced)

✅ Prebuilt quick questions for each domain  
✅ Simple and interactive UI using Streamlit  

---

## 🛠️ Tech Stack

- **Frontend/UI:** Streamlit  
- **Backend Logic:** Python  
- **Data Handling:** Pandas  
- **AI Integration:** OpenAI API (`gpt-4o-mini`)  

---

## 📂 Project Structure

project/
│── app.py
│── README.md
│── requirements.txt

---

## 📊 Knowledge Base Format (CSV)

Your uploaded CSV must contain:

| topic | information |

Example:

topic,information  
Protein,Protein helps in muscle repair and growth  

---

## ⚙️ Installation & Setup

1. Clone the repository  
git clone https://github.com/fasrinrahman/  

2. Install dependencies  
pip install -r requirements.txt  

3. Run the app  
streamlit run app.py  

---

## 🧩 How It Works

1. Setup Tab → Select domain + upload CSV  
2. Chat Tab → Ask questions  
3. Quick Questions Tab → Use templates  

---

## ⚠️ Constraints

- Answers only within selected domain  
- Uses only provided knowledge base  

---

## 🎯 Learning Outcomes

- Prompt engineering  
- Streamlit development  
- API integration  
- File handling  

---

## 👨‍💻 Author

Mohamed Fasrin Rahman  
GitHub: https://github.com/fasrinrahman  
