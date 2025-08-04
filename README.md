# 🌍 Travel Planner Agent

An AI-powered travel planning assistant that generates personalized itineraries based on user preferences such as location, duration, and interests. Built as part of the **IBM SkillsBuild Internship (Edunet Foundation)** in the **AI and Cloud domain**.

---

## 📌 Overview

This project aims to simplify travel planning by using AI to create customized trip itineraries. Users can input a location and number of days, and the system will return a well-structured travel plan, leveraging AI generation and optional document retrieval via RAG (Retrieval-Augmented Generation).

---

## ⚙️ Features

- 🔍 AI-generated travel plans based on location
- 🧠 Backend logic built in Python
- 💬 IBM Watsonx Granite Model integration (optional)
- 📄 RAG-based support for document-aware responses
- 🌐 User-friendly interface built with Streamlit
- ☁️ IBM Cloud services for deployment and model simulation

---

## 💡 Technologies Used

### 🔧 Programming & Tools
- Python
- Jupyter Notebook

### 🤖 AI & NLP
- IBM Watsonx.ai
- IBM Granite 13B Chat Model *(simulated due to region limitations)*
- Retrieval-Augmented Generation (RAG)

### ☁️ IBM Cloud Services
- IBM Watsonx.ai
- IBM Cloud Object Storage *(for optional document support)*
- IBM Prompt Lab *(Region-restricted: simulated locally)*

---

## 🛠️ Installation

### Prerequisites:
- Python 3.8+
- `pip` installed


---

## ▶️ Usage

1. Open the app in browser (usually at `http://localhost:8501`)
2. Enter a destination (e.g., "Goa")
3. Specify number of days
4. Click on **Plan My Trip**
5. Get a customized travel plan

---

## 📽️ Demo

> Watch the full demo: [Link to demo video]  
> Screenshot of UI:  
> ![UI Screenshot](screenshots/ui.png)

---

## 📂 Project Structure

```bash
travel-planner-agent/
│
├── backend/
│   └── travel_logic.ipynb           # IBM Watsonx Notebook with logic
│
├── frontend/
│   └── app.py                       # Streamlit app UI
│
├── data/
│   └── RAG_documents/               # Docs for RAG (optional)
│
├── requirements.txt
└── README.md
```

---

## 🙋‍♀️ End Users

- Casual travelers
- Students planning academic or leisure trips
- Solo backpackers & travel bloggers
- Travel startup prototypes

---

## ✨ Wow Factors

- 🔗 Integration of AI & RAG for real-world travel planning
- 🌐 Streamlit UI that runs in browser with zero setup
- ☁️ Uses IBM Cloud + Watsonx ecosystem
- 💡 Simulates AI even when Prompt Lab access is restricted
- 🧩 Modular design – easy to scale or upgrade

---

## 👩‍💻 Developed By

**Sanjana Reddy**  
AI & Cloud Intern @ IBM SkillsBuild (Edunet Foundation)  
📍 India  
 [LinkedIn](https://www.linkedin.com/in/sanjana-reddy-golla-540752310?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app)

---

## 📝 License

This project is licensed under the [MIT License](LICENSE).

---

## 🙏 Acknowledgements

- IBM SkillsBuild & Edunet Foundation
- IBM Watsonx Documentation
- Streamlit Community
- Mentors and team members
