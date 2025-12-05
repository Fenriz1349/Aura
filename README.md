# AuraApp – iOS + Vapor Full-Stack Demo 🚀

[Swift](https://img.shields.io/badge/Swift-FA7343?style=for-the-badge&logo=swift&logoColor=white)
[SwiftUI](https://img.shields.io/badge/SwiftUI-0D96F6?style=for-the-badge&logo=swift&logoColor=white)
[SwiftData](https://img.shields.io/badge/SwiftData-8A2BE2?style=for-the-badge)
[Vapor](https://img.shields.io/badge/Vapor-0C7CFF?style=for-the-badge&logo=vapor&logoColor=white)
[Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
[KotlinMultiplatform-ready](https://img.shields.io/badge/KMP-ready-7F52FF?style=for-the-badge)

AuraApp is a small full-stack project combining a SwiftUI iOS app with a Vapor backend.  
It was developed as part of a training course to practice mobile–backend interaction, JWT authentication and CRUD operations, kept intentionally simple and portfolio-friendly.

---

## 🌟 Features

### 📱 iOS App (SwiftUI + SwiftData)
- SwiftData persistence  
- Simple, clean UI with reactive updates  
- Communication with Vapor backend  
- JWT-based authentication  

### 🖥️ Backend (Vapor)
- REST API (Vapor 4)  
- JWT authentication + protected routes  
- CRUD for tasks/items  
- SQLite + Docker support  

---

## 🏗️ Tech Stack

**Frontend:** SwiftUI • SwiftData • MVVM  
**Backend:** Vapor • Fluent • JWT • Docker  

---

## 🚀 Getting Started

### Backend
Run directly:
cd backend
swift run

Or via Docker:

docker build -t aura-backend .
docker run -p 8080:8080 aura-backend


Server default URL: `http://localhost:8080`

### iOS App
1. Open `Aura.xcodeproj`  
2. Select a simulator  
3. Run with **⌘R**  

Update the API base URL in the project if necessary.

---

## 🔌 API Endpoints (summary)

| Method | Endpoint | Description |
|--------|----------|-------------|
| POST | `/auth/login` | Authenticates user, returns JWT |
| GET | `/tasks` | Fetch all tasks |
| POST | `/tasks` | Create a task |
| PUT | `/tasks/:id` | Update a task |
| DELETE | `/tasks/:id` | Delete a task |

---

## 🎯 Purpose of the Project

Created as part of a training course to practice:  
- full-stack development (iOS + Vapor)  
- REST API design  
- SwiftUI + SwiftData usage  
- JWT-secured communication  
- Docker deployment basics  

A compact portfolio-friendly project without unnecessary complexity.

---

## 📌 Future Improvements
- User registration  
- Better UI/UX  
- Add unit tests (Swift + Vapor)  
- GitHub Actions CI/CD  

---

## 📝 License
MIT – free to use and learn from.
