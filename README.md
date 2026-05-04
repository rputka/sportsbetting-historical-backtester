## Backend

```bash
cd backend
python -m venv .venv
source .venv/bin/activate   # Windows: .venv\Scripts\activate
pip install -r requirements.txt
uvicorn main:app --reload --port 8000
```

## Frontend

```bash
cd frontend
npm install
npm run dev
```

Start the backend first. The UI is at [http://localhost:5173](http://localhost:5173); `/api` is proxied to the backend on port 8000.
