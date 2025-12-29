# commerce-platform
commerce-platformはECサイトシステムである。



## 使用する技術

### Frontend：

- Vue 3
- Element Plus
- Vite

### Backend：

- Spring Boot
- Spring Security + JWT
- REST API (JSON)
- Springdoc OpenAPI + Swagger UI

### Infrastructure：

- MariaDB
- Nginx
- Docker / Docker Compose



## プロジェクト構成
commerce-platform/
  - ec-backend/     　 # Spring Boot
  -  ec-frontend/         # Vue 3
  -  ec-nginx/               # Nginx config
  - ec-db/                    # DB init script
  - docker-compose.yml
  - .env.example
  - README.md



## バージョン

- Java:21(LTS)
- Spring Boot 4.0.1
- MariaDB lts-ubi9（LTS）