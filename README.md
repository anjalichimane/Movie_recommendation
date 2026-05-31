# Movie Recommender System

## Tech Stack
- FastAPI (Backend)
- Streamlit (Frontend)
- TMDB API
- TF-IDF

## Setup

1. Create virtual environment
2. Install dependencies:
   pip install -r requirements.txt

3. Create .env file:
   TMDB_API_KEY=your_key

4. Run backend:
   uvicorn main:app --reload

5. Run frontend:
   streamlit run app.py