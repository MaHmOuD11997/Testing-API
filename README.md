# 🧪  REST API Testing (Postman + JSONPlaceholder)

## 🔧 Tools
- Postman
- Newman CLI
- HTMLExtra Reporter
- JSON Schema Validation

## ✅ Covered Scenarios
- `GET /posts`
- `GET /posts/1` with Schema check
- `POST /posts` (create + chaining)
- `PUT /posts/:id`
- `DELETE /posts/:id`
- Negative test (POST without title)

## ▶️ How to Run with Newman

1. Install dependencies:
```bash
npm install -g newman newman-reporter-htmlextra
