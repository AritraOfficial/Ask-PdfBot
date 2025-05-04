# 📄 Chat with Multiple PDFs using LangChain & Google Gemini
<p align="center">
  <a href="https://chatwithmultiplepdfs-arimofficial.streamlit.app/" target="_blank">
    <img src="https://img.shields.io/badge/-🚀 Live%20Demo-000000?style=for-the-badge&logo=firefox&logoColor=white&labelColor=00C853&color=000000" alt="Live Demo">
  </a>
</p>
Build an AI-powered chatbot that can intelligently answer your questions from multiple PDF documents using Google Gemini, FAISS vector storage, and LangChain — all wrapped in a beautiful Streamlit interface.

---
![image](https://github.com/user-attachments/assets/ac9fb489-5a8e-4e75-bd03-8f9178c9d25b)

## 🚀 Features

* 🔍 **Multi-PDF Support** – Upload and query across multiple PDF documents
* 💡 **Google Gemini Integration** – Accurate, intelligent answers from a powerful LLM
* ⚡ **FAISS Vector Store** – Fast document similarity search
* 🧠 **LangChain QA Chain** – Efficient retrieval-augmented generation
* 🌐 **Streamlit Interface** – Simple, user-friendly front-end to interact with the chatbot

---

## 📋 Project Flow  
Below is the structured flow of the project:  
![diagram-export-04-05-2025-15_29_11](https://github.com/user-attachments/assets/8f087154-36db-42f5-83ea-918b005e3471)

## 📁 Project Structure

```
├── streamlit_app.py                     # Streamlit app entry point
├── requirements.txt           # Dependencies
├── .streamlit/config.toml     # Streamlit theme config (optional) (In your local drive)
├── faiss_index/               # Local vector index (In your local drive)
├── docenv/                    # Virtual Env (In your local drive)
├── .env                       # .env {For loading all keys and nessessary} (In your local drive)
└── README.md
```

---

## 🛠️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/AritraOfficial/Chat_With_Multiple_PDFs.git
cd Chat_With_Multiple_PDFs
```

### 2. Set Up Environment

Make sure you’re using **Python 3.9+**. {MAKE SURE THE PY Version I Used 3.13.1}

```bash
pip install -r requirements.txt
```

### 3. Configure API Key

Set your Google Gemini API key:

```bash
export GOOGLE_API_KEY="your_api_key_here"
```

Or create a `.env` file:

```env
GOOGLE_API_KEY=your_api_key_here
```

---

## ▶️ Run the App

```bash
streamlit run app.py
```

The app will open in your browser. Upload PDFs and ask questions!

---

## 📸 Screenshots

| Upload PDFs                       | Ask Questions                    | Get Answers                       |
| --------------------------------- | -------------------------------- | --------------------------------- |
| ![image](https://github.com/user-attachments/assets/d1bf2052-9c3a-4fef-8527-59ff7bd5ebd6) | ![ask](https://github.com/user-attachments/assets/bdda8359-2a1b-45ad-bb82-28fec0b785e0)| ![answer](https://github.com/user-attachments/assets/a2402ab5-aa77-41e0-b973-0e0597513b0b)|

---

## 🔧 Key Technologies

* **Google Generative AI** (Gemini Pro or Flash)
* **LangChain**
* **FAISS**
* **Streamlit**
* **Python**

---

## 🧠 Use Cases

* 📚 Academic research assistant
* 🏥 Clinical document analysis
* ⚖️ Legal contract understanding
* 📊 Business document summarization

---

## 💡 Future Improvements

* Chat history & memory (Already Have But not in this version)
* Support for other document types (Word, CSV, etc.)
* Upload via cloud storage

---

## 📜 License

This project is licensed under the MIT License.
Feel free to use, modify, and share.

---

## 🙌 Acknowledgments  
Special thanks to the creators of **Google**, **Streamlit**, and **Github** for the powerful tools that made this project possible.  

---

## 📧 Contact 
For queries or collaborations, feel free to connect:  
<p align="center">
  <a href="https://www.linkedin.com/in/aritramukherjeeofficial/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
  </a>
  <a href="https://x.com/AritraMofficial" target="_blank">
    <img src="https://img.shields.io/badge/Twitter-%231DA1F2.svg?style=for-the-badge&logo=twitter&logoColor=white" alt="Twitter">
  </a>
  <a href="https://www.instagram.com/aritramukherjee_official/?__pwa=1" target="_blank">
    <img src="https://img.shields.io/badge/Instagram-%23E4405F.svg?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram">
  </a>
  <a href="https://leetcode.com/u/aritram_official/" target="_blank">
    <img src="https://img.shields.io/badge/LeetCode-%23FFA116.svg?style=for-the-badge&logo=leetcode&logoColor=white" alt="LeetCode">
  </a>
  <a href="https://github.com/AritraOfficial" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-%23181717.svg?style=for-the-badge&logo=github&logoColor=white" alt="GitHub">
  </a>
  <a href="https://discord.com/channels/@me" target="_blank">
    <img src="https://img.shields.io/badge/Discord-%237289DA.svg?style=for-the-badge&logo=discord&logoColor=white" alt="Discord">
  </a>
  <a href="mailto:aritra.work.official@gmail.com" target="_blank">
    <img src="https://img.shields.io/badge/Email-%23D14836.svg?style=for-the-badge&logo=gmail&logoColor=white" alt="Email">
  </a>
</p>

---
---

Would you like me to include badges (e.g., stars, forks, license) or a deployment link (Streamlit Cloud)?
