# FitBuddy: AI Fitness Plan Generator

Generates personalized 3-day workout plans and nutrition tips using Gemini.

## Features
- Real-time streaming workout plans
- Nutrition tips based on your goal
- Feedback loop to update plans
- SQLite storage
- Admin dashboard at /view-all-users

## Tech Stack
- FastAPI + SQLite + SQLAlchemy
- Google Gemini
- HTML/CSS/Jinja2

## How to Run
1. `python -m venv venv`
2. `venv\Scripts\activate`
3. `python -m pip install -r requirements.txt`
4. Create `.env` with `GOOGLE_API_KEY=AIzaSy...`
5. `python -m uvicorn app.main:app --reload`
6. Open http://127.0.0.1:8000