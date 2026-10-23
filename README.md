# Fastapi_learning
Learning and practising fastapi python web framework 
# FastAPI Learning 🚀
## About
This repository documents my step-by-step learning of FastAPI through small, numbered examples. Each folder focuses on a specific backend development concept.
## Learning Topics
1 Path and query parameters, request body, response models.
2 Pydantic models and validation in depth.
3 Routers and project structure (do not keep everything in main.py).
4 Connecting to a database using SQLAlchemy, first SQLite and then PostgreSQL.
5 Database migrations with Alembic.
6 Dependency injection (the Depends system), one of FastAPI's best features.
7 Authentication with password hashing and JWT tokens, then role based authorization.
8 Error handling, status codes, and logging.
9 Background tasks and file uploads.
10 Testing with pytest and FastAPI's TestClient.
11 Environment variables and settings management, never hard coding secrets.
12 Docker, so your app runs the same everywhere, then deployment.
## How to Run
Install FastAPI and Uvicorn:
```bash
pip install fastapi uvicorn
```
Run an example from its folder:
```bash
python -m uvicorn 01_hello_world:app --reload
```
Run this command from the directory containing the example file. If the filename is inside a numbered folder, run the command from that folder and use the module name without `.py`.
Open the interactive documentation at:
http://127.0.0.1:8000/docs
## Projects
Real-world projects are maintained in separate repositories.
## Goal
Build strong backend development skills and prepare for MCA placements.
