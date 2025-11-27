## Running Integration Tests (pytest)

This project includes full integration tests for:
- User registration + login
- CRUD operations for calculations (BREAD endpoints)
- Full FastAPI server startup (using Playwright and REST)

###  Run all tests:
```bash
pytest -v

### Run only integration tests:
```bash
pytest tests/integration -v
