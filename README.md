# 📊 AI Data Analyst Chatbot (RAG Powered)

An intelligent **AI-powered Data Analyst Chatbot** that performs **EDA, generates insights, builds visualizations, and provides business recommendations** using **Gemini API + RAG (Retrieval-Augmented Generation)**.

---

## 🚀 Features

* 📂 Upload CSV / Excel datasets
* 📊 Automatic Exploratory Data Analysis (EDA)
* 🧠 AI-generated dataset summary (200–250 words)
* 🤖 Ask questions about your data (Chat interface)
* 🔍 RAG-based smart data retrieval
* 📈 Custom chart builder (Line, Bar, Scatter, Histogram)
* 🎨 Multiple charts with color customization
* 💡 Generates **5 business recommendations**

---

## 🧠 Tech Stack

* **Frontend/UI**: Streamlit
* **Backend**: Python
* **AI Model**: Gemini (Google GenAI)
* **RAG Engine**: FAISS
* **Data Processing**: Pandas, NumPy
* **Visualization**: Matplotlib, Seaborn

---

## 📁 Project Structure

```
ai-data-analyst-chatbot/
│
├── mainDA.py
├── requirements.txt
├── .env
├── README.md
└── assets/ (optional screenshots)
```

---

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/BoffilJoshua/AI-Data-Analyst-Chatbot.git
cd AI-Data-Analyst-Chatbot
```

---

### 2. Create virtual environment

```bash
python -m venv .venv
.venv\Scripts\activate
```

---

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

---

### 4. Add API Key

Create a `.env` file:

```env
GEMINI_API_KEY=your_api_key_here
```

---

## ▶️ Run the App

```bash
streamlit run mainDA.py
```

---

## 🧪 How It Works

1. Upload dataset (CSV/Excel)
2. System performs EDA
3. RAG retrieves relevant data
4. Gemini generates:

   * Summary
   * Insights
   * Business recommendations
5. User can build custom charts

---

## 🎥 Demo

👉 Add your demo video link here
(e.g., Google Drive / YouTube)

---

## 💡 Future Improvements

* 🔥 Real embeddings (instead of mock embeddings)
* 💬 Chat memory (context-aware conversations)
* 📊 Auto chart generation using AI
* 🌐 Deployment (Streamlit Cloud / Render)

---

## 🤝 Contributing

Feel free to fork this repo and improve it!

---

## 📜 License

This project is open-source and available under the MIT License.

---

## 👨‍💻 Author

**Joshua**
Aspiring AI/ML Engineer | Data Analyst

---
