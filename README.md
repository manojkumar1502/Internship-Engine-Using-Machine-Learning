# 🇮🇳 Internship Engine Using Machine Learning

## 📌 Project Overview

The **Internship Engine Using Machine Learning** is a full-stack web application designed to help students discover suitable internship opportunities under the **Prime Minister's Internship Scheme (Government of India)**.

The system recommends internships based on a student's education background, skills, preferred location, and stipend expectations using a **machine learning–based text similarity approach**.

This project was developed as a **self-built, hackathon-ready solution**, focusing on practical usability, clean architecture, and real-world relevance.

---

## 🎯 Objective

* Help students easily find relevant PM Internship opportunities
* Reduce manual searching and mismatched applications
* Provide intelligent, personalized internship recommendations
* Support the **Digital India** & **Youth Empowerment** initiative

---

## ⚙️ Tech Stack

### Backend

* Python 3.8+
* Flask (REST API)
* Pandas (data processing)
* Scikit-learn (TF-IDF & cosine similarity)
* Flask-CORS

### Frontend

* HTML5
* CSS3 (responsive design)
* JavaScript (ES6)
* Font Awesome icons

### Data & ML

* CSV-based internship dataset
* TF-IDF vectorization
* Cosine similarity for matching

---

## ✨ Key Features

* Education-based internship filtering
* Skill-based intelligent matching
* Location & stipend preference support
* TF-IDF powered recommendation engine
* Match percentage scoring
* Direct links to company career pages
* Responsive and user-friendly UI

---

## 🧠 Recommendation Logic (Simplified)

1. User profile (education + skills) is converted into text
2. Internship descriptions are vectorized using **TF-IDF**
3. **Cosine similarity** is calculated between user profile and internships
4. Internships are ranked based on relevance + filters
5. Top recommendations are returned to the user

---

## 🏢 Supported Domains

* Computer Science / IT
* Mechanical Engineering
* Civil Engineering
* Electronics & Electrical
* Commerce / Finance
* Business & Management
* Marketing & Digital Media
* HR & Psychology
* Design & Creative Fields
* Operations & Logistics

---

## 📁 Project Structure

```
pm-internship-engine/
├── backend/
│   ├── app.py
│   ├── recommendation_engine.py
│   └── requirements.txt
├── frontend/
│   ├── index.html
│   ├── style.css
│   ├── mobile.css
│   └── script.js
├── data/
│   └── internship.csv
└── README.md
```

---

## 🚀 Installation & Setup

### Prerequisites

* Python 3.8 or above
* Web browser

### Steps

1. Clone the repository

```bash
git clone https://github.com/manojkumar1502/Internship-Engine-Using-Machine-Learning.git
cd Internship-Engine-Using-Machine-Learning
```

2. Install backend dependencies

```bash
cd backend
pip install -r requirements.txt
```

3. Start Flask server

```bash
python app.py
```

4. Open frontend

```bash
cd ../frontend
open index.html
```

---

## 🔌 API Endpoints

### Health Check

```
GET /health
```

### Get Internship Recommendations

```
POST /api/recommendations
Content-Type: application/json
```

#### Request Body

```json
{
  "education": "Computer Science",
  "skills": ["Python", "Web Development"],
  "location_preference": "Bangalore",
  "min_stipend": 20000
}
```

---

## 🚧 Future Enhancements

* User login & profiles
* Save/bookmark internships
* Application tracking
* Advanced filters (duration, start date)
* Email notifications
* Mobile app version

---

## 👨‍💻 Developer

**Manoj Kumar Patil**
Engineering Student
Interested in **Full-Stack Development** & **Applied Machine Learning**
Focused on building **practical solutions for students**
