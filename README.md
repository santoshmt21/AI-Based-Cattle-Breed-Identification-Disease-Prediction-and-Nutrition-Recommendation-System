# 🐄 AI-Based Cattle Breed Identification and Nutrition Recommendation System

An AI-powered web application that helps farmers, veterinarians, and livestock managers identify cattle breeds and receive personalized nutrition recommendations using Deep Learning, Computer Vision, and Retrieval-Augmented Generation (RAG).

> **Note:** 🚧 Disease Prediction is currently under development and will be added in a future update.

---

# 📌 Project Overview

This project combines Artificial Intelligence and Computer Vision to support cattle management through:

- 🐂 **Cattle Breed Identification**
- 🥗 **Nutrition Recommendation**
- 🤖 **AI Chatbot (RAG)**
- 🩺 **Disease Prediction (In Progress)**

---

# ✨ Features

## ✅ Cattle Breed Identification

- Upload cattle images
- Predict cattle breed using a Vision Transformer (ViT)
- Display prediction confidence

## ✅ Nutrition Recommendation

- Personalized nutrition recommendations based on:
  - Predicted breed
  - Age
  - Weight
  - Health condition
- Balanced feeding suggestions

## ✅ AI Chatbot (RAG)

- Answers cattle-related questions
- Retrieves information from veterinary documents
- Powered by Retrieval-Augmented Generation (RAG)

## 🚧 Disease Prediction *(Under Development)*

- Disease detection from cattle images
- Planned integration using YOLO
- Detection of infected regions
- Confidence score for disease predictions

---

# 🛠 Tech Stack

## Frontend

- React.js
- HTML
- CSS
- JavaScript
- Axios

## Backend

- FastAPI
- Python

## AI & Machine Learning

- PyTorch
- Vision Transformer (ViT)
- OpenCV
- NumPy
- Pandas
- Scikit-learn

## RAG

- LangChain
- ChromaDB
- HuggingFace Embeddings
- Groq LLM

---

# 📂 Project Structure

```text
PROJECT_PHASE_21
│
├── BACKEND
│   ├── app.py
│   ├── rag.py
│   ├── MODELS
│   ├── Artifacts
│   └── requirements.txt
│
├── FRONTEND
│   ├── src
│   ├── public
│   └── package.json
│
├── README.md
└── .gitignore
```

---

# ⚙️ Installation

## Clone Repository

```bash
git clone https://github.com/santoshmt21/AI-Based-Cattle-Breed-Identification-Disease-Prediction-and-Nutrition-Recommendation-System.git

cd AI-Based-Cattle-Breed-Identification-Disease-Prediction-and-Nutrition-Recommendation-System
```

## Backend Setup

```bash
python -m venv .venv

.venv\Scripts\activate

pip install -r BACKEND/requirements.txt

cd BACKEND

uvicorn app:app --reload
```

Backend:

```
http://127.0.0.1:8000
```

## Frontend Setup

```bash
cd FRONTEND

npm install

npm run dev
```

Frontend:

```
http://localhost:5173
```

---

# 🚀 Workflow

1. Upload a cattle image.
2. AI predicts the cattle breed.
3. Receive nutrition recommendations based on the prediction.
4. Ask cattle-related questions using the AI chatbot.
5. *(Upcoming)* Disease prediction from cattle images.

---

# 🧠 Models Used

| Module | Model |
|---------|-------|
| Breed Identification | Vision Transformer (ViT) |
| Nutrition Recommendation | Rule-Based Recommendation System |
| AI Chatbot | RAG + LangChain + Groq |
| Disease Prediction *(Upcoming)* | YOLO |

---

# 📸 Screenshots

Add screenshots of:

- Home Page
- Breed Identification
- Nutrition Recommendation
- AI Chatbot

---

# 🚀 Future Enhancements

- ✅ Disease Prediction using YOLO
- Mobile Application
- Live Camera Detection
- Vaccination Reminder System
- Multi-language Support
- Cloud Deployment
- Farmer Dashboard

---

# 👨‍💻 Author

**Santosh Talekattu**

Computer Science Engineering Student

---

# 📜 License

This project is developed for educational and research purposes.

---

# ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub!
