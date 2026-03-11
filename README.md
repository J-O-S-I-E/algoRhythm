# AlgoRhythm Agent API

A content creator agent built with LangGraph and served via FastAPI.

## Running locally

1. Install dependencies: `pip install -r requirements.txt`
2. Add your API keys to a `.env` file in the project root
3. Start the server: `uvicorn app.main:app --reload --port 8000`

## Endpoints

- `GET /health` — confirms the server is running
- `POST /chat` — sends a message to the agent and returns a response
- `GET /ui` — chat interface
- `GET /docs` — interactive API documentation
