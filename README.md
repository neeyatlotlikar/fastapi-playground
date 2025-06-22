# fastapi-playground

Simple backend API I created while following the docs and learning about FastAPI.

## Setup

1. Create a Python Virtual Environment (Recommended)
2. Run: `pip install -r requirements.txt`
3. Run: `uvicorn app.main:app --host 0.0.0.0 --port 8000`
4. API: <http://localhost:8000/docs>

## Features

- REST API
- FastAPI Swagger Docs
- Uses a mocked "database" which is really just python dicts
- CRUD operations mocked (in-memory)

## Tech Stack

- Python, FastAPI
