# EV Charging Station Monitor

An academic full-stack application for discovering and monitoring electric-vehicle charging stations.

The backend aggregates station data from TomTom and OpenChargeMap, stores operational data in MongoDB, and supports background processing with Celery and Redis. A React and Leaflet frontend provides the user interface.

## Technology stack

- FastAPI and Pydantic
- MongoDB with Motor
- Celery and Redis
- TomTom and OpenChargeMap APIs
- React and Leaflet

## Local setup

1. Copy `backend/.env.example` to `backend/.env`.
2. Add your own API keys and application secret.
3. Start MongoDB and Redis.
4. Install `backend/requirements.txt`.
5. Run the API with `uvicorn app.main:app --reload`.
6. Run the React frontend with `npm start`.

Never commit `backend/.env` or real API credentials.

