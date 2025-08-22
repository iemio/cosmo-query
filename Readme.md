# 🔭 Astronomy Picture Search  

A **real-world search application** built using **Elasticsearch**, **FastAPI**, and **Vue.js**, powered by NASA's **Astronomy Picture of the Day (APOD)** dataset.  

This project demonstrates how to implement:  
- 🚀 Data cleaning pipelines  
- ✂️ Tokenization & text preprocessing  
- 📑 Pagination  
- 📊 Aggregations (filters, counts, etc.)  
- 🔍 Full-text search with Elasticsearch  
- ⚡ Modern backend with FastAPI  
- 🎨 Responsive frontend with Vue.js

---

## ⚙️ Tech Stack  
- **Backend:** [FastAPI](https://fastapi.tiangolo.com/)  
- **Search Engine:** [Elasticsearch](https://www.elastic.co/elasticsearch/)  
- **Frontend:** [Vue.js 3](https://vuejs.org/)  
- **Data:** NASA’s [APOD dataset](https://github.com/nasa/apod-api)  
- **Containerization:** Docker & Docker Compose

---

## 🚀 Getting Started  

### 1️⃣ Clone Repository  
```bash
git clone https://github.com/your-username/astronomy-search.git
cd astronomy-search
```
### 2️⃣ Start Elasticsearch with Docker
```bash
docker-compose up -d
```
### g3️⃣ Backend Setup (FastAPI)
```bash
cd backend
uv install
uv run main.py
```
API available at: 👉 http://localhost:8000/docs

### 4️⃣ Frontend Setup (Vue.js)
```bash
cd frontend
npm install
npm run dev
```
Frontend available at: 👉 http://localhost:5173

🔍 Features
✅ Data Cleaning Pipeline – Preprocess APOD dataset (remove duplicates, normalize text, clean missing fields).
✅ Tokenization – Apply analyzers & tokenizers for better search results.
✅ Pagination – Efficient scrolling through large datasets.
✅ Aggregations – Filter by year, media type (image/video), keywords, etc.
✅ Search UI – Autocomplete, filters, and results ranking.
