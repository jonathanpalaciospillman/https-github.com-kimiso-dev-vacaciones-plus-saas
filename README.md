# https-github.com-kimiso-dev-vacaciones-plus-saas
cp backend/.env.example backend/.env
cp frontend/.env.example frontend/.env
docker compose up --build
| Servicio           | URL                                                                |
| ------------------ | ------------------------------------------------------------------ |
| **Frontend (Web)** | <http://localhost:3000>                                            |
| **Backend API**    | <http://localhost:8000/docs>                                       |
| **PostgreSQL**     | `localhost:5432` (usuario: `vacaciones`, contraseña: `vacaciones`) |
