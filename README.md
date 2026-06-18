# survival-cv2030
survival cv2030
│
├── README.md
│
├── backend
│   ├── main.py
│   ├── requirements.txt
│   └── database.py
│
├── frontend
│   ├── index.html
│   ├── style.css
│   └── app.js
│
└── docs
    └── roadmap.md
# Career2030

AI-Powered Career Survival Platform

## Features

- CV Analysis
- Future Job Prediction
- Career Path Recommendations
- Course Recommendations
- Internal Promotion Suggestions
- AI Career Expert
- Recruiter Portal

## Tech Stack

Frontend:
- React
- Next.js

Backend:
- FastAPI

Database:
- PostgreSQL

AI:
- OpenAI
fastapi
uvicorn
python-multipart
openai
sqlalchemy
psycopg2-binary
from fastapi import FastAPI

app = FastAPI(
    title="Career2030"
)

@app.get("/")
def home():
    return {
        "message": "Career2030 API Running"
    }

@app.get("/health")
def health():
    return {
        "status":"ok"
    }
from sqlalchemy import create_engine

DATABASE_URL = "postgresql://user:password@localhost/career2030"

engine = create_engine(DATABASE_URL)
<!DOCTYPE html>
<html>
<head>
<title>Career2030</title>
<link rel="stylesheet" href="style.css">
</head>

<body>

<h1>Career2030</h1>

<p>
Discover your future career path.
</p>

<button id="uploadBtn">
Upload CV
</button>

<script src="app.js"></script>

</body>
</html>
body{
font-family:Arial;
padding:40px;
}

button{
background:#2563eb;
color:white;
padding:10px 20px;
border:none;
cursor:pointer;
}
document
.getElementById("uploadBtn")
.addEventListener("click",()=>{

alert("Upload CV Coming Soon");

});
# Career2030 Roadmap

Phase 1
- User Registration
- CV Upload
- AI Analysis

Phase 2
- Job Matching
- Courses Recommendation

Phase 3
- AI Career Expert

Phase 4
- Recruiter Portal

Phase 5
- Global Expansion    
