# HW12 — FastAPI Calculator + User Auth + BREAD Endpoints + CI/CD

This project extends a FastAPI application with:
- User registration + login (JWT authentication)
- CRUD operations for calculations (BREAD endpoints)
- Full integration testing (pytest + Playwright + REST)
- Automated Docker build and push (CI/CD)
- PostgreSQL support via SQLAlchemy ORM

---

## 📁 Project Structure

```plaintext
app/
 ├── auth/
 ├── models/
 ├── routers/
 ├── schemas/
 ├── operations/
 ├── database.py
 ├── config.py
 └── main.py

tests/
 ├── unit/
 ├── integration/
 └── e2e/

Dockerfile
requirements.txt
README.md
```

---


# Running the App

### **Start FastAPI locally**
```bash
uvicorn main:app --reload
```
Visit 
http://127.0.0.1:8000/docs

---

## Running the tests
``` bash
pytest
```



