# 🚀 BackendDeveloperHub FastAPI

**FastAPI** starter project created under **BackendDeveloperHub**.

The goal is to help beginners learn backend development by building real-world APIs.

## 🔧 Tech Stack
- **Language:** Python
- **Framework:** FastAPI
- **Server:** Uvicorn
- **Database:** SQLite (initially)

## 📁 Project Structure
```text
├── app
│   ├── config.py
│   ├── database.py
│   ├── main.py
│   ├── routes
│   │   └── health.py
│   └── schemas
│       └── health.py
├── README.md
└── requirements.txt
```

## ▶️ Running the Project
### 1. Clone the Repository

```bash
# Clone repo
git clone https://github.com/BackendDeveloperHub/backenddeveloperhub-fastapi.git

# Navigate to project folder
cd backenddeveloperhub-fastapi
```

### 2. Create a Virtual Environment

```bash
# Create virtual environment (venv) folder
python3 -m venv venv

# Activate virtual environment
source venv/bin/activate        # Linux / macOS
venv\Scripts\activate           # Windows
```

### 3. Install Dependencies
`pip install -r requirements.txt`

### 4. Start the Server
`uvicorn app.main:app --reload`

The server runs on http://127.0.0.1:8000 by default. Open this in the browser and the server should return a "Hello World" JSON object:

```json
{
  "Hello": "World"
}
```

Task 01 – Run FastAPI project

Task 02 – Understand project structure

Task 03 – Create /health API

Task 04 – Create /ping API

Task 05 – Response models

Task 06 – Query parameters

Task 07 – Path parameters

Task 08 – Error handling

Task 09 – SQLite setup

Task 10 – Create model

Task 11 – Create table

Task 12 – Create POST API

Task 13 – Create GET API

Task 14 – Update API

Task 15 – Delete API

Task 16 – Pagination

Task 17 – Environment variables

Task 18 – Project cleanup

Task 19 – Documentation update

Task 20 – Final review & refactor
