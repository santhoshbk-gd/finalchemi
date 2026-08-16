# API

| Method | Route | Description |
|---|---|---|
| GET | `/api/health` | Service status |
| POST | `/api/auth/register` | Register `{name,email,password,educationLevel}` |
| POST | `/api/auth/login` | Login `{email,password}` |
| GET | `/api/progress` | Current learner progress (Bearer token) |
| POST | `/api/ai/chat` | Chemi answer (Bearer token) |

Protected routes expect `Authorization: Bearer <token>`. Validation failures are returned as safe 400 responses.
